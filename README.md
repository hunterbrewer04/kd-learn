# KD Learn

Welcome! This repo is your home base for learning Python and Claude Code. Whether you've never written a line of code or you're just getting started with AI-assisted development, you're in the right place.

## What's in here?

- **resources/** — Curated learning links for Python, Git, SSH, and more
- **claude-toolkit/** — A collection of skills, agents, and hooks for Claude Code (added as a git submodule)

## Getting Started

### 1. Install Python

**Mac:**
```bash
brew install python
```

**Windows:**

Download from [python.org](https://www.python.org/downloads/) and run the installer. Make sure to check "Add Python to PATH" during installation.

Verify it's working:
```bash
python3 --version
```

### 2. Install Claude Code

Claude Code is an AI coding assistant that runs in your terminal. It can help you write, understand, and debug code — perfect for learning.

```bash
npm install -g @anthropic-ai/claude-code
```

> You'll need [Node.js](https://nodejs.org/) installed first. Download the LTS version.

Once installed, run it in any project folder:
```bash
claude
```

### 3. Clone this repo

```bash
git clone --recurse-submodules https://github.com/hunterbrewer04/kd-learn.git
cd kd-learn
```

> The `--recurse-submodules` flag pulls in the claude-toolkit automatically.

## How to use Claude Code to learn

Claude Code is like having a tutor in your terminal. Here are some things you can try:

- **Ask it to explain code:** Paste any Python snippet and ask "what does this do?"
- **Get help with errors:** When you hit an error, ask Claude to explain what went wrong
- **Build small projects:** Describe what you want to build and work through it together
- **Learn concepts:** Ask questions like "what is a for loop?" or "how do lists work in Python?"

The key is to stay curious and experiment. Don't worry about breaking things — that's how you learn.

## Resources

Check out [resources/RESOURCES.md](resources/RESOURCES.md) for a curated list of learning links.

## Claude Toolkit

The [claude-toolkit](https://github.com/hunterbrewer04/claude-toolkit) submodule contains skills, agents, and hooks that extend what Claude Code can do. As you get more comfortable, explore it to see how to customize your Claude Code setup.
