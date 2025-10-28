# Autonomo Axiom

### “Git, evolved for humans and AI.”

> **Human + AI = Co-Creators**
> At **Autonomo**, we believe the future isn’t humans *or* artificial intelligence — it’s humans *with* AI, working together.
> Research shows that when humans and AI collaborate, they achieve outcomes neither could alone.
> Autonomo Axiom embodies that partnership: tools that empower you — the developer, the creator, the innovator — *and* your AI partner to version, build, and evolve code as a unified team.

---

## ⚙️ What It Does

Autonomo Axiom transforms version control into a conversational, intelligent experience designed for both humans and AI collaborators.
It streamlines the Git workflow into natural actions like `update`, `undo`, and `redo`, while preserving all the power of traditional Git underneath a much cleaner interface.

> “Axiom doesn’t just track your code — it remembers your intent.”

---

## 🧬 How It Works

Under the hood, **Axiom runs on real `git`**, but **stores its data in its own isolated directory**:

```
.autonomo-vcs/
```

This means:

* It **never interferes** with your project’s existing Git repository.
* You get **all the benefits** of Git’s proven backend — diffs, history, merging, and safety —
* Without any of the clutter, syntax anxiety, or detached-HEAD confusion.

The result is a **parallel, intelligent VCS layer** built for clarity, collaboration, and AI co-evolution.

---

## 🧱 Core Features

| Command                         | Description                                                                                   |
| ------------------------------- | --------------------------------------------------------------------------------------------- |
| **`axiom store`**               | Stage and record new or modified files safely.                                                |
| **`axiom update`**              | Automatically commit the latest tracked changes with an AI-generated or human-edited message. |
| **`axiom undo` / `axiom redo`** | Instantly revert or re-apply your last change — whether made by you or your AI assistant.     |
| **`axiom delete`**              | Delete files safely, with confirmation and undo support.                                      |
| **`axiom push`**                | Guided push with remote + branch detection.                                                   |
| **AI Commit Intelligence**      | Analyzes diffs, suggests semantic messages, and explains intent.                              |
| **Smart Git Safety Layer**      | Detects destructive commands (`git clean -fd`, etc.) and warns before execution.              |
| **Branch Awareness**            | Suggests human-readable branch names like `feature/login-flow`.                               |
| **Pre-Push Validation**         | Scans for conflicts and missing merges before pushing.                                        |

---

## 💻 Example Usage

```bash
# Initialize the repository
axiom init

# Store a new file
axiom store src/main.rs

# Update: commit all tracked changes
axiom update
# -> AI proposes: "Refactor main.rs to improve logging performance"

# Undo the last commit or action
axiom undo
# -> Reverts to the state before last commit

# Redo what was undone (reapply)
axiom redo
# -> Reapplies the undone commit safely

# Push to your remote repository
axiom push
# -> Axiom asks: remote name, branch, and commit message if missing
```

Axiom guides you through each step — gently, intelligently, and never in the way.

---

## 🛠️ Technical Overview

* Written in **Rust 🦀** for reliability and speed
* Built atop native **Git libraries** for perfect compatibility
* Maintains a **local `.autonomo-vcs` directory** separate from your repo
* Offers **transaction-safe undo/redo stack**
* Functions as **CLI, library, or embeddable service**
* Integrates with **Autonomo CLI**, **Software Locker**, and **Axiom API**

---

## 🛡️ Safety First

Axiom was designed by developers who know the pain of losing work to a stray Git command.
Every destructive operation is intercepted, logged, and confirmable.
Automatic pre-push checks, backup snapshots, and readable confirmations ensure you never lose history — human or AI-made.

> “Every push should be confident, not cautious.”

---

## 🌌 Philosophy in One Line

> “Autonomo Axiom turns Git from a command line into a conversation.”

No syntax battles. No lost branches.
Just continuous evolution — where humans and AI co-author history together.

---

## 🧩 Links

* 🦀 **GitHub** → `github.com/autonomo-dev/axiom`
* 📘 **Docs** → `docs.autonomo.codes/axiom`
* 🧠 **Powered by Autonomo AI** → [autonomo.codes](https://autonomo.codes)

