# Workflow and Third-Party Dependency Audit — 2026-06-14

**Trace ID:** `TL-2026-06-14-004`  
**Target:** `AIUZ-Terra-Codex-EcoSystem/terra-legal`  
**Operator:** Abdurashid Abdulkhamitovich Abdukarimov  
**Audit scope:** visible GitHub Actions, citation/licensing alignment, REUSE mapping, and third-party dependency register  
**Status:** workflow layer reviewed; full file-level rights audit remains pending

## Operator context

The repository-level licensing contradiction had already been stabilized. This pass begins the next stage without mass relicensing and without modifying the legal meaning of foundational Terra documents.

The work was performed in the review branch:

- `audit/file-rights-2026-06-14`

This prevents parallel Terra AI or Codex activity from silently overwriting the default branch.

## Files reviewed

- `.github/workflows/release-and-publish.yml`
- `.github/workflows/zenodo-release.yml`
- `.github/workflows/terra-audit.yml`
- `README.md`
- `LICENSE`
- `LICENSE.md`
- `LEGAL.md`
- `CITATION.cff`
- `REUSE.toml`
- `THIRD_PARTY_NOTICES.md`
- `audits/2026-06-14-terra-legal-stabilization.md`
- `TRACELOG.md`

## Findings

### 1. The previous Terra Audit was a presence check only

The earlier workflow verified that eight governance files existed. It did not check:

- the scoped CC BY 4.0 and Apache-2.0 license split;
- separation of the Terra Public License draft;
- ORCID and repository URL alignment in `CITATION.cff`;
- REUSE annotations;
- registration of external GitHub Actions;
- an active placeholder DOI;
- floating or unpinned action references.

This meant the audit could pass while important licensing contradictions remained.

### 2. External GitHub Actions were not named in the register

The workflow layer invokes:

- `actions/checkout@v4`;
- `softprops/action-gh-release@v2`.

Upstream license files identify both actions as MIT-licensed. Their version tags and code remain external dependencies and are not relicensed by Terra's Apache-2.0 policy for repository-authored workflow files.

The third-party register has been expanded to name these dependencies and to distinguish invoked external code from Terra-authored workflow logic.

### 3. Action references are version-tagged, not commit-pinned

The visible workflows use major-version tags rather than reviewed 40-character commit SHAs.

This is not treated as an immediate licensing failure, but it is a supply-chain review item. The strengthened audit reports this condition as a review note and rejects floating references such as `@main`, `@master`, or `@latest`.

No commit pin was invented during this pass. Pinning requires separate verification of the exact upstream revisions.

### 4. The Zenodo workflow name overstates its current function

`.github/workflows/zenodo-release.yml` does not:

- create a Zenodo deposition;
- upload a release bundle to Zenodo;
- publish a Zenodo record;
- mint a DOI.

It accepts an already known DOI and writes DOI, version, date, and repository URL values into `CITATION.cff`.

It should therefore be understood as a manual Zenodo metadata synchronization helper. The boundary is now recorded in `THIRD_PARTY_NOTICES.md`. Renaming the workflow and clarifying the README remain separate reviewable changes.

### 5. REUSE mapping still requires a real lint pass

`REUSE.toml` provides broad defaults for Markdown, HTML, CSS, workflows, legal drafts, and license reference files. The separate annotation for `legal-drafts/**` is present, but overlapping annotations and repository-wide coverage should be tested with an actual REUSE-compatible validation run.

This pass verifies that the intended mappings are declared. It does not claim full REUSE compliance.

### 6. `CITATION.cff` represents only the documentation-facing citation license

`CITATION.cff` currently states `CC-BY-4.0`, while repository-authored software-like files use Apache-2.0. The accompanying message and repository documentation explain the mixed scope.

This is accepted provisionally for repository citation, but it must not be read as relicensing every file under CC BY 4.0. File-level notices and `LICENSE.md` control.

## Changes made

### Updated

- `.github/workflows/terra-audit.yml`
  - renamed the visible check to `Terra Legal Audit`;
  - added SPDX metadata for the workflow file;
  - expanded required legal and governance surfaces;
  - added license, citation, REUSE, draft-separation, dependency-register, DOI-placeholder, and action-reference checks;
  - retained read-only workflow permissions.

- `THIRD_PARTY_NOTICES.md`
  - registered `actions/checkout@v4` and `softprops/action-gh-release@v2`;
  - recorded their upstream MIT licensing status;
  - clarified that external actions are not Terra-owned;
  - documented the current Zenodo workflow boundary;
  - added minimum fields for future dependency notices.

### Created

- `audits/2026-06-14-workflow-third-party-audit.md`

## Controls preserved

- no files were deleted;
- no repository history was rewritten;
- no root license was replaced;
- no earlier grant was described as revoked;
- no third-party dependency was claimed as Terra-owned;
- no unverified action commit SHA was invented;
- no mass portfolio migration was authorized;
- all modifications were isolated in a review branch.

## Validation status

`partial file-level audit complete — workflow and dependency layer reviewed`

## Remaining work

- run or add a real REUSE compliance check;
- verify exact action revisions and decide whether to pin full commit SHAs;
- rename and clarify the Zenodo metadata workflow without implying deposition;
- inspect templates, HTML, CSS, images, icons, diagrams, and generated files individually;
- validate GitHub Pages against the shared stylesheet and external asset rights;
- expand third-party notices for every copied or invoked component;
- record the merged commit references in `TRACELOG.md` after review;
- obtain professional legal review before commercial, partner, certification, or child-facing deployment of custom Terra policy terms.

## Final declaration

This pass strengthens automated detection of repository-level legal contradictions and records the visible workflow dependencies. It does not claim completion of the whole repository file-level rights audit.