# AI Calling Strategy — Ditto Insurance

**Nyasa Dwivedi · Product Strategy Case Study**

---

## What This Is

Ditto Insurance loses over 85% of its leads before a prospect ever speaks to an advisor — not because the product is bad, but because the logistics between "form submitted" and "call booked" are slow and manual.

This case study proposes an AI voice calling strategy to fix that gap, without touching the one thing Ditto cannot afford to automate: the advisory call itself.

The central decision this entire document is built around:

> **AI should handle logistics. Humans should handle trust.**

---

## The Problem I Was Solving

Ditto's advisors are spending a meaningful chunk of their day on tasks that require no insurance knowledge — confirming leads, booking slots, sending reminders. Meanwhile, inbound leads who submitted a form 20 minutes ago have already moved on.

The opportunity isn't to replace advisors. It's to make sure leads actually reach them.

---

## What's Inside

**Funnel Analysis** — A stage-by-stage breakdown of where Ditto loses leads, with conversion benchmarks sourced from LeadSquared, Unbounce, and Zopper India. The prioritisation is explicit: Stages 2–3 are the only stages where AI adds value without adding risk.

**User Segmentation** — Three customer segments (under 35, 35–50, 50+) with different channel preferences, behavioural hypotheses, and distinct success metrics. Labelled as hypotheses to be tested in the pilot, not assumptions to be shipped.

**Platform Comparison** — Bolna AI, Exotel, and Plivo evaluated via direct vendor outreach (not just pricing pages). Recommendation: Bolna for the pilot (speed, native Hinglish, no-code), Exotel for scale (BFSI compliance, India data residency).

**AI Caller Design** — A named persona (Arya), a full branching call script under 55 seconds, and 23 edge cases across customer behaviour, technical failures, language switching, and escalation triggers.

**Execution Plan** — A 6-week rollout with owners, dependencies, and a time-of-day calling strategy based on Indian working professional pickup patterns.

**KPI Framework** — 5 metrics with derived targets (not guesses). Each target is anchored to an industry benchmark and tied to a specific decision it should trigger.

**Dashboard Design** — Built around one question a sales manager should answer in under 60 seconds each morning: *did the AI perform, are leads stuck, and are there any brand risk signals?*

---

## The Decision I'm Most Confident In

Keeping Stage 4 — the 30-minute advisory consultation — entirely human.

This is where most "AI in insurance" proposals go wrong. The advisory call is not a cost centre to be optimised. It is Ditto's product. It is why they have a 4.9 Google rating from 12,000+ customers. Automating it would be faster to build and catastrophic to the brand.

Every other decision in this document flows from protecting that boundary.

---

## What I'd Validate Next

The segmentation hypotheses (under-35 users preferring WhatsApp async, 50+ users needing faster human escalation) are stated explicitly as hypotheses — not shipped as decisions. The pilot is designed to test them.

Given more time, I'd:
- Interview 5–8 Ditto customers on whether an AI scheduling call feels helpful or intrusive
- A/B test AI call vs. WhatsApp-first as the lead confirmation channel
- Validate KPI targets against Ditto's actual CRM data before committing to scale benchmarks

---

## Full Document

The complete case study — including funnel tables, call scripts, edge case handling, data schemas, and dashboard wireframe — is in the PDF above.


