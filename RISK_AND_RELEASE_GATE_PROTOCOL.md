# Risk and Release Gate Protocol

**Repository:** `terra-legal`  
**Role:** risk classification and publication authorization  
**Status:** interim publication-ready protocol

## Purpose

This protocol converts validation and audit findings into a clear publication decision. A passing technical workflow alone does not authorize release.

## Risk categories

- child and vulnerable-person safety;
- security and access control;
- privacy and personal data;
- ownership, licensing, and contributor rights;
- third-party material and supply chain;
- provenance and source integrity;
- scientific and technical claims;
- citation, DOI, release, and metadata integrity;
- accessibility and usability;
- continuity, archive, and recovery;
- governance, naming, trademark, endorsement, and certification;
- deployment and infrastructure exposure.

## Severity levels

### Critical

An immediate or serious risk affects safety, protected data, rights, security, provenance, or public reliance.

**Gate:** `BLOCK` until contained and reviewed.

### High

A material unresolved issue could invalidate the declared publication scope or create substantial harm.

**Gate:** normally `HOLD`. `GO WITH EXCLUSIONS` is permitted only when the affected surface is fully excluded and the exclusion is visible.

### Medium

A limited issue affects quality, traceability, accessibility, clarity, or maintainability without invalidating the declared scope.

**Gate:** repair or publish with a recorded limitation.

### Low

An editorial or minor maintenance issue has no material safety, rights, integrity, or reliance impact.

**Gate:** publication may proceed with a follow-up record.

## Risk record

Each material finding states:

- risk ID;
- category and severity;
- affected surface;
- evidence;
- likely impact;
- current containment;
- responsible decision role;
- repair or acceptance action;
- status: `open`, `contained`, `accepted`, `resolved`, or `superseded`;
- TraceLog reference.

## Release gate decisions

### GO

All required controls pass for the declared scope.

### GO WITH EXCLUSIONS

The publishable scope is coherent, but named files, claims, or functions remain excluded. Exclusions must appear in the release note, package manifest, and TraceLog.

### HOLD

A material repair, evidence item, operator decision, or professional review remains required.

### BLOCK

A critical safety, security, rights, provenance, evidence, or integrity failure prevents publication.

## Protected decisions

The operator explicitly approves:

- publication of a normative legal or governance surface;
- interim use of contributor terms pending professional review;
- acceptance of material exclusions;
- release classification;
- public deployment boundaries;
- acceptance of a known high risk.

An AI system or CI workflow may report a gate state but may not silently make a protected decision.

## Service exposure rule

A local service is not production-ready merely because it returns successful responses. Network exposure, access control, data handling, logging, development-server status, incident shutdown, and recovery must be reviewed before public or child-facing use.

## Final gate record

The final record identifies:

- commit or release;
- publication scope;
- validation and audit results;
- evidence and review status;
- open risks and exclusions;
- operator decision;
- gate state;
- recovery reference;
- TraceLog ID.

## Documentary provenance

This protocol extracts the useful severity, blocker, acceptance-criteria, safety, security, publication, and phased-readiness logic from earlier Terra and AIUZ materials while rejecting arbitrary compliance percentages and self-issued certification levels.