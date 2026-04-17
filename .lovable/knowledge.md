# Brimax Life — Lovable Knowledge

## Project overview

This project is the public wedding website for `brimax.life`.

The website should feel premium, emotional, modern, and highly polished. It is the main public-facing experience for wedding guests. The site should work beautifully on mobile because many users will arrive through shared links on WhatsApp and Instagram.

This first phase is **frontend only**. The goal is to generate a beautiful and production-ready landing page and section-based website. Do **not** build the admin/backoffice yet.

## Primary goals

1. Create a memorable and elegant wedding website.
2. Make the experience extremely easy to use on mobile.
3. Help guests quickly find the most important information.
4. Encourage RSVP completion.
5. Present the gift list clearly and beautifully.
6. Support future integration with backend APIs, payments, and WhatsApp automation.

## Primary Language Requirement

All visible website content must be written in Brazilian Portuguese (pt-BR).

This includes:
- headings
- buttons
- navigation
- forms
- placeholders
- validation messages
- FAQ
- footer
- RSVP labels
- gift registry text
- confirmation messages

Do not generate public-facing text in English.

Prompts may be written in English, but output UI content must always be pt-BR.

Use natural Brazilian Portuguese.
Tone should be elegant, warm, welcoming, and premium.
Avoid literal machine translations.
Prefer culturally natural phrasing for Brazilian guests.

All public-facing text must be in Brazilian Portuguese (pt-BR).

Use the names Brida e Max naturally in copywriting.
Examples:
- Brida & Max
- Casamento de Brida e Max
- A história de Brida e Max
- Celebre com Brida e Max

## Couple Identity

The wedding couple names are:

- Brida
- Max

The brand/domain "brimax.life" comes from the combination of:
Brida + Max = Brimax

This identity should be subtly reflected throughout the website.

Use the names naturally in:
- hero section
- headings
- invitations
- storytelling sections
- footer
- romantic copy

The tone should feel elegant, genuine, and personal.

## Current project state

- Domain: `brimax.life`
- Hosting: AWS S3 + CloudFront
- DNS: Cloudflare
- Repo exists and will be used for the frontend
- Backend is not deployed yet
- Backoffice is intentionally out of scope for now

## Design direction

The main visual inspiration is **Aceternity UI**.

The aesthetic should be:
- premium
- elegant
- cinematic
- emotional
- modern
- minimalist, but not cold
- highly polished
- motion-rich, but tasteful

### Desired visual mood

Use a blend of:
- modern romantic wedding aesthetic
- subtle luxury
- refined editorial layout
- soft glow / layered visual depth
- high-end product design polish

### Color direction

Prefer a soft and elegant palette:
- ivory
- white
- warm beige
- champagne / muted gold accents
- soft gray for contrast

Avoid:
- loud neon colors
- harsh contrast everywhere
- generic SaaS blue aesthetics
- overly playful cartoon styles

### Typography direction

Typography should feel premium and readable.

Recommended direction:
- elegant serif for selected headings if it improves the wedding/luxury feel
- clean modern sans-serif for body text and UI
- large type for hero and key sections
- high readability on mobile

### Motion and interaction

Use motion intentionally.

Recommended:
- subtle entrance animations
- parallax or layered depth only if tasteful
- elegant hover states
- soft gradients, glows, or blur effects where appropriate
- smooth scrolling experience
- transitions that feel refined, not flashy

Avoid:
- noisy motion
- too many animations competing for attention
- performance-heavy effects that degrade mobile UX

## UX priorities

The most important aspect of the website is **user experience**.

### UX principles

1. Mobile-first.
2. Important information should be easy to find in under a few seconds.
3. RSVP should be obvious and frictionless.
4. The website should be beautiful, but beauty must not reduce usability.
5. Older family members and non-technical guests should still find it simple.
6. Navigation should be intuitive and section-based.
7. Clear calls to action are required.

### Target audience

The users are wedding guests, which may include:
- family members
- friends
- older users
- mobile-first users
- users arriving from WhatsApp links

The website must be comfortable for all of them.

## Scope for this phase

### In scope

Build a beautiful public wedding website with these sections:

1. Hero section
2. Countdown section
3. Our Story
4. Ceremony Location
5. Groomsmen and Bridesmaids
6. Vendors / Suppliers
7. Gift List
8. RSVP section
9. Live Streaming section with embedded YouTube area
10. FAQ
11. Footer

### Out of scope for now

Do **not** build these yet:
- admin dashboard
- backoffice
- Google SSO
- WhatsApp API dashboard
- purchased gifts tracking admin UI
- confirmation tracking admin UI
- real payment processing integration
- real backend integration
- real authentication

However, the design should be future-friendly so these can be added later.

## Page structure

The site should behave like a premium one-page wedding website with strong section composition.

Recommended order:

1. Hero
2. Countdown
3. Our Story
4. Ceremony Location
5. Wedding Party
6. Vendors / Suppliers
7. Gift List
8. RSVP
9. Live Streaming
10. FAQ
11. Footer

## Section requirements

### 1. Hero

Purpose:
- create emotional impact immediately
- communicate wedding identity quickly
- drive RSVP and gift list exploration

Include:
- couple names
- wedding date
- short romantic tagline
- primary CTA: `RSVP Now`
- secondary CTA: `Gift List`

Style:
- high-impact, cinematic, premium
- elegant layered visuals
- subtle animation
- generous spacing

### 2. Countdown

Purpose:
- build excitement
- reinforce event date

Include:
- countdown timer to the ceremony
- elegant typography
- optional supporting sentence

### 3. Our Story

Purpose:
- add emotional depth and storytelling

Include:
- relationship timeline or milestone cards
- visual rhythm and elegant content blocks
- optional photos or placeholders

Style:
- editorial storytelling
- soft visual transitions
- emotionally warm

### 4. Ceremony Location

Purpose:
- make logistics easy

Include:
- venue name
- date and time
- location summary
- embedded map placeholder
- practical information area

Style:
- beautiful but highly functional

### 5. Groomsmen and Bridesmaids

Purpose:
- celebrate the wedding party

Include:
- cards with photo placeholders
- names
- optional short role/description

Style:
- polished profile grid
- strong mobile layout

### 6. Vendors / Suppliers

Purpose:
- showcase vendors elegantly

Include:
- vendor cards
- category labels
- short descriptions
- optional links/placeholders

Potential vendor categories:
- venue
- photography
- music
- catering
- decoration

### 7. Gift List

Purpose:
- make gift browsing inviting and clear

Include:
- beautiful card-based layout
- image placeholders
- gift title
- short description
- price placeholder or contribution CTA placeholder
- gift CTA button

Important:
- This is visual only for now.
- Do not wire real payment flows yet.
- Structure the section so it can later integrate with a payment service.

### 8. RSVP

Purpose:
- maximize confirmation completion

Include:
- elegant RSVP form UI
- fields for name, attendance, guests, message/notes
- obvious submit CTA

Important:
- For now, this can be mock or frontend-only.
- Build the UI as if it will later connect to a real backend.

UX guidance:
- keep the form simple
- minimize friction
- strong mobile ergonomics

### 9. Live Streaming

Purpose:
- allow remote participation

Include:
- embedded YouTube livestream placeholder area
- title and support copy
- good responsive behavior

Important:
- make the section elegant, not just a raw embedded block

### 10. FAQ

Purpose:
- reduce guest confusion

Suggested FAQ topics:
- dress code
- arrival time
- parking
- gifts
- live streaming access
- RSVP deadline

Use an elegant accordion or expandable card pattern.

### 11. Footer

Include:
- simple closing message
- social placeholders
- contact placeholder
- copyright or small branded note if appropriate

## Navigation

The website should include a modern sticky or semi-sticky navigation optimized for both desktop and mobile.

Recommended nav items:
- Home
- Our Story
- Location
- Wedding Party
- Vendors
- Gift List
- RSVP
- Live
- FAQ

Mobile navigation should be smooth and easy.

## Product constraints

### Important constraints

- Build the site as a **frontend-only experience for now**.
- Do not depend on real backend data.
- Use placeholder/mock content where necessary.
- Keep architecture ready for future API integration.
- Keep components reusable and clean.
- Prefer production-quality structure over a throwaway mockup.

## Technical direction

Assume the project is a modern React-based frontend.

Preferred implementation direction:
- React
- TypeScript
- responsive design
- component-based structure
- animation patterns inspired by Aceternity UI

Prefer code that can later fit into a real engineering codebase.

## Content placeholders

Use tasteful placeholders where exact content is not known yet.

### Placeholder content needed

- couple names
- wedding date
- hero tagline
- story milestones
- venue details
- wedding party names/photos
- vendor names/details
- gift items
- YouTube live URL
- FAQ answers

Use realistic placeholders, not lorem ipsum whenever possible.

## Conversion priorities

The page should optimize for these actions:

1. RSVP
2. Explore wedding details
3. View gift list
4. Access live stream

The interface should make the RSVP action especially clear.

## Accessibility and usability

The site should feel premium without sacrificing accessibility.

Requirements:
- good contrast
- readable font sizes
- large tap targets on mobile
- semantic structure where possible
- simple form UX
- minimal friction

## Mobile requirements

This is critical.

The mobile experience should feel first-class.

Prioritize:
- responsive hero layout
- easy section navigation
- elegant stacking of cards and content
- RSVP form usability on small screens
- embedded map/video that behaves well on mobile
- no cluttered dense layouts

## What success looks like

A successful output should feel like:
- a premium modern wedding website
- emotionally engaging
- easy for guests to use
- visually impressive on first load
- highly polished on mobile
- ready for future integration work

## Explicit instructions for generation

When generating this site:

- prioritize UX over decoration
- use Aceternity UI as primary design inspiration
- create a cohesive visual system, not a random collection of sections
- ensure all sections feel like part of one premium brand
- favor elegant modern design over generic template aesthetics
- make the site look high-end and memorable
- do not build backoffice or admin features yet
- do not add fake complex backend logic
- structure the frontend so backend integrations can be added later

## Notes for future phases

Future versions may add:
- Google SSO authenticated backoffice
- confirmation tracking
- gift purchase tracking
- WhatsApp API message tracking
- payment provider integration
- real RSVP backend
- guest management

This future possibility should influence structure, but not current scope.
