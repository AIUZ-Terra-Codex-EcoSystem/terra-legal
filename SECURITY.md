# Security Policy

**Repository:** `terra-legal`  
**Maintainer contact:** `a.abdukarimov@fractal-metascience.org`  
**Status:** public reporting and documentary security policy

## Scope

This repository contains legal, governance, validation, audit, publication, identity, and workflow material. Security review therefore includes:

- accidental publication of credentials or private material;
- unsafe workflow permissions or dependencies;
- integrity of public documents and releases;
- misleading security or production-readiness claims;
- privacy and child-safety implications;
- local or network-accessible Terra services referenced by the repository.

This policy does not claim the existence of a staffed security, legal, or child-protection team.

## Reporting

Report a suspected security issue privately by email:

`a.abdukarimov@fractal-metascience.org`

Use subject prefix: `[SECURITY]`.

Include only the information needed to understand the issue:

- affected repository, file, workflow, release, or service;
- concise description;
- steps needed to confirm the problem where safe;
- likely impact;
- suggested correction where available.

Do not publish sensitive evidence in a public issue.

No fixed response time is promised. Reports are reviewed according to severity, available capacity, and the need to protect affected persons or systems.

## Severity

- `critical` — immediate serious safety, privacy, rights, or system-integrity risk;
- `high` — material risk requiring correction before public reliance or deployment;
- `medium` — limited risk affecting integrity, access, or maintainability;
- `low` — minor issue or hardening opportunity.

Child-safety and unnecessary personal-data exposure receive priority containment.

## Local Terra service boundary

A local Terra AI service is not production-ready merely because it starts successfully or returns successful responses.

Before use beyond the operator's own device, review:

- whether the service is limited to the local device or visible on a wider network;
- access control;
- data and log handling;
- input validation;
- dependency and update status;
- development-server warnings;
- shutdown and correction path;
- whether children, vulnerable persons, or personal data may be involved.

A development server must remain classified as development until a separate deployment and security review is completed.

## Workflow and dependency security

- use minimum required workflow permissions;
- record every external action or dependency;
- prefer reviewed immutable commit references for GitHub Actions;
- do not treat a successful workflow as proof of legal compliance, complete security, publication, or scientific validation;
- verify release and DOI status from actual external records;
- keep credentials outside committed files.

## Coordinated correction

When a material issue is confirmed:

1. contain the affected public or operational surface;
2. preserve only the evidence necessary for review;
3. apply the smallest safe correction;
4. repeat validation, audit, Detox, and the publication gate;
5. record a safe public summary in TraceLog;
6. avoid publishing details that would increase harm.

## Limitations

This policy is a repository reporting and review process. It is not a warranty, certification, promise of complete security, or substitute for qualified professional assessment.