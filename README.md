# Tomographic Summer Chill — 30–31 July 2026

Website for the Tomographic Summer Chill workshop at ETH Zürich
(LEE C114 / LEE E101, mornings of 30–31 July 2026).

**Live site:** https://wangyuhan2002.github.io/2026-tomo-workshop/

## What this is

A single self-contained `index.html` — no build step, no dependencies.
Open it locally or drop it on any static host.

## Editing

- **Programme / speakers / abstracts** — the `<section id="programme">` block.
  Each talk is one `.slot`; abstracts are `<details class="abs">`.
- **Registration email** — the `user` / `domain` variables in the mailto
  script near the bottom. That is the single source of truth; the address is
  assembled at runtime so scrapers can't harvest it from the source.
- **Colours / type** — CSS custom properties in `:root` at the top.
  Light and dark themes are both defined.

## Registration

Registration is by plain email. Zoom runs as a normal recurring Meeting
(the ETH staff licence covers 500 participants — no Webinar add-on needed).
The join link is never published here; it is mailed to registrants.
**BCC — never To — when mailing the list.**
