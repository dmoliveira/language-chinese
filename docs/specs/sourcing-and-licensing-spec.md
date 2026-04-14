# Sourcing and Licensing Specification

## Objective

Ensure the repository can be public and open-source/open-education friendly without licensing confusion.

## Content classes

### Class A: safe to republish or remix

- Project-authored content.
- Public domain content.
- CC0 content.
- Clearly licensed CC BY or CC BY-SA content.
- Open-source code and tooling under approved software licenses.

### Class B: usable by link/reference only

- Official HSK and other exam materials without explicit open reuse rights.
- Free apps and services without redistribution permission.
- Browser-native speech services and proprietary voices.
- Paid courses, books, and apps used only as references.

### Class C: avoid for repository redistribution

- Unclear license materials.
- Non-commercial-only content unless the project intentionally accepts the restriction.
- User-uploaded decks or media with no explicit reuse rights.

## Selected project licensing model

- **Code:** MIT.
- **Original educational content:** CC BY-SA 4.0.
- **Original downloadable data where broad reuse is preferred:** CC BY 4.0 or CC0.

## Inbound contribution rule

- By contributing code, content, media, or data, contributors agree that their submission may be distributed under the repository's selected outbound license model for that content type.
- Contributors must only submit material they own or can legally contribute under compatible terms.

## Output license matrix

- Site code and scripts remain under the code license.
- Original lesson pages and authored educational text remain under the content license.
- Downloadable datasets or deck exports must declare their own license explicitly.
- Mixed outputs that include share-alike source material must remain under a compatible share-alike license.
- Pages that only link to third-party resources do not inherit the target resource license, but copied excerpts still require compliance.

## Approved foundational sources for early planning

- **CC-CEDICT** for dictionary/reference support.
- **OpenCC** for simplified/traditional conversion support.
- **Tatoeba subsets** only when license metadata permits reuse.
- **Wiktionary / Wikisource excerpts** when attribution and share-alike obligations are handled.
- **LibriVox** and selected **Wikimedia Commons** media with per-item review.

## Reuse rules

1. Every third-party asset must have source, license, and attribution recorded.
2. Every imported dataset or media batch must include a manifest.
3. If a source has share-alike obligations, derived content must remain compatible.
4. If a source lacks explicit redistribution rights, link to it instead of copying it.

## Third-party resource categories

### Open or open-friendly

- Dictionary/reference data.
- Open-source text processing or speech tooling.
- Public-domain audio.
- Clearly licensed example sentences.

### Free but not open

- Commercial language apps.
- Official exam portals.
- Browser speech engines.
- Paid books, courses, and tutoring services.

## Repository safeguards

- Add a license note to every dataset folder.
- Keep attribution files version-controlled.
- Prefer scripts that fetch or transform allowed resources over storing questionable assets.
- Keep original authored content separate from imported materials.
- Require contributors to assert they have rights to submit any text, media, or data they add.

## Professional standard

The project must be legally conservative: when reuse rights are unclear, the default behavior is to link, describe, or reference rather than republish.
