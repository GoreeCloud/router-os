# Historical Drive Feature Roadmap Migration Source — GoreeCloud Router OS

> **Status:** Historical, non-authoritative migration evidence.  
> **Source:** Former Google Drive roadmap, captured during repository migration on 2026-09-27.  
> **Rule:** Do not synchronize this file with Google Drive and do not use historical authority statements below as current governance. Current feature truth is in `IMPLEMENTED-FEATURES.md`, `PLANNED-FEATURES.md`, and `CHANGELOGS.md`.

GoreeCloud Router OS
Feature Roadmap
Status Integrity
This roadmap records repository implementation and future feature obligations. It does not represent GoreeCloud Router OS as released, deployed, production-qualified, or Stable. Prototype work remains Development unless separate acceptance evidence establishes otherwise.
Current Roadmap
Immediate Development Gate and Synchronization
Reference Build 0.1 must remain a development artifact until routing, firewall, NAT, DHCP, configuration transaction, rollback, recovery, and management-safety behavior pass applicable automated and virtual-machine acceptance tests.
The privileged adapter remains deliberately incomplete. It may execute only its accepted namespace-scoped static-LAN and IPv4-forwarding subset. The complete compiled Reference Build plan must continue to fail closed until WAN DHCP, firewall/NAT, LAN DHCP, and management operations have accepted backends and observed-state/recovery behavior.
Deployment method must not create divergent Router OS products. Docker, Podman, GoreeCloud Containers, Proxmox VM, generic VM, bare-metal, cloud, system-container, and later qualified targets must reuse the canonical configuration/state/API/administration/recovery contracts. A target may be advertised as Supported only after its required environment capabilities and shared cross-environment acceptance suite pass. Missing required kernel, networking, storage, or security capabilities must fail closed rather than silently downgrade Router OS behavior.
Synchronization: Keep this central roadmap materially synchronized with repository FEATURE-ROADMAP.md and the canonical Router OS project specification.
Status
Development roadmap
Product lifecycle
Proposed
Repository
GoreeCloud/goreecloud-router-os
Synchronized source
FEATURE-ROADMAP.md on main
Priority
Work item
Lifecycle
Implementation
Verification
P0
Milestone 0 configuration/state model
Development
Prototype implemented
Unit tests included
P0
Deterministic configuration compiler
Development
Abstract-plan prototype implemented
Unit tests included
P0
Safe configuration preview and review/apply consistency
Development
Privacy-safe deterministic preview and exact previous/desired review token implemented
PR #5 CI passed: 32 unit tests and reference-config validation; production management-lockout recovery not verified
P0
Transactional apply/verify/rollback
Development
Prototype includes atomic local journal and interrupted-state reconciliation
Automated rollback/journal/recovery tests included; production recovery not verified
P0
Repository governance baseline
Development
Implemented on main
PR #1 CI passed and merged
P0
Reference Build 0.1 virtual network lab
Development
Isolated Linux namespace/veth topology scaffold and routed smoke test implemented
PR #6 CI passed: 38 unit tests, reference-config validation, routed ping with 0% packet loss, host default route unchanged, and generated namespaces removed; product routing/firewall/NAT/DHCP acceptance remains unverified
P0
Privileged Linux execution adapter
Development
Namespace-only adapter implements complete preflight, allowlisted static-LAN execution, and namespace-scoped IPv4 forwarding; full Reference Build plan fails closed while required backends are absent
PR #8 exact-head CI passed: 48 unit tests, reference-config validation, routed namespace lab with 0% packet loss/unchanged host default route/clean teardown, and privileged-adapter smoke with static LAN plus IPv4 forwarding observed, unchanged host default route, and namespace removal; production privilege model and full Reference Build execution remain unverified
P0
nftables firewall/NAT backend
Planned
Not implemented
Not verified
P0
LAN DHCP backend
Planned
Not implemented
Not verified
P0
Local authenticated management API
Planned
Not implemented
Not verified
P1
Multi-environment deployment portability and installation profiles
Planned
Deployment portability contract defined for Proxmox VM, generic VM, Docker, Podman, GoreeCloud Containers, bare metal, and additional qualified targets; install artifacts/adapters are not implemented
No install profile is accepted yet; each claimed profile must pass the shared capability, network-safety, routing/firewall/NAT/DHCP, transaction/recovery, upgrade/rollback, backup/restore/migration, diagnostics, performance, and platform-conformance matrix
P1
Minimal Glaze UI administration surface
Planned
Not implemented
Not verified
P1
Everkeep-backed durable snapshots/recovery
Planned
Local journal/recovery proof only; Everkeep not integrated
Not accepted or production-verified
P1
Privacy Shield authorization/retention enforcement
Planned
Not implemented
Not verified
P1
Wardveil evidence and security-state integration
Planned
Not implemented
Not verified
P1
Network/Conduit and Beacon integration contracts
Planned
Not implemented
Not verified
P2
VLANs, policy routing, multi-WAN, SQM
Planned
Not implemented
Not verified
P2
Wi-Fi and travel-router hardware workflows
Planned
Not implemented
Not verified
P3
IDS/IPS, dynamic routing, extensions, HA
Future
Not implemented
Not verified