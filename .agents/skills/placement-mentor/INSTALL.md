# Onboarding & Operations Manual: Version 1.0

This guide outlines setup, usage pipelines, and maintenance strategies for your custom Placement Mentor.

---

## 1. First Installation
1. Locate your Claude Desktop config file:
   - **Windows**: `%APPDATA%\Claude\claude_desktop_config.json`
2. Configure developer settings to register custom system prompts or copy the contents of [SKILL.md](file:///e:/Phase%203/.agents/skills/placement-mentor/SKILL.md) directly into your Custom Instructions (Claude Desktop Settings -> Custom Instructions).

---

## 2. Connector Setup
- **GitHub**: Link your GitHub account in Claude (Connected Accounts). Point to your repository in `profile.json`.
- **Google Drive**: Link Drive. Store your resume inside the specified drive location.
- **Google Calendar**: Connect Calendar to sync Online Assessment (OA) and interview schedules.
- **Public Profiles**: Add URLs for LeetCode and GeeksforGeeks in `profile.json`.

---

## 3. First Session
1. Load state files into the chat:
   ```markdown
   [Load Config]
   Profile: <Paste profile.json>
   State: <Paste roadmap.json>
   Settings: <Paste settings.json>
   ```
2. The mentor will parse the connected services, detect progress, and output a single highest-priority question to begin.

---

## 4. Daily, Weekly, and Monthly Workflows
- **Daily**: Execute morning standups, run the **Study Optimizer** template, and wrap up by copying the output JSON back to `roadmap.json`.
- **Weekly**: Audit LeetCode solve delta, run **Profile Reviews**, and update deadlines.
- **Monthly**: Pivot strategy if milestones are slipping. Adjust target companies or salary thresholds in `profile.json`.

---

## 5. Directory Layout
- `SKILL.md`: Behavioral instructions.
- `profile.json`: Static student record.
- `roadmap.json`: Dynamic progress log.
- `settings.json`: Custom settings.
- `templates.md`: Prompt templates.

---

## 6. Updating State & Backups
- **State Updates**: Manually overwrite your local `roadmap.json` with the updated JSON block generated at the end of each session.
- **Backup Strategy**: Keep a backup folder of previous `roadmap.json` files weekly.
- **Maintenance**: Review [bugs.md](file:///e:/Phase%203/.agents/skills/placement-mentor/bugs.md) weekly to note anomalies in Claude's behavior.
- **Version Upgrade**: If upgrading the skill, modify instructions in `SKILL.md` directly.

---

## 7. Troubleshooting
- **GitHub Connector Fails**: Disconnect and reconnect under Claude Accounts settings.
- **State Inconsistencies**: Ensure `roadmap.json` matches the exact schema structure.
- **"Insufficient Evidence" Error**: Ensure the public URL contains public statistics or confirm completion manually in writing.
