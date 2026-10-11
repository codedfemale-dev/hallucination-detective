# Hallucination Detective

**[Play the game](https://codedfemale-dev.github.io/hallucination-detective/)**

A free browser game by [Coded Female](https://codedfemale.com). Investigate five convincing AI summaries, compare them with fictional source records and distinguish supported claims, contradictions and claims the evidence does not establish.

The interface uses a charcoal investigation console, gold accents, a case queue and labelled source records. On wide screens the evidence archive stays beside the claims as you scroll. The original Coded Female fonts are retained, with system monospace for technical labels.

Meet B.I.T. (Brilliant In Theory), a confident moonbase bot whose reports need a human check. Cases include a droid satisfaction survey, a portal experiment, invented NPC dialogue, a cached launch approval and the haunted server hypothesis. Feedback celebrates each solved incident, and the final score awards a playful title.

Cases cover survey denominators, percentages versus percentage points, invented quotations, outdated approvals and correlation versus causation. The final case contains no flawed claims. Classify three claims and select a careful summary in each case. First answers count towards 20 judgements, with optional clues, detailed explanations, replay and downloadable notes.

## Run locally

Serve this folder with any static web server, for example `python3 -m http.server 8767`, and open `http://localhost:8767/`.

## Checks

Run `node tests.cjs`. It checks all 405 verdict and summary combinations, source references and the clean case. There is no build step.

## Privacy and learning limits

All organisations, people and evidence records are fictional. This game uses scripted examples, not a live AI model or a fact-checking service. Answers are held in memory for the current page only. No analytics, external fonts, API keys or account is required. GitHub Pages hosting has its own platform policies.

Open Sans and Playfair Display are bundled with their font licence files in `assets/`.
