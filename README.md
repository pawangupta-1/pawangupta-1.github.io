# Pawan Gupta — personal site

A plain HTML/CSS site, no build tools required. Six pages, one shared stylesheet.

```
index.html          About / home
cv.html              CV
research.html        Research
projects.html        Projects (Apnapan, etc.)
writing.html         Poetry & essays
notes.html           Index of teaching/learning notes (any topic, work or not)
notes/template.html  Copy this to start a new note
styles.css           Shared design system
assets/              Put your photo and any images here
```

## Adding a new note (teaching/learning content, any topic)
1. Copy `notes/template.html` and rename it (e.g. `notes/first-boxing-lesson.html`).
2. Fill in the title, tag, date, and body text — the placeholders are marked with `[brackets]`.
3. Add one matching `<li>` entry to the list in `notes.html`, linking to your new file.

This is the place for the cross-disciplinary stuff — a note can be about learning analytics or about your first month of boxing; the template and tone stay the same either way, which is the point.

## What still needs your input
Search each file for the word **"Placeholder"** — every spot marked that way is content I drafted or stubbed out for you to replace:
- **Your bio** (index.html) — I drafted a starting version from your public mentor bio; swap in your own words whenever ready.
- **Your photo** (index.html) — replace the placeholder `<div class="avatar-placeholder">` with `<img src="assets/photo.jpg" alt="Pawan Gupta" class="avatar-placeholder">` once you drop a photo into `assets/`.
- **Contact email** (contact.html, index.html)
- **Publications list** (research.html)
- **Education history** (cv.html)
- **Poems and articles** (writing.html)
- **CV PDF link** (cv.html) — link to a hosted PDF, or remove the button if you'd rather keep the on-page summary only.

## How to edit
Every file is plain HTML — open in any text editor (or Claude Code / Claude in VS Code) and edit the text directly. No compiling needed; just save and refresh the browser.

## How to host it for free
The easiest path, since you already have GitHub:
1. Create a new GitHub repo (e.g. `pawangupta-1.github.io` for a root-level personal site, or any name + enable Pages).
2. Upload these files to the repo.
3. In the repo's **Settings → Pages**, set the source to your main branch.
4. Your site goes live at `https://pawangupta-1.github.io` (or `https://pawangupta-1.github.io/<repo-name>`).

You can also drag this folder into Netlify or Vercel for a similar free deploy with a custom domain later.

## Design notes
- Palette: warm ivory paper, deep pine green (growth/human development), muted gold accent (for the poetry/human touches).
- Type: Literata (serif, headlines) + IBM Plex Sans/Mono (body, data).
- The thin vertical rule down the left of each section is the recurring motif — a nod to field notes / a research notebook.
