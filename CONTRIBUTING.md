# Contributing to Skills Workshop

Thank you for your interest in contributing! Here's how to add skills or improve existing ones.

## Quick Start

### Adding a New Skill

1. **Fork the repository**
2. **Create a folder** under `skills/` following the naming convention:
   - Lowercase letters, numbers, and hyphens only
   - Must match the `name` field in your `SKILL.md`
   - Example: `skills/my-new-skill/`

3. **Add a `SKILL.md`** file with:
   - YAML frontmatter (`name` and `description` required)
   - Instructions in Markdown

4. **Submit a pull request**

## SKILL.md Format

```markdown
---
name: your-skill-name
description: |
  A clear description of what this skill does and when to use it.
  Include keywords that help agents identify relevant tasks.
---

Your instructions here.
```

### Required Fields

| Field | Constraints |
|-------|-------------|
| `name` | 1-64 chars, lowercase, hyphens only |
| `description` | 1-1024 chars, describes what AND when to use |

### Optional Fields

| Field | Purpose |
|-------|---------|
| `license` | License name or reference |
| `compatibility` | Environment requirements |
| `metadata` | Arbitrary key-value pairs |
| `allowed-tools` | Pre-approved tools (experimental) |

## Best Practices

### Write for Agents
- Focus on what the agent **wouldn't know** on its own
- Include specific keywords for triggering
- Be concrete — avoid generic instructions

### Test Your Skill
- Run it with real prompts
- Check that it activates when expected
- Verify the output quality

### Keep It Scoped
- One skill = one capability
- Well-scoped skills compose better together
- If it's too complex, split it into multiple skills

## Skill Quality Checklist

Before submitting:

- [ ] `name` is lowercase with hyphens only
- [ ] `description` is clear and includes trigger keywords
- [ ] Instructions are actionable and specific
- [ ] No unnecessary explanation of basics
- [ ] Tested with real prompts
- [ ] No copyrighted material without permission

## Ideas for Skills

- **Communication patterns** — Stuart's triggers, conversation openers
- **Domain expertise** — legal, medical, technical specializations
- **Creative tools** — brainstorming, ideation, writing assistance
- **Workflow automation** — repeated processes, templates

## Questions?

Open an issue or reach out to the repository owner.

Happy skill-building!