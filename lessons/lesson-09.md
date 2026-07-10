# Lesson 9: KiroClaw Advanced — Cron, Subagents, Self-Learning (Advanced)

**Duration:** 60–90 minutes
**Tools used:** KiroClaw (or OpenClaw)
**Installs required:** None (running from week 8)
**Cost:** $0 (uses the Kiro CLI credit pool)

> **Advanced track.** The peak of the course's depth. The payoff moment: an agent that does work **on its own, on a schedule** — without you asking in real time.

> **⚠️ Same availability note as week 8:** run on OpenClaw if KiroClaw's public repo isn't live yet. Concepts are identical.

---

## Learning objectives

By the end of this session, students will be able to:

1. **Explain a "scheduled job" (cron)** — telling an agent to do something on a schedule, on its own
2. **Set up one scheduled job** that produces a real result (e.g., a morning summary)
3. **Explain what a "subagent" is** — an agent that spins up helper agents to do parts of a task
4. **Describe "self-learning"** — an agent saving lessons so it improves over time
5. **Talk about autonomy responsibly** — the more an agent does on its own, the more your permission choices matter

---

## What students will produce

- One working scheduled job (cron) the student set up
- A short description of a task they'd delegate to a subagent
- A notebook note: "One lesson I'd want my agent to remember so it does better next time"

---

## Why this lesson matters

This is the final "wow" — the wk-9 rung of The Ladder. An agent that shows up at 8 AM and did work you never asked for *in that moment* is a genuinely new idea for most students. It closes the course's escalation: chatbot → agent → workspace → CLI → project → publish → iterate → remembers-you → **acts-on-its-own**. It also lands the responsibility message at its most important: autonomy + permissions = you're still in charge, even when you're not watching.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:10 | Recap + hook | "What if it did work while you slept?" |
| 0:10 – 0:26 | Lesson | Cron, subagents, self-learning — one idea at a time |
| 0:26 – 0:38 | Demo | Instructor sets a job to fire in ~2 min; it runs live |
| 0:38 – 1:02 | Hands-on | Students set up their own scheduled job |
| 1:02 – 1:15 | Discussion | Autonomy & responsibility |

---

## Instructor notes (zero-prereq lesson script)

### Recap + hook (10 min)

> "Last week your agent remembered you. This week it does things *on its own schedule* — even when you're not there. Imagine waking up to a summary of today's weather, your calendar, and a joke, that your agent made at 7 AM without you asking. Let's build that."

### Core lesson (16 min) — one idea at a time

**1. Cron (scheduled jobs).**
> "A cron job is you telling the agent: 'do this thing every day at 7 AM' — and it does, on its own. No app open, no you clicking. It just runs."

**2. Subagents.**
> "For a big task, an agent can spin up *helper* agents — subagents — each doing a piece at the same time, then hand the results back. Like a group project where one person coordinates."

**3. Self-learning.**
> "When you correct the agent — 'always keep it short' — it can *save* that as a lesson and follow it next time, in every future conversation. It gets better because it remembers what you taught it."

Keep each concrete and honest — these are files + a scheduler, not sci-fi.

### Demo (12 min)

On the projector, set a job to fire in ~2 minutes so it runs *during class*:
> "Every day (and right now for the demo), write me a one-line good-morning message with today's date and a fun fact."

Let it fire live. "Nobody asked it just now — the schedule did. That's autonomy." Then show one permission consideration: "Because it can act on its own, what it's *allowed* to do matters even more."

### Hands-on — your scheduled job (24 min)

Each student sets up one cron job with a real, safe output. Ideas:
- A daily "good morning" note with the date + a fact
- A daily study reminder
- A weekly "here's what I said I'd build" nudge from their project plan

Requirements:
1. Set the job.
2. Trigger it (or set it ~2 min out) to see it run.
3. Confirm the output landed.

TA circulates — scheduling syntax is the sticky spot; keep examples on the board.

### Discussion (13 min)

Prompt: **"If an agent can act on its own, who's responsible for what it does?"** Land:
> "Autonomy is powerful and it raises the stakes on your choices. You decide what it's allowed to do and when. An agent working on its own is still working *for you* — and you're still accountable for it. That's true here, and it'll be true for every autonomous system you meet for the rest of your life."

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Cause | Fix |
|---|---|---|
| Job didn't fire | Schedule syntax / agent not running | Use the on-the-board example; trigger manually to test |
| Job fired but did nothing | Task under-specified or blocked on permission | Make the task concrete; check what it needed permission for |
| "So it's alive / conscious?" | Anthropomorphizing autonomy | "It follows a schedule and instructions — powerful, not alive" |
| Set a job that spams | Too-frequent schedule | Daily/weekly, not every minute; show how to pause/remove |
| Overwhelmed | Advanced-track ceiling | Reassure — even *seeing* this work is a win; depth is optional |

---

## Materials needed

- Projector
- KiroClaw/OpenClaw running from week 8
- Scheduling-syntax examples on the board
- A safe demo job pre-tested on the instructor's machine

---

## Homework before next session — showcase prep!

- Keep your scheduled job running for a day; note what it produced
- **Prepare your showcase:** pick your favorite thing you built and get ready to show it in 2 minutes next week
- Update your portfolio so your best project is front-and-center
- Glossary reading: **cron / scheduled job, subagent, autonomy, self-learning**

---

## Optional stretch question (for advanced students)

> "You built an agent that acts on its own. What's one job you'd trust it to do unwatched, and one you absolutely wouldn't? What makes the difference?"

---

## What's next

**Lesson 10: Showcase & launchpad.** You show what you built, we celebrate it, and you leave with a concrete plan to keep learning on your own — the whole point of this club.
