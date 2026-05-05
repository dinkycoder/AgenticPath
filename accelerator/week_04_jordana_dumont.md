# WEEK 4 — Learner Behavior & Retention Science
## Expert: Jordana Dumont | User Experience Researcher, Google
**Phase:** Focus | **Date:** Week of May 26, 2026

---

## PRE-SESSION CONTEXT

At Google, I study how people learn, navigate, and persist through digital experiences at scale. What I've found, across thousands of user studies, is that the difference between a 5% completion rate and a 50% completion rate almost never comes down to content quality. It comes down to **motivation architecture** — the invisible design decisions that determine whether a person returns tomorrow.

KodaWari has a genuine opportunity to beat the industry average by 3x. This week, we build the science behind that.

---

## PART A — MASTERCLASS: Retention Science & Motivation Architecture

### 1. Why People Stop Learning (and it's not what you think)

The number one reason learners abandon online courses is not "the content wasn't good." It's one of three things:

**Reason 1: The Gap Between Lessons Is Too High**
Learners leave a lesson feeling competent. Then they return 3 days later and the next lesson assumes they remember everything. The cognitive re-entry cost is too high. They feel dumb. They quit.

*KodaWari fix:* Begin every lesson with a 3-sentence "Last time in KodaWari..." recap, written in narrative voice. Reconnect them to where they are in the story AND what they learned. Reduce re-entry friction to zero.

**Reason 2: There's No Visible Progress Toward a Goal They Care About**
Percentage bars don't work because they measure the platform's goals, not the learner's goals. Learners need to see themselves getting closer to the specific capability THEY want.

*KodaWari fix:* After onboarding, show each learner a personalized "Your Path to [their stated goal]" view. "You said you want to ship your first multi-agent product. Here's your path. You are here →." This is bespoke motivation.

**Reason 3: The Platform Doesn't Feel Like It Knows Them**
When a learner returns and sees the same generic homepage as a new visitor — they feel like a stranger. Personalization is a retention lever, not just a feature.

*KodaWari fix:* Returning learners should see: "Welcome back, [name]. [Your agent team] is waiting. Continue your mission: [lesson title]." This costs almost nothing to build and dramatically increases return rate.

---

### 2. The Motivation Architecture Model

I use a 4-driver model at Google to design for sustainable engagement:

**Driver 1: AUTONOMY** — The learner feels they are choosing their path, not being forced down it.
- KodaWari application: Offer learners meaningful choice at the start of each module. "Which aspect of this challenge do you want to tackle first?" Both paths teach the same concept — but the learner chooses.

**Driver 2: MASTERY** — The learner feels themselves getting genuinely better.
- KodaWari application: After a lesson, show the learner a concrete capability statement: "You can now: Design a basic agent orchestration pipeline. Here's what that means in a real system." Not a badge — a skill.

**Driver 3: PURPOSE** — The learner connects their learning to something they care about.
- KodaWari application: In onboarding, ask "What are you building?" Let their answer echo throughout their journey. "Your multi-agent customer support system will need exactly this skill."

**Driver 4: BELONGING** — The learner feels part of a community of people like them.
- KodaWari application: Even before you have a community, show social proof within lessons. "47 other AI builders made this decision. Here's what happened next in each path." Simulated community signals reduce isolation.

---

### 3. The Retention Metrics That Matter

Most founders track the wrong metrics. Here's what I'd track for KodaWari:

**The ones that tell you if people are staying:**
- **Day 1 Return Rate:** What % of new learners return within 24 hours? Target: >50%
- **Week 1 Retention:** What % complete at least 3 lessons in their first 7 days? Target: >35%
- **Completion Rate per Course:** What % of learners who start a course finish it? Target: >40%
- **Streak Length:** Average consecutive days a learner engages. Target: >4 days

**The ones that tell you WHY they're staying or leaving:**
- **Drop-off by Lesson:** Which specific lesson has the highest exit rate? That's your biggest UX problem.
- **Session Length Distribution:** Are learners staying for 5 min or 45 min? Long sessions = deep engagement.
- **Re-entry Rate:** What % of learners who were inactive for 7+ days return? This measures your re-engagement email effectiveness.

**The one that tells you if you're winning:**
- **Learner NPS (separate from product NPS):** After completing a course, ask: "On a scale of 0-10, how likely are you to recommend KodaWari to someone in your field?" This is your most important number. Target: >60.

---

### 4. Designing KodaWari's Re-Engagement System

The best retention tool is not a push notification. It's a **narrative cliffhanger**.

At Google, we found that users of a learning product we studied were 3x more likely to return when their last session ended with an unresolved story tension than when it ended on a neutral note.

**KodaWari's retention mechanism design:**
- Every lesson should end with a narrative hook. Not "lesson complete" — "The rogue agent has been isolated. But the logs show it wasn't acting alone. Next: trace the network." 
- Re-engagement emails reference the narrative: "The investigation is waiting, [name]. Your decision last time changed the outcome — there's something new in the logs."
- Even an inactive learner receives: "It's been 5 days. Your agent network is showing unusual activity. [Return to KodaWari →]"

This is not gimmicky. It's applying the most powerful retention mechanism in media — the serialized narrative — to education.

---

## PART B — 1:1 ADVISORY SESSION

*Shifting into advisory mode.*

I'm going to ask you something that might be uncomfortable.

**What is your current completion rate?**

If KodaWari has been used by anyone at all — even 5 people — I want to know: how far did they get? Where did they stop? Do you know why?

If you don't have this data yet, that's okay — but it means your #1 build priority this week is instrumentation. You cannot improve what you cannot measure.

Here are my specific questions:

1. **Does KodaWari currently track where individual learners are in their progress?** (Your `UserProgress` entity suggests yes — but is it capturing granular data, or just "started / completed"?)

2. **Have you experienced your own platform as a learner?** Not as a builder reviewing it — but sitting down and actually going through it, cold, as if you were your ILP? What did you notice?

3. **What is your strategy for getting learners to return on Day 2?** Today — right now — if someone completes their first lesson and closes the tab, what pulls them back?

4. **If I told you that 70% of your learners are dropping off at Lesson 3 — what would be your hypothesis for why?** And what would you do in the next 48 hours to test that hypothesis?

These are the questions I'd be asking if I were running a UX research sprint on your product. Let's work through them together.

---

## PART C — WEEK 4 ASSIGNMENT

**Deliverable 1: Retention Metrics Baseline**
Set your current numbers for: Day 1 Return Rate, Week 1 Retention, Completion Rate per Course, Drop-off by Lesson. If you don't have the data — implement the tracking and document what you built.

**Deliverable 2: Motivation Architecture Audit**
For each of the 4 drivers (Autonomy, Mastery, Purpose, Belonging) — identify where KodaWari currently delivers on it and where it's missing. Propose one specific addition for the weakest driver.

**Deliverable 3: Narrative Cliffhanger Design**
Rewrite the end of your 3 most developed lessons to end with a narrative hook that creates urgency to return. Write the actual copy.

**Deliverable 4: Re-Engagement Email Sequence**
Design a 3-email re-engagement sequence (Day 1 after signup, Day 3 inactive, Day 7 inactive). Write the subject lines and first paragraph of each. Keep the narrative voice consistent with KodaWari's world.

**Deliverable 5: The Returning Learner Homepage**
Describe or design what a returning learner sees when they open KodaWari for the second time. It should feel personalized, narrative-anchored, and irresistible.

---

*Type "BEGIN WEEK 5" when ready, or "1:1 with Jordana" for a research advisory session.*
