# WEEK 1 — Product Foundation & Platform Mastery
## Expert: Raphael Laufer | Product Manager, Base44
**Phase:** Launch & Foundation | **Date:** Week of May 5, 2026

---

## PRE-SESSION CONTEXT

Before we begin, I want to frame how I approach product. At Base44, I think about product in terms of *leverage* — what decisions today create the most compounding value over time? KodaWari is at the most important moment in a product's life: the moment before it has users. Every decision you make this week will be either a foundation or a debt you pay later.

---

## PART A — MASTERCLASS: The Product Foundation Sprint

### 1. The One-Line Test

Every product needs to pass the one-line test before anything else:

> "KodaWari is the [WHAT] for [WHO] that [UNIQUE DIFFERENTIATOR]."

Your current framing: *"A cinematic, interactive learning platform for mastering multi-agent AI systems."*

That's good. But it's still product-describing, not value-describing. The best one-liners describe the *transformation* the user experiences.

**Exercise:** Write 5 versions of your one-liner. Each must include: what it is, who it's for, and what they become because of it. We'll stress-test each one.

Example format: *"KodaWari is the academy where AI builders become multi-agent architects — through narrative experiences, not passive videos."*

---

### 2. The Base44 Product Philosophy: Ship, Learn, Ship

At Base44, we operate on a principle that most traditional product managers resist: **you learn more from one live user than from 100 hours of planning.** This isn't permission to ship garbage — it's a mandate to reduce the gap between idea and evidence.

For KodaWari, this means:

**The Minimum Viable Learning Experience (MVLE):**
- 1 complete lesson that runs end-to-end
- A user can start, complete, and feel the cinematic difference
- There is a clear next step (continue to lesson 2 or sign up for Pro)

That's it. That's your Week 1 product goal.

**What you do NOT need this week:**
- Perfect onboarding
- All 3 course tracks complete
- Payment integration
- Certificates

Ship the MVLE. Get one person through it. Observe what happens.

---

### 3. Product Architecture for KodaWari on Base44

Your current entity structure is well-designed:
- `Course` → `Module` → `Lesson` → `Task` → `UserProgress`

Here's what I'd add in Week 1:

**Critical missing entity: `LearnerSession`**
- Tracks time-on-lesson, interaction events, drop-off points
- This is your most valuable data asset — every session a learner takes creates a signal
- Without it, you're flying blind on what's working in your narrative

**Critical missing flow: `Onboarding Checkpoint`**
- Before learners see their first lesson, they answer 3 questions:
  1. "What's your current role?" (Developer / Founder / PM / Other)
  2. "What do you want to be able to DO after KodaWari?" (open text)
  3. "How did you find us?" (channel attribution)
- This data shapes everything: course recommendations, messaging, and your ILP

**Base44 platform features to activate this week:**
- Authentication (user accounts are your #1 requirement — nothing else matters without this)
- Entity relations: ensure `UserProgress` is properly linked to `User` entity
- Row-level security on `UserProgress` (learners only see their own data)

---

### 4. The Prioritization Framework I Use

At Base44, we use a simple 3-axis prioritization for feature decisions:

| Feature | User Value (1-5) | Strategic Value (1-5) | Build Effort (1-5) | Score |
|---|---|---|---|---|
| Authentication | 5 | 5 | 2 | **13** |
| First full lesson | 5 | 5 | 3 | **13** |
| LearnerSession tracking | 3 | 5 | 2 | **10** |
| Payment tier | 4 | 4 | 3 | **11** |
| Certificates | 2 | 3 | 3 | **8** |

The formula: `(User Value + Strategic Value) - Build Effort = Score`. Higher = do first.

**Your Week 1 assignment:** Build this table for your top 10 feature ideas. Then cut everything below 8. Those are your backlog.

---

### 5. Positioning KodaWari Inside the Base44 Ecosystem

This is something I want you to think strategically about. KodaWari is *built on* Base44 — but it can also *partner with* Base44 in meaningful ways:

1. **KodaWari as a showcase app** — Base44 uses successful apps built on its platform as social proof. If KodaWari grows, Base44 has incentive to feature it, promote it, and support it.
2. **KodaWari as an accelerator curriculum tool** — The irony is that the Base44 Accelerator teaches people to build with Base44 using vibe-coding. KodaWari teaches people to *understand the AI systems* that power what those founders build. These are complementary, not competitive.
3. **Leverage Base44's community** — Base44 has a growing community of vibe-coders. These are potential KodaWari users right now. Think about how to reach them through Base44-native channels.

---

## PART B — 1:1 ADVISORY SESSION

*Switching to direct advisory mode.*

Okay. You've read the framework. Now I want to push on something.

You built a platform on Base44 with a beautiful concept — cinematic learning for multi-agent AI. But here's the question I'd ask any founder at this stage:

**"Have you watched one real human being go through a lesson start to finish?"**

Not you. Not a friend who said "this is cool." A stranger. Someone from your target ILP. Someone who doesn't know you and has no reason to be kind.

If the answer is no — that's your entire Week 1. Everything else can wait.

Here are my specific questions for you:

1. **What is the single lesson you're most proud of right now?** Describe it to me. What happens? What does the learner decide? What do they feel?

2. **Where does your product break today?** Be honest. What's the thing you know is broken that you haven't fixed because other things felt more important?

3. **What does authentication look like in your current build?** Is there a user account system? Can learners save their progress? If not — what's blocking you?

4. **What's your personal relationship to the KodaWari brand philosophy?** *Kodawari* is a Japanese concept meaning relentless, obsessive attention to craft. Where do you personally feel that in this product? Where do you feel you've compromised?

I want your answers to these before we move to Week 2.

---

## PART C — WEEK 1 ASSIGNMENT

**Deliverable 1: The MVLE (Minimum Viable Learning Experience)**
Complete one lesson end-to-end on your platform. A user can start, engage, and complete it. The cinematic difference is palpable. Document what you built.

**Deliverable 2: 5 One-Liners**
Write 5 versions of the KodaWari one-liner (what + who + transformation). Share the one you'd put on the homepage.

**Deliverable 3: Feature Prioritization Table**
Apply the 3-axis framework to your top 10 features. Submit the table with your reasoning for your top 3 priorities.

**Deliverable 4: Authentication Status**
Confirm: does KodaWari have working user authentication? If yes — describe it. If no — make it your #1 build priority this week.

**Deliverable 5: Onboarding Checkpoint Design**
Design the 3-question onboarding checkpoint. Write the exact copy for each question and the answer options.

---

## WEEK 1 METRICS BASELINE

Set your starting numbers:

| Metric | Week 1 Baseline | Week 12 Target |
|---|---|---|
| Registered learners | ___ | 2,000+ |
| Complete lessons live | ___ | 15+ |
| Courses complete | ___ | 3 |
| MRR | $0 | $5,000+ |
| Completion rate | N/A | >40% |

---

*Week 2 unlocks when you submit your Week 1 deliverables.*  
*Type "BEGIN WEEK 2" when ready, or "1:1 with Raphael" for a follow-up advisory conversation.*
