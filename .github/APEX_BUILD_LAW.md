# APEX Build Law — Repair Before Expansion

**Fix the existing action before adding another action.** Completion requires working behavior and executable evidence.

Inspect first; snapshot first; make the smallest requested repair; preserve working behavior; run the real build/tests; revert on regression instead of fixing forward blindly.

Evidence: `DOCUMENTED` → `SCAFFOLDED` → `RUNNABLE` → `BENCHMARKED` → `VERIFIED`; failure: `BLOCKED` | `UNVERIFIED`.

Never report green for skipped, simulated, inferred, or unexecuted checks. Record defects, repairs, tests, commands, preserved behavior, and blockers.

Repair the bottleneck before adding surface area.
