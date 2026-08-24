# MVP — the real bar for "done"

This is what actually gets graded as Meets/Approaching/Below per skill.
See instructor `rubric.md` for the full rubric if your instructor has
shared it — this is the same bar in checklist form.

## Field classification

- [ ] Every field in your dataset classified by sensitivity tier
      (public/internal/confidential/restricted), each with a real,
      specific, **named** regulatory or business justification — not a
      uniform tier applied to everything (`common_project_mistakes` #1:
      the most common way to fail this module).

## The real data contract

- [ ] `data_contract.schema.yaml` **actually validates** as JSON
      Schema — real `jsonschema` output pasted as evidence, not just
      "it looks right" (`common_project_mistakes` #2).
- [ ] Real ownership/stewardship metadata (owner, refresh cadence,
      business glossary term) for ≥3 real fields.
- [ ] Real access-control requirements, derived from the real,
      specific regulation named — "we should follow HIPAA" alone is
      not sufficient (`common_project_mistakes` #3).

## The real ERD

- [ ] Makes sensitivity tiering visible at a glance (labeled/color-
      coded), not buried in a separate document nobody cross-references.
- [ ] **Agrees with the data contract on every field** — a
      contradiction between the two is `common_project_mistakes` #4.

## The regulation gap memo

- [ ] The real, specific applicable framework named (FISMA/NIST RMF or
      CJIS, correctly distinguished).
- [ ] The real, specific compliance gap identified — not a vague "this
      isn't secure enough."
- [ ] A real, concrete fix proposed.

## The open-data publication plan

- [ ] Done with a real partner, both named.
- [ ] A real, specific redaction/aggregation level chosen for the
      geospatial risk, with real reasoning for why it's the right
      tradeoff.
- [ ] Real metadata that would let an outside reader understand the
      dataset's scope/limitations without contacting your team.

## What "Below" looks like, concretely

- Sensitivity tiers assigned by gut feeling with no stated rationale.
- The schema is invalid JSON/YAML, or doesn't actually validate.
- A governance memo that says "we should follow HIPAA" without naming
  what specifically doesn't comply.
- The ERD and the written contract contradicting each other about
  which fields are restricted.
