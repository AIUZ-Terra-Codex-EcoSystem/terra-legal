# TraceLog Protocol

**Repository:** `terra-legal`  
**Role:** normative donor protocol  
**Creator signature:** Abdurashid Abdukarimov — ORCID 0009-0000-6394-4912  
**Codex relation:** documentary continuity  
**Trace relation:** PLT / Universal TraceLog bridge  
**Σ-core relation:** documentary bridge only; no implementation claim

## Purpose

TraceLog preserves the continuity of documentary work without turning provenance into surveillance.

It records why a change occurred, which sources governed it, what meaning was preserved, which risks were detected, and how the result was validated.

TraceLog is not:

- hidden behavioral monitoring;
- user profiling;
- a substitute for consent;
- a store for secrets or unnecessary personal data;
- proof that an undocumented claim is true.

## Governing sequence

Every material change follows three explicit phases.

### Before the step

1. Identify the operator instruction.
2. Read the relevant donor and source files.
3. Apply Rule 0 and Rule 0.5.
4. Identify the target surface and its declared role.
5. Record expected risks, especially provenance loss, semantic drift, child-safety risk, manipulation, and false completeness.

### During the step

1. Keep the change attributable and role-limited.
2. Preserve original meaning and authorship.
3. Apply Detox Engine checks continuously.
4. Record files created, updated, moved, deprecated, or intentionally left unchanged.
5. Do not place credentials, private correspondence, personal identifiers, or confidential material in the public trace.

### After the step

1. Re-read the changed surface.
2. Verify internal links and donor references.
3. Apply validation and audit.
4. Record unresolved risks and blocked decisions.
5. Record the Git commit reference or equivalent integrity marker.

## Minimum TraceLog record

Each record should contain:

- `trace_id`;
- date and time in ISO 8601 form;
- operator instruction;
- target surface;
- declared role;
- sources read;
- change type;
- files affected;
- meaning-preservation note;
- Detox status before, during, and after;
- validation status;
- audit status;
- unresolved risks;
- commit reference;
- creator or executing agent role.

## Trace classes

- `public` — safe for the repository root and public review;
- `restricted` — contains operational detail that should remain outside the public repository;
- `private` — contains personal, security, or legally sensitive material and must not be committed publicly.

Only `public` traces belong in `TRACELOG.md`.

## Data minimization

A public trace must contain only what is necessary to reconstruct the documentary decision.

Do not record:

- access tokens;
- passwords or secrets;
- private email bodies;
- health or identity data not required for the documentary role;
- behavioral inference;
- speculative psychological interpretation;
- hidden analytics.

## Correction and deletion

A trace may be corrected when it contains factual error, broken provenance, or unnecessary personal data.

Corrections must:

1. preserve the existence of the correction event;
2. state what was repaired;
3. avoid reproducing removed sensitive content;
4. retain enough continuity to understand the change.

Deletion is permitted when required for safety, privacy, law, or removal of exposed secrets. The public record should state that a protected deletion occurred without repeating the removed material.

## Relationship to Invisible Shadow

TraceLog records explicit documentary continuity.

The Invisible Shadow bridge preserves the fact that meaningful relations may exist before or beyond formal capture. TraceLog must therefore avoid two errors:

- treating unrecorded reality as nonexistent;
- converting every living or contextual relation into compulsory data collection.

## Relationship to other donor files

This protocol operates together with:

- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md`;
- `VALIDATION_PROTOCOL.md`;
- `AUDIT_REGULATION.md`;
- `REPOSITORY_PROTOCOL.md`;
- `BIBLIOGRAPHY_SYNC_PROTOCOL.md`.

## Status language

Allowed completion states:

- `open`;
- `in progress`;
- `complete with unresolved risks`;
- `complete`;
- `blocked`;
- `superseded`.

No record may use `complete` while a material provenance, safety, licensing, or integrity issue remains unresolved.

## Documentary provenance

This bridge protocol is assembled from:

- Rule 0 and Rule 0.5 source-first logic;
- Terra Detox Engine operating rules;
- Terra repository and packaging protocols;
- PLT and Universal TraceLog continuity principles;
- the Invisible Shadow requirement that continuity not be reduced to compulsory capture;
- explicit operator instruction to apply Detox before, during, and after every step.
