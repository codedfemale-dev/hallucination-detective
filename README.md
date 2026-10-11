# Hallucination Detective

**[Play the game](https://codedfemale-dev.github.io/hallucination-detective/)**

A free browser game by [Coded Female](https://codedfemale.com). Investigate five convincing AI summaries, compare them with fictional source records and distinguish supported claims, contradictions and claims the evidence does not establish.

Cases cover survey denominators, percentages versus percentage points, invented quotations, outdated approvals and correlation versus causation. The final case contains no flawed claims. Classify three claims and select a careful summary in each case. First answers count towards 20 judgements, with optional clues, detailed explanations, replay and downloadable notes.

## Run locally

Serve this folder with any static web server, for example `python3 -m http.server 8767`, and open `http://localhost:8767/`.

## Checks

Run `node tests.cjs`. It checks all 405 verdict and summary combinations, source references and the clean case. There is no build step.

## Privacy and learning limits

All organisations, people and evidence records are fictional. This game uses scripted examples, not a live AI model or a fact-checking service. Answers are held in memory for the current page only. No analytics, external fonts, API keys or account is required. GitHub Pages hosting has its own platform policies.

Open Sans and Playfair Display are bundled with their font licence files in `assets/`.
