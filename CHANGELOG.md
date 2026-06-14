# CHANGELOG

All notable changes to **terra-legal** are documented here.

Format: [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
Versioning: [Semantic Versioning](https://semver.org/)

---

## [Unreleased]

### Stabilization package — branch `stabilize/terra-legal-licensing-v1`

#### Added

- `LEGAL.md` — controlling licensing and rights scope for the multi-license repository.
- `LICENSES/CC-BY-4.0.txt` — canonical Creative Commons Attribution 4.0 text.
- `LICENSES/Apache-2.0.txt` — canonical Apache License 2.0 text.
- `REUSE.toml` — intentionally limited first-stage file-level licensing map.
- `NOTICE` — repository attribution and scope notice.
- `RESPONSIBLE_USE_POLICY.md` — ethical and safety policy separated from copyright licensing.
- `TRADEMARK_AND_BRAND_POLICY.md` — brand, endorsement, certification, and nominative-use boundaries.
- `THIRD_PARTY_NOTICES.md` — third-party rights and external-components register.
- `CONTRIBUTOR_TERMS.md` — contributor certification, rights, attribution, and sign-off terms.
- `audits/2026-06-14-terra-legal-stabilization.md` — branch-level rights, structure, publication, and protocol audit.

#### Changed

- Replaced the conflicting root `LICENSE` with a file-scoped multi-license notice.
- Converted `LICENSE.md` into an archive-status record for the former Terra Public License draft and preserved the complete historical text through a pinned commit link.
- Removed the false `CC0-1.0` declaration from `CITATION.cff` and stated that licensing is file-specific.
- Corrected the public author identity to Abdurashid Abdukarimov where the stabilization package creates or updates rights notices.
- Rewrote `CONTRIBUTING.md` around contributor certification, file-level licensing, Rule 0, Detox, TraceLog, and protected legal review.
- Replaced obsolete `.terra-legal` and automatic Terra Public License inheritance instructions in `LINKING-INSTRUCTIONS.md`.
- Replaced unsupported standing-vote and fixed-timeline governance claims with reviewable editorial, normative, protected legal, security, and emergency-safety processes.
- Updated README and Living Index to expose the stabilized legal stack and its limitations.
- Updated Repository Protocol, Publication Rule, Standards, Validation Protocol, and Audit Regulation for file-scoped licensing, third-party exclusions, historical grants, metadata coherence, and professional-review boundaries.
- Migrated `index.html` to the shared Terra Legal stylesheet and exposed the corrected public legal boundary.

#### Stabilization decision

- No single blanket license governs every repository file.
- New stabilization documents are mapped under CC BY 4.0 where stated.
- `design/terra-legal.css` is mapped under Apache-2.0.
- Historical unclassified files are not silently relicensed.
- Earlier public grants are not represented as revoked.
- Terra Public License remains an archived draft, not an active automatic portfolio license.
- Universal Convention and Responsible Use Policy remain separate from standard public-license permissions.

#### Current status

`prepared for review — not merged`

#### Remaining work

- complete file-level rights classification for historical files;
- audit contributors, dependencies, GitHub Actions, copied templates, icons, fonts, media, and donor materials;
- verify prior releases, Zenodo deposits, and historical license metadata;
- confirm the legal status and rights-holding capacity of any foundation or entity named in future legal notices;
- obtain qualified review for trademarks, privacy, child data, commercial terms, governing law, warranties, liability, and dispute resolution;
- prepare multilingual companion texts only after the English controlling surface is stabilized.

### Earlier Unreleased additions

- `TRACELOG_PROTOCOL.md` — public and protected trace discipline with before/during/after Detox stages.
- `TRACELOG.md` — living public record of material repository decisions.
- `NAMING_STANDARD.md` and `NAMING_CARD_TEMPLATE.md` — source-first naming and registry rules.
- `BRAND_IDENTITY_STANDARD.md`, `VISUAL_IDENTITY_GUIDE.md`, and `design/terra-legal.css` — restrained and accessible identity layer.
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md` — continuity, anti-closure, and anti-capture bridge.
- `REPOSITORY_LICENSE_MAP.md` — repository-level inventory for 29 connected GitHub repositories.
- `TERRA_LEGAL_FRAMEWORK_STRATEGY.md` — layered legal strategy for content, software, data, brand, governance, and commercial terms.
- `RELICENSING_PROTOCOL.md` — repository-by-repository rights, migration, Detox, validation, and audit sequence.
- audits dated 2026-06-14 for naming/identity integration and portfolio licensing strategy.

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

The Terra Public License draft and its ethical principles are preserved in repository history. The stabilization branch does not present that draft as the active blanket license.

---

## Links

- [Licensing and Rights Scope](./LEGAL.md)
- [Repository License Map](./REPOSITORY_LICENSE_MAP.md)
- [Terra Legal Framework Strategy](./TERRA_LEGAL_FRAMEWORK_STRATEGY.md)
- [Relicensing Protocol](./RELICENSING_PROTOCOL.md)
- [FMP Ecosystem](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO)
- [ORCID 0009-0000-6394-4912](https://orcid.org/0009-0000-6394-4912)

---

*© 2025-2026 Abdurashid Abdukarimov. Terra Ecosystem.*
