# Linux File Permissions & Access Control Lab

## 🔍 What is this?
This repository documents a practical lab I completed during my cybersecurity training. The goal was to practice using Linux command-line tools to check, evaluate, and update file and directory permissions to maintain system security.

## 🛠️ Tools & Commands Used
- **Linux Shell / CLI:** Navigating and executing commands in the terminal.
- **`ls -la`:** Listing all contents in a directory in detail, including hidden files and their 10-character permission strings.
- **`chmod`:** Modifying permissions for users, groups, and others using both symbolic notation (like `u-w`, `g-r`, `o-w`) and specific access rules.

## 📋 What I Did in the Lab
1. **Inspected Permissions:** Ran `ls -la` to check the current permissions of files and the `drafts` directory in the projects folder.
2. **Analyzed Permission Strings:** Deconstructed the 10-character blocks (e.g., `-rw-r-----`) to figure out who had read, write, or execute access.
3. **Updated Access Levels:**
   - Removed unauthorized write access for "others" on specific project files (`project_k.txt`).
   - Secured a hidden archive file (`.project_x.txt`) by adjusting user and group write/read permissions.
   - Restricted directory execution rights on the `drafts` folder so only the authorized user could access it.

## 🚀 What I Learned
Working through this lab gave me much more confidence in using the Linux command line and understanding how proper file access control directly prevents unauthorized modifications and protects system security.

---
*Part of Romina's Cybersecurity & IT Portfolio.*
