# Lewis Fausett — Personal Site

Personal site and public notebook for Lewis Fausett. Plain HTML/CSS, no frameworks, no build step. Hosted on GitHub Pages.

Live at: https://aufbau1s.github.io/Fausett.github.io/

## Structure

```
/
├── index.html              # Home: positioning, Now, selected work, latest notes
├── 404.html
├── favicon.svg
├── css/
│   └── style.css           # Design system (Warm Academic: Inter + JetBrains Mono)
└── pages/
    ├── work.html           # Reach Digital, Tulya, consulting, PAD (2017–2026)
    ├── research.html       # Applied math, ML interpretability, 2020 publication
    ├── notes.html          # Published essays + pipeline of drafts
    ├── notes/              # Individual essays
    ├── reading.html        # Reading list
    ├── about.html          # Bio + timeline + contact
    └── projects/           # Project write-ups
```

## Publishing a note

Notes are sourced from Lewis's Obsidian vault. The curation list lives in the
student vault at `wiki/syntheses/Old Second Brain Public Writing Candidates - 2026-06-29.md`.
To publish: clean the source note (remove private details, internal links, and
local paths), convert it to an HTML page under `pages/notes/`, and add it to the
Published list in `pages/notes.html` and the Latest notes list in `index.html`.

## Updating content

Edit the HTML file, commit, push. GitHub Pages updates within ~30 seconds.
Contact email across the site: lewis@fausett.management.
