# Fractal Repository Template Protocol

This file defines how a new Terra or FMP repository should inherit structure from donor layers instead of being rebuilt manually each time.

## Purpose

The goal is not to freeze one rigid repository shape.

The goal is to ensure that each new repository:

- stays readable for humans first;
- keeps theory and practice distinct;
- inherits governance and security from the donor layer;
- inherits publication and citation logic from the bibliography layer;
- inherits naming and identity rules from the naming and brand donor surfaces;
- stays traceable through a living operational record;
- preserves continuity without hidden monitoring;
- does not multiply entropy by inventing a new structure from scratch.

## Donor centers

### 1. Governance donor

Primary donor:

- `terra-legal`

Typical inherited files:

- `CONTRIBUTING.md`;
- `SECURITY.md`;
- `CODE_OF_CONDUCT.md`;
- `LICENSE.md` or an explicitly chosen compatible license surface;
- `CITATION.cff`;
- `PUBLICATION_RULE.md`;
- `REPOSITORY_PROTOCOL.md`.

### 2. Bibliography donor

Primary donor:

- the living bibliography layer maintained outside any single article draft.

This donor feeds references, evidence discipline, source lists, article-level citation repair, and repository-level citation alignment.

### 3. Trace donor

Primary donors:

- `TRACELOG_PROTOCOL.md`;
- `TRACELOG.md` or a repository-local trace;
- PLT and Universal TraceLog continuity files.

This donor preserves:

- provenance;
- reading order;
- repair history;
- Detox passes;
- why a repository was shaped the way it was.

### 4. Naming donor

Primary donors:

- `NAMING_STANDARD.md`;
- `NAMING_CARD_TEMPLATE.md`;
- `naming/registry/`.

This donor governs repository name, public title, acronym, aliases, migration, and deprecation.

### 5. Brand and identity donor

Primary donors:

- `BRAND_IDENTITY_STANDARD.md`;
- `VISUAL_IDENTITY_GUIDE.md`;
- `design/terra-legal.css` where web presentation is used.

This donor preserves recognition, accessibility, and restrained public identity.

### 6. Continuity donor

Primary donor:

- `INVISIBLE_SHADOW_CONTINUITY_BRIDGE.md`.

This donor prevents source loss, false closure, archive leakage, and excessive trace collection.

## Required layer split

A healthy repository should not collapse all content into one public surface.

At minimum, distinguish:

- theory;
- practice;
- governance and legal donor layer;
- publication layer;
- naming and identity layer;
- machine or automation layer;
- archive or shadow layer.

If a repository is mainly one layer, its README must say so openly.

## Template rule

Each new repository should be created from template logic, not from memory.

The template should contain:

- English-first README surface;
- visible but honest badge layer;
- linked donor governance files;
- naming status and Name Card relation;
- publication workflow spine;
- citation metadata spine;
- TraceLog entry path;
- identity and accessibility relation;
- boundary note saying what the repository is and is not.

## Living DNA rule

A repository should preserve the weave of living knowledge, not flatten it into one false center.

That means:

- do not treat one folder as the whole system;
- do not present archive residue as a finished public surface;
- do not merge theory, practice, identity, and automation into one undifferentiated root;
- do not erase relations between strands merely to simplify a README.

The repository should show a readable weave, while TraceLog prevents that weave from dissolving into chaos.

## Minimal onboarding sequence

1. Define whether the repository is theory, practice, legal, publication, or a mixed bridge.
2. Search the corpus under Rule 0.
3. Create or verify the Name Card.
4. Pull the governance donor layer from `terra-legal`.
5. Link the bibliography donor layer.
6. Add TraceLog and continuity relations.
7. Add the release and citation workflow spine when publication-facing.
8. Apply the brand and visual-identity rules.
9. Add a human-facing README that declares role, reading path, and ecosystem links.
10. Run Detox, validation, and audit.
11. Record creation in TraceLog.

## Detox rule

Before expanding a repository:

- remove mojibake;
- remove fake placeholders;
- remove contradictory duplicate service files;
- remove misleading machine-facing top surfaces;
- identify unreviewed names;
- separate historical visual exploration from current identity rules;
- identify hidden trace or privacy risk.

Only then add new structure.
