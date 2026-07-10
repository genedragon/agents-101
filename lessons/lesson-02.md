# Lesson 2: Install Kiro IDE + Workspace Tour

**Duration:** 60–90 minutes
**Tools used:** Kiro IDE
**Installs required:** Kiro IDE (one install — the only one today)
**Cost:** $0 (Kiro free tier: 50 credits/month, perpetual)

---

## Learning objectives

By the end of this session, students will be able to:

1. **Install Kiro IDE** on their own laptop and sign in
2. **Name the main parts of the workspace:** the file tree, the editor, the terminal, and the agent chat panel
3. **Explain what a "workspace" is** — a folder on your computer the agent can see and work in
4. **Ask the agent to create their first file** and watch it appear in the file tree

---

## What students will produce

- Kiro IDE installed and signed in
- A first file (`hello.md` or `about-me.txt`) created *by the agent* at the student's request
- A one-paragraph note in their course notebook: "Here's what each part of the Kiro window does."

---

## Why this lesson matters

Last week agents were an idea. This week they become a tool on the student's own screen. The single most important concept today is the **workspace** — the folder the agent can see and act in. Everything about tools, files, and permissions in the coming weeks builds on "the agent works inside this folder." Seeing a file the agent created appear in the tree is the first "whoa, it actually did something" moment on their *own* machine.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:08 | Recap | Quick review of perceive → decide → act; collect Assignment 1 |
| 0:08 – 0:30 | Install | Everyone installs Kiro IDE together, step by step |
| 0:30 – 0:45 | Tour | Instructor walks the four parts of the window on the projector |
| 0:45 – 1:05 | Hands-on | Students ask the agent to create their first file |
| 1:05 – 1:15 | Wrap | Notebook note + preview next week |

---

## Instructor notes (zero-prereq lesson script)

### Recap (8 min)

> "Last week: an agent perceives, decides, and acts — and loops. Today we put one on your own laptop. By the end you'll have created a file just by asking."

Collect Assignment 1. TA can skim while the install runs.

### Install together (22 min)

**Go slowly. This is the make-or-break moment — a student stuck on install falls behind for weeks.**

1. Everyone opens `kiro.dev` (or the school-provided install link).
2. Download the installer for their OS (Windows / Mac / ChromeOS via Linux container — see `install-guides/kiro-ide.md`).
3. Run the installer. **This is where school laptop permissions matter** — if installs are blocked, use the fallback (see below).
4. Sign in with the account path the school confirmed (personal, school SSO, or Builder ID).
5. Confirm everyone sees the Kiro welcome screen before moving on.

**The TA's whole job this block:** circulate and unstick. Nobody moves to the tour until their neighbor is also in.

> **Fallback if installs are blocked:** use Kiro in the browser (if available) or GitHub Codespaces with a code-agent extension. `install-guides/kiro-ide.md` has the alternate path. Confirm this with school IT *before* session 2, not during.

### The workspace tour (15 min)

On the projector, open a folder as a workspace and point to each part:

| Part | What it is | Kid-friendly framing |
|---|---|---|
| **File tree** (left) | The files/folders in your workspace | "Everything the agent can see and touch lives here" |
| **Editor** (center) | Where you read and edit files | "The document you're looking at" |
| **Terminal** (bottom) | Where commands run | "The place where things happen — we'll use it more in week 4" |
| **Agent chat** (side) | Where you talk to the agent | "Where you tell the agent what you want" |

**The one big idea:** draw a box around the file tree and say —

> "This folder is the agent's whole world. It can see these files and change them. It can't touch anything outside this box unless you let it. That box is called your **workspace**."

### Hands-on — first file (20 min)

Each student, in their own Kiro:

1. Open (or create) a folder as their workspace — call it `my-first-workspace`.
2. In the agent chat, type: *"Create a file called about-me.md and write three fun facts about me: [their facts]."*
3. Watch the file appear in the tree. Open it. Read it.
4. Then: *"Add a fourth fact: I'm learning to build with AI agents."*
5. Watch the file change.

**Pause the room:** "Did you type into that file directly? No. You asked, and the agent did it. That's the workspace + agent loop."

### Wrap (10 min)

Notebook note: "Label the four parts of the Kiro window and what each does." Preview week 3: "Next week we find out *how* the agent did that — the tools it used, and how you stay in control with permissions."

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Likely cause | Fix |
|---|---|---|
| Installer won't run | School laptop blocks unsigned installs | Use the browser/Codespaces fallback; escalate to IT with the allowlist doc |
| "Can't sign in" | Wrong account type / age gate | Use the account path confirmed with school; see deferred age-policy note |
| Agent chat greyed out | Not signed in, or out of credits | Confirm sign-in; 50 credits is plenty for today |
| File didn't appear | Agent created it outside the open folder | Re-open the correct workspace folder; ask "where did you put it?" |
| Student raced ahead and is lost | Skipped the tour | Pair them with the TA; re-anchor on the four-parts diagram |

---

## Materials needed

- Projector for the install walkthrough + workspace tour
- `install-guides/kiro-ide.md` open and ready
- School IT allowlist confirmed **before** class (Kiro download + sign-in domains)
- WiFi that can handle ~10 simultaneous installer downloads
- A backup USB copy of the installer in case downloads are slow/blocked

---

## Homework before next session

- Make sure Kiro opens and you can sign in (tell the instructor now if it doesn't)
- Ask the agent to create one more file about a hobby — bring it next week
- Glossary reading: **workspace, file tree, terminal, editor, IDE**

---

## Optional stretch question (for advanced students)

> "The agent can only touch files inside your workspace folder. Why is that a *safety* feature and not just a limitation? What could go wrong if an agent could touch any file on your computer?" (We answer this in week 3.)

---

## What's next

**Lesson 3: Tools, files, permissions.** We open the hood: what "tools" the agent actually used to make your file, and how the permission prompts keep you in charge of what it's allowed to do.
