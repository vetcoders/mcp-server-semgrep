# Risk Register

Project: `/Users/maciejgad/vc-workspace/VetCoders/mcp-server-semgrep`
Snapshot: `main@0f0a074`

This card collects risk signals and recommended actions for the current context scope.

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
  "risk": {
    "cache_scope": "DirtyWorktree",
    "cache_scope_authority": "repo_verified",
    "dirty_worktree": true,
    "high_fan_in": [],
    "hotspots": [],
    "snapshot_health": "dirty",
    "stale_snapshot": false
  }
}
```

## What this card does not cover

This Risk Register does not include full source content. Use `loct slice`/`loct impact` for exact file-level surgery.
