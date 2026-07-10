# Lesson 1 Wow Moment — Instructor Playbook

**When it runs:** Minutes 3–20 of session 1, immediately after the 3-minute welcome.
**Goal:** Every student leaves the room wanting to know how to do that themselves.
**Non-goal:** Teach anything. This is pure demonstration. The teaching starts *after* the wow.

---

## The core idea

You (instructor) build and deploy a working web app **live**, in front of the class, in under 10 minutes, using Kiro IDE and a plain-English prompt. Then you push it to GitHub Pages, project the QR code, and let students play with the thing on their phones.

The whole loop:

```
Ask class for suggestion → prompt Kiro → files/code appear →
working artifact → git push → GitHub Pages URL → QR code →
students play on phones → "you'll do this yourself by week 3"
```

Total elapsed time: 15–17 minutes.

---

## The five beats

### 1. The Ask (1 min)

> "Someone shout out something fun you'd like to see built in the next 8 minutes — a silly website, a game, a quiz, whatever. If you're shy, I've got a backup idea ready."

- Take one suggestion. If several fly in, pick the most doable and say "we'll queue the rest for later weeks."
- If the class is silent (very possible in the first minute of session 1), smile and say "cool, I've got you" — roll with a rehearsed default (below).
- **Quietly rewrite the suggestion into a more concrete prompt in your head** before you type it. Students said "make a game" → you prompt "make a single-file Snake game in HTML/JS/CSS with arrow-key controls, dark theme, score in the corner."

### 2. The Build (7–8 min)

- Open Kiro IDE on the projector. Empty workspace.
- Type the prompt out loud so students can hear you thinking:
  > "OK, so I want a Snake game, in one HTML file, works in a phone browser, arrow keys or swipe controls, dark theme. Let me just say that."
- Hit enter. Narrate what happens as it happens:
  - "Look — it's asking a clarifying question. It wants to know if I want sound."
  - "Now files are appearing in the sidebar. That's `index.html`. Watch — it's writing code into the file."
  - "It's about to run the code. Let's see what happens."
- If Kiro asks for a permission (e.g., write to disk, run a command), **let students see the prompt** — narrate why:
  > "See how it's asking me? Agents ask for permission before doing things. That's the safety layer. In week 3 we'll spend a whole session on this."
- Open the resulting file in the browser preview. Play the game for 5 seconds. If it works — great. If it has a small bug (say the snake moves too fast), turn to Kiro:
  > "Slow it down and give me a game-over screen when I hit the wall."

**If Kiro produces something broken and can't self-fix in one round-trip: bail.** Move to the deploy step with what you have — students still get the wow. Never let the demo turn into 5 minutes of debugging.

### 3. The Deploy (2 min)

- In the Kiro terminal (or IDE git panel):
  ```
  git add -A
  git commit -m "wow moment demo"
  git push
  ```
- Refresh the pre-configured GitHub Pages URL for the repo.
- Confirm the game loads.

### 4. The Playthrough (3 min)

- Convert the GitHub Pages URL to a QR code (`https://qrcode.show/<url>` works one-shot).
- Project the QR code full-screen.
- **"Everyone pull out your phone. Scan this. Play it."**
- Let the room get loud. This is the point.

### 5. The Frame (2 min)

Cut through the noise:

> "Alright, everybody freeze for a second. That game did not exist 15 minutes ago. Nobody in this room typed a single line of code. I described what I wanted, in English, and an agent built it. Then I deployed it. And now it's on the internet — anyone in the world can play it, at that URL, forever."
>
> "That's an agent. That's what this class is about."
>
> "**By week 3, you'll do that yourself.** By week 6, each of you has your own portfolio site live on the internet. By week 9, your agent will be doing things for you while you sleep. Any questions before we dig in?"

Pause. Take one or two questions. Then transition to the whiteboard for the core lesson.

---

## Safe-default demos (rehearse one, keep the others in your back pocket)

Pick the one you're most comfortable with. Rehearse it end-to-end **at least twice** the day before, timing each run.

### Option A — Snake game (recommended default)

- Universally understood
- Works on phones (touch controls)
- Small enough to build in one shot
- Deterministic — Kiro rarely gets this wrong

**Prompt:**
> "Make a single-file HTML Snake game. Arrow keys on desktop, swipe on mobile. Dark theme, purple snake, score in the corner. Game over screen with a play again button."

### Option B — Meme generator

- High relatability
- Visual — good for a projector demo
- Shareable — students can make memes about their teachers

**Prompt:**
> "Make a single-file HTML meme generator. User picks a template image from a dropdown (I'll add my own images later), types top text and bottom text, hits generate. Result is a downloadable PNG."

**Watch out:** avoid actual meme templates in the demo — school-appropriate blank rectangles only.

### Option C — "Would you rather" quiz

- Zero visual complexity → very fast to build
- Sparks discussion — students can shout answers

**Prompt:**
> "Make a single-file HTML 'would you rather' quiz. 10 hardcoded questions, two buttons per question, tally at the end. Dark theme. Reset button."

### Option D — Pixel-art canvas

- Very visual — great on a projector
- Multi-touch capable → the class can co-draw

**Prompt:**
> "Make a single-file HTML pixel-art canvas. 20x20 grid, click a cell to toggle it filled. Color picker with 8 preset colors. Clear button. Save-as-PNG button."

### Option E — What-should-I-eat picker

- Instantly applicable to students' lives
- Very small, very fast

**Prompt:**
> "Make a single-file HTML 'what should I eat tonight' picker. User types 5 food options, hits spin, gets a randomized pick with a fun animation. Dark theme."

---

## What to AVOID in the wow demo

- ❌ Anything requiring an API key (breaks the illusion of "it just works")
- ❌ Anything requiring user accounts / sign-ins
- ❌ Anything with sound (schools = no sound is a safe default)
- ❌ Anything the agent might get partly wrong that you can't fix in one prompt cycle
- ❌ Anything that touches a database or backend server (single-file HTML/JS/CSS only)
- ❌ Anything the school IT might have blocked (e.g., npm-installed frameworks — stick to CDN or vanilla)
- ❌ Anything topical/controversial — pick evergreen, silly-fun content

---

## The Ladder — closing preview screenshots

Prepare four screenshots or live tabs to show at the end of lesson 1. These preview the wow moments of later weeks.

### Wk 3 — "The agent moved files without me"

- A screenshot or short video (< 30 sec) of an agent restructuring a small codebase — moving files, renaming folders, updating imports — in the Kiro IDE.
- Caption: "That's you, week 3. The agent works at your computer, not just in a chat window."

### Wk 6 — "My website is live on the internet"

- Use the included **sample portfolio**: open `sample-portfolio/index.html` (or its GitHub Pages URL) and click into the live Mood → Playlist mini-app.
- URL visible in the browser bar.
- Caption: "That's you, week 6. This page is live at that URL, right now, for anyone in the world — and a beginner built it."
- After the first cohort ships real portfolios, swap in a past student's (with permission) for even more pull.

### Wk 8 — "The agent remembered me from last week"

- Screenshot of a KiroClaw session where the agent recalls a prior conversation ("Last week you were working on the pixel-art game — want to pick up where you left off?").
- Caption: "That's you, week 8. It remembered you without being told."

### Wk 9 — "The agent worked while I slept"

- A Slack DM or dashboard notification showing a KiroClaw scheduled job that ran overnight and produced a real result (e.g., a morning news digest, a check-my-portfolio report).
- Timestamp clearly on it (e.g., "3:00 AM").
- Caption: "That's you, week 9. Your agent was awake when you weren't."

---

## Prep the night before checklist

- [ ] Kiro IDE installed and signed in on the instructor laptop
- [ ] Instructor GitHub account has a fresh empty repo for the demo (e.g., `agent-demo-YYYY-MM-DD`)
- [ ] Repo has GitHub Pages enabled on `main` branch, root folder
- [ ] Local clone of the repo ready on the instructor laptop with `main` checked out
- [ ] Rehearsed the chosen safe-default demo at least twice, end-to-end, timing each run
- [ ] Confirmed the final URL loads on the instructor phone
- [ ] Bookmarked a QR code generator (e.g., `qrcode.show`)
- [ ] Four Ladder screenshots saved as easy-to-project images (or four browser tabs ready)
- [ ] Have a rollback plan: if Kiro is down, fall back to a rehearsed browser-chat demo that produces a single HTML file the instructor can paste into a new file and open (still deploys via git push)

---

## If it goes wrong

**Kiro is down or offline:** switch to a browser AI chat (Claude, Gemini) that can produce a single HTML file. Copy the HTML into a `index.html`, git push. The story is the same; the tool is different.

**The agent produces something broken and can't fix it in one prompt cycle:** commit and push whatever you have. The story becomes "agents are powerful but not perfect — that's exactly what we'll learn to work with." Then move to the frame beat.

**GitHub push fails:** deploy to Netlify Drop instead (drag-and-drop, no git). Same URL, same wow.

**Nothing works:** show a recording of a prior wow-moment run. Not ideal, but the story lands.

---

## After the demo

Move immediately to the whiteboard for the core lesson. **Reference the wow demo constantly** during the perceive → decide → act discussion. The students just watched it happen — the vocabulary maps onto something they saw with their own eyes.

Praise Kier — and please enjoy each demo option equally.
