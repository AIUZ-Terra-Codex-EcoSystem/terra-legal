# Third-Party Notices

**Repository:** `terra-legal`  
**Status:** workflow and dependency register initiated

## Purpose

This file prevents the repository's default licensing policy from being misread as relicensing external material.

## General rule

Third-party materials remain under their original rights, licenses, access rules, or restrictions. The presence of a reference, excerpt, template, badge, link, workflow, standard, or external license text in this repository does not make it Terra-owned.

## Current third-party and external reference categories

### Public licenses and legal tools

The repository references public legal tools and license texts including:

- Creative Commons Attribution 4.0 International (`CC-BY-4.0`);
- Apache License, Version 2.0 (`Apache-2.0`);
- SPDX License List and identifiers;
- REUSE Specification.

These materials are governed by their own publishers' terms and official sources.

### GitHub Actions and automation dependencies

The current workflow layer calls external GitHub Actions:

- `actions/checkout@v4` — maintained by GitHub and distributed under the MIT License upstream;
- `softprops/action-gh-release@v2` — maintained by its upstream authors and distributed under the MIT License upstream.

The version tags above are dependency references, not copies owned by Terra. Their upstream repositories, notices, release tags, security posture, and license terms control. A future hardening pass should evaluate pinning each action to a reviewed full commit SHA while retaining an explanatory version comment.

The workflow files authored in this repository remain governed by the repository's software-like file policy (`Apache-2.0`), but that policy does not relicense the external actions they invoke.

### GitHub platform and automation services

Badges, workflow labels, GitHub Actions execution, release infrastructure, and GitHub metadata are governed by their respective providers and the terms of the GitHub platform or action authors.

### Zenodo metadata handling

The file `.github/workflows/zenodo-release.yml` is currently a repository metadata helper. It writes an already known DOI and version into `CITATION.cff`; it does not itself deposit files in Zenodo, create a Zenodo record, or mint a DOI.

Zenodo records, APIs, metadata, logos, and platform services remain governed by Zenodo/CERN terms and the terms applicable to each deposited record.

### External law and policy references

References to instruments such as the UN Convention on the Rights of the Child, GDPR, COPPA, UNESCO AI Ethics Recommendation, or similar sources are legal, policy, and scholarly references. They are not authored or relicensed by this repository.

### Fonts and design references

References to typefaces such as Montserrat, Inter, and Fira Code are design references. Any actual font file or external package remains governed by its own license. Font files should not be committed unless their license and redistribution terms are verified.

### Historical donor materials

Historical Terra, FMP, Invisible Shadow, naming, visual-identity, and protocol donor materials may have their own provenance and rights context. Bridge files in this repository do not erase that provenance.

## Required additions

Add a notice here when a repository file includes or depends on:

- copied third-party code;
- third-party images, icons, fonts, or diagrams;
- external standards or legal texts;
- copied templates;
- datasets or database contents;
- material from institutions, archives, museums, publishers, or media organizations;
- external GitHub Actions, packages, APIs, hosted services, or reusable workflow components.

For each dependency or copied component, record at least:

- exact name and upstream source;
- version, tag, or commit used;
- upstream license or rights status;
- whether the material is copied, linked, invoked, transformed, or merely cited;
- date and method of verification.

## Review status

This register now covers the visible workflow dependencies and major external-reference categories. A full file-level third-party audit remains pending under `RELICENSING_PROTOCOL.md`.