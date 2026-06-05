# Loctree Context Atlas

Project: `/Users/maciejgad/vc-workspace/VetCoders/mcp-server-semgrep`
Snapshot: `main@0f0a074`
Generated: `2026-05-23T00:50:42.343179Z`

This atlas is precomputed repository understanding. It contains the repo map an agent would otherwise have to rediscover manually through search/open cycles.

Tokens are cheaper than wrong assumptions.

## Recommended Reading Path

| Step | File | Lines | Why read it | Saves you from |
|---:|---|---:|---|---|
| 0 | `00-core-map.md` | 67 | Repo identity, current risk, authority labels, safe next commands. | wrong project state, stale assumptions, unsafe first actions |
| 1 | `01-structural-map.md` | 20 | Files, symbols, imports, consumers, entrypoints; read before edits/refactors. | missed consumers, wrong impact, blind dependency edits |
| 2 | `02-runtime-map.md` | 22 | Runtime behavior, framework hints, env contracts, reachability. | wrong tests, hidden runtime coupling, config mistakes |
| 3 | `03-memory-trail.md` | 17 | Prior decisions, outcomes, tasks, and AICX continuity when available. | repeated work, forgotten decisions, reimplemented tasks |
| 4 | `04-verification-gates.md` | 33 | Commands and likely tests most relevant to validate changes. | wrong validation path, skipped downstream checks, false confidence |
| 5 | `05-risk-register.md` | 60 | Hotspots, cache/snapshot health, stale assumptions, next risk-reducing actions. | release blockers, high fan-in surprises, stale-cache decisions |

## Completeness

Current reading state: `0/6` context cards read.
A broad repo-level answer is incomplete until at least `00-core-map.md`, `01-structural-map.md`, and `02-runtime-map.md` have been read.
