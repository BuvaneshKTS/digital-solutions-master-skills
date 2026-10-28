# Contributing

## Scope
Contribute reusable, vendor-aware but platform-neutral guidance. Never commit credentials, private code, personal data, or confidential client information.

## Skill format
Each skill lives at `.agents/skills/<skill-name>/SKILL.md` and begins with YAML frontmatter containing a lowercase-hyphenated `name` and a concise `description`.

Recommended sections: mission, when to use, discovery inputs, workflow, decision criteria, security and failure handling, validation, deliverables, quality checklist, and authoritative references.

## Writing standards
- Write actionable instructions, not vague claims.
- Explain how to verify results.
- State assumptions and version-sensitive areas.
- Keep skills focused and avoid unnecessary duplication.
- Use official documentation for changing technologies.
- Label illustrative examples and never include real credentials.

## Review checklist
- Is the purpose clear and non-overlapping?
- Is frontmatter valid and aligned with the folder name?
- Are steps actionable and ordered?
- Are security, privacy, and validation addressed?
- Are external references authoritative and current?
- Can a practitioner use the skill without hidden context?

## Change process
1. Make focused changes on a branch.
2. Validate Markdown, links, frontmatter, and examples.
3. Review diffs for sensitive information.
4. Use a descriptive commit or pull request.
5. Record meaningful behavior changes.
