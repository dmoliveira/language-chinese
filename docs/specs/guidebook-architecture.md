# Guidebook Architecture Specification

## Objective

Turn the repository from a strong public MVP into a practical multi-year guidebook that an English-speaking learner can follow for 2 to 4 years.

## Product posture

The project should behave like a **handbook + workbook + reference library**.

- **Handbook** gives the primary learning order.
- **Workbook** gives guided practice and review.
- **Reference library** gives reusable explanations for grammar, vocabulary, pronunciation, and study strategy.

## Primary learner path

### Current MVP public navigation

The current public site remains:

1. Start Here
2. Learn by Skill
3. Learn by Goal
4. Study Plans
5. Flashcards
6. References
7. Evaluation

### Post-MVP handbook navigation target

As the guidebook matures, the main learner-facing route should evolve toward:

1. Start Here
2. Learn by Stage
3. References
4. Review & Assess
5. Study Plans

Skill pages and goal pages should remain available as secondary discovery views. This means the project is **not replacing the current IA immediately**; it is defining the next architectural direction beyond the MVP.

## Multi-year handbook structure

### Part I — Foundations

- sounds, pinyin, tones
- first greetings and introductions
- first high-frequency words and characters
- first sentence patterns

### Part II — Core Beginner

- daily life language
- time, routine, food, family, places, study, work
- short listening and reading passages
- short guided speaking and writing

### Part III — Everyday Expansion

- connected descriptions
- short explanations
- comparison, preference, plans, habits
- longer graded reading and listening

### Part IV — Independent Intermediate Use

- practical discussion
- summaries, opinions, clarifications
- broader reading and writing range
- more spontaneous speaking

### Part V — Applied Tracks

- Tech / CS / AI / ML Chinese
- future optional overlays for business, travel, or academic use

## Hierarchy

Use this stable hierarchy for content planning and publishing:

- **Part**
  - **Stage**
    - **Unit**
      - **Lesson**
      - **Reference**
      - **Deck**
      - **Checkpoint**

This hierarchy should be added as a first-class planning and content-model concept before it becomes the default public navigation model.

## Recommended sizing

- **Part:** 6 to 12 months
- **Stage:** 6 to 10 weeks
- **Unit:** 1 to 2 weeks
- **Lesson:** 15 to 45 minutes

## Rule of coherence

Every stage should be complete enough that a learner can stay in the project without needing to guess what to do next.

That means every stage should include:

- a clear stage overview
- a unit sequence
- lesson links
- deck links
- reference links
- review loop
- checkpoint or milestone

## Core path vs optional path

### Core path

- required for all learners
- general Chinese progression
- default route in navigation and study plans

### Optional paths

- technical overlay
- enrichment references
- extra graded input
- optional exports/downloads

## Navigation expectation

Every learner page should answer three questions clearly:

1. Where am I?
2. What should I do next?
3. What should I review if I feel lost?

## Content system expectation

Every lesson/unit/stage should support four learner needs:

- learn
- practice
- review
- check progress

## Practical guidebook principle

If a learner used only this repository and site for 2 to 4 years, they should still be able to see a coherent route from beginner foundations to practical independent use.
