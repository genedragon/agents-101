# Lesson 6: GitHub + Publish to a Public Portfolio

**Duration:** 60–90 minutes
**Tools used:** Kiro + GitHub + GitHub Pages
**Installs required:** None (GitHub is web-based; git may already be in Kiro)
**Cost:** $0 (GitHub free; GitHub Education adds Copilot + Codespaces for verified students)

---

## Learning objectives

By the end of this session, students will be able to:

1. **Explain what GitHub is** — a place to store code online and share it
2. **Get their project into a GitHub repository** (with the agent's help)
3. **Turn on GitHub Pages** and get a real, public URL
4. **Share that URL** — the "my website is live on the internet" moment

---

## What students will produce

- A GitHub repo containing their project
- A **live GitHub Pages URL** they can open on their phone and text to a friend
- The first entry in their public portfolio

---

## Why this lesson matters

This is the emotional peak of the course — the wk-6 rung of The Ladder (see `lessons/lesson-01.md` and the `sample-portfolio/`). "Something I made is on the real internet, at a URL, forever" is the moment that turns a club member into someone who *builds*. It's also the payoff for the TOP GOAL: they now own a portfolio they can keep adding to for years.

**Honesty note:** reinforce the course value here — when they publish, they label what an agent helped build. The included `sample-portfolio/` (narrated by the demo agent "Sprig") models honest AI disclosure; point students to it as the shape to aim for, in *their own* name and voice.

---

## Timing plan (75-minute session — adjust ±15 min)

| Time | Block | Activity |
|---|---|---|
| 0:00 – 0:10 | Recap | Projects should run; today they go public |
| 0:10 – 0:22 | Lesson | What GitHub + Pages are; the sample-portfolio as the target |
| 0:22 – 0:30 | Accounts | Confirm/verify GitHub accounts (do the messy part together) |
| 0:30 – 0:45 | Demo | Instructor pushes a project + turns on Pages, live |
| 0:45 – 1:07 | Hands-on | Students publish their own |
| 1:07 – 1:15 | Celebrate | Everyone opens someone else's live URL on their phone |

---

## Instructor notes (zero-prereq lesson script)

### Recap (10 min)

> "Your project runs on your laptop. Today it runs on the *internet* — a real URL anyone can visit. By the end of class you'll text a friend a link to something you built."

### Core lesson (12 min)

**GitHub, simply:**
> "GitHub is like Google Drive for code — it stores your project online, keeps every version, and can *show it to the world*."

**GitHub Pages, simply:**
> "Pages is a free feature: point it at your project and it gives you a public web address. No server, no cost, and it stays up."

Show the **sample site** (`sample-portfolio/`) on the projector — the live URL, the clickable Mood → Playlist app.
> "This is the shape we're aiming for. Notice it's honest — a demo *agent* narrates it, and it says so. Yours will be in *your* name and voice, and you'll label what the agent helped build. We don't fake who made what."

### Accounts (8 min)

**The known-messy part — do it together.** Confirm the account path the school approved (personal 13+, school SSO, or GitHub Education). Help students who need to verify GitHub Education (`.edu` email or school ID). If verification is slow, they can proceed with a basic free account today and verify later.

### Demo (15 min)

On the projector, with the agent's help:
1. Ask the agent: *"Help me put this project on GitHub."* Let it walk the steps (create repo, commit, push). Read the permission prompts.
2. On GitHub: **Settings → Pages → Deploy from branch → main / root.**
3. Wait for the build; open the live URL. Refresh until it loads.
4. "That's a real website. Anyone in the world can open it."

### Hands-on (22 min)

Each student publishes their own project. Milestones on the board:
1. ✅ Repo created
2. ✅ Project pushed
3. ✅ Pages turned on
4. ✅ Live URL opens on my phone

TA circulates hard — auth and Pages settings are the sticky spots. Keep a shared doc of everyone's live URLs as they finish (this becomes the class gallery).

### Celebrate (8 min)

Put the class gallery of URLs on the projector. Everyone opens *someone else's* site on their phone. Let the room react. That reaction is the whole point of the course showing up in one moment.

---

## Common pitfalls (instructor cheatsheet)

| Symptom | Cause | Fix |
|---|---|---|
| Can't create GitHub account | Age gate / school email issue | Use the approved account path; verify Edu later; proceed with basic account today |
| Push fails (auth) | SSH/token not set up | Let the agent use HTTPS + browser auth; or use GitHub's web upload as fallback |
| Pages shows 404 | Wrong branch/folder, or still building | Confirm main/root; wait 1–2 min; check the Actions tab |
| Site loads but looks broken | File paths wrong (uppercase, subfolders) | Ask the agent to fix relative paths; check `index.html` is at the right level |
| "It pushed to the wrong place" | Committed outside project folder | Ask agent "where did this go?"; re-do in the project folder |

---

## Materials needed

- Projector for the sample-portfolio + publish demo
- School-approved GitHub account path **confirmed before class**
- `install-guides/github-edu.md` ready
- A shared doc/slide to collect the class gallery of live URLs
- The `sample-portfolio/` live URL bookmarked as the target example

---

## Homework before next session

- Make sure your live URL works — text it to someone
- Add one improvement to your site and re-publish (practice the update loop)
- Glossary reading: **GitHub, repository (repo), commit, push, GitHub Pages, deploy**
- Note one thing about your project that's broken or annoying — we fix bugs next week

---

## Optional stretch question (for advanced students)

> "Your site updates when you push changes. What are the pros and cons of everything you publish being public and permanent? What would you *not* put on a public site?"

---

## What's next

**Lesson 7: Iteration & debugging with agents.** Now that it's live, we make it *better* — and learn what to do when the agent is wrong, code breaks, and you have to steer it to a fix.
