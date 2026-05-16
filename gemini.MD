# Project Overview

Fledgling is a browser game (Phaser + TypeScript + Vite) where each run procedurally generates a new language and uses that language in gameplay dialogue.

## Development Commands

- Install dependencies: `npm install`
- Run local dev server: `npm run dev`
- Typecheck + production build: `npm run build`
- Typecheck only: `npm run typecheck`
- Run tests: `npm run test`

## Repository Layout

- `src/scenes/` — Phaser scenes
- `src/lang/` — language generation and frame encode/decode systems
- `src/sim/` — dialogue trees, NPC behavior, gameplay simulation data
- `src/voice/` — ElevenLabs and Gemini live voice integrations
- `src/integration/` — Convex integrations
- `convex/` — backend schema, queries, mutations, world tick loop
- `api/` — serverless API routes for token minting

## Working Conventions

- Keep changes focused and minimal.
- Prefer existing scripts and tooling in `package.json`.
- Validate changes with `npm run test` and `npm run build`.
- Avoid introducing new dependencies unless required.
