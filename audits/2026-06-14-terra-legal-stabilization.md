# Terra Legal Stabilization Audit — 2026-06-14

**Trace ID:** `TL-2026-06-14-003`  
**Repository:** `AIUZ-Terra-Codex-EcoSystem/terra-legal`  
**Branch:** `stabilize/terra-legal-licensing-v1`  
**Base commit:** `46460fd1490c927bd007cbc08d138ca2f5a6e2d5`  
**Operator:** Abdurashid Abdukarimov — ORCID 0009-0000-6394-4912  
**Audit levels:** rights, structural, publication, protocol  
**Status:** stabilization package prepared for review; not merged

## Operator instruction

Stabilize `terra-legal` as the first repository under the portfolio licensing map and Rule-0-based legal strategy.

## Sources read before change

### Repository sources

- `README.md`;
- `LICENSE`;
- `LICENSE.md`;
- `CITATION.cff`;
- `CONTRIBUTING.md`;
- `GOVERNANCE.md`;
- `LINKING-INSTRUCTIONS.md`;
- `REPOSITORY_PROTOCOL.md`;
- `PUBLICATION_RULE.md`;
- `STANDARDS.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `TRACELOG.md`;
- `REPOSITORY_LICENSE_MAP.md`;
- `TERRA_LEGAL_FRAMEWORK_STRATEGY.md`;
- `RELICENSING_PROTOCOL.md`;
- naming, brand, visual identity, Invisible Shadow, Rule 0, Detox, and TraceLog donor files.

### External primary sources

- Creative Commons Attribution 4.0 International legal code;
- Apache License 2.0;
- SPDX License List and identifiers;
- REUSE Specification for machine-readable file-level licensing.

## Before-step findings

### Root-license contradiction

The repository simultaneously exposed:

- `LICENSE` — short CC BY 4.0 notice with the name `Abdurashid Khamdamov`;
- `LICENSE.md` — Terra Public License v1.0 as an active blanket custom license;
- `CITATION.cff` — `CC0-1.0`.

These positions could not coherently govern the same mixed repository.

### Object-class collapse

Legal documents, governance files, policies, CSS, workflows, templates, official license texts, donor bridges, and historical drafts were treated as if one license could govern all material automatically.

### Automatic inheritance claim

`LINKING-INSTRUCTIONS.md` stated that linking another repository automatically inherited Terra Public License v1.0 and official ecosystem status.

That claim lacked a rights, contract, and governance mechanism.

### Obsolete repository identity

Contribution and linking files still used `.terra-legal` instead of `terra-legal`.

### Governance overstatement

The prior governance file described a standing voting and consultation mechanism, fixed review periods, and community authority not evidenced by a defined membership or implemented process.

### Missing machine-readable scope

The repository had no `LICENSES/` structure, no `REUSE.toml`, and no controlled file-level licensing boundary.

## Stabilization design

The branch introduces an intentionally limited file-scoped structure:

1. root `LICENSE` becomes a multi-license scope notice rather than a blanket license;
2. `LEGAL.md` defines controlling rights and exclusions;
3. exact standard texts are stored in `LICENSES/`;
4. `REUSE.toml` classifies only new stabilization files and the repository stylesheet;
5. historical unclassified files are not silently relicensed;
6. Terra Public License is preserved as an archived draft status file with a pinned historical link;
7. responsible use, trademark and brand, contributor, and third-party rules are separated;
8. README, citation metadata, governance, contribution, linking, publication, validation, audit, repository, standards, index, and living index surfaces are aligned;
9. earlier grants are not represented as revoked;
10. material changes remain on a branch for review before merge.

## Files created

- `LEGAL.md`;
- `RESPONSIBLE_USE_POLICY.md`;
- `TRADEMARK_AND_BRAND_POLICY.md`;
- `THIRD_PARTY_NOTICES.md`;
- `CONTRIBUTOR_TERMS.md`;
- `LICENSES/Apache-2.0.txt`;
- `LICENSES/CC-BY-4.0.txt`;
- `NOTICE`;
- `REUSE.toml`;
- this audit record.

## Files materially updated

- `LICENSE`;
- `LICENSE.md`;
- `CITATION.cff`;
- `README.md`;
- `LIVING_INDEX.md`;
- `CONTRIBUTING.md`;
- `GOVERNANCE.md`;
- `LINKING-INSTRUCTIONS.md`;
- `REPOSITORY_PROTOCOL.md`;
- `PUBLICATION_RULE.md`;
- `STANDARDS.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `index.html`.

## Key commit references

- `4d5a38f8155961022c7402eba5973f4d257e0792` — licensing and rights scope;
- `6234bdaee2ae19938e4543c0c788b91550e1948a` — Responsible Use Policy;
- `7d9eeacc9b8a98562dc2fd60225268f01584a6e7` — Trademark and Brand Policy;
- `d80a3a503f4f3cd83b88a8e7f04eec1087a1aaf1` — third-party register;
- `df51aa6454db37cfa58a74cad06513d89d098513` — contributor terms;
- `a096484b4361ae37b91e9adcec85e7f9db300897` — Apache-2.0 canonical text;
- `18ecaf8e8e5957934e22c671c2f70d089935ec9d` — CC-BY-4.0 canonical text;
- `23703ea989dac06367f7140ce4aba909c933d338` — root license scope notice;
- `1268f6acacdd0d4fcce5432a6b6349cff160e489` — archived Terra Public License status;
- `c947da9ba98e6aa1e4517b1bbccba1fb3d406483` — attribution notice;
- `cd76aa28ff0ab24067d560166c10461ff22e4b05` — initial REUSE map;
- `bf1daeec868295c3b233e32c8b0b3873cd57190f` — citation metadata stabilization;
- `f45699b37614fe1735fe650f339030077ef41b33` — contribution rules;
- `4b9c600bb40d998eb1d6adf6d29b65ce4324d121` — linking boundary;
- `916f86b7feddad3a980cfbbe0416138c123b1e77` — governance stabilization;
- `eb0b2f3aef7535209ae176b52c4d706b26193ef3` — README stabilization;
- `51175b1f1add6077bfb03d0552b57fc7d281f838` — Living Index stabilization;
- `3333c1d72b0dbe4a5c2d1fe50e333b8df6614a91` — repository protocol stabilization;
- `7edc3d982dacda45e5ae29cbca6894f525f0b24f` — publication rule stabilization;
- `4355ef42cec8d11f7bcefff3fa7d4a006f8a7c9f` — public page stabilization;
- `f283b4275822cbe92b2b11486289fd5d82e7f467` — standards stabilization;
- `dfe69bc3c1feb912e3fb006296acd3d45b644734` — validation stabilization;
- `6435d7d47b24a442dc4f87c51745fd12537ed70c` — audit regulation stabilization.

## Detox record

### Before

Passed.

No final license was chosen before the current repository license surfaces, role, historical grants, object classes, and external standard requirements were reviewed.

### During

Passed with explicit containment:

- no Git history rewrite;
- no claim that earlier CC, CC0, or custom-license grants disappeared;
- no blanket relicensing of all historical files;
- no third-party material treated as project-owned;
- no custom Terra license described as OSI-approved;
- no Universal Convention or Responsible Use term added secretly to a standard license;
- no trademark registration or legal compliance claim inferred from policy text;
- no automatic certification or ecosystem status through linking.

### After

Passed for the prepared branch, subject to the unresolved conditions below.

## Validation results

### Root and metadata coherence

Prepared for review.

The visible CC BY / CC0 / Terra Public License contradiction is removed on the branch. Citation metadata no longer declares CC0. The root notice points to file-level scope.

### Canonical license texts

Prepared for review.

CC BY 4.0 and Apache-2.0 texts are stored under SPDX-compatible filenames in `LICENSES/`.

### File-level scope

Partial pass.

`REUSE.toml` intentionally maps only newly created stabilization files and `design/terra-legal.css`. Historical files remain unclassified pending rights review.

### Historical continuity

Pass.

The previous Terra Public License text is preserved through a pinned historical commit link, and the branch does not claim withdrawal of prior public grants.

### Linking and governance

Pass for branch content.

Automatic license inheritance and unsupported standing-vote claims have been removed.

### Public page

Pass for branch content.

`index.html` now uses the shared Terra stylesheet and exposes the stabilized legal boundary.

## Unresolved conditions

- complete file-by-file copyright and license classification for historical files;
- contributor and commit-history review beyond the current connected account evidence;
- workflow, dependency, action, template, icon, font, and media rights audit;
- verification of prior release and Zenodo metadata and any earlier deposited license statements;
- confirmation of the exact legal identity and current registration status of the Fractal Metascience Foundation before it is used as a rights holder;
- jurisdiction-specific review for trademarks, privacy, child data, commercial terms, governing law, warranties, liability, and dispute resolution;
- review of archived Terra Public License language before any future custom-license development;
- multilingual legal companion versions only after the English controlling text is stabilized.

## Audit conclusion

**Status: prepared for review — not merged.**

The branch substantially stabilizes the repository's public licensing, governance, contribution, responsible-use, brand, publication, validation, audit, and linking surfaces without claiming complete historical rights clearance.

Merge should occur only after branch comparison, pull-request review, and confirmation that the remaining rights-review limitations are visible and acceptable.
