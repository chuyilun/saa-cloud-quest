# Cloud Quest / 雲嶼計畫

Original AWS SAA-C03 study game with Traditional Chinese explanations and English retake scenarios.

Play at https://chuyilun.github.io/saa-cloud-quest/ using a modern browser, including Safari on iPhone.

## Features

- 48 introductory scenarios and 56 English diagnostic, service-comparison, multiple-response, and assessment scenarios.
- 32 additional original English priority-practice scenarios (136 questions total),
  organized into 8 topics with 8 two-requirement multiple-response exercises.
- Per-option explanations and AWS documentation links.
- Confidence checks, spaced review, and local progress backup/import.
- Separate held-out assessment sets with local exposure tracking.
- A searchable English story glossary: 150 cards across 12 connected Cloudhaven chapters.
  Each card separates a simple story scene, an AWS definition, and a confusion warning,
  with an optional Chinese terminology hint. Chapters include recall prompts and AWS references.

## Priority practice

The retake dashboard shows cumulative English practice separately from the latest
standalone diagnostic. Each domain displays unique questions answered, cumulative
correct attempts, latest-wrong questions, and spaced mastery. Coverage bars are
not ability scores. Confirmed daily, duel, multiple-response, priority, domain-focus,
and review attempts for non-assessment English questions count toward practice.
Diagnostic/held-out questions and introductory Chinese questions are excluded from
these practice totals. Existing records populate the dashboard without migration.
Taking daily practice does not complete the separate 12-question diagnostic.

Choose **重點考點練習** to practice four questions from one topic or a mixed set of six.
Topics cover identity/encryption, networking, storage, databases, events, compute,
hybrid migration, and operations/recovery/cost. Each option has a Traditional Chinese
explanation; multiple-response questions also require mapping components to requirements.
These questions participate in English daily practice, domain focus, concept search,
wrong-answer/due review, confidence tracking, and spaced repetition.
Existing local progress and v1 backups remain valid. Backups containing the new question
IDs must be imported into this updated version, not an older offline HTML copy.

Selection combines the official SAA-C03 scope with a systematic concept-only sample
of 99 pages from the 2,970-page user-provided PDF (page 21, then every 30 pages).
This is separate from the initial 59-page sample used for the introductory game.
The sample counts service mentions by page, not questions or exam frequencies.
No PDF questions, answers, or discussions are reproduced or published.
All added questions are newly authored scenarios, not translations of PDF questions.
Priority labels are study recommendations, not verified claims of exam frequency.
The new bank is allocated 10/8/8/6 across the four domains; it is not a calibrated mock exam.
Existing diagnostic and held-out banks remain unchanged and separate.

## Story glossary

Choose **英文故事詞典** in the navigation. Search English, acronyms, or Chinese,
or filter to one chapter. The story follows building Cloudhaven, opening a festival,
surviving a storm, and reviewing the bill. Analogy is not a service specification.
The glossary broadly follows the official SAA-C03 service/concept scope but is not
an exhaustive or permanent exam vocabulary list. Check current AWS documentation,
particularly for legacy and specialist services.

Reading the glossary does not modify progress, scores, or assessment exposure records.
It does not reveal the held-out assessment questions.

## Progress and privacy

This is a static website. Progress is stored in the browser's local storage, not on GitHub.
There is no login, automatic cross-device synchronization, or persistence of unfinished test answers.
Use the in-game study guide to export and import a JSON progress backup. Import replaces existing progress.
Opening this website does not automatically transfer progress from a local HTML file.
Private browsing or clearing browser data can remove progress; keep backups.

## Learning scope

These are original educational scenarios, not official AWS exam questions.
Practice accuracy does not predict AWS scaled scores or guarantee certification.
The short assessments do not replace full-length unseen practice, official exam guides, or hands-on work.
No source PDF, private keys, credentials, or personal study records are included.

## Hosting

GitHub Pages serves `index.html` from the root of the `main` branch.
Update that file and push to `main` to publish a new version.
