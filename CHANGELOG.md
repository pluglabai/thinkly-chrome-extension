# Changelog

## chrome-extension-beta-v4.2.0-beta.15

- Added Gemini auto-capture support for current user-query and model-response DOM structures.
- Kept Gemini auto-capture limited to the latest exchange to prevent full-thread backfills.
- Improved Claude auto-capture across user-message, copy/action button, and message body fallbacks.
- Clarified auto-capture status as local captures waiting for review before sync.

## chrome-extension-beta-v4.2.0-beta.14

- Reserved more scroll space so bottom captures remain visible while selection actions are open.
- Hardened Gemini capture to avoid broad DOM fallback and save only the latest role-bearing exchange.
- Added Claude-specific DOM extraction from user-message and message-action anchors.
- Blocked provider chrome, privacy, and help text before automatic capture saves.

## chrome-extension-beta-v4.2.0-beta.13

- Sync now sends only reviewed captures, keeping unreviewed auto-captures local until approved.
- Fixed ChatGPT, Claude, and Gemini platform attribution across sync payloads and popup stats.
- Added floating contextual help for popup actions.
- Replaced the onboarding Capture V2 label with the Thinkly logo and animated AI example cards.

## chrome-extension-beta-v4.2.0-beta.12

- Added a two-row selection action bar so Review, Export, and Delete stay readable in pinned mode.
- Added search result counts to the Feed when a query is active.
- Added a dismissible free AI organization CTA that stays hidden for 24 hours.

## chrome-extension-beta-v4.2.0-beta.11

- Adds Feed review filters for All, To review, and Reviewed captures.
- Adds checkbox-style selection actions for Mark reviewed, Review again, Delete, and Export.
- Fixes Local/Synced popup stats by treating sent and synced captures as synced.
- Broadens Feed search across source metadata, model, platform, URLs, page title, and thread URL.

## chrome-extension-beta-v4.2.0-beta.4

- Keeps the popup header actions on one row: Local, Pin, Sign in, and Export now share consistent sizing.
- Replaces the header Settings text button with a compact Export icon action.
- Hides the Capture v2 setup banner after Capture v2 is enabled.
- Defers auto-capture while AI responses are still generating, then updates the same turn after the answer stabilizes.
