# Five Launch Gates And Three Packages

A public-safe Codex skill for planning and reviewing go-to-market launches for hardware and consumer products.

The skill helps an AI agent turn rough product information into practical GTM outputs: launch plans, readiness reviews, asset checklists, competitive positioning, pricing adjustment logic, and post-launch optimization plans.

## What This Project Is

This repository contains a reusable Codex skill built around a simple GTM operating model:

- **Five Launch Gates**: the key decision points from sample readiness to first price adjustment.
- **Three Launch Packages**: the core launch assets needed by sales, channels, ecommerce, marketing, and leadership.

The goal is to help teams move from product information to execution-ready launch work, with clear owners, risks, deadlines, and deliverables.

## When To Use It

Use this skill when you want an AI agent to help with:

- New product launch planning
- Launch readiness reviews
- GTM workback plans
- Competitive positioning
- Sales and channel enablement
- Marketing brief development
- Launch asset checklists
- Pricing and first price adjustment planning
- Post-launch review and optimization

It is designed for hardware and consumer product contexts, but the framework can be adapted to other product launches.

## Framework Overview

### Five Launch Gates

1. **Sample readiness gate**: validate near-final samples and collect cross-functional feedback.
2. **Launch readiness gate**: confirm positioning, price logic, selling points, channel plans, enablement, and risks.
3. **First shipment / availability gate**: align product availability with launch timing and channel allocation.
4. **Official launch gate**: coordinate ecommerce, retail, sales, content, PR, social, advertising, supply, support, and customer communication.
5. **First price adjustment gate**: plan the first controlled price move after launch.

### Three Launch Packages

1. **Specification package**: product details, configuration, feature list, certifications if available, images, listing information, and setup details.
2. **Competition package**: competitor matrix, price-band comparison, feature comparison, use-case tests, positioning, and attack-and-defense talking points.
3. **Marketing package**: product story, customer pitch, PR angles, creator review guide, ecommerce copy, content themes, campaign assets, and advertising angles.

## Repository Structure

```text
.
├── SKILL.md
└── agents/
    └── openai.yaml
```

- `SKILL.md`: the main skill definition and operating instructions.
- `agents/openai.yaml`: optional UI metadata for skill display surfaces.

## Installation

To use this as a local Codex skill, copy the repository folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R five-launch-gates-three-packages ~/.codex/skills/
```

Then restart or refresh your Codex environment so the skill can be discovered.

If your Codex setup supports `.skill` package uploads, package the skill folder so that the archive root contains `SKILL.md`.

## Example Prompts

```text
Use Five Launch Gates And Three Packages to build a launch readiness review for [Product].
```

```text
Create a GTM launch plan for [Product] entering [Market] through [Channel].
```

```text
Review this product brief and identify missing launch assets, risks, owners, and next steps.
```

```text
Build a first price adjustment plan for a consumer hardware product after launch.
```

## Public-Safe Design

This skill is intentionally written for public reuse. It avoids company-specific references, private links, internal stage names, personal details, credentials, exact costs, exact margins, unreleased launch dates, and customer or supplier names.

When using the skill with private business data, keep that data in your own workspace and avoid publishing generated outputs that include confidential details.

## Validation

This skill was validated with the Codex skill validation utility:

```bash
python3 /path/to/skill-creator/scripts/quick_validate.py /path/to/five-launch-gates-three-packages
```

## License

No license has been added yet. Add a license before inviting broad external reuse or contributions.

