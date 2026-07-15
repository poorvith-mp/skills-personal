# skills-personal

Claude / Agent **skills** library by **Poorvith M P**.

- Version: **v0.1**
- Last updated: **July 2026**
- License: **MIT**
- Skills in this repo: **10**

Part of the **[open-claude-skills](https://github.com/prvthmpcypher/open-claude-skills)** multi-repo hub.

## Install

### Claude Code
```bash
# copy one skill
cp -R skills/<skill-id> ~/.claude/skills/<skill-id>
# or project-local
cp -R skills/<skill-id> .claude/skills/<skill-id>
```

### Claude.ai
Zip a single `skills/<skill-id>` folder and upload via **Settings → Capabilities → Skills**.

## Skill index

| Skill ID | Title |
|----------|-------|
| `financial-plan-starter` | Financial Plan Starter |
| `habit-tracker-designer` | Habit Tracker Designer |
| `know-me` | Know Me |
| `linkedin-profile-optimizer` | LinkedIn Profile Optimizer |
| `relationship-crm-builder` | Relationship CRM Builder |
| `resume-optimizer` | Resume Optimizer |
| `salary-negotiation-coach` | Salary Negotiation Coach |
| `second-brain-architect` | Second Brain Architect |
| `travel-planner` | Travel Planner |
| `year-review-system` | Year Review System |

## Structure

Each skill follows skill-creator conventions:

```text
skills/<skill-id>/
├── SKILL.md
├── references/NOTE.md   # empty tips for future progressive disclosure
└── assets/NOTE.md       # empty tips for future templates
```

## Author

Copyright (c) 2026 Poorvith M P
