# Portfolio Licensing Audit — 2026-06-14

**Trace ID:** `TL-2026-06-14-002`  
**Scope:** 29 repositories under `Secret-Uzbek` and `AIUZ-Terra-Codex-EcoSystem`  
**Operator:** Abdurashid Abdukarimov  
**Audit level:** portfolio, documentary, licensing, metadata  
**Status:** inventory complete; rights audit pending

## Operator instruction

Prepare a complete repository licensing map and a Rule-0-based legal framework strategy before any portfolio-wide license migration.

## Rule 0 result

Passed.

The following were read before strategy drafting:

- the full connected repository inventory;
- root `LICENSE` or `LICENSE.md` surfaces for all repositories where present;
- representative README and `CITATION.cff` files;
- Terra legal, Rule 0, Detox, TraceLog, publication, validation, audit, naming, identity, and Invisible Shadow bridge files;
- official Creative Commons, Apache, GNU, OSI, SPDX, REUSE, and Open Data Commons materials.

## Inventory result

- 29 accessible repositories were mapped.
- One repository, `pixel-perfect-match`, is private.
- Root-license states include CC0, CC BY, CC BY-SA, CC BY-NC-SA, MIT, GPL, Terra Public License, missing licenses, damaged copies, obsolete pointers, and placeholder stubs.
- Several mixed repositories attempt to apply one license to software, documents, datasets, archives, and third-party materials.

## Critical findings

### License and metadata contradiction

`Secret-Uzbek/AIUZ` contains GPL v3 at root while README and `CITATION.cff` identify CC0-1.0.

### CC0 on strategic mixed repositories

`AIUZ-Terra-codex` and `FMP-CENTRAL-REPO` use CC0 root licenses even though they contain substantial authored documentation, implementation material, and workflows.

Earlier CC0 grants cannot be treated as if they never existed. A different license may govern future releases only where the rights holder is authorized to offer the new version under those terms.

### Terra Public License propagation

Multiple repositories use:

- full Terra Public License copies;
- damaged copies;
- one-line pointers;
- obsolete links to `.terra-legal`.

The custom license is not suitable as an automatic blanket license for the whole portfolio.

### Authorship and owner identity

Observed owner labels include:

- `Abdurashid Abdukarimov`;
- `Abdurashid Abdulkhamitovich Abdukarimov`;
- `Abdurashid Khamdamov`;
- `Secret Uzbek`;
- `Fractal Silk Route Hub`;
- foundation and project names.

These are not interchangeable legal rights holders. Documentary verification and assignment records are required.

### Corpus and third-party rights

Corpus repositories contain or may contain source texts, articles, images, scans, archival materials, and institutional documents. A root license may cover original project metadata and annotations but cannot automatically relicense third-party objects.

### Partner and commercial uncertainty

`cargotrack-bot` requires an ownership and partner-rights decision before relicensing.

### Template and upstream rights

`Secret-Uzbek/docs` contains an MIT notice naming Mintlify. Upstream template code and original Terra documentation require separate scope statements.

## Strategy result

The legally preferred portfolio architecture is layered:

1. CC BY 4.0 for original scholarly and documentary material;
2. Apache-2.0 as the default candidate for newly licensed project-owned software;
3. preservation of valid MIT, GPL, and CC BY-SA licenses unless a justified rights-cleared change is approved;
4. CC BY 4.0 and item-level rights for original corpus metadata and annotations;
5. optional ODbL only after a database-rights decision;
6. separate Universal Convention, Responsible Use Policy, Trademark and Brand Policy, contributor framework, privacy framework, and commercial agreements;
7. file-level SPDX and REUSE data for mixed repositories.

## Terra Public License result

Recommended status:

**Draft — not approved for automatic portfolio-wide application**

Its ethical principles should be preserved but separated into a Responsible Use Policy, contractual partner terms, privacy and child-safety rules, and the Universal Convention.

## Detox result

### Before

Passed. No portfolio-wide license was selected before current-license and repository-role inventory.

### During

Passed. The strategy does not:

- claim withdrawal of earlier public grants;
- treat accessible third-party material as project-owned;
- treat handles or brands as legal owners without evidence;
- call the custom Terra license open source;
- use the Universal Convention as an undisclosed additional restriction.

### After

Passed with mandatory next-stage conditions.

No repository license was changed during this audit.

## Files created

- `REPOSITORY_LICENSE_MAP.md`;
- `TERRA_LEGAL_FRAMEWORK_STRATEGY.md`;
- `RELICENSING_PROTOCOL.md`;
- this audit record.

## Blocking conditions before migration

- contributor and commit-history audit;
- ownership identity verification;
- third-party dependency and media review;
- co-author and publisher agreement review;
- per-repository operator decision;
- professional legal review where custom restrictions, privacy, child data, trademarks, or commercial terms are involved.

## Final status

`inventory complete — rights audit pending`

The portfolio now has a complete repository-level map and a coherent legal architecture. It does not yet have file-by-file copyright clearance, and no mass relicensing is authorized by this audit.
