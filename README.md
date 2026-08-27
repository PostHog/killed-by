# killed-by

The PostHog graveyard — killedby.posthog.com. Inspired by killedbygoogle.com, restyled for PostHog.

A single static `index.html`, no build step. Deploy by serving the folder.

The proposal box at the bottom is a PostHog survey ([Which product should we kill next?](https://us.posthog.com/project/2/surveys/01a04414-9dbd-0000-48ee-488d3dacf81f)) rendered inline via `posthog.renderSurvey`. It's a **draft** — launch it in PostHog before the site goes live, or the box stays empty.

To bury another product, copy the `<article class="grave">` block in `index.html` and bump the tally.
