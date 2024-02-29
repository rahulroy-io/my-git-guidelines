# My Git Guidelines
Git Guidelines that I prefer to follow.

## Initialization and Cloning:
1. **Initialize Repository:**
   - `git init` - Initializes a new Git repository.

2. **Clone Repository:**
   - `git clone <repository-url>` - Clones a repository from the specified URL.

## Branching:
3. **Create & Switch Branch:**
   - `git branch <branch-name>` - Creates a new branch.
   - `git checkout <branch-name>` - Switches to the specified branch.
   - `git branch -d <branch-name>` - Deletes the specified branch.
   - `git branch -m <new-branch-name>` - Renames the current branch.

   Renaming a branch is easy! Just use `git branch -m <new-branch-name>` to give your branch a new name.

4. **Switch Branch:**
   - `git checkout <branch-name>` - Switches to the specified branch.

## Staging and Committing:
5. **Stage Changes:**
   - `git add <file(s)>` - Adds specific files to the staging area.
   - `git add .` - Adds all changes in the working directory to the staging area.
   - `git add -A` - (Alternative for adding all changes)

6. **Commit Changes:**
   - `git commit -m "Your message"` - Commits the staged changes with a descriptive message. Remember, friendly commit messages make collaboration more enjoyable!

## Merging and Remote Operations:
7. **Merge Branches:**
   - `git checkout <target-branch>` - Switches to the target branch.
   - `git merge <source-branch>` - Merges changes from the source branch into the target branch.

8. **Pull Changes from Remote:**
   - `git pull origin <branch-name>` - Fetches changes from the remote repository and merges them into the current branch.

9. **Push Changes to Remote:**
   - `git push origin <branch-name>` - Pushes local changes to the remote repository.

## Repository Status and History:
10. **Check Repository Status:**
    - `git status` - Displays the status of the working directory.

11. **View Commit History:**
    - `git log` - Shows the commit history.

12. **Pull Changes from Local Branch:**
    - `git pull origin <local-branch-name>` - Pulls changes from a local branch.

13. **Get into a Specific Commit:**
    - `git checkout <commit-hash>` - Checks out a specific commit.
    - `git switch <commit-hash>` - (for Git version 2.23 and later)

14. **List Commands:**
    - `git help` - Displays general help information.
    - `git --help` - Shows a list of common Git commands.
    - `git <command> --help` - Provides help for a specific command.

## Reverting and Amending:
15. **Discard Uncommitted Changes:**
    - `git checkout -- <file(s)>` - Discards changes in the working directory.

16. **Undo Last Commit:**
    - `git reset HEAD^` - Undoes the last commit.

17. **Amend the Last Commit:**
    - `git commit --amend` - Modifies the last commit.

## Remote Management:
18. **View Remote Repositories:**
    - `git remote -v` - Lists remote repositories and their URLs.

19. **Add Remote Repository:**
    - `git remote add <remote-name> <remote-url>` - Adds a remote repository.

20. **Remove Remote Repository:**
    - `git remote rm <remote-name>` - Removes a remote repository.

21. **Fetch Changes from Remote:**
    - `git fetch <remote-name>` - Fetches changes from a remote repository.

## Tags and Special Operations:
22. **Create Tag:**
    - `git tag <tag-name>` - Creates a tag for the current commit.

23. **Push Tags to Remote:**
    - `git push --tags` - Pushes tags to the remote repository.

24. **Resolve Merge Conflicts:**
    - Manually edit conflicting files and then `git add` and `git commit` - Resolves conflicts during a merge.

25. **Ignore and Rebase:**
    - Create a `.gitignore` file.
    - `git rebase <base-branch>` - Rebases the current branch onto the specified base branch.
    - `git rebase -i <base-branch>` - Interactive rebase, allowing modification of commit history.

26. **Bisect and Archive:**
    - `git bisect start`, `git bisect good`, `git bisect bad` - Helps find the commit that introduced a bug.
    - `git archive --format=zip --output=<output-filename>.zip <branch-name>` - Creates a zip archive of a specific branch.

27. **Submodules:**
    - `git submodule add <repository-url> <path>` - Adds a submodule.

## Naming Conventions:
28. **Folder and File Naming Conventions:**
    - **Folders:**
      - Use lowercase letters.
      - Separate words with hyphens or underscores.
    - **Files:**
      - Use lowercase letters.
      - Descriptive names, indicating the file's purpose.

29. **Subfolder Naming Conventions:**
    - Follow the same conventions as for folders.

Remember to customize these guidelines based on your project's specific needs and workflows.
