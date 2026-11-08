# Supervised Kira Production Roles

These role prompts are reusable agent briefs for this production. They are saved as project files because this workspace does not allow creating runtime agent configs under `.codex/agents`. They do not run continuously or submit VideoExpress jobs on their own.

## Roles

1. **ImboniStory** — maps the approved narration to discrete visual beats, keeps claims and fictional RWF examples accurate, and maintains a complete timed shot ledger.
2. **ImboniCharacter** — reviews Kira identity, style, set, props, edges, and motion on actual rendered media; returns PASS, REPAIR, or REJECT per scene.
3. **ImboniCutSentinel** — preserves and times the original Leo narration, checks continuous Kira coverage, assembles the edit, and verifies the exported file before release.

## Supervised sequence

The production operator invokes Story for the shot map, Character for each completed batch, and CutSentinel for assembly and release QA. One operator submits provider jobs and reconciles their receipts. Treat planned scenes, generated outputs, inspected clips, and approved clips as separate states.

## Known production limits

- Current VideoExpress interface provides scene-level generation; no verified 174-shot batch action or unattended render service is available in this project.
- The stickman production guidance records a ten-minute VideoExpress export limit. The current source narration exceeds thirteen minutes, so check the current export controls and use a supported long-form assembly path if the limit still applies.
- Do not re-enable legacy graphics in the final replacement. Keep them hidden in the working project until complete Kira coverage is ready.
