# split-publish-skill

Portable `split-publish` skill package for Codex and Claude.

## Files

- `SKILL.md`: Codex skill entry
- `CLAUDE.md`: Claude instruction block
- `references/grouping-rules.md`: commit grouping rubric

## Codex Usage

Install from this repository using your Codex skill installer flow, or clone and place under:

- `~/.codex/skills/split-publish`

## Claude Usage

Reference `CLAUDE.md` from your project-level instruction file (for example `AGENTS.md`).

Example:

```md
When handling split-commit publish tasks, follow:
`<repo-root>/CLAUDE.md`
```

## Trigger Phrases

- split publish
- split changes by job and push
- group pending changes into separate commits and publish
