# our words

A beautiful, single-page word cloud visualizer built with vanilla HTML, CSS, and JavaScript. Displays a personalized word cloud from hardcoded word frequency data, rendered on an HTML5 canvas with a soft pastel aesthetic.

## Features

- **Word cloud rendering** — words are sized by frequency and placed using a spiral layout algorithm to avoid overlaps
- **Multiple colour palettes** — choose from pastel, rose, sky, mint, or sunset themes
- **Custom title** — rename the cloud to anything you like
- **Stats display** — shows total words, unique word count, and the most-used word
- **Top word pills** — highlights the 12 most-used words with colour-coded badges
- **Save as image** — download the rendered cloud as a PNG
- **Floating hearts animation** — a small celebratory effect on each regeneration
- **Responsive design** — adapts to mobile screens

## Usage

Open `index.html` in any modern browser — no build step or server required.

Use the controls panel to:
1. Set a custom **title** for the cloud
2. Pick a **colour palette**
3. Click **regenerate** to redraw with a fresh layout

Click **save as image** to download the canvas as `our-words.png`.

## Tech Stack

- HTML5 / CSS3 (custom properties, flexbox, canvas)
- Vanilla JavaScript (no dependencies)
- Google Fonts — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) & [Quicksand](https://fonts.google.com/specimen/Quicksand)

## Data

Word frequency data is hardcoded in `ALL_WORDS` inside the script. To use your own data, replace that array with `[["word", count], ...]` pairs sorted by count descending, and update `TOTAL_WORDS` and `UNIQUE_WORDS` accordingly.
