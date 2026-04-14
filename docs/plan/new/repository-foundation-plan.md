# Repository Foundation Plan

## Purpose

Create a public, accessible, professional learning repository and GitHub Pages site for English speakers learning Chinese, with a strong optional focus on technology, computer science, and AI/ML contexts.

This planning slice defines how to start safely before implementation, content production, or repository publication.

## Core product idea

- Teach Chinese across four core skills: listening, reading, writing, and speaking.
- Support self-study with flashcards, study plans, quizzes, answer keys, and writing/speaking feedback.
- Publish content as open educational material when licensing allows.
- Use GitHub Pages as the first delivery platform so content can remain simple, inspectable, and easy to contribute to.
- Keep the experience useful for general learners while offering a technical-language track for people entering software, data, and AI-related work.

## Product principles

1. Accessibility first.
2. Open by default.
3. Clear licensing and attribution.
4. Static-first architecture with progressive enhancement.
5. Human-readable content in Markdown first, scripts second.
6. Beginner-friendly without sacrificing professional quality.
7. Technical Chinese as an overlay, not a barrier.

## Strategic reasoning

### Why GitHub Pages first

- Low-cost and public by default.
- Good fit for Markdown, static references, lesson pages, and lightweight browser interactions.
- Supports JavaScript for quizzes, flashcards, progress helpers, and speaking/writing evaluation prototypes.
- Encourages transparent learning materials and open contributions.

### Why separate content from evaluation logic

- Lesson content should remain reusable and portable.
- Interactive logic can evolve independently without rewriting educational material.
- This reduces risk if the site later moves from pure static pages to a generated site.

### Why use a mixed sourcing strategy

- Some materials can be fully open and republished.
- Some materials are free to access but should only be linked.
- The repository needs a formal sourcing policy so public reuse is legally safe.

## Selected initial license model

- **Code:** MIT License.
- **Original educational content:** CC BY-SA 4.0.
- **Original datasets created by the project when appropriate:** CC BY 4.0 or CC0, depending on whether attribution is required.

This split keeps software easy to adopt while keeping public educational derivatives open.

## Safe sourcing policy summary

- Republish or remix only content with explicit open/public licenses.
- Keep per-asset attribution records.
- Link to official HSK and other non-open resources instead of mirroring them.
- Prefer building original lesson content on top of open references such as CC-CEDICT, OpenCC, selected Tatoeba subsets, and clearly licensed media.

## Initial execution phases

### Phase 0: foundation planning

- Define product scope.
- Define content model and site architecture.
- Define sourcing and accessibility policies.
- Define MVP and roadmap.

### Phase 1: publishable MVP

- Launch a simple GitHub Pages site.
- Publish beginner foundations.
- Ship one starter module for each core skill.
- Add flashcards and lightweight quizzes.
- Add transcripts, answer keys, and study plans.

### Phase 2: applied learner experience

- Add technical Chinese pathway.
- Add more graded reading and listening.
- Add writing rubrics and speaking practice prompts.
- Add browser-based AI-assisted feedback prototypes.

### Phase 3: mature open learning platform

- Expand references and lesson library.
- Improve search, navigation, and learner progress helpers.
- Support contributor workflows and content review.
- Add stronger offline/export options and optional mobile-friendly packaging.

## Decisions already made in this plan

- Public-first educational repository.
- Open-license-first content policy.
- GitHub Pages as initial platform.
- Multi-skill curriculum with modular structure.
- Tech/AI vocabulary as a layered track.
- Iterative delivery rather than building everything before launch.

## Out of scope for the first iteration

- Native mobile apps.
- Custom backend services.
- Formal certification claims.
- Full automated grading for pronunciation or freeform writing.
- Massive corpus ingestion without license review.

## Next iteration targets

1. Finalize naming, audience language, and public positioning.
2. Draft the first publishable lesson pages from the MVP inventory.
3. Refine the chosen GitHub Pages stack into concrete folder conventions and templates.
4. Draft contribution-facing content templates.
5. Draft sourcing manifests for reusable third-party materials.
