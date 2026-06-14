# Terra Validation Protocol

This file defines validation for Terra repository, licensing, publication, documentary, naming, identity, trace, responsible-use, and continuity surfaces.

## Purpose

Validation confirms that a surface is not only present, but usable and internally coherent within its declared role.

Validation must answer:

- does the surface belong here;
- does it perform the role it claims;
- are rights, provenance, limitations, and review status visible;
- is it coherent with directives, standards, licensing, naming, identity, and donor rules;
- is it safe, traceable, and publication-ready where applicable.

## Relationship to audit

Audit identifies disorder, contradiction, and risk.

Validation confirms readiness against declared requirements.

The two layers work together but are not interchangeable.

## Validation inputs

Begin with the relevant controlling surfaces:

- `LICENSE`;
- `LEGAL.md`;
- `REUSE.toml`;
- `THIRD_PARTY_NOTICES.md`;
- `RELICENSING_PROTOCOL.md`;
- `RESPONSIBLE_USE_POLICY.md`;
- `TRADEMARK_AND_BRAND_POLICY.md`;
- `CONTRIBUTOR_TERMS.md`;
- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `TRACELOG_PROTOCOL.md`;
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md`;
- `NAMING_STANDARD.md`;
- `BRAND_IDENTITY_STANDARD.md`;
- `terra_living_protocols_constitution.md`;
- `terra-main-directive-v7.0.md`;
- `STANDARDS.md`;
- `REPOSITORY_PROTOCOL.md`.

## Validation domains

### 1. Role validation

Check that the file or package matches the repository role and does not claim authority, certification, partnership, scientific validation, legal advice, or institutional status that has not been established.

### 2. Legal and licensing validation

Check:

- object class is identified: documentation, software, data, media, brand, third-party material, or archive;
- applicable license is explicit and uses an exact standard identifier where available;
- canonical license text is present in `LICENSES/` where required;
- `LICENSE`, `LEGAL.md`, SPDX headers, adjacent `.license` files, and `REUSE.toml` do not conflict;
- copyright and contributor identity are verified;
- historical grants and version boundaries are preserved;
- unannotated historical files are not silently relicensed;
- third-party works, standard license texts, quotations, media, and external components are excluded or recorded correctly;
- Universal Convention and Responsible Use Policy are not presented as hidden additional conditions on a standard public license;
- trademarks, privacy duties, commercial terms, and certification claims are not collapsed into a copyright license;
- professional-review requirements are visible.

### 3. Metadata validation

Check consistency among:

- README and badges;
- `CITATION.cff`;
- package and workflow metadata;
- release notes and tags;
- Zenodo and DOI records;
- website footers and downloadable bundles.

A placeholder, workflow badge, or draft field is not proof of a completed release, DOI deposit, audit, or certification.

### 4. Trace and provenance validation

Check that donor relation, operator instruction, sources, affected files, changes, decisions, and unresolved risks are visible.

Public TraceLog records must exclude secrets, unnecessary personal data, and protected evidence.

### 5. Structural validation

Check that entry path, links, companion files, file names, internal references, and historical pointers remain coherent.

### 6. Safety and responsible-use validation

Check:

- child and vulnerable-person safety;
- anti-manipulation safeguards;
- privacy and data minimization;
- no-secret publication;
- human oversight and escalation paths;
- scientific and documentary integrity;
- no harmful or deceptive drift.

### 7. Contributor validation

Where a contribution is accepted, check:

- contributor has certified the right to submit;
- target file license is known and compatible;
- third-party material and employer, publisher, client, or co-author restrictions are disclosed;
- attribution is preserved;
- AI assistance has not introduced fabricated provenance or unauthorized copying;
- no ownership transfer is implied without a separate written agreement.

### 8. Naming validation

Where a public name is introduced or changed, check:

- Name Card exists;
- primary role is unambiguous;
- language review is visible;
- legal and trademark review status is not overstated;
- aliases and deprecated forms are preserved;
- decision is connected to TraceLog.

### 9. Identity and trademark validation

Where a public visual or naming surface is changed, check:

- Terra identity rules are applied consistently;
- accessibility remains intact;
- color is not the sole carrier of meaning;
- excessive motion and promotional residue are absent;
- legal meaning remains clearer, not more decorative;
- design does not imply registration, endorsement, certification, partnership, or capability that is not established;
- `TRADEMARK_AND_BRAND_POLICY.md` is respected.

### 10. Continuity validation

Check:

- source and derivative relation;
- migration and alias continuity;
- historical license and release continuity;
- missing context is marked rather than invented;
- archive or shadow material is not presented as the live public surface;
- trace collection does not exceed its declared purpose.

### 11. Publication validation

Where a surface is publication-facing, check:

- author and contributor records;
- citation and bibliography relation;
- publisher and co-author rights where applicable;
- release classification and license scope;
- language packaging role;
- public readability;
- package integrity;
- third-party exclusions;
- DOI and deposit facts are verified rather than inferred.

## Minimal validation sequence

1. Identify the target surface and declared role.
2. Read governing and external sources first.
3. Classify the object and rights status.
4. Verify ownership, contributors, third-party material, and historical grants.
5. Verify required companion files and canonical license texts.
6. Verify structural coherence and readability.
7. Verify metadata consistency.
8. Verify provenance and trace visibility.
9. Verify naming, identity, and trademark coherence where applicable.
10. Verify continuity and anti-capture safeguards.
11. Verify safety and Detox compatibility.
12. Declare status:
    - `valid`;
    - `valid with exclusions`;
    - `valid with repair notes`;
    - `prepared for review`;
    - `blocked pending rights review`;
    - `blocked pending professional legal review`.

## Validation output

Each validation record states:

- target and role;
- branch, commit, release, or version;
- controlling rules and sources consulted;
- object and rights classification;
- status;
- exclusions and unresolved risks;
- next repair or review action;
- TraceLog reference.

## Failure conditions

A surface must not be marked valid if it:

- contradicts Rule 0 or explicit operator control;
- hides or loses provenance;
- depends on broken donor or license references;
- presents contradictory license, citation, or release metadata;
- silently relicenses historical or third-party material;
- claims completeness or rights clearance without evidence;
- uses a modified standard license under the original standard name;
- introduces an unreviewed name, mark, certification, or endorsement claim;
- uses design to imply authority or capability that is not established;
- converts continuity into unnecessary monitoring;
- omits a material TraceLog record;
- treats a policy or charter as an undisclosed additional restriction on a standard license.

## Documentary provenance

This protocol incorporates the stabilized file-scoped licensing architecture prepared under TraceLog `TL-2026-06-14-003` and remains subject to professional legal review where material legal obligations arise.
