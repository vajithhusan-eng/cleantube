# Changelog

All notable changes to CleanTube, newest first. **None of this is code.** CleanTube is
a plan, and so far the record is a series of documents.

## 2026-10-17 — documentation standard

- Added `README.md`, `docs/README.md` and this changelog, brought `AGENTS.md` and
  `STATE.md` up to the same standard, and added `LICENSE` (MIT).
- Added a CI workflow that **asserts there is still no source code** and that every
  top-level document is indexed in `docs/README.md`. It is a guard, not a test run —
  there is nothing to test yet.
- No design changed. `PLAN.md` is still the sole design document.

## Earlier — the plan, v4

- `PLAN.md` **v4 (source-verified)**, superseding the v1–v3 drafts. Evidence base:
  NewPipeExtractor `@dev`, AdAway's `VpnService` source, Intra's `allowFamily` usage,
  the live Play *Device and Network Abuse* policy, and yt-dlp's PO-Token guide.
- The plan is ~68 KB and, by its own accounting, internally contradictory in twelve
  places. Those contradictions are catalogued in [`STATE.md`](STATE.md) rather than
  papered over — they are the reason milestone **M0 is a kill-gate**.

## Not yet

~11 weeks of work sits behind M0, which is 4–5 days and can end the project. No
milestone has started.
