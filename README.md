# claude-team-skills

A Claude Code plugin marketplace that keeps our team's Claude skills in one place.

## Install (once per teammate)

```
/plugin marketplace add hasalaonline/claude-team-skills
/plugin install team-standards@team-skills
```

## Add or change a skill

1. Add a folder under `plugins/team-standards/skills/<skill-name>/` with a `SKILL.md`.
2. Run `claude plugin validate .`
3. Open a PR. Once merged, everyone gets it on their next update.
