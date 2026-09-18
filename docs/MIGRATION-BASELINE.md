# Migration Baseline — DataDiver

**Recorded:** 18 September 2026  
**Repository:** `williammcada/DataDiver`  
**Branch:** `main`  
**Source-preservation checkpoint:** `94233db3e9f9f731f59761282a023cf5edda5572`  
**Record status:** Current source identity. This is not by itself a functional-test, release, or deployment claim.

## Canonical source identity

| Field | Value |
| --- | --- |
| Canonical source path | `DataDiver_v15_PolarAquatic_CaptionFix.html` |
| Git blob SHA | `3b78f3f99ddddf2507971c422bec3095379e80e2` |
| Version represented | v15 Polar Aquatic caption-fix source baseline |
| Repository source checkpoint | `94233db3e9f9f731f59761282a023cf5edda5572` |

The checkpoint above identifies the application/planning source immediately before this normalization record was committed. Later documentation-only commits do not change the preserved application bytes.

## Verification status

| Check | Result | Evidence / limitation |
| --- | --- | --- |
| Source exists in the default branch | Passed | Repository paths and Git object identities were read directly on 18 September 2026. |
| Byte-preservation comparison | Passed | Passed — the Git blob matched the preserved Library source during the 18 September 2026 audit. |
| Functional workflow | Not run | Source preservation does not establish that imports, gameplay, reports, storage or exports work. |
| Hosted/running application | Not run | Not verified; DataDiver is preserved as a standalone offline HTML application. |

## Documentation authority

- [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md) records purpose, scope, must-retain behavior and verification requirements.
- [`change-specs/INDEX.md`](change-specs/INDEX.md) identifies approved or directional change records.
- [`MIGRATION-NOTE.md`](MIGRATION-NOTE.md) is retained as historical migration context but its pre-upload source-status language is superseded by this baseline.
- This file controls current source identity when an older brief or note says the source was unknown or “TO ESTABLISH.”

## Next gate

Use the committed v15 source as the canonical preservation baseline and verify the offline analytics/import/report workflow before further revision.

Do not label a future commit a verified release until the exact candidate has passed the project brief’s required verification and that evidence is preserved.
