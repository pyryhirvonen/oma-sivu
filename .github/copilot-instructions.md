# Copilot Instructions

## Project goal

This repository contains a single-page Finnish Independence Day invitation. The page presents the event date (6.12.), time (16.00), location in Vesilahti, dress code, invitation message, and RSVP contact placeholders.

## Implementation boundaries

- Keep the page self-contained in the root `index.html`.
- Use semantic HTML and responsive CSS in the same file's `<style>` block.
- Use only system fonts; do not add external font, framework, or build-tool dependencies.
- Keep the visual direction clean, modern, elegant, and slightly formal with a blue-and-white palette and restrained decorative elements.
- Keep `[SÄHKÖPOSTI]` and `[PUHELIN]` as easy-to-replace RSVP placeholders until real contact details are supplied.
- JavaScript is optional and should only be added if a concrete interaction requires it.

## Validation

There are no project-specific build, test, or lint commands. Validate changes by opening `index.html` in a browser and checking both desktop and narrow mobile layouts, then reviewing the Git diff.
