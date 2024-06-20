



# 🖥️ Curso Git Udemy

Welcome to the Git Essentials Guide! This document is a comprehensive resource for understanding and mastering Git seen in the course, the most popular version control system. 

## Table of Contents
1. [Introduction](#introduction)
2. [Key Concepts](#key-concepts)
    - [Repository](#repository)
    - [Branch](#branch)
    - [Commit](#commit)
    - [Merge](#merge)
    - [Clone](#clone)
3. [Basic Commands](#basic-commands)
    - [Initialize Repository](#initialize-repository)
    - [Clone Repository](#clone-repository)
    - [Check Status](#check-status)
    - [Add Files](#add-files)
    - [Commit Changes](#commit-changes)
    - [Push Changes](#push-changes)
    - [Pull Changes](#pull-changes)
    - [Branching](#branching)
    - [Merging](#merging)
4. [Advanced Commands](#advanced-commands)
    - [Stashing](#stashing)
    - [Rebasing](#rebasing)
    - [Cherry-pick](#cherry-pick)
5. [Useful Tips](#useful-tips)
6. [Resources](#resources)

---

## Introduction
Git is a distributed version control system created by Linus Torvalds. It allows multiple developers to work on a project simultaneously without overwriting each other's changes.

---

## Key Concepts

### Repository
A repository is a directory that contains all of your project's files and the entire revision history.

### Branch
Branches are used to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

![Branching](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png)

### Commit
A commit is a snapshot of your repository at a specific point in time. It contains metadata, including the author, date, and commit message.

### Merge
Merging combines changes from different branches into a single branch.

![Merging](https://media.geeksforgeeks.org/wp-content/uploads/20230516192737/git-three-way-merging.png)

### Clone
Cloning a repository means creating a copy of it on your local machine.

---

## Basic Commands

### Initialize Repository
```bash
git init
```
Creates a new Git repository.

### Clone Repository
```bash
git clone <repository-url>
```
Clones a repository into a new directory.

### Check Status
```bash
git status
```
Displays the state of the working directory and the staging area.

### Add Files
```bash
git add <file-name>
```
Adds a file to the staging area.

### Commit Changes
```bash
git commit -m "Commit message"
```
Records changes to the repository.

### Push Changes
```bash
git push origin <branch-name>
```
Uploads local repository content to a remote repository.

### Pull Changes
```bash
git pull origin <branch-name>
```
Fetches and integrates changes from a remote repository to the local repository.

### Branching
```bash
git branch <new-branch-name>
git checkout <new-branch-name>
```
Creates a new branch and switches to it.

### Merging
```bash
git checkout <branch-to-merge-into>
git merge <branch-to-merge>
```
Merges the specified branch into the current branch.

---

## Advanced Commands

### Stashing
```bash
git stash
git stash apply
```
Temporarily shelves changes made to the working directory.

### Rebasing
```bash
git rebase <branch-name>
```
Reapplies commits on top of another base tip.

### Cherry-pick
```bash
git cherry-pick <commit-hash>
```
Applies the changes introduced by some existing commits.

---

## Useful Tips
- **Undo Last Commit**: `git commit --amend`
- **List Branches**: `git branch -a`
- **Show Commit History**: `git log`

---

## Resources
- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---





