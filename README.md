# FinalScout Plugins

Official [FinalScout](https://finalscout.com) plugin marketplace for [Claude Code](https://code.claude.com).

## Installation

Add this marketplace in Claude Code:

```
/plugin marketplace add finalscout/finalscout-plugins
```

Then install a plugin:

```
/plugin install finalscout@finalscout-plugins
```

These commands work the same everywhere Claude Code runs — the terminal CLI, the desktop app (Mac/Windows), and the IDE extensions.

### Using in the Claude Code desktop app

1. Open the desktop app and type `/plugin marketplace add finalscout/finalscout-plugins` in the chat input.
2. Type `/plugin` to open the plugin manager, then go to the **Discover** tab to browse this marketplace's plugins.
3. Select a plugin (for example **FinalScout Email Finder**) and press **Enter** to view its details — including the commands and skills it will install — then choose an installation scope (**User** to install for yourself across all projects).
4. Run `/reload-plugins` (or restart the session) to activate the plugin.

Alternatively, skip the browsing UI and install directly with `/plugin install finalscout@finalscout-plugins`.

## Available plugins

| Plugin | Description |
| --- | --- |
| [FinalScout Email Finder](https://github.com/finalscout/claudecode-plugin-b2b-contact-enrichment) | Find verified professional email addresses with the FinalScout API — by LinkedIn profile URL, full name + company domain, or news article URL. Single lookups, bulk batches with progress tracking, CSV export, webhooks, and credit checks. |

## Updating

Refresh your local copy of the marketplace at any time:

```
/plugin marketplace update finalscout-plugins
```

## License

Each plugin is licensed individually — see the plugin's repository for details.
