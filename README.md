# Claude Certified Architect Study Guide

This repository contains a lightweight, self-contained study companion for the Claude Certified Architect certification with tips in Brazilian Portuguese.

## What is included

- A single-page web app in [index.html](index.html) that provides:
  - exam mental-model guidance
  - a compact cheatsheet
  - a topic-by-topic summary
  - a flash cards mode for concept review: a curated deck of concept cards based on the claudecertificationguide.com study guide (not the raw quiz questions) — the front asks a conceptual question, the back reveals the key idea plus a didactic explanation and a link to the relevant guide page; study by one, several, or all themes, mark cards as "já sei"/"revisar" and re-study just the ones flagged for review
  - an interactive quiz simulator
- [questions_raw.json](questions_raw.json): raw question dataset
- [questions_final.json](questions_final.json): finalized data used for the study experience

## Project purpose

The app is designed to help learners:

- understand the dominant patterns behind the certification questions
- review the most important Claude Code and agentic architecture concepts
- practice with a simulated quiz and review explanations for incorrect answers

## How to use it

Because this is a static site, there is no build step or dependency installation required.

### Option 1: Open directly in a browser

- Open [index.html](index.html) with your browser.

## Repository structure

```text
.
├── index.html
├── questions_raw.json
└── questions_final.json
```

## License

No explicit license file is included in this repository.
