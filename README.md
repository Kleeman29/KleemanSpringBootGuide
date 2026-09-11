# Kleeman Spring Boot Guide

A beginner-friendly Spring Boot course presented as narrated slides. It contains 30 lessons, 311 slides, code examples, practice exercises, progress tracking, and a downloadable Task API project.

## Run it locally

No installation is required. Open `index.html` in a browser.

For a local web server, run this from the project folder:

```bash
python -m http.server 3000
```

Then open `http://localhost:3000`.

## Put it on GitHub

### Option 1: GitHub website

1. Create a new empty repository on GitHub.
2. Extract this ZIP.
3. On the repository page, choose **Add file → Upload files**.
4. Upload the contents of this folder. Make sure `index.html` is at the repository root.
5. Commit the files.

### Option 2: Git commands

Create an empty GitHub repository first, then run:

```bash
git init
git add .
git commit -m "Add Kleeman Spring Boot Guide"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub information.

## Publish it on Vercel

1. Sign in at [vercel.com](https://vercel.com) with GitHub.
2. Choose **Add New → Project**.
3. Import the GitHub repository containing this project.
4. Leave **Framework Preset** set to **Other**.
5. Leave the build command blank.
6. Leave the output directory blank.
7. Choose **Deploy**.

Vercel will serve `index.html` as the home page. The included `vercel.json` adds basic security and caching headers.

## Main files

- `index.html` — page structure and metadata
- `style.css` — red theme and responsive layout
- `lessons.js` — lesson content
- `slides.js` — slideshow and browser voiceover
- `app.js` — navigation, rendering, and progress tracking
- `downloads/task-api.zip` — downloadable Spring Boot Task API
- `vercel.json` — Vercel configuration

## Notes

Voiceover uses the browser's built-in speech service, so available voices vary by browser and device. Lesson progress is stored in the visitor's browser with `localStorage`.

