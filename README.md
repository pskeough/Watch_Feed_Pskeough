# Signal Watch

**Retired 31 August 2026.** The selection pipeline that fed this app was switched off after
forty nightly runs. `data/watch.json` is the last feed it produced and is kept as a record;
nothing updates it. The successor system generates its own video rather than selecting
existing video, and is hosted separately.

Static host for Signal Watch, a personal video feed served as a progressive web app.

`data/watch.json` holds the final feed. `index.html`, `sw.js` and
`manifest.webmanifest` are the app shell, which reads that file and caches it for
offline use.

The selection pipeline ran as a scheduled task on a local machine and was not in this repo.
