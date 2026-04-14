# Information Architecture Specification

## Public site structure

- Home
- Start Here
- Learn by Skill
  - Listening
  - Reading
  - Writing
  - Speaking
- Learn by Goal
  - General Chinese
  - Tech / CS / AI / ML Chinese
- Study Plans
- Flashcards
- References
- Evaluation
- About / Contribute

## Repository structure

- `docs/plan/`
  - planning and staged delivery notes
- `docs/specs/`
  - product, content, accessibility, roadmap, sourcing specifications
- `docs/curriculum/`
  - levels, modules, study plans, references
- `content/`
  - lessons, references, study plans, decks, evaluation content, media manifests, templates
- `scripts/`
  - content transforms, validation helpers, data generation
- `site/`
  - MVP static site pages, styles, and JavaScript assets

## Navigation principles

1. Users can start by skill or by goal.
2. Every lesson belongs to exactly one main skill module.
3. Technical content is tagged as an overlay, not isolated from the main path.
4. References are stable and reusable across lessons.
5. Evaluation pages point back to prerequisite lessons and related study plans.

## Page design expectations

Each lesson page should include:

- title
- learner level
- estimated time
- prerequisites
- learning objectives
- vocabulary/patterns
- examples
- practice tasks
- answer key or rubric
- related flashcards
- transcript or audio notes when applicable

## URL and content conventions

- lowercase, hyphenated slugs
- stable IDs for lessons and decks
- consistent level tags
- machine-readable metadata at page or data level

## Search and discovery expectations

- learners should be able to browse by level, skill, and topic
- technical vocabulary should be filterable by domain
- every lesson should expose related references and next steps
