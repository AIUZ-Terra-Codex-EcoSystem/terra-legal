# Terra Legal Stabilization — Pull Request Review Checklist

**Branch:** `stabilize/terra-legal-licensing-v2`  
**Primary stabilization trace:** `TL-2026-06-14-004`  
**Rule 0 reconciliation trace:** `TL-2026-06-14-005`  
**Merge-readiness trace:** `TL-2026-06-14-006`  
**Primary audit:** `audits/2026-06-14-terra-legal-stabilization-v2.md`  
**Merge-readiness audit:** `audits/2026-06-14-pr2-merge-readiness.md`

## Architecture decision

- [ ] Confirm that `terra-legal` is a multi-license repository.
- [ ] Confirm that no single blanket license governs every file.
- [ ] Confirm that only explicitly classified files receive CC BY 4.0 or Apache-2.0.
- [ ] Confirm that unclassified historical files remain pending rights review.
- [ ] Confirm that earlier public grants are not represented as revoked.

## Terra Public License

- [ ] Confirm that Terra Public License v1.0 remains a draft, not the active repository or portfolio-wide license.
- [ ] Confirm that its ethical principles remain available through Responsible Use, Universal Convention, security, child-safety, and future contractual instruments.

## Standard licenses

- [ ] Confirm that `LICENSES/CC-BY-4.0.txt` contains the full standard legal code.
- [ ] Confirm that `LICENSES/Apache-2.0.txt` contains the full standard legal text.
- [ ] Confirm that no Terra-specific restriction was inserted into either standard license.

## Rights and metadata

- [ ] Confirm the formal author-name form: Abdurashid Abdulkhamitovich Abdukarimov.
- [ ] Confirm ORCID 0009-0000-6394-4912.
- [ ] Confirm that Fractal Metascience Foundation is currently used as affiliation or ecosystem identity, not automatically as a legal rights holder.
- [ ] Confirm that `CITATION.cff` does not state a false single license, release date, or DOI.
- [ ] Confirm that `REUSE.toml` maps only reviewed files and does not use blanket historical wildcards.

## Contributor Terms protected decision

- [ ] Confirm that Contributor Terms become operative only after explicit Lead Maintainer approval and publication on the default branch.
- [ ] Confirm that Contributor Terms apply prospectively and do not retroactively change earlier contributions.
- [ ] Confirm that sign-off records express acceptance where the terms are not otherwise operative.
- [ ] Record whether professional legal review is completed, explicitly deferred for an interim policy, or required before merge.
- [ ] Record the Lead Maintainer's protected legal decision in the PR and TraceLog.

## Governance and linking

- [ ] Confirm that linking to `terra-legal` does not apply a license automatically.
- [ ] Confirm that linking does not create partnership, certification, endorsement, or official status.
- [ ] Confirm editorial, normative, protected legal, security, and emergency-safety decision classes.
- [ ] Confirm contributor sign-off and rights certification rules.

## Publication and public page

- [ ] Confirm that release and DOI claims require verification.
- [ ] Confirm third-party exclusions and historical grant preservation.
- [ ] Confirm that `index.html` uses the shared stylesheet and presents the legal boundary accurately.
- [ ] Confirm that no obsolete temporary marker such as `PR2_NOT_OPENED.md` remains.

## Technical validation

- [ ] Confirm the latest Terra Legal Audit run succeeds after the final change set.
- [ ] Compare the branch with `main` immediately before merge and confirm it is not behind.
- [ ] Confirm PR #3 remains closed and unmerged.
- [ ] Confirm GitHub Action tag pinning remains an explicitly recorded follow-up item.

## Remaining limitations

- [ ] Accept that full historical file-by-file clearance remains pending.
- [ ] Accept that contributor, dependency, workflow, template, icon, font, media, and donor-rights audits remain pending.
- [ ] Accept that trademarks, privacy, child data, commercial terms, governing law, liability, warranties, and dispute resolution require qualified review.
- [ ] Accept that multilingual controlling legal versions are deferred until the English structure is approved.

## Final decision

- [ ] Approve architecture for merge.
- [ ] Request specified changes.
- [ ] Block pending additional rights evidence.
- [ ] Block pending protected legal decision.
- [ ] Block pending professional legal review.
