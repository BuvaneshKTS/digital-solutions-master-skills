---
name: api-development
description: "Use for REST, GraphQL, webhooks, API contracts, versioning, authentication, and third-party integrations."
---

# API Development

## Mission
Use for REST, GraphQL, webhooks, API contracts, versioning, authentication, and third-party integrations.

## When to use
Use this skill when the task materially involves the scope described above. Combine it with other specialist skills only when the work crosses domains.

## Workflow
Define consumers, resources, operations, schemas, error model, pagination, filtering, versioning, and compatibility policy. Prefer explicit OpenAPI or equivalent contracts. Apply authentication, authorization, input validation, rate limiting, idempotency, request size limits, and safe CORS configuration. For webhooks, verify signatures, reject replay, acknowledge quickly, process asynchronously, and support retries and deduplication. Set timeouts and bounded retries for outbound calls. Add contract and integration tests; document examples, limits, scopes, and failure behavior.

## Required working habits
- Inspect the actual project, versions, constraints, and existing conventions before proposing changes.
- Separate verified facts, assumptions, recommendations, and open questions.
- Prefer official, current documentation for version-sensitive behavior and cite sources when research is involved.
- Protect credentials, personal information, customer data, and intellectual property.
- Make changes incrementally and explain important trade-offs.
- Ask for clarification only when missing information materially changes the design or could cause unsafe or expensive work.

## Deliverables
Tailor deliverables to the task. Common outputs include a concise assessment, proposed approach, implementation or design artifacts, validation evidence, risks, and next steps. Do not produce irrelevant documents merely to satisfy a template.

## Quality checklist
- [ ] Scope and acceptance criteria are understood.
- [ ] Existing implementation and constraints were inspected.
- [ ] Security, privacy, accessibility, reliability, and maintainability were considered where relevant.
- [ ] Failure paths and operational ownership are addressed.
- [ ] Validation steps are defined and executed where tools permit.
- [ ] Limitations and unverified assumptions are disclosed.

## References
Prefer official documentation for the selected technologies and versions. Add specific authoritative links to this skill's `references/` directory as the skill is expanded.
