# Terra Validation and Audit Stack

**Repository:** `terra-legal`  
**Role:** controlling map for validation, audit, Detox, evidence, release, trace, and recovery  
**Status:** interim publication-ready protocol approved for prospective use

## Purpose

This document defines the complete order of checks required before a Terra repository surface is described as reviewed, ready, released, or published.

Validation and audit are necessary but not sufficient on their own. A complete control stack also requires evidence, independent review, risk classification, a release gate, TraceLog, and recovery planning.

## Controlling sequence

1. **Rule 0 and NULLO** — search the existing corpus and freeze assumptions before action.
2. **Scope and object classification** — identify the target, repository layer, object type, rights status, and declared role.
3. **Evidence and provenance** — connect each material claim to traceable evidence and record uncertainty, exclusions, and failure modes.
4. **Validation** — verify that the surface performs its declared role and meets stated requirements.
5. **Independent review** — obtain a review distinct from the producing pass when risk or public impact is material.
6. **Audit** — detect contradiction, unsupported authority, rights conflict, security risk, fragmentation, and publication drift.
7. **Risk classification** — assign severity and ownership to unresolved findings.
8. **Detox** — remove manipulative language, fabricated precision, self-certification, status inflation, simulated evidence, and autonomous drift.
9. **Security, privacy, and safety check** — verify secrets, personal data, child-safety, access, deployment exposure, and incident handling.
10. **Reproducibility and integrity check** — verify files, links, checksums where used, environment or workflow evidence, and repeatability of relevant tests.
11. **Publication and release gate** — issue a recorded decision: `GO`, `GO WITH EXCLUSIONS`, `HOLD`, or `BLOCK`.
12. **TraceLog** — record instruction, sources, changes, evidence, risk, review, validation, audit, Detox, gate status, and integrity marker.
13. **Recovery and rollback** — preserve a reversible path and define containment if publication or deployment proves unsafe.

No later step erases an unresolved earlier failure.

## Required control surfaces

- `RULE_0_SOURCE_FIRST_PROTOCOL.md`
- `DETOX_ENGINE_PROTOCOL.md`
- `EVIDENCE_AND_PROVENANCE_PROTOCOL.md`
- `VALIDATION_PROTOCOL.md`
- `INDEPENDENT_REVIEW_PROTOCOL.md`
- `AUDIT_REGULATION.md`
- `RISK_AND_RELEASE_GATE_PROTOCOL.md`
- `SECURITY.md`
- `PUBLICATION_RULE.md`
- `FULL_PACKAGING_PROTOCOL.md`
- `TRACELOG_PROTOCOL.md`
- `RECOVERY_AND_ROLLBACK_PROTOCOL.md`

## Evidence rule

A statement is not validated merely because:

- it appears in code or documentation;
- an AI generated a score;
- a script found expected keywords;
- a badge or workflow exists;
- a document calls itself final, compliant, certified, secure, or production-ready;
- a simulated example returned a passing result.

Material conclusions require identifiable evidence appropriate to the claim.

## Separation of roles

- the producing pass creates or changes the surface;
- validation checks declared requirements;
- independent review challenges assumptions and evidence;
- audit checks the wider system, contradictions, and risk;
- the operator makes protected legal, publication, and strategic decisions;
- qualified professionals review jurisdiction-specific or specialist matters where required.

One person may perform more than one documentary role in a small project, but the record must disclose that independence was limited. Self-review must not be described as independent review.

## Status vocabulary

### Validation

- `valid`
- `valid with exclusions`
- `valid with repair notes`
- `prepared for review`
- `blocked pending evidence`
- `blocked pending rights review`
- `blocked pending professional review`

### Audit

- `pass`
- `pass with findings`
- `conditional pass`
- `fail`
- `not assessed`

### Release gate

- `GO` — all required controls passed for the declared scope.
- `GO WITH EXCLUSIONS` — publication is allowed only with explicit exclusions and limitations.
- `HOLD` — repair or operator decision is required before publication.
- `BLOCK` — critical safety, security, rights, provenance, or integrity failure prevents publication.

## Prohibited shortcuts

- no invented percentages or scores without a defined method and evidence;
- no self-certification by keyword matching;
- no use of draft code as evidence of deployed capability;
- no automatic conversion of an audit into legal compliance or certification;
- no release based only on a passing CI check;
- no silent removal of unresolved risks from the public record;
- no publication of secrets, private correspondence, unnecessary personal data, or sensitive incident evidence;
- no destructive rewrite of source or archive provenance.

## Minimal publication record

Before publication, the record must state:

- target and declared role;
- commit or release identity;
- sources and evidence consulted;
- rights and third-party status;
- validation result;
- independent-review status;
- audit result;
- Detox result;
- open risks and exclusions;
- release-gate decision;
- TraceLog ID;
- rollback or containment reference.

## Documentary provenance

This stack is a cleaned synthesis of earlier Terra and AIUZ validation, audit, development, security, recovery, publication, and research protocols. It preserves their useful control logic while excluding unsupported compliance percentages, simulated evidence, self-issued certification levels, and unverified production-readiness claims.