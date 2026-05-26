# Terra Validation Protocol

This file defines the validation layer for Terra repository, publication, and documentary surfaces.

It replaces the earlier AIUZ-specific component checklist with a donor-grade protocol suitable for living cross-repository validation.

## Purpose

Validation confirms that a surface is not only present, but usable within the Terra ecosystem.

Validation must answer:

- does the surface belong here;
- does it perform the role it claims;
- is it coherent with directives, standards, and donor rules;
- is it safe, traceable, and publication-ready where applicable.

## Relationship to audit

Audit identifies structural disorder and risk.
Validation confirms operational and documentary readiness.

The two layers must work together but are not interchangeable.

## Validation inputs

Validation should begin with the following donor surfaces where relevant:

- `RULE_0_SOURCE_FIRST_PROTOCOL.md`
- `DETOX_ENGINE_PROTOCOL.md`
- `terra_living_protocols_constitution.md`
- `terra-main-directive-v7.0.md`
- `STANDARDS.md`
- `REPOSITORY_PROTOCOL.md`

## Minimal validation domains

### 1. Role validation

Check that the file or package matches the repository role and layer boundary.

### 2. Trace validation

Check that provenance, donor relation, and documentary role are visible.

### 3. Structural validation

Check that entry path, links, supporting files, and internal references remain coherent.

### 4. Safety validation

Check child safety, anti-manipulation safeguards, no-secret publication, and no harmful drift.

### 5. Publication validation

Where a surface is publication-facing, check:

- citation metadata;
- bibliography relation;
- language packaging role;
- public readability;
- packaging integrity.

## Minimal validation sequence

1. Identify the surface and its declared role.
2. Read the governing donor rules first.
3. Verify presence of required companion surfaces.
4. Verify structural coherence and readability.
5. Verify provenance and trace visibility.
6. Verify safety and detox compatibility.
7. Declare status:
   - valid;
   - valid with repair notes;
   - blocked pending repair.

## Validation outputs

Each validation record should state:

- target;
- role;
- governing rules consulted;
- status;
- blocking issues if any;
- next repair action if needed.

## Failure conditions

A surface should not be marked valid if it:

- contradicts Rule 0 or explicit-command operation;
- hides or loses provenance;
- depends on broken donor references;
- claims completeness while omitting essential supporting surfaces;
- preserves formatting while destroying meaning.

## Documentary provenance

This protocol is a donor-grade rewrite derived from:

- the earlier AIUZ validation checklist;
- `terra_fmp_research_mandate.md`;
- `AI_RULES.md`;
- `terra-main-directive-v7.0.md`;
- `terra_living_protocols_constitution.md`.
