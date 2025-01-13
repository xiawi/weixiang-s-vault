---
tags:
  - note
up: "[[Git]]"
date: 2025-01-11
---
Files in Git can either be staged, commited, or modified. Using a command like `git status` shows us everything that is being tracked and untracked. When initializing a repository, every file is untracked. To track a file, we must first [[Git staging environments|stage it]].

We can also do `git status --short` to have a more compact view of changes.

> [!info]
> **Note:** Short status flags are:
> - ?? - Untracked files
> - A - Files added to stage
> - M - Modified Files
> - D - Deleted Files

- **Modified** means that you have changed the file but have not committed it yet.
- **Staged** means that you have marked a modified file in its current version to go into your next commit.
- **Committed** means that the data is safely stored locally.