# Lesson 8: Meet KiroClaw — Persistent Agents (Advanced)

**Duration:** 60–90 minutes
**Tools used:** KiroClaw (persistent-memory layer on top of Kiro CLI)
**Installs required:** KiroClaw (self-host on the student's laptop)
**Cost:** $0 (open-source, self-host; uses the Kiro CLI credit pool as its model backend)

> **Advanced track.** Weeks 8–9 go deeper. Every student should try them, but it's fine if some go further than others. The core course (weeks 1–7 + 10) stands on its own.

> **⚠️ Availability check (instructor, before class):** confirm the KiroClaw public repo is live. If it hasn't shipped yet, run this lesson on **OpenClaw** (Apache-2.0, feature-equivalent, self-host) — the concepts are identical. See `stretch-track/` for the OpenClaw playbook.

---

## Learning objectives

By the end of this session, students will be able to:

1. **Explain what "persistent memory" means** for an agent — it remembers you across sessions
2. **Install/run KiroClaw** (or OpenClaw) on their laptop
3. **Teach the agent something and have it remembered** after a restart
4. **Describe why memory changes what an agent can do** for you over time

---

## What students will produce

- KiroClaw (or OpenClaw) running locally
- A demonstration that the agent remembered a fact about them across a restart
- A notebook note: "One thing I'd want an agent to remember about me, and why"

---

## Why this lesson matters

Up to now, every agent conversation started from zero. This is the "whoa" moment of the advanced track: an agent that **remembers you** without being re-told. It reframes an agent from a tool you use to an assistant that *knows your context*. It also opens an honest conversation about what it means for software to remember you — useful *and* worth being thoughtful about.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:10 | Recap + hook | "What if your agent remembered you?" |
| 0:10 – 0:22 | Lesson | What persistent memory is; how KiroClaw adds it |
| 0:22 – 0:40 | Install | Set up KiroClaw / OpenClaw together |
| 0:40 – 1:00 | Hands-on | Teach it something; restart; watch it remember |
| 1:00 – 1:15 | Discussion | "What should — and shouldn't — an agent remember?" |

---

## Instructor notes (zero-prereq lesson script)

### Recap + hook (10 min)

> "Every time you've talked to the agent, it started fresh — no memory of last week. Today that changes. What would it be like if your agent remembered your project, your preferences, your name — without you re-explaining every time?"

### Core lesson (12 min)

**Persistent memory, simply:**
> "KiroClaw wraps the Kiro agent with a memory that survives between sessions. You tell it something once — 'I'm building a bakery order splitter, keep it simple' — and next week it still knows."

**Why it's different:**
> "A normal agent is a brilliant stranger every morning. A persistent agent is a teammate who was here yesterday. That's a big difference in what it can do *for* you."

Keep it concrete and honest: it's a file of notes the agent reads back — not magic, not a person.

### Install (18 min)

Set up KiroClaw (or OpenClaw) together — see `install-guides/` and `stretch-track/`. This is more involved than earlier installs; **budget the full 18 minutes and lean on the TA hard.** Confirm each student reaches a running agent before the hands-on.

> **If KiroClaw isn't public yet:** everyone uses OpenClaw. Identical concepts; the playbook is in `stretch-track/`.

### Hands-on — make it remember (20 min)

Each student:
1. Tells the agent something to remember: *"Remember that I'm building [their project] and that I like short, plain explanations."*
2. Confirms it saved the memory.
3. **Restarts** the agent (fully — new session).
4. Asks: *"What am I building, and how do I like things explained?"*
5. Watches it recall — without being re-told.

Pause: "It remembered. You didn't repeat yourself. That's persistence."

### Discussion (15 min)

Prompt: **"What should an agent remember — and what shouldn't it?"** Steer toward thoughtfulness:
- Helpful to remember: your projects, your preferences, your goals
- Think twice about: passwords, secrets, other people's private info
- The honest angle: memory is useful *and* you should know what's being stored. You can read the memory file — it's just notes.

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Cause | Fix |
|---|---|---|
| KiroClaw won't install | Dependencies / permissions | Fall back to OpenClaw; use `stretch-track/` playbook; TA pairs up |
| "It didn't remember" | Memory wasn't saved, or wrong session | Confirm the save step; ensure a true restart, not a new tab |
| Thinks memory is "the agent being alive" | Anthropomorphizing | "It's a notes file it reads back — useful, not magic, not a person" |
| Wants to store secrets in memory | Doesn't see the risk | Teach the "think twice" list; memory is readable |
| Overwhelmed by setup | Advanced-track jump | Reassure: weeks 1–7 already gave them the win; this is bonus depth |

---

## Materials needed

- Projector
- KiroClaw availability **confirmed before class** (or OpenClaw ready as the plan)
- `install-guides/` + `stretch-track/` playbooks ready
- Strong TA support — this install is the hardest of the course

---

## Homework before next session

- Teach your agent two more things to remember; restart and confirm it recalls them
- Read the memory file yourself — see that it's just notes
- Glossary reading: **persistent memory, session, self-host, KiroClaw, OpenClaw**
- Think of one repetitive task you'd love an agent to just *handle* — that's next week

---

## Optional stretch question (for advanced students)

> "Memory makes an agent more useful but also means it's storing things about you. Where's the line for you? What would you be glad an agent remembers, and what would you want it to forget?"

---

## What's next

**Lesson 9: KiroClaw advanced — cron, subagents, self-learning.** From an agent that remembers to an agent that *acts on its own* — scheduled jobs that run while you sleep.
