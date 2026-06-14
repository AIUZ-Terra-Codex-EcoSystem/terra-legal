# TraceLog Protocol

**Repository:** `terra-legal`  
**Role:** normative donor protocol  
**Creator signature:** Abdurashid Abdukarimov — ORCID 0009-0000-6394-4912  
**Codex relation:** documentary continuity  
**Trace relation:** PLT / Universal TraceLog bridge  
**Σ-core relation:** documentary bridge only; no implementation claim

## Purpose

TraceLog preserves the continuity of documentary work without turning provenance into surveillance.

It records why a change occurred, which sources governed it, what meaning was preserved, what evidence supported it, which risks were detected, how it was reviewed, and whether publication was authorized.

TraceLog is not:

- hidden behavioral monitoring;
- user profiling;
- a substitute for consent;
- a store for credentials or unnecessary personal data;
- proof that an undocumented claim is true;
- a substitute for independent or professional review.

## Governing sequence

Every material change follows three explicit phases.

### Before the step

1. Identify the operator instruction.
2. Read relevant donor and source files.
3. Apply Rule 0 and Rule 0.5.
4. Identify target, declared role, object class, and rights status.
5. List material claims and expected evidence.
6. Record expected risks, especially provenance loss, semantic drift, child-safety risk, manipulation, false completeness, and publication overclaim.
7. Identify the prior repository state or other correction reference.

### During the step

1. Keep the change attributable and role-limited.
2. Preserve original meaning, authorship, rights, and provenance.
3. Apply Detox continuously.
4. Record files created, updated, moved, deprecated, or intentionally left unchanged.
5. Record evidence actually examined, not evidence merely expected.
6. Record whether review is internal, operator, domain, or professional.
7. Do not place credentials, private correspondence, unnecessary personal identifiers, or confidential material in the public trace.

### After the step

1. Re-read the changed surface.
2. Verify internal links and donor references.
3. Verify material claims against evidence.
4. Apply validation, independent-review rules, and audit.
5. Classify unresolved risks and exclusions.
6. Record publication gate: `GO`, `GO WITH EXCLUSIONS`, `HOLD`, or `BLOCK`.
7. Record correction path and prior-state reference where material.
8. Record commit, release, or equivalent integrity marker.

## Minimum TraceLog record

Each record should contain:

- `trace_id`;
- ISO 8601 date and time;
- operator instruction;
- target surface;
- declared role and object class;
- sources read;
- evidence examined and evidence status;
- change type;
- files affected;
- meaning-preservation note;
- Detox status before, during, and after;
- validation status;
- internal or independent-review status;
- audit status;
- risk category and severity;
- exclusions and unresolved risks;
- publication gate;
- correction or prior-state reference;
- commit or release reference;
- creator or executing-agent role.

## Trace classes

- `public` — safe for the repository root and public review;
- `restricted` — contains operational detail that should remain outside the public repository;
- `private` — contains personal, security, or legally sensitive material and must not be committed publicly.

Only public traces belong in the public repository.

## Data minimization

A public trace contains only what is necessary to reconstruct the documentary decision.

Do not record access credentials, private email bodies, unnecessary health or identity data, behavioral inference, speculative psychological interpretation, or hidden analytics.

## Evidence language

Allowed evidence states:

- `supported`;
- `partially supported`;
- `unsupported`;
- `contradicted`;
- `not applicable`;
- `not assessed`.

`Not assessed` must never be recorded as `supported`.

## Review language

Allowed review states:

- `internal review complete`;
- `operator review complete`;
- `domain review complete`;
- `professional review complete`;
- `review limited`;
- `review pending`.

An internal review must not be labeled independent external review.

## Risk language

Use severity:

- `critical`;
- `high`;
- `medium`;
- `low`;
- `not applicable`.

Use status:

- `open`;
- `contained`;
- `accepted`;
- `resolved`;
- `superseded`.

## Correction and deletion

A trace may be corrected when it contains factual error, broken provenance, or unnecessary personal data.

Corrections must preserve the existence of the correction event, state what was repaired, avoid reproducing removed sensitive content, and retain enough continuity to understand the change.

A protected deletion may occur when required for safety, privacy, or law. The public record should state that a protected deletion occurred without repeating removed material.

## Relationship to Invisible Shadow

TraceLog records explicit documentary continuity.

The Invisible Shadow bridge preserves the fact that meaningful relations may exist before or beyond formal capture. TraceLog must therefore avoid treating unrecorded reality as nonexistent or converting every living relation into compulsory data collection.

## Relationship to other donor files

This protocol operates together with:

- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `EVIDENCE_AND_PROVENANCE_PROTOCOL.md`;
- `INDEPENDENT_REVIEW_PROTOCOL.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `AUDIT_COMPLETION_PROTOCOL.md`;
- `RISK_AND_RELEASE_GATE_PROTOCOL.md`;
- `VALIDATION_AUDIT_STACK.md`;
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md`;
- `REPOSITORY_PROTOCOL.md`;
- `BIBLIOGRAPHY_SYNC_PROTOCOL.md`.

## Completion states

- `open`;
- `in progress`;
- `complete with unresolved risks`;
- `complete`;
- `blocked`;
- `superseded`.

No record may use `complete` while a material provenance, safety, licensing, evidence, review, or integrity issue remains unresolved inside the declared scope.

## Documentary provenance

This bridge protocol is assembled from Rule 0, NULLO, Detox, PLT and Universal TraceLog continuity, repository and packaging protocols, evidence and reproducibility requirements, independent-review logic, risk classification, publication gates, and the Invisible Shadow anti-capture boundary.