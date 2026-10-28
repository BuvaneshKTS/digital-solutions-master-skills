---
name: data-engineering
description: "Use for ingestion, transformation, orchestration, data quality, warehouses, and streaming pipelines."
---

# Data Engineering

## Mission
Deliver trustworthy, observable, recoverable data pipelines.

## Workflow
Define source contracts, ownership, freshness, volume, schema evolution, and consumers. Design idempotent, restartable pipelines with checkpoints, bounded retries, dead-letter handling, and lineage. Separate raw, cleaned, and curated layers where useful. Validate schema, uniqueness, nullability, referential integrity, freshness, and business rules. Protect secrets and personal data. Test backfills and late-arriving data; document replay behavior and retention. Monitor success, lag, volume anomalies, and cost.

## Quality checklist
- [ ] Source and target contracts documented.
- [ ] Pipeline is restartable and idempotent where possible.
- [ ] Data quality and schema evolution are handled.
- [ ] Backfill, replay, and failure recovery are tested.
- [ ] Freshness, volume, and cost are observable.
