# Hospital BI Dashboard — AI Instructions

# Project AI Instructions

Read the canonical rules in BehnamFekri/Beni-Repository-HUB/AGENTS.md and docs/ai-workflow.md before editing. This repository remains the source of truth for its own code and technical documentation.

## Required workflow
1. Sync and inspect the latest default branch, README, project docs, existing tests, and open PRs.
2. Create a dedicated task branch from the latest default branch. Never edit main directly.
3. Understand the current architecture and data contracts before changing files.
4. Make a small, reversible change; back up before destructive or schema-changing work.
5. Run relevant tests, static checks, and builds. Report only checks actually executed.
6. Review the complete diff for secrets, data exposure, accidental deletions, and unrelated changes.
7. Update docs/changelog/status as appropriate, commit to the task branch, and open a PR when useful.
8. Do not merge, release stable, or publish publicly without explicit user approval.

## Security and privacy
- Keep repositories and update channels private by default.
- Never commit credentials, tokens, API keys, private keys, environment files, connection strings, production dumps, or real user/patient data.
- Use sanitized examples and synthetic datasets.
- Graphify must exclude secrets, personal identifiers, health/patient data, production data, binaries, build outputs, caches, and vendored dependencies.
- Do not add external services, telemetry, background jobs, or network access without a clear requirement and user approval.

## Handoff
Report branch, commit/PR, files changed, actual test/build results, limitations, and next action. If a tool or runtime prevents testing, state the blocker; do not imply that tests passed.

## BI data safeguards
- Never commit real patient/user data, production exports, credentials, or private connection details.
- Use synthetic/anonymized samples and document metric definitions, grain, filters, and refresh assumptions.
- Validate KPI calculations against documented definitions before changing dashboards.
- Keep data model changes backward-compatible where possible and document migration/refresh impacts.
