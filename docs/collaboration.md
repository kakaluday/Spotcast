# Collaboration Workflow

## Branches
- `main`: approved, stable work.
- `feature/<short-description>`: new features.
- `content/<short-description>`: editorial changes.
- `fix/<short-description>`: fixes.

## Pull requests
1. Create a branch from current `main`.
2. Commit a focused change.
3. Open a PR explaining purpose, screenshots/preview and testing.
4. Request review from the other collaborator.
5. Merge only after checks and approval.

## Mobile workflow
Use GitHub mobile to review issues, PRs and comments; use deployment preview URLs to inspect mobile layouts.

## Safety
Do not commit secrets, customer data or private agreements. Keep sensitive settings in the deployment provider's secret store. Add branch protection, required checks and collaborator permissions in GitHub settings when available.

## Decisions
Record significant architectural and brand decisions in `docs/` through reviewed PRs.
