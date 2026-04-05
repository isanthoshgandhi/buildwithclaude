# Build with Claude — Platform Context

> Updated: 2026-03-22
> READ THIS FIRST for web UI / infra work

---

## RESUME FROM HERE
Last session: 2026-03-22 (approx)
What was done: Web UI live, Docker support added, MCP flag added
Current state: buildwithclaude.com live, Docker MCP flag supported
Open bugs: None known
Next action: Check UPDATES.md for latest platform changes

---

## Platform Overview
- **Web UI:** buildwithclaude.com — browse/search/explore plugins
- **Install:** `claude plugin marketplace add isanthoshgandhi/buildwithclaude`
- **Docker:** MCP flag supported (added v1.2.1)

## Key Files
- `web-ui/` — frontend code
- `scripts/` — sync and utility scripts
- `mcp-servers.json` — MCP server index
- `package.json` — dependencies
- `Dockerfile` — Docker config

## Sync Workflow
GitHub Actions syncs plugin updates from source repos.
Trigger: Actions -> "Sync plugins" -> Run workflow -> choose plugin or "all"
