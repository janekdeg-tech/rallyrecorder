# Next Point — home screen prototypes

Static home screens for **Next Point**, in different visual styles. Each is a single
self-contained HTML file (webfonts embedded as base64, works offline). Nothing is wired
up yet — the Upload match button is presentational.

## Mobile (current direction)

Designed at 390 × 844 (iPhone), single tap-target upload button, no drag-and-drop,
tab bar at the bottom, 44px+ touch targets throughout.

| File | Style |
|------|-------|
| `04-paper.html` | **Paper** — warm cream, Fraunces serif headline with italic clay accent, big clay button, rounded cards, a Continue card with progress for the match still in progress. |
| `05-crisp.html` | **Crisp** — cool near-white, all-sans, tight negative letterspacing, ink-black button, hairline-divided list with rally-count badges and done/open pills, stat strip. |

## Desktop explorations (first pass)

| File | Style |
|------|-------|
| `01-broadcast.html` | Sports-graphics energy — condensed uppercase display type, lime on orange over black. |
| `02-calm.html` | The clean look these mobile screens came from — warm paper, serif headline, rounded cards. |
| `03-lab.html` | Technical instrument — monospace, hairline grid, cyan on near-black. |

Screenshots of every prototype are in `shots/`.

## The premise

Load a match video, scrub it, stamp the start and end of every rally, flag lets, and copy
the timestamp list out. See `rally-recorder.html` for the working editor screen.
