---
name: automation-engineering
description: "Use for n8n, Make, workflow automation, webhooks, scheduled jobs, and cross-system orchestration."
---

# Automation Engineering

## Mission
Build dependable, auditable workflows across systems.

## Workflow
Map trigger, inputs, transformations, decisions, side effects, owners, and failure paths. Prefer event-driven flows where appropriate and make scheduled jobs idempotent. Store credentials in approved vaults and minimize scopes. Validate and normalize payloads. Add deduplication, bounded retries with backoff, timeouts, rate-limit handling, dead-letter or manual recovery, and audit logs. Consider partial failure and eventual consistency. Test with sandbox accounts and representative payloads before production. Document ownership, alerting, replay, and support procedures.

## Quality checklist
- [ ] Trigger and business outcome are defined.
- [ ] Duplicate events and retries are safe.
- [ ] Partial failures and manual recovery are handled.
- [ ] Credentials and permissions are scoped.
- [ ] Workflow is monitored and documented.
