---
id: 0003
title: Update project constitution
stage: constitution
date: 2025-11-29
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: NAVEED261
command: /sp.constitution
labels: ["constitution"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
- .specify/memory/constitution.md
- history/prompts/constitution/0003-update-project-constitution.constitution.prompt.md
tests:

---

## Prompt

/sp.constitution

Project: Research paper on AI-native software development

Core principles:
- Accuracy through primary source verification
- Clarity for academic audience (computer science background)
- Reproducibility (all claims cited and traceable)
- Rigor (peer-reviewed sources preferred)

Key standards:
- All factual claims must be traceable to sources
- Citation format: APA style
- Source types: minimum 50% peer-reviewed articles
- Plagiarism check: 0% tolerance before submission
- Writing clarity: Flesch-Kincaid grade 10-12

Constraints:
- Word count: 5,000-7,000 words
- Minimum 15 sources
- Format: PDF with embedded citations

Success criteria:
- All claims verified against sources
- Zero plagiarism detected
- Passes fact-checking review

## Response snapshot

The project constitution has been successfully updated according to your input.

## Outcome

- ✅ Impact: Project constitution updated.
- 🧪 Tests: N/A
- 📁 Files: .specify/memory/constitution.md updated.
- 🔁 Next prompts: User can now proceed with other project tasks.
- 🧠 Reflection: Successfully updated the constitution based on user input and created a PHR.

## Evaluation notes (flywheel)

- Failure modes observed: Initially tried to write without reading, leading to an error. Corrected by reading the (template) file first.
- Graders run and results (PASS/FAIL): PASS
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): null
