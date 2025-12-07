# Stitch

TODOs speak, tickets move.

Stitch watches diffs for `TODO:` lines and auto-creates/resolves issues in Jira, Linear, or GitHub—no keys needed. Add a TODO in code → a clean issue appears with links to the exact line. Remove the TODO → the issue closes.

## Quick start
1) Install the Stitch GitHub App/Action (WIP).
2) Add tracker tokens as secrets (e.g., `LINEAR_API_KEY`, `JIRA_TOKEN`, `GITHUB_TOKEN`).
3) Write TODOs naturally, e.g.:
   - `// TODO: Add routing to auth`
   - `# TODO: Refactor token refresh`
4) Push your changes. Stitch opens/updates issues automatically.

## What it does
- Reacts to push/PR events
- Parses unified diffs for added/removed TODOs
- Generates titles from TODO text (e.g., “Add routing to auth”)
- Links back to file, line, commit/PR
- Resolves issues when TODOs disappear

## Config (optional)
Create `stitch.config.json` to set default tracker, path→project mapping, labels, and confidence rules.

## Status
Pre-release. APIs and behavior may change.

## License
MIT
