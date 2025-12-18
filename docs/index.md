<div class="gs-hero">
  <div class="gs-hero__mark">
    <img src="assets/images/gs-mark.png" alt="Groundstation mark">
  </div>
  <div class="gs-hero__body">
    <p class="gs-hero__eyebrow">Hybrid Rocket Groundstation</p>
    <h1>Ops-first, safety-forward documentation</h1>
    <p class="gs-hero__lede">
      Everything needed to build, operate, and review the groundstation:
      architecture, procedures, safety intent, and verification.
    </p>
    <div class="gs-hero__tags">
      <span>Operators</span>
      <span>Engineers</span>
      <span>Reviewers</span>
    </div>
  </div>
</div>

## How to use this site
- Operators: go to `operation/` for checklists and to `physical-ui/` for button/indicator mappings.
- Engineers: `hardware/`, `software/`, and `development/` capture architecture, build steps, and change control.
- Reviewers: `safety/` sets intent; `testing/` and `appendix/` carry evidence and traceability.

## System snapshot
- Purpose: provide a reliable ground interface for hybrid rocket operations (telemetry, command, abort).
- Platform: single-board computer with hardened I/O, physical UI, and network links to the vehicle and local LAN.
- Safety posture: default-to-safe, human-in-the-loop, with physical dead-man and software interlocks.

## Navigation hints
- Start with `overview/mission-context.md` for mission framing.
- Keep diagrams current in `diagrams/`; text should reference them directly.
- Track changes in `appendix/revision-history.md` so reviewers can see deltas per release.
