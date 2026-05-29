# 🖤 ScottsTechX tmux

<p align="center">
  <img src="https://img.shields.io/badge/tmux-Terminal-Multiplexer-00ff88?style=for-the-badge&logo=linux&logoColor=black" alt="tmux"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **Terminal multiplexer — split panes, persistent sessions, and detachable terminals.**

---

## ⚡ What It Does

tmux lets you split terminals into multiple panes, windows, and sessions — run multiple commands simultaneously, detach and reattach sessions, and share terminals with others.

## 🚀 Quick Usage

```bash
# Start new session
tmux new -s pentest

# Split horizontal
Ctrl+b "

# Split vertical
Ctrl+b %

# Navigate panes
Ctrl+b arrow-keys

# Detach session
Ctrl+b d

# Reattach session
tmux attach -t pentest

# List sessions
tmux ls
```

## 🎯 CTF Workflow

```bash
# Create session with windows
tmux new -s ctf
# Window 1: recon
# Window 2: exploitation
# Window 3: notes

# Detach when done
Ctrl+b d

# Resume later
tmux attach -t ctf
```

---

MIT © 2026
