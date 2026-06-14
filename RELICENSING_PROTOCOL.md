# Terra Relicensing Protocol

**Repository:** `terra-legal`  
**Purpose:** safe, traceable, repository-by-repository license correction and migration  
**Operator:** Abdurashid Abdukarimov — ORCID 0009-0000-6394-4912

## Non-negotiable rule

No repository is relicensed merely to make the portfolio look uniform.

A license change is permitted only after the project proves that it has the rights, evidence, scope definition, and metadata needed to make the change accurately.

## Rule 0 sequence

## Stage 0 — Freeze

Before analysis:

- stop automatic license propagation;
- do not copy the Terra Public License into additional repositories;
- do not remove existing license files;
- do not rewrite Git history;
- do not claim that an earlier public license has been revoked;
- mark known conflicts as `review required`.

## Stage 1 — Repository identity

Record:

- repository full name;
- visibility;
- primary role;
- public or private status;
- active, archive, template, demonstrator, publication, or partner status;
- owner account;
- canonical project and repository links;
- operator decision source.

If the repository role is unclear, relicensing is blocked.

## Stage 2 — Object classification

Classify every major file group:

- software source;
- workflow and configuration;
- documentation;
- scholarly manuscript;
- diagram and media;
- dataset or database;
- corpus item;
- third-party work;
- logo or trademark;
- confidential or partner material;
- generated output;
- archive snapshot.

A single repository may require multiple licenses.

## Stage 3 — Rights and authorship audit

Check:

- commit history;
- contributors;
- co-authors;
- contractors and partner organizations;
- upstream projects;
- copied templates;
- publisher agreements;
- grant or employer obligations;
- existing assignments or contributor agreements;
- authorship and copyright-owner names.

Record one result for each relevant contributor or source:

- project owns rights;
- contributor consent required;
- third-party license controls;
- public domain;
- permission documented;
- rights unknown;
- excluded from relicensing.

If material rights are unknown, that material is excluded or the migration is blocked.

## Stage 4 — Existing grant audit

Identify every visible licensing statement in:

- `LICENSE`;
- `LICENSE.md`;
- `LICENSES/`;
- source headers;
- README badges;
- `CITATION.cff`;
- package manifests;
- `.zenodo.json`;
- release notes;
- DOI deposits;
- website footers;
- downloadable archives.

Earlier public grants remain relevant to copies and versions already distributed.

A new license may govern a future version only when the rights holder is authorized to offer that version under the new terms.

## Stage 5 — Dependency and third-party audit

For software:

- identify direct and transitive dependencies;
- record license identifiers;
- identify copyleft, notice, source-offer, patent, and attribution duties;
- verify copied code and GitHub Actions;
- preserve upstream notices.

For research and corpus repositories:

- identify articles, books, images, maps, scans, museum objects, archival materials, and datasets;
- record the original rights status;
- distinguish citation from redistribution permission;
- confirm whether public access means public domain or merely accessible.

## Stage 6 — Target license decision

Use `TERRA_LEGAL_FRAMEWORK_STRATEGY.md` and `REPOSITORY_LICENSE_MAP.md`.

The decision record must state:

- target object class;
- target license and exact SPDX identifier;
- reason for selection;
- compatibility findings;
- existing grants preserved;
- files excluded;
- contributor approvals;
- legal-review requirement;
- operator approval;
- TraceLog ID.

## Stage 7 — Migration package

Prepare a reviewable branch or pull request containing, as applicable:

- root legal notice;
- `LICENSES/` canonical license files;
- `REUSE.toml` or file headers;
- `LEGAL.md`;
- `THIRD_PARTY_NOTICES.md`;
- `DATA_RIGHTS.md`;
- `TRADEMARK_POLICY.md` link;
- `RESPONSIBLE_USE_POLICY.md` link;
- corrected README badge and wording;
- corrected `CITATION.cff`;
- corrected Zenodo and package metadata;
- migration note and effective version;
- no claim that earlier licenses disappeared.

## Stage 8 — Detox during migration

Reject:

- false claims of sole ownership;
- replacement of contributor names without evidence;
- silent relicensing of third-party material;
- using an open-source label for a field-of-use-restricted license;
- treating the Universal Convention as an invisible additional condition on a standard public license;
- presenting an informal project or handle as legal owner without basis;
- copying a license text while changing its terms but retaining the original license name;
- hiding material conflicts behind badges or metadata.

## Stage 9 — Validation

The migration passes only when:

- root and file-level licenses agree;
- copyright identity is verified;
- all license files use exact canonical text;
- SPDX expressions are valid;
- README, `CITATION.cff`, package, release, and DOI metadata agree;
- exclusions and third-party rights are visible;
- old releases retain their historical notices;
- the new license applies from a clear version, date, or commit;
- the migration is recorded in TraceLog.

## Stage 10 — Post-migration audit

After merge:

1. fetch the public repository again;
2. verify GitHub license detection;
3. verify release bundles;
4. verify Zenodo and DOI metadata;
5. verify Pages and documentation footers;
6. verify package registries if used;
7. search for contradictory license strings;
8. record remaining risks.

## Status values

- `unclassified`;
- `inventory complete`;
- `rights audit pending`;
- `third-party review pending`;
- `contributor consent pending`;
- `target selected`;
- `migration prepared`;
- `legal review required`;
- `approved for merge`;
- `migrated`;
- `validated`;
- `blocked`;
- `no change recommended`.

## Priority order

### Priority A — critical conflicts

- contradictory root license and metadata;
- incorrect copyright identity;
- CC0 on strategic mixed repositories;
- custom Terra Public License used as blanket software or publication license;
- partner or commercial ownership uncertainty;
- third-party corpus material under a blanket root license.

### Priority B — broken or incomplete notices

- obsolete `.terra-legal` pointers;
- placeholder license stubs;
- one-line license files;
- stale repository links;
- missing third-party notices.

### Priority C — normalization

- SPDX and REUSE adoption;
- README and citation alignment;
- multilingual legal explanations;
- consistent brand and policy links.

## Refusal conditions

A migration must not proceed when:

- ownership is disputed or unclear;
- contributor consent is necessary but absent;
- a publisher agreement has not been checked;
- third-party material cannot be separated;
- a private partner project has no written IP decision;
- the operator has not approved the target;
- legal counsel is required for a custom restriction and has not reviewed it.

## TraceLog rule

Each repository receives one TraceLog record containing:

- evidence read;
- Detox before, during, and after;
- rights findings;
- selected license;
- excluded material;
- approvals;
- commit and release references;
- validation result.

## Completion rule

A repository is not `license complete` merely because it contains a file named `LICENSE`.

Completion requires consistent scope, ownership, third-party treatment, metadata, public notices, and validated release behavior.
