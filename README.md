# split-publish-skill

Portable `split-publish` skill package for Codex, Claude, and Gemini.

## Files

- `SKILL.md`: Codex skill entry
- `CLAUDE.md`: Claude instruction block
- `GEMINI.md`: Gemini instruction block
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

## Gemini Usage

### Global Installation (Everywhere)
Add a reference to this repository's `GEMINI.md` in your global `~/.gemini/gemini.md` file:

```md
# Split Publish Skill
--- Context from: /absolute/path/to/split-publish-skill/GEMINI.md ---
```

### Local Installation (Specific Project)
Copy or symlink `GEMINI.md` to your project root, or include it in your project's `GEMINI.md`:

```md
When handling split-commit publish tasks, follow:
`./GEMINI.md`
```

## Trigger Phrases

- split publish
- split changes by job and push
- group pending changes into separate commits and publish
