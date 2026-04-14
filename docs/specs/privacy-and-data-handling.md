# Privacy and Data Handling Specification

## Objective

Protect learners in a public educational project, especially when speaking, writing, and browser-based interactive features are introduced.

## Default privacy posture

1. Core reading and lesson access must work without account creation.
2. Default behavior should keep learner activity in the browser whenever practical.
3. Audio, text, or recordings must not leave the learner's device unless the page clearly says so.
4. Any optional upload, external API use, or third-party speech service must require explicit user action.
5. MVP pages should first-party host all core assets by default.

## Storage policy

- local progress may use browser storage for convenience
- local storage usage must be documented in the UI and docs
- no personal profile is required for the MVP
- no hidden background recording or uploads

## Audio and speaking policy

- microphone access must be user-initiated
- pages must explain whether analysis happens locally, in-browser, or through an external service
- recordings should not be retained by the project unless a later backend policy explicitly defines retention and consent

## Writing and text submission policy

- writing practice should default to local, client-side handling where practical
- if external AI or API services are introduced later, users must be warned that submitted text may leave the browser

## Telemetry and analytics policy

- no analytics by default in the MVP unless explicitly documented
- if analytics are later added, they should be privacy-minimizing and disclosed publicly

## Third-party network request policy

- third-party runtime requests are privacy-relevant by default
- any external script, font, media host, model host, or API must be documented before use
- core learning pages should not depend on third-party runtime requests in the MVP
- if an external request is optional, the user should trigger it knowingly

## Public disclosure requirements

Every interactive tool that handles learner input should disclose:

- what data is processed
- where it is processed
- whether it is stored
- whether any third party receives it
- what the learner should avoid submitting

## Sensitive data guidance

- learners should be told not to submit personal, confidential, or employer-sensitive information
- technical/workplace exercises should use fictional or sanitized examples
