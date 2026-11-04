# Colorfigures

A static gallery of interactive illustrations. Each figure is one HTML file with its drawing code inlined, and nothing loaded from elsewhere. GitHub Pages serves the root of `main` at [too-old-to-code.github.io/colorfigures](https://too-old-to-code.github.io/colorfigures/).

## Figures

- [Hip impingement (FAI)](hip-impingement.html) — a left hip showing cam, pincer and mixed femoroacetabular impingement, flexion and internal rotation (the FADIR test), and a see-through view.
- [Jet engine](jet-engine.html) — a high-bypass turbofan with start, ignite, throttle, thrust reverse, shutdown, and a see-through view.
- [A heat pump service](heat-pump-service.html) — a playable statechart: from plot number to a logged service, and the two ways a Daikin warranty can slip.

## Add a figure

1. Drop the new HTML file in the repository root, next to `index.html`. Keep it self-contained: inline the script, and do not add external stylesheets, scripts, or images.
2. In `index.html`, copy an `<a class="card">` and set its `href` to the new filename as a relative path (for example `href="new-figure.html"`). Fill in the title and a one-line description.
3. Commit to `main`. Pages publishes the files as they are; `.nojekyll` stops Jekyll from processing them.
