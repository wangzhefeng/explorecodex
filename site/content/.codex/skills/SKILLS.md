# Skills

A skill is a reusable instruction package in `.codex/skills/<name>/SKILL.md`.

## Why Skills Matter

- standardize repeated engineering workflows
- reduce prompt repetition across the team
- keep complex procedures in version control

## Recommended Skill Structure

- `SKILL.md`: task instructions and acceptance criteria
- `scripts/`: executable helpers
- `references/`: optional deep docs
- `assets/`: templates and static resources

## First Skill Checklist

1. create `.codex/skills/review/SKILL.md`
2. describe trigger conditions and outputs
3. add a script if deterministic automation helps
4. test the workflow on a small task

## Official Docs

- Skills: https://developers.openai.com/codex/cli/skills
