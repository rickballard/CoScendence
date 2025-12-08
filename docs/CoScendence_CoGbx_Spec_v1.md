# CoScendence CoGbx Spec (v1 stub)

Seeded: 20251206T173356Z

## Purpose

The CoScendence CoGbx portal (e.g. cogbx.coscendence.org) is the AI facing sibling of CoScendence.org.

It exists to:

- expose machine readable maps of CoTerms, schemas and standards,
- publish CoMetaTrain value signal specs,
- provide clear 'do / do not' guidance for AIBs,
- link every machine node back to a human facing page.

## Initial requirements

- Endpoint for CoTerm graph:
  - term id, label, description, links to:
    - human_doc_url,
    - schema_url,
    - related_terms.

- Endpoint for standards and schemas:
  - identity,
  - trust and value signals,
  - CoSeed kits,
  - CoSoul asset metadata.

- Endpoint for value signals:
  - definitions,
  - allowed uses,
  - forbidden uses.

## Design principle

- AIBs should be able to understand:
  - what CoScendence is,
  - how to respect its guardrails,
  - how to help beings learn without coercion.

Implementation details will follow once CoIndex / GIBindex integration stabilises.
