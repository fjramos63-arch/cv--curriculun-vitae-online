# AGENTS.md

## Project
Static personal site (CV/portfolio) for **Francisco Javier Ramos**, content in Spanish. No build step, no dependencies.

## Files
- `index.html` — single-page layout (hero, services, contact form)
- `styles.css` — all styles, inline-linked from HTML

## Dev
- Preview: open `index.html` in a browser or serve with any static server (e.g. `npx serve`)
- No lint, test, typecheck, or CI tooling exists

## Conventions
- All visible text is in Spanish
- No JavaScript — the contact form has no backend handler

## Git
- Commit only when explicitly requested by the user
- Commit messages: concise, present tense, describe the exact change (e.g., "Update name to Jorge Miralles")
- Never force push to main; warn user if requested
- Push to remote only when explicitly asked

- Commit Types:
Type     Purpose
feat     New feature
fix     Bug fix
docs     Documentation only
style     Formatting/style (no logic)
refactor     Code refactor (no feature/fix)
perf     Performance improvement
test     Add/update tests
build     Build system/dependencies
ci     CI/config changes
chore     Maintenance/misc
revert     Revert commit
- Generate Commit Message
    Type: What kind of change is this?
    Scope: What area/module is affected?
    Description: One-line summary of what changed (present tense, imperative mood, <72 chars)

- Execute Commit

# Single line
git commit -m "<type>[scope]: <description>"