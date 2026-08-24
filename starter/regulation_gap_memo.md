# Regulation Gap Memo (objective 4 — fill in for real)

**The real given scenario**: a team stores criminal-history background-
check results in a shared spreadsheet that any employee with a company
login can open — no access logging, no recertification process, no
role restriction. The team believes this is fine because "the
spreadsheet itself is on a private company drive, not the public
internet."

## 1. The real, specific applicable framework

TODO: is this scenario governed by **FISMA/NIST RMF**, or by **CJIS**
records-handling rules specifically (criminal-history data is a real
CJIS trigger — CJIS requirements are more specific than general FISMA
controls, not a subset of them)? Name the real, specific framework —
not both vaguely.

## 2. The real, specific gap

TODO: what specifically about this scenario would fail a real audit?
Name the real, specific control that's missing (e.g. a real CJIS
access-recertification requirement, or a real FISMA/NIST RMF access-
control family control) — "this isn't secure enough" is not a real
finding (`common_project_mistakes`' own #3: a memo that says "we should
follow [X]" without naming what specifically doesn't comply).

## 3. The real fix

TODO: what would you actually change? Be specific — a real role
restriction, a real access log, a real recertification cadence — not
"add more security."

## Why this matters for your final data contract

Your real `data_contract.schema.yaml`'s `x-access-control` section
should reflect the same real reasoning discipline you used here —
this memo is real practice for that.
