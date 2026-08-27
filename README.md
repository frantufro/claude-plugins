# Claude Code Plugins by Fran Tufro

A Claude Code plugin marketplace.

## Install

```
/plugin marketplace add frantufro/claude-plugins
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **skulk** | Manage a fleet of remote Claude Code agents over SSH | `/plugin install skulk@frantufro-plugins` |
| **cubil** | Manage markdown-based tasks in a plain `.cubil/` directory (backlog, doing, done) | `/plugin install cubil@frantufro-plugins` |
| **husmo** | Save and retrieve documents/links through the husmo MCP server, with search by meaning, tag, or full-text | `/plugin install husmo@frantufro-plugins` |
| **rust-development** | Senior Rust skills: TDD implementation (`rust-dev`) and structured code review (`rust-review`) | `/plugin install rust-development@frantufro-plugins` |

## About

Some plugins live in their own source repositories (like `skulk`) and are fetched from there when installed. Others live directly inside this repo under `plugins/`.
