# NORNR Budget Shield Demo

Minimal public repo that shows one real Budget Shield install:

- baseline repo on `main`
- one demo pull request that introduces a new consequential surface
- one review-first NORNR comment on the PR

Use this repo when you want to show what Budget Shield actually looks like in a real GitHub pull request instead of only reading the action README.

## What this repo proves

- Budget Shield installs in one workflow file
- one local `.nornr-pr-audit.json` keeps the comment narrow
- the pull request receives one calm NORNR review comment before merge
- the output names the likely next NORNR lane instead of only saying "risky"

## Files

- `.github/workflows/nornr-budget-shield.yml`
  - runs the public action on pull requests
- `.nornr-pr-audit.json`
  - narrows the demo comment to the intended consequential surfaces
- `src/runtime.ts`
  - safe baseline file on `main`

## Public proof

- Action repo: https://github.com/NORNR/nornr-budget-shield
- Live demo PR: https://github.com/NORNR/nornr-budget-shield-demo/pull/1
- NORNR explainer: https://nornr.com/pr-comment-audit
