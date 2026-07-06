# Park Rave 005

Event landing page and collective hub for **Park Rave 005 — Bicycle Day Banger Part Two**, a free outdoor Philadelphia rave presented by No Nonsense & Massive Promotions, live at **[davehomeassist.github.io/park-rave-005](https://davehomeassist.github.io/park-rave-005/)**.

## What's here

| Path | What it is |
|---|---|
| `index.html` | The Park Rave 005 event page — date/time/RSVP details, flyer, feature highlights, and an email-updates capture form (submits via `mailto:`). |
| `nononsensephl-v2.html` | The wider "No Nonsense PHL" collective hub — event countdown with live/past states, RSVP + add-to-calendar (`.ics` download), artist booking and vendor application links, gear rental info, and merch showcase. |
| `park-rave-005-flyer.png` | Official event flyer, used as the social preview image and on-page poster. |
| `favicon.png` | Site favicon / touch icon. |
| `LICENSE` | All-rights-reserved notice. |

Both pages are self-contained static HTML with inline CSS/JS — no build step, no dependencies, no backend. RSVP and vendor/booking links point out to Instagram, Linktree, and Google Forms; the collective page tracks RSVP state and countdown timing client-side via `localStorage`.

## How to run

Open `index.html` directly in a browser, or serve the folder with any static file server. `nononsensephl-v2.html` is a standalone page and can be opened the same way.
