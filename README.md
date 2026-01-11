# Homebrew Tap for repo-tasks

Official Homebrew tap for [repo-tasks](https://github.com/claydiffrient/repo-tasks) - fast, file-based task management for git repositories.

## Installation

```bash
# Add the tap
brew tap claydiffrient/repo-tasks

# Install repo-tasks
brew install repo-tasks
```

Or install directly without tapping:

```bash
brew install claydiffrient/repo-tasks/repo-tasks
```

## What is repo-tasks?

`repo-tasks` is a lightning-fast CLI tool for managing tasks directly in your git repository. Tasks are stored as simple Markdown files with YAML frontmatter, making them easy to read, edit, and version control.

### Features

- ⚡ **Blazing Fast** - Sub-10ms response times
- 📁 **File-Based** - Tasks stored as readable Markdown files
- 🔍 **Powerful Search** - Full-text search powered by ripgrep
- 🔄 **Git Integration** - Commit changes with auto-generated messages
- 🤖 **LLM-Friendly** - Designed for easy AI agent manipulation
- 🔌 **MCP Server** - Built-in Model Context Protocol server for Claude integration

## Documentation

For full documentation, visit the [main repository](https://github.com/claydiffrient/repo-tasks).

## Updating

```bash
brew update
brew upgrade repo-tasks
```

## Uninstalling

```bash
brew uninstall repo-tasks
brew untap claydiffrient/repo-tasks
```

## Issues

If you encounter any issues with the Homebrew formula, please report them at:
- Tap issues: [homebrew-repo-tasks/issues](https://github.com/claydiffrient/homebrew-repo-tasks/issues)
- App issues: [repo-tasks/issues](https://github.com/claydiffrient/repo-tasks/issues)
