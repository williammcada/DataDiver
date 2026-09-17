# Project Brief — DataDiver

**Brief status:** Migration baseline / requires source verification where noted  
**Brief version:** 0.1  
**Last updated:** 18 September 2026  
**Owner:** William McAda  
**Product credit:** A WILLIAM MCADA PRODUCT  
**Handbook repository:** `williammcada/mcada-project-handbook`  
**Handbook baseline:** `6557a45aaa6d29d7d1abde808e6d0ac248b08820 (AI-START-HERE.md); UNIVERSAL-RULES.md @ aed6fe311aa2e88983f862a30a2d8f05d2ffc04d`  
**Repository:** `williammcada/DataDiver`  
**Canonical source status:** TO ESTABLISH from the latest known-good DataDiver application/source.  
**Current project state:** Existing analytics concept/application with established report sections; exact current version and source must be verified.

## 1. Purpose and audience

DataDiver is an institutional assessment-analysis application for overview metrics, item exploration, teacher reports, school reports, method documentation, and formal data-dive reporting.

**Primary audience / operator:** Teachers, instructional leaders, and school administrators analyzing assessment performance.

## 2. Standards selection

**Universal baseline:** U-01 through U-08 where applicable.

**Conditional modules:** S-02 Curriculum/Assessment/Evidence; S-04 Distribution/Deployment as applicable

Apply only the selected modules and project-local requirements. Do not import restrictions from unrelated projects.

## 3. Project-specific requirements

- Preserve distinction between student-level evidence and teacher/school-level aggregation.
- Labels such as Priority, Monitor, Aligned, and Strength must have documented definitions and reproducible logic.
- Item/teacher/school reports must trace back to the underlying assessment data.
- Do not infer individual mastery behavior merely because the ecosystem also includes GradePal.

## 4. Preserve from the current accepted project

- OVERVIEW.
- ITEM EXPLORER.
- TEACHER REPORTS.
- SCHOOL REPORT.
- METHOD.
- DATA DIVE REPORT.
- Priority / Monitor / Aligned / Strength analytical framework where present in the source.

## 5. Relationship to other projects

- Institutional analytics counterpart to GradePal's learner-level model.
- May consume assessment evidence from TestForge/benchmarks in future explicit integrations.

A conceptual relationship is not proof of an implemented integration. Do not invent a shared API, data schema, identity layer, or deployment dependency without an explicit integration task.

## 6. Source and version discipline

The exact current source artifact or repository commit must be identified before a substantive build. If the field above says the source is not yet established, first locate the latest known-good local file/ZIP or existing repository state and record its exact identity here.

For substantial revisions use:

**DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY (when applicable)**

A packaging/export/deployment failure must not force reconstruction of an already verified build.

## 7. Definition of done

| # | Requirement / check | Result | Evidence / limitation |
| ---: | --- | --- | --- |
| 1 | Imported/source assessment data is parsed correctly. | Not run | |
| 2 | Item-level metrics reproduce independently checked calculations. | Not run | |
| 3 | Teacher/school aggregation is correct. | Not run | |
| 4 | Analytical labels follow the documented method. | Not run | |
| 5 | Exported reports match on-screen data and source scope. | Not run | |

Allowed results: **Passed / Failed / Not run / Not applicable**. A "Passed" result requires an actual check against the identified candidate.

## 8. Known issues and migration notes

Do not claim current integrations or production readiness until the actual source and data contracts are established.

## 9. Handoff files

A substantive AI implementation task should retrieve or receive:

1. `AI-START-HERE.md`;
2. `UNIVERSAL-RULES.md`;
3. the relevant sections of `CONDITIONAL-STANDARDS.md`;
4. this project brief;
5. the exact current source artifact/commit;
6. the approved version-specific change specification;
7. applicable assets and deployment configuration.

Do not reconstruct the current implementation from a historical chat summary when the actual source should be available.

## 10. Ownership

**William McAda**  
**A WILLIAM MCADA PRODUCT**
