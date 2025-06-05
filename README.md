# Neogit

**A Custom Version Control System Inspired by Git**

> Implemented by *Sara Ghazavi*
> Sharif University of Technology – Fall 1402

---

## 📝 Description

**Neogit** is a custom-built **Version Control System (VCS)** developed as a course project for *Fundamentals of Programming* at Sharif University of Technology. It mimics the core behavior of Git, allowing users to manage source code versions through a simplified command-line interface.

This project was built in two phases and features several Git-like commands implemented from scratch using the C programming language.

---

## 📁 Features

### ✅ Implemented Commands

#### **Phase 1**

* `neogit init` – Initialize a new repository
* `neogit add` – Stage files and directories (supports wildcards and batch additions)
* `neogit reset` – Unstage files
* `neogit status` – Show file status in the working directory
* `neogit commit` – Save staged changes with a message
* `neogit log` – View commit history (with filters)
* `neogit branch` – Create and list branches
* `neogit checkout` – Switch between commits or branches

#### **Phase 2**

* `neogit revert` – Revert changes from a specific commit
* `neogit tag` – Create and list tags (with metadata)
* `neogit tree` – Visualize commit tree structures
* `neogit stash` – Temporarily save and restore working state
* `neogit pre-commit` – Run custom hooks before committing
* `neogit grep` – Search within files and commits
* `neogit diff` – Compare content line-by-line between files or commits
* `neogit merge` – Merge branches with conflict resolution

---

## 🛠️ Technical Stack

* **Language**: C
* **Platform**: Linux / Unix-based systems
* **File System**: POSIX compliant, supports directory trees and file metadata
* **Data Structures**: Stack, Linked List, Tree (for commit history)
* **Versioning**: Supports semantic tagging and branching

---

## 📘 Educational Objectives

* Deepen understanding of how VCS like Git work internally
* Practice system-level programming in C
* Gain experience with file handling, memory management, and command-line interface design
* Reinforce clean code principles and modular programming

---

## 👩‍💻 Author

**Sara Ghazavi**
Sharif University of Technology
Course: Fundamentals of Programming – Fall 1402
