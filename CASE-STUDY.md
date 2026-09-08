# Case Study: D-Side Designs

*A surprise business website, designed and shipped entirely from a phone.*

## The brief

A close friend started a laser engraving business — coasters, wood signs, leather, metal, custom photo portraits, stickers — as a hobby that grew into real demand. I wanted to give him a real business website as a surprise, and use the project as a serious portfolio piece for myself.

Constraints that shaped everything:
- **It had to stay a secret.** No asking him for content, branding direction, or feedback until reveal day.
- **My tools were HTML, a little Python, and a willingness to learn.**
- **It needed to look like a considered design, not a template** — this was going on my portfolio.

## Process

**Planning first.** Before writing a line of code, I mapped the project into four phases — static site, reveal, real order backend, portfolio polish — and kept a running project plan doc as the single source of truth throughout. Every decision, every "needs confirmation later," every open question got logged there instead of living only in chat history.

**Designing around the subject, not a template.** The temptation with an AI-assisted build is to land on generic defaults — a cream background, a terracotta accent, rounded cards with soft shadows. Instead, the whole visual identity was grounded in what the business actually does: a laser burning a precise line into material. That gave a real base palette (light "raw material" surface, dark "burned" ink, one sharp ember-red accent used sparingly) and, eventually, a signature moment — the site's wordmark loads as a hollow outline and gets traced solid by a small traveling beam, like it's being engraved in real time.

**Working from real content, not placeholders, as fast as possible.** As soon as real photos of his work came in, I used them — after stripping location metadata phones quietly embed in photos, correcting a sideways image, and holding back two photos that weren't right for a public gallery yet (one was someone's personal memorial, not mine to publish without consent; the other was a screenshot with a stranger's name visible in it). Small craft details like that matter as much as the visual design.

## The unexpected challenge: shipping from a phone

Partway through, my laptop wasn't available for a full day. Rather than pause, I treated it as a constraint to design around:

- **GitHub Pages hosting requires a public repo on the free tier** — worth knowing and flagging honestly, since this was meant to stay a secret pre-reveal.
- **GitHub's mobile app can create repos but can't upload files** — that part still needs Safari.
- **Multi-file folder uploads are fragile on a phone file picker.** The fix was flattening the image folder structure into the project root so everything could be selected and uploaded in one pass, instead of fighting nested folder paths in a mobile browser.
- **Real bugs only showed up on a real device** — a mis-sized nav menu, a CSS flex-direction typo that collapsed a three-bar hamburger icon into a single line. Both were found and fixed live, from the same phone that broke them.

None of this was in the original plan. All of it made it into the final site.

## Outcome

A five-page, fully responsive business website — Home, Gallery, Services & Pricing, About, Contact — with a working, tested order-request form, live on GitHub Pages, built with a from-scratch design system rather than a template. Every part of it, from repository creation to the final deploy, happened on an iPhone.

## What's next

**Phase 2:** Reveal the site and swap in Larry's final photos, copy, and feedback.
**Phase 3:** A Python/Flask backend with real order storage and email notifications — the point where this becomes genuine full-stack work, and where a laptop comes back into the picture.

## What I'd tell someone starting a similar project

Constraints aren't just obstacles — they're often the most interesting part of the story. The mobile-only deployment wasn't in the plan, but it's the part of this case study worth remembering.
