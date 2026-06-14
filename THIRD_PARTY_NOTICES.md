# Third-Party Notices

**Repository:** `terra-legal`  
**Status:** workflow dependency register initiated — full file-level review pending

## Purpose

This file prevents the repository's file-scoped licensing structure from being misread as relicensing external material.

## General rule

Third-party materials remain under their original rights, licenses, access rules, or restrictions. The presence of a reference, excerpt, template, badge, link, workflow, standard, or external license text in this repository does not make it Terra-owned.

## Public licenses and legal tools

The repository references public legal tools and license texts including:

- Creative Commons Attribution 4.0 International (`CC-BY-4.0`);
- Apache License, Version 2.0 (`Apache-2.0`);
- SPDX License List and identifiers;
- REUSE Specification.

These materials are governed by their official texts, publishers, and upstream terms.

## GitHub Actions and automation dependencies

The visible workflow layer invokes:

- `actions/checkout@v4` — upstream MIT License;
- `softprops/action-gh-release@v2` — upstream MIT License.

These are external dependencies referenced by version tags. They are not copied works owned by Terra and are not relicensed by any Apache-2.0 notice applied to repository-authored workflow logic.

The current tags are not pinned to reviewed full commit SHAs. This is recorded as a supply-chain review item, not as proof of compromise or license failure. Exact pinning requires a separate revision-verification step.

## GitHub platform and hosted automation

Badges, workflow execution, release infrastructure, repository metadata, and hosted platform services remain governed by their respective providers and upstream authors.

## Zenodo metadata boundary

The current file `.github/workflows/zenodo-release.yml` is a metadata synchronization helper. It accepts an already known DOI and writes DOI, version, date, and repository URL values into `CITATION.cff`.

It does not itself:

- create a Zenodo deposition;
- upload the release bundle to Zenodo;
- publish a Zenodo record;
- mint a DOI.

No badge, workflow name, or placeholder may be treated as evidence that a Zenodo deposit or DOI exists.

## External law and policy references

References to instruments such as the UN Convention on the Rights of the Child, GDPR, COPPA, the UNESCO Recommendation on the Ethics of Artificial Intelligence, or similar sources are legal, policy, and scholarly references. They are not authored or relicensed by this repository.

## Fonts and design references

References to typefaces such as Montserrat, Inter, and Fira Code are design references. Any actual font file or external package remains governed by its own license. Font files must not be committed unless redistribution rights and required notices are verified.

## Historical donor materials

Historical Terra, FMP, Invisible Shadow, naming, visual-identity, and protocol donor materials may have their own provenance and rights context. Bridge files in this repository do not erase that provenance or establish ownership by repetition.

## Required dependency record

When a repository file includes, invokes, transforms, or depends on third-party material, record at least:

- exact name and upstream source;
- version, tag, or commit used;
- upstream license or rights status;
- whether the material is copied, linked, invoked, transformed, embedded, or merely cited;
- date and method of verification;
- required attribution, notice, or redistribution conditions;
- unresolved security, provenance, or rights questions.

This applies to:

- copied third-party code;
- GitHub Actions, packages, APIs, hosted services, and reusable workflows;
- images, icons, fonts, diagrams, and templates;
- external standards and legal texts;
- datasets and database contents;
- material from institutions, archives, museums, publishers, or media organizations.

## Review status

The visible GitHub Action dependencies and Zenodo workflow boundary are now recorded. Full file-level dependency, media, template, donor-material, and historical-rights review remains pending under `RELICENSING_PROTOCOL.md`.