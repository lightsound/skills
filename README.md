# lightsound/skills

A collection of agent skills for Claude Code and Craft Agent.

## Installation

Install all skills:

```bash
npx skills add lightsound/skills
```

Install a specific skill:

```bash
npx skills add lightsound/skills/git-commit
```

## Skills

### git-commit

Analyze diffs, split into logical commits, and create Conventional Commit messages.

**Use when:** You want to commit changes, stage files, or split work into multiple well-scoped commits.

**Features:**
- Follows [Conventional Commits](https://www.conventionalcommits.org/) format
- Splits unrelated changes into separate commits automatically
- Sanity-checks staged changes (no secrets, no debug logs)
- Runs a lint/test check before finalizing

## License

MIT
