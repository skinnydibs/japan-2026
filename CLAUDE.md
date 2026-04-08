# CLAUDE.md — Japan 2026 Itinerary

## What This Project Is
A single-file family travel itinerary for Japan, April 2026.
Travelers: Hugo (child), James, Lynn.

## Tech Stack
- **One file only**: `index.html` (~1000 lines). No build tools, no frameworks, no package.json.
- Vanilla HTML + CSS + JS
- Google Fonts: Shippori Mincho (headings) + DM Sans (body)
- No external dependencies beyond the font CDN

## Trip Details
| | |
|---|---|
| Dates | 12–21 April 2026 (10 days) |
| Route | KIX → Kyoto → Osaka → Singapore |
| Night 1 | Hotel Nikko KIX (airport-connected) |
| Nights 2–5 | 22 Pieces Hotel, Kyoto |
| Nights 6–9 | Fraser Residence Osaka (near Namba) |

### Day-by-day
| Day | Date | Title |
|---|---|---|
| 1 | 12 Apr (Sun) | Arrival — KIX |
| 2 | 13 Apr (Mon) | Kyoto Check-In · Railway Museum |
| 3 | 14 Apr (Tue) | Fushimi Inari · Uji |
| 4 | 15 Apr (Wed) | Arashiyama · Bamboo · Rickshaw · Monkey Park |
| 5 | 16 Apr (Thu) | Nara Day Trip |
| 6 | 17 Apr (Fri) | Osaka Arrival · Castle · Dotonbori |
| 7 | 18 Apr (Sat) | Kaiyukan · Tempozan |
| 8 | 19 Apr (Sun) | Nifrel · EXPOCITY |
| 9 | 20 Apr (Mon) | Kids Plaza · Kuromon · Shinsaibashi |
| 10 | 21 Apr (Tue) | Departure → Singapore |

## Key Features in the HTML
- Collapsible day cards (click header to expand/collapse)
- Family markers: Hugo (gold/kids), James (nature/green), Lynn (shopping/pink)
- Annotation block types: memory moment, nature note, shop note, hidden gem, suggestion, time-sensitive alert, rest window
- Tabbed panel at the bottom: booking checklist (with real reservation numbers embedded)
- Map links (Google Maps) inline with activities
- Fully responsive — mobile breakpoint at 600px

## Rules for Editing
- **Do not split into multiple files** — single-file is intentional. Keep everything in `index.html`.
- Do not introduce build tools, npm, or frameworks.
- Reservation numbers and booking details are real — do not edit or fabricate them.
- CSS custom properties (`:root` vars) control the colour system — use those, don't hardcode hex values.
- Keep the existing block/component patterns (`.tl-item`, `.memory-block`, `.gem-block`, etc.) — don't invent new patterns for things that already have a component.
