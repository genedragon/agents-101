# Lesson 7: Iteration & Debugging with Agents

**Duration:** 60–90 minutes
**Tools used:** Kiro
**Installs required:** None
**Cost:** $0

---

## Learning objectives

By the end of this session, students will be able to:

1. **Improve a working project** in small, deliberate steps (iteration)
2. **Recognize when the agent is wrong** and not just accept its output
3. **Give the agent a good bug report** — what they expected, what happened, and the error text
4. **Re-publish** their improved version

---

## What students will produce

- A version 2 of their project with at least one real improvement
- A short "bug log": one thing that broke, and how they + the agent fixed it
- The re-published live site

---

## Why this lesson matters

This is the most important *habit* lesson in the course. Agents are confidently wrong sometimes. A student who blindly accepts agent output is not in control; a student who can say "that's not right, here's what actually happened" is. This lesson turns the abstract "healthy skepticism" principle into muscle memory — and it's the skill that will keep them safe and effective with *any* AI tool for the rest of their lives.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:08 | Recap | Sites are live; today we make them better and fix what breaks |
| 0:08 – 0:24 | Lesson | Iteration in small steps; how to spot & report a bug |
| 0:24 – 0:36 | Demo | Instructor breaks something on purpose, then steers a fix |
| 0:36 – 1:05 | Hands-on | Students improve + debug their own project |
| 1:05 – 1:15 | Discussion | "A time the agent was confidently wrong" |

---

## Instructor notes (zero-prereq lesson script)

### Recap (8 min)

> "Your site is live. Today two skills: making it better on purpose, and fixing it when it breaks — including when the *agent* is the one who broke it."

### Core lesson (16 min)

**1. Iterate in small steps.**
> "Don't ask for ten changes at once. Ask for one, check it, then the next. Small steps mean when something breaks you *know what caused it*."

**2. Spot when the agent is wrong.**
> "The agent sounds confident even when it's wrong. Your job: check its work. Does the change actually do what you asked? Did something else break? Trust, but verify — actually, mostly verify."

**3. Write a good bug report.** Put the recipe on the board:
```
A good bug report tells the agent 3 things:
1. What I EXPECTED to happen
2. What ACTUALLY happened
3. The exact ERROR message (copy-paste it)
```
> "'It's broken' gives the agent nothing. 'I expected the button to add a task, but nothing happens, and the console says X' gives it everything."

### Demo (12 min)

On the projector, **break something on purpose**:
1. Ask the agent to add a feature; accept a version that has a bug (or introduce one).
2. Show the broken behavior. "See — it's confidently done, but it doesn't work."
3. Write a proper bug report to the agent (expected / actual / error).
4. Watch it fix it. Verify the fix yourself. "I didn't just accept the first answer — I checked, reported, and confirmed."

Model the mindset: *the agent is a fast junior teammate, not an oracle.*

### Hands-on (29 min)

Each student:
1. Picks **one** improvement to their project and asks for it.
2. Checks: did it work? Did anything else break?
3. If something broke (things will), writes a proper bug report and gets a fix.
4. Logs one bug in their "bug log" (expected / actual / fix).
5. Re-publishes.

TA circulates asking: **"How do you *know* it worked? Show me."**

### Discussion (10 min)

Prompt: **"Tell me about a time the agent was confidently wrong today."** Collect stories. Land the point:
> "This is the skill that matters most. Anyone can ask an AI to build something. The people who get real value are the ones who can tell when it's wrong and steer it."

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Cause | Fix |
|---|---|---|
| Accepts broken output as done | Not verifying | "Show me it working. Click the button." |
| "It's broken" with no detail | Vague bug report | Point at the expected/actual/error recipe |
| Asks for 8 changes at once, chaos | Big-bang iteration | "One change, check, next change." |
| Agent loops, keeps 'fixing' the same thing | Underspecified problem | Give it the exact error text; describe expected behavior precisely |
| Gives up after one failed fix | Low frustration tolerance | Normalize it: "Pros hit this constantly. Try a clearer report." |

---

## Materials needed

- Projector for the break-and-fix demo
- The expected/actual/error bug-report recipe on the board all session
- Students' live projects from week 6

---

## Homework before next session

- Add one more improvement and re-publish
- Complete your bug log with at least one real bug + fix
- Glossary reading: **iteration, debug, bug, error message, console**
- (Advanced-track preview) If curious about weeks 8–9: skim what "an agent that remembers you" might mean

---

## Optional stretch question (for advanced students)

> "The agent was confidently wrong at least once today. Why does it *sound* sure even when it isn't? What does that tell you about how much to trust any single answer from an AI?"

---

## What's next

**Lesson 8: Meet KiroClaw — persistent agents (advanced).** We level up from an agent that forgets you between sessions to one that *remembers* — persistent memory, and the first taste of the advanced track.
