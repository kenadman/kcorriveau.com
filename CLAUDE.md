This repo is kcorriveau.com, Ken's personal website. It is not Vista or Evolvium. If a request mentions Vista, Evolvium, Supabase, or the platform build, stop and confirm with Ken before touching anything.

# Project rules

## Purpose
- Personal site for Ken Corriveau.
- Audience: PE firms and portfolio CEOs, executive recruiters, and boards.
- Goal: fractional, interim, or full-time CIO roles and board seats.
- It does not sell Evolvium or consulting services.

## Sections (v1, one page, in order)
1. Hero
2. Approach ("When Leaders Call Me")
3. AI ("My View on AI")
4. Experience ("Track Record")
5. Ventures ("One Mission, Three Ways to Work With Me")
6. Board and Advisory
7. Media ("Interviews and Articles")
8. Contact ("Let's Talk")

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
- The primary call to action is engaging Ken through Fortium Partners.
- The secondary is the booking link https://app.reclaim.ai/m/kencorriveau/flexible-quick-meeting.
- Contact also lists ken@kcorriveau.com and LinkedIn https://www.linkedin.com/in/kennethcorriveau/.
- No phone number and no contact form.

## Fortium link placeholder
- Fortium profile URL pending. Every Fortium link points to https://fortiumpartners.com and carries data-placeholder="fortium-profile" so all of them can be swapped in one pass later.

## Executive education (confirmed)
Executive education courses, not degrees. Newest first:
- Stanford University, artificial intelligence program (2025)
- UC Berkeley Haas School of Business, Innovation and Change (2021)
- Harvard, leadership program (2012)
- MIT Sloan School of Management, Technology Management (2006)

## Design
- One family with Evolvium AI, with its own accent.
- Fonts: Outfit for headings, DM Sans for body, from Google Fonts.
- Navy #162842: headings, the nav and dark bands.
- Ink #1F3553: body text.
- Muted #4A5670.
- Page background #F7F9FC. Cards #FFFFFF. Soft panels #EDF3FA. Borders #DCE5F0.
- Accent copper #A9521C for buttons and links on light backgrounds (white text on it is 5.4:1).
- On navy backgrounds use #E3A472 for accent text.
- Never use magenta or a ring gradient. That accent belongs to Evolvium.
- Feel: board-ready and calm, generous white space, one idea per section.
- Mobile first. Subtle motion only, and respect prefers-reduced-motion.
- Favicon: SVG KC monogram in navy and copper.
- No cookie banner, no analytics, no scripts beyond Google Fonts. No HTML comments.

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
