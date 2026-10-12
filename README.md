# Freedom, Citizenship and Civil Rights – GitHub course site

This folder contains a small static HTML learning course for Year 10 Intercultural Studies.

## Files

```text
freedom-citizenship-civil-rights/
├── index.html
├── styles.css
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

## What each file does

- `index.html` is the course homepage and links to all four modules.
- `styles.css` contains the shared design. Edit this once to change fonts, colours or layout on every page.
- Each `module-*.html` file is a separate student-facing module.
- `SOURCES.md` is the mandatory source and image-rights log.
- `images/` is where you save the selected public-domain or clearly licensed historic images.

## Step 1: Create the folder structure

Create a project folder named `freedom-citizenship-civil-rights`.

Inside it, create a folder named `images`.

Save all six HTML/CSS/Markdown files in the main project folder. Save the four image files in `images/` using exactly the file names listed above.

## Step 2: Add your images legally

1. Open the original institutional page listed in `SOURCES.md`.
2. Check the image’s exact rights statement or rights advisory.
3. Download the image only if the stated terms permit your intended school use.
4. Rename the downloaded file exactly as required:
   - `emancipation-proclamation.jpg`
   - `freedmens-bureau-school.jpg`
   - `segregated-railway.jpg`
   - `march-on-washington.jpg`
5. Record the final credit, URL, creator, date and rights note in `SOURCES.md`.

The HTML already points to these local files, for example:

```html
<img src="images/emancipation-proclamation.jpg" alt="The Emancipation Proclamation, 1863">
```

## Step 3: Preview locally

Double-click `index.html` to open it in a browser. All module links should work without an internet connection once the local images have been added.

## Step 4: Create a GitHub repository

1. Sign in to GitHub.
2. Select **New repository**.
3. Repository name: `freedom-citizenship-civil-rights`.
4. Choose **Public** or **Private** according to your school policy.
5. Do not upload images until you have checked their rights statements.
6. Create the repository.

## Step 5: Upload through the GitHub website

1. In the repository, choose **Add file → Upload files**.
2. Upload:
   - `index.html`
   - `styles.css`
   - all four `module-*.html` files
   - `SOURCES.md`
3. Create an `images` folder by uploading the four image files into a folder called `images`.
4. Commit the changes with a clear message, for example: `Add four-source learning course`.

## Step 6: Publish with GitHub Pages

1. Open the repository’s **Settings**.
2. Open **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`.
5. Save.
6. GitHub will display the public course URL after deployment.

## Step 7: Check the published site

Open the GitHub Pages URL and check:

- all four module links work;
- all four images load;
- captions and credits are visible;
- the site displays correctly on a school device;
- print preview produces readable worksheets.

## Optional changes

### Add a fifth synthesis or test page

Create `module-5-test.html`, then add a fifth card to `index.html`:

```html
<a class="module-card" href="module-5-test.html">
  <span>Module 5</span>
  <h3>Synthesis and test</h3>
  <p>Compare the four sources and write a historical judgement.</p>
</a>
```

### Change course colours

Edit the colour values at the top of `styles.css`:

```css
:root{
  --navy:#133b5c;
  --gold:#bf8529;
}
```

### Add teacher-only solutions

Do not upload answer keys to a public repository if students can access it. Instead, keep a private teacher repository or save the answer key locally.

## Important copyright reminder

GitHub Pages makes a repository publicly available. Only upload images that you are permitted to publish online. If an image is suitable only for closed classroom use, keep the repository private or replace it with a public-domain / openly licensed alternative.
