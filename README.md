# ParkPilot AI pitch deck

An interactive, animated pitch deck for ParkPilot AI: two AI departments for UK holiday parks.

It is a single self-contained file, `index.html`, with no build step. Open it in a browser, or host the repository root on any static host (Netlify, GitHub Pages).

## Slides

1. Introduction
2. The problem
3. The 9pm Tuesday story (toggle without / with ParkPilot)
4. The two departments: AI Guest Services and AI Owner Services
5. Demo: website chat widget feeding the CRM pipeline automatically
6. Around the clock (drag the time of day)
7. Human handover (three scenarios, choose the team's action)
8. One platform alongside existing systems
9. Results and customers
10. Getting started and pricing
11. Next steps

## Controls

- Left and right arrow keys, the buttons in the bottom bar, or a swipe.
- Each slide has its own link, for example `index.html#demo`.
- The full-screen button is in the bottom-right corner.

## Editing

Brand colours and fonts are tokens in the `:root` block at the top of the stylesheet. The demo conversation (`SCRIPT`), the 9pm Tuesday timelines (`TL`), the time-of-day examples (`EX`) and the handover scenarios (`CASES`) are plain data near the bottom of the file.

Conversations, the demo park and scenario details are illustrative. Statistics are ParkPilot estimates unless a source is given on the slide. The Philmar Guest House quote is used exactly as supplied.
