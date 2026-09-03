# Project Overview: Data Governance, Security & Public-Sector Compliance

## The objective

Produce a real **data contract** (JSON Schema, authored in YAML) and a
real, matching **ERD/Mermaid diagram** for your own dataset — real
field-level sensitivity classification, real ownership/stewardship
metadata, and real access-control requirements, all grounded in the
**specific, named regulation** that actually governs your chosen
domain. Plus two smaller real artifacts along the way: a regulation-
gap memo and an open-data publication plan (with a partner).

## Why it matters

Every project so far has treated data as something to model, pipe, or
analyze. This is the first time you're asked "who's *allowed* to see
this, and why" as the real, central question — the same question a
real data governance/compliance team answers every day, and the same
reasoning `pii-classification-ai-rag` requires **before** any dataset
gets handed to an AI/RAG pipeline, not after. `data-governance` is an
explicit prerequisite for both **Module 14** (Responsible AI
Governance) and **Module 13** (the final project).

## Deliverables at a glance

- A real data contract (`data_contract.schema.yaml`) that **actually
  validates** as JSON Schema — every field classified by sensitivity
  tier, each with a real, named regulatory justification.
- A real ERD (`erd.mmd`, Mermaid) that shows sensitivity tiers at a
  glance and **agrees with the contract** — no contradictions.
- A real regulation-gap memo — a given compliance scenario, evaluated
  against the real, specific framework that applies.
- A real open-data publication plan — **with a partner** — for a given
  geospatial public dataset: what needs redaction, what metadata must
  accompany release.

## Skills you'll practice

- **Data Governance / Master Data Management** — resolving a real
  golden-record conflict, naming a real data owner.
- **Data Security Compliance / Federal Security Compliance / CJIS
  Records Compliance** — real regulatory gap analysis (FISMA/NIST RMF,
  CJIS), not generic "be compliant" language.
- **Metadata Management / Data Cataloging** — a real catalog entry a
  new team member could actually use.
- **PII Classification (AI/RAG)** — real, justified field-level
  sensitivity tiers, the real pre-ingestion step before any AI/RAG use.
- **Open Data Management / GIS Geospatial Analysis** — a real public-
  release redaction/aggregation plan.
- **Documentation** — real, specific metadata an outside reader could
  actually use.

## Timeline

7 days for your own submission, plus a required share-out session
scheduled after. See `CHECKLIST_TIMELINE.md` for the day-by-day pace and
the full submission checklist.

## Where to start

Go to `README.md`, then `GETTING_STARTED.md` — real `jsonschema`
validation setup, and `SCENARIOS.md` for picking your real dataset and
its real, matching regulation.
