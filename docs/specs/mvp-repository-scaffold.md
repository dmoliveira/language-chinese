# MVP Repository Scaffold Specification

## Objective

Define the first concrete repository scaffold so implementation can start with consistent folder ownership and predictable file placement.

## Top-level structure

```text
docs/
content/
scripts/
site/
```

## Folder responsibilities

### `docs/`

- planning documents
- specifications
- curriculum-level guidance

### `content/`

- source-of-truth learning content
- reusable metadata-driven lesson and support files
- manifests for media and third-party sources

### `scripts/`

- content validation helpers
- format/export helpers
- lightweight build helpers if needed later

### `site/`

- public GitHub Pages scaffold
- static HTML pages
- CSS and JavaScript assets
- generated or copied content artifacts later if the project adds a build step

## MVP content scaffold

```text
content/
  lessons/
    listening/
    reading/
    writing/
    speaking/
    overlays/
  references/
  study-plans/
  decks/
  evaluation/
  media/
    manifests/
  templates/
```

## MVP site scaffold

```text
site/
  index.html
  start-here/
    index.html
  learn-by-skill/
    index.html
    listening/
    reading/
    writing/
    speaking/
  learn-by-goal/
    index.html
    general-chinese/
    tech-cs-ai-ml/
  study-plans/
    index.html
  flashcards/
    index.html
  references/
    index.html
  evaluation/
    index.html
  about-contribute/
    index.html
  assets/
    css/
    js/
    media/
```

## Authoring rules

1. `content/` is the content source of truth.
2. `site/` is the publishable presentation layer.
3. MVP should allow manual publishing even before automation exists.
4. If a page is content-driven, its canonical metadata should live in `content/`, not only in `site/`.
5. Third-party media metadata must live under `content/media/manifests/`.

## MVP artifact mapping

| Artifact | Source folder | Notes |
| --- | --- | --- |
| Listening lessons | `content/lessons/listening/` | one file per lesson |
| Reading lessons | `content/lessons/reading/` | one file per lesson |
| Writing lessons | `content/lessons/writing/` | one file per lesson |
| Speaking lessons | `content/lessons/speaking/` | one file per lesson |
| Technical overlays | `content/lessons/overlays/` | optional Level 1+ content |
| References | `content/references/` | reusable across lessons |
| Study plans | `content/study-plans/` | weekly guidance |
| Decks | `content/decks/` | flashcards and exports |
| Evaluation pages | `content/evaluation/` | quizzes and checklists |
| Templates | `content/templates/` | canonical authoring starting points |
| Media manifests | `content/media/manifests/` | attribution and license tracking |

## Exercise ownership rule for MVP

- lesson practice stays embedded in lesson files for the MVP
- standalone checks such as placement and milestone pages live in `content/evaluation/`
- do not create a separate `content/exercises/` folder in the MVP scaffold

## Naming conventions

- use lowercase kebab-case filenames
- keep filenames aligned with canonical slugs
- keep one item per file
- prefix lessons and other sequenced assets with stable IDs inside metadata, not filenames unless useful

## MVP implementation order

1. create scaffold folders
2. add template files
3. add foundation site pages
4. add first four starter lessons
5. add references, study plans, decks, and evaluation pages
6. connect site navigation to content pages

## Initial non-goals

- no complex generator pipeline required for first scaffold
- no CMS
- no backend persistence
