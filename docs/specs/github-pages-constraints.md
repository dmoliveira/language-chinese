# GitHub Pages Constraints Specification

## Objective

Keep the first public release compatible with static hosting while leaving room for richer interactive features later.

## Core constraints

- no required custom backend for MVP
- assets should be version-controlled or fetched from approved sources
- interactive features should work in-browser with JavaScript
- user progress should default to local/browser storage unless a later backend is introduced

## Recommended implementation posture

- Markdown or generated static pages for core content
- small JavaScript modules for quizzes, flashcards, and filtering
- browser-first media playback with transcript fallbacks
- optional external or downloadable models only when clearly documented
- core navigation and lesson reading should remain usable without JavaScript

## Chosen MVP stack

- GitHub Pages hosting
- repository-authored Markdown for lesson and reference content
- static HTML, CSS, and vanilla JavaScript for the first interactive features
- no required backend for the MVP
- first-party hosted core assets wherever practical

## Initial folder expectation

- `docs/` for planning and specifications
- `content/` for lessons, exercises, decks, glossary, and media manifests
- `scripts/` for validation or content helper scripts
- `site/` for static page assets and JavaScript when the first site scaffold is created

## Evaluation implications

- objective quizzes are easy to support statically
- writing feedback should begin with checklists and rubrics
- speaking feedback should begin with lightweight browser or open-source tooling and clear limitations

## Media implications

- keep media sizes manageable
- prefer transcripts and text alternatives
- host only media with clear licensing and practical bandwidth expectations
- document whether large media or models are stored in-repo, fetched at runtime, or linked externally

## Future-compatible directions

- static site generators
- client-side search
- progressive web app support
- optional external APIs behind explicit opt-in flows
