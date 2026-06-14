# Linking a Repository to terra-legal

## Purpose

This guide explains how another repository may reference `terra-legal` as a governance and documentary donor layer.

**A link does not automatically change the other repository's license, ownership, official status, or legal obligations.**

Each repository must select and document its own licensing structure under the [Relicensing Protocol](./RELICENSING_PROTOCOL.md).

## Correct repository address

Use:

`https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal`

Do not use the deprecated name `.terra-legal` in new links, submodules, badges, or documentation.

## What linking may mean

A repository may link to `terra-legal` to indicate that it consults or adopts specified donor documents, such as:

- Code of Conduct;
- Security Policy;
- contribution rules;
- validation and audit protocols;
- naming and visual-identity standards;
- TraceLog and continuity rules;
- portfolio licensing strategy.

The adopting repository must state exactly which documents it adopts and whether they are copied, adapted, or referenced.

## What linking does not mean

Linking does not by itself:

- apply Terra Public License v1.0;
- apply CC BY 4.0 or Apache-2.0;
- relicense existing files;
- transfer copyright;
- create a partnership, agency, certification, or endorsement;
- add a repository to an official registry;
- make the Universal Convention a hidden additional license condition;
- authorize use of logos, certification badges, or official status language.

## Minimal README reference

```markdown
## Governance and legal references

This repository consults selected donor documents from
[terra-legal](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal).

Adopted documents:
- [Code of Conduct](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/blob/main/CODE_OF_CONDUCT.md)
- [Security Policy](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/blob/main/SECURITY.md)
- [Relicensing Protocol](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal/blob/main/RELICENSING_PROTOCOL.md)

Repository-specific licensing is defined locally in `LICENSE`, `LEGAL.md`,
`LICENSES/`, and file-level SPDX or REUSE records.
```

## Badge example

```markdown
[![Governance donor: terra-legal](https://img.shields.io/badge/governance-terra--legal-2E8B57)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)
```

Do not label this badge `license` unless the local repository actually uses a verified license identified in its own files.

## Repository-specific legal package

A repository adopting the donor layer should prepare, as applicable:

- `LICENSE` — short scope notice;
- `LEGAL.md` — repository-specific rights and exclusions;
- `LICENSES/` — canonical license texts;
- `REUSE.toml` or SPDX headers;
- `THIRD_PARTY_NOTICES.md`;
- `CONTRIBUTING.md`;
- `CODE_OF_CONDUCT.md`;
- `SECURITY.md`;
- `CITATION.cff`;
- data, corpus, media, privacy, trademark, or commercial policies required by the repository role.

## License selection by object class

Typical target structure:

| Object | Typical target |
|---|---|
| Original articles, monographs, documentation, and diagrams | CC BY 4.0 |
| New project-owned software and workflows | Apache-2.0 |
| Existing correctly licensed MIT or GPL code | Preserve pending compatibility and ownership review |
| Original corpus metadata and annotations | CC BY 4.0 with item-level rights |
| Third-party texts, images, datasets, scans, or archival objects | Original rights status |
| Logos, names, and certification marks | Separate Trademark and Brand Policy |
| Ethical and safety principles | Responsible Use Policy and contractual instruments |

This is a starting matrix, not an automatic decision.

## Adoption record

The adopting repository should record:

- donor documents read;
- exact versions or commit references;
- local adaptations;
- repository-specific license decision;
- files excluded from the default license;
- third-party rights;
- operator approval;
- TraceLog ID.

## Submodules and copied files

A submodule preserves the donor repository as a separate project. It does not merge licensing scopes.

When copying a donor file:

1. preserve source and attribution;
2. preserve the applicable license;
3. identify local changes;
4. update internal links;
5. do not imply that the copied file makes the whole repository officially certified or licensed.

## Verification checklist

- [ ] Correct `terra-legal` URL used
- [ ] Local repository role declared
- [ ] Local `LICENSE` and `LEGAL.md` present
- [ ] License texts and SPDX identifiers match
- [ ] `CITATION.cff` does not contradict the license files
- [ ] Third-party rights and exclusions visible
- [ ] Donor documents and adaptations identified
- [ ] No false certification, partnership, or endorsement claim
- [ ] TraceLog record created
- [ ] Detox completed before, during, and after integration

## Contact

Questions about donor-layer adoption:

`a.abdukarimov@fractal-metascience.org`

Suggested subject:

`[TERRA LEGAL ADOPTION] repository-name`
