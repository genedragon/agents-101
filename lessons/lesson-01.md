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
| 0:00 – 0:05 | Welcome | Roll call, club rules, intro to the TA, what we'll build over 10 weeks |
| 0:05 – 0:20 | Lesson | "What is an agent?" — instructor-led with whiteboard / slides |
| 0:20 – 0:30 | Demo | Instructor demos a browser chat doing something agentic in real time |
| 0:30 – 0:50 | Hands-on | Students log into the browser chat tool and try the prompts below |
| 0:50 – 1:05 | Assignment work | Students start the "Three agents in my life" assignment |
| 1:05 – 1:15 | Discussion | Share examples; instructor probes "is that really agentic? why?" |

---

## Instructor notes (zero-prereq lesson script)

### Opening (5 min)

> "Welcome. Over the next 10 weeks we're going to learn what agentic AI is by actually using it — not just talking about it. By week 10 you'll have a public website with something you built, and you'll know how to keep going on your own."
>
> "Quick rules: nobody here knows everything. Asking questions is the whole point. There's a TA (introduce them) and there's me. We will get stuck together. That's normal. The agents we use will sometimes be wrong — we'll learn to spot that and fix it."

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

**Ask the class:**
- "Is Siri an agent or a chatbot?" *(Answer: it depends. Siri answering "what time is it" is a chatbot. Siri setting a timer or texting your mom is an agent — it acted on the world.)*
- "What about autocorrect?" *(Mostly a chatbot — it predicts text, doesn't act on anything.)*
- "What about a self-driving car?" *(Agent. Perceives the road, decides where to go, acts on the steering wheel.)*

### Demo (10 min)

Open the chosen browser chat tool on the instructor's screen. Try this sequence — it shows the perceive → decide → act loop clearly:

1. Ask: *"What's today's date?"* — chatbot behavior, one step.
2. Ask: *"What is the weather where I am right now?"* — the tool has to perceive (geolocate? ask?), decide, and act (fetch). The student sees it pause and think.
3. Ask: *"Make me a 4-day itinerary for a fun weekend in [your city] — pull real events happening this weekend, with links."* — full agent behavior. It will look up multiple things, decide what to include, and assemble.

**Pause after each step and ask the class:** "Was that perceive, decide, or act? Or all three?"

### Hands-on (20 min)

Each student opens the browser chat tool. Have them try three prompts:

1. **A chatbot-style prompt:** *"What is the capital of France?"*
2. **A research-style prompt:** *"Find three free online courses about [a topic the student cares about]. Include links and what's covered in each one."*
3. **An agentic prompt:** *"Help me plan something I should do this Saturday. Look up events happening near my school. Pick the three best and tell me why."*

**Have students compare the three answers.** Which felt like a calculator? Which felt like a chatbot? Which felt like an agent?

### Assignment kickoff (15 min)

Hand out (or post) the assignment for the week (see `assignment-01.md`). Students should begin filling out the worksheet while you and the TA circulate to answer questions.

### Closing discussion (10 min)

Pick 3–4 student examples and put them up on the board. For each, probe the class:
- "Does it perceive? What?"
- "Does it decide? Or does it follow fixed rules?"
- "Does it act on the world?"

Reinforce: there's no shame in getting it wrong. Some real-world tools are *kind of* agentic but not fully. That gray area is part of the field.

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
- Projector or large screen for the instructor demo
- WiFi access for student laptops
- One browser-based AI chat account per student (sign-ups happen at home as homework — see `assignment-01.md`)

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
