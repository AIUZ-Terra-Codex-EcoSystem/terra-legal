# Evidence and Provenance Protocol

**Repository:** `terra-legal`  
**Role:** evidence, claims, provenance, and reproducibility control  
**Status:** interim publication-ready protocol

## Purpose

This protocol prevents a Terra document, audit, workflow, or public statement from treating repetition, simulation, formatting, or AI confidence as evidence.

It applies to legal, technical, scientific, security, publication, governance, and repository-readiness claims.

## Claim record

Each material claim should identify:

- the exact statement;
- its scope and boundary conditions;
- the evidence that supports it;
- the source location and date checked;
- the method used to verify it;
- uncertainty and known limitations;
- alternative explanations or contrary evidence;
- failure conditions;
- reviewer and review date where applicable.

## Evidence statuses

- `supported` — sufficient evidence supports the claim within its stated scope.
- `partially supported` — some elements are supported, but material limitations remain.
- `unsupported` — evidence is absent or inadequate.
- `contradicted` — credible evidence conflicts with the claim.
- `not applicable` — the claim type does not require evidence in this context.
- `not assessed` — no conclusion has been reached.

`Not assessed` must never be presented as `supported`.

## Evidence hierarchy

Use evidence appropriate to the claim. Examples include:

- primary legal texts and official records for legal status;
- repository history, signed records, and author confirmations for provenance and ownership;
- actual workflow runs and release records for automation and publication;
- test outputs, reproducible environments, and source code for technical behavior;
- peer-reviewed research, data, methods, and replication for scientific claims;
- direct inspection and documented tests for accessibility and usability;
- qualified professional review for jurisdiction-specific legal or specialist conclusions.

Secondary commentary may explain a primary source but does not replace it where the primary source is available.

## Prohibited evidence substitutes

The following are not sufficient evidence by themselves:

- a generated percentage or confidence score;
- a script searching for expected words in a sample string;
- simulated data described as a real test;
- code that has not been run;
- a badge, title, filename, or self-description;
- a planned workflow or placeholder DOI;
- an AI statement that a system is secure, compliant, final, certified, or production-ready;
- an internal policy cited as proof of external legal compliance;
- the number of files, commits, references, or lines of code without a relevant method.

## Reproducibility record

Where the claim concerns technical or research behavior, preserve as applicable:

- input or test fixture;
- code or procedure used;
- software and environment information;
- configuration and relevant dependency versions;
- expected and observed output;
- timestamp;
- checksum or commit identifier;
- limitations and conditions under which the result may differ.

Sensitive inputs must not be published. A safe description or restricted evidence reference should be used instead.

## Falsification and challenge

For important claims, record at least one of:

- a condition that would show the claim to be false;
- a simpler competing explanation;
- a known negative case;
- a test designed to find disconfirming evidence;
- a boundary beyond which the claim is not made.

A claim that cannot be challenged must not be presented as an empirically validated conclusion.

## Provenance chain

For copied, adapted, extracted, or migrated material, record:

- source repository and path;
- source commit or stable identifier where available;
- original author or publisher;
- original license or rights status;
- whether the new surface is literal, adapted, summarized, translated, or synthesized;
- meaning-preservation note;
- changes and exclusions;
- destination file and TraceLog ID.

## Confidential and restricted evidence

Public evidence records must exclude:

- credentials and tokens;
- private correspondence;
- unnecessary personal data;
- child data;
- health information unrelated to the public documentary role;
- exploitable vulnerability detail before coordinated disclosure;
- legally privileged or contractually restricted material.

The public record may state that restricted evidence was reviewed without publishing it.

## Relationship to validation and audit

Validation asks whether the declared requirements are met.

Audit asks whether the evidence, scope, rights, contradictions, risks, and wider system support the conclusion.

Neither may mark a material claim as passed while its evidence status is `unsupported`, `contradicted`, or `not assessed`, unless the claim is removed or explicitly excluded.

## Documentary provenance

This protocol extracts the evidence, reproducibility, provenance, falsifiability, triangulation, independent replication, and explicit-exclusion logic found across the earlier FMP research, completion, pipeline, TraceLog, and Terra validation corpus.