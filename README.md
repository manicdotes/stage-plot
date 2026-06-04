# manicdotes — Stage Plot

Live stage plot, input list, and FOH tech notes for **manicdotes**, hosted on GitHub Pages.

**Live site:** https://manicdotes.github.io/stage-plot/

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Full stage plot + 7-channel input list + FOH tech notes. **Print / Save PDF** button; the input-list section links to the full-screen view. |
| `inputs.html` | Oversized, high-legibility input list for fast reading during dark changeovers. Has its own **Print / Save PDF** button and a link back to the stage plot. |

Both pages are self-contained (inline CSS, no build step, no dependencies) and use a light background with dark text. The **Print / Save PDF** button prints whichever page you're on, set up for US Letter portrait. Toolbar buttons and nav links are hidden when printing.

## Editing

Everything lives in the two HTML files. To change a member, channel, or note, edit the text directly and commit — the band rig is defined in:

- The stage diagram nodes (`<div class="pos">…`) and input-list table in `index.html`
- The channel `.row` blocks in `inputs.html`

Keep the two input lists in sync when channels change.

## The rig (summary)

- 4-piece, **fully ampless** (guitars + bass on HX Stomp modelers).
- Band brings its own mixer and hands FOH a **7-channel XLR snake**: VOX RIGHT / LEFT / CENTER / REAR (mic level), GUITAR RIGHT / LEFT, BASS (line level).
- **In-ear monitors** — no stage wedges needed from FOH.
- FOH mics the **drum kit** at engineer's discretion (FOH only).
- Power: one drop per position + two powered cabs (behind Rob & Justin, power only).

Contact: info@manicdotes.com
