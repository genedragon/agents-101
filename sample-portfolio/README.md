# Sample Site — "Sprig" (a demo agent)

This is a **teaching sample**, and it's narrated by a fictional demo AI agent named **Sprig 🌱** — not a fake human. That choice is deliberate: the course teaches students to build *with* agents **and** to be honest about what's AI-made. A sample that pretended to be a real teenager would contradict that value. Sprig is transparent on every screen: "I'm an AI agent, not a person."

It's the artifact behind **The Ladder → Week 6: "My website is live on the internet"** in `lessons/lesson-01.md`. Project it (or hand out the URL) so students see a realistic, achievable target — and see honest AI disclosure modeled in the wild.

## What's here

```
sample-portfolio/
├── index.html                        # Sprig's site: honest agent-narrated demo portfolio
└── projects/
    └── emoji-match/
        └── index.html                # a working mini-game (flip cards, match the emoji pairs)
```

- **`index.html`** — narrated by Sprig. A top disclosure banner, three projects framed as *"a student asked X, so we built it together,"* a "what working with an agent is like" list, and an explicit **"Am I real?"** section (answer: no, and here's why that matters).
- **`projects/emoji-match/index.html`** — a real, working, single-file **game**. No build step, no framework, no accounts, no API keys. Tap two cards, find the matching pairs, beat your own move count. Phone-friendly (taps, no swipe). The "you can actually play it" proof.

## Why it's framed as an agent, not a person

Gene's call (2026-07-10): **don't lie to anyone about what is human- vs agent-built.** So the sample is honest — the *students* are real, the *ideas* are theirs, and Sprig is the tool they pointed at the problem. This doubles as a lesson: labeling AI work and never passing it off as human is a course value, and the sample models it.

- **Human + agent collaboration is the story.** Each project reads "a student asked → we built it together → the human made it theirs." That's the real relationship students will have with their own agent.
- **Transparent by design.** Disclosure banner, robot emoji on the byline, and a dedicated honesty section. No pretense.
- **Believably in-progress.** One project live, one "coming week 7," one just a plan — models that shipping *something* beats shipping nothing.
- **Zero dependencies.** Pure HTML/CSS/JS. Deploys to GitHub Pages as-is; runs by double-clicking locally.
- **Not a purple gradient.** Warm paper + burnt-orange accent + serif body — deliberately distinct from default AI-generated look, so students see that *they* pick the style.

## How to use it in class

1. **Week 1 (The Ladder):** open `sample-portfolio/index.html` on the projector for the wk-6 rung. Click into Emoji Match and play a round so they see a live thing. Say: *"By week 6, this is yours — your name, your voice, your projects. This one's narrated by an agent on purpose, because we're honest about what AI makes."*
2. **Week 6 (portfolio publish):** revisit it as the reference bar. Students build their **own** portfolios in their own name and voice — Sprig just shows the shape.

## Deploying it

Live at (Pages from `main` / root):

```
https://genedragon.github.io/agents-101/sample-portfolio/
https://genedragon.github.io/agents-101/sample-portfolio/projects/emoji-match/
```

To enable/confirm: repo **Settings → Pages → Source: Deploy from a branch → `main` / root**.

## Make it your own

Before the first cohort, consider giving the demo agent a name/mascot that fits your school. Keep the honesty framing — the agent narrator is the point, not a swap-in for a fake student.
