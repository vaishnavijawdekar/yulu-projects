# Yulu Projects

A shared index of all Yulu-related projects — production tools and pipelines built by PMs, designers, and engineers across the team.

This repo doesn't host the projects themselves. It's a directory that points to where each project lives, who built it, and what it does.

**Want to add your project?** See [CONTRIBUTING.md](./CONTRIBUTING.md) — open an issue using the "Add a project" template, or PR an entry directly into this README.

---

## Production / Live Tools

Projects that are deployed and in active use.

### yulu-intel
Automated competitive intelligence platform for the Indian micromobility market. Tracks competitors (Bounce, Rapido, Zypp), generates monthly analysis reports via GitHub Actions, and delivers insights to Slack.

- **Repo:** https://github.com/kritisharma-yulu/yulu-intel
- **Live:** https://competeiq-reports.onrender.com
- **Owner:** @kritisharma-yulu
- **Tech:** Python, Node.js, Supabase, GitHub Actions, Exa API, OpenAI
- **Status:** Live
- **Ownership:** Official Yulu

### yulu-intel-slack-bot
Slack Q&A bot for querying Yulu competitive intelligence data. Companion to yulu-intel — gives the team a conversational interface over the same dataset.

- **Repo:** https://github.com/kritisharma-yulu/yulu-intel-slack-bot
- **Owner:** @kritisharma-yulu
- **Tech:** Node.js, Slack Bolt, OpenAI, Supabase
- **Status:** Live
- **Ownership:** Official Yulu

### support-insights
Weekly pipeline that fetches inbound support emails from Gmail, categorizes them with AI (issue type, product area, severity, sentiment), detects trends and anomalies, and delivers an executive summary to Slack and email. Answers: *what are users struggling with this week?*

- **Repo:** https://github.com/kritisharma-yulu/support-insights
- **Owner:** @kritisharma-yulu
- **Tech:** Python, SQLite, Gmail API, OpenAI, Slack Bolt
- **Status:** Live
- **Ownership:** Official Yulu

### metrics-agent
Weekly pipeline that pulls product metrics from Gmail, stores them in SQLite, runs anomaly detection (z-score), generates AI-powered analyst summaries plus matplotlib trend charts, and posts to Slack and email.

- **Repo:** https://github.com/kritisharma-yulu/metrics-agent
- **Owner:** @kritisharma-yulu
- **Tech:** Python, SQLite, Gmail API, OpenAI, matplotlib, Slack Bolt
- **Status:** Live
- **Ownership:** Official Yulu

### yulu-metrics-dashboard
Self-contained interactive HTML dashboard that visualizes the metrics-agent dataset (Plotly.js charts, trend views, anomaly highlights). Auto-deployed on Render whenever metrics-agent pushes new data.

- **Repo:** https://github.com/kritisharma-yulu/yulu-metrics-dashboard
- **Owner:** @kritisharma-yulu
- **Tech:** Plotly.js, HTML, Render
- **Status:** Live
- **Ownership:** Official Yulu

---

## Add Your Project

If you've built something Yulu-related — a tool, dashboard, pipeline, anything — add it here so the rest of the team can find it.

**Two ways to contribute:**
1. **Easy:** [Open an issue using the "Add a project" template](../../issues/new?template=add-project.yml) — fill in the form and we'll add the entry for you.
2. **Direct:** Fork this repo, add an entry to the right section above, and open a PR. See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## About this hub

- Maintained by Kriti Sharma (@kritisharma-yulu) with support from Akshay (HoP).
- Hosted on the `kritisharma-yulu` GitHub account, the home for all Yulu-related repos.
- Open to all Yulu PMs, designers, and engineers. External collaborators welcome via PR.
