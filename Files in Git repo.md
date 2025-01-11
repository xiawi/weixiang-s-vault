---
tags:
  - note
up: "[[Git]]"
date: 2025-01-11
---
Files in Git can either be tracked or untracked. Using a command like `git status` shows us everything that is being tracked and untracked. When initializing a repository, every file is untracked. To track a file, we must first [[Git staging environments|stage it]].

We can also do `git status --short` to have a more compact view of changes.

> [!info]
> **Note:** Short status flags are:
> - ?? - Untracked files
> - A - Files added to stage
> - M - Modified Files
> - D - Deleted Files

