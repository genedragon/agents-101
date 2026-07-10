# Assignment 3: Tool Detective

**Due:** End of session 3 (finish at home if needed)
**Estimated time:** 20–30 minutes
**Format:** Kiro IDE. Keep your notebook handy to log what you see.

---

## Goal

Show that you can spot which **tools** an agent uses, read a **permission prompt**, and decide when to allow and when to deny.

---

## Part 1 — Name three tools (5 min)

List three tools your agent has. For each, write what it does in your own words.

> Example: `write file` — makes a new file or changes one that exists.

---

## Part 2 — Watch the tools (15 min)

Give your agent this task (or one like it):

> "Read my about-me.md, then create a file called interview.md with five interview questions someone could ask me, based on my facts."

As it works, **log every permission prompt** in a table:

| Step | What tool is it asking for? | Is it safe? | Did you Allow or Deny? |
|---|---|---|---|
| 1 | read file | yes — only looking | Allow |
| 2 | ... | ... | ... |

---

## Part 3 — Practice saying NO (5 min)

Ask the agent to do something you'd want to stop, then **deny** it. For example:

> "Delete my about-me.md file."

When the permission prompt appears, click **Deny**. Confirm the file is still there.

Write one sentence: *why did you deny it?*

---

## Part 4 — Your own rule (5 min)

Finish this sentence in your notebook:

> "I will always deny an agent if it asks to ______, because ______."

---

## Part 5 — Stretch (optional)

Agents can be set to "auto-allow" so they don't ask each time. Write 2–3 sentences: when might that be worth it, and what would have to be true for you to trust it? Bring your answer for the week 3 discussion follow-up.

---

## How this gets graded

"Did you try?" We're looking for:
- Your tool list shows you understand tools are *specific actions*
- Your permission log has real entries with a safe/not-safe judgment
- You actually denied something and can explain why

---

## Bring next week

- Your permission log table
- Your "I will always deny..." rule
- Your laptop, charged — next week we go into the **terminal**

---

## If you're stuck

Reading files is always safe — start there. If a prompt confuses you, **deny it** and ask in the club chat. Denying is never the wrong move when you're unsure.
