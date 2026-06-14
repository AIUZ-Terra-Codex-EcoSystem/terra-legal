# Terra Legal Stabilization Audit v2 — 2026-06-14

**Trace ID:** `TL-2026-06-14-004`  
**Repository:** `AIUZ-Terra-Codex-EcoSystem/terra-legal`  
**Branch:** `stabilize/terra-legal-licensing-v2`  
**Base commit:** `3fc3422b1209f7650c714ef3310d1c227fed27af`  
**Operator:** Abdurashid Abdulkhamitovich Abdukarimov — ORCID 0009-0000-6394-4912  
**Audit levels:** rights, structural, publication, protocol  
**Status:** prepared for review — not merged

## Operator instruction

Stabilize `terra-legal` as the first repository governed by the portfolio license map and Rule-0-based legal strategy.

## Reconciliation history

The first working branch was created from an older repository state. During preparation, `main` received a parallel partial stabilization that changed overlapping files.

Draft pull request #1 was closed without merge because it was non-mergeable and had been superseded.

This v2 branch was created from the updated `main` commit and reconciles the useful parts of both stabilization paths.

## Sources read

### Repository sources

- `README.md`;
- `LICENSE`;
- `LICENSE.md`;
- `LEGAL.md`;
- `REUSE.toml`;
- `CITATION.cff`;
- `CONTRIBUTING.md`;
- `GOVERNANCE.md`;
- `LINKING-INSTRUCTIONS.md`;
- `REPOSITORY_PROTOCOL.md`;
- `PUBLICATION_RULE.md`;
- `STANDARDS.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `DOCUMENTATION-STANDARD.md`;
- `DOCUMENT_TEMPLATES.md`;
- `TRACELOG.md`;
- `REPOSITORY_LICENSE_MAP.md`;
- `TERRA_LEGAL_FRAMEWORK_STRATEGY.md`;
- `RELICENSING_PROTOCOL.md`;
- Rule 0, Detox, naming, identity, TraceLog, and Invisible Shadow bridge files.

### External primary sources

- Creative Commons Attribution 4.0 International legal code;
- Apache License 2.0;
- SPDX License List and identifiers;
- REUSE Specification for machine-readable file-level licensing.

## Findings before reconciliation

### Blanket wildcard licensing

The partial `main` stabilization assigned:

- all Markdown files to CC BY 4.0;
- all HTML files to CC BY 4.0;
- all CSS and workflow files to Apache-2.0;
- legal drafts to a custom LicenseRef.

This was too broad because historical ownership, copied donor material, standard texts, contributor rights, and third-party components had not yet been cleared file by file.

### Repository-level default ambiguity

`LICENSE` and `LICENSE.md` still described broad default licensing. A mixed repository requires explicit file-level assignment and exclusions.

### Incomplete standard license files

The files under `LICENSES/` were short references, not the complete standard legal texts expected for a machine-readable licensing structure.

### Citation metadata

`CITATION.cff` described the repository as a single CC-BY-4.0 object and contained an unverified release date even though the repository was mixed and stabilization had not been released.

### Incomplete governance and contributor controls

The repository lacked a dedicated contributor-rights instrument. Governance and linking documents still required stronger separation among licensing, policy, certification, partnership, and official status.

### Documentation residue

The documentation standard and templates still contained automatic Terra Public License assumptions, unsupported fixed requirements, and speculative implementation or certification patterns.

## Stabilization architecture

The reconciled branch establishes:

1. no single blanket repository license;
2. explicit file-level assignment through SPDX, adjacent `.license` files, `REUSE.toml`, directory notices, or file notices;
3. CC BY 4.0 only for explicitly classified, rights-cleared original documentary material;
4. Apache-2.0 only for explicitly classified, rights-cleared original implementation material;
5. full standard license texts under `LICENSES/`;
6. preservation of earlier grants and historical version boundaries;
7. Terra Public License retained as a draft, not the active repository license;
8. separate Responsible Use, trademark, contributor, third-party, privacy, and commercial layers;
9. no automatic license inheritance, certification, partnership, or official status through linking;
10. reviewable governance, validation, audit, publication, documentation, and template rules.

## Files created

- `CONTRIBUTOR_TERMS.md`;
- `NOTICE`;
- `traces/TL-2026-06-14-004.md`;
- this audit record.

## Files updated

- `LEGAL.md`;
- `LICENSE`;
- `LICENSE.md`;
- `LICENSES/CC-BY-4.0.txt`;
- `LICENSES/Apache-2.0.txt`;
- `REUSE.toml`;
- `CITATION.cff`;
- `README.md`;
- `LIVING_INDEX.md`;
- `CHANGELOG.md`;
- `CONTRIBUTING.md`;
- `GOVERNANCE.md`;
- `LINKING-INSTRUCTIONS.md`;
- `REPOSITORY_PROTOCOL.md`;
- `PUBLICATION_RULE.md`;
- `STANDARDS.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `DOCUMENTATION-STANDARD.md`;
- `DOCUMENT_TEMPLATES.md`;
- `index.html`.

## Detox record

### Before

Passed.

No blanket license decision was accepted without reading the current repository state, portfolio strategy, rights protocol, and official standard-license sources.

### During

Passed with containment.

- all changes remained on a dedicated branch;
- no history was rewritten;
- no earlier public grant was described as withdrawn;
- no wildcard license was applied to all historical files;
- third-party, donor, archived, and rights-unresolved material was excluded from automatic licensing;
- standard legal texts were reproduced without Terra-specific additions;
- the Universal Convention and Responsible Use Policy were not added as hidden restrictions to CC BY 4.0 or Apache-2.0;
- no trademark registration, legal compliance, certification, or partnership was inferred from repository documents;
- no unverified DOI or release date was retained.

### After

Passed for the prepared branch, subject to unresolved conditions.

## Validation results

### Legal and licensing coherence

**Prepared for review.**

- root notice, `LEGAL.md`, `LICENSE.md`, and `REUSE.toml` now use explicit file-level scope;
- full CC BY 4.0 and Apache-2.0 texts are present;
- historical files are not silently relicensed;
- Terra Public License remains a draft;
- earlier grants are preserved as historical facts.

### Metadata coherence

**Prepared for review.**

`CITATION.cff` no longer contains a false single-license field, unverified release date, or placeholder DOI.

### Contributor and governance coherence

**Prepared for review.**

Contributor certification, attribution, AI-assistance responsibility, protected legal review, decision classes, conflict disclosure, and emergency safety processes are defined.

### Linking and endorsement boundary

**Pass for branch content.**

Linking no longer applies a license automatically or creates official status, certification, partnership, endorsement, or rights transfer.

### Documentation and templates

**Pass with future implementation review.**

Automatic custom-license assumptions and speculative metrics were removed. Templates now require evidence, status, rights, provenance, Detox, validation, audit, and trace.

### Public page

**Pass for branch content.**

The page uses the shared stylesheet and exposes the file-scoped licensing, governance, responsible-use, and linking boundaries.

## Unresolved conditions

- complete historical file-by-file rights and provenance classification;
- contributor and commit-history review beyond currently visible records;
- dependency, workflow, GitHub Action, template, icon, font, media, and donor-material audit;
- verification of earlier releases, downloadable bundles, Zenodo deposits, and historical license metadata;
- documentary confirmation before the Fractal Metascience Foundation is identified as a legal rights holder rather than an affiliation or project identity;
- jurisdiction-specific legal review for trademarks, privacy, child data, commercial terms, governing law, warranties, liability, and dispute resolution;
- multilingual legal companion versions only after the English controlling structure is approved.

## Audit conclusion

**Status: prepared for review — not merged.**

The reconciled branch materially stabilizes repository licensing, governance, contribution, responsible-use, trademark, publication, validation, audit, documentation, templates, metadata, and public presentation without claiming complete historical rights clearance.

Merge should occur only after branch comparison confirms no new divergence from `main`, a draft pull request is reviewed, and the remaining limitations remain visible.
