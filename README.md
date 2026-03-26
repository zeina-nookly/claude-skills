# Claude Skills — Nookly

This repo contains Claude Code skills and remote trigger prompts for Nookly.

## Structure

```
triggers/          — Remote agent prompts (run on Anthropic's cloud on a schedule)
.claude/skills/    — Local Claude Code skills (slash commands you run in the CLI)
```

## Active Triggers

| Name | Schedule | Trigger ID | Description |
|------|----------|------------|-------------|
| Daily AI Digest | 7:47am Dubai daily | `trig_014zmSFbdqGLjHLds2kNcTTB` | Searches AI news, filters for Nookly relevance, creates Gmail draft |

Manage triggers at: https://claude.ai/code/scheduled
