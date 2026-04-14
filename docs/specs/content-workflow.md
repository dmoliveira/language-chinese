# Content Workflow Specification

## Objective

Make the project implementation-ready by defining how lessons, sources, and contributions enter the repository safely and consistently.

## Workflow

1. propose a lesson or reference item
2. define source and license status
3. draft with the standard lesson template
4. review for language accuracy, accessibility, and licensing
5. publish only after metadata and attribution checks pass

## Minimum contributor rules

- contributors must only submit material they wrote or material they can legally reuse
- imported media or datasets must include source, license, and attribution notes
- unclear-license assets are rejected or converted to link-only references

## Canonical lesson template

- title
- id
- skill
- level
- estimated time
- objectives
- prerequisites
- vocabulary and patterns
- lesson content
- exercises
- answer key or rubric
- related flashcards
- transcript or media notes
- source and license notes

### Example lesson metadata

```yaml
id: listening-foundations-001
title: Greetings and Introductions
summary: Learn to recognize and respond to simple beginner greetings.
skill: listening
level: 0
status: draft
estimated_time: 15m
prerequisites: []
license: CC BY-SA 4.0
slug: greetings-and-introductions
tags: [foundations, greetings]
```

## Canonical source manifest example

- asset name
- asset type
- source URL
- author or publisher
- publisher when applicable
- license
- attribution text
- local file path or external link
- source class: A, B, or C
- reuse decision: republish, transform, link-only, or do-not-use

### Example source manifest item

```yaml
asset_name: example-sentence-audio-001
asset_type: audio
source_url: https://example.org/resource
author: Example Author
publisher: Example Project
license: CC BY-SA 4.0
attribution: "Example Author via Example Project, CC BY-SA 4.0"
source_class: A
reuse_decision: link-only
local_path: content/media/example-sentence-audio-001.mp3
used_in:
  - listening-foundations-001
notes: Replace with reviewed decision.
```

## Publish gate checklist

- metadata complete
- accessibility checks complete
- answer key or rubric present
- transcript present when audio exists
- source and license recorded

## Progressive enhancement rule

- core lesson reading and navigation should work without JavaScript
- JavaScript may enhance quizzes, flashcards, filtering, and optional feedback tools
