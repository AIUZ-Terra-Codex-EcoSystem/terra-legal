# Terra Name Card Template

Use one file per accepted, proposed, blocked, or deprecated public name.

```yaml
name: ""
name_class: ""
status: "proposed"
primary_role: ""

creator_signature:
  name: "Abdurashid Abdukarimov"
  orcid: "0009-0000-6394-4912"

source:
  source_language: ""
  literal_meaning: ""
  historical_or_cultural_context: ""
  first_known_terra_use: ""
  donor_files_consulted: []

forms:
  official_form: ""
  short_form: ""
  acronym: ""
  aliases: []
  deprecated_forms: []

language_review:
  en:
    pronunciation: ""
    meaning_risk: ""
    status: "not reviewed"
  ru:
    pronunciation: ""
    meaning_risk: ""
    status: "not reviewed"
  uz_latin:
    pronunciation: ""
    meaning_risk: ""
    status: "not reviewed"
  additional_languages: []

semantic_checks:
  nullo: ""
  plt: ""
  ucomm: ""
  euo: ""
  fmp: ""
  detox: ""

public_surface:
  intended_audience: ""
  repository_or_domain: ""
  search_ambiguity: ""
  visual_identity_relation: ""

legal_review:
  domain_status: "not checked"
  entity_name_status: "not checked"
  trademark_status: "not checked"
  jurisdiction: ""
  reviewer: ""
  note: "A naming review is not legal clearance."

decision:
  operator_decision: ""
  decision_date: ""
  trace_id: ""
  limitations: []

continuity:
  redirect_or_alias_plan: ""
  affected_files: []
  deprecation_note: ""
```

## Completion rule

A card is not complete until:

- the primary role is unambiguous;
- origin and donor sources are visible;
- English, Russian, and Uzbek Latin checks are recorded;
- NULLO, PLT, UCOMM, EUO, FMP, and Detox checks are complete;
- legal-review status is stated honestly;
- the operator decision and TraceLog record are linked.
