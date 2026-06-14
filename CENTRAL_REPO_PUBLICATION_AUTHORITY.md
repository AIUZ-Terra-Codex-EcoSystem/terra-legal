# Central Repository Publication Authority

**Normative source:** `terra-legal`  
**Operational controller:** `Secret-Uzbek/FMP-CENTRAL-REPO`

## Authority split

`terra-legal` defines the mandatory legal, validation, audit, evidence, Detox, TraceLog, risk, and publication-gate rules.

`FMP-CENTRAL-REPO` remains the operational publication control plane for the FMP and Terra repository portfolio.

A managed repository must not publish independently when its publication workflow is governed by the Central Repository control plane.

## Required publication chain

1. the managed repository declares its role, release scope, license boundary, and required files;
2. the Central Repository applies the publication preflight;
3. the preflight verifies the pinned Terra Legal policy reference;
4. validation, audit, Detox, TraceLog, risk, and operator gate records are checked;
5. the Central Repository release workflow creates the GitHub release package;
6. external records are created or updated only through separately verified platform-specific steps;
7. DOI and external metadata are written back only after the external record exists and is verified;
8. the publication event is recorded in the managed repository and Central Repository trace surfaces.

## Prohibited shortcuts

- no release based only on a tag or button press;
- no DOI written before a verified external record exists;
- no independent Figshare or OSF creation outside the approved publication chain;
- no self-issued compliance or completion claim;
- no floating reusable-workflow reference;
- no hidden expansion of license scope;
- no silent publication of archive, donor, private, or excluded material.

## Current policy reference

The initial control-plane modernization is based on Terra Legal publication state represented by commit:

`4a2a95300e2eb752a72fc86fa9b37483aa7f819d`

Managed repositories must record a later policy commit explicitly when the controlling Terra Legal rules change.
