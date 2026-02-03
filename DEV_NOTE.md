# Private Evolver Development Workspace

This is a **private, isolated** copy of the `evolver` skill.
Use this directory for experimental development, refactoring, and testing without affecting the live `skills/evolver` or `skills/feishu-evolver-wrapper`.

## Protocol
1.  **Isolation**: Do not run `npm link` or `openclaw install` from here into the main workspace.
2.  **Safety**: Test changes locally using `node index.js`.
3.  **Sync**: Only manually copy approved changes back to `skills/evolver`.
4.  **Git**: This folder should have its own git history or be ignored by the main repo's `.gitignore` if we want strict separation (or just tracked carefully).

## Current Version
Copied from `skills/evolver` on 2026-02-03.
