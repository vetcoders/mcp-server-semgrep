# Core Map

Project: `/Users/maciejgad/vc-workspace/VetCoders/mcp-server-semgrep`
Snapshot: `main@0f0a074`

This card tells you where you are, what is risky, and what actions are safe next.

```json
{
  "action": {
    "likely_tests": [
      "tests/security.test.ts",
      "tests/stdio-smoke.test.ts"
    ],
    "next_safe_commands": [
      "loct slice AGENTS.md",
      "loct impact AGENTS.md",
      "loct context --file AGENTS.md"
    ],
    "verification_gates": [
      "npm run lint",
      "npm run test",
      "npm run build"
    ]
  },
  "authority": {
    "aicx_agent": [],
    "aicx_failure": [],
    "aicx_operator": [],
    "loctree_derived": [
      "action.likely_tests.tests/security.test.ts",
      "action.likely_tests.tests/stdio-smoke.test.ts",
      "action.next_safe_commands.loct slice AGENTS.md",
      "action.next_safe_commands.loct impact AGENTS.md",
      "action.next_safe_commands.loct context --file AGENTS.md",
      "action.verification_gates.npm run lint",
      "action.verification_gates.npm run test",
      "action.verification_gates.npm run build"
    ],
    "repo_verified": [
      "risk.cache_scope"
    ],
    "semantic_guess": [],
    "stale_or_unknown": []
  },
  "project": {
    "branch": "main",
    "canonical_root": "/Users/maciejgad/vc-workspace/VetCoders/mcp-server-semgrep",
    "commit": "0f0a074",
    "snapshot_id": "main@0f0a074"
  },
  "risk": {
    "cache_scope": "DirtyWorktree",
    "cache_scope_authority": "repo_verified",
    "dirty_worktree": true,
    "high_fan_in": [],
    "hotspots": [],
    "snapshot_health": "dirty",
    "stale_snapshot": false
  },
  "schema_version": "1.0"
}
```

## What this card does not cover

This Core Map does not include dependency consumers, runtime entrypoints, or prior decisions. For code changes, read `01-structural-map.md` next.
