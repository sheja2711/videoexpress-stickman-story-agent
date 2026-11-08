---
name: imboni-kira-longform
description: Plan, generate, align, and review long-form Imboni Money Architecture videos using the approved Kira 2D stickman, existing narration, and VideoExpress. Use when creating or replacing Kira footage for cash-flow documentaries or other approved Imboni long-form productions.
---

# Imboni Kira Longform Production

## Run contract

- Read the project production OS, current checkpoint, approved script, shot ledger, and saved VideoExpress project before work.
- Preserve the current approved narration, voice, aspect ratio, story, and channel. For this cash-flow film, keep the original four Leo Crawford narration clips and Landscape 16:9.
- Preserve the previous export and edit as source material. Work in the named Kira rebuild project.
- Use the confirmed Kira design and stable sets in `KIRA_CONTINUITY.md`; record exact reference asset IDs and actual settings observed in VideoExpress.
- Keep public gallery sharing off. Use only controls visible in the current interface. Do not invent provider APIs or claim a background worker exists.

## Storyboard and timing

- Use the actual narration duration and word/cue boundaries. The ledger may be preplanned to a provisional duration, but must be recalculated against measured audio before final assembly.
- For long narrations, plan approximately one 5-second visual beat per renderable clip unless the current VideoExpress controls support a verified alternative. Short footage must not be stretched into a false full-length replacement.
- Write prompts as one observable action with an incoming pose, prop state, camera plan, and outgoing handoff. Avoid asking generated imagery to render legible text or financial arithmetic; place verified labels and figures in the editor.
- Generate a small number of proof scenes before scaling. Check provider job state before retries and record job/output IDs, setting receipts, and rejected results.

## Render and assembly gates

1. Lock the script, audio, visual bible, shot map, and duration target.
2. Generate and inspect stills before rendering each clip.
3. Use the Kira reference when the UI binds it. If unavailable, apply the approved identity description and mark reference-lock unverified.
4. Review actual clips for character count, identity, wardrobe, object states, composition, hands, edge artifacts, ghosting, camera, duration, audio, and transitions. Reject or repair a failed shot before assembly.
5. Assemble Kira footage in story order; preserve the original narration and align visual cuts to measured audio cues. Keep the original graphic layer hidden for the replacement cut, but preserve the source project until the new cut passes QA.
6. Verify the full timeline reaches past the narration endpoint. Investigate any VideoExpress export cap; do not label a capped render as the complete film.
7. Export only after continuous Kira coverage exists. Play the actual exported file at the beginning, middle, end, and through the full timeline when feasible; verify runtime, audio, and file integrity. Mark release PASS, FAIL, or UNVERIFIED with evidence.

## Supervised agent roles

Use the role contracts in `AGENTS_README.md` for independent storyboard, continuity, and edit/QA passes. Roles do not imply unattended provider execution. A single operator submits provider jobs and reconciles each receipt.

## Current production files

- `PRODUCTION_STATUS.md` — latest verified checkpoint.
- `SHOTS.csv` — full replacement shot plan; planned rows are not proof of generated footage.
- The approved creator package and original narration remain in the production workspace.
- `AGENTS_README.md` — three supervised role prompts.
