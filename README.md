
# Git Conventional Commits Extension

> A **Pure Gemini Extension** (No-Code) that enforces [Conventional Commits](https://www.conventionalcommits.org/).

This extension empowers Gemini to act as a **Senior Git Workflow Expert**, guiding you through creating semantic commits and standardizing feature branches using your system's `git` directly.

## ✨ Features
- **Prompt-Based Logic**: Uses the official spec as ground truth for LLM reasoning.
- **Zero Dependencies**: No Node.js, Python, or compiled binaries required.
- **System Git**: Executes `!git` commands directly in your shell.
- **🧠 Context Evaluation**: Analyzes staged changes to suggest semantic messages.

## 🚀 Quick Start

### Install as Gemini Extension (Recommended)

Transform your terminal into an intelligent git assistant:

```bash
gemini extensions install https://github.com/jorelcb/git-conventional-commits
```

**🔄 Updating**:
```bash
gemini extensions install https://github.com/jorelcb/git-conventional-commits
```

### Available Slash Commands

| Command | Description |
|---------|-------------|
| `/commit` | 📝 Interactively stage changes and commit with a valid message. |
| `/feature:start` | 🌿 Start a new feature branch (e.g., `feature/awesome-logic`). |
| `/feature:finish` | 🏁 Finish the current feature (Rebase + Push). |

**Part of the [Gemini Extensions Monorepo](../README.md)**
