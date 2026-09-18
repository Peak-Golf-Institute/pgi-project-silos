# PGI Project Silos Dashboard

A real-time visual dashboard for tracking PGI's major project initiatives across Technology, HR, and Marketing silos.

## Overview

This dashboard provides a quick, daily-reference view of:
- **Technology**: Digital Evaluations, Mental Assessments
- **HR & Talent**: Talent Hub, CPC Training Build
- **Marketing**: Flyers (Caddy), Website Upgrades

Each project shows:
- Current status (Active, Planning, Blocked, Complete)
- Progress percentage
- Project owner
- Target completion date
- Key blockers

## Features

✨ **Interactive Status Tracking** — Click badges to cycle through status states  
📊 **Visual Progress Bars** — See at a glance where each project stands  
🎨 **Dark Mode Support** — Automatically follows your system preference  
📱 **Responsive Design** — Works on desktop, tablet, and mobile  

## Local Development

```bash
# Clone the repo
git clone https://github.com/Peak-Golf-Institute/pgi-project-silos.git
cd pgi-project-silos

# Open in browser (static site, no build needed)
open index.html
```

## Deployment

Deployed automatically to **pgi-project-silos.netlify.app** via Netlify.

### Deploy Steps
1. Push changes to `main` branch
2. Netlify auto-deploys within 1-2 minutes
3. Live at: https://pgi-project-silos.netlify.app

### Rollback
```bash
git log --oneline          # See commit history
git revert <commit-hash>   # Undo a specific commit
git push origin main       # Auto-deploys
```

## Updating the Dashboard

### Add/Edit Projects
Edit `index.html` directly. Each project is a `.branch` div with:
- Title, status badge, owner, target date
- Progress bar (0-100%)
- Description and blockers (optional)

### Change Status
Click the status badge on the live site to cycle through:
- ● Active (green)
- ⏱ Planning (orange)
- ⛔ Blocked (red)
- ✓ Complete (gray)

### Update Progress Bars
Find the `.progress-fill` element and change `width: X%`

## Project Structure

```
pgi-project-silos/
├── index.html          # Main dashboard
├── README.md           # This file
├── .gitignore          # Git exclusions
└── netlify.toml        # Netlify config
```

## Tech Stack

- **HTML/CSS/JS** — No build step, pure web standards
- **Netlify** — Auto-deployment from GitHub
- **GitHub** — Version control

## Questions?

See the Peak Golf Institute GitHub organization for related projects:
- [pgi-mental-assessments](https://github.com/Peak-Golf-Institute/pgi-mental-assessments)
- [pgi-business-development](https://github.com/Peak-Golf-Institute/pgi-business-development)

---

**Last Updated:** 2026-09-18  
**Live URL:** https://pgi-project-silos.netlify.app
