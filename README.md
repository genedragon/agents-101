# Agents 101 — an Agentic AI course for high school students

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status: In development](https://img.shields.io/badge/status-in%20development-orange.svg)](#status)

A free, 10-week, no-prior-CS-needed introduction to agentic AI for high schoolers, taught in a student-club format. Every session ends with a working artifact. By the end, students have a public GitHub Pages portfolio and know where to keep learning on their own.

Repo: **https://github.com/genedragon/agents-101**

---

## Who this is for

- **Students** in grades 9–12 (reading level targeted at grades 10–11)
- **Instructors** at a school, library, makerspace, or community center
- **Parents** who want to learn alongside their kid

## What students will be able to do by the end

1. Explain what an agent is — and what it isn't — to a non-technical adult
2. Use Kiro IDE and Kiro CLI to build, edit, and run a real software project with an agent
3. Publish work to a public GitHub Pages portfolio anyone can see
4. Use Amazon Quick to automate everyday tasks (the "help your parents" tool)
5. Know where to go next — communities, free resources, next projects

---

## Course at a glance

| Wk | Topic | Tool focus | What gets built |
|---|---|---|---|
| 1 | What is an agent? | Browser chat | Plain-English definition + 3 real-world examples |
| 2 | Install Kiro IDE + workspace tour | Kiro IDE | First agent-driven file edit |
| 3 | Tools, files, permissions | Kiro IDE | Multi-tool agent task |
| 4 | CLI primer | Kiro CLI | First terminal automation |
| 5 | Project kickoff — design & scaffold | Kiro | Project plan + scaffold |
| 6 | GitHub + portfolio publish | GitHub Pages | Live public site |
| 7 | Iteration & debugging with agents | Kiro | Working v2 with bug log |
| 8 | Quick — agentic AI for non-developers | Amazon Quick | A Flow that helps a parent/teacher |
| 9 | Stretch track — advanced topics | optional | Advanced demo |
| 10 | Showcase + launchpad | — | Public showcase + next-steps plan |

Each session: 60–90 minutes. Format: short lesson, then hands-on work with instructor and TA available for questions.

---

## What you need

**Students:**
- A laptop (personal or school-provided) — Windows, macOS, or ChromeOS
- An email address (school or personal, with parent help if needed)
- Willingness to make mistakes and ask questions

**Instructor:**
- Comfort using a computer at a power-user level (no coding required — but you'll learn alongside the students)
- One TA per ~10 students recommended
- ~2 hours of prep time per week for the first run

**Network:**
- Internet access (school WiFi is fine, see `school-it-conversation-guide.md` for IT allowlist)
- Ability to install Kiro IDE and Kiro CLI on student laptops

---

## Costs

This curriculum is built to run at **$0 for a pilot cohort of ~10 students**. Every tool is labeled with its actual price.

| Tool | Cost | Notes |
|---|---|---|
| Kiro IDE | Free (50 credits/month perpetual) | Heavy users may exceed; sponsorship ask in `kiro-credits-request.md` |
| Kiro CLI | Free (shared 50-credit pool) | Same account as Kiro IDE |
| GitHub | Free | GitHub Education adds Copilot + Codespaces for free |
| GitHub Pages | Free | 1 GB storage, 100 GB/mo bandwidth |
| Netlify | Free starter | 100 GB/mo, 300 build minutes |
| Hugging Face Spaces | Free CPU tier | Used in week 9 only |
| Amazon Quick (web) | Free forever | Used in week 8 |
| Amazon Quick Desktop | Free for 30 days, then $20/mo | We use the 30-day trial only |

**Worst-case student-cost cushion:** ~$80 to cover 1–2 students who burn through Kiro free credits during deep-build weeks. Schools can budget this or apply for Kiro sponsored credits.

---

## Repository layout

```
agents-101/
├── README.md                          ← you are here
├── LICENSE                            ← CC BY 4.0 — remix and reuse allowed
├── lessons/
│   ├── lesson-01.md ... lesson-10.md  ← full lesson plans
├── assignments/
│   ├── assignment-01.md ... assignment-10.md
├── install-guides/                    ← per-tool, per-OS install walkthroughs (WIP)
├── instructor-handbook.md             ← prep, troubleshooting, rubric (WIP)
├── student-handbook.md                ← glossary, quick reference, prompt cheatsheet (WIP)
├── school-it-conversation-guide.md    ← what to ask school IT (WIP)
├── kiro-credits-request.md            ← draft email to Kiro team (WIP)
└── stretch-track/                     ← advanced topics for eager students (WIP)
```

Files marked WIP are not yet written; they'll land as the curriculum builds out ahead of the September pilot.

---

## How to use this curriculum

**As an instructor:**
1. Read `instructor-handbook.md` first — it has the prep checklist and the "common things that go wrong" guide (when it lands)
2. For each session, read the matching `lessons/lesson-NN.md` and `assignments/assignment-NN.md`
3. Hand students the `student-handbook.md` on day one
4. Use the `install-guides/` files as homework for sessions that need installs

**As a student:**
1. Show up to your first session — no prep needed
2. Keep `student-handbook.md` open as a reference during class
3. After each session, push your work to your GitHub portfolio (your instructor will show you how starting week 6)
4. Ask the agent — that's literally why we're learning this

---

## Design philosophy

This curriculum makes three opinionated choices:

1. **Kiro IDE first, Quick second.** The IDE makes "agent workspace" concepts visible (files, terminal, tool calls all on one screen). Quick comes later as the consumer-facing flavor — "the version you can show your parents."

2. **Build, don't just chat.** Every session produces an artifact, not a transcript. The goal is for students to have *things they made* by the end, not screenshots of conversations.

3. **Teach skepticism on day one.** Agents are wrong sometimes. Week 7 explicitly covers "when the agent is wrong, what do you do?" — but every lesson reinforces verify-then-trust.

---

## Status

**In active development** (June–August 2026). Pilot runs at a local U.S. public high school, Sept–Nov 2026. Post-pilot v2 release: December 2026.

Current state (2026-07):
- ✅ Master spec locked
- ✅ README + Lesson 1 + Assignment 1 drafted (format-setter)
- ⏳ Lessons 2–10 + assignments 2–10 pending
- ⏳ Install guides, handbooks, IT guide pending
- ⏳ Kiro sponsored-credits ask draft pending
- ⏳ September CS-teacher consult
- ⏳ Dry run with TA before pilot

---

## Contributing

Contributions welcome — issues and pull requests both. This curriculum is designed to be **remixed for your school** under CC BY 4.0. If you fork it for a different age group, a different tool stack, or a different cadence, please share what you learn — either open a PR here or drop a link in the issues.

## License

[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) — see [LICENSE](./LICENSE).

You are free to use, remix, and redistribute this curriculum for any purpose (including commercially) as long as you give appropriate credit and link back to this repo.

## Contact

Gene Alpert — GitHub [@genedragon](https://github.com/genedragon)
