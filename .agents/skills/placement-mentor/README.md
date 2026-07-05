# Personal Placement Mentor Claude Skill

This repository contains a personal, token-optimized placement mentor skill for Claude Desktop.

## Repository Layout
- `SKILL.md`: Core system logic and behavioral engines.
- `profile.json`: Permanent personal context, targets, and links.
- `roadmap.json`: Dynamic state, milestones, progress, and logs.
- `settings.json`: Configurable rules (concise/strict).
- `templates.md`: Prompt templates (Daily Standup, LeetCode Peer Review).

## Daily Workflow
1. Start a session by pasting your current `roadmap.json` and the previous session's summary.
2. Use prompt templates from `templates.md` to perform daily standups or reviews.
3. End the session by asking the mentor to output the updated `roadmap.json` block and a summary, then save them to your workspace.
