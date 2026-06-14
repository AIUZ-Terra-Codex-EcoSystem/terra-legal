# Terra Legal Framework Strategy

**Operator and architect:** Abdurashid Abdukarimov  
**ORCID:** 0009-0000-6394-4912  
**Repository:** `AIUZ-Terra-Codex-EcoSystem/terra-legal`  
**Date:** 2026-06-14  
**Status:** strategic framework for implementation and professional legal review

## Executive decision

The Terra and FMP portfolio should not use one custom license for every repository.

The legally coherent structure is a layered framework:

1. standard copyright or software license for the actual work;
2. Terra Universal Convention as an ethical and governance charter;
3. Terra Responsible Use Policy for conduct, child safety, and deployment expectations;
4. Trademark and Brand Policy for names, logos, certification marks, and identity;
5. contributor, privacy, data, commercial, and third-party rights instruments where relevant.

This model preserves open-science and open-source interoperability while keeping Terra's ethical identity visible and enforceable where a separate contract, hosted service, partnership agreement, or participation rule makes it binding.

## Rule 0 legal sequence

No license is selected merely because it is familiar, strict, generous, ethical, or already present in another repository.

Every legal action follows this order.

### Before the step

1. Read the repository role, source corpus, current license files, metadata, release records, and donor rules.
2. Identify the actual protected objects:
   - source code;
   - documentation;
   - scientific writing;
   - database structure;
   - individual data items;
   - images and media;
   - brand elements;
   - confidential or partner material.
3. Identify copyright owners, contributors, co-authors, publishers, upstream projects, and third-party rights.
4. Record current public grants that cannot simply be treated as nonexistent.
5. Apply Detox against false ownership, false completeness, prestige language, and automatic blanket licensing.

### During the step

1. Choose the narrowest correct standard instrument for each object class.
2. Preserve all earlier notices and third-party terms.
3. Separate ethical policy from copyright permission.
4. Separate brand permission from content permission.
5. Use TraceLog and a reviewable pull request.
6. Do not rewrite history or imply withdrawal of earlier irrevocable public grants.

### After the step

1. Align root license files, `LICENSES/`, README, `CITATION.cff`, package metadata, Zenodo metadata, releases, and documentation.
2. Validate SPDX identifiers and file-level scope.
3. Re-run contributor, dependency, media, and publication-rights checks.
4. Confirm that no third-party item was relicensed accidentally.
5. Record unresolved risks and legal-review status.

## Normative legal stack

## Layer 1 — Copyright and software permissions

This layer answers:

> What may another person do with this specific work under copyright, database, or software rights?

### Default scholarly and documentation license

**CC BY 4.0** is the default for:

- original articles;
- monographs;
- theoretical and methodological writing;
- project-authored documentation;
- original diagrams and educational explanations;
- original corpus metadata and annotations where appropriate.

Reasons:

- attribution is mandatory;
- adaptation and translation are permitted;
- commercial and non-commercial reuse are treated consistently;
- the license is internationally recognized and machine-readable;
- it supports scholarly dissemination and repository interoperability.

### Existing CC BY-SA 4.0 material

CC BY-SA 4.0 may remain where reciprocal licensing of adaptations is an intentional part of the knowledge commons.

Do not replace it only for visual uniformity. Change it only after compatibility, contributor, and publication review.

### Default new software license

**Apache-2.0** is the default candidate for newly licensed, fully owned Terra software because it provides:

- broad permissions;
- a patent-license framework;
- preservation of notices;
- compatibility with commercial and institutional adoption.

### Existing MIT software

Valid MIT licensing may remain.

A future cleanly owned major branch may adopt Apache-2.0, but existing MIT grants remain valid for earlier copies and versions.

### Existing GPL software

Existing GPL software remains under its current GPL status until:

- contributor ownership is established;
- source headers and version choice are verified;
- dependency compatibility is reviewed;
- a documented decision is made about reciprocal licensing.

### AGPL option

AGPL-3.0 may be considered only for a network service where the operator deliberately wants modified server-side versions to remain available under reciprocal terms.

It is not an automatic default and requires a product, partnership, and deployment decision.

## Layer 2 — Data and corpus rights

A corpus repository must distinguish at least four things:

1. project-authored metadata and annotations;
2. database structure and selection;
3. public-domain objects;
4. third-party copyrighted or restricted objects.

### Default

Use CC BY 4.0 for project-authored metadata, annotations, glossaries, schemas, and explanatory documentation where the project owns the relevant rights.

### Optional database share-alike

ODbL-1.0 may be selected only when:

- a protectable database exists;
- the project controls the database rights;
- share-alike obligations are intentionally desired;
- compatibility with research, institutional, and commercial reuse has been reviewed.

### Mandatory item-level rights

Every corpus item should expose fields such as:

- `rights_holder`;
- `rights_status`;
- `license`;
- `source`;
- `access_conditions`;
- `provenance`;
- `review_status`.

A root license never automatically overrides the rights of authors, archives, museums, publishers, photographers, or institutions whose material is referenced or stored.

## Layer 3 — Universal Convention

The Terra Universal Convention remains the ecosystem's ethical and governance charter.

It should state clearly that it is:

- an internal normative and ethical framework;
- not a treaty;
- not a state law;
- not an internationally ratified convention;
- not a replacement for the repository's copyright or software license.

### Relationship to standard licenses

The Convention may:

- guide Terra maintainers;
- govern participation in Terra-managed communities;
- form part of partner or commercial contracts when expressly incorporated;
- define certification and internal governance criteria;
- inform product safety, privacy, and child-protection review.

The Convention must not be presented as an additional restriction automatically imposed on material already offered under CC BY, Apache, MIT, GPL, or another standard public license when that license prohibits downstream restrictions or does not contain those conditions.

## Layer 4 — Terra Responsible Use Policy

The ethical obligations currently mixed into the Terra Public License should be moved into a separate policy covering:

- child safety;
- privacy and data minimization;
- human oversight;
- anti-manipulation;
- non-discrimination;
- responsible AI deployment;
- incident reporting;
- cultural and linguistic respect;
- environmental responsibility where relevant;
- prohibitions applicable to Terra-operated services and contractual partners.

### Binding status

The Responsible Use Policy becomes legally binding only through a valid mechanism, such as:

- terms of service for a hosted platform;
- partnership or licensing agreement;
- contributor or membership agreement;
- procurement or deployment contract;
- employment or contractor agreement;
- certification terms.

For independently redistributed open-source code, it remains a policy and ethical expectation unless the chosen software license itself contains a valid condition.

## Layer 5 — Trademark and Brand Policy

The following must be separated from open content licensing:

- `Terra` and compound Terra names;
- `Fractal Metascience Foundation`;
- `FMP` and named framework identifiers where used as source identifiers;
- logos, emblems, visual marks, certification badges, and identity systems;
- `Terra Certified`, award, quality, compliance, or partnership marks.

The Trademark and Brand Policy should permit:

- truthful nominative reference;
- attribution;
- links to official projects;
- unmodified screenshots for commentary and teaching;

while requiring permission for:

- modified official logos;
- claims of endorsement, certification, partnership, or institutional status;
- confusingly similar project branding;
- use of Terra marks in commercial product names.

Logos and trademarks should not be placed under a blanket CC license by default.

## Layer 6 — Contributor and authorship framework

### DCO path

Use a Developer Certificate of Origin workflow for ordinary open-source repositories where contributors certify that they have the right to submit their work under the existing project license.

### CLA path

Use a Contributor License Agreement only for repositories where Terra needs explicit rights to:

- dual-license;
- commercially license;
- relicense future versions;
- enforce rights centrally;
- integrate contributions into proprietary hosted services.

Likely CLA candidates require separate review and may include core platforms, commercial utilities, and future Terra-licensed products.

### Scholarly authorship

Articles, monographs, and research repositories require:

- named author and co-author records;
- contributor-role declarations;
- publication agreement register;
- identification of accepted manuscript, version of record, preprint, and repository version;
- confirmation that the deposited version may be licensed as stated.

## Layer 7 — Commercial framework

Commercial activity should not be embedded as changing fee tables inside a public copyright license.

Use separate instruments for:

- enterprise support;
- hosted services;
- closed-source integrations;
- brand use;
- certification;
- training and consulting;
- data processing;
- partnership and deployment;
- indemnity, warranty, service levels, and jurisdiction.

Public open licenses and commercial agreements may coexist when the project owns the necessary rights.

## Layer 8 — Privacy, data protection, and child safety

Copyright licensing does not replace privacy law, data-protection duties, or child-safety obligations.

Repositories or services handling personal data require separate documents as applicable:

- Privacy Notice;
- Data Processing Agreement;
- Records of Processing Activities;
- retention and deletion schedule;
- security and incident-response plan;
- parental-consent and age-appropriate design process;
- data transfer and processor register.

No public repository license should imply that personal data is freely reusable merely because code or documentation is open.

## Terra Public License disposition

The existing Terra Public License texts should be frozen as historical and developmental legal artifacts pending professional review.

### Immediate status

Use the label:

**Draft — not approved for automatic portfolio-wide application**

### What should be retained

The following conceptual elements remain valuable:

- child safety first;
- anti-exploitation safeguards;
- transparency;
- human oversight;
- responsible use;
- cultural respect;
- environmental responsibility;
- commercial and partnership accountability.

### What should be separated

- copyright and software permissions;
- ethical use rules;
- community conduct;
- privacy duties;
- certification;
- commercial fees;
- partnership conditions;
- trademarks;
- dispute resolution;
- aspirational Convention language.

### Future custom license option

A future custom Terra responsible-technology license may be drafted only when a real product or controlled licensing use case requires restrictions that standard open-source licenses cannot provide.

It must then:

- define the licensed object precisely;
- identify the licensor accurately;
- define permitted and prohibited uses clearly;
- state governing law and dispute mechanism after counsel review;
- distinguish copyright conditions from privacy, conduct, and service obligations;
- include warranty and liability provisions;
- include severability, termination, notices, and version rules;
- avoid calling itself open source unless it satisfies the Open Source Definition and is appropriately reviewed;
- use a `LicenseRef-...` identifier until accepted into a recognized license list.

## Ownership identity strategy

The portfolio currently uses several inconsistent owner names, including personal names, an incorrect surname, GitHub handles, project names, and foundation names.

The legal owner must be selected from actual rights holders, not branding convenience.

### Current rule

Until a registered entity owns rights through creation, assignment, or contract, use the verified individual copyright holder's full legal name.

Do not identify:

- a GitHub handle;
- an unregistered project title;
- an informal foundation name;
- a partner brand;

as copyright owner without documentary basis.

### Future entity rule

When the Fractal Metascience Foundation or another legal entity is validly established and rights are assigned, future works may identify that entity according to the assignment and employment or contractor agreements.

Earlier personal rights do not transfer merely because the entity name appears in repository metadata.

## Machine-readable compliance

Each maintained repository should ultimately contain:

- one clear top-level license explanation;
- `LICENSES/` with canonical license texts;
- SPDX license identifiers;
- SPDX copyright notices or `REUSE.toml`;
- `LEGAL.md` defining scope and exclusions;
- `THIRD_PARTY_NOTICES.md`;
- aligned `CITATION.cff`;
- aligned Zenodo and release metadata;
- repository-specific data or media rights files where applicable.

For mixed repositories, use file-level licensing rather than pretending one root license governs everything.

## Decision matrix

| Question | Legal consequence |
|---|---|
| Is the primary object scholarly text or documentation? | Default CC BY 4.0 |
| Is it newly licensed software owned by the project? | Default candidate Apache-2.0 |
| Is it existing MIT code? | Retain MIT unless there is a justified future-version decision |
| Is it existing GPL code? | Retain GPL until contributor and compatibility review |
| Is reciprocal network-service disclosure required? | Consider AGPL-3.0 after explicit decision |
| Is it original corpus metadata? | CC BY 4.0 with item-level rights |
| Is database share-alike intentionally required? | Consider ODbL after rights review |
| Does the repository contain third-party works? | Exclude and register them individually |
| Does the material contain logos or marks? | Trademark and Brand Policy, not blanket CC |
| Are ownership or partner rights unclear? | No license change; hold and investigate |
| Is the repository private? | No public grant until release decision |

## Implementation phases

### Phase 0 — Freeze

- stop automatic Terra Public License propagation;
- do not mass-edit license files;
- mark known conflicts visibly.

### Phase 1 — Portfolio inventory

- maintain `REPOSITORY_LICENSE_MAP.md`;
- identify license, role, visibility, owner, contributors, dependencies, releases, and DOI records.

### Phase 2 — Rights audit

- contributor history;
- co-author and publisher agreements;
- third-party code and media;
- dataset and archive rights;
- ownership identity.

### Phase 3 — Policy adoption

Prepare and review:

- Responsible Use Policy;
- Trademark and Brand Policy;
- Contributor Policy;
- Data and Corpus Rights Policy;
- Publication Rights Policy;
- Commercial Licensing Policy.

### Phase 4 — Per-repository migration

- one repository at a time;
- one reviewable branch or pull request;
- no history rewrite;
- update all metadata surfaces;
- preserve prior release notices.

### Phase 5 — Professional legal review

Obtain qualified review for:

- Uzbekistan law and entity structure;
- international contracts and enforcement;
- child-data and privacy deployments;
- custom responsible-use terms;
- trademarks and brand registration;
- commercial and partner agreements.

### Phase 6 — Release and continuous audit

- publish only after validation;
- record the license decision in TraceLog;
- re-audit on major repository-role, contributor, dependency, or business-model change.

## Legal status statement

This strategy is a documentary and technical governance framework. It is designed to organize evidence and reduce licensing contradictions. It is not a substitute for jurisdiction-specific advice from a qualified lawyer.

## Primary external legal references

- Creative Commons Attribution 4.0 International Legal Code
- Creative Commons Attribution-ShareAlike 4.0 International Legal Code
- Creative Commons FAQ on software, databases, and trademarks
- Apache License 2.0
- GNU GPL v3 and AGPL v3
- Open Source Definition
- SPDX License List
- REUSE Specification
- Open Data Commons ODbL 1.0
