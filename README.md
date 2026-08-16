# Signal Watch

Static host for Signal Watch, a personal video feed served as a progressive web app.

`data/watch.json` holds the current feed. `index.html`, `sw.js` and
`manifest.webmanifest` are the app shell, which reads that file and caches it for
offline use.

The selection pipeline runs as a scheduled task on a local machine and is not in this repo.
