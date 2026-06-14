# Pull Request 2 Merge-Readiness Audit — 2026-06-14

**Trace ID:** `TL-2026-06-14-006`  
**Repository:** `AIUZ-Terra-Codex-EcoSystem/terra-legal`  
**Pull request:** #2  
**Branch:** `stabilize/terra-legal-licensing-v2`  
**Base branch:** `main`  
**Base commit:** `3fc3422b1209f7650c714ef3310d1c227fed27af`  
**Reviewed branch state before this audit record:** `d53a1add7cf3972e51447e1d599aa1f51e0b32d5`  
**Operator:** Abdurashid Abdulkhamitovich Abdukarimov — ORCID 0009-0000-6394-4912  
**Audit levels:** rights, structural, publication, protocol, merge readiness  
**Status:** improved and technically coherent; protected legal decision still pending

## Instruction

Continue the Rule 0 review of PR #2 after PR #3 was reconciled and closed without merge.

## Sources reviewed

### Pull-request and branch state

- PR #2 metadata, changed-file list, and current branch content;
- comparison of `main` with `stabilize/terra-legal-licensing-v2`;
- Terra Legal Audit workflow and its latest successful run before this review;
- PR #2 review checklist, audit, and TraceLog records.

### Controlling repository surfaces

- `LEGAL.md`;
- `LICENSE`;
- `LICENSE.md`;
- `REUSE.toml`;
- `CITATION.cff`;
- `CONTRIBUTOR_TERMS.md`;
- `CONTRIBUTING.md`;
- `GOVERNANCE.md`;
- `PUBLICATION_RULE.md`;
- `THIRD_PARTY_NOTICES.md`;
- `README.md`;
- `index.html`;
- `TRACELOG.md`;
- `traces/TL-2026-06-14-004.md`;
- `traces/TL-2026-06-14-005.md`;
- `audits/2026-06-14-terra-legal-stabilization-v2.md`;
- `audits/2026-06-14-pr3-rule0-reconciliation.md`.

### External primary sources

- Creative Commons Attribution 4.0 International Legal Code and official plain-text form;
- Apache License, Version 2.0 official text.

The standard license files were reviewed for the expected complete sections and absence of Terra-specific restrictions. This audit does not claim byte-for-byte identity across differently formatted official representations.

## Branch comparison

At the recorded comparison:

- branch status: ahead of `main`;
- ahead: 73 commits;
- behind: 0 commits;
- merge base: `3fc3422b1209f7650c714ef3310d1c227fed27af`.

No parallel `main` divergence was detected at that point. A fresh comparison is still required immediately before merge.

## Findings and repairs

### 1. Obsolete pre-PR marker

`PR2_NOT_OPENED.md` remained in the branch even though PR #2 was already open. Its presence contradicted the pull-request description and publication rule against temporary machine residue.

**Repair:** deleted in commit `29a9d68c9169ca8dd2fecf9394738577f5dedf3d`.

### 2. Contributor Terms lacked an explicit effective boundary

The earlier text stated that submission created certifications and a license grant but did not clearly state:

- when the terms become operative;
- whether they affect earlier contributions;
- how a contributor expressly accepts them before default-branch publication.

This created avoidable retroactivity and assent ambiguity.

**Repair:** `CONTRIBUTOR_TERMS.md` now states that the terms:

- are a draft on the review branch;
- become operative only after explicit Lead Maintainer approval and default-branch publication;
- apply prospectively or through express written acceptance;
- do not retroactively alter ownership, license, authorship, or contractual status;
- require an effective boundary for future material amendments.

`CONTRIBUTING.md` now explains that sign-off records express acceptance while the terms are not otherwise operative and does not alter earlier contributions.

### 3. Standard license integrity

The local Apache-2.0 file contains Sections 1 through 9 and the application appendix. The local CC BY 4.0 file contains the complete public-license structure, including definitions, scope, attribution, database rights, warranty and liability provisions, termination, other terms, and interpretation.

No Terra-specific restriction was identified inside either standard license text during this review.

### 4. Foundation identity boundary

The branch consistently treats Fractal Metascience Foundation as an affiliation or ecosystem identity unless documentary evidence supports use as a legal rights holder. This boundary remains necessary and must not be removed during merge review.

### 5. Release and DOI boundary

`CITATION.cff` does not activate a repository-wide single license, release date, or DOI. The Zenodo helper is documented as metadata synchronization rather than proof of deposition or DOI minting.

## Current strengths

- explicit file-scoped multi-license architecture;
- no blanket historical wildcard in `REUSE.toml`;
- historical grants preserved rather than described as revoked;
- Terra Public License separated as a draft artifact;
- standard license texts present;
- contributor ownership and attribution preserved;
- endorsement, partnership, certification, trademark, responsible-use, and copyright layers separated;
- branch not behind `main` at the recorded comparison;
- PR #3 duplication reconciled and closed without merge.

## Remaining merge blockers

### Protected legal decision

Contributor Terms include a prospective contributor certification and license-grant mechanism. Before merge, the Lead Maintainer must explicitly decide one of the following and record it:

1. approve the terms for default-branch operation after qualified legal review;
2. approve them as an interim repository policy while explicitly deferring specified professional review;
3. keep them as a non-operative draft and exclude them from the merge.

The AI executor cannot make this protected legal decision on behalf of the operator.

### Rights clearance

The branch does not complete historical file-by-file rights, contributor, publisher, donor, media, font, icon, template, dependency, or dataset clearance.

### Supply-chain review

GitHub Actions remain referenced by version tags rather than reviewed full commit SHAs. This is recorded as a follow-up item, not proof of compromise.

### Release verification

Earlier releases, downloadable bundles, Zenodo records, and historical license metadata remain to be verified before a new rights-cleared release or DOI statement.

### Professional review

Jurisdiction-specific questions involving contributor assent, trademarks, privacy, child data, commercial terms, governing law, warranties, liability, and dispute resolution remain outside this documentary audit.

## Merge decision

**Do not merge automatically.**

PR #2 is structurally coherent and substantially improved, but it remains a draft until:

- the protected legal decision for Contributor Terms is recorded;
- the current CI run succeeds after these repairs;
- a fresh `main` comparison shows no new divergence;
- unresolved limitations remain visible in the pull-request description and release status.

## Final declaration

The review identified and repaired one obsolete publication residue and one material contributor-terms ambiguity. The branch is technically closer to merge readiness but is not declared fully rights-cleared or professionally legally approved.