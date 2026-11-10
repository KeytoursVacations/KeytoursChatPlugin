# Keytours Claude Plugins

Official [Claude Code](https://code.claude.com) plugin marketplace from [Keytours Vacations](https://www.keytours.com/).

## Plugins

| Plugin | Description |
|---|---|
| [Keytours](plugins/keytours) | Luxury Travel & Vacations. Your personal luxury travel planner: hotels, tours, activities, flights, trains, transfers, cruises and car rentals, saved as a trip plan in your Keytours account. Powered by KeyBrain. |

## Installation

In Claude Code, add this marketplace and install the plugin:

```
/plugin marketplace add keytours/claude-plugins
/plugin install keytours@keytours
```

Then ask Claude to plan a trip, for example:

> Plan a luxury 10-day vacation to Italy for two adults in May, with 5-star hotels and private airport transfers.

The first time you save a trip plan, a browser window opens for you to sign in with your Keytours account.

## Repository structure

```
.claude-plugin/marketplace.json            Marketplace catalog
plugins/keytours/
  .claude-plugin/plugin.json               Plugin manifest
  .mcp.json                                Keytours MCP server connection
  skills/plan/SKILL.md                     Travel planning skill
  assets/keytours-vacations-logo.png       Plugin icon
```

## Privacy and terms

- [Privacy Policy](https://www.keytours.com/sp/privacy-policy)
- [Terms & Conditions](https://www.keytours.com/sp/terms-conditions)

## Support

Contact us at info@keytours.com or https://www.keytours.com/sp/contact-us.

## License

Proprietary. See [LICENSE](LICENSE).
