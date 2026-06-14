# Independent Review Protocol

**Repository:** `terra-legal`  
**Role:** separation of producing, reviewing, and approving functions  
**Status:** interim publication-ready protocol

## Purpose

This protocol prevents self-review, AI confidence, or an internal checklist from being misrepresented as independent validation.

Independent review is required when a change may materially affect rights, safety, security, privacy, public claims, scientific conclusions, releases, or external reliance.

## Review levels

### Level 1 — separate verification pass

A second pass re-reads the changed surface against the controlling sources and evidence. It may be performed by the same human or technical agent only when the limited independence is disclosed.

### Level 2 — operator review

The operator reviews scope, meaning, exclusions, and protected decisions. Operator approval is required for strategy, publication, license selection, contributor terms, ownership claims, trademarks, and other protected decisions.

### Level 3 — domain review

A suitably qualified reviewer examines specialist claims such as software security, accessibility, research methods, child safety, data protection, or archival integrity.

### Level 4 — professional review

A qualified professional reviews jurisdiction-specific legal obligations, enforceability, contracts, privacy duties, child-data rules, trademarks, warranties, liability, or dispute resolution.

## Independence disclosure

Each review record states:

- reviewer identity or role;
- relation to the producing work;
- sources and evidence examined;
- conflicts of interest or limitations;
- questions raised;
- findings accepted, rejected, or unresolved;
- review date and target commit or version.

A review performed by the producing AI or the sole maintainer may still be useful, but it must be described as internal review, not independent external review.

## Required challenge questions

The reviewer should ask:

- What evidence would disconfirm the conclusion?
- Is a simpler explanation available?
- Does the document claim more than the evidence shows?
- Are rights, contributors, and third-party materials fully identified?
- Could a badge, design, score, or workflow imply unsupported authority?
- Are safety, privacy, security, and vulnerable-person impacts visible?
- Are exclusions and unresolved risks prominent enough?
- Can the change be reversed safely?

## Conflict handling

When reviewers disagree:

1. record each position and its evidence;
2. identify the controlling source or protected decision;
3. do not average incompatible legal, safety, or factual conclusions;
4. classify the conflict as resolved, accepted limitation, operator decision, professional-review requirement, or blocker;
5. link the resolution to TraceLog.

## Approval boundaries

Internal review may approve editorial and clearly safe technical corrections.

The operator approves normative and strategic publication decisions.

Neither an AI system nor a repository workflow may independently approve:

- legal compliance or enforceability;
- copyright assignment;
- trademark registration;
- child-data processing;
- professional certification;
- production security;
- scientific validation;
- external partnership or institutional status.

## Emergency exception

An immediate containment change may be applied to prevent active exposure of secrets, personal data, child-safety risk, or exploitable security harm. The change must then receive retrospective review, audit, and TraceLog as soon as safely possible.

## Documentary provenance

This protocol extracts the earlier Terra requirements for an independent observer, human oversight, peer review, expert review, operator confirmation, and explicit handling of audit conflicts, while removing unsupported claims that an internal automated pass is independent certification.