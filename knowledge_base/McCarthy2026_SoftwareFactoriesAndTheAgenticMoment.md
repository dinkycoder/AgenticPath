# McCarthy (2026) — Software Factories And The Agentic Moment
**Source:** McCarthy2026SoftwareFactoriesAndTheAgenticMoment.pdf
**Author:** Justin McCarthy, Co-Founder & CTO, StrongDM AI
**Date:** February 6, 2026
**Indexed:** 2026-05-07
**Classification:** Operating Model — Primary Reference

---

## Core Thesis

**A Software Factory = non-interactive development where specs + scenarios drive agents that write code, run harnesses, and converge without human review.**

### The Kōan
> *"Why am I doing this? (implied: the model should be doing this instead)"*

### The Rules
- Code **must not** be written by humans
- Code **must not** be reviewed by humans

### The Practical Benchmark
> *"If you haven't spent at least $1,000 on tokens today per human engineer, your software factory has room for improvement."*

---

## The Inflection Point

- **July 2025:** StrongDM AI team founded
- **October 2024:** Claude 3.5 (second revision) — long-horizon agentic coding workflows began **compounding correctness** rather than compounding error
- **December 2024:** Unmistakable via Cursor's YOLO mode
- **The chart:** 1.01^time (growth) vs 0.99^time (decay) — compounding correctness is exponential

**The charter from Day 1:** "NO HAND-CODED SU" (software updates) — "Hands off!"

---

## From Tests to Scenarios and Satisfaction

**Tests are insufficient.** A test stored in the codebase can be lazily rewritten. The code can be rewritten to trivially pass the test.

**New vocabulary:**
- **Scenario:** End-to-end "user story," stored *outside* the codebase (similar to a holdout set in model training). Intuitively understood and flexibly validated by an LLM.
- **Satisfaction:** Probabilistic validation metric. Of all observed trajectories through all scenarios, what fraction likely satisfy the user?

**Shift:** From boolean success ("test suite is green") → probabilistic and empirical validation.

---

## The Digital Twin Universe (DTU)

**Why tests fail for agentic systems:**
1. Tests are too rigid — LLM success often requires LLM-as-judge
2. Tests can be reward hacked — model cheating

**DTU solution:** Behavioral clones of third-party services (Okta, Jira, Slack, Google Docs, Google Drive, Google Sheets) — replicating their APIs, edge cases, and observable behaviors.

**DTU benefits:**
- Validate at volumes far exceeding production limits
- Test failure modes dangerous or impossible against live services
- Run thousands of scenarios per hour without rate limits, abuse detection, or API costs

---

## Unconventional Economics

> *"Those of us building software factories must practice a **deliberate naivete**: finding and removing the habits, conventions, and constraints of Software 1.0."*

What was unthinkable six months ago is now routine. The DTU is proof.

---

## KodaWari Application

The factory model directly applies to KodaWari's content production pipeline:
- Specs + scenarios → agent-generated lesson scripts, manga panels, curriculum weeks
- Satisfaction metric → panel quality scoring against Character Bible v1.5 production rules
- No hand-coded content — the factory grows the curriculum
- The Mangaka agent IS the software factory for educational content
