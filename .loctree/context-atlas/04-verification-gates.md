# Verification Gates

Project: `/Users/maciejgad/vc-workspace/VetCoders/mcp-server-semgrep`
Snapshot: `main@0f0a074`

This card lists likely verification commands and tests derived from the current context.

```json
{
  "likely_tests": [
    "tests/security.test.ts",
    "tests/stdio-smoke.test.ts"
  ],
  "next_safe_commands": [
    "loct slice AGENTS.md",
    "loct impact AGENTS.md",
    "loct context --file AGENTS.md"
  ],
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

This Verification Gates card does not prove correctness by itself. Run the commands before release or submit.
