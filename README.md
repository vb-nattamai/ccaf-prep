# CCA-F Exam Simulator

Practice tool for the Claude Certified Architect, Foundations (CCA-F) exam.

Independent practice tool. Not affiliated with or endorsed by Anthropic. All questions are original.

## Features

- **Exam mode**: 4 of 6 scenarios drawn at random, 15 questions each, 60 total, 120-minute timer, flagging, scaled score against the 720 pass line.
- **Learn mode**: instant feedback with why the answer is right, why the distractors fail, and the exam pattern behind it.
- **Patterns**: all decision rules grouped by exam domain.
- **Readiness tracking** per domain, weighted by the official blueprint.

Progress is stored in the browser only (localStorage). No backend, no tracking.

## Run locally

Open `index.html` in a browser. It is one self-contained file.

## Publish on GitHub Pages

1. Create a repository and add `index.html` at the root.
2. Go to **Settings > Pages**.
3. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. The site goes live at `https://<user>.github.io/<repo>/`.

## Content

90 scenario-based questions across six scenarios and five domains:

| Domain | Weight |
|---|---|
| D1 Agentic Architecture & Orchestration | 27% |
| D2 Claude Code Configuration & Workflows | 20% |
| D3 Prompt Engineering & Structured Output | 20% |
| D4 Tool Design & MCP Integration | 18% |
| D5 Context Management & Reliability | 15% |
