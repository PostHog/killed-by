# killed-by

The PostHog graveyard — killedby.posthog.com. Inspired by killedbygoogle.com, restyled for PostHog.

A single static `index.html`, no build step. Deploy by serving the folder.

The proposal box at the bottom is a PostHog survey ([Which product should we kill next?](https://us.posthog.com/project/2/surveys/01a04414-9dbd-0000-48ee-488d3dacf81f)) rendered inline via `posthog.renderSurvey`. It's launched, and it's `api` type, so it only appears where `renderSurvey` is called — it never auto-pops on other pages using this project's token.

To bury another product, copy the `<article class="grave">` block in `index.html` and bump the tally.
