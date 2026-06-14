# Repository License Map

**Snapshot date:** 2026-06-14  
**Scope:** all 29 repositories accessible through the connected GitHub accounts `Secret-Uzbek` and `AIUZ-Terra-Codex-EcoSystem`  
**Operator:** Abdurashid Abdukarimov — ORCID 0009-0000-6394-4912  
**Status:** documentary inventory and migration recommendation; no mass relicensing performed

## Reading rule

This map distinguishes:

- the license text currently visible at repository root;
- conflicts in README, `CITATION.cff`, authorship, or donor links;
- the repository's primary role;
- the recommended legal action for future releases.

A recommendation is not permission to overwrite earlier grants. Existing public licenses may continue to govern copies already received. Relicensing also depends on copyright ownership, contributor consent, third-party material, dependencies, and publication agreements.

## License families used in this map

- **CC BY 4.0** — default for original scholarly, documentary, educational, and explanatory material.
- **CC BY-SA 4.0** — valid share-alike content license; retain when the reciprocal content commons is intentional.
- **Apache-2.0** — default candidate for newly licensed software where patent terms and broad adoption are desired.
- **MIT** — valid permissive software license; may remain where already correctly applied.
- **GPL-3.0** or **AGPL-3.0** — deliberate reciprocal software choices, not automatic defaults.
- **ODbL-1.0** — optional database share-alike license, only after database-rights and ownership review.
- **No public license** — private, unclassified, or rights-unresolved material.
- **Terra Public License** — frozen for review; not to be applied automatically to additional repositories.

## Complete map

| # | Repository | Primary role | Current root license surface | Main risk or conflict | Recommended action | Priority |
|---:|---|---|---|---|---|---|
| 1 | `Secret-Uzbek/AIUZ-Terra-codex` | Practice and implementation architecture | `LICENSE`: CC0-1.0; `CITATION.cff`: CC0-1.0 | CC0 is a public-domain dedication for a mixed implementation repository; code, documents, diagrams, and archives are not separated | Preserve prior CC0 grants; for future releases use Apache-2.0 for code and CC BY 4.0 for original documentation through `LICENSES/` and `REUSE.toml` | Critical |
| 2 | `Secret-Uzbek/FMP-monograph` | Monograph and publication layer | `LICENSE.md`: Terra Public License v1.0 with encoding damage | Custom license is mismatched to a scholarly monograph; damaged text weakens notice quality | Migrate future monograph releases to CC BY 4.0; exclude third-party figures and publisher-controlled versions explicitly | Critical |
| 3 | `Secret-Uzbek/AIUZ` | Public platform and software practice layer | `LICENSE`: GPL v3 text; README badge and `CITATION.cff`: CC0-1.0 | Direct contradiction between GPL and CC0 metadata | Do not relicense code yet; treat GPL-3.0 as provisional root license, remove CC0 metadata after contributor and source-header audit; license documentation separately under CC BY 4.0 | Critical |
| 4 | `Secret-Uzbek/AIUZ-terra-codex-FMP` | Mixed theory, publication, code, and archive repository | `LICENSE.md`: Terra Public License v1.1 Full | One custom license attempts to cover code, knowledge, protocols, archives, ethics, and brand | Convert to an explicit multi-license repository: CC BY 4.0 documents, Apache-2.0 software, item-level third-party rights, brand policy, and a non-license Responsible Use Policy | Critical |
| 5 | `Secret-Uzbek/Theory-of-fractal-metascience-paradigm` | Theory and scholarly publication | `LICENSE`: pointer to Terra Public License at obsolete `.terra-legal` path | Broken donor link and inappropriate blanket custom license | Use CC BY 4.0 for original theory and publication material; Apache-2.0 only for separable software tools | High |
| 6 | `Secret-Uzbek/Uzbek-mining` | Human-facing industrial research branch | `LICENSE`: obsolete Terra Public License pointer | Research reports, datasets, source documents, and third-party materials have different rights | CC BY 4.0 for original analysis and metadata; item-level rights registry for sources; consider ODbL only for an owned structured database | High |
| 7 | `Secret-Uzbek/Nullo-PLT-UCOMM-FMP-Academic-Research` | Academic research and article repository | `LICENSE`: CC BY 4.0 | Copyright line identifies `Abdurashid Khamdamov`, inconsistent with ORCID and repository authorship | Keep CC BY 4.0; correct copyright identity after documentary verification; align README, `CITATION.cff`, Zenodo, and release metadata | Critical |
| 8 | `Secret-Uzbek/FMP-CENTRAL-REPO` | Central public hub, publication and workflow spine | `LICENSE`: CC0-1.0 | CC0 removes attribution control from central authored material and does not distinguish code from documents | Preserve prior CC0 grants; apply CC BY 4.0 to new original documents and Apache-2.0 to new software/workflows using file-level SPDX data | Critical |
| 9 | `Secret-Uzbek/FMP-Full-Publication-Package` | Publication package and article distribution | `LICENSE`: obsolete Terra Public License pointer | Published manuscripts, accepted versions, figures, and third-party materials may have publisher-specific rights | CC BY 4.0 only for versions the author is entitled to license; add publication-agreement register and per-file rights notices | Critical |
| 10 | `Secret-Uzbek/terra-fmp-research-pipeline` | Research automation and publication tooling | `LICENSE`: obsolete Terra Public License pointer | Software is governed by a non-standard ethical license pointer; documentation and code are mixed | Apache-2.0 for code and workflows; CC BY 4.0 for documentation; preserve external action and dependency licenses | High |
| 11 | `Secret-Uzbek/terra-translation-api` | Translation API software | `LICENSE`: MIT; copyright `Secret Uzbek` | GitHub handle is used as copyright owner; ownership identity and contributor history need confirmation | Retain MIT for existing code; correct copyright notice after rights audit; Apache-2.0 may be used only for a future cleanly owned major branch | High |
| 12 | `Secret-Uzbek/ust-mvp` | UST demonstrator and interface implementation | `LICENSE`: obsolete Terra Public License pointer | Mixed software and documentation under a broken custom pointer | Apache-2.0 for code; CC BY 4.0 for original documentation and interface explanations; third-party UI assets separately recorded | High |
| 13 | `Secret-Uzbek/navoiy-terra-corpus` | Cultural and linguistic corpus | `LICENSE`: obsolete Terra Public License pointer | Corpus includes project-authored metadata and potentially third-party literary or scholarly materials | CC BY 4.0 for original metadata, annotations, and documentation; per-item rights fields; no blanket relicensing of source texts | Critical |
| 14 | `Secret-Uzbek/terra-ust-autobuild` | Build and deployment automation | `LICENSE`: obsolete Terra Public License pointer | Software automation under a non-standard custom pointer | Apache-2.0 for project-owned code; retain notices and licenses for third-party actions and dependencies | High |
| 15 | `Secret-Uzbek/babur-terra-codex` | Cultural knowledge and corpus branch | `LICENSE`: obsolete Terra Public License pointer | Historical texts, images, translations, annotations, and code cannot share one blanket license | CC BY 4.0 for original annotations and documentation; item-level rights for historical and third-party materials; Apache-2.0 for separable code | High |
| 16 | `Secret-Uzbek/terra-ust-core` | Core UST software and architecture | `LICENSE`: obsolete Terra Public License pointer | Core software lacks a standard software license and patent terms | Apache-2.0 candidate after ownership and dependency audit; CC BY 4.0 for documentation | Critical |
| 17 | `Secret-Uzbek/desktop-tutorial` | GitHub Desktop tutorial residue | No `LICENSE` or `LICENSE.md` | Not a Terra project; default tutorial content has unclear value and provenance | Archive or delete after confirmation; do not apply a Terra license merely to fill the gap | Low |
| 18 | `Secret-Uzbek/cargotrack-bot` | Cargo tracking implementation utility | `LICENSE.md`: Terra Public License v1.0 with encoding damage | Potential partner or company IP, unclear ownership, and a license designed for educational child-facing systems | Freeze relicensing; first document ownership, contributors, partner rights, data-processing role, and dependencies; then choose a standard software license or keep private/proprietary | Critical hold |
| 19 | `Secret-Uzbek/women-made-central-asia` | Research, public history, and publication project | `LICENSE`: CC BY 4.0 placeholder stub | Stub is not a complete legal notice; images and sourced materials require exclusions | Keep CC BY 4.0 for original text and metadata; replace stub with complete notice; add `THIRD_PARTY_NOTICES.md` and image-rights register | High |
| 20 | `Secret-Uzbek/women-made-central-asia-corpus` | Evidence and cultural-history corpus | `LICENSE`: CC BY 4.0 placeholder stub | Root notice may be read as relicensing all collected material | CC BY 4.0 for original metadata and annotations only; item-level rights and provenance required for every external object | Critical |
| 21 | `Secret-Uzbek/ziyarat-terra-corpus` | Ziyarat research corpus | `LICENSE.md`: CC BY-NC-SA 4.0 with third-party exclusions | The structure is stronger than most repositories, but NonCommercial is not an open-license default and may block legitimate research reuse | Keep temporarily; make a documented decision between CC BY 4.0 and CC BY-NC-SA 4.0; preserve third-party exclusions and item-level rights | Medium decision |
| 22 | `Secret-Uzbek/fractal-silk-route-hub-invisible-shadow` | Mixed philosophy, logistics analysis, and deployable artifact | `LICENSE`: MIT; copyright `Fractal Silk Route Hub` | Project name may not be the legal copyright owner; MIT blanket may cover documents and commercial strategy unintentionally | Retain MIT only for clearly identified software; CC BY 4.0 for research documents; reserve confidential, partner, and business materials; verify ownership identity | Critical |
| 23 | `Secret-Uzbek/Secret-Uzbek` | Personal GitHub profile repository | No root license | Public profile text has no explicit reuse terms, but a broad license is not operationally necessary | Optional CC BY 4.0 notice for original profile text; exclude personal data, logos, and third-party assets; no urgent relicensing | Low |
| 24 | `Secret-Uzbek/docs` | Documentation site based on Mintlify material | `LICENSE`: MIT, copyright Mintlify 2023 | Upstream template rights and user-authored documentation are conflated | Preserve Mintlify MIT notice for upstream template/code; license original Terra documentation under CC BY 4.0; add third-party notices and file-level scope | Critical |
| 25 | `AIUZ-Terra-Codex-EcoSystem/Nullo-PLT-FMP-Theory` | Organization theory repository | `LICENSE`: CC BY-SA 4.0 | Valid license, but repository URL and attribution metadata require review | Retain CC BY-SA 4.0 unless a deliberate interoperability decision favors CC BY 4.0; repair metadata and canonical links | Medium |
| 26 | `AIUZ-Terra-Codex-EcoSystem/AIUZ-Terra-Ecosystem` | Organization implementation repository | `LICENSE`: MIT for software; CC BY-SA 4.0 for documentation | Good dual-license structure, but repository and owner metadata contain stale references | Retain dual licensing; normalize copyright owner, repository URL, `CITATION.cff`, and SPDX scope | Medium |
| 27 | `AIUZ-Terra-Codex-EcoSystem/github` | Organization profile and community donor surface | `LICENSE.md`: one-line Terra Public License v1.0 | Incomplete custom-license notice and no scope definition | CC BY 4.0 for original organization profile and community documentation; link governance policies separately | High |
| 28 | `AIUZ-Terra-Codex-EcoSystem/terra-legal` | Legal, governance, identity, and protocol donor repository | `LICENSE`: CC BY 4.0 with inconsistent name; `LICENSE.md`: Terra Public License; `CITATION.cff`: CC0-1.0 | Three incompatible license positions in one repository | Use a scoped multi-license structure: CC BY 4.0 documentation/policies, Apache-2.0 code/styles/workflows, official licenses under their own terms, custom Terra legal drafts as `LicenseRef` documents, and trademarks reserved | Critical |
| 29 | `AIUZ-Terra-Codex-EcoSystem/pixel-perfect-match` | Private TypeScript implementation repository | No root license found | Private status gives no public grant, but contributors and third-party dependencies still matter | Keep private with no public license until ownership and release intent are decided; prepare an internal IP and dependency register | Hold |

## Portfolio findings

### Current visible root-license pattern

The portfolio currently contains:

- CC0 public-domain dedications on central or implementation repositories;
- Terra Public License copies and obsolete pointer files;
- valid MIT, GPL, CC BY, CC BY-SA, and CC BY-NC-SA licenses;
- missing licenses;
- incomplete license stubs;
- mixed repositories whose files require different licenses;
- inconsistent author and copyright-owner names;
- stale `.terra-legal` links;
- metadata that contradicts the root license.

### Immediate freeze rule

Until the ownership and contributor audit is completed:

- do not mass-replace all `LICENSE` files;
- do not rewrite repository history;
- do not claim that earlier CC0, CC, MIT, or GPL grants have been withdrawn;
- do not apply the Terra Public License to additional repositories;
- do not apply a license to third-party materials merely because they are stored in a Terra repository.

## Target portfolio architecture

| Repository class | Default future license structure |
|---|---|
| Scholarly theory, articles, monographs, original documentation | CC BY 4.0 |
| Existing deliberate share-alike knowledge repository | Retain CC BY-SA 4.0 unless changed after compatibility review |
| New project-owned software | Apache-2.0 |
| Existing valid MIT software | Retain MIT unless a future cleanly owned branch adopts Apache-2.0 |
| Existing GPL software | Retain GPL until contributor and compatibility review supports a change |
| Network service requiring reciprocal publication | AGPL-3.0 only after explicit product and business decision |
| Original corpus metadata and annotations | CC BY 4.0, with item-level rights registry |
| Structured database requiring database share-alike | ODbL-1.0 only after ownership and database-rights review |
| Third-party texts, images, scans, articles, archival objects | Original rights status; excluded from repository default license |
| Logos, names, certification marks, visual marks | Separate Trademark and Brand Policy; not CC-licensed by default |
| Universal Convention and ethical principles | Separate charter and Responsible Use Policy; not an added restriction on a standard open license |
| Private or ownership-unresolved code | No public license until rights and release intent are established |

## Required next evidence layer

Before any per-repository migration, create or verify:

1. contributor and commit-history report;
2. copyright-owner record;
3. dependency and third-party license inventory;
4. publisher and co-author agreement register;
5. media and dataset rights register;
6. current release and DOI license record;
7. target license decision signed in TraceLog;
8. migration PR with README, `CITATION.cff`, Zenodo, package metadata, and SPDX alignment.

## Status

This is a complete repository-level inventory of the connected 29-repository GitHub scope. It is not yet a file-by-file copyright clearance. File-level clearance is the mandatory second stage under the Relicensing Protocol.
