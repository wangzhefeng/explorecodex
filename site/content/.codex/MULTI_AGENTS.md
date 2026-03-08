# Multi-Agent Workflows

Large tasks become faster and clearer when split across agents.

## Pattern

1. one agent builds a plan and decomposition
2. execution agents implement isolated parts in parallel
3. a final pass agent verifies integration and regressions

## When To Use

- large refactors
- cross-folder migrations
- bug triage plus fix plus test hardening
- docs + code + validation bundles

## Guardrails

- keep each agent scope narrow
- define ownership boundaries before execution
- reconcile outputs through one integration checkpoint

## Official Docs

- Multi-agent concepts: https://developers.openai.com/codex/agents
