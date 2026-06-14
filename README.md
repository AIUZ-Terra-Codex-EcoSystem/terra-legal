# terra-legal

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6394--4912-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0000-6394-4912)
[![License](https://img.shields.io/badge/License-scoped%20multi--license-2E8B57)](./LICENSE.md)
[![Release](https://img.shields.io/github/v/release/AIUZ-Terra-Codex-EcoSystem/terra-legal?display_name=tag)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/releases)
[![Last Commit](https://img.shields.io/github/last-commit/AIUZ-Terra-Codex-EcoSystem/terra-legal)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/commits/main)
[![Release Pipeline](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/release-and-publish.yml/badge.svg)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/release-and-publish.yml)
[![Zenodo Sync](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/zenodo-release.yml/badge.svg)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/zenodo-release.yml)
[![Terra Audit](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/terra-audit.yml/badge.svg)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/actions/workflows/terra-audit.yml)
[![Pages](https://img.shields.io/badge/Pages-terra--legal-2E8B57)](https://aiuz-terra-codex-ecosystem.github.io/terra-legal/)

> Normative donor repository for the Terra ecosystem: legal, governance, validation, audit, participation, publication, naming, identity, TraceLog, continuity, and portfolio licensing strategy.

## Repository role

`terra-legal` is the strongest compact donor repository for:

- license language and portfolio license mapping;
- contribution rules;
- code of conduct;
- governance logic;
- security baseline;
- publication boundaries;
- convention and protocol files, including full normative texts for core legal instruments;
- visible donor files for audit, validation, FMP analysis, naming, identity, continuity, and templates.

It is a donor layer, not the whole theory corpus, not the whole archive, and not a dump zone.
It may still carry complete normative texts when a foundational document would be misleading or useless in bridge-only form.

## Stabilized repository licensing

`terra-legal` now uses a scoped multi-license policy:

- original documentation, standards, policies, protocols, audit records, maps, and explanatory texts: **CC BY 4.0**;
- project-owned software-like files, stylesheets, workflows, scripts, and configuration: **Apache-2.0**;
- Terra custom legal drafts: preserved in `legal-drafts/` as draft legal artifacts, not default repository licenses;
- third-party materials and official external texts: governed by their own terms;
- names, logos, badges, certification claims, and marks: governed by the Trademark and Brand Policy.

Start with:

- [LICENSE](./LICENSE)
- [LICENSE.md](./LICENSE.md)
- [LEGAL.md](./LEGAL.md)
- [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)
- [RESPONSIBLE_USE_POLICY.md](./RESPONSIBLE_USE_POLICY.md)
- [TRADEMARK_POLICY.md](./TRADEMARK_POLICY.md)

The former Terra Public License default text is preserved as a draft in [`legal-drafts/TERRA_PUBLIC_LICENSE_v1.0_DRAFT.md`](./legal-drafts/TERRA_PUBLIC_LICENSE_v1.0_DRAFT.md).

## Main public surfaces

- GitHub Pages: [aiuz-terra-codex-ecosystem.github.io/terra-legal](https://aiuz-terra-codex-ecosystem.github.io/terra-legal/)
- Repository root: [github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)
- Citation metadata: [CITATION.cff](./CITATION.cff)
- Living trace: [TRACELOG.md](./TRACELOG.md)

## Portfolio licensing strategy

The connected GitHub portfolio has been inventoried at repository level before any mass license change.

- [Complete Repository License Map](./REPOSITORY_LICENSE_MAP.md)
- [Terra Legal Framework Strategy](./TERRA_LEGAL_FRAMEWORK_STRATEGY.md)
- [Relicensing Protocol](./RELICENSING_PROTOCOL.md)
- [Portfolio Licensing Audit](./audits/2026-06-14-license-portfolio-strategy.md)

Current strategic rule:

- no automatic portfolio-wide Terra Public License propagation;
- no mass replacement of root license files;
- standard licenses selected by object class and repository role;
- Universal Convention, Responsible Use, brand, privacy, contribution, and commercial rules kept as separate legal layers;
- repository-by-repository rights audit before migration.

## Publication automation

This donor repository exposes the publication chain for:

- release bundle creation on tagged releases;
- Zenodo DOI synchronization after release publication;
- Terra audit of the visible donor surface.

The DOI field remains pending until a successful published release is verified.

## Core files

### Legal, governance, and participation

- [LICENSE.md](./LICENSE.md)
- [LEGAL.md](./LEGAL.md)
- [RESPONSIBLE_USE_POLICY.md](./RESPONSIBLE_USE_POLICY.md)
- [TRADEMARK_POLICY.md](./TRADEMARK_POLICY.md)
- [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)
- [REUSE.toml](./REUSE.toml)
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- [CONTRIBUTING.md](./CONTRIBUTING.md)
- [GOVERNANCE.md](./GOVERNANCE.md)
- [SECURITY.md](./SECURITY.md)
- [REPOSITORY_LICENSE_MAP.md](./REPOSITORY_LICENSE_MAP.md)
- [TERRA_LEGAL_FRAMEWORK_STRATEGY.md](./TERRA_LEGAL_FRAMEWORK_STRATEGY.md)
- [RELICENSING_PROTOCOL.md](./RELICENSING_PROTOCOL.md)

### Audit, validation, and analysis

- [AUDIT_REGULATION.md](./AUDIT_REGULATION.md)
- [VALIDATION_PROTOCOL.md](./VALIDATION_PROTOCOL.md)
- [FMP_ANALYSIS_PROTOCOL.md](./FMP_ANALYSIS_PROTOCOL.md)
- [BIBLIOGRAPHY_SYNC_PROTOCOL.md](./BIBLIOGRAPHY_SYNC_PROTOCOL.md)

### Documentary and repository standards

- [STANDARDS.md](./STANDARDS.md)
- [DOCUMENTATION-STANDARD.md](./DOCUMENTATION-STANDARD.md)
- [TECHNICAL_GLOSSARY.md](./TECHNICAL_GLOSSARY.md)
- [GITHUB_LAYER_MODEL.md](./GITHUB_LAYER_MODEL.md)
- [TERRA_DOCUMENTARY_LAYER.md](./TERRA_DOCUMENTARY_LAYER.md)
- [FRACTAL_REPOSITORY_TEMPLATE_PROTOCOL.md](./FRACTAL_REPOSITORY_TEMPLATE_PROTOCOL.md)
- [DOCUMENT_TEMPLATES.md](./DOCUMENT_TEMPLATES.md)

### Rule, Detox, packaging, and donor trace

- [RULE_0_SOURCE_FIRST_PROTOCOL.md](./RULE_0_SOURCE_FIRST_PROTOCOL.md)
- [DETOX_ENGINE_PROTOCOL.md](./DETOX_ENGINE_PROTOCOL.md)
- [FULL_PACKAGING_PROTOCOL.md](./FULL_PACKAGING_PROTOCOL.md)
- [DONOR_SOURCE_REGISTRY.md](./DONOR_SOURCE_REGISTRY.md)
- [TRACELOG_PROTOCOL.md](./TRACELOG_PROTOCOL.md)
- [TRACELOG.md](./TRACELOG.md)

### Naming, brand, and visual identity

- [NAMING_STANDARD.md](./NAMING_STANDARD.md)
- [NAMING_CARD_TEMPLATE.md](./NAMING_CARD_TEMPLATE.md)
- [Naming Registry](./naming/registry/README.md)
- [BRAND_IDENTITY_STANDARD.md](./BRAND_IDENTITY_STANDARD.md)
- [VISUAL_IDENTITY_GUIDE.md](./VISUAL_IDENTITY_GUIDE.md)
- [Terra Legal stylesheet](./design/terra-legal.css)

### Continuity and living philosophy bridge

- [INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md](./INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md)
- [TERRA_UNIVERSAL_CONVENTION.md](./TERRA_UNIVERSAL_CONVENTION.md)
- [terra_living_protocols_constitution.md](./terra_living_protocols_constitution.md)
- [terra-main-directive-v7.0.md](./terra-main-directive-v7.0.md)
- [terra-sequence-protocol-v7.0.md](./terra-sequence-protocol-v7.0.md)
- [PUBLICATION_RULE.md](./PUBLICATION_RULE.md)
- [REPOSITORY_PROTOCOL.md](./REPOSITORY_PROTOCOL.md)

## Template scaffold

Reusable starter scaffold for new repositories:

- [`templates/fractal_repository_template`](./templates/fractal_repository_template)

## Reading path

1. Start with [README.md](./README.md)
2. Continue to [LICENSE.md](./LICENSE.md) and [LEGAL.md](./LEGAL.md)
3. Read [TERRA_DOCUMENTARY_LAYER.md](./TERRA_DOCUMENTARY_LAYER.md)
4. Read [RULE_0_SOURCE_FIRST_PROTOCOL.md](./RULE_0_SOURCE_FIRST_PROTOCOL.md)
5. Read [DETOX_ENGINE_PROTOCOL.md](./DETOX_ENGINE_PROTOCOL.md)
6. Read [TRACELOG_PROTOCOL.md](./TRACELOG_PROTOCOL.md)
7. Read [REPOSITORY_LICENSE_MAP.md](./REPOSITORY_LICENSE_MAP.md)
8. Read [TERRA_LEGAL_FRAMEWORK_STRATEGY.md](./TERRA_LEGAL_FRAMEWORK_STRATEGY.md)
9. Read [RELICENSING_PROTOCOL.md](./RELICENSING_PROTOCOL.md)
10. Read [INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md](./INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md)
11. Read [NAMING_STANDARD.md](./NAMING_STANDARD.md)
12. Read [BRAND_IDENTITY_STANDARD.md](./BRAND_IDENTITY_STANDARD.md)
13. Read [FULL_PACKAGING_PROTOCOL.md](./FULL_PACKAGING_PROTOCOL.md)
14. Read [DONOR_SOURCE_REGISTRY.md](./DONOR_SOURCE_REGISTRY.md)
15. Continue to [TERRA_UNIVERSAL_CONVENTION.md](./TERRA_UNIVERSAL_CONVENTION.md)
16. Then read the main directive, sequence protocol, layer model, audit, validation, publication, and template files.

## Ecosystem use

Other repositories may:

- inherit files directly from here;
- adapt them with repo-local bridge language;
- link back here as the donor layer;
- keep stricter local rules where needed for safety or source integrity.

## Boundary

This repository should remain compact, readable, and normative.
It should not absorb theory corpora, raw archives, or shadow duplicates.
Foundational legal texts may appear here in full when the legal donor layer would otherwise degrade into pointers without substantive content.

## Remaining stabilization work

The principal repository-level license contradiction has been stabilized. Remaining work:

- file-level audit of all older materials;
- full third-party notice expansion;
- GitHub Pages visual migration to the shared stylesheet;
- validation of workflows and Zenodo metadata;
- professional legal review before using custom Terra terms in commercial or child-facing deployments.

## Author

**Abdurashid Abdulkhamitovich Abdukarimov**

- ORCID: [0009-0000-6394-4912](https://orcid.org/0009-0000-6394-4912)
- Foundation: Fractal Metascience Foundation
- Location: Tashkent, Uzbekistan
