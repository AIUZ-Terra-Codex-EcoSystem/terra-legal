# GitHub Layer Model

## Purpose

This file defines how the Terra / FMP GitHub ecosystem should be organized so
that dense meaning does not collapse into one flat repository story.

The goal is not simplification by destruction.
The goal is legibility through layer separation.

## Core layers

### 1. Profile and organization surface

Human entry points.

These surfaces should answer:

- where to start;
- what is theory;
- what is practice;
- where legal and donor rules live;
- where publication-facing material lives;
- where design, philosophy, and branch projects live.

They should stay:

- English-first;
- badge-rich but honest;
- readable without local context;
- free from archive residue and machine noise.

### 2. Theory layer

Repositories whose main role is conceptual, analytical, philosophical, or
research-theoretical.

Typical contents:

- paradigm statements;
- monograph branches;
- theory papers;
- NULLO / PLT / UCOMM / EUO analytical work;
- world comparison tables;
- foundation proposals.

### 3. Practice layer

Repositories whose main role is implementation, experimentation, deployment,
translation, tooling, or demonstrator work.

Typical contents:

- AIUZ branches;
- UST and translation tooling;
- APIs;
- demos;
- implementation architecture;
- device, platform, or educational product branches.

### 4. Publication layer

Repositories or sublayers whose main role is publication packaging,
dissemination, release preparation, DOI generation, citation, and external
research visibility.

Typical contents:

- article packages;
- release bundles;
- DOI-facing metadata;
- Zenodo workflows;
- publication instructions;
- citation metadata.

This layer may overlap theory and practice, but its role is distinct and should
be named explicitly.

### 5. Governance and donor layer

The normative source of compact reusable rules.

This is where:

- contribution rules;
- code of conduct;
- security baseline;
- validation;
- audit;
- repository template logic;
- bibliography sync logic;
- publication boundary rules

should live in their strongest compact form.

This role belongs primarily to `terra-legal`.

### 6. Design and identity layer

The visual, rhetorical, and human-recognition surface.

Typical contents:

- brand book;
- design code;
- design system;
- public page identity;
- presentation identity;
- interaction language.

This layer should not be buried as random residue if it is still alive.

### 7. Philosophy and living knowledge layer

Large human-facing conceptual bridges that explain how the ecosystem thinks,
grows, remembers, and transforms.

Typical contents:

- living seed philosophy;
- Invisible Shadow ontology;
- philosophy pages;
- living DNA logic;
- high-level bridges between theory, practice, and civilization-scale meaning.

### 8. Archive and session layer

Dated sessions, snapshots, recovery artifacts, and evolution memory.

This layer is real and valuable, but it should not pretend to be the first
human entry surface.

### 9. Machine and workflow layer

Automation, build logic, release workflows, audit checks, machine maps, and
supporting operational files.

This layer should stay visible enough to audit, but not dominate human entry.

## Routing rules

When a new repository or document appears, classify it by:

1. primary role;
2. intended audience;
3. evidence/publication status;
4. whether it is living work or archive memory.

Then route it to the corresponding layer instead of dropping everything into one
root story.

## Public entry rule

The top GitHub surfaces should show the layers clearly.

At minimum, a public human-facing profile should route readers toward:

- theory;
- practice;
- publication;
- governance / donor;
- design / philosophy;
- branch projects.

## Anti-entropy rule

The layer model exists to reduce entropy.

It should prevent:

- archive dumps at the public root;
- machine files pretending to be welcome pages;
- duplicate rules across repositories;
- theory/practice collapse;
- design/philosophy invisibility;
- DOI and publication logic being hidden or faked.
