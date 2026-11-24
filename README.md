# solnair-site

The Solnair Automation landing page, live at https://solnairautomation.com (hosted on Netlify).

## Files

- `index.html`: the whole page (layout, styles and the small script for the calculator, booking buttons and videos)
- `favicon.svg`: the green sun icon in the browser tab

## The lines you edit

Near the bottom of `index.html`, under `EDIT THESE TWO LINES`:

- `BOOKING_URL`: the booking page every "Book" button opens
- `LOOM_EMBED_URL`: the main demo video (leave empty and the demo section stays hidden)
- `LOOM_LIBRARY`: one slot per system for the demo library lower on the page (empty slots stay hidden)

Loom links must be the embed form: `https://www.loom.com/embed/VIDEO_ID`.

## Publishing

Netlify publishes this repo automatically once it is linked to the `solnair` project
(no build command, publish directory `/`). Every commit to `main` goes live.
