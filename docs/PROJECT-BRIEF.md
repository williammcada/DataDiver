# Project Brief — DataDiver

**Brief version:** 0.3 — source-baseline normalization  
**Owner:** William McAda · **Credit:** A WILLIAM MCADA PRODUCT  
**Status:** Canonical source identity reconciled; release, functional and deployment verification remain separately stated.  
**Repository:** `williammcada/DataDiver`, branch `main`.  
**Current running version:** Not independently verified. Exact committed v15 source identity and byte preservation are established.  
**Source/baseline:** Canonical preserved source: `DataDiver_v15_PolarAquatic_CaptionFix.html`, Git blob `3b78f3f99ddddf2507971c422bec3095379e80e2`, at source checkpoint `94233db3e9f9f731f59761282a023cf5edda5572`.  
**Next work:** Use the committed v15 source as the canonical preservation baseline and verify the offline analytics/import/report workflow before further revision.  

## 1. Purpose, audience and detailed scope

- Local browser-only benchmark analytics for teacher data dives; no installation or required internet. Import GradeCam workbooks and retain data provenance.
- Preserve OVERVIEW, ITEM EXPLORER, TEACHER REPORTS, SCHOOL REPORT, METHOD and DATA DIVE REPORT.
- Teacher comparisons use the rest of school; school comparisons use the rest of network, avoiding inclusion of the target in its comparator.
- Normalize item performance to 0–100%; reconstruct item means/variance from response counts. Preserve two-sided Welch testing and Benjamini–Hochberg FDR, recorded default q<.05.
- Recorded interpretation: Same range for gaps under five points; Unclear for larger nonsignificant gaps. Preserve Priority/Monitor/Aligned/Strength definitions as implemented, but do not infer their thresholds from names alone.
- Explain denominators, missing/small-sample behavior, test assumptions and multiple-comparison family. Keep raw difference, significance and instructional interpretation distinct.
- Retain teacher/school/network reports, item statistics, reteach reports and supported PDF/print/XLSX outputs with branding; verify exact menu against canonical source.
- DataDiver is institutional analytics, not GradePal's individual persistent learner model; no automatic ecosystem integration.

## 2. This task and boundaries

This normalization establishes the exact repository source path, Git object identity and source-preservation checkpoint; creates the linked migration baseline; and retires stale pre-upload source-status wording. It does not change application behavior, approve new features, rerun product tests or convert source preservation into a release claim.

## 3. Standards and adoption

[Canonical handbook](https://github.com/williammcada/mcada-project-handbook). File blob revisions consulted: AI-START-HERE.md 6557a45aaa6d29d7d1abde808e6d0ac248b08820; UNIVERSAL-RULES.md aed6fe311aa2e88983f862a30a2d8f05d2ffc04d; CONDITIONAL-STANDARDS.md dad2d3a05ca0f18260196ea51ac6351bffffdc1c; PROJECT-TEMPLATE.md 574f4c6fcf19ecc2f9e27582fd856fb08123e8da. These are file blobs, not repository commit SHAs.

Relevant rules: U-01 identity, U-02 help, U-03 input validation, U-04 unambiguous math/text where applicable, U-05 reader/device, U-06 preservation, U-07 verification, U-08 local scope. Conditional selection: S-02, S-04.
Baseline adoption: selected for this documentation task within existing user instructions. Handbook still labels shared scope/modules seeded/draft; no new global rule ratification is inferred. Project-specific approved decisions control their own scope.

## 4. Must-retain behavior

The detailed scope above is the feature-preservation inventory. Preserve existing settings, data, accepted content, assets, exports and compatibility confirmed in source. Distinguish implemented behavior, accepted pending changes and historical requests during intake. A missing entry in this brief is not authorization to remove working behavior. Preserve valid user work during migrations and failures.

## 5. Source, release and deployment discipline

Canonical preserved source: `DataDiver_v15_PolarAquatic_CaptionFix.html`, Git blob `3b78f3f99ddddf2507971c422bec3095379e80e2`, at source checkpoint `94233db3e9f9f731f59761282a023cf5edda5572`.

See [`MIGRATION-BASELINE.md`](MIGRATION-BASELINE.md) for the authoritative source manifest and the checks actually performed.

DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY.

Use “implementation checkpoint” or “release candidate” before verification. Preserve candidate bytes and logs before packaging; recover that checkpoint after a ZIP/upload failure. Do not rebuild a verified implementation to fix delivery. Repository upload and website deployment are different operations.

## 6. Known issues, conflicts and open evidence

The canonical preserved file is now identified as `DataDiver_v15_PolarAquatic_CaptionFix.html`. Statistical thresholds and label mappings still require exact-source inspection and functional testing; source selection does not establish production readiness.

| Conflict or risk | Required handling |
| --- | --- |
| Historical claim versus current source | Inspect exact source; keep historical claim labeled until verified. |
| Proposed next scope versus working baseline | Use the approved version-specific specification; do not silently promote proposals. |
| Other project rules | Do not import AAC quotas, other-game retry counts, or a shared backend without explicit scope. |
| Handbook proposals | No additional exception or proposal is adopted by this brief. |

## 7. Verification contract

Reconcile counts and normalized scores by hand; verify leave-target-out comparison groups, Welch/FDR results, edge samples, label boundaries and exported reports without student-data transmission.

| Evidence required | Result in this task |
| --- | --- |
| Exact source candidate/commit identified and preserved | Passed — canonical path and source checkpoint recorded in `docs/MIGRATION-BASELINE.md`; no functional verification inferred |
| Project-specific checks above, with inputs and expected/actual results | Not run |
| Save/import/export and malformed-input regression | Not run |
| Intended devices and real deployment path, where applicable | Not run |
| Version, release notes and delivered bytes agree | Not run |

The next build report must name the candidate, environment and test results; historical reports of passing tests do not transfer to a changed candidate.

## 8. Handoff and provenance

Current source identity is recorded in [`MIGRATION-BASELINE.md`](MIGRATION-BASELINE.md). That manifest supersedes earlier unknown-source or pre-upload statements while preserving the original migration note as history.

Required project records: committed `DataDiver_v15_PolarAquatic_CaptionFix.html`; synthetic GradeCam fixtures; method/report definitions; any earlier candidates retained only as explicitly historical records.

Provenance: previous migration brief and project-history audit in this conversation; directly read dossier/proposal where explicitly stated above. Records not explicitly marked read here are retrieval targets, not claims of fresh inspection. No current app code was tested for this brief.

Before substantive implementation retrieve these records, the current source, approved change spec and applicable handbook. If an indispensable spec is inaccessible, report the gap instead of filling it with invented details. Do not delete unique historical chats/assets until their contents are independently preserved.

## 9. Ecosystem boundary

Shared principles do not establish shared code, accounts or interfaces. MathQuest is engagement, TestForge assessment design, GradePal learner-level evidence, and DataDiver institutional analytics. Integration remains separately specified unless confirmed in source. Other projects remain independent unless their brief explicitly says otherwise.
