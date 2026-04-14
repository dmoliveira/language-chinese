# Content Templates and Metadata Specification

## Objective

Provide canonical metadata and structure for the first MVP content types so authors can create consistent files before any automation exists.

## Shared metadata rules

All publishable content files should declare:

- `id`
- `title`
- `summary`
- `level`
- `tags`
- `status`
- `estimated_time`
- `slug`
- `license`

Use these status values:

- `draft`
- `review`
- `published`

## Lesson template

### Required metadata

```yaml
id: listening-foundations-001
title: Greetings and Introductions
summary: Learn to recognize and respond to simple beginner greetings.
skill: listening
level: 0
tags: [foundations, greetings, introductions]
goal_tags: [general-chinese]
topic_tags: [greetings, self-introduction]
status: draft
estimated_time: 15m
prerequisites: []
related_references:
  - reference-foundations-001
related_decks:
  - deck-foundations-001
transcript_available: true
source_notes: original
license: CC BY-SA 4.0
slug: greetings-and-introductions
```

### Required sections

1. Objectives
2. Prerequisites
3. Vocabulary and patterns
4. Lesson content
5. Practice
6. Answer key or rubric
7. Related flashcards and references
8. Transcript or media notes
9. Source and license notes

## Reference template

### Required metadata

```yaml
id: reference-foundations-001
title: Pinyin and Tone Basics
summary: A beginner-friendly introduction to pinyin initials, finals, and tones.
content_type: reference
category: pronunciation
level: 0
tags: [foundations, pronunciation, pinyin]
status: draft
estimated_time: 10m
linked_lessons:
  - speaking-foundations-001
license: CC BY-SA 4.0
slug: pinyin-and-tone-basics
```

### Required sections

1. What this reference is for
2. Key concepts
3. Examples
4. Common mistakes
5. Related lessons
6. Source and license notes

## Study plan template

### Required metadata

```yaml
id: study-plan-foundations-001
title: Two-Week Absolute Beginner Starter
summary: A short daily study path for learners starting from zero.
content_type: study-plan
level: 0
tags: [study-plan, beginner, foundations]
status: draft
estimated_time: 2-weeks
audience: absolute-beginners
weekly_cadence: 6-days-per-week
license: CC BY-SA 4.0
slug: two-week-absolute-beginner-starter
```

### Required sections

1. Audience
2. Time commitment
3. Weekly plan
4. Lesson sequence
5. Review checkpoints
6. Completion criteria
7. Source and license notes

## Flashcard deck template

### Required metadata

```yaml
id: deck-foundations-001
title: Greetings and Introductions Deck
summary: Starter review cards for common greetings and self-introduction phrases.
content_type: deck
level: 0
tags: [flashcards, greetings, foundations]
status: draft
estimated_time: 10m
source_lesson_ids:
  - listening-foundations-001
  - writing-foundations-001
export_formats: [json, csv]
license: CC BY-SA 4.0
slug: greetings-and-introductions
```

### Required sections

1. Deck purpose
2. Included lessons
3. Card design notes
4. Export notes
5. Source and license notes

## Evaluation template

### Required metadata

```yaml
id: evaluation-foundations-001
title: Entry Self-Check
summary: A lightweight self-check to help learners choose a starting point.
content_type: evaluation
level: 0
tags: [evaluation, placement, foundations]
status: draft
estimated_time: 10m
evaluation_type: self-check
related_lessons: []
license: CC BY-SA 4.0
slug: entry-self-check
```

### Required sections

1. Purpose
2. Instructions
3. Questions or tasks
4. Scoring or interpretation guidance
5. Recommended next steps
6. Source and license notes

## Source manifest template

```yaml
asset_name: example-audio-001
asset_type: audio
source_url: https://example.org/resource
author: Example Author
publisher: Example Publisher
license: CC BY-SA 4.0
attribution: Example Author via Example Publisher, CC BY-SA 4.0
source_class: A
reuse_decision: link-only
local_path: content/media/example-audio-001.mp3
used_in:
  - listening-foundations-001
notes: Approved for MVP reuse.
```

## Format guidance

- store content as Markdown with front matter or clearly separated metadata blocks
- keep examples and answers in the same file for MVP unless reuse requires separation
- prefer readable authoring over premature normalization
