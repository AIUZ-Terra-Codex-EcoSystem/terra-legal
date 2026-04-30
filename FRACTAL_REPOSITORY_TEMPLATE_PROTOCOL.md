# Fractal Repository Template Protocol

This file defines how a new Terra or FMP repository should inherit structure
from donor layers instead of being rebuilt manually each time.

## Purpose

The goal is not to freeze one rigid repository shape.

The goal is to ensure that each new repository:

- stays readable for humans first;
- keeps theory and practice distinct;
- inherits governance and security from the donor layer;
- inherits publication and citation logic from the bibliography layer;
- stays traceable through a living operational record;
- does not multiply entropy by inventing a new structure from scratch.

## Donor centers

Every repository should draw from the following donor centers.

### 1. Governance donor

Primary donor:

- `terra-legal`

Typical inherited files:

- `CONTRIBUTING.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`
- `LICENSE.md`
- `CITATION.cff`
- `PUBLICATION_RULE.md`
- `REPOSITORY_PROTOCOL.md`

### 2. Bibliography donor

Primary donor:

- the living bibliography layer maintained outside any single article draft

This donor feeds:

- references;
- evidence discipline;
- source lists;
- article-level citation repair;
- repository-level `CITATION.cff` alignment.

### 3. Trace donor

Primary donor:

- TraceLog and continuity files

This donor preserves:

- provenance;
- reading order;
- repair history;
- detox passes;
- why a repository was shaped the way it was.

## Required layer split

A healthy repository should not collapse all content into one public surface.

At minimum, distinguish:

- theory;
- practice;
- governance and legal donor layer;
- publication layer;
- machine or automation layer;
- archive or shadow layer.

If a repository is mainly one of these layers, its README must say so openly.

## Template rule

Each new repository should be created from a template logic, not from memory.

That template logic should contain:

- English-first README surface;
- visible badge layer;
- linked donor governance files;
- publication workflow spine;
- citation metadata spine;
- boundary note saying what the repository is and what it is not.

## Living DNA rule

A repository should preserve the weave of living knowledge, not flatten it into
one false center.

That means:

- do not treat one folder as the whole system;
- do not present archive residue as a finished public surface;
- do not merge theory, practice, and automation into one undifferentiated root;
- do not erase the relation between strands just to make a shallow README.

The repository should show a readable weave, while TraceLog prevents that weave
from dissolving into chaos.

## Minimal onboarding sequence for a new repository

1. Define whether the repository is theory, practice, legal, publication, or a mixed bridge.
2. Pull the governance donor layer from `terra-legal`.
3. Pull or link the bibliography donor layer.
4. Add the release and citation workflow spine if the repository is publication-facing.
5. Add a human-facing README that declares role, reading path, and ecosystem links.
6. Record the creation in TraceLog.

## Detox rule

Before expanding a repository:

- remove mojibake;
- remove fake placeholders;
- remove contradictory duplicate service files;
- remove misleading machine-facing top surfaces.

Only then add new structure.
