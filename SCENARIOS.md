# Your Real Dataset and Regulation

Unlike Module 9, this project doesn't need a new external data pull —
the real point of this module is applying governance/classification
reasoning to a dataset you already know deeply. **Reuse your own
Module 3/7/8 domain dataset.**

## Match your real domain to its real, specific regulation

Pick the regulation that **actually, specifically** applies — not a
generic "data privacy" gesture (`common_project_mistakes`' own #3
trap):

- **healthcare_operations** → **HIPAA** — real, specific, and directly
  the framework this module's own guidance uses as its worked example
  (the Privacy Rule's "minimum necessary" standard; the Safe Harbor
  de-identification method's real 18-identifier list — birthdate,
  geographic subdivisions smaller than a state, and more, are real
  quasi-identifiers under this standard).
- **finance_insurance** → real state insurance-privacy statutes and
  **GLBA** (Gramm-Leach-Bliley Act) — real financial-privacy
  obligations around nonpublic personal information.
- **professional_services** → real client-confidentiality obligations
  and applicable state consumer-privacy law (e.g. CCPA-style
  frameworks) — the weakest single federal hook of the four, so be
  specific about which real state/contractual obligation you're
  actually naming.
- **public_sector** → **FISMA/NIST RMF**, and **CJIS** specifically if
  your data touches criminal-justice records — the real frameworks
  this module's own objective 4 names directly.

## If you want a genuinely public-sector-flavored dataset instead

Real, live, public-domain options (not required — only if you want a
different real dataset than your own domain):

- [data.cms.gov](https://data.cms.gov/) — browse for a current
  synthetic/de-identified claims-style dataset (the specific SynPUF
  link this curriculum once cited no longer resolves).
- [data.gov](https://www.data.gov/) — the U.S. government's general
  open-data catalog; check each specific dataset's own license badge.

## Either way

- Name the real, specific regulation **first**, then classify fields
  (`exemplar_guidance`'s own instruction — design the access-control
  section from the regulation backward, not the schema forward).
- Your contract and ERD must **agree with each other** on every
  field's real tier.
