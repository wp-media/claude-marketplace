# WP Media — Claude Code Marketplace

Central plugin registry for WP Media Claude Code plugins.

## Setup

```bash
/plugin marketplace add wp-media/claude-marketplace
```

## Available plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **Maestro** | Unified AI delivery pipeline for WordPress plugin and website projects | `/plugin install maestro@wp-media` |
| **Podium** | AI observability dashboard for Claude Code sessions | `/plugin install podium@wp-media` |
| **Cadenza** | Standalone utility agents — no pipeline required | `/plugin install cadenza@wp-media` |

## Plugins

### Maestro
Orchestrates the full AI delivery pipeline: grooming → implementation → review → QA → release. Configured per-project via `maestro.json`.

→ [wp-media/maestro](https://github.com/wp-media/maestro)

### Podium
Zero-token observability dashboard. Captures every tool call and agent spawn via Claude Code hooks, streams to a real-time dashboard.

→ [wp-media/podium](https://github.com/wp-media/podium)

### Cadenza
Standalone utility agents — each with one job. Generate changelogs, write PR descriptions, author PHPUnit tests, and produce retrospective reports. Works on its own or alongside Maestro.

→ [wp-media/cadenza](https://github.com/wp-media/cadenza)
