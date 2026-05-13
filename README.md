# Lewis Fausett — Personal Portfolio Site

A personal portfolio and project directory. Built with plain HTML/CSS, no frameworks, no build step. Hosted on GitHub Pages.

## Structure

```
/
├── index.html              # Home / directory
├── css/
│   └── style.css           # Full design system
├── pages/
│   ├── business.html       # Business & E-Commerce pillar
│   ├── research.html       # Physics, Math & ML pillar
│   └── thoughts.html       # Writing & Notes pillar
└── assets/
    └── img/                # Images and pixel art assets
```

## Deploying to GitHub Pages

1. Push this repository to GitHub (repo name: `yourusername.github.io` for a root site, or any name for a project site).
2. Go to **Settings → Pages**.
3. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`.
4. Your site will be live at `https://yourusername.github.io` (or `https://yourusername.github.io/repo-name` for a project site).

## Adding a Custom Domain

1. Buy a domain (e.g., `patrickadair.com`).
2. In your DNS settings, add a `CNAME` record pointing to `yourusername.github.io`.
3. In **Settings → Pages → Custom domain**, enter your domain.
4. Check **Enforce HTTPS**.

## Updating Content

All content is in the HTML files. Each `[WIP]` placeholder is a clear marker for where to add content. No build step required — edit the file, commit, push, and the site updates within ~30 seconds.

## Design System

- **Fonts:** Press Start 2P (headings), VT323 (mono/stats), Inter (body)
- **Palette:** Dark background (`#0f0f1a`), gold accent (`#f0c040`), blue accent (`#6ab0f5`), green accent (`#5dbd7a`)
- **Aesthetic:** Pixel art / loose RPG — subtle scanlines, pixel borders, RPG stat bars
