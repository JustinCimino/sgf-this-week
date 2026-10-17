# sgf-this-week

Publish SGF events in one place drawing from a variety of sources.

Live at https://sgfmoevents.com

## How it works

- `index.html` is the page. Its layout does not change week to week.
- `data/week.json` holds the events. A scheduled Claude task rewrites this one file every Thursday morning and pushes it here; GitHub Pages republishes automatically.
- Every event in `events` was confirmed on a curated local calendar or the venue's own site. Aggregator-only listings go in `unconfirmed`.

The source list, run instructions and page spec live in the SGF Events Claude project.
