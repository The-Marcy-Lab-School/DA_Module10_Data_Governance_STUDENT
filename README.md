# Data Governance, Security & Public-Sector Compliance Project

Start with `PROJECT_OVERVIEW.md` for what you're building and why. This
file (`README.md`) is where the step-by-step setup lives.

**Due:** 7 days. See `CHECKLIST_TIMELINE.md` for the day-by-day pace
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
