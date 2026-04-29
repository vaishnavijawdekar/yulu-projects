# Yulu Projects

A shared index of all Yulu-related projects — production tools, workshops, prototypes, and experiments built by PMs, designers, and engineers across the team.

This repo doesn't host the projects themselves. It's a directory that points to where each project lives, who built it, and what it does.

**Want to add your project?** See [CONTRIBUTING.md](./CONTRIBUTING.md) — open an issue using the "Add a project" template, or PR an entry directly into this README.

---

## Production / Live Tools

Projects that are deployed and in active use.

### yulu-intel
Automated competitive intelligence platform for the Indian micromobility market. Tracks competitors (Bounce, Rapido, Zypp), generates monthly analysis reports via GitHub Actions, and delivers insights to Slack.

- **Repo:** https://github.com/kritisharma2708/yulu-intel
- **Live:** https://competeiq-reports.onrender.com
- **Owner:** @kritisharma2708
- **Tech:** Python, Node.js, Supabase, GitHub Actions, Exa API, OpenAI
- **Status:** Live
- **Ownership:** Personal experiment (Yulu-themed)

### yulu-intel-slack-bot
Slack Q&A bot for querying Yulu competitive intelligence data. Companion to yulu-intel — gives the team a conversational interface over the same dataset.

- **Repo:** https://github.com/kritisharma2708/yulu-intel-slack-bot
- **Owner:** @kritisharma2708
- **Tech:** Node.js, Slack Bolt, OpenAI, Supabase
- **Status:** Live
- **Ownership:** Personal experiment (Yulu-themed)

---

## Workshops & Learning

Educational material, internal training, course content.

### yulu-ai-workshop
6-session AI workshop series for PMs and designers at Yulu. Covers LLMs, agents, MCP, and AI-augmented product workflows. Includes a course hub website (Astro + Starlight) with interactive React components and hands-on exercises.

- **Repo:** https://github.com/kritisharma2708/yulu-ai-workshop
- **Owner:** @kritisharma2708 (with @akshay)
- **Tech:** Astro, Starlight, React, TypeScript, Vercel
- **Status:** Active
- **Ownership:** Official Yulu (internal training)

---

## Experiments & Prototypes

Workshop exercises, demos, and exploratory builds.

### yulu-landing-exercise
Single-page landing page concept for yulu.bike. Built as a Workshop 3 hands-on exercise — vanilla HTML/CSS/JS, no dependencies.

- **Lives in:** `yulu-ai-workshop/yulu-landing-exercise/` (no separate repo)
- **Owner:** @kritisharma2708
- **Tech:** HTML, CSS, JavaScript
- **Status:** Workshop artifact
- **Ownership:** Personal experiment

### yulu-rag-exercise
Rider support chatbot exercise. RAG over an internal Yulu knowledge base (parking, pricing, refunds, safety, hours).

- **Lives in:** `yulu-ai-workshop/yulu-rag-exercise/` (no separate repo)
- **Owner:** @kritisharma2708
- **Tech:** RAG, LLM, Yulu KB
- **Status:** Workshop artifact
- **Ownership:** Personal experiment

---

## Add Your Project

If you've built something Yulu-related — a tool, prototype, dashboard, exercise, anything — add it here so the rest of the team can find it.

**Two ways to contribute:**
1. **Easy:** [Open an issue using the "Add a project" template](../../issues/new?template=add-project.yml) — fill in the form and we'll add the entry for you.
2. **Direct:** Fork this repo, add an entry to the right section above, and open a PR. See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## About this hub

- Maintained by Kriti Sharma (@kritisharma2708) with support from Akshay (HoP).
- Hosted on a personal GitHub account for now; will transfer to an official Yulu org if/when one is set up.
- Open to all Yulu PMs, designers, and engineers. External collaborators welcome via PR.
