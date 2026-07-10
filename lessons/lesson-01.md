# Lesson 1: What Is an Agent?

**Duration:** 60–90 minutes
**Tools used:** Any browser-based AI chat (Amazon Quick web, Claude.ai, ChatGPT, Gemini — instructor's choice)
**Installs required:** None
**Cost:** $0

---

## Learning objectives

By the end of this session, students will be able to:

1. **Define an agent in plain language** — a one-sentence answer they could give to a parent
2. **Distinguish three things:** a calculator, a chatbot, and an agent
3. **Identify three real-world examples** of agents they encounter (Siri, Alexa, autocomplete, etc.) and explain what makes each one "agentic"
4. **Articulate the three things every agent does:** perceive, decide, act

---

## What students will produce

A short written submission in their own words:
- One-sentence definition of an agent
- Three examples of agents from their daily life
- For each example: what does it perceive? What does it decide? What does it act on?

This becomes the first entry in their course notebook (paper notebook, Google Doc, or Notes app — student's choice).

---

## Why this lesson matters

This is the conceptual foundation. **No installs, no terminal, no code.** We want every student to leave session 1 confident that they understand what we're about to spend nine weeks building with. If a student walks out still confused about "what is an agent," every later session will be harder.

The lesson also surfaces a common misconception early: **a chatbot is not the same as an agent.** A chatbot answers; an agent does things. We'll lean on this distinction every week from here on.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:03 | Welcome | Roll call, TA intro — kept short so the wow moment lands early |
| 0:03 – 0:20 | 🎯 **Wow moment** | Instructor builds & deploys a working app **live** based on a student suggestion — see `wow-demo-script.md` |
| 0:20 – 0:35 | Core lesson | "What is an agent?" — instructor-led with whiteboard, referencing what students just watched |
| 0:35 – 0:55 | Hands-on | Students try three prompts on their own browser chat |
| 0:55 – 1:10 | Assignment work | Students start "Three agents in my life" |
| 1:10 – 1:15 | 🪜 **The Ladder** | Preview: what you'll build by wk 3, 6, 8, 9 |

---

## Instructor notes (zero-prereq lesson script)

### Opening (3 min)

> "Welcome. Before we talk about what an agent is, I'm going to **show you one working**. Someone shout out something fun you'd like to see built in the next 8 minutes — a silly website, a game, a quiz, whatever. If you're shy, I've got a backup idea ready."

Take one suggestion. If the class is silent, roll with the rehearsed default (see `wow-demo-script.md`).

### 🎯 Wow moment — live build & deploy (15–17 min)

**This is the hook.** Full playbook lives in `wow-demo-script.md`. High-level beats:

1. **The Ask (1 min):** Take a student's suggestion for what to build. Instructor picks a doable one or falls back to a rehearsed default (Snake game, meme generator, "would you rather" quiz, pixel-art canvas).
2. **The Build (7–8 min):** Instructor types a plain-English prompt into Kiro IDE on the projector. Class watches files appear, code get written, the agent occasionally pause and ask a clarifying question.
3. **The Deploy (2 min):** One commit + push. GitHub Pages URL comes back live.
4. **The Playthrough (3 min):** QR code up on the projector. Students pull out phones, visit the URL, play the thing that didn't exist 10 minutes ago.
5. **The Frame (2 min):** "That's an agent. You'll do that yourself by week 3. By week 6, each of you has your own portfolio site live on the internet. By week 9, your agent is doing work for you while you sleep. Any questions before we dig in?"

**Whatever the students just watched becomes the running example** for the rest of the lesson — the whiteboard three-column diagram references the same build ("when I typed *'make it purple'*, was that perceive, decide, or act?").

### Core lesson (15 min)

**Use the whiteboard. Draw three columns side by side:**

| Calculator | Chatbot | Agent |
|---|---|---|
| You type `2+2`, it shows `4` | You type "what's the weather", it tells you | You type "find me a place to eat near my friend's house tonight", it looks up your friend's address, checks restaurants, reads reviews, picks one |

**Key teaching points:**

- A **calculator** has fixed rules. Same input = same output. No "decisions."
- A **chatbot** generates an answer. It looks at what you said, and produces text. One step.
- An **agent** does *more than one step on its own*. It perceives the world (reads files, looks up websites, checks the time), decides what to do next, and acts (sends a message, edits a file, runs a command). Then it loops.

**Write on the board:**

```
AGENT = perceive → decide → act → repeat
```

This is the definition we'll come back to every week.

**Point back to the wow demo:**
- "When Kiro read the existing files before writing code — that was perceive."
- "When it chose which file to edit and what to write — that was decide."
- "When it saved the file and ran the build — that was act."
- "Then it looked at the result and kept going — that's the loop."

**Then ask the class:**
- "Is Siri an agent or a chatbot?" *(Depends. Siri answering "what time is it" is a chatbot. Siri setting a timer or texting your mom is an agent — it acted on the world.)*
- "What about autocorrect?" *(Mostly a chatbot — it predicts text, doesn't act on anything.)*
- "What about a self-driving car?" *(Agent. Perceives the road, decides where to go, acts on the steering wheel.)*

**Mini second demo (5 min) — the perceive→decide→act ladder in a browser chat:**

Open the chosen browser chat tool. Try this sequence:

1. Ask: *"What's today's date?"* — chatbot behavior, one step.
2. Ask: *"What is the weather where I am right now?"* — has to perceive (geolocate? ask?), decide, and act (fetch).
3. Ask: *"Make me a 4-day itinerary for a fun weekend in [your city] — pull real events happening this weekend, with links."* — full agent behavior. It looks up multiple things, decides what to include, and assembles.

**Pause after each step:** "Was that perceive, decide, or act? Or all three?"

### Hands-on (20 min)

Each student opens the browser chat tool. Have them try three prompts:

1. **A chatbot-style prompt:** *"What is the capital of France?"*
2. **A research-style prompt:** *"Find three free online courses about [a topic the student cares about]. Include links and what's covered in each one."*
3. **An agentic prompt:** *"Help me plan something I should do this Saturday. Look up events happening near my school. Pick the three best and tell me why."*

**Have students compare the three answers.** Which felt like a calculator? Which felt like a chatbot? Which felt like an agent?

### Assignment kickoff (15 min)

Hand out (or post) the assignment for the week (see `assignment-01.md`). Students should begin filling out the worksheet while you and the TA circulate to answer questions.

### Closing discussion (5 min)

Pick 3–4 student examples and put them up on the board. For each, probe the class:
- "Does it perceive? What?"
- "Does it decide? Or does it follow fixed rules?"
- "Does it act on the world?"

Reinforce: there's no shame in getting it wrong. Some real-world tools are *kind of* agentic but not fully. That gray area is part of the field.

### 🪜 The Ladder — closing preview (5 min)

Before dismissing, project four screenshots (or live tabs) showing where the course goes. This gives students the arc — "here is what YOU will build" — and ends session 1 on a forward-looking note.

| Week | The wow moment | What students see |
|---|---|---|
| **Wk 3** | *"The agent moved files without me"* | An agent restructuring a small codebase in real time — students realize agents can do work at their computer, not just answer questions |
| **Wk 6** | *"My website is live on the internet"* | The included **sample portfolio** (`sample-portfolio/index.html`) loading on their phone with a real URL they can share — click into "Mood → Playlist" so they see a live, working thing a beginner built |
| **Wk 8** | *"The agent remembered me from last week"* | A KiroClaw agent recalling a prior conversation without being told anything — the moment persistence clicks |
| **Wk 9** | *"The agent worked while I slept"* | A screenshot or Slack post from a KiroClaw scheduled job that ran overnight and produced a real result — the moment autonomy clicks |

Close with:
> "Week 1 job is to leave here knowing what an agent *is*. Weeks 2–10 you'll learn to *build one*. See you next week — bring a laptop."

---

## Common pitfalls (instructor cheatsheet)

| Student says... | Reality | How to redirect |
|---|---|---|
| "ChatGPT is an agent." | Plain ChatGPT (no tools) is a chatbot — sophisticated, but one-step. *ChatGPT with browsing/tools enabled* is agentic. | "Is it doing more than one step? Is it looking up real-world stuff or running tools? If yes, agent. If just generating text, chatbot." |
| "My phone's autocomplete is an agent." | No — it predicts the next word, one step at a time, no decisions about the world. | "It's smart, but is it changing anything other than the words on your screen? An agent does *things*." |
| "If it talks back, it's an agent." | The talking-back is the chatbot part. Acting is the agent part. | Draw the three-column whiteboard again. |
| "Then ALL apps are agents — Spotify recommends, Instagram suggests, etc." | These are recommendation systems, not agents — they don't take multi-step autonomous actions. | "Did the app actually go do something for you, or did it just suggest? Suggestion alone isn't agency." |
| "Are agents the same as AI?" | AI is the umbrella. Agents are a specific *use* of AI that involves acting, not just predicting. | "All agents use AI. Not all AI is agentic." |

---

## Materials needed

- Whiteboard or large paper for the three-column diagram
- Projector or large screen for the wow-moment demo and the ladder preview
- Instructor laptop with Kiro IDE installed and signed in (or fallback browser AI chat with code output)
- Pre-created empty GitHub repo for the wow-demo build, with GitHub Pages enabled
- Phone or tablet to generate a QR code for the finished demo URL (`qrcode.show` or similar)
- WiFi access for student phones (they'll visit the deployed URL live)
- WiFi access for student laptops for the hands-on segment
- One browser-based AI chat account per student (sign-ups happen at home as homework)

## Instructor prep checklist (do the night before)

- [ ] Kiro IDE loaded on instructor laptop, signed in, works
- [ ] Empty scratch workspace ready to accept the demo build
- [ ] Empty GitHub repo created for the demo (e.g. `agent-demo-YYYY-MM-DD`) with Pages enabled on `main`
- [ ] Rehearse the safe-default demo end-to-end (see `wow-demo-script.md`) — measure the time. If it takes > 10 minutes, pick a simpler default.
- [ ] Have the four "Ladder" screenshots ready — one per milestone (wk 3, 6, 8, 9). See `wow-demo-script.md` for what each should show.
- [ ] QR-code generator bookmarked (e.g. `qrcode.show/<url>`) so you can share the demo URL to phones in one click.

---

## Homework before next session

- Read the `student-handbook.md` glossary entries for: **agent, chatbot, model, prompt, tool**
- Sign up for a free account on one of: Claude.ai, Gemini, or Amazon Quick web (instructor picks the default) — just to have hands-on browser chat experience before class next week
- Bring a laptop next week — we install Kiro IDE in session 2

---

## Optional stretch question (for advanced students)

> "If an agent makes the wrong decision, who is responsible — the person who built it, the person using it, or the agent itself? Bring an opinion next week. We'll come back to this in lesson 7."

---

## What's next

**Lesson 2: Install Kiro IDE + workspace tour.** Students will install their first piece of agentic software and see the workspace concept (files, terminal, agent panel) for the first time.
