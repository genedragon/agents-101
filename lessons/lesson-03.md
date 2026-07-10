# Lesson 3: Tools, Files, and Permissions

**Duration:** 60–90 minutes
**Tools used:** Kiro IDE
**Installs required:** None (Kiro already installed in week 2)
**Cost:** $0

---

## Learning objectives

By the end of this session, students will be able to:

1. **Explain what a "tool" is** for an agent — a specific action it can take (read a file, write a file, run a command, search the web)
2. **Read a permission prompt** and decide whether to allow it
3. **Watch an agent use multiple tools** to complete one request and narrate what it's doing
4. **State the golden rule of staying in control:** read before you allow

---

## What students will produce

- A small task completed by the agent that visibly uses **two or more tools** (e.g., read an existing file, then create a new one based on it)
- A notebook entry listing three tools their agent has, and what each one does
- One example of a permission prompt they allowed and one they'd deny (real or hypothetical)

---

## Why this lesson matters

This is the safety-and-agency backbone of the whole course. Students already saw the agent *act* — now they learn that every action is a specific **tool**, and that they hold a checkpoint: the **permission prompt**. The lesson that sticks: *an agent is powerful, and you are the one who decides what it's allowed to do.* This is where "healthy skepticism, not blind trust" becomes a habit, not a slogan.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:08 | Recap | Workspace = the agent's world; today, what it can *do* in there |
| 0:08 – 0:25 | Lesson | What a tool is; the permission prompt; read-before-allow |
| 0:25 – 0:40 | Demo | Instructor runs a multi-tool task, narrating each permission |
| 0:40 – 1:03 | Hands-on | Students run their own multi-tool task |
| 1:03 – 1:15 | Discussion | "When would you say NO to an agent?" |

---

## Instructor notes (zero-prereq lesson script)

### Recap (8 min)

> "Last week: the workspace is the agent's world. Today: what can it actually *do* in that world, and how do you stay the boss of it?"

### Core lesson (17 min)

**Define a tool simply:**

> "A tool is one specific thing the agent can do. Not 'be smart' — a specific action. Like: read a file. Write a file. Run a command. Search the web. Each one is a tool. When the agent works, it's really just picking tools and using them one after another."

**Put a short list on the board — the agent's toolbox:**

```
read file    write file    run command    search web    list folder
```

**Then the permission prompt — the most important idea today:**

> "Before the agent does something that changes your stuff or reaches outside — like writing a file or running a command — Kiro asks you first. That pop-up is a **permission prompt**. It's your checkpoint. You read what it wants to do, and you say Allow or Deny."

**The golden rule, write it big:**

```
READ BEFORE YOU ALLOW.
```

> "You wouldn't sign a paper without reading it. Same here. The agent is fast and usually right — but *you* are responsible for what it does on your computer."

### Demo (15 min)

On the projector, give the agent a task that forces multiple tools:

> "Read my about-me.md file, then create a new file called intro.md that turns those facts into a friendly one-paragraph introduction."

Narrate each step:
- "See — first permission: it wants to **read** about-me.md. That's safe, it's just looking. Allow."
- "Now it wants to **write** intro.md. It's creating something new, not overwriting. Allow."
- "Two tools, one request. Read, then write. That's an agent working."

Then deliberately show a **deny**:

> "Watch this — I'll ask it to delete a file." *(Ask: "delete about-me.md")* "Here's the permission prompt. This one I'll **Deny** — I'm not ready to lose that file. See how nothing happened? I stayed in control."

### Hands-on (23 min)

Each student runs a two-tool task in their own workspace. Suggested:

> "Read my about-me.md, then make a file called quiz.md with three quiz questions about me based on those facts."

They must:
1. Point at each permission prompt and say (out loud or to a neighbor) what tool it is and whether it's safe.
2. Allow the safe ones.
3. Try one request they'd **deny**, and deny it.

TA circulates asking: "What tool is that prompt asking for? Is it safe? Why?"

### Discussion (12 min)

Put up: **"When would you say NO to an agent?"** Harvest answers. Steer toward:
- Deleting something you can't get back
- Running a command you don't understand
- Anything reaching outside your workspace to the internet or other files
- When you're just not sure — "not sure" is a fine reason to deny and ask a question first

---

## Common pitfalls (instructor cheatsheet)

| Student says / does | Reality | Redirect |
|---|---|---|
| Clicks Allow on everything without reading | Defeats the whole point | "Slow down — what tool is it asking for? Read it first." |
| "Permissions are annoying, can I turn them off?" | You can, but you shouldn't while learning | "The prompt is how you stay in charge. Speed comes later, control comes first." |
| Thinks 'tool' means a physical thing | It's just an action the agent can take | Point back at the board: read/write/run/search |
| Denies everything and gets stuck | Over-corrected | "Reading files is safe. Allow the safe ones — deny the risky ones." |
| Agent did something unexpected | It used a tool they didn't notice | "Scroll up — which tools did it use? Let's read the trail." |

---

## Materials needed

- Projector for the multi-tool demo
- Each student's week-2 `about-me.md` present in their workspace (recreate if missing — good practice)
- The "agent's toolbox" word list ready for the board

---

## Homework before next session

- Ask your agent to do a task that needs at least two tools; write down which tools it used and which permissions you allowed
- Glossary reading: **tool, permission, allow/deny, command**
- Think of one task you would *never* let an agent do without watching closely — bring it

---

## Optional stretch question (for advanced students)

> "Some agents can run in an 'auto-allow' mode where they don't ask permission for each step. When is that a good idea, and when is it dangerous? What would you want to be true before you trusted an agent to run without asking?"

---

## What's next

**Lesson 4: CLI primer.** We move from clicking in the IDE to typing in the terminal with Kiro CLI — the same agent, a leaner cockpit, and your first multi-step automation.
