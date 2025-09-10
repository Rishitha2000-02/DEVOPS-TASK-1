**VERSION CONTROL WITH GIT**

Company name :--Code Tech IT solution

Name:--Rishitha Blaji

Domain:-- Devops


# DevOps Internship Task - Git Conflict Resolution

## Overview

This repository demonstrates Git branching, merging, and conflict resolution as part of my internship task.

## Branches

- **master**: main branch.
- **feature-branch**: additional changes made for demonstration.

## Merge conflict

When I tried to merge `feature-branch` into `master`, there was a conflict in `file.txt` because both branches modified the same line.

### Conflict markers in file.txt

<<<<<<< HEAD
Changes from master branch.
Changes from feature-branch.


## How I resolved it

1. Opened `file.txt`.
2. Chose to keep both changes and manually edited the file to:
3. 3. Removed conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
4. Added and committed the resolved file.

## Commands used
git checkout master
git merge feature-branch

Conflict appeared Edited file.txt manually:---

git add file.txt
git commit -m "Resolved merge conflict between master and feature-branch"

## Conclusion

Successfully merged branches and resolved conflict. Clear commit history can be viewed in the repository.

