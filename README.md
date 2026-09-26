# Skills

This repository contains the marketplace manifest for my custom Claude Code skills

## Available skills

| Skill name | Description | Repository |
| --- | --- | --- |
| `context-manager` | Preserve engineering context across long-running tasks, sessions, and coding agents. | [duckysmacky/context-manager-skill](https://github.com/duckysmacky/context-manager-skill) |
| `guitar-setup` | Configure guitar and amplifier settings to play a certain song | [duckysmacky/guitar-setup-skill](https://github.com/duckysmacky/guitar-setup-skill) |
| `loom` | Drive your self-hosted Loom graph (projects, studies, ideas) from Claude | [duckysmacky/loom](https://github.com/duckysmacky/loom) |

## Installation

Add the marketplace in Claude Code:

```text
/plugin marketplace add duckysmacky/skills
```

Then choose a skill from the table and install it by replacing `<skill-name>` with its name:

```text
/plugin install <skill-name>@duckysmacky
```
