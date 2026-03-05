# aurehub-claude-marketplace

Marketplace index for installing AureHub Claude Code plugins.

## Indexed Plugins

- `aurehub-agents` -> `aurehub/agents` (`claude/` subdirectory)
- `aurehub-skills` -> `aurehub/skills` (repository root)

## Usage

In Claude Code:

```text
/plugin marketplace add https://github.com/aurehub/claude-marketplace
/plugin install aurehub-agents@aurehub-marketplace
/plugin install aurehub-skills@aurehub-marketplace
```

For local testing:

```text
/plugin marketplace add /absolute/path/to/aurehub-claude-marketplace
```
