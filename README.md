# Git Guidelines

## Initialize Repository:
- `git init`

## Clone Repository:
- `git clone <repository-url>`

## Create & Switch Branch:
- `git checkout -b <branch-name>`
- `git checkout -b <branch-name>`
- `git checkout -b <branch-name>`
- `git checkout -b <branch-name>`

## Switch Branch:
- `git checkout <branch-name>`

## Stage Changes:
- `git add <file(s)>`

## Commit Changes:
- `git commit -m "Your message"`

## Merge Branches:
- `git checkout <target-branch>`
- `git merge <source-branch>`

## Pull Changes from Remote:
- `git pull origin <branch-name>`

## Push Changes to Remote:
- `git push origin <branch-name>`

## Check Repository Status:
- `git status`

## View Commit History:
- `git log`

## Discard Uncommitted Changes:
- `git checkout -- <file(s)>`

## Undo Last Commit:
- `git reset HEAD^`

## Amend the Last Commit:
- `git commit --amend`

## View Remote Repositories:
- `git remote -v`

## Add Remote Repository:
- `git remote add <remote-name> <remote-url>`

## Remove Remote Repository:
- `git remote rm <remote-name>`

## Fetch Changes from Remote:
- `git fetch <remote-name>`

## Create Tag:
- `git tag <tag-name>`

## Push Tags to Remote:
- `git push --tags`

## Resolve Merge Conflicts:
- Manually edit conflicting files and then `git add` and `git commit`

## Git Ignore:
- Create a `.gitignore` file to specify files or directories to be ignored.

## Branch Rebase:
- `git rebase <base-branch>` to rebase the current branch onto the specified base branch.

## Interactive Rebase:
- `git rebase -i <base-branch>` for an interactive rebase, allowing you to modify commit history.

## Git Bisect:
- `git bisect start`, `git bisect good`, `git bisect bad` to find the commit that introduced a bug.

## Git Archive:
- `git archive --format=zip --output=<output-filename>.zip <branch-name>` to create a zip archive of a specific branch.

## Submodules:
- `git submodule add <repository-url> <path>` to add a submodule.

## Folder and File Naming Conventions:

- **Folders:**
  - Use lowercase letters.
  - Separate words with hyphens or underscores.

- **Files:**
  - Use lowercase letters.
  - Descriptive names, indicating the file's purpose.

## Subfolder Naming Conventions:

- Follow the same conventions as for folders.

Remember to customize these guidelines based on your project's specific needs and workflows.
