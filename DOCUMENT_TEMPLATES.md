# Terra Document Templates

**Repository:** `terra-legal`  
**Purpose:** reviewable templates for technical, governance, legal, audit, trace, publication, and rights documents

## Template rule

A template is a structure, not evidence.

Placeholders must be replaced with verified information or removed. Do not publish a template containing invented metrics, certification, compliance, encryption, users, partners, legal status, performance, or implementation claims.

Every material document follows:

1. Rule 0 source review;
2. object and rights classification;
3. Detox before, during, and after drafting;
4. validation;
5. audit;
6. TraceLog recording where material.

---

## Template 1 — Repository README

```markdown
# [Repository name]

> [One factual sentence describing the repository.]

## Repository role

This repository is:

- [primary layer and function]

This repository is not:

- [important boundary]

## Current status

- Status: [concept / draft / prototype / implemented / released / archived / blocked]
- Last verified: [YYYY-MM-DD]
- Verification method: [method or `not yet verified`]

## Reading path

1. [first file]
2. [second file]
3. [third file]

## Main contents

- `[path]` — [role]
- `[path]` — [role]

## Licensing and rights

- Scope: [`LICENSE` / `LEGAL.md`]
- File-level records: [`REUSE.toml` / SPDX headers / adjacent `.license` files]
- Third-party notices: [`THIRD_PARTY_NOTICES.md`]
- Historical grants or exclusions: [summary]

## Citation

- `CITATION.cff`
- DOI: [verified DOI or `not assigned`]

## Governance, security, and responsible use

- `GOVERNANCE.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `RESPONSIBLE_USE_POLICY.md` or donor link

## Provenance and limitations

- Donor sources: [list]
- Known limitations: [list]
- Unresolved review: [list]

## Maintainer

[Verified name, role, ORCID, and contact]
```

---

## Template 2 — Technical specification

```markdown
# [Component name] — Technical Specification

## Document control

- Version: [version]
- Status: [draft / review / implemented / tested / deprecated]
- Date: [YYYY-MM-DD]
- Maintainer: [verified person or entity]
- Applicable license: [SPDX identifier or rights note]
- Trace ID: [ID]

## Purpose

[Problem and intended function.]

## Scope

Included:

- [item]

Excluded:

- [item]

## Current implementation status

- Implemented: [verified functions]
- Proposed: [not yet implemented functions]
- External dependencies: [list]

## Architecture

### Components

| Component | Role | Input | Output | Status |
|---|---|---|---|---|
| [name] | [role] | [input] | [output] | [status] |

### Data flows

[Text description and diagram link.]

## Security and privacy

- Data classes: [public / restricted / private]
- Secrets handling: [method]
- Retention: [rule]
- Access control: [method]
- Threat assumptions: [list]
- Unresolved risks: [list]

## Child and vulnerable-person safeguards

[Applicable only when relevant. State `not applicable` with reason rather than inventing controls.]

## Interfaces

[API, file, protocol, command, or user interface specifications.]

## Dependencies and third-party rights

| Component | Source | Version | License | Notice required |
|---|---|---|---|---|
| [name] | [source] | [version] | [license] | [yes/no/details] |

## Verification

| Requirement | Test or evidence | Result | Date |
|---|---|---|---|
| [requirement] | [method] | [pass/fail/not tested] | [date] |

## Limitations

[Known technical, empirical, legal, or operational limitations.]

## Change history

[Material changes and TraceLog references.]
```

---

## Template 3 — Governance or policy document

```markdown
# [Policy or governance title]

## Status and authority

- Status: [draft / active / superseded / archived]
- Decision owner: [verified role]
- Effective date: [date or `not yet effective`]
- Applies to: [defined participants or surfaces]
- Does not apply to: [boundary]
- Trace ID: [ID]

## Purpose

[Purpose and problem addressed.]

## Definitions

[Only necessary defined terms.]

## Roles and authority

| Role | Authority | Limits | Appointment or source |
|---|---|---|---|
| [role] | [authority] | [limits] | [source] |

## Decision process

1. [proposal]
2. [evidence review]
3. [conflict review]
4. [decision]
5. [record]
6. [appeal or correction]

## Emergency process

[Temporary protective action, evidence preservation, data minimization, and post-action review.]

## Transparency and privacy

[What is public, restricted, or private.]

## Conflicts of interest

[Disclosure and recusal rules.]

## Review and amendment

[How material changes are proposed, reviewed, approved, and traced.]

## Limitations

[Jurisdictional, institutional, operational, and professional-review limits.]
```

---

## Template 4 — Licensing and rights scope

```markdown
# [Repository or package] — Licensing and Rights Scope

## Object classes

- Documentation: [scope]
- Software: [scope]
- Data or corpus: [scope]
- Media: [scope]
- Brand and marks: [scope]
- Third-party material: [scope]
- Archived material: [scope]

## Controlling order

1. File-level SPDX header or adjacent `.license` file
2. `REUSE.toml`
3. Directory-specific notice
4. `LEGAL.md`
5. Version-specific historical notice

## Standard licenses

| Object class | License | SPDX identifier | Canonical text |
|---|---|---|---|
| [class] | [license] | [identifier] | [path] |

## Historical grants

[Earlier versions, dates, commits, and licenses.]

## Exclusions

- [third-party item]
- [publisher-controlled version]
- [logo or mark]
- [confidential or private material]

## Rights holder and contributors

[Verified rights information and unresolved consent.]

## Metadata alignment

- README: [status]
- `CITATION.cff`: [status]
- Package metadata: [status]
- Release: [status]
- DOI or deposit: [status]

## Professional review

[Questions requiring qualified legal review.]
```

---

## Template 5 — Third-party rights record

```markdown
# Third-Party Record — [Item or component]

- Name: [name]
- Source: [stable source]
- Version or date: [version]
- Creator or rights holder: [verified name]
- Material type: [code / text / image / dataset / standard / template]
- Rights status: [license / public domain / permission / exception / unknown]
- License identifier: [SPDX or exact rights statement]
- Required notice: [text or path]
- Modification: [none / description]
- Redistribution allowed: [yes / no / limited / unknown]
- Repository location: [path]
- Review date: [date]
- Reviewer: [role]
- Unresolved risks: [list]
```

---

## Template 6 — Audit record

```markdown
# Audit — [Target] — [Date]

- Trace ID: [ID]
- Target: [repository/file/release]
- Branch or version: [reference]
- Audit levels: [surface / rights / structural / publication / protocol]
- Status: [status]

## Operator instruction

[Instruction.]

## Sources read

- [source]

## Findings before change

- [finding]

## Changes reviewed

- [file and role]

## Detox

### Before
[status]

### During
[status]

### After
[status]

## Validation

- Role: [result]
- Rights: [result]
- Metadata: [result]
- Third-party material: [result]
- Safety and privacy: [result]
- Naming and identity: [result]
- Continuity: [result]

## Exclusions and unresolved risks

- [risk]

## Conclusion

[valid / valid with exclusions / prepared for review / blocked]
```

---

## Template 7 — TraceLog entry

```markdown
## [Trace ID]

- Status: [status]
- Operator instruction: [instruction]
- Target: [surface]
- Branch or version: [reference]

### Source-first record

[Sources read and why they were relevant.]

### Detox before

[Findings and risks.]

### Changes

Created:
- [file]

Updated:
- [file]

### Detox during

[Controls applied.]

### Validation and audit

- Validation status: [status]
- Audit record: [path]

### Detox after

[Result and unresolved conditions.]

### Commit and release references

- [reference]
```

---

## Template 8 — Scholarly publication rights record

```markdown
# Publication Rights Record — [Title]

- Author or co-authors: [verified names]
- ORCID: [identifiers]
- Work type: [preprint / accepted manuscript / version of record / monograph]
- Repository file: [path]
- Publisher or journal: [name]
- Submission or article ID: [ID]
- DOI: [verified DOI or `not assigned`]
- Publication agreement checked: [yes/no/date]
- Repository deposit allowed: [yes/no/conditions]
- License applied by author: [license]
- Publisher license: [license]
- Embargo: [date or none]
- Figures and third-party content: [rights status]
- Co-author consent: [status]
- Review status: [status]
- Trace ID: [ID]
```

---

## Completion checklist

Before publishing a document created from these templates:

- [ ] All placeholders were replaced or removed
- [ ] Role and status are accurate
- [ ] Sources and provenance are visible
- [ ] Rights and third-party material are classified
- [ ] No credentials or unnecessary personal data are present
- [ ] No unsupported certification, compliance, security, partnership, or performance claim remains
- [ ] Names and contacts are verified
- [ ] Links and identifiers work
- [ ] Metadata agrees with licenses and releases
- [ ] Detox was completed before, during, and after drafting
- [ ] Validation and audit are recorded
- [ ] TraceLog is updated where material
