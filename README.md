```markdown
# 🚀 Useful Git Commands

This guide lists essential Git commands with a brief description for each. These commands will help you manage your workflow effectively and maintain clean project history.

---

## 🔄 **1. git init**

```bash
git init
```

- **Description**: Initializes a new Git repository in the current directory. This is the first step to start tracking a project with Git.

---

## 🔍 **2. git status**

```bash
git status
```

- **Description**: Displays the state of the working directory and the staging area. It shows changes that are staged, unstaged, and untracked files.

---

## ➕ **3. git add**

```bash
git add <file>
git add .
```

- **Description**: Adds changes to the staging area. Use `git add .` to add all changes in the directory, or specify a file to add changes from a specific file.

---

## 📦 **4. git commit**

```bash
git commit -m "commit message"
git commit --amend
```

- **Description**: Creates a snapshot of the staged changes. Use `-m` to add a message. The `--amend` option allows you to modify the previous commit.

---

## 🚀 **5. git push**

```bash
git push origin <branch>
```

- **Description**: Pushes committed changes to the remote repository. Replace `<branch>` with the branch you are working on (e.g., `main`, `dev`).

---

## ⬇️ **6. git pull**

```bash
git pull origin <branch>
```

- **Description**: Fetches and integrates changes from the remote repository into your current branch. This keeps your local branch up-to-date with remote changes.

---

## 📝 **7. git branch**

```bash
git branch
git branch <new-branch>
```

- **Description**: Lists all branches in the repository. Use `git branch <new-branch>` to create a new branch.

---

## ✨ **8. git checkout**

```bash
git checkout <branch>
git checkout -b <new-branch>
```

- **Description**: Switches to another branch or commit. Use `-b` to create and switch to a new branch.

---

## 🛠️ **9. git merge**

```bash
git merge <branch>
```

- **Description**: Merges changes from the specified branch into the current branch. Commonly used when integrating feature branches into `main` or `dev`.

---

## 🧹 **10. git rebase**

```bash
git rebase <branch>
git rebase -i HEAD~3
```

- **Description**: Moves or combines a sequence of commits to a new base commit. Use the `-i` (interactive) option to edit commit history, squash, or reorder commits.

---

## ✂️ **11. git reset**

```bash
git reset <file>
git reset --hard <commit>
```

- **Description**: Unstages or removes changes from the working directory. Use `--hard` to reset the entire history and working directory to a specific commit.

---

## 🔍 **12. git log**

```bash
git log
git log --oneline --graph
```

- **Description**: Shows a detailed log of commit history. The `--oneline --graph` option provides a more condensed and visual representation of the history.

---

## ⬇️ **13. git fetch**

```bash
git fetch origin
```

- **Description**: Retrieves changes from the remote repository without merging them into the current branch. Useful for seeing what others have pushed before you integrate it locally.

---

## ❌ **14. git stash**

```bash
git stash
git stash apply
```

- **Description**: Temporarily saves changes that are not ready to be committed. Use `git stash apply` to retrieve the stashed changes.

---

## 🧽 **15. git clean**

```bash
git clean -fd
```

- **Description**: Removes untracked files and directories from the working directory. Useful when you want to clean up your project directory.

---

## 🏗️ **16. git remote**

```bash
git remote -v
git remote add origin <url>
```

- **Description**: Lists or adds remote repositories. Use `git remote add` to link your local repository to a remote one (e.g., GitHub).

---

## 🔐 **17. git clone**

```bash
git clone <url>
```

- **Description**: Clones a repository from a remote server to your local machine. This command creates a full copy of the project including its history.

---

## 📋 **18. git diff**

```bash
git diff
```

- **Description**: Shows the changes between your working directory and the last commit. This is useful for reviewing code before committing.

---

## 🚨 **19. git push --force**

```bash
git push origin <branch> --force
```

- **Description**: Forcefully pushes changes to the remote repository, overwriting the history on the remote. Use this with caution, especially when working with a team, as it can overwrite others' changes.

---

## 🎉 **20. git tag**

```bash
git tag <version>
git push origin <version>
```

- **Description**: Creates a tag to mark a specific point in your project’s history (e.g., release versions). Use `git push origin <version>` to push the tag to the remote repository.

---

## 🧠 **21. git cherry-pick**

```bash
git cherry-pick <commit>
```

- **Description**: Applies changes from a specific commit into your current branch. This is useful for selectively integrating changes.

---

## 🧹 **22. git reflog**

```bash
git reflog
```

- **Description**: Shows a history of all Git commands executed in your repository. This can be very useful for recovering from mistakes, especially after resets or rebases.

---

### 🔑 Key Git Concepts:

- **Rebase**: Reapplies commits on top of another base commit, keeping the commit history linear.
- **Merge**: Combines changes from multiple branches without altering the commit history.
- **Force-push**: Pushes changes while overriding the history on the remote repository.
