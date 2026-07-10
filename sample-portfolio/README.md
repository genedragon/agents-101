# Sample Portfolio — "Maya Chen"

This is a **teaching sample**, not a real student. It exists to answer one question a student will silently ask in week 1:

> *"What am I actually working toward?"*

It's the artifact behind **The Ladder → Week 6: "My website is live on the internet"** in `lessons/lesson-01.md`. Project it (or hand out the URL) so students see a realistic, achievable target: a clean personal portfolio with a couple of real projects, built by a beginner with an agent as pair-programmer.

## What's here

```
sample-portfolio/
├── index.html                        # the portfolio landing page
└── projects/
    └── mood-playlist/
        └── index.html                # a working mini-app (pick a mood → get a playlist idea)
```

- **`index.html`** — the portfolio itself. Intro, three projects (one live, one in progress, one just-a-sketch — deliberately, so it feels like week 6 and not a finished product), a "what I learned" list, contact links.
- **`projects/mood-playlist/index.html`** — a real, working, single-file app. No build step, no framework, no accounts, no API keys. Click a mood, get a themed playlist idea and a background color. This is the "you can actually click it" proof.

## Why it's designed the way it is

- **Believably beginner.** Not every project is finished. One is live, one is "coming week 7," one is a sketch for a real person (the student's aunt). That honesty is the point — it models that shipping *something* beats shipping nothing.
- **Voice over polish.** It reads like a 16-year-old wrote it, because a portfolio that sounds human is more motivating to students than a slick agency site they'll never match.
- **Zero dependencies.** Pure HTML/CSS/JS in each file. Deploys to GitHub Pages as-is. Runs by double-clicking the file locally. No install required to demo it.
- **Not a purple gradient.** Warm paper + burnt-orange accent + a serif body font — deliberately distinct from default AI-generated look, so students see that *they* pick the style.

## How to use it in class

1. **Week 1 (The Ladder):** open `sample-portfolio/index.html` on the projector for the wk-6 rung. Click into Mood → Playlist so they see a live thing. Say: *"By week 6, this is yours — your name, your projects."*
2. **Week 6 (portfolio publish):** revisit it as the reference bar. Students aren't copying it — they're using it to understand scope.

## Deploying it (optional)

If enabled on the repo, GitHub Pages serves this at:

```
https://genedragon.github.io/agents-101/sample-portfolio/
```

To enable: repo **Settings → Pages → Source: Deploy from a branch → `main` / root**. Give it a minute, then the URL above goes live.

## Make it your own

Before the first cohort, consider swapping "Maya Chen" for a lightly-fictionalized version that matches your school (mascot, town, a project idea relevant to your students). The closer it feels to *them*, the harder it pulls.
