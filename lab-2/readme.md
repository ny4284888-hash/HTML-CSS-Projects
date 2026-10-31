# Lab 2 – Pushing and Cloning a Repository

## Aim
To understand how to push commits to a remote Git repository and clone an existing repository.

## Theory

Git is a distributed version control system used to track changes in source code and manage projects.

A **Remote Repository** is a repository hosted at another location, such as GitHub or another computer. It allows developers to share and collaborate on projects.

A **Bare Repository** is a Git repository that stores version control information without a working directory. It is commonly used as a remote repository for pushing and sharing code.

**Pushing** is the process of uploading local commits to a remote repository.

**Cloning** means creating a local copy of an existing remote repository. It copies the project files and commit history.

## Important Git Commands

| Command | Purpose |
|---|---|
| `git init --bare ../html-remote` | Creates a bare repository |
| `git remote add origin ../html-remote` | Connects a remote repository |
| `git remote -v` | Displays remote connections |
| `git push origin master` | Pushes commits to the remote master branch |
| `git clone ../html-remote html-copy` | Creates a local copy |
| `git log --oneline` | Displays commit history |

## Procedure

1. Created a bare Git repository named `html-remote`.
2. Connected the local repository to the bare repository.
3. Checked the remote