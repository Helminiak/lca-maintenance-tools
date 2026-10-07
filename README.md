# Lima Charlie Aero Maintenance Tools

Public repository for generic, reusable Rotax and light-sport-aircraft maintenance utilities and blank engineering templates.

## Purpose

Version-control reusable tooling separately from the Lima Charlie Aero website and from completed customer maintenance records.

This repository supports repeatable preparation, calculation, inspection documentation, and data validation. Each tool must state its assumptions, units, applicability, source references, and limits.

## Current status

Repository bootstrap. Planned tools and forms are not yet validated maintenance procedures or released software.

## Planned contents

- Blank pre-buy, condition-inspection, and periodic-inspection templates.
- Service-interval and maintenance-planning utilities.
- Leak-down recording and comparison helpers with explicit test conditions.
- Unit conversion and other generic engineering calculators.
- BUDS report parsing and validation tools using sanitized examples.
- Reusable blank forms, field definitions, and documentation.

## Planned layout

```text
rotax/                 Generic engine-specific utilities and templates
lsa/                   Generic aircraft inspection templates
calculators/           Calculations with documented units and assumptions
forms/                 Blank public-safe forms
scripts/               Data validation and conversion utilities
tests/                 Reference cases and sanitized fixtures
docs/                  Applicability, source revisions, and tool guidance
handoff/               CURRENT_STATE.md
```

## Repository boundary

Keep website source, content, and SEO tooling in `Helminiak/LimaCharlieAero`.

Keep completed inspections, customer records, aircraft-owner details, invoices, private logbooks, and customer-linked BUDS reports in their designated records system.

## Technical controls

Record the applicable engine or aircraft configuration and the revision/date of each referenced manufacturer document. A calculator or checklist must not replace applicable current maintenance instructions, approval requirements, or the responsible person's judgment.

Do not redistribute proprietary manuals or licensed software. Link to authorized source material where appropriate.

## Public data policy

Commit reusable code, blank templates, source-reference metadata, tests, and sanitized fixtures. Never commit customer or aircraft-owner personal information, credentials, private reports, or completed maintenance records.

## Work control

A Git commit identifies the working state. Use reviewed changes and tagged releases for issued tools or templates. Record the repository, branch, commit SHA, objective, acceptance criteria, and next action in `handoff/CURRENT_STATE.md`.

