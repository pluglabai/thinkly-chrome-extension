# Thinkly Chrome Extension Beta Preview

This branch is the public beta-preview surface for the Thinkly Chrome extension.

It is for:

- upcoming v2 foundation notes
- UI and onboarding preview screenshots
- beta release notes
- known gaps before a public installable beta

It is not for:

- stable installation
- Chrome Web Store upload assets
- load-unpacked developer builds

## Current status

- Preview-only beta branch
- Installable beta ZIP can be published only after generating it from the private monorepo with a separate beta extension key and a separate beta Google OAuth client
- Stable install instructions remain on the `main` branch

## Download beta ZIP

- [Download `thinkly-beta-v4.2.0-beta.5.zip`](https://github.com/pluglabai/thinkly-chrome-extension/raw/beta-preview/thinkly-beta-v4.2.0-beta.5.zip)
- Beta release notes: https://github.com/pluglabai/thinkly-chrome-extension/releases/tag/chrome-extension-beta-v4.2.0-beta.5

## What is changing in beta

The current beta focus is extension v2 foundation work:

- GTM-focused onboarding and popup copy
- category UI hidden from popup and Quick Save surfaces
- popup header alignment and compact Pin / Export actions
- Capture v2 setup banner persistence fix
- safer auto-capture timing for streaming AI answers
- popup shell refresh
- onboarding and settings foundation
- inline capture UI refresh
- status pill groundwork
- Gemini validation support
- main-world page bridge groundwork

## Stable branch

For the current stable public distribution surface, use:

- branch: `main`
- release tag: `chrome-extension-v4.1.0`

## Beta prerelease

- prerelease tag: `chrome-extension-beta-v4.2.0-beta.5`

This prerelease may contain preview docs and screenshots before an installable beta ZIP is attached.

## Preview screenshots

### Popup shell

![Thinkly Beta popup shell](assets/popup-shell.png)

### Onboarding

![Thinkly Beta onboarding](assets/onboarding.png)

### Inline status pill

![Thinkly Beta status pill](assets/status-pill.png)

## Feedback

Until installable beta builds are published, feedback should be based on:

- release notes
- screenshots
- product walkthroughs
- direct coordination with the Thinkly team
