# Interactive source course – GitHub Pages package

This version replaces the previous static module files. Each module contains:

- a source and contextual visual;
- vocabulary help;
- typed-answer activities;
- click-to-answer questions;
- drag-and-drop ordering where appropriate;
- a written response that saves in the learner’s browser;
- a short end-of-module quiz;
- automatic feedback and a completion status.

## File structure

```text
freedom-citizenship-civil-rights-interactive/
├── index.html
├── styles.css
├── app.js
├── module-1-emancipation.html
├── module-2-reconstruction.html
├── module-3-plessy.html
├── module-4-king.html
├── SOURCES.md
└── images/
    ├── emancipation-proclamation.jpg
    ├── freedmens-bureau-school.jpg
    ├── segregated-railway.jpg
    └── march-on-washington.jpg
```

## How the interactivity works

- `app.js` checks radio-button answers and typed key words.
- The Reconstruction module includes drag-and-drop ordering.
- Written responses are stored using browser `localStorage`. They remain on the same device/browser but are not sent to the teacher or GitHub.
- A module is marked complete after a learner scores at least 2 out of 3 in its end quiz.
- The home page shows progress from 0 to 4 completed modules.

## Add the four images

1. Create an `images` folder.
2. Download only public-domain or clearly licensed images from the original institutions.
3. Use exactly these filenames:
   - `emancipation-proclamation.jpg`
   - `freedmens-bureau-school.jpg`
   - `segregated-railway.jpg`
   - `march-on-washington.jpg`
4. Document exact source, creator/date where available, source URL and rights statement in `SOURCES.md`.

## Test locally

Open `index.html` in a browser. Complete a quiz, then return to the home page. The progress bar should update. Refresh the page: typed reflections and completed modules should remain saved.

## Publish on GitHub Pages

1. Create a repository on GitHub.
2. Upload all files and the `images/` folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`.
6. Save and wait for the GitHub Pages URL.

## Privacy and school use

This static site does not collect names, e-mail addresses or answers centrally. Student text remains in each browser’s local storage. Do not treat these browser-based results as formal assessment evidence without another documented method of submission.

## Teacher option: collect student work

For assessment, ask students to copy their saved written reflections into a school-approved LMS, Word document, Forms tool or learning platform. Do not add external form collection without checking GDPR / school data-protection requirements.
