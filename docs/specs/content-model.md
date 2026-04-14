# Content Model Specification

## Core entities

### Lesson

- id
- title
- summary
- skill
- level
- goal tags
- topic tags
- prerequisites
- estimated time
- vocabulary list
- grammar or pattern focus
- exercises
- answer key or rubric
- related references
- related flashcard set
- media references

### Exercise task

- embedded in a lesson or evaluation file for the MVP
- exercise type
- prompt
- expected answer or evaluation method
- hints
- difficulty

### Flashcard deck

- id
- title
- level
- topic
- source lesson ids
- item list
- export format notes

### Reference entry

- id
- category
- title
- explanation
- examples
- linked lessons

### Study plan

- id
- audience
- duration
- weekly cadence
- required modules
- milestone checks

## Module definitions

### Listening

- audio-first exposure
- transcript support
- comprehension questions
- repeat and shadow tasks

### Reading

- graded texts
- glossed vocabulary
- comprehension checks
- domain-specific reading passages over time

### Writing

- sentence construction
- short responses
- guided composition
- optional character-writing support

### Speaking

- imitation and repetition
- prompt response tasks
- role-play scripts
- self-recording and feedback workflows

### Flashcards

- cross-cutting review support for vocabulary and sentence patterns

### Evaluation

- placement checks
- lesson checks
- module exit tasks
- milestone reviews

## Metadata rules

- all publishable items must declare level, estimated time, and tags
- lessons and other skill-specific pages must declare a primary skill
- all media-linked lessons must declare transcript availability
- all imported content must declare source and license metadata

## Content design rules

1. Prefer short, reusable units.
2. Keep English explanations concise and explicit.
3. Avoid hiding essential meaning in audio-only or image-only formats.
4. Use technical Chinese only after the learner has a core general-language base.
5. Keep every lesson connected to at least one review or assessment mechanism.
