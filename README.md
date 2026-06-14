# BioScout

BioScout is a source-grounded biotech intelligence workspace. This public repository is a
minimal example dataset, not the full private development workspace.

The public example company is Revolution Medicines. The records are structured so that report
prose can trace back to source IDs, evidence quotes, confidence levels, review status, and
open questions.

## Contents

- `companies/revolution_medicines/profile.yaml`: company profile and summary claim IDs
- `companies/revolution_medicines/seed_sources.yaml`: public source metadata
- `companies/revolution_medicines/claims.yaml`: source-linked claim ledger
- `companies/revolution_medicines/open_questions.yaml`: unresolved diligence questions
- `companies/revolution_medicines/report_config.yaml`: report page configuration
- `config/companies/revolution_medicines.yaml`: company config entry

Generated docs, source code, local data ledgers, and private company examples are intentionally
not included in this public repository.

## Source Discipline

BioScout treats biomedical, clinical, funding, patent, and investment-adjacent claims as
uncertain unless they are directly sourced. Company disclosures are preserved as company
disclosures, not independent validation.

High-risk facts such as clinical status, regulatory designations, patent ownership, license
status, funding terms, efficacy, and safety should remain caveated unless direct source support
is available.

## Public Example

The Revolution Medicines seed data uses public source metadata and compact evidence excerpts to
demonstrate the data shape:

- source records have stable `source_id` values
- claims reference one or more source IDs
- claims include evidence text snippets for traceability
- high-risk claims carry higher risk levels and review notes
- open questions make uncertainty explicit

This repository is intended as a public, reviewable example of the data model and source-grounded
review style.
