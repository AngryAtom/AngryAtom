# AngryAtom Repository Standard

This standard defines the expected shape of public AngryAtom engineering repositories.

The goal is consistency without forcing every project into the same template. Each repository should make its purpose, engineering value, operating model, and documentation path clear within the first few minutes of reading.

## Core Principles

- Preserve technical depth.
- Document engineering decisions.
- Explain how the project is built, operated, secured, and improved.
- Make status and scope obvious.
- Keep sensitive details out of public documentation.
- Cross-link related AngryAtom projects where the connection helps the reader.

## Recommended Repository Structure

Use this structure where it fits the project:

```text
README.md
LICENSE
SECURITY.md
docs/
  architecture/
  guides/
  operations/
  security/
  projects/
  incident-notes/
diagrams/
examples/
CHANGELOG.md
ROADMAP.md
```

Not every repository needs every folder. Small tools should stay lean. Flagship or platform repositories should include more of the structure.

## README Standard

Every public repository should answer these questions:

- What is this?
- Why does it exist?
- What does it demonstrate?
- Who is it for?
- What is the current status?
- Where should a reader start?
- What are the major technical decisions?
- How is it operated, secured, or maintained?

Recommended README sections:

1. Project name.
2. One-sentence positioning statement.
3. Repository status.
4. What this demonstrates.
5. Start here.
6. Architecture or design overview.
7. Operations or usage notes.
8. Security notes.
9. Roadmap.
10. Related repositories.

## Repository Status

Use plain status language:

- Active: current work is ongoing.
- Maintained: stable, updated when needed.
- Reference: kept as a documented example.
- Experimental: used for exploration and learning.
- Archived: no longer maintained.

Status should not hide risk. If a project is experimental, say so.

## Documentation Expectations

Documentation should explain real decisions, not only happy-path setup.

Strong documentation includes:

- Architecture overview.
- Service or component catalog.
- Known limitations.
- Security considerations.
- Operational checklists.
- Failure modes.
- Recovery notes.
- Lessons learned.
- Future plans.

## Case Study Standard

Project case studies should preserve the engineering story:

- Problem.
- Constraints.
- Design goals.
- Architecture.
- User workflow.
- Security model.
- Operations model.
- Interesting failure modes.
- Lessons learned.
- Future direction.

## Security Standard

Public repositories should avoid secrets, private hostnames, credentials, sensitive screenshots, and live attack instructions.

Security documentation should be scoped, legal, and defensive. Lab security work should clearly distinguish contained practice from activity against systems that are not owned or authorized.

## Visual Standard

Use visuals when they clarify the system:

- Mermaid diagrams for architecture and flows.
- Screenshots when they show real product or operational behavior.
- Tables for service catalogs, exposure matrices, and roadmap views.

Visuals should support understanding. They should not replace technical explanation.

## Cross-Linking Standard

Repositories should feel like one engineering ecosystem.

Use cross-links for:

- Flagship architecture that supports a project.
- Case studies related to a tool or service.
- Shared standards.
- Related runbooks, guides, and incident notes.

Avoid unrelated links that make repositories feel cluttered.

## Quality Bar

An AngryAtom repository should leave a technical reader thinking:

This engineer builds real systems, understands the operational consequences, and documents the work clearly enough for someone else to learn from it.
