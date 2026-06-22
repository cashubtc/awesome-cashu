---
name: awesome-cashu-add-project
description: Use when maintaining the awesome-cashu repository and the user wants to add new project entries from new-projects.json to README.md, then commit, push, and open a PR. Triggers on "add new project", "awesome list update", "awesome-cashu update", "process new-projects.json", or similar requests.
---

# Add new project(s) to awesome-cashu

Codifies the routine of pulling entries from `new-projects.json`, slotting
them into the right existing category in `README.md`, and shipping the
result as a PR.

## Pre-flight

1. **Check the input file exists.** If `new-projects.json` is missing, stop
   and ask the user where it is (or whether the project list lives inline in
   the message). Do not invent entries.
2. **Read both files end-to-end** before touching anything: `new-projects.json`
   for the new entries, `README.md` for the existing categories and current
   alphabetical ordering.
3. **Identify the default base branch** with
   `git symbolic-ref refs/remotes/origin/HEAD` and confirm `git status` is
   clean before starting.

## Per-project insertion

For each project in `new-projects.json`:

1. **Find the correct existing category.** Walk the `## ...` and `### ...`
   headings in `README.md`. Map project → category by what the project *is*,
   not just by name. Default to `Projects → Various nutcases` only when no
   tighter category fits.
2. **If no existing category fits, ask the user.** Do not silently create a
   new section. List the candidates you'd consider (e.g. "Marketplace",
   "Various nutcases") and let the user pick.
3. **Check for duplicates** in the chosen category by both name
   (case-insensitive) and URL. The Agicash *wallet* and Agicash *Giftcards*
   are distinct products — name match alone is not enough.
4. **Insert at the correct alphabetical position.** Compare full strings;
   remember `A` < `a` < `B` etc. Do not re-sort entries that were already
   out of order in the file.
5. **Preserve the file's formatting exactly:**
   `- [Name](url) is/are <one-sentence description>.`
   - One blank line above `##` / `###` headings, none between bullet items.
   - Trailing spaces and the existing line endings stay as they are.
6. **If a project genuinely doesn't fit anywhere** (and the user confirms a
   new category), create the `###` heading under the appropriate `##`
   parent, in the same style as siblings. Otherwise: skip and report.

## Branch, commit, push

1. **Branch name:** `add-<project-name>` (kebab-case). With multiple
   projects, default to a single branch covering all of them
   (`add-<project1>-<project2>`); ask the user only if they'd rather split
   into one branch per project.
2. **Stage and commit:**
   - `git switch -c <branch>`
   - `git add README.md`
   - `git commit -m "Add <Project1> and <Project2> to <Category>"`
3. **Push:** `git push -u origin <branch>`. SSH-keyed pushes work even when
   `gh` auth is broken — fall back to git push, do not block on gh.

## Open the PR

1. Run `gh pr create --base <default-branch> --head <branch>` with a body
   that names each project, its category, and the line it was inserted on
   (use `git diff` to confirm before writing the body).
2. **If `gh` returns 401 / bad credentials:** do not retry. Report clearly,
   print the manual URL
   (`https://github.com/cashubtc/awesome-cashu/pull/new/<branch>`), and stop.

## Iteration after the commit

If the user changes a description *before* the PR is opened, edit the file
and amend:

```
git add README.md
git commit --amend --no-edit
git push --force-with-lease origin <branch>
```

Preserve user-supplied wording exactly, including oddities like double
spaces — surface the oddity once and let them confirm rather than silently
"fixing" it.

## Return

Always end with the PR URL (or the manual-open URL if `gh` failed) and a
one-line summary of which categories were touched.
