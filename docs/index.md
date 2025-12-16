# Groundstation Documentation

This site captures the baseline for the hybrid rocket groundstation: how it is built, how it is operated, and why it is safe. It is written for operators, maintainers, and reviewers.

## How to use this documentation
- Operators: follow the checklists in `operation/` and the button/indicator reference in `physical-ui/`.
- Engineers: see `hardware/`, `software/`, and `development/` for architecture, build steps, and change control.
- Reviewers: safety intent is captured in `safety/`, with verification in `testing/` and traceability in `appendix/`.

## System snapshot
- Purpose: provide a reliable ground interface for hybrid rocket operations (telemetry, command, abort).
- Platform: single-board computer with hardened I/O, physical UI, and network links to the vehicle and local LAN.
- Safety posture: default-to-safe, human-in-the-loop, with physical dead-man and software interlocks.

## Navigation
- Start with `overview/mission-context.md` for mission framing.
- Keep diagrams current in `diagrams/`; text should reference them directly.
- Track changes in `appendix/revision-history.md` so reviewers can see deltas per release.
