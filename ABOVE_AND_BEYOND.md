# Above & Beyond

Optional. Do these **after** MVP is genuinely solid — a shaky MVP with
extra features isn't the goal. Pick 1-2, not all of them.

## A second dataset/domain's data contract

Pick a genuinely different domain than your main one (e.g. if you built
your MVP against healthcare_operations/HIPAA, try public_sector/FISMA)
and build a second, real, smaller data contract for it. Write up what
genuinely differed — which fields got a *different* real tier under the
different regulation, and why.

## A real, deeper geospatial redaction analysis

Your MVP's publication plan picks a real aggregation level
qualitatively. Go one step further: for your specific geospatial field,
work out a real, approximate k-anonymity estimate (how many real real-
world entities would plausibly share your chosen aggregation level —
e.g. how many households in a given census block) — a real, numeric
argument for why your chosen level is genuinely safe, not just
"probably fine."
