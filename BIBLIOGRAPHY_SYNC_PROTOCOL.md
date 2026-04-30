# Bibliography Sync Protocol

This file defines how Terra and FMP repositories should consume a shared
bibliographic layer instead of carrying isolated citation debris.

## Purpose

The bibliography layer should function as a shared evidence donor for:

- articles;
- monographs;
- repository metadata;
- talks and presentations;
- website publication surfaces;
- DOI and release metadata repair.

## Shared donor rule

No repository should behave as if its local `.bib`, `.ris`, or source list is
the whole truth by itself.

Each repository should either:

- link to the current living bibliography donor;
- import a curated subset from it;
- or document why it temporarily diverges.

## Repository obligations

If a repository is publication-facing, it should expose:

- a readable `CITATION.cff`;
- a repository role note in `README.md`;
- a visible relation to the shared bibliography donor;
- a traceable record of which references belong to which publication layer.

## Evidence discipline

The bibliography layer is not decorative.

It exists to support:

- claims;
- quotations;
- conceptual framing;
- prior-art comparison;
- external validation.

Where a repository makes strong scholarly claims, its publication layer should
be repaired toward explicit evidence density rather than vague assertion.

## Sync sequence

1. Identify the current publication role of the repository.
2. Identify the living bibliography donor relevant to that role.
3. Repair or create `CITATION.cff`.
4. Repair article-local `.bib` or `.ris` files if they are broken or stale.
5. Record the sync in TraceLog.

## Boundary

The bibliography donor should not be blindly copied into every repository root.

Instead:

- keep the shared donor layer living and repairable;
- let repositories consume the needed subset;
- keep the relation explicit.
