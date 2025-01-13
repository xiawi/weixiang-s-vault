---
tags:
  - note
up: "[[Pro Git]]"
date: 2025-01-12
---
```table-of-contents
```
# Snapshots, not differences.
Git takes snapshots of our tracked files instead of changes, unlike most other version control systems. Git stores files and pointers referencing those files. If a file remains unchanged, it does not re-store the same file. It simply provides a pointer to the previous commit file.