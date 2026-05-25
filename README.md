# SmartTill Admin Tool

Internal admin tool for managing SmartTill client licences, generating client files, and managing Firebase configuration.

## Access

**Live URL:** https://digitalsolutions1194.github.io/SmartTill-Admin/

## Features

- Client management (add, edit, view all clients)
- Licence management (Free / Pro / Business tiers)
- File generator — generates customised SmartTill.html for each client
- Firebase configuration management
- Self-updating via GitHub Pages

## Setup

1. Open `chi-admin-tool.html` in a browser
2. On first launch, enter your admin PIN — this becomes your permanent PIN stored locally
3. The tool checks for updates automatically after login

## Deployment

Push `chi-admin-tool.html`, `index.html`, and `version.json` to this repo.
GitHub Pages serves from the `main` branch root.

## Updating

When releasing a new version:
1. Update `ADMIN_VERSION` in `chi-admin-tool.html`
2. Update `version` in `version.json`
3. Push both files to GitHub
4. The admin tool will detect the update on next login and prompt to update
