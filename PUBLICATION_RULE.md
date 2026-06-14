# Terra Publication Rule

This file defines publication boundaries for the `terra-legal` donor repository.

## What belongs here

- stable legal and licensing scope documents;
- governance and contribution rules;
- responsible-use, security, and reporting guidance;
- validation, audit, publication, naming, identity, TraceLog, and continuity protocols;
- bridge documents that other repositories may adopt explicitly;
- canonical license texts used by files in this repository;
- rights maps, migration records, and third-party notices.

## What does not belong here

- raw archive dumps;
- duplicate theory corpora;
- temporary exports and machine residue;
- confidential or private operational material;
- personal data not necessary for the public documentary role;
- false complete-package claims;
- unreviewed names, trademarks, licenses, partnerships, or certifications presented as approved;
- promotional material presented as legal authority;
- full Invisible Shadow theory copied into the legal donor layer;
- third-party works published under a Terra license without authority.

## Publication principles

Public material should be:

1. intentional;
2. readable and reviewable by humans;
3. safe for open publication;
4. linked to a clear repository role;
5. traceable to donor and external sources;
6. classified by object type and rights status;
7. packaged without flattening different legal or documentary layers;
8. consistent with naming and visual-identity standards;
9. recorded in TraceLog when material;
10. compatible with Invisible Shadow anti-capture safeguards.

## License and rights publication rule

Before publication or release, verify:

- each published file has a clear rights status;
- every used license has a canonical text in `LICENSES/` where required;
- SPDX headers, adjacent `.license` files, or `REUSE.toml` identify scope;
- `LICENSE`, `LEGAL.md`, README, `CITATION.cff`, package metadata, release notes, and DOI metadata do not contradict one another;
- earlier grants and historical notices are preserved;
- unannotated historical files are not silently relicensed;
- third-party material is excluded or clearly identified;
- contributor, co-author, publisher, partner, or employer rights have been checked where applicable;
- logos and marks are not treated as automatically CC-licensed;
- the Universal Convention and Responsible Use Policy are not presented as hidden additional conditions on a standard public license.

## Release classification

A release should state one of these statuses:

- `rights-cleared`;
- `rights-cleared with stated exclusions`;
- `historical snapshot — original licensing preserved`;
- `draft — not for redistribution as a complete licensed package`;
- `blocked pending rights review`.

Do not use `rights-cleared` while material ownership, license compatibility, third-party rights, or publication agreements remain unresolved.

## Citation and DOI rule

Citation and deposit metadata must identify:

- author or rights holder accurately;
- repository and version;
- release date only after actual release;
- DOI only after verified deposit;
- license only when the cited or deposited object has a coherent license scope;
- exclusions or mixed licensing where the deposit includes multiple object classes.

A workflow badge, placeholder DOI, or draft metadata entry is not proof of publication.

## Naming publication rule

Before a public name appears in a release, site, repository title, badge, or package:

- create or update a Name Card;
- state approval status;
- preserve aliases and deprecated forms;
- separate language review from legal or trademark review;
- link the decision to TraceLog.

## Identity publication rule

Public design should:

- follow `BRAND_IDENTITY_STANDARD.md`;
- use `VISUAL_IDENTITY_GUIDE.md` and the shared stylesheet where applicable;
- remain readable without special fonts or JavaScript;
- avoid excessive motion and promotional residue;
- never imply registration, certification, partnership, or scientific proof through design alone;
- respect `TRADEMARK_AND_BRAND_POLICY.md`.

## Continuity publication rule

A release should preserve:

- source and derivative relation;
- donor map;
- aliases and migration notes;
- previous licensing statements and effective-version boundaries;
- unresolved questions and limitations;
- protected handling of private or sensitive material.

## Living publication rule

Publication surfaces may evolve, but a released version is a stable historical record. Later changes do not erase the terms, metadata, or provenance of an earlier released version.

## Cross-repository rule

- theoretical works belong primarily in theory repositories;
- corpus and evidence objects belong primarily in corpus repositories;
- documentary donor rules and legal bridge files may belong in `terra-legal`;
- private, confidential, or backup material belongs outside the public legal layer.

A link to `terra-legal` does not automatically apply a license or create official status.

## Packaging rule

Publication should follow:

- `LEGAL.md`;
- `RELICENSING_PROTOCOL.md`;
- `THIRD_PARTY_NOTICES.md`;
- `FULL_PACKAGING_PROTOCOL.md`;
- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `TRACELOG_PROTOCOL.md`;
- `NAMING_STANDARD.md`;
- `BRAND_IDENTITY_STANDARD.md`;
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md`.

## Protected decision boundary

License choice, relicensing, authorship, copyright ownership, trademark status, privacy obligations, governing law, commercial terms, and jurisdictional claims require explicit operator decision and professional review where appropriate.

Publication packaging must not conceal unresolved conflicts.

## Documentary provenance

This rule is aligned with the stabilized file-scoped licensing architecture introduced under TraceLog `TL-2026-06-14-003`.
