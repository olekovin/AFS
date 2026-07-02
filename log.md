# AFS — Change Log

> Append-only. Never edit past entries — only add new ones at the bottom.
> Template: Intent / Reason / Impact / Gate / Rollback / Status.

## 2026-07-02 — Scaffold rollout (TODO.md + log.md)

- **Intent:** Bring this repo up to the workspace scaffold convention — `TODO.md` (living) +
  `log.md` (append-only), per K2O Standardization Master Plan v2.
- **Reason:** Workspace-wide compliance audit found `TODO.md`/`log.md` present in only a
  minority of repos; this repo is one of several rolled out after the canary
  (`k2o-minecraft-servers-lol`).
- **Impact:** Adds `TODO.md` and `log.md` only. No other files touched.
- **Gate:** 🟢 docs-only, no infra touched.
- **Rollback:** `git rm TODO.md log.md`.
- **Status:** done.
