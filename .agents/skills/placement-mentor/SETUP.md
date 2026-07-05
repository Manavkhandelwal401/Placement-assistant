# Integration & Setup Guide

This document maps integrations, access methods, and required setup actions.

---

## 1. Automatic Integrations
*These require active Claude Connectors and sync automatically without file updates.*

### GitHub
- **Purpose**: Verify code commits, review project structure, check repo hygiene.
- **Access Method**: Claude GitHub Connector.
- **Required Action**: Authenticate Claude to your GitHub account under settings.

### Google Drive
- **Purpose**: Access resume versions and project documents.
- **Access Method**: Claude Google Drive Connector.
- **Required Action**: Authenticate Google Drive and add the drive folder path to `profile.json`.

### Google Calendar
- **Purpose**: Track upcoming OAs and interview schedules.
- **Access Method**: Claude Google Calendar Connector.
- **Required Action**: Link Google Calendar and add placement events to your calendar.

---

## 2. Semi-Automatic Integrations
*These use public profile scraper scripts or public URL lookups.*

### LeetCode
- **Purpose**: Track solve counts, verify solved problems, evaluate weak topics.
- **Access Method**: Scrape public profile page listed in `profile.json`.
- **Required Action**: Set LeetCode profile to public and add the link to `profile.json`.

### GeeksforGeeks
- **Purpose**: Track coding metrics.
- **Access Method**: Public profile URL lookup.
- **Required Action**: Set profile to public and add the link to `profile.json`.

### Portfolio
- **Purpose**: Design review, hosting verification.
- **Access Method**: Scrape URL.
- **Required Action**: Add public link to `profile.json`.

---

## 3. Manual Integrations
*These require manual copy-pasting or file editing.*

### College Placement Portal
- **Purpose**: Ingest job postings and college rules.
- **Access Method**: Copy-paste text.
- **Required Action**: Paste announcement texts during active session chats.

### Resume & Mock Interviews
- **Purpose**: Detailed line-by-line feedback.
- **Access Method**: File upload (PDF/TXT) or pasting transcripts.
- **Required Action**: Upload resume files or paste interview transcripts when prompted.
