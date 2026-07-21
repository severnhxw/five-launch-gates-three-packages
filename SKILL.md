---
name: gtm-five-launch-gates-three-packages
description: "Public-safe GTM skill for new product launch planning using the GTM Five Launch Gates And Three Packages framework. Use when the user needs GTM-specific support to build, review, or improve a new product launch plan, launch readiness checklist, launch asset package, competitive positioning, pricing adjustment plan, sales/channel enablement plan, marketing brief, or post-launch optimization plan for hardware or consumer products."
---

# GTM Five Launch Gates And Three Packages

Use this skill to turn product information into a practical GTM launch plan using the GTM Five Launch Gates And Three Packages framework.

Core stance: GTM moves a product from “built” to “launched, understood, sold, scaled, and improved.”

## Public-Safe Rules

Keep outputs generic and reusable unless the user explicitly provides company-specific information for a private task.

- Do not invent or expose company names, internal codenames, people, emails, phone numbers, private links, exact costs, exact margins, tokens, credentials, supplier names, customer names, or unreleased launch dates.
- When publishing examples, use placeholders such as `[Product]`, `[Market]`, `[Channel]`, `[Competitor A]`, `[Launch Date]`, and `[Owner]`.
- Replace company-specific stage gates with generic terms such as `development gate`, `production readiness gate`, and `launch readiness gate`.
- Treat price, cost, margin, and sales forecast as sensitive. Ask the user whether the work is private before including exact numbers.
- Flag unverified claims involving performance, medical/health effects, safety, certifications, lab tests, children, or competitor superiority.

## Default Method: GTM Five Launch Gates And Three Packages

Use this method unless the user clearly asks for another framework.

### Five Launch Gates

1. **Sample readiness gate**
   - Purpose: obtain near-final samples before formal launch.
   - GTM actions: collect feedback from product, testing, sales, channel, support, and marketing teams.
   - Output: sample feedback list, issue tracker, optimization suggestions, trial feedback, early selling points, and risk list.

2. **Launch readiness gate**
   - Purpose: confirm the product can move from development into commercial launch preparation.
   - GTM actions: review positioning, price logic, selling points, channel plan, material plan, training plan, and open risks.
   - Output: launch readiness checklist, core message, channel plan, enablement plan, and risk owner list.

3. **First shipment / availability gate**
   - Purpose: ensure goods will be available for the planned launch window.
   - GTM actions: align production, inventory, channel allocation, listing timing, and campaign timing.
   - Output: availability timeline, allocation logic, launch-window risks, and adjustment recommendation.

4. **Official launch gate**
   - Purpose: coordinate the market starting point.
   - GTM actions: align ecommerce, retail, sales, content, PR, social, advertising, supply, support, and customer communication.
   - Output: launch calendar, go-live checklist, content plan, listing plan, sales script, promotion plan, and monitoring plan.

5. **First price adjustment gate**
   - Purpose: plan the first price move after launch as a controlled commercial decision, not a reactive discount.
   - GTM actions: consider competition, cost movement, promotion calendar, sales target, margin target, inventory, and old/new product transition.
   - Output: trigger conditions, price ladder, competitor response plan, promo calendar, and old/new product bridge.

### Three Launch Packages

1. **Specification package**
   Include product specifications, configuration, feature list, certifications if available, product images, comparison basics, listing information, and setup details.

2. **Competition package**
   Include competitor matrix, price-band comparison, feature comparison, use-case tests, advantage/disadvantage summary, attack-and-defense talking points, and positioning implications.

3. **Marketing package**
   Include product story, customer pitch, PR/media angles, creator review guide, ecommerce selling points, detail-page copy, content themes, visual asset direction, campaign assets, and advertising angles.

## Standard Workflow

1. **Clarify the business objective**
   Identify product category, target market, launch timing, business goal, target price band, key competitors, channel scope, and current product stage.

2. **Map the five launch gates**
   Judge whether each gate has a clear owner, input, output, deadline, and risk.

3. **Build the three launch packages**
   List required materials, missing materials, downstream users, owners, and deadlines.

4. **Translate product language into market language**
   Turn technical features into user benefits, use cases, proof points, sales language, and content angles.

5. **Define competitive strategy**
   Identify who to compete against, where the product wins, where to avoid direct comparison, how to defend weak points, and which use cases to amplify.

6. **Define pricing and first adjustment logic**
   Consider competitor price, cost/margin sensitivity, promotion map, launch objective, inventory health, and old/new product transition.

7. **Output an execution-ready plan**
   Use tables, checklists, owners, risks, deadlines, and decision recommendations.

## Output Formats

Choose the structure that best matches the user request.

### GTM Launch Plan

```markdown
# [Product] GTM Launch Plan

## 1. Launch Objective
## 2. Market And Competitor Read
## 3. Positioning And Core Selling Points
## 4. Five Launch Gates
## 5. Three Launch Packages
## 6. Channel Strategy
## 7. Content / PR / Advertising Strategy
## 8. Pricing And First Adjustment Logic
## 9. Risks And Mitigation
## 10. Milestones And Owners
```

### Launch Readiness Review

```markdown
# Launch Readiness Review

## 1. Overall Decision
Ready / Conditionally ready / Not ready

## 2. Five Gate Status
| Gate | Status | Evidence | Risk | Owner | Next Step |
| --- | --- | --- | --- | --- | --- |

## 3. Three Package Status
| Package | Completion | Gap | Business Impact | Next Step |
| --- | --- | --- | --- | --- |

## 4. Critical Risks
## 5. Must-Fix Items
## 6. Recommended Decision
```

### Launch Asset Checklist

```markdown
| Asset | Downstream User | Status | Missing Input | Owner | Deadline |
| --- | --- | --- | --- | --- | --- |
| Specification package | Sales / channel / ecommerce |  |  |  |  |
| Competition package | Sales / channel / leadership |  |  |  |  |
| Marketing package | Content / PR / creators / ads |  |  |  |  |
```

### Pricing Adjustment Plan

```markdown
| Item | Recommendation |
| --- | --- |
| Current price position |  |
| Trigger condition |  |
| Proposed price ladder |  |
| Competitor response scenario |  |
| Margin / inventory risk |  |
| Old/new product bridge |  |
| Communication plan |  |
```

## Quality Rules

- Make the output directly usable, not just conceptual.
- Connect every GTM action to business value: sell-through, launch timing, market share, margin, channel confidence, consumer understanding, or resource efficiency.
- When data is missing, state assumptions and provide a fill-in template instead of stopping.
- Separate facts, assumptions, risks, and recommendations.
- Use neutral placeholders for public examples.
- Keep confidential or unreleased information out of public-facing outputs.

## Common Terms

Use these terms consistently:

- Five launch gates
- Three launch packages
- Sample readiness gate
- Launch readiness gate
- First shipment / availability gate
- Official launch gate
- First price adjustment gate
- Specification package
- Competition package
- Marketing package
- Launch rhythm
- Launch readiness
- Competitive positioning
- Price ladder
- Old/new product transition
- Sales attack-and-defense talking points
- Product-to-market translation

## Final Answer Behavior

For most user requests, output the finished work directly. Do not explain the framework unless the user asks why. If the user provides rough notes, screenshots, or partial product information, extract, restructure, and upgrade them into a polished GTM work product.
