# MVP Inventory Specification

## Objective

Define the exact first publishable scope so the project can move from planning into implementation in small, clear steps.

## Site foundation pages

- Home
- Start Here
- Learn by Skill index
- Learn by Goal index
- Study Plans index
- Flashcards index
- References index
- Evaluation index
- About / Contribute

## Starter curriculum pages

### Listening

- Listening 001: Greetings and Introductions

### Reading

- Reading 001: First Characters and High-Frequency Words

### Writing

- Writing 001: Build Simple Self-Introduction Sentences

### Speaking

- Speaking 001: Pronunciation, Tones, and Basic Self-Introduction

## Reference pages

- Pinyin and tone basics
- Pronunciation guide
- Core sentence pattern basics
- Starter vocabulary reference

## Study plans

- 2-week absolute beginner starter plan
- 8-week beginner foundation plan

## Flashcard sets

- Foundations deck: greetings and introductions
- Foundations deck: core starter vocabulary

## Evaluation pages

- entry self-check
- lesson quiz pattern page
- beginner milestone checklist

## Technical track starter pages

- Tech vocabulary overlay 001: software and AI learning basics
- curated references to free and paid external tools for technical learners

This technical-track starter is an optional **Level 1 overlay** and is not required to complete Level 0 foundations.

## Media and support assets

- transcript for every audio-bearing starter page
- source manifest file for every third-party asset batch
- answer key or rubric for every exercise page

## MVP completion rule

The MVP is ready when every item in this inventory exists in publishable form with metadata, accessibility support, and license/source notes where required.

## Relationship to future guidebook model

This MVP inventory reflects the current public skill/goal-first site. A future handbook expansion may introduce Parts, Stages, and Units as a higher-order curriculum structure, but that does not replace the validity of the current MVP inventory.

## Canonical source-of-truth mapping

| Artifact type | Authoring location | Publish pattern | Notes |
| --- | --- | --- | --- |
| Site foundation pages | `site/` | top-level site routes | mostly hand-authored static pages |
| Lessons | `content/lessons/` | `/learn-by-skill/<skill>/<slug>/` | content-driven pages with metadata |
| Lesson practice | embedded in lesson files | within lesson pages | answer keys or rubrics required |
| References | `content/references/` | `/references/<slug>/` | reusable canonical explanations |
| Study plans | `content/study-plans/` | `/study-plans/<slug>/` | time-based guided sequences |
| Flashcard sets | `content/decks/` | `/flashcards/<slug>/` | can also expose downloadable exports |
| Evaluation pages | `content/evaluation/` | `/evaluation/<slug>/` | self-checks, quizzes, milestone checklists |
| Media manifests | `content/media/manifests/` | not directly routed | source and license tracking |

## Canonical MVP IDs and slugs

| Item | ID | Slug |
| --- | --- | --- |
| Home | `page-home` | `/` |
| Start Here | `page-start-here` | `start-here` |
| Learn by Skill | `page-learn-by-skill` | `learn-by-skill` |
| Learn by Goal | `page-learn-by-goal` | `learn-by-goal` |
| Study Plans index | `page-study-plans` | `study-plans` |
| Flashcards index | `page-flashcards` | `flashcards` |
| References index | `page-references` | `references` |
| Evaluation index | `page-evaluation` | `evaluation` |
| About / Contribute | `page-about-contribute` | `about-contribute` |
| Learn by Skill: Listening | `page-learn-by-skill-listening` | `learn-by-skill/listening` |
| Learn by Skill: Reading | `page-learn-by-skill-reading` | `learn-by-skill/reading` |
| Learn by Skill: Writing | `page-learn-by-skill-writing` | `learn-by-skill/writing` |
| Learn by Skill: Speaking | `page-learn-by-skill-speaking` | `learn-by-skill/speaking` |
| Learn by Goal: General Chinese | `page-learn-by-goal-general` | `learn-by-goal/general-chinese` |
| Learn by Goal: Tech / CS / AI / ML | `page-learn-by-goal-tech` | `learn-by-goal/tech-cs-ai-ml` |
| Listening 001 | `listening-foundations-001` | `greetings-and-introductions` |
| Reading 001 | `reading-foundations-001` | `first-characters-and-high-frequency-words` |
| Writing 001 | `writing-foundations-001` | `build-simple-self-introduction-sentences` |
| Speaking 001 | `speaking-foundations-001` | `pronunciation-tones-and-basic-self-introduction` |
| Pinyin reference | `reference-foundations-001` | `pinyin-and-tone-basics` |
| Pronunciation guide | `reference-foundations-002` | `pronunciation-guide` |
| Sentence patterns | `reference-foundations-003` | `core-sentence-pattern-basics` |
| Starter vocabulary | `reference-foundations-004` | `starter-vocabulary-reference` |
| 2-week starter plan | `study-plan-foundations-001` | `two-week-absolute-beginner-starter` |
| 8-week foundation plan | `study-plan-foundations-002` | `eight-week-beginner-foundation` |
| Greetings deck | `deck-foundations-001` | `greetings-and-introductions` |
| Starter vocabulary deck | `deck-foundations-002` | `core-starter-vocabulary` |
| Entry self-check | `evaluation-foundations-001` | `entry-self-check` |
| Quiz pattern page | `evaluation-foundations-002` | `lesson-quiz-pattern` |
| Beginner milestone | `evaluation-foundations-003` | `beginner-milestone-checklist` |
| Tech overlay 001 | `tech-overlay-001` | `software-and-ai-learning-basics` |
