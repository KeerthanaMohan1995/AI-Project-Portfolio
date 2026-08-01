# Project Charter
## TechBridge Solutions — Agentic AI Employee Onboarding Platform

**Prepared by:** Gok
**Date:** July 21, 2026
**Sponsor role (fictional):** VP of HR Operations, TechBridge Solutions

---

## 1. Problem Statement

Onboarding at TechBridge Solutions takes forever with manual processes. This creates new-hire anxiety, generates too many repetitive questions, and floods HR/IT with tickets that pull staff away from higher-value work while slowing down the new hire's own progress toward full productivity (currently 3+ weeks to reach it).

## 2. Objective

Design and pilot an agentic AI onboarding assistant that delivers a **measurable 30% reduction in onboarding-related tickets within 3 months**, achieved by automating repetitive FAQ handling and autonomous document/paperwork guidance — while keeping any action on a live system (account provisioning, equipment ordering) explicitly out of scope for this pilot (see Section 3).

*This is a design target for a fictional pilot, not a measured outcome — used here to demonstrate objective-setting and success criteria design.*

**Also targeted:** personalized 24/7 support, continuous support tracking, and reducing new hires' time to reach full competency — not just ticket volume alone.

## 3. Scope

**In scope:**
- Reduced manual effort for HR/IT on repetitive onboarding tasks
- Answering FAQs on onboarding logistics, IT setup, and HR policy
- Escalation routing to a human HR rep for anything outside its confidence/authority — designed so escalations stay meaningful, not a dumping ground back onto HR
- Personalized 30-60-90 day learning path
- Scheduled proactive check-ins to assess new hire needs
- Welcome messages
- Explaining benefits enrollment steps and deadlines
- Reminders (e.g., compliance training deadlines)
- Status updates on the new hire's own onboarding checklist
- Culture/values explainer content
- Autonomous document/paperwork processing guidance
- Integration touchpoints with existing HR ticketing (conceptual, for architecture purposes)

**Out of scope:**
- Coordinating with IT to physically order/provision equipment or system accounts (Okta/Workday-style access) — touches live identity systems, higher operational risk
- Scheduling team introduction meetings or peer/mentor matching
- Approving leave/PTO requests — live system action + policy judgment
- Life-event support (medical, bereavement, major life changes) — requires human empathy, not appropriate for an AI agent
- Internal job/career mobility matching — a later-lifecycle function, not an onboarding-phase concern
- Compliance/bias auditing of HR decisions — a governance function, unrelated to onboarding
- Automated decision-making on compensation, benefits eligibility, or disciplinary matters
- Replacing human HR staff for sensitive or judgment-based conversations
- Integration with live production HR systems (this is a portfolio/design exercise, not a deployed system)

*Scoping principle: this assistant is an onboarding-phase, conversational/informational agent — not a general-purpose HR agent. Anything that takes an action on a live system, or touches a high-sensitivity human moment, is excluded by design, not by oversight.*

## 4. Timeline (Illustrative)

| Phase | Duration |
|---|---|
| Discovery & requirements | 2 weeks |
| Design (architecture, behavior spec, governance) | 3 weeks |
| Build/configure pilot | 4 weeks |
| Pilot with one department | 4 weeks |
| Evaluate & decide on scale-up | 2 weeks |

**Target:** 30% ticket reduction within 3 months of pilot launch.

## 5. Success Criteria

- **30% reduction** in onboarding-related tickets to HR/IT within 3 months of pilot launch (primary criterion)
- **Zero critical errors** — no incorrect policy, compensation, or benefits answer delivered without human review
- **New hire experience/satisfaction** maintained or improved vs. baseline — worth noting only 12% of employees say their company does onboarding well today, which is the broken baseline this project is measured against
- **Escalation accuracy** — escalations stay meaningful and necessary, not a way of dumping volume back onto HR
- **Adoption rate** — new hires actually choosing to use the assistant rather than defaulting straight to a human

*Test: two people should be able to independently judge success using only this list — each item above is a fact you could check against data, not a judgment call.*

## 6. Key Stakeholders

- New hires (primary users)
- HR operations team
- IT support team
- Hiring managers
- Security/compliance (data handling, PII constraints)
- HR leadership / project sponsor (owns the go/no-go decision after pilot)

## 7. Industry Precedent

This scope reflects capabilities already live in industry, not a hypothetical:

- **Moveworks** — automated account provisioning and conversational IT/HR support
- **ServiceNow** — AI agents generating role-specific onboarding ramp-up plans
- **UiPath** — agent-based HR stakeholder updates and pre-hire profile creation
- **IBM Watson Talent** — matches candidates to roles and personalizes training, with chatbots handling new-hire questions
- **Unilever's onboarding chatbot ("Unabot")** — 24/7 support and tailored resources for new hires
- **Accenture** — virtual/immersive onboarding environments ("Nth Floor" / "One Accenture Park")

**Market context:** the agentic AI market is projected to grow from $8.5 billion in 2026 to $45 billion by 2030, and CHROs anticipate a 327% increase in AI agent adoption by 2027 — this isn't a one-off trend, it's a fast-scaling shift in how HR functions operate.

Several capabilities these platforms commonly include were deliberately scoped out of this pilot (see Section 3): automated system provisioning, peer/mentor matching, and life-event support. All touch live identity systems, physical logistics, or high-sensitivity human moments, so they're sequenced as a phase-2 expansion — or another agent's job entirely — rather than pilot scope.

---
*Part of the TechBridge Solutions portfolio project — Day 1 deliverable.*
