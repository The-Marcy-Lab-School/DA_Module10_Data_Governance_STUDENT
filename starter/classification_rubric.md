# Field Sensitivity Classification Rubric (given)

Use this real rubric to classify every field in your dataset — in
`data_contract.schema.yaml`'s `x-sensitivity-tier` for each field. Every
tier assignment needs a real, specific, named regulatory or business
justification (`x-regulatory-basis`) — **not gut feeling**
(`common_project_mistakes`' own #1 real trap).

## Public

No real harm if disclosed to anyone, including outside your
organization. Already publicly available, or intentionally published
(e.g. a facility's public name/city, once you've confirmed it's not
itself sensitive in your specific domain).

## Internal

No real regulatory sensitivity, but not meant for public release —
disclosure would be a real business-judgment problem, not a legal one
(e.g. an internal surrogate key, a refresh timestamp).

## Confidential

Real, specific sensitivity exists — disclosure could cause real harm to
an individual or the organization, and a **named** regulation or
contractual obligation applies, even if the field alone isn't a full
legal identifier. Demographic fields, financial amounts tied to an
individual, and diagnosis-adjacent free text are common real examples.

## Restricted

The highest real tier — a direct identifier, or a field whose exposure
alone creates real, serious legal/compliance risk (e.g. a real HIPAA
direct identifier, a SSN, a CJIS-protected record). Access should be
real, narrowly scoped, and logged.

## How to actually use this

For **every** field: name the real, specific regulation or business
reason first (per `exemplar_guidance`'s own instruction — design the
access-control section from the regulation backward, not the schema
forward), *then* pick the tier that reason implies. "We should follow
HIPAA" is not a real basis (`common_project_mistakes`' own #3) — name
the actual rule (e.g. "HIPAA Safe Harbor's 18-identifier list treats
any geographic subdivision smaller than a state as a real
quasi-identifier").
