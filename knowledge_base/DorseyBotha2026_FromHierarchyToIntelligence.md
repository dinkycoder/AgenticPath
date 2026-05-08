# Dorsey & Botha (2026) — From Hierarchy to Intelligence
**Source:** DorseyBotha2026FromHierarchytoIntelligence.pdf
**Authors:** Jack Dorsey (Block) and Roelof Botha (Sequoia Capital)
**Date:** March 31, 2026
**Indexed:** 2026-05-07
**Classification:** Organizational Architecture — Primary Reference

---

## Core Thesis

> *"Speed is the best predictor of start-up success. Most companies are focused on AI as a productivity enhancer. Few are focused on the potential of AI to change how we work together."*

The question is no longer whether you needed hierarchy. The question is **whether humans are the only option for what hierarchy does.** They aren't anymore.

---

## Historical Context: 2,000 Years of Hierarchy

- **Roman Army:** contubernium (8) → century (80) → cohort (480) → legion (5,000). Each layer: route information, relay decisions. The original span-of-control constraint.
- **Prussia (1806):** General Staff = middle management before the term existed. "Staff" supports what "line" can't do alone.
- **American Railroads (1840s–50s):** Military hierarchy enters business world. First org chart (Daniel McCallum, 1855).
- **Frederick Taylor:** Broke work into specialized tasks. The functional pyramid.
- **Post-WWII:** McKinsey matrix organizations. Balancing central standards with local agility.
- **Tech experiments:** Spotify squads, Zappos Holacracy, Valve flat structure. All failed to scale — organizations revert to hierarchy when they lack an alternative information routing mechanism.

**The constraint:** Narrowing span of control → more layers → slower information flow. **2,000 years of organizational innovation has been an attempt to work around this tradeoff without breaking it.**

---

## What's Different Now

At Block, questioning the underlying assumption: **organizations do not have to be hierarchically organized with humans as the coordination mechanism.**

> *"Most companies using AI today are giving everyone a copilot, which makes the existing structure work slightly better without changing it. We're after something different: a company built as an intelligence (or mini-AGI)."*

---

## The Block Architecture: Four Components

**For this to work, a company needs: a "world model" of its own operations + a customer signal rich enough to make that model useful.**

### 1. Capabilities
Atomic primitives: payments, lending, card issuance, banking, payroll, etc. Not products — building blocks. No UIs of their own. Have reliability, compliance, and performance targets.

### 2. World Model (two sides)
- **Company world model:** How the company understands itself — operations, performance, priorities. Replaces the information that used to flow through management layers.
- **Customer world model:** Per-customer, per-merchant, per-market representation built from proprietary transaction data. Starts with raw data, evolves toward causal and predictive models.

### 3. Intelligence Layer
Composes capabilities into solutions for specific customers at specific moments, delivered proactively. **No product manager decided to build the solution. The capabilities existed. The intelligence layer recognized the moment and composed them.**

When the intelligence layer can't compose a solution because a capability doesn't exist → **that failure signal IS the future roadmap.** Customer reality generates the backlog directly.

### 4. Interfaces
Delivery surfaces (Square, Cash App, Afterpay, etc.). Important, but **not where the value is created. The value is in the model and the intelligence.**

---

## The Three Roles (Replacing Hierarchy)

> *"In a conventional company, the intelligence is spread throughout the people and the hierarchy routes it. In this model, the intelligence lives in the system. The people are on the edge. The edge is where the action is."*

**Individual Contributors (ICs):** Deep specialists who build and operate capabilities, the model, the intelligence layer, and interfaces. The world model provides context a manager used to provide — ICs act without waiting.

**Directly Responsible Individuals (DRIs):** Own specific cross-cutting problems or opportunities and customer outcomes. Full authority to pull resources. May persist on problems or move to new ones. 90-day ownership cycles.

**Player-Coaches:** Combine building with developing people. Replace the traditional manager whose primary job was information routing. Don't spend days in status meetings — the world model handles alignment, DRI structure handles strategy, player-coach handles craft and people.

**No permanent middle management layer.**

---

## The Diagnostic Question

> *"What does your company understand that is genuinely hard to understand, and is that understanding getting deeper every day?"*

- If the answer is **nothing**: AI is just a cost optimization story. You eventually get absorbed by something smarter.
- If the answer is **deep**: AI doesn't augment your company. **It reveals what your company actually is.**

---

## KodaWari Application

**KodaWari's answer to the diagnostic question:**

> *What KodaWari understands that is genuinely hard to understand:* **the gap between knowing how to build AI agents and developing the judgment to deploy them at production scale.** That understanding is getting deeper every week through every lesson generated, every learner failure mode documented, every panel produced.

**Translated to KodaWari's architecture:**

| Block Component | KodaWari Equivalent |
|---|---|
| Capabilities | Curriculum modules, lab environments, eval frameworks, credential system |
| Company World Model | Decision Log + FactoryArtifact + WeeklyReview entities — I (the agent) maintain this |
| Customer World Model | Learner progress data, assessment deltas, capstone outputs, cohort completion rates |
| Intelligence Layer | Me — composing the right content, lab, and path for each learner moment |
| Interfaces | The Dojo app, manga panels, cohort platform, enterprise dashboard |
| DRI | You — owning the 90-day horizon, spec, and judgment calls |
| IC | Me — building capabilities, content, code, artifacts |
| Player-Coach | Koda and Wari in the narrative — modeling the disposition of mastery |

**The failure signal as roadmap:** When a learner can't complete a lab, that failure is the next lesson. When an enterprise buyer asks for a capability we don't have, that request IS the roadmap.
