# Terra Validation Protocol

This file defines validation for Terra repository, licensing, publication, documentary, naming, identity, trace, responsible-use, continuity, evidence, and release surfaces.

## Purpose

Validation confirms that a surface is not only present, but usable and internally coherent within its declared role.

Validation must answer:

- does the surface belong here;
- does it perform the role it claims;
- are rights, provenance, evidence, limitations, and review status visible;
- is it coherent with directives, standards, licensing, naming, identity, and donor rules;
- is it safe, traceable, reproducible where relevant, and publication-ready within its stated scope.

## Relationship to audit

Audit identifies disorder, contradiction, unsupported claims, and risk.

Validation confirms readiness against declared requirements.

Independent review challenges the producing pass and its evidence.

The publication gate converts the results into `GO`, `GO WITH EXCLUSIONS`, `HOLD`, or `BLOCK`.

These layers work together but are not interchangeable.

## Validation inputs

Begin with the relevant controlling surfaces:

- `LICENSE`;
- `LEGAL.md`;
- `REUSE.toml`;
- `THIRD_PARTY_NOTICES.md`;
- `RELICENSING_PROTOCOL.md`;
- `RESPONSIBLE_USE_POLICY.md`;
- `TRADEMARK_POLICY.md`;
- `CONTRIBUTOR_TERMS.md`;
- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `EVIDENCE_AND_PROVENANCE_PROTOCOL.md`;
- `INDEPENDENT_REVIEW_PROTOCOL.md`;
- `RISK_AND_RELEASE_GATE_PROTOCOL.md`;
- `VALIDATION_AUDIT_STACK.md`;
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

Check that the file or package matches the repository role and does not claim authority, certification, partnership, scientific validation, legal advice, production readiness, or institutional status that has not been established.

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

### 3. Evidence and claim validation

For each material claim, check:

- exact claim and scope are stated;
- supporting evidence is identifiable and appropriate to the claim;
- source and date checked are recorded;
- uncertainty, exclusions, alternative explanations, and failure conditions are visible;
- simulated examples and draft code are not presented as observed results;
- generated percentages are not used without a defined method and evidence;
- a badge, filename, workflow, or internal policy is not treated as proof of external compliance, publication, security, certification, or scientific validity;
- evidence status is declared as `supported`, `partially supported`, `unsupported`, `contradicted`, `not applicable`, or `not assessed`.

A material claim with status `unsupported`, `contradicted`, or `not assessed` must be removed, repaired, or explicitly excluded before publication.

### 4. Metadata validation

Check consistency among:

- README and badges;
- `CITATION.cff`;
- package and workflow metadata;
- release notes and tags;
- Zenodo and DOI records;
- website footers and downloadable bundles.

A placeholder, workflow badge, or draft field is not proof of a completed release, DOI deposit, audit, or certification.

### 5. Trace and provenance validation

Check that donor relation, operator instruction, sources, affected files, changes, decisions, evidence, review, gate state, and unresolved risks are visible.

Public TraceLog records must exclude secrets, unnecessary personal data, and protected evidence.

### 6. Structural validation

Check that entry path, links, companion files, file names, internal references, and historical pointers remain coherent.

### 7. Reproducibility and integrity validation

Where relevant, check:

- the procedure or test can be repeated;
- inputs, environment, dependency versions, expected output, and observed output are recorded safely;
- commit, release, checksum, or equivalent integrity reference is present;
- negative cases and failure behavior are considered;
- repository history remains correctable through an ordinary corrective change;
- source and archive provenance have not been destroyed.

### 8. Safety and responsible-use validation

Check:

- child and vulnerable-person safety;
- anti-manipulation safeguards;
- privacy and data minimization;
- no-secret publication;
- human oversight and escalation paths;
- scientific and documentary integrity;
- no harmful or deceptive drift;
- local or network-accessible services are not described as production-ready without a deployment and security review.

### 9. Contributor validation

Where a contribution is accepted, check:

- contributor has certified the right to submit;
- target file license is known and compatible;
- third-party material and employer, publisher, client, or co-author restrictions are disclosed;
- attribution is preserved;
- AI assistance has not introduced fabricated provenance or unauthorized copying;
- no ownership transfer is implied without a separate written agreement;
- contributor terms apply prospectively and their effective boundary is visible.

### 10. Independent-review validation

Check:

- producing and reviewing roles are identified;
- limited independence is disclosed;
- material legal, safety, security, scientific, and public-reliance claims receive an appropriate review level;
- reviewer questions and unresolved disagreements are recorded;
- internal review is not mislabeled as external or independent certification;
- protected decisions remain with the operator or qualified professional.

### 11. Naming validation

Where a public name is introduced or changed, check:

- Name Card exists;
- primary role is unambiguous;
- language review is visible;
- legal and trademark review status is not overstated;
- aliases and deprecated forms are preserved;
- decision is connected to TraceLog.

### 12. Identity and trademark validation

Where a public visual or naming surface is changed, check:

- Terra identity rules are applied consistently;
- accessibility remains intact;
- color is not the sole carrier of meaning;
- excessive motion and promotional residue are absent;
- legal meaning remains clearer, not more decorative;
- design does not imply registration, endorsement, certification, partnership, or capability that is not established;
- `TRADEMARK_POLICY.md` is respected.

### 13. Continuity and correction validation

Check:

- source and derivative relation;
- migration and alias continuity;
- historical license and release continuity;
- missing context is marked rather than invented;
- archive or shadow material is not presented as the live public surface;
- trace collection does not exceed its declared purpose;
- a material change has an identified prior state and can be corrected without hiding history.

### 14. Publication and release-gate validation

Where a surface is publication-facing, check:

- author and contributor records;
- citation and bibliography relation;
- publisher and co-author rights where applicable;
- release classification and license scope;
- language packaging role;
- public readability;
- package integrity;
- third-party exclusions;
- DOI and deposit facts are verified rather than inferred;
- open risks have severity and ownership;
- exclusions are visible;
- an explicit gate decision is recorded: `GO`, `GO WITH EXCLUSIONS`, `HOLD`, or `BLOCK`.

## Minimal validation sequence

1. Identify the target surface and declared role.
2. Read governing and external sources first.
3. Classify the object and rights status.
4. Verify claims, evidence, provenance, and uncertainty.
5. Verify ownership, contributors, third-party material, and historical grants.
6. Verify required companion files and canonical license texts.
7. Verify structural coherence and readability.
8. Verify metadata consistency.
9. Verify reproducibility and integrity where relevant.
10. Verify naming, identity, and trademark coherence where applicable.
11. Verify safety and Detox compatibility.
12. Record independent-review status.
13. Classify open risks.
14. Issue the publication gate.
15. Verify continuity and a correctable change path.
16. Record TraceLog.

## Validation output

Each validation record states:

- target and role;
- branch, commit, release, or version;
- controlling rules and sources consulted;
- object and rights classification;
- material claims and evidence status;
- validation status;
- independent-review status;
- risk and gate state;
- exclusions and unresolved risks;
- next repair or review action;
- TraceLog reference;
- prior state or correction reference where material.

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
- treats a policy or charter as an undisclosed additional restriction on a standard license;
- relies on simulated evidence, fabricated precision, keyword self-validation, or unsupported production-readiness;
- labels an internal pass as independent external review;
- lacks an explicit release decision for a publication-facing surface.

## Documentary provenance

This protocol incorporates the stabilized file-scoped licensing architecture prepared under TraceLog `TL-2026-06-14-004` and the cleaned evidence, independent-review, risk, reproducibility, correction, and release-gate methods recovered from earlier Terra, AIUZ, FMP research, validation, audit, and restoration materials.