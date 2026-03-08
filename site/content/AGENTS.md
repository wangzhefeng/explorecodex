# AGENTS.md

`AGENTS.md` is the instruction file Codex uses as persistent project context.

## What To Put Here

- project architecture and important directories
- build, test, lint, and release commands
- coding conventions and review expectations
- constraints and no-touch areas
- deployment and environment gotchas

## Minimal Starter Template

```markdown
# Project Rules

## Build & Test
- Install: pnpm install
- Test: pnpm test
- Lint: pnpm lint

## Coding Standards
- TypeScript strict mode required
- Prefer named exports
- Add tests for all behavior changes

## Safety
- Never commit secrets
- Ask before destructive operations
```

## Writing Tips

- Keep instructions concrete and testable
- Keep the file short enough to audit regularly
- Update it when your workflow changes
- Put team rules in this file, not in scattered chat history

## Official Learning Path

- Codex Overview: https://developers.openai.com/codex/overview
- Codex Quickstart: https://developers.openai.com/codex/quickstart
- AGENTS.md Guide: https://developers.openai.com/codex/agents
