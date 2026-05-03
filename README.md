# Sylvie Phonics Adventure

A calm, offline-first phonics and early literacy practice app for home co-play and educator-informed practice.

## What this is

This is a static web app. It can run from a single `index.html` file and can be deployed on GitHub Pages, Vercel, Netlify, or any static host.

## Quick start

Open `index.html` in a browser, or serve the folder locally:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. Go to **Settings → Pages**.
4. Set source to **Deploy from a branch**.
5. Choose `main` and `/root`.
6. Save.

Your app should appear at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME/
```

## Deploy to Vercel

1. Import the GitHub repo into Vercel.
2. Framework preset: **Other** or **Static**.
3. Build command: leave blank.
4. Output directory: leave blank / root.
5. Deploy.

## Notes

- This app stores progress locally in the browser.
- It does not upload child data to a server.
- Curriculum references are EYLF-informed and NSW transition-aware, not official certification.
