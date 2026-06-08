# rafa-plugins

Personal plugin catalog (marketplace) for **Claude Code** and **Codex**.

This repo holds **no plugin code** — only marketplace manifests that point to the
plugins where they live:

- **Claude Code** → `.claude-plugin/marketplace.json`
- **Codex** → `.agents/plugins/marketplace.json`

## Plugins

| Plugin | Claude Code | Codex |
|--------|-------------|-------|
| `buildprint-cli` | ✅ `rafachavantes/using-buildprint-cli` | ✅ (same repo, `.codex-plugin`) |
| `honcho` | ✅ `rafachavantes/claude-honcho` (`plugins/honcho`) | ⏳ honcho-codex (pending) |

## Add the marketplace

```bash
# Claude Code
/plugin marketplace add rafachavantes/rafa-plugins

# Codex
codex plugin marketplace add rafachavantes/rafa-plugins
```
