# CHANGELOG

All notable changes to **terra-legal** are documented here.

Format: [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
Versioning: [Semantic Versioning](https://semver.org/)

---

## [Unreleased]

### Reconciled stabilization package — branch `stabilize/terra-legal-licensing-v2`

#### Added

- `CONTRIBUTOR_TERMS.md` — contributor certification, rights, attribution, AI-assistance, and sign-off terms.
- `NOTICE` — repository attribution, mixed-licensing, third-party, and brand boundary notice.
- `audits/2026-06-14-terra-legal-stabilization-v2.md` — reconciled branch-level audit.

#### Reconciled and strengthened

- `LEGAL.md` now states that no blanket license applies and that only explicitly classified files receive CC BY 4.0 or Apache-2.0.
- `LICENSE` is a strict file-scoped notice rather than a repository-wide default grant.
- `LICENSE.md` preserves the Terra Public License as a draft while aligning the repository policy with explicit file-level classification.
- `REUSE.toml` no longer assigns licenses to every Markdown, HTML, CSS, or workflow file by wildcard; it maps only reviewed stabilization files.
- `LICENSES/CC-BY-4.0.txt` and `LICENSES/Apache-2.0.txt` now contain the full standard legal texts rather than link-only summaries.
- `CITATION.cff` no longer declares a false single repository license, unverified release date, or placeholder DOI.
- `CONTRIBUTING.md` and `CONTRIBUTOR_TERMS.md` now require rights-aware submissions, provenance, sign-off, and protected legal review.
- `GOVERNANCE.md` now distinguishes editorial, normative, protected legal, security, and emergency-safety decisions instead of claiming an unsupported standing voting structure.
- `LINKING-INSTRUCTIONS.md` no longer claims that linking automatically applies a license, creates certification, transfers rights, or grants official Terra status.
- `REPOSITORY_PROTOCOL.md`, `PUBLICATION_RULE.md`, `STANDARDS.md`, `VALIDATION_PROTOCOL.md`, and `AUDIT_REGULATION.md` now enforce file-scoped licensing, historical-grant preservation, third-party exclusions, metadata coherence, and professional-review boundaries.
- `DOCUMENTATION-STANDARD.md` no longer requires automatic Terra Public License adoption and now uses status, evidence, rights, citation, translation, and linking controls.
- `DOCUMENT_TEMPLATES.md` replaces speculative metrics and certification claims with source-first technical, governance, licensing, audit, trace, and publication-rights templates.
- `README.md`, `LIVING_INDEX.md`, and `index.html` expose the stabilized legal structure and its unresolved limits.
- `index.html` now uses the shared Terra Legal stylesheet.

#### Stabilization rule

- No single blanket license governs every file.
- CC BY 4.0 applies only to explicitly classified original documentary material.
- Apache-2.0 applies only to explicitly classified original implementation material.
- Historical unclassified files are not silently relicensed.
- Earlier public grants are not represented as revoked.
- Terra Public License remains a draft, not an active automatic portfolio license.
- Universal Convention, Responsible Use, trademark, privacy, contributor, and commercial layers remain separate from standard public-license permissions.

#### Current status

`prepared for review — not merged`

#### Remaining work

- complete file-level rights classification for historical files;
- audit contributors, dependencies, GitHub Actions, copied templates, icons, fonts, media, and donor materials;
- verify earlier releases, Zenodo deposits, and historical license metadata;
- confirm the legal status and rights-holding capacity of any foundation or entity named in future legal notices;
- obtain qualified review for trademarks, privacy, child data, commercial terms, governing law, warranties, liability, and dispute resolution;
- prepare multilingual companion texts only after the English controlling surface is approved.

### Earlier 2026-06-14 additions

- `TRACELOG_PROTOCOL.md` and `TRACELOG.md` — public and protected trace discipline.
- `NAMING_STANDARD.md`, `NAMING_CARD_TEMPLATE.md`, and `naming/registry/` — source-first naming and registry rules.
- `BRAND_IDENTITY_STANDARD.md`, `VISUAL_IDENTITY_GUIDE.md`, and `design/terra-legal.css` — restrained and accessible identity layer.
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md` — continuity, anti-closure, and anti-capture bridge.
- `REPOSITORY_LICENSE_MAP.md` — repository-level inventory for 29 connected GitHub repositories.
- `TERRA_LEGAL_FRAMEWORK_STRATEGY.md` — layered legal strategy for content, software, data, brand, governance, and commercial terms.
- `RELICENSING_PROTOCOL.md` — repository-by-repository rights, migration, Detox, validation, and audit sequence.
- `RESPONSIBLE_USE_POLICY.md`, `TRADEMARK_POLICY.md`, `THIRD_PARTY_NOTICES.md`, and `legal-drafts/TERRA_PUBLIC_LICENSE_v1.0_DRAFT.md`.
- audits dated 2026-06-14 for naming and identity integration, portfolio licensing strategy, and initial repository stabilization.

---

## [1.0.0] - 2026-03-03

### Added

- `DOCUMENTATION-STANDARD.md`
- `LINKING-INSTRUCTIONS.md`
- `CHANGELOG.md`
- `GOVERNANCE.md`

### Notes

- Initial complete release of the terra-legal framework.
- Core governance documents present.

---

## [0.9.0] - 2025-07-16

### Added

- original `LICENSE.md` Terra Public License draft;
- `CODE_OF_CONDUCT.md`;
- `CONTRIBUTING.md`;
- `SECURITY.md`;
- `CITATION.cff`;
- `README.md`.

### Historical note

The Terra Public License draft and its ethical principles remain preserved. The stabilization architecture does not present that draft as the active blanket license.

---

## Links

- [Licensing and Rights Scope](./LEGAL.md)
- [Repository License Map](./REPOSITORY_LICENSE_MAP.md)
- [Terra Legal Framework Strategy](./TERRA_LEGAL_FRAMEWORK_STRATEGY.md)
- [Relicensing Protocol](./RELICENSING_PROTOCOL.md)
- [FMP Ecosystem](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO)
- [ORCID 0009-0000-6394-4912](https://orcid.org/0009-0000-6394-4912)

---

*© 2025-2026 Abdurashid Abdulkhamitovich Abdukarimov. Terra Ecosystem.*
