# Contributing to thedoctormes-hue

## Commit Convention
- Use conventional commits: `feat:`, `fix:`, `chore:`, `docs:`, `test:`, `refactor:`
- Write in English
- Subject line: imperative mood, no period, max 72 chars

## Before Committing
- No files larger than 10MB
- No .env, credentials, secrets, node_modules, build artifacts
- Use `bin/lab-commit.sh <agent> -m "message"` for commits

## Security
- Never commit secrets, tokens, passwords, keys
- Use environment variables or vault for secrets
