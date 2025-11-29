---
id: 0004
title: Show and explain constitution
stage: general
date: 2025-11-29
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: NAVEED261
command: Show me the generated constitution file and explain what it contains.
labels: ["constitution", "explanation"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
- .specify/memory/constitution.md
- history/prompts/general/0004-show-and-explain-constitution.general.prompt.md
tests:

---

## Prompt

Show me the generated constitution file and explain what it contains.

## Response snapshot

The constitution file `.specify/memory/constitution.md` contains the following:

```markdown
# Project Constitution: Research paper on AI-native software development

## Core Principles:
- Accuracy through primary source verification
- Clarity for academic audience (computer science background)
- Reproducibility (all claims cited and traceable)
- Rigor (peer-reviewed sources preferred)

## Key Standards:
- All factual claims must be traceable to sources
- Citation format: APA style
- Source types: minimum 50% peer-reviewed articles
- Plagiarism check: 0% tolerance before submission
- Writing clarity: Flesch-Kincaid grade 10-12

## Constraints:
- Word count: 5,000-7,000 words
- Minimum 15 sources
- Format: PDF with embedded citations

## Success Criteria:
- All claims verified against sources
- Zero plagiarism detected
- Passes fact-checking review
```

This constitution outlines the fundamental guidelines for the "Research paper on AI-native software development" project. It covers:

*   **Core Principles:** The foundational values guiding the research, such as accuracy, clarity for a specific audience, reproducibility, and rigor.
*   **Key Standards:** Specific rules for content and presentation, including source traceability, citation style, source types, plagiarism checks, and writing clarity.
*   **Constraints:** Defines the practical limitations and requirements for the paper, such as word count, minimum number of sources, and output format.
*   **Success Criteria:** The measurable conditions that must be met for the project to be considered successful, focusing on verification of claims, plagiarism, and fact-checking.

In essence, this document serves as a blueprint to ensure the quality, integrity, and academic adherence of the research paper.


## Outcome

- ✅ Impact: User provided with the constitution file content and a clear explanation.
- 🧪 Tests: N/A
- 📁 Files: .specify/memory/constitution.md read, new PHR created.
- 🔁 Next prompts: User can now proceed with further project development.
- 🧠 Reflection: Successfully addressed the user's request to display and explain the constitution, followed by PHR creation.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): PASS
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): null
