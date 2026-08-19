# Home screen prototypes

Three home screens for Rally Recorder, in intentionally different visual styles.
Each is a single self-contained HTML file (fonts embedded as base64, no network needed)
and is static — the big **Upload Match** button is not wired up yet.

| # | File | Style |
|---|------|-------|
| 1 | `01-broadcast.html` | **Broadcast** — sports-graphics energy: near-black, condensed uppercase display type, acid lime on orange, hard offset shadows, scoreboard stat blocks. |
| 2 | `02-calm.html` | **Calm** — warm paper background, Fraunces serif headline, clay/sage palette, big rounded cards, centred and unhurried. Consumer-app feel. |
| 3 | `03-lab.html` | **Lab** — technical instrument: monospace throughout, hairline grid, cyan-on-black ingest panel, dense data table of past sessions. |

Screenshots of each are in `shots/`.

The premise they're built around: load a match video, scrub it, stamp the start and end
of every rally, flag lets, and copy the timestamp list out — see `rally-recorder.html`
for the working editor screen.
