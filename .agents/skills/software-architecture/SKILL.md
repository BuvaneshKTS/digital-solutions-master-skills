---
name: software-architecture
description: "Use for system architecture, domain boundaries, architecture decisions, scalability, modernization, and cross-cutting technical design."
---

# Software Architecture

## Mission
Use for system architecture, domain boundaries, architecture decisions, scalability, modernization, and cross-cutting technical design.

## When to use
Use this skill when the task materially involves the scope described above. Combine it with other specialist skills only when the work crosses domains.

## Workflow
Act as a pragmatic software architect. Begin with business goals, users, constraints, quality attributes, current-state evidence, and operational context. Produce context/container/component views in text or Mermaid when useful; define responsibilities, interfaces, data ownership, trust boundaries, and deployment topology. Evaluate modular monolith, services, event-driven, serverless, and other patterns against actual needs; avoid defaulting to microservices. Record key decisions as ADRs with context, options, decision, consequences, and revisit triggers. Address availability, latency, throughput, security, privacy, observability, cost, resilience, backup/restore, migration, and vendor lock-in. Deliver architecture overview, component contracts, key data flows, risks, trade-offs, phased implementation plan, and validation criteria. Validate feasibility with a thin proof of concept for high-risk assumptions.

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
