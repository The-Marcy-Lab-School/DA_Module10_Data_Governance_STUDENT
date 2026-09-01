# Getting Started

## "Use this template" vs. Fork vs. Clone

Same rule as every project: **"Use this template"** on this repo's GitHub
page (not Fork) creates your own independent copy. Clone *that* copy, not
this template directly.

## Step 1: Install jsonschema (real, one command, no account needed)

This module needs no cloud signup, no Docker, no external account —
the lightest-weight setup so far. Just:

```bash
pip install jsonschema pyyaml
```

## Step 2: Validate your real data contract

Your data contract is written in YAML (comments are allowed there;
plain JSON doesn't support them) but validates as real JSON Schema.
Run this for real, not just once you think you're done — run it as you
build, so you catch a real syntax mistake early:

```python
import yaml
from jsonschema import Draft202012Validator

with open("starter/data_contract.schema.yaml") as f:
    schema = yaml.safe_load(f)

Draft202012Validator.check_schema(schema)
print("Schema is valid JSON Schema")
```

**Real gotcha, confirmed while building this template**: JSON Schema's
`type` field must be a real schema type (`string`, `integer`, `number`,
`boolean`, `array`, `object`) — a placeholder like `type: TODO` will
fail `check_schema` for real (that's the point — it's forcing you to
actually decide the real type, not skip it).

## Step 3: Build and check your real ERD

`starter/erd.mmd` is real Mermaid syntax (plain text — version-controls
cleanly, same reasoning as every given-template file this session).
Paste it into the free [Mermaid Live Editor](https://mermaid.live) as
you build it, not just at the end — you'll see a real syntax error
immediately if you make one. Prefer a visual drag-and-drop editor
instead? [draw.io / diagrams.net](https://app.diagrams.net) is a real,
free alternative — export as an image and reference it from your
contract if you go this route.

## Step 4: your real dataset and regulation

See `SCENARIOS.md` for how to pick your real dataset (likely your own
Module 3/8/9 domain) and its real, matching regulation.

## What's next

Once `jsonschema` is installed and you've confirmed the given templates
open cleanly in Mermaid Live Editor, go back to `README.md`'s "What to
do" section.
