# jacobswift-me

A small collection of self-contained browser tools, served as a static site on GitHub Pages.

## Structure

Each tool lives in its own folder as `index.html`, so it gets a clean URL
(e.g. `/housing-cost-calculator/`). The root `index.html` is the landing page
that links to them all.

```
.
├── index.html                        landing page
├── .nojekyll                         serve files as-is (no Jekyll processing)
├── narrowbody-layout-playground/     N01 · Aviation
├── region-divider-usa/               N02 · Mapping
├── housing-cost-calculator/          N03 · Finance
├── key-driver-diagram/               N04 · Healthcare QI
├── expense-splitter/                 N05 · Everyday
└── safe-steps/                       N06 · Healthcare
```

## Adding a new tool

1. Make a new lowercase-hyphenated folder (e.g. `my-new-tool/`).
2. Drop the tool's HTML inside it, renamed to `index.html`.
3. Add a matching card to the grid in the root `index.html`.

## Editing the landing page

The landing page has a hidden edit mode (Edit button, bottom-right). It lets you
change wording and formatting in the browser, then downloads an updated
`index.html`. Replace the root file with that download to publish changes.
Note: the passcode is client-side only and visible in the page source — it deters
casual edits, it is not real security.
