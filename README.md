# D-Side Designs — Business Website

**Live site:** https://morganh02.github.io/Larrys-Lasers/

A full business website built as a surprise for a close friend who's starting a laser engraving business — coasters, wood, leather, metal, stickers, custom photo work. Designed, built, and deployed end-to-end from a phone.

## About this project

This isn't a template. It's a real design system built from scratch around the actual subject matter: a laser burning a precise mark into material. The visual identity — palette, type, and a small signature animation where the logo appears to be "engraved" on load — comes directly from that idea rather than a generic starting point.

It's also a working piece of business infrastructure, not just a mockup: the contact/order form is live and tested, actually delivering messages.

## Tech stack

- **Frontend:** HTML, CSS, JavaScript — hand-written, no framework
- **Form handling:** [Formspree](https://formspree.io) (contact/order requests)
- **Hosting:** GitHub Pages
- **Coming in Phase 3:** Python + Flask backend, a real database for order storage, and transactional email notifications

## Features

- 5 pages: Home, Gallery, Services & Pricing, About, Contact
- Fully responsive, tested on a real device (not just a browser resize)
- Custom SVG icon set and a single signature motion moment (the "engrave reveal" on the wordmark) rather than scattered generic animations
- Working order-request form
- Every commit, upload, and settings change made from an iPhone — no laptop touched this repo until Phase 3

## Project structure

```
index.html      Home
gallery.html    Recent work
about.html      About Larry
services.html   Services & pricing
contact.html    Contact / order request
styles.css      Full design system
script.js       Mobile nav behavior
*.jpg           Gallery photos
```

## Roadmap

- [x] **Phase 1** — Static site, fully built and live
- [x] **Phase 2** — Reveal to Owner, swap in his final photos/copy/feedback
- [x] **Phase 3** — Flask backend, database-backed order storage, real email notifications
- [x] **Phase 4** — Portfolio case study (see `CASE-STUDY.md`)

## Built with

Designed and developed by Morgan, in collaboration with Claude (Anthropic) for planning, design direction, and code — including diagnosing and fixing several mobile-only deployment issues along the way.
