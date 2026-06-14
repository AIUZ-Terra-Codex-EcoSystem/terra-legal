# Contributing to terra-legal

`terra-legal` is a normative donor repository. Contributions may affect licensing, governance, child safety, privacy, publication, naming, identity, or cross-repository inheritance. Changes therefore require visible provenance and review.

## Before contributing

Read:

1. [LEGAL.md](./LEGAL.md)
2. [CONTRIBUTOR_TERMS.md](./CONTRIBUTOR_TERMS.md)
3. [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
4. [RESPONSIBLE_USE_POLICY.md](./RESPONSIBLE_USE_POLICY.md)
5. [RULE_0_SOURCE_FIRST_PROTOCOL.md](./RULE_0_SOURCE_FIRST_PROTOCOL.md)
6. [DETOX_ENGINE_PROTOCOL.md](./DETOX_ENGINE_PROTOCOL.md)
7. [TRACELOG_PROTOCOL.md](./TRACELOG_PROTOCOL.md)
8. [DOCUMENTATION-STANDARD.md](./DOCUMENTATION-STANDARD.md)

## Repository setup

```bash
git clone https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal.git
cd terra-legal
git checkout -b feature/clear-change-name
```

Do not use the obsolete repository name `.terra-legal` in new links, scripts, submodules, or documentation.

## Contribution scope

Useful contributions include:

- correcting legal or licensing contradictions;
- improving provenance and source references;
- repairing broken links and encoding;
- adding verified translations;
- improving accessibility and documentary clarity;
- reviewing privacy, child-safety, security, or responsible-use language;
- adding file-level SPDX and REUSE information;
- identifying third-party rights or dependency obligations;
- testing release, citation, audit, and publication workflows.

Do not submit:

- confidential material;
- credentials or access tokens;
- personal data not necessary for the public record;
- copied legal text without source and rights information;
- fabricated citations, authority, partnerships, certifications, or validation;
- unreviewed commercial fee schedules;
- a new blanket license for the whole ecosystem without a rights audit.

## Licensing of contributions

This is a multi-license repository.

A contribution follows the license assigned to the target file or directory through an SPDX header, adjacent `.license` file, `REUSE.toml`, or explicit notice.

Typical classifications are:

- documentary material: `CC-BY-4.0`;
- software and implementation material: `Apache-2.0`.

Unclassified files must be classified before merge. Submission does not silently relicense third-party or historically licensed material.

## Contributor certification

Material pull requests should include:

```text
Signed-off-by: Full Name <email>
```

The sign-off certifies the statements in [CONTRIBUTOR_TERMS.md](./CONTRIBUTOR_TERMS.md), including that the contributor has the right to submit the material. It is not a copyright assignment.

## Required workflow

1. Search the repository and donor corpus before drafting.
2. Open an issue for a material legal, governance, privacy, licensing, trademark, or policy change.
3. Create a focused branch.
4. Make the smallest coherent change.
5. Record sources, assumptions, affected files, and unresolved risks.
6. Apply Detox before, during, and after the change.
7. Update TraceLog where the change is material.
8. Submit a pull request with a clear rationale.
9. Do not merge until required review is complete.

## Pull request description

Use this structure:

```markdown
## Purpose

## Source-first record
- Sources read:
- Existing files affected:

## Change type
- [ ] Documentation
- [ ] Licensing or rights
- [ ] Governance
- [ ] Responsible use or child safety
- [ ] Privacy or security
- [ ] Naming or brand
- [ ] Workflow or implementation
- [ ] Translation

## Rights and provenance
- Applicable license:
- Third-party material:
- Contributor sign-off:

## Detox
- Before:
- During:
- After:

## Validation
- Links checked:
- Metadata checked:
- Unresolved risks:

## TraceLog
- Trace ID:
```

## Review levels

### Editorial

Typos, formatting, and non-substantive link repair may be approved by the maintainer after validation.

### Normative

Changes to governance, validation, audit, publication, naming, identity, or responsible-use rules require a documented rationale and TraceLog entry.

### Legal

Changes to licenses, contributor rights, copyright ownership, privacy obligations, commercial terms, trademarks, jurisdiction, dispute resolution, warranties, or liability require a dedicated legal review. Professional counsel may be required before merge or release.

## Child-safety and security reports

Do not place sensitive evidence in a public issue.

Use the process in [SECURITY.md](./SECURITY.md) and minimize personal data.

## Maintainer

Abdurashid Abdulkhamitovich Abdukarimov  
ORCID: 0009-0000-6394-4912  
Email: `a.abdukarimov@fractal-metascience.org`
