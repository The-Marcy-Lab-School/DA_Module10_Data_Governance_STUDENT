# Data Governance, Security & Public-Sector Compliance Project

Start with `PROJECT_OVERVIEW.md` for what you're building and why. This
file (`README.md`) is where the step-by-step setup lives.

**Due:** 7 days for your own submission, plus a required share-out
session scheduled after. See `CHECKLIST_TIMELINE.md` for the day-by-day pace
and the full submission checklist.

This repo is a **GitHub template** — a starting point, not something you
edit directly on Marcy's copy of it.

## Getting started

### Step 1: Get your own copy

On this repo's GitHub page, click **"Use this template" → "Create a new
repository"** (not Fork). Name it something like
`data-governance-security-compliance`, keep it **public**, and create
it.

### Step 2: Clone your new repo locally

```bash
git clone <the URL of your own new repo>
cd <your-repo-name>
```

### Step 3: git setup — already done for you this time

`.gitignore` and `LICENSE` are already here — `git-version-control`
isn't newly tested this module. Commit as you go, same discipline as
every prior module.

### Step 4: real jsonschema validation setup

See `GETTING_STARTED.md` — a one-line `pip install`, no accounts, no
cloud signup needed this module (the lightest-weight setup so far).

## Find a real partner — for the open-data publication plan only

Everything else in this project is solo — this one deliverable
(`starter/open_data_publication_plan.md`) needs a real second person, a
real redaction/metadata decision made together, not solo with a
partner's name added after.

**How partners are formed**: self-organize first — post in your
cohort's channel, or just ask around; most students pair up this way
within a day. **If you don't have a partner by Day 3** (see
`CHECKLIST_TIMELINE.md`), message your instructor directly — they'll
either pair you with someone else who's still looking, or, if the
cohort has an odd number, set up one real group of 3 for this one
deliverable. Asking for this is normal, not a sign you're behind —
don't wait until the deadline to raise it for the first time.

## What to do

- `starter/data_contract.schema.yaml` and `starter/erd.mmd` are
  **given, real templates** — real structure, the actual field-by-
  field classification/access-control content left as `TODO`. Following
  them is the guided rep; your real, independent project needs more
  than filling in these TODOs — your instructor's shared checklist has
  the full required scope.
- Pick your real dataset and its real, matching regulation (see
  `SCENARIOS.md`).
- Classify every field for real, using `starter/classification_rubric.md`
  — a real, specific, named regulatory basis per field, not a uniform
  tier.
- Fill in `starter/regulation_gap_memo.md` for real (a given compliance
  scenario).
- Fill in `starter/open_data_publication_plan.md` for real — **with a
  real partner** — a given geospatial public-data scenario.
- Build your real data contract and ERD, making sure they **agree with
  each other**.
- Validate your real data contract with `jsonschema` (see
  `GETTING_STARTED.md`) — it needs to actually validate, not just look
  plausible.
- Fill in `starter/required_components.md` as you go.

`CHECKLIST_TIMELINE.md` has the suggested day-by-day pace and the full
sequenced checklist.

**Where's the exact bar for "done," and what are the optional stretch
goals?** This repo (your own copy) doesn't include `MVP.md` (your **M**inimum **V**iable **P**roduct —
the required baseline) or `ABOVE_AND_BEYOND.md` on purpose — they're not something to keep sitting
in your portfolio repo. Ask your instructor for the link to this
template's `project-scope` branch to read them, or check the checklist
your instructor shares through the classroom, which covers the same
ground.
