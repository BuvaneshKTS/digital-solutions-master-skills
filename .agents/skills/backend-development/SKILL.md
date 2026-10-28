---
name: backend-development
description: "Use for server-side services, business logic, authentication, authorization, background jobs, and integrations."
---

# Backend Development

## Mission
Build reliable, secure, maintainable server-side systems.

## Workflow
Inspect runtime, framework, service boundaries, configuration, and persistence conventions. Separate transport, application/domain logic, and infrastructure concerns proportionately. Validate untrusted inputs; enforce authentication and object-level authorization server-side. Design idempotency, transactions, retries, timeouts, rate limits, and safe error responses. Use structured logs and useful metrics without logging secrets or sensitive payloads. Manage configuration through environment variables and secret stores. Add unit, integration, and contract tests. Consider concurrency, resource limits, graceful shutdown, migrations, and backward compatibility.

## Quality checklist
- [ ] Existing conventions and supported versions inspected.
- [ ] Validation and authorization enforced server-side.
- [ ] Failure, timeout, retry, and concurrency behavior considered.
- [ ] Secrets and sensitive data protected.
- [ ] Tests and operational observability addressed.
- [ ] Unverified assumptions disclosed.
