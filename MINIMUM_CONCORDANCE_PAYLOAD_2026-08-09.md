# Fractalish / FSS Concordance — Minimum Payload — 2026-08-09

This is a conservative intake delta for four workstreams the project owner has designated as mandatory concordance and rolling-work-queue entries. Missing authority is preserved as an explicit gap rather than inferred.

## Fractalish Constitution

- Function: program-level governance constitution defining durable principles, authority boundaries, decision rules, and constraints for Fractalish research/build activity.
- Classification: **WORKING GOVERNANCE CONSTITUTION / CANONICAL CANDIDATE**.
- Controlling evidence for this intake: `BonAcqui-LLC/fractalish`, `CONSTITUTION.md` v0.1 dated 2026-08-09, merged to `main` in commit `41ea6aa664c2b390757bae5de6db5ccb3ef3382b` via PR `https://github.com/BonAcqui-LLC/fractalish/pull/12`.
- Live public URLs:
  - `https://fractalish.com/constitution`
  - `https://fractalish.com/constitution.html`
  - `https://fractalish.com/`
- Deployment evidence: Cloudflare Pages production deployment `https://07f91bfa.fractalish.pages.dev`, source `eed3191`, verified after clean Git-clone deploy. The Constitution content baseline was introduced in `41ea6aa`; `eed31915da9732bdc4c34acfd715d74a244e0cbb` adds the post-release live-validator correction.
- Evidence boundary: this closes the missing-artifact portion of GAP-015 for Constitution v0.1 intake only. Future amendments, steward ratification, version promotion, and downstream implementation consequences must remain separately tracked.
- Required closure: preserve amendment history and reconcile any later Constitution revisions against this v0.1 baseline before treating them as controlling.
- Gap: **GAP-015 — Canonical authority package — pointed to Constitution v0.1 baseline**.

## R2R / Research-to-Runtime Promotion Engine

- Function: governed paper-to-mechanism-to-test-to-promotion engine for rapid literature assimilation with receipts, gates, trust boundaries, and reversible promotion.
- Controlling evidence for this intake: `BonAcqui-LLC/fractalish-r2r-engine`, branch `harden/r2r-v0.1.3-trust-anchor`, commit `729b95844cefd3b5702de6f9c4428fbaf839e444`; frozen v0.1.2 baseline `f8948e93ad71c47919c5c760629b4b81cd4241a1` remains preserved.
- Classification: **BUILT_LOCAL / HARDENED PROMOTION ENGINE; PRODUCTION BOOTSTRAP HOLD**.
- Evidence boundary: v0.1.3 adds TEST/DEVELOPMENT/PRODUCTION trust-anchor resolution, external production trust root, control-plane snapshots, durable approval consumption, and engine commit pinning. Production readiness still depends on actual human external trust-anchor/signer bootstrap.
- Required closure: reconcile post-v0.1.3 advances, verify frozen baseline and trust-bootstrap state, then track Candidate 001 only through the declared gate sequence.
- Gap: **GAP-016 — Production trust bootstrap**.

## Anti-Illogical

- Function: research-grounded public build/site translating Anti-Illogical project work into navigable project pages, security material, and an AI-assisted public interface.
- Controlling evidence for this intake: `persistentiterations/anti-illogical`, latest indexed commit `ee09e52ae3d7f6c122c764d125e879df5ff9c9d2` (2026-08-07).
- Classification: **ACTIVE PUBLIC SITE / RESEARCH-GROUNDED BUILD; CONTINUOUS CLAIM REVIEW REQUIRED**.
- Captured repository advances: initial website v0.1; Cloudflare AI Assistant; research-source grounding; Security Insights and Swarm Security additions; editor-note removal; dynamic-route fix and regeneration of project pages.
- Evidence boundary: site functionality/publication polish do not validate scientific or security claims by themselves; source-to-page lineage must remain auditable.
- Required closure: ingest current project/site updates, audit claim lineage, verify routes/content, and establish a repeatable update/review cadence.
- Gap: **GAP-017 — Public-site/source synchronization**.

## ValufAI / valufai.com

- Function: active product/site build tracked as a distinct project workstream.
- Classification: **ACTIVE BUILD / CURRENT AUTHORITY NOT YET RECONCILED**.
- Evidence boundary: the project owner identifies valufai.com and ongoing updates as current work. No repository named `valufai` is visible in the currently connected GitHub inventory, so architecture, deployment state, claims, and repository authority are not inferred.
- Required closure: locate the current valufai.com repo/build source, ingest latest update history, define scope/authority/status, and establish a bounded next-action plan.
- Gap: **GAP-018 — Repository / authority reconciliation**.

## Work-queue relationship

These are mandatory tracked lanes, not an instruction to make all four ACTIVE simultaneously. Scientific/evidentiary state lives in the concordance; attention state lives in the rolling work queue. The existing WIP-limit and displacement rules remain in force.
