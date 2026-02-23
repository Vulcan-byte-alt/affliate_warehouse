# Project: Affiliate Warehouse Landing Page

## Vision
Premium $50k agency-level website. Think ClickUp.com, Linear.app, Framer.com.
Every section must have a "wow factor." Not a basic SaaS template.
Client must be impressed. Judges must be impressed.

## Tech Stack
- HTML5 (single file: index.html)
- Tailwind CSS via CDN v3
- Vanilla JavaScript only (no frameworks)
- GSAP 3.12.2 + ScrollTrigger plugin via CDN
- Google Fonts: Inter + DM Serif Display

## Design Language
- Hero and 2-3 key sections: DARK (deep navy #07111F)
- Other sections: Clean white or off-white
- This contrast creates the ClickUp "wow" effect
- Blue accent: #3B82F6
- Glassmorphism cards on dark sections
- Elevated shadow cards with hover lift on light sections
- 3D card tilt on hover (CSS perspective + JS mousemove)
- GSAP scroll animations on every section — cinematic, not subtle
- Animated canvas mesh/particle background in hero
- Glow orbs as decorative background elements on dark sections
- Oversized dramatic typography — headings must feel BIG
- Every section has one strong visual "hero moment"

## Typography Scale
- Hero H1: 72px desktop / 42px mobile — DM Serif Display
- Section H2: 52px desktop / 36px mobile — DM Serif Display
- Subheadlines: 18-20px — Inter 400
- Body: 16px — Inter 400
- Labels/eyebrows: 11px uppercase tracked — Inter 700

## Color Tokens
- --navy-deep: #07111F (hero, dark sections)
- --navy-mid: #0D1B2E (cards on dark)
- --navy-border: #1A3050
- --blue-accent: #3B82F6
- --blue-bright: #60A5FA
- --success: #10B981
- --gold: #F59E0B

## Navigation
- Fixed (not sticky) — overlays hero
- Transparent over hero, frosted glass on scroll
- Logo: DM Serif Display, white + blue

## Section Order
1. Hero — dark, canvas animation, floating UI cards
2. Logos/Trust bar — light
3. How It Works — dark, large numbered steps
4. Price Tracking — light, mockup visual
5. Fees & Incentives — dark, 3 dramatic cards
6. No Lock-Ins — light
7. Wholesaler Alignment — dark
8. Social Proof — light
9. FAQ — light
10. Three Conversion Forms — dark
11. Compliance + Footer — dark

## Critical Content Rules
- NEVER suggest bypassing or circumventing wholesalers
- Fee: 1.1% of verified discount only — no discount = no charge
- Wholesalers: TradeZone, Ideal Electrical, Voltex
- Tone: calm, professional, trust-first — premium not hyped

## DO NOT
- Use Bootstrap
- Use jQuery
- Make it look like a basic WordPress site
- Use stock photo placeholder boxes
- Over-explain in body copy — let design do the work
- Use gradients that look cheap