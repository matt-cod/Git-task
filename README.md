# Version Control

## What is Version Control?
Version control is a system that records changes to files over time, enabling collaboration, tracking, and management of code or documents. It allows developers to:
- Track history of changes.
- Collaborate effectively.
- Revert to previous versions.

---

## Git vs GitHub

| **Aspect**       | **Git**                                               | **GitHub**                                           |
|-------------------|-------------------------------------------------------|-----------------------------------------------------|
| **Definition**    | A distributed version control system to track changes.| A platform for hosting and managing Git repositories.|
| **Purpose**       | Tracks changes locally and across systems.            | Provides cloud storage and collaboration tools.     |
| **Usage**         | Command-line interface.                               | Web-based GUI and integrations with Git.           |

---

## GitHub Alternatives
1. GitLab
2. Bitbucket
3. SourceForge

---

## Git Fetch vs Git Pull

| **Command**   | **Description**                                                                 |
|---------------|---------------------------------------------------------------------------------|
| **git fetch** | Downloads data from the remote repository but does not integrate it.           |
| **git pull**  | Fetches the latest changes and directly merges them into your current branch.  |

---

## Git Rebase

Rebasing takes the changes from one branch and re-applies them on another. It ensures a linear commit history.

### Command

```
git rebase <base-branch>
```

---
## Git Cherry-pick

Cherry-pick allows you to select specific commits from one branch and apply them to another.

### Command

```
git cherry-pick <commit-hash>
```
