# Terra Audit Regulation

This file defines audit requirements for documentary, repository, licensing, publication, naming, identity, TraceLog, responsible-use, and continuity surfaces within the Terra ecosystem.

## Purpose

Audit verifies that a public surface is:

- structurally coherent;
- rights-aware and licensing-consistent;
- documentary traceable;
- safe for publication;
- aligned with its declared role;
- free from hidden fragmentation, silent drift, false authority, or public-facing distortion.

## Audit scope

Use this regulation when reviewing:

- repository root and legal surfaces;
- license texts, SPDX records, `REUSE.toml`, and third-party notices;
- living indexes and reading paths;
- directives, policies, protocols, and governance files;
- contribution and responsible-use terms;
- publication-facing bridge documents;
- naming and trademark records;
- brand and visual-identity surfaces;
- TraceLog records;
- Invisible Shadow continuity bridges;
- release bundles, DOI deposits, and documentary packages;
- audit and validation files themselves.

## Non-negotiable audit rules

### 1. Source-first rule

No audit may certify a surface assembled without reading the relevant repository, donor, official license, rights, and metadata sources.

### 2. No implicit action rule

Audit may identify problems and prepare repair surfaces, but it must not silently convert analysis into an unannounced license change, ownership claim, or structural migration.

### 3. Human-readable rule

Audit outputs must remain reviewable by humans and must not collapse into opaque machine-only diagnostics.

### 4. Rights integrity rule

A licensing surface fails audit when it:

- applies one blanket license to materially different object classes without scope;
- changes a standard license text while retaining the standard name;
- contradicts README, citation, package, release, or DOI metadata;
- identifies an unverified person, handle, project, or entity as rights holder;
- silently relicenses historical or third-party material;
- hides earlier grants or version boundaries;
- omits required canonical license texts or notices;
- treats policy, ethics, trademark, privacy, or commercial terms as if they were automatically part of a standard copyright or software license.

### 5. Child-safety and dignity rule

Any surface that weakens child safety, dignity, privacy, human oversight, or anti-manipulation safeguards fails audit regardless of formatting quality.

### 6. Naming and trademark integrity rule

A public name or mark fails audit when its origin, role, language review, aliases, decision, limitations, registration status, or endorsement boundary is hidden or overstated.

### 7. Identity integrity rule

A visual surface fails audit when design obscures legal meaning, simulates unsupported authority, reduces accessibility, or imports unreviewed promotional claims.

### 8. Trace and anti-capture rule

A trace surface fails audit when it records secrets, unnecessary personal data, hidden behavioral inference, or monitoring beyond its declared documentary purpose.

## Audit levels

- `surface`
  - readability, links, entry path, role clarity, badges, naming, and visual consistency
- `rights`
  - ownership, contributors, object classification, license scope, SPDX, REUSE, exclusions, third-party notices, and historical grants
- `structural`
  - layer boundaries, donor relations, provenance, duplication, archive separation, and continuity
- `publication`
  - authorship, citation, publisher rights, release status, DOI evidence, packaging, public safety, and license metadata
- `protocol`
  - consistency with Rule 0, Detox, Governance, TraceLog, responsible use, naming, identity, and continuity rules
- `professional-review`
  - custom restrictions, privacy, child data, trademarks, commercial agreements, governing law, dispute resolution, warranties, liability, or other jurisdiction-specific legal questions

## Minimal audit sequence

1. Identify the target surface, object class, and declared role.
2. Read relevant donor and official sources.
3. Check current and historical license statements.
4. Check rights holder, contributors, co-authors, publishers, employers, partners, and upstream sources where applicable.
5. Check canonical license texts, SPDX identifiers, `REUSE.toml`, file-level notices, and exclusions.
6. Check README, `CITATION.cff`, package, release, DOI, and website metadata for contradiction.
7. Check third-party code, workflows, data, media, quotations, and standards.
8. Check for mojibake, dead links, false exhaustiveness, broken provenance, or archive leakage.
9. Check naming origin, aliases, trademark status, and endorsement boundaries.
10. Check accessibility and visual-identity compliance.
11. Check responsible-use, privacy, child-safety, and security safeguards.
12. Check whether continuity is preserved without excessive capture.
13. Check compatibility with Rule 0, Detox, operator control, TraceLog, Invisible Shadow, and living protocols.
14. State the audit result, exclusions, blocking conditions, and required repair path.

## Required audit output

An audit output identifies:

- target and repository role;
- branch, commit, release, or version;
- audit levels used;
- sources consulted;
- object and rights classification;
- detected contradictions or risks;
- files and materials excluded;
- TraceLog reference;
- status and required action:
  - `keep`;
  - `clarify`;
  - `classify rights`;
  - `detox`;
  - `extract`;
  - `re-layer`;
  - `relocate`;
  - `deprecate`;
  - `prepare for review`;
  - `block pending operator decision`;
  - `block pending rights clearance`;
  - `block pending professional legal review`.

## Immediate audit failure

- fabricated provenance, authorship, ownership, partnership, or certification;
- public secrets or unnecessary personal data;
- false claims that a partial surface is the whole system;
- broken donor or license references presented as valid;
- contradictory license and citation metadata;
- silent relicensing of third-party or historical material;
- modified standard license text presented under the original standard identifier;
- machine-generated noise presented as documentary or legal authority;
- assistant initiative replacing operator intent;
- unreviewed names or marks presented as approved or registered;
- identity elements presented as legal registration, scientific proof, or official certification;
- TraceLog used for hidden monitoring;
- unresolved legal conflict hidden behind a badge, release, DOI, or compliance claim.

## Documentary provenance

This regulation incorporates the stabilized file-scoped licensing and rights architecture prepared under TraceLog `TL-2026-06-14-004`.
