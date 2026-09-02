# PLT

Tooling and analysis for Pro tenant configuration.

## Repository layout

- `FULL TENANT/` — raw tenant configuration export, one folder per entity with a
  `response.json` payload. Untracked by default; see [Tenant export](#tenant-export).

## Tenant export

The export is about 183 MB across 221 folders. Two payloads approach GitHub's
50 MB per-file warning threshold:

| File | Size |
| --- | --- |
| `FULL TENANT/ProcessModel/response.json` | 49.8 MB |
| `FULL TENANT/BusinessProcess/response.json` | 49.2 MB |

Decide whether to track the export in Git, store it with Git LFS, or keep it local
before you commit it.
