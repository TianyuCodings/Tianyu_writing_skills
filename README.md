# Tianyu_writing_skills

Private Claude Code plugin packaging Tianyu's academic writing skill for AI conference papers.

The skill (`skills/tianyu-writing-skills/SKILL.md`) is distilled from
[hzwer/WritingAIPaper](https://github.com/hzwer/WritingAIPaper) by hzwer and DingXiaoH.
The complete original handbook and the "not good ideas" catalogue are preserved verbatim under
`skills/tianyu-writing-skills/references/` — all credit for that content goes to the original authors.

## Install as a plugin (recommended)

Inside Claude Code:

```
/plugin marketplace add TianyuCodings/Tianyu_writing_skills
/plugin install tianyu-writing-skills@tianyu-writing-skills-marketplace
```

(For a private repo, make sure `git`/`gh` credentials on the machine can read it; a local clone path also works with `/plugin marketplace add /path/to/Tianyu_writing_skills`.)

## Alternative: install as a plain personal skill

```
git clone git@github.com:<github-user>/Tianyu_writing_skills.git
cp -r Tianyu_writing_skills/skills/tianyu-writing-skills ~/.claude/skills/
```

## What the skill does

When drafting, revising, or pre-submission-checking an AI/ML paper, Claude applies:

- Core-idea framing (insight / performance / capability) before any prose
- The three-move introduction formula and related-work guidance
- Four readability properties: logical strength, defensibility, confusion time, information density
- Polishing and last-few-hours submission checklists
- Self-review against common negative reviewer comments and questionable experimental practices
