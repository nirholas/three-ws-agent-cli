# AGENTS.md

Instructions for AI coding agents working in or with `@three-ws/agent`.

## What this is

Run a three.ws agent on your own machine or VPS: a terminal UI with slash commands, streaming tool output, local file and shell tools in a resource-limited sandbox, the three.ws MCP tools and agent wallet, SQLite sessions with full-text search, parallel subagents, natural-language cron, and a Telegram gateway.

## Use it

```bash
npm install @three-ws/agent
```

Full API reference: [README.md](README.md). Machine-readable summary: [llms.txt](llms.txt). Full text: [llms-full.txt](llms-full.txt).

## Work on it

- Node 20 or newer, ESM only.
- Run the tests with `npm test` before proposing a change.
- Keep runtime dependencies at their current count. Prefer a well-maintained library over new hand-rolled code, and say why in the pull request.
- No mocks, placeholders or TODO comments in committed code.
- Do not use em-dashes or en-dashes in code, comments or docs.

## Source of truth

This repository is exported from https://github.com/nirholas/three.ws/tree/main/packages/agent-cli. Bug reports belong here; larger changes should be proposed against the monorepo path.
