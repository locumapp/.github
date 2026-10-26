# Locum

*The one who covers your post while you are away.*

Locum is a macOS app that runs AI agents in the background and takes over part
of the engineering work: it reviews pull requests, investigates, pulls context
from several tools and writes the draft. Nothing an agent produces goes out on
its own. Every action that writes to an outside service (commenting on GitHub,
replying in Slack, touching a card) stops in a queue and waits for your
approval.

- **Local first.** SQLite, credentials in the macOS keychain, execution on your
  own machine. There is no Locum server in the middle.
- **Nothing leaves without you.** Every write to an outside service goes through
  a single approval gate.
- **Configurable without code.** Agents, triggers, providers and connections are
  set up in the interface or by Claude Code talking to Locum's own MCP server.

## Repositories

| repository | what it is |
|---|---|
| [locumapp.github.io](https://github.com/locumapp/locumapp.github.io) | site and macOS releases |
| [locum-marketplace](https://github.com/locumapp/locum-marketplace) | connections, automation templates and packages |

## Get it

Download the `.dmg` from [locumapp.github.io](https://locumapp.github.io). Apple
Silicon only for now.
