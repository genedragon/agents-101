# Lesson 4: CLI Primer — Meet the Terminal

**Duration:** 60–90 minutes
**Tools used:** Kiro CLI (terminal)
**Installs required:** Kiro CLI (shares the same free credit pool as the IDE)
**Cost:** $0 (same 50 credits/month pool)

---

## Learning objectives

By the end of this session, students will be able to:

1. **Open a terminal** and explain what it is — a place to type commands instead of clicking
2. **Run three basic commands** to look around (list files, see where they are, read a file)
3. **Start Kiro CLI** and give the agent a task from the terminal
4. **Complete one multi-step automation** — a single request that makes the agent do several things in a row

---

## What students will produce

- Kiro CLI installed and launched
- A short automation the agent ran from the terminal (e.g., "make a folder, put three themed files in it, and list them back to me")
- A notebook note: "Three commands I can type myself, and what they do."

---

## Why this lesson matters

The terminal is where a lot of students freeze — it looks intimidating and "hacker-ish." Demystifying it early is a gift that pays off for the rest of their computing lives. The key reframe: *the terminal is just another way to talk to your computer — text instead of clicks — and the agent lives there too.* By the end, the scary black box is a tool they've used on purpose.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:08 | Recap | Tools & permissions; today, a new place to use them |
| 0:08 – 0:22 | Lesson | What the terminal is; three safe commands to look around |
| 0:22 – 0:35 | Install | Launch Kiro CLI together |
| 0:35 – 0:40 | Demo | Instructor runs a multi-step automation from the CLI |
| 0:40 – 1:05 | Hands-on | Students run their own automation |
| 1:05 – 1:15 | Wrap | "The terminal isn't scary" debrief + preview project weeks |

---

## Instructor notes (zero-prereq lesson script)

### Recap (8 min)

> "You've been clicking to talk to the agent. Today you'll *type* — in the terminal. Same agent, new cockpit. And by the end the terminal won't feel scary."

### Core lesson (14 min)

**Reframe the terminal:**

> "The terminal is just a place where you type commands and the computer does them. That's it. No mouse. Before graphical windows existed, this is *all* there was. It looks intense but it's just text in, text out."

**Teach exactly three safe, read-only commands. Put them on the board:**

| Command | What it does | Say it as |
|---|---|---|
| `pwd` | Shows the folder you're in | "where am I?" |
| `ls` | Lists the files here | "what's here?" |
| `cat filename` | Prints a file's contents | "show me this file" |

> "All three of these just *look*. They don't change anything. Perfect for getting your bearings. Try them — you literally cannot break anything with these three."

(Windows note: PowerShell uses the same `pwd`/`ls`/`cat` aliases — students are fine. `install-guides/kiro-cli.md` covers per-OS specifics.)

### Install & launch (13 min)

1. Install Kiro CLI (see `install-guides/kiro-cli.md`) — it uses the same login and credit pool as the IDE, so no new account.
2. Open the terminal (in Kiro IDE's built-in terminal is easiest — one window).
3. Type the three safe commands and watch the output.
4. Start the agent: `kiro-cli chat` (or the current launch command).
5. Confirm everyone sees the agent prompt.

### Demo — first automation (5 min)

On the projector, one request that chains several actions:

> "Make a folder called playlist-ideas, then create three files inside it — one for a workout playlist, one for studying, one for chilling — each with 3 song ideas. Then list the folder so I can see them all."

Narrate: "One sentence from me. Watch — it made a folder, wrote three files, and listed them. Several steps, one ask. That's automation, and permissions still protect you at each step."

### Hands-on — your automation (25 min)

Each student picks a theme and runs a multi-step automation from the CLI. Ideas:
- "Make a folder `about-me`, put three files in it (favorites, goals, funny-story), then list them."
- "Create a `week-plan` folder with a file per weekday, each with one thing I want to do."

Requirements:
- Use at least one of `pwd` / `ls` / `cat` themselves, by hand, first.
- Then give the agent one multi-step request.
- Read the permission prompts (callback to week 3).

TA circulates: "Type `ls` yourself — what do you see? Good. Now ask the agent."

### Wrap (10 min)

> "Raise your hand if the terminal felt scary an hour ago." (Most hands.) "Raise your hand if you just used it on purpose." (Same hands.) "That's the win. Next week we stop doing tiny exercises and start a real project you'll publish."

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Cause | Fix |
|---|---|---|
| "command not found" | Kiro CLI not on PATH / not installed | Re-run install; use the IDE's built-in terminal; check `install-guides/kiro-cli.md` |
| Typed a command in the agent chat instead of the shell | Confused the two prompts | Show the difference: shell prompt vs `kiro-cli chat` prompt |
| Terminal "froze" | A command is waiting for input | Ctrl-C to cancel; explain it's waiting, not broken |
| Afraid to type anything | Terminal intimidation | Start with `ls` — "this only looks, it can't break anything" |
| Ran out of credits mid-class | Heavy earlier use | Reassure: resets monthly; keep today's asks small |

---

## Materials needed

- Projector for the command board + automation demo
- `install-guides/kiro-cli.md` ready
- The three-command reference (`pwd` / `ls` / `cat`) visible all session
- Confirmed CLI install works on the school's laptop image (test before class)

---

## Homework before next session

- Run `pwd`, `ls`, and `cat` on your own at least once
- Give the agent one multi-step automation from the terminal and note the steps it took
- Glossary reading: **CLI, terminal, command line, automation, PATH**
- **Come with a project idea!** Next week we start building something real. Think: something useful to you, a friend, or family.

---

## Optional stretch question (for advanced students)

> "The IDE and the CLI are the same agent with the same tools. Why might a professional prefer the terminal for some tasks even though the IDE has buttons? (Hint: think about speed, scripting, and doing the same thing 100 times.)"

---

## What's next

**Lesson 5: Project kickoff — design & scaffold.** No more exercises. You pick a real project, design it *with* the agent, and scaffold the first version. This is the start of the thing you'll publish in week 6.
