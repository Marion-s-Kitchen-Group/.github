# Contributing

Applies to every Marion-s-Kitchen-Group repository unless its own README, `AGENTS.md` or `CLAUDE.md` says otherwise. Those files win.

## Branches and pull requests
- The default branch is what runs in production (a Shopify theme synced to the store, a deployed worker or app). Change it only through a pull request.
- Branch names: `feature/<what>`, `fix/<what>`, `chore/<what>`, `claude/<what>` for agent work. Delete the branch once merged.
- One topic per pull request. Say what changed, how it was checked, and how to roll it back.
- CI must pass. Never weaken a check to make it pass.

## Commits
Conventional style: `fix(scope): what changed`, `feat(...)`, `docs(...)`, `chore(...)`, `deps(...)`. The body says why.

## AI agents
- Read the repo's `AGENTS.md` (or `CLAUDE.md`) first; it lists the commands and the rules that must not be broken.
- Never print or commit secrets, never push to the default branch, and never run store writes, deploys or publishes unless the operator asked for them.

## Shopify themes
Theme repos are connected to the store with Shopify's GitHub integration: merging to a connected branch updates that theme. Editor saves arrive as "Update from Shopify" commits; don't revert them.
