# GoreeCloud Router OS — Changelogs

> **Authority:** Repository-native human-readable change history.  
> **Migration:** Preserves the prior `CHANGELOG.md` content below and adds the Drive feature-authority migration event.

## 2026-09-27 — Drive feature-roadmap migration

- Migrated feature-state authority to `IMPLEMENTED-FEATURES.md`, `PLANNED-FEATURES.md`, and this `CHANGELOGS.md`.
- Preserved the Drive roadmap under `docs/history/drive-feature-roadmap-source-2026-09-27.md` as non-authoritative historical evidence.
- No lifecycle promotion, release acceptance, or production readiness is implied.

## Prior changelog history

# Changelog

This repository changelog records source-level development milestones. The canonical GoreeCloud project changelog is maintained separately in Google Drive.

## Unreleased — Milestone 0

- Established the governed repository baseline.
- Added the unprivileged Reference Build 0.1 configuration/state proof-of-architecture.
- Added deterministic validation, compilation, transaction, verification, and rollback tests.
- Added truthful Platform Contract state with blocked/unaccepted integrations.
- Added an optional atomic, integrity-checked local transaction journal for prepared/applied/retained/rolled-back phase evidence.
- Added sensitive-field refusal for journal persistence and restrictive POSIX journal permissions.
- Added fail-closed interrupted-transaction recovery that accepts only exact desired/previous revisions and preserves corrupt or third-state evidence.
- Added deterministic privacy-safe configuration previews, bounded risk classification, exact previous/desired review tokens, and stale-review refusal before apply.
- Added a Development-only Reference Build 0.1 Linux network-namespace lab scaffold with routed-connectivity smoke testing, host-default-route invariance, and verified teardown requirements.
- Added a bounded Development `LinuxNamespaceExecutionAdapter` restricted to dedicated adapter namespaces and explicit interface allowlists.
- Added complete privileged-plan preflight, structured-argv static LAN configuration, namespace-scoped IPv4 forwarding, absolute tool resolution, and fail-closed refusal for unimplemented backend kinds.
- Added adapter unit coverage and an isolated root CI smoke test that observes static LAN/forwarding state and requires host-route invariance plus namespace teardown.
- Kept the adapter outside the product transaction runtime; WAN DHCP, nftables/NAT, LAN DHCP, management execution, and production privilege/recovery acceptance remain unresolved.
