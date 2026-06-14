# Pull Request Rationale — Terra Legal Stabilization v2

This file preserves the review rationale for the reconciled stabilization branch.

## Purpose

Stabilize `terra-legal` through a file-scoped, reviewable rights architecture without silently relicensing historical or third-party material.

## Core decisions

- no single blanket repository license;
- CC BY 4.0 only for explicitly classified original documentary files;
- Apache-2.0 only for explicitly classified original implementation files;
- historical grants preserved;
- unclassified historical files remain pending review;
- Terra Public License remains a draft;
- Universal Convention, Responsible Use, trademark, contributor, privacy, and commercial layers remain separate from standard public-license permissions.

## Reconciliation

The first branch was superseded because `main` changed concurrently. Pull request #1 was closed without merge. This branch starts from updated `main` commit `3fc3422b1209f7650c714ef3310d1c227fed27af` and is currently ahead of `main` without being behind.

## Controlling records

- Trace: `traces/TL-2026-06-14-004.md`
- Audit: `audits/2026-06-14-terra-legal-stabilization-v2.md`
- Review checklist: `PULL_REQUEST_REVIEW_CHECKLIST.md`

## Merge boundary

The branch is prepared for human review. It does not claim full historical rights clearance and must not be merged automatically.
