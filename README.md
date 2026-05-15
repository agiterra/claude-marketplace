# agiterra — Claude Code plugin marketplace

This repo is the plugin marketplace registry for the Agiterra Multi-Agent Toolkit on Claude Code. To install:

```
/plugin marketplace add agiterra/claude-marketplace
```

Then `/plugin install <name>@agiterra` for each plugin you want.

## Concepts and setup live elsewhere

This repo only contains the marketplace JSON. To learn what the Toolkit is, how it fits together, and how to set it up properly:

- **[agiterra/handbook](https://github.com/agiterra/handbook)** — concepts (personai vs ephemeral, Wire, knowledge vaults, plugin map), setup walkthroughs, and project patterns
- **[github.com/agiterra](https://github.com/agiterra)** — the org landing with the full plugin map

## Quick start for operators

If you have a Claude Code agent open, the fastest path is:

> "Install the Agiterra marketplace and set up the minimum-useful Agiterra Multi-Agent Toolkit on my machine."

Your agent should follow [handbook/SETUP-CLAUDE-CODE.md](https://github.com/agiterra/handbook/blob/main/SETUP-CLAUDE-CODE.md) and ask only what it genuinely needs.

## Plugins in this marketplace

See [marketplace.json](./.claude-plugin/marketplace.json) for the canonical list. Each plugin has its own README in its repo with the install command and a quickstart.

## Codex (and other runtimes)

Codex agents don't use a marketplace. See [handbook/SETUP-CODEX.md](https://github.com/agiterra/handbook/blob/main/SETUP-CODEX.md) for the `config.toml` approach.

## License

MIT.
