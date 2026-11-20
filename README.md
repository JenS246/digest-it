# Digest It! — The Deposition Challenge

A standalone, 12-question introductory deposition digest practice game for civil litigation students. All testimony is fictional. The game runs entirely in the browser, does not collect personal information, and has no dependencies or backend.

## Run locally

Open `index.html` in a modern browser, or serve this directory with `python3 -m http.server 8000` and visit http://localhost:8000. The question content and answer keys are in `game.js`.

## Publish

This static project is ready for GitHub Pages. Create a public repository, push the default branch, and set Pages source to GitHub Actions. The included workflow publishes the repository root. The expected URL for a `digest-it` repository under JenS246 is https://jens246.github.io/digest-it/ (available only after successful deployment). No backend, credentials, or data storage are required.
