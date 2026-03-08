# Sandbox & Approvals

Codex separates what can run automatically from what requires confirmation.

## Core Idea

- sandbox mode limits filesystem and command execution scope
- approval mode defines when Codex must ask before running commands

## Practical Guidance

- use restrictive defaults for production repositories
- allow broader access only for trusted paths and commands
- review command intent before approving escalated actions
- document your policy in AGENTS.md so team behavior stays consistent

## Official Docs

- Sandboxing guide: https://developers.openai.com/codex/cli/sandboxing
