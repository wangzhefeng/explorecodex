# CLI Slash Commands

Codex CLI supports slash commands for common control flows.

## Common Daily Commands

- `/help`: show command list
- `/status`: current model, context, and session status
- `/model`: inspect or switch model
- `/approvals`: review approval mode and pending approvals
- `/mcp`: inspect MCP tool connections

## Good Practice

- start each session by checking `/status`
- switch model intentionally based on task complexity
- keep approvals strict in risky repos
- use `/mcp` before tool-heavy tasks to verify connectivity

## Official Docs

- CLI overview: https://developers.openai.com/codex/cli
