# Speakout B2 · Course Companion

A static, hash-routed companion site for the local Speakout 3rd Edition B2 book. The design and navigation mirror the reference companion site; all educational content is condensed from the local B2 Student Book and its original media only.

## Structure

- `index.html`, `app.js`, `styles.css`, `reference.css` — static SPA shell and design system
- `data/unit1.json` … `data/unit8.json` — condensed lessons, vocabulary, grammar, tasks and quizzes
- `data/media.json` — manifest of all copied media
- `data/videoscripts.txt` — working text extracted from the local videoscripts PDF
- `media/audio/`, `media/video/` — original class audio and BBC videos
- `books/` — original Student Book and Videoscripts PDFs

## Local preview

```powershell
node D:\new book b1+\_b2-work\serve.js D:\new book b1+\_b2-site 4173
```

Open `http://localhost:4173/#/`.

## Publishing

Deployed publicly on GitHub Pages from the repository root. All asset URLs are relative so the site works under a Pages project subpath.
