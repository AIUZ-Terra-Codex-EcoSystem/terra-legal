# Repository Protocol

Operational protocol for maintaining `terra-legal`.

## Before change

- confirm that the proposed change belongs to the legal donor layer;
- read the relevant donor and source files under Rule 0;
- classify the change as editorial, normative, protected legal, security, or emergency safety;
- identify the affected object class: documentation, software, data, media, brand, third-party material, or archived draft;
- check current license, ownership, contributors, provenance, and external obligations;
- identify the required TraceLog record;
- check child safety, dignity, privacy, security, and publication risk;
- apply Detox before implementation.

## During change

- work on a reviewable branch or pull request for material changes;
- keep edits minimal, attributable, and role-limited;
- preserve originals, historical grants, aliases, and provenance;
- do not silently relicense unclassified or third-party material;
- use canonical standard license texts without modification;
- separate copyright permissions, responsible-use rules, brand permissions, privacy duties, and commercial terms;
- keep design subordinate to documentary clarity;
- keep the public trace limited to necessary information;
- apply Detox continuously.

## After change

- verify internal and external links;
- verify license texts, SPDX identifiers, REUSE mappings, and file scope;
- verify copyright and author identity;
- verify `LICENSE`, `LEGAL.md`, README, `CITATION.cff`, release, DOI, and package metadata do not contradict each other;
- verify third-party exclusions and notices;
- verify naming, brand, accessibility, and continuity safeguards;
- run validation and audit;
- record the result in TraceLog;
- apply Detox after implementation.

## Licensing rule

`terra-legal` is a multi-license repository.

The controlling order is:

1. explicit file-level SPDX header or adjacent `.license` file;
2. applicable `REUSE.toml` annotation;
3. directory-specific or file-specific notice;
4. `LEGAL.md` scope statement;
5. historical release or version-specific notice.

The root `LICENSE` is a scope notice, not a claim that one license governs every file.

Unannotated historical files remain pending classification and are not silently relicensed.

## Protected decision boundary

The following require explicit operator approval and protected legal review:

- license selection or relicensing;
- copyright ownership or assignment;
- contributor terms;
- trademarks and certification marks;
- privacy and child-data obligations;
- commercial terms;
- governing law, dispute resolution, warranties, and liability;
- claims of official status, partnership, certification, or legal compliance.

Professional counsel is required where jurisdiction-specific enforceability or material legal risk is involved.

## Linking rule

A reference to `terra-legal` does not automatically:

- apply a license;
- transfer copyright;
- create official ecosystem status;
- create certification, partnership, or endorsement;
- bind a third party to the Universal Convention or Responsible Use Policy.

See `LINKING-INSTRUCTIONS.md`.

## Refusal rule

Do not merge changes that:

- weaken child or vulnerable-person protections;
- erase provenance, authorship, or historical grant information;
- expose confidential material, secrets, or unnecessary personal data;
- present unreviewed names, marks, licenses, or certifications as approved;
- use design or policy language to imply authority not established;
- convert TraceLog or Invisible Shadow into hidden monitoring;
- conceal unresolved legal or integrity conflicts;
- apply a repository-wide license to third-party material without authority;
- claim that earlier irrevocable grants have been withdrawn.
