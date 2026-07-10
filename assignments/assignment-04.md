# Assignment 4: Terminal, Tamed

**Due:** End of session 4 (finish at home if needed)
**Estimated time:** 20–30 minutes
**Format:** Kiro CLI / terminal. Log commands and output in your notebook.

---

## Goal

Prove the terminal isn't scary: run three commands yourself, then use Kiro CLI to run one multi-step automation.

---

## Part 1 — Three commands, by hand (10 min)

Open the terminal and run each of these yourself. Write down what each one showed you:

| Command | What it does | What you saw |
|---|---|---|
| `pwd` | where am I? | |
| `ls` | what files are here? | |
| `cat about-me.md` | show me this file | |

None of these change anything — they only look. You cannot break anything with them.

---

## Part 2 — One automation, from the terminal (15 min)

Start Kiro CLI (`kiro-cli chat`) and give it **one** request that takes several steps. Pick one:

- "Make a folder called `week-plan`, add a file for each weekday, and put one goal in each. Then list the folder."
- "Create a folder `about-me`, put three files in it (favorites, goals, funny-story), then show me the folder contents."

In your notebook, list **the steps the agent took** (folder made? files made? listed?). Note any permission prompts you allowed.

---

## Part 3 — Read it back (5 min)

Use `ls` and `cat` yourself to check the agent's work. Did it make everything it said it did? Write one line: *did the agent's report match what you actually see with `ls`?*

(This is a sneaky-important habit: **verify the agent's work yourself.**)

---

## Part 4 — Stretch (optional)

Find one new safe, look-only command (ask the agent: "what's a safe terminal command that only reads or shows information?"). Try it. Write what it does. Do **not** run commands you don't understand.

---

## How this gets graded

"Did you try?" We're looking for:
- You ran `pwd` / `ls` / `cat` yourself and recorded what you saw
- Your automation log shows multiple steps from one request
- You **verified** the agent's work with your own eyes

---

## Bring next week — this one matters!

- **A project idea.** Next week we start building something real that you'll publish. Ideas: something useful to you, a friend, or a family member. A tool, a game, a tracker, a page — anything.
- Your laptop, charged
- Your automation notes

---

## If you're stuck

The terminal cannot be broken by looking. If a command seems stuck, it's probably waiting for you — press **Ctrl-C** to cancel and try again. Ask in the club chat if `kiro-cli` won't start.
