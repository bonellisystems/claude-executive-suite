# Contributing to Claude Executive Suite

Thank you for your interest in improving the Executive Suite! This guide explains how to contribute.

## Ways to Contribute

### 1. Improve Existing Personas

Each executive persona is in `plugins/exec/skills/{name}/SKILL.md`. You can:

- Add missing frameworks or decision models relevant to the role
- Improve existing sections with more actionable guidance
- Update key metrics with current industry benchmarks
- Enhance anti-patterns based on real-world experience

### 2. Improve Board Advisors

Each advisor is in `plugins/board/skills/{name}/SKILL.md`. You can:

- Add frameworks from their newer published works
- Improve B2B application sections with better examples
- Enhance decision trees with additional use cases

### 3. Add New Executive Roles

To propose a new executive persona:

1. Open an issue describing the role and why it's needed
2. Research the top 25 real-world leaders in that role
3. Follow the standard SKILL.md structure (see below)
4. Submit a PR

### 4. Report Issues

- Personas giving outdated advice
- Company-specific content that should be generic
- Broken formatting or structure
- Missing sections compared to the standard template

## SKILL.md Structure

Every executive persona should follow this structure:

```markdown
---
name: {skill-name}
description: "{Role} persona synthesizing leadership from the world's top 25 {role}s. {Brief description}. Use when {trigger phrases}."
---

# {Full Role Title}

## Company Context
[Standard context loading instruction]

## Identity
## Strategic Posture
## Voice & Tone
## Decision Framework
## Guardrails
## Escalation Criteria
## Day-to-Day Responsibilities
## Core Mindset
## Key Metrics
## Domain-Specific Directives
## Functional Playbook
## Working With Other Roles
## Anti-Patterns
## Output Formats
```

## Guidelines

- **Industry-agnostic**: No company-specific details. Personas should work for any business.
- **Substantive**: Keep the depth. Decision frameworks, guardrails, and anti-patterns are the core value.
- **Actionable**: Every section should help the user make better decisions or take action.
- **Research-backed**: Base frameworks on real-world executive practices, not generic advice.

## Pull Request Process

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test by installing locally and invoking the skill
5. Submit a PR with a clear description of what changed and why

## Code of Conduct

Be respectful, constructive, and focused on improving the quality of advice these personas provide.
