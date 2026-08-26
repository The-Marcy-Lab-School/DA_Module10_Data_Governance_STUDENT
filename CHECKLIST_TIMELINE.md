# Checklist & Timeline

**7 days.** The lightest-infrastructure project so far (no cloud
signup, no Docker) — but 4 real distinct artifacts, each needing real
regulatory research. Don't mistake "no setup" for "less work."

## Day 1 — Setup, dataset, regulation

- [ ] `jsonschema`/`pyyaml` installed, confirmed with `check_schema`.
- [ ] Real dataset picked (your own Module 3/7/8 domain, or a real
      CMS/data.gov alternative).
- [ ] The real, specific regulation that applies to your domain named
      (`SCENARIOS.md`).

## Day 2 — Field classification

- [ ] Every real field classified by sensitivity tier
      (`classification_rubric.md`), each with a real, specific,
      **named** regulatory basis — not a uniform tier.

## Day 3 — Regulation gap memo

- [ ] `regulation_gap_memo.md` filled in for real: the real specific
      framework (FISMA/NIST RMF or CJIS), the real specific gap, the
      real fix.

## Day 4 — Open-data publication plan (with a partner)

- [ ] Real partner found.
- [ ] `open_data_publication_plan.md` filled in for real: real
      redaction/aggregation level, real reasoning, real metadata.

## Day 5-6 — The real data contract and ERD

- [ ] `data_contract.schema.yaml` completed for real — ownership/
      stewardship metadata for ≥3 fields, real access-control section.
- [ ] Schema **actually validates** — real `check_schema` output
      pasted into `required_components.md`.
- [ ] `erd.mmd` completed for real — sensitivity tiers visible at a
      glance, confirmed rendering cleanly in Mermaid Live Editor.
- [ ] Contract and ERD cross-checked — they **agree** on every field.

## Day 7 — Finish, submit

- [ ] `required_components.md` fully filled in with real evidence.
- [ ] Commit and push.

## Submission checklist

- [ ] Every field classified with a real, specific, named regulatory
      basis.
- [ ] A real data contract that actually validates as JSON Schema.
- [ ] A real ERD that agrees with the contract, sensitivity visible at
      a glance.
- [ ] A real regulation-gap memo, naming the real specific framework
      and gap.
- [ ] A real open-data publication plan, with a real partner.
- [ ] **Delete `PROJECT_OVERVIEW.md` and `SCENARIOS.md`** — they explain
      the assignment, not your project; a real portfolio repo shouldn't
      have "here's what you were asked to build" sitting in it.
- [ ] **Replace `README.md`'s content with your own real project README**
      — write it for someone who's never seen this assignment:
  - **Business Problem** — your dataset and its real, matching
    regulation.
  - **Regulatory Framework** — the specific framework you applied and
    why.
  - **Data Contract & ERD Overview** — your real classification/access-
    control design.
  - **Governance Recommendations** — your real gap-memo and publication-
    plan findings.
- [ ] Ownership/stewardship metadata for ≥3 real fields.
