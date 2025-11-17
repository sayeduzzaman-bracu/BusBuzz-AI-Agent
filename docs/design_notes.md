# Design Notes

## Purpose
Document the architecture and reasoning design choices behind BusBuzz.

## Architecture
- Single **system prompt** defines core behavior.
- Modular prompt documents for maintainability (negotiation, complaints, emergencies).
- Flow docs represent deterministic conversation flows for quality assurance.
- Examples demonstrate expected bot replies for training and evaluation.

## Privacy & Safety
- Never transmit raw PII to operators; use masked contact tokens.
- Escalate any unethical provider instructions to service team immediately.
- Keep responses concise and avoid legal/medical promises.

## Versioning
- Update prompt files and flows when policy or operator rules change.
- Tag releases with `vX.Y` when major policy updates occur.
