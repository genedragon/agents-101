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

- **`index.html`** — narrated by Sprig, in simple present tense. A top disclosure banner, one real thing it made (the game), a forward-looking **"What you'll build"** list, and an explicit **"Am I real?"** section (answer: no, and here's why that matters). No invented backstory — it shows what *is* and what students *will* build.
- **`projects/emoji-match/index.html`** — a real, working, single-file **game**. No build step, no framework, no accounts, no API keys. Tap two cards, find the matching pairs, beat your own move count. Phone-friendly (taps, no swipe). The "you can actually play it" proof.

## Why it's framed as an agent, not a person

Gene's call (2026-07-10): **don't lie to anyone about what is human- vs agent-built** — and don't fabricate a past that never happened either. So the sample is honest and simple: Sprig is an AI agent showing one real thing it made and previewing what students *will* build. Present/forward tense, no invented student history.

- **Simple and present-tense.** Sprig shows what it *is* and what students *will* build — it doesn't narrate a fictional backstory ("a student asked me last week...") to sound lived-in. Honesty covers fabricated history, not just fake personas.
- **Transparent by design.** Disclosure banner, robot emoji on the byline, and a dedicated honesty section. No pretense.
- **One real, playable thing.** The live Emoji Match game is the "you can actually do this" proof — better than a page of claims.
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
