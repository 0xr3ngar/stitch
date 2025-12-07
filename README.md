<div align="center">
<img width="250" height="250" alt="Screenshot 2025-12-07 at 23 09 23" src="https://github.com/user-attachments/assets/d077d5c7-17e5-457b-8711-8f9e62f26127" />


# Stitch

**TODOs speak, tickets move. Auto-create and resolve issues from code comments.**

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.9-blue?style=for-the-badge&logo=typescript"/>
  <img alt="GitHub App/Action" src="https://img.shields.io/badge/GitHub-App%20%2F%20Action-black?style=for-the-badge&logo=github"/>
  <img alt="License" src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>
</div>

---

Stitch watches diffs for `TODO:` lines and syncs them to Jira, Linear, or GitHub Issues—no keys needed. Add a TODO → a clean issue appears with deep links. Remove the TODO → the issue resolves.

## Features
- Auto-create issues from plain TODOs
- Resolve when TODOs disappear
- Links back to file, line, commit/PR
- Optional config for paths, labels, ownership

## Prerequisites
- GitHub App or Action installed
- Tokens: `JIRA_TOKEN`, `LINEAR_API_KEY`, `GITHUB_TOKEN`

## Install
```bash
# WIP: app/action release incoming
```

## Configure
Create `.env` or repo secrets with tracker tokens. Optional `stitch.config.json` for path→project maps and labels.

## Usage
Write natural TODOs:
```
// TODO: Add routing to auth
# TODO: Refactor token refresh
```
Push your code. Stitch opens/updates issues automatically.

## Status
Pre-release. APIs and behavior may change.

## License
MIT
