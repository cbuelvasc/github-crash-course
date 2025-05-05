# Key Git Commands

This project uses Git for version control. Below are some essential Git commands and their descriptions to help you manage your codebase efficiently.

| Command                           | Description                                                         |
|-----------------------------------|---------------------------------------------------------------------|
| `git init`                        | Initialize a Git repository (only required once per project)        |
| `git add <file(s)>`               | Stage code changes (for the next commit)                            |
| `git commit -m "..."`             | Create a commit for the staged changes (with a message)             |
| `git status`                      | Get the current repository status (e.g., which changes are staged)  |
| `git log`                         | Output a chronologically ordered list of commits                    |
| `git checkout <id>`               | Temporarily move back to commit `<id>`                              |
| `git revert <id>`                 | Revert the changes of commit `<id>` (by creating a new commit)      |
| `git reset <id>`                  | Undo commit(s) up to commit `<id>` by deleting commits              |
| `git branch`                      | List all local branches                                             |
| `git branch <name>`               | Create a new branch                                                 |
| `git checkout -b <name>`          | Create a new branch and switch to it                                |
| `git checkout <name>`             | Switch to an existing branch                                        |
| `git branch -d <name>`            | Delete a branch (safe - won't delete if it has unmerged changes)    |
| `git branch -D <name>`            | Force delete a branch (will delete even with unmerged changes)      |
| `git merge <branch>`              | Merge a branch into the current branch                              |
| `git branch -m <old-name> <new-name>` | Rename a branch                                                 |
| `git push origin --delete <name>` | Delete a remote branch                                              |
---

Feel free to use these commands as a quick reference while working on this project. 