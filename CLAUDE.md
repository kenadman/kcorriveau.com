This repo is kcorriveau.com, Ken's personal website. It is not Vista or Evolvium. If a request mentions Vista, Evolvium, Supabase, or the platform build, stop and confirm with Ken before touching anything.

# Project rules

## Purpose
- Personal site for Ken Corriveau.
- Audience: PE firms and portfolio CEOs, executive recruiters, and boards.
- Goal: fractional, interim, or full-time CIO roles and board seats.
- It does not sell Evolvium or consulting services.

## Planned sections
Hero, about, core pillars, experience timeline, skills, case studies, certifications, thought leadership, speaking and board, testimonials, contact.

## Structure
- All website files live in /docs, which is the GitHub Pages publishing folder.
- Repo-level files (CLAUDE.md, README.md) stay outside /docs so they are never published as pages.

## Tech
- Plain HTML and CSS with minimal vanilla JavaScript.
- No framework, no build step, no npm.
- Keep an empty .nojekyll file in /docs.

## Paths
- Links and asset paths must be relative (about.html, css/site.css), never root-absolute (/about).
- The preview runs at https://kenadman.github.io/kcorriveau.com/ until the domain cutover.

## Domain
- Do not create a CNAME file or set a custom domain. Ken will call the DNS cutover when the site is approved.

## Privacy
- The repo is public. Never commit drafts, notes, the content blueprint, contact lists, credentials, or anything private.

## Content
- Content comes only from Ken. Never invent testimonials, metrics, clients, or credentials.

## Contact
- Booking link: https://app.reclaim.ai/m/kencorriveau/flexible-quick-meeting
- Email: ken@kcorriveau.com
- No contact form.

## Writing rules
- No em dashes.
- No exclamation points.
- No emoji.
- Never use the word "excited".

## Images
- Only photos Ken supplies.
- Reuse nothing from the old Network Solutions site.

## Build quality
- Build mobile first.
- Give every image alt text.
- Keep pages fast.

## Workflow
- Small commits pushed to main, then check the preview URL.
