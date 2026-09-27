# Menas Antachew — Portfolio

A plain HTML/CSS/JavaScript portfolio. No framework or build step is required.

## How the site is organised

- `index.html` — all page copy, sections and links.
- `theme.css` — the quickest place to change colours and fonts.
- `styles.css` — layout, spacing, responsive behaviour and component styling.
- `script.js` — small scroll/reveal interactions.
- `assets-headshot.jpg` — headshot used near the final contact section.
- `Menas-Antachew-Resume.pdf` — downloadable résumé.

## Your safe editing workflow

1. Create a branch from `main`.
2. Make one logical change.
3. Preview and review it.
4. Commit the change with a clear message.
5. Merge the branch into `main` when you are happy.
6. Once hosting is connected, changes to `main` can deploy automatically.

## Common edits

### Change page copy
Open `index.html`, find the text you want to change, edit it and commit.

### Change colours
Open `theme.css`. The main controls are:
- `--ink` — primary dark colour
- `--paper` — page background
- `--accent` — lime highlight
- `--muted` — secondary text
- `--line` — borders/dividers

### Change layout
Edit `styles.css`. This is where section spacing, grids, type sizing and mobile rules live.

### Preview locally
You can open `index.html` directly in a browser. A local server such as VS Code Live Server is more convenient when making repeated edits.

## V1

The `portfolio-v1` branch is the first reviewable version. It includes:
- editorial, mostly photo-free hero
- selected product work
- Underlap / Building with AI section
- product principles
- career story
- football coaching section
- headshot as the final personal sign-off

The headshot and résumé are binary files and may need to be uploaded through GitHub's **Add file → Upload files** flow before V1 is complete.
