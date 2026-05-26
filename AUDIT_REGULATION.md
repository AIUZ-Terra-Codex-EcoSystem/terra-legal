# Terra Audit Regulation

This file defines the audit layer for documentary, repository, publication, and bridge surfaces within the Terra ecosystem.

It replaces the too-narrow AIUZ-only wording of the earlier audit draft with a donor-grade regulation suitable for cross-repository use in `terra-legal`.

## Purpose

Audit exists to verify that a public surface is:

- structurally coherent;
- documentary traceable;
- safe for publication;
- aligned with living directives and repository role;
- free from hidden fragmentation, silent drift, or public-facing distortion.

## Audit scope

Use this regulation when reviewing:

- repository root surfaces;
- living indexes;
- directives and protocol files;
- publication-facing bridge documents;
- release bundles and documentary packages;
- audit, validation, and governance files themselves.

## Non-negotiable audit rules

### 1. Source-first rule

No audit may certify a surface that was assembled without reading the donor corpus relevant to that surface.

### 2. No implicit action rule

Audit may identify problems and prepare repair surfaces, but it must not silently convert analysis into unannounced structural change.

### 3. Human-readable rule

Audit outputs must remain reviewable by humans and must not collapse into opaque machine-only diagnostics.

### 4. Child-safety and dignity rule

Any surface that weakens child safety, dignity, or anti-manipulation safeguards fails audit regardless of formatting quality.

## Audit levels

- `surface`
  - check readability, links, entry path, role clarity
- `structural`
  - check layer boundaries, donor relations, provenance, duplication
- `publication`
  - check citation, evidence relation, packaging role, public safety
- `protocol`
  - check consistency with directives, Rule 0, detox, and living protocol rules

## Minimal audit sequence

1. Identify the target surface and its declared repository role.
2. Read the relevant donor rules, directives, or protocol sources.
3. Check whether the surface matches its declared role.
4. Check for mojibake, dead links, false exhaustiveness, broken provenance, or archive leakage.
5. Check whether the surface contradicts:
   - Rule 0;
   - Detox Engine logic;
   - explicit-command operation;
   - living protocol rules.
6. State the audit result and required repair path.

## Required audit output

An audit output should identify:

- target surface;
- repository role;
- audit level used;
- detected fragmentation or risk;
- recommended action:
  - keep;
  - clarify;
  - detox;
  - extract;
  - re-layer;
  - relocate;
  - deprecate.

## What fails audit immediately

- fabricated provenance;
- public secrets;
- false claims that a partial surface is the whole system;
- broken donor references presented as valid;
- machine-generated noise presented as documentary authority;
- assistant initiative replacing operator intent.

## Documentary provenance

This regulation is a donor-grade rewrite based on:

- earlier `AIUZ_Audit_Regulation` logic;
- `terra-main-directive-v7.0.md`;
- `terra_living_protocols_constitution.md`;
- `RULE_0_SOURCE_FIRST_PROTOCOL.md`;
- `DETOX_ENGINE_PROTOCOL.md`;
- `REPOSITORY_PROTOCOL.md`.
