---
tags:
  - note
up: "[[Pro Git]]"
date: 2025-01-15
---
lists commits logged in the repository.

- `git log -p` shows the difference introduced in each commit.
- `git log --graph` shows graph with branches.
# Limiting Log Outputs
- `git log --since <date/time>`
- `git log --until <date/time>`
- `git log -S <string>` takes a string and shows only commits that change the number of occurrences of that string.
- `git log -- <path_to_file>` shows commits that only made changes to specific files.
