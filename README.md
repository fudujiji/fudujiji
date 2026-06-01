# Jack Sun

AI-native operator focused on MCP, agent tooling, prediction markets, and local automation.

I work best on small, concrete fixes: reproducing bugs, tightening tests, improving docs, and turning messy research workflows into tools that are easy to inspect and run.

## Current Focus

- MCP servers, SDKs, inspector tooling, and conformance tests
- Prediction-market and crypto research infrastructure
- Agent workflows: repo triage, review loops, memory, and local automation
- Clear documentation with reproducible steps and honest limitations

## Recent OSS Work Under Review

- [hn-research/axray #5](https://github.com/hn-research/axray/pull/5) - added Zed `context_servers` discovery for MCP server scans.
- [modelcontextprotocol/inspector #1397](https://github.com/modelcontextprotocol/inspector/pull/1397) - hardened `Managed*State` connect-path tests by replacing fixed microtask flushes with `vi.waitFor`.
- [hummingbot/mcp #23](https://github.com/hummingbot/mcp/pull/23) - fixed bot status PnL percentage formatting so values are not multiplied by 100 twice.
- [caiovicentino/polymarket-mcp-server #29](https://github.com/caiovicentino/polymarket-mcp-server/pull/29) - fixed market text search to use Polymarket's public search endpoint.
- [Goldentrii/AgentRecall-MCP #17](https://github.com/Goldentrii/AgentRecall-MCP/pull/17) - exposed `journal_search` filtering options for `since` and `limit`.

## Supporting Tools

- [codex-repo-onboarding-kit](https://github.com/fudujiji/codex-repo-onboarding-kit) - local-first CLI that generates Codex-ready `PROJECT_BRIEF.md` files for repositories.
- [research-card-studio](https://github.com/fudujiji/research-card-studio) - local-first tool for turning messy research notes into clean shareable cards.
- [openclaw-hybrid-memory-starter](https://github.com/fudujiji/openclaw-hybrid-memory-starter) - minimal starter for hybrid memory retrieval in agent workflows.
- [tab-auto-refresh](https://github.com/fudujiji/tab-auto-refresh) - tiny Chrome extension for manual current-tab refresh automation.

## Principles

- Small tools over bloated demos.
- Real issue reproduction before code changes.
- Useful README first: what it does, who it helps, how to run it, and where it breaks.
- Automation with human-readable evidence and clear failure modes.
