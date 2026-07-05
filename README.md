# PhantomOS 🚀

PhantomOS is a customized, interactive dashboard and personal placement mentor engine designed to track and accelerate preparation for software engineering roles leading up to the September 1 target date.

## 📁 Repository Layout

### Frontend Dashboard (Root)
- **`index.html`**: The main responsive, interactive placement dashboard dashboard.
- **`manifest.json`** & **`sw.js`**: Progressive Web App (PWA) configuration files enabling offline support and direct "Add to Home Screen" installation on mobile.
- **`profile.json`**: Personal targets, context, and profile.
- **`roadmap.json`**: Current milestone progress logs and active DSA study topics.
- **`settings.json`**: Configurable rules for the mentor agent.

### Custom Mentor Agent ( `.agents/skills/placement-mentor/` )
- **`SKILL.md`**: Core system logic and behavioral instructions for the AI agent.
- **`MENTOR_GUIDE.md`**: Mentorship operational guidelines.
- **`templates.md`**: Prompt templates for Daily Standups and LeetCode Peer Review.
- **`SETUP.md`** & **`INSTALL.md`**: Setup and installation guides for custom agent systems.

---

## ⚡ Deployment on GitHub Pages

This repository is pre-configured to be hosted directly on GitHub Pages:
1. Go to your repository settings on GitHub.
2. Navigate to **Pages** in the left sidebar.
3. Under **Build and deployment**, select **Deploy from a branch** and set the source to `main` (Root `/`).
4. Click **Save**. Your HTTPS URL will be generated, allowing you to access the dashboard and download the application on your phone natively.
