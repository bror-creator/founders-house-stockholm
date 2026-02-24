# Founders House Stockholm — Website Brief

Build a single-page, ultra-premium website for "Founders House Stockholm".

## Reference
The Helsinki site (founders-house.fi) is a React + Three.js SPA with:
- Pure black (#000) background
- Fonts: Outfit (headings, weight 800) + IBM Plex Sans (body)
- Minimal, luxury aesthetic
- 3D elements via Three.js

## Requirements
Build a static HTML/CSS/JS site (single index.html is fine, or with separate CSS/JS files). NO build tools needed.

### Design
- **Color**: Black background (#000), white text, subtle gold/warm accent (#C9A96E or similar)
- **Typography**: Google Fonts — Outfit (800) for headings, IBM Plex Sans for body
- **Layout**: Full-screen hero sections, generous whitespace, slow fade-in animations
- **Vibe**: Think Soho House meets Aesop meets Swiss design. Extremely premium.

### Content (Swedish + English mix, lean English)
1. **Hero**: Full viewport. "FOUNDERS HOUSE" large. Tagline: "Built for the obsessed. Built for the exceptional." Subtitle: "Stockholm"
2. **About**: "A home for ambitious founders in the heart of Stockholm. Not a coworking space. A private community for builders who refuse to settle."
3. **Space section**: Describe the space — "Curated interiors. Private meeting rooms. A rooftop with a view of Gamla Stan." (make it aspirational, not real yet)
4. **Membership**: "Apply for membership" CTA. Tiers: Resident (full-time desk + all access), Community (events + lounge access), Founder Circle (invite-only, equity network)
5. **Events**: "Intimate dinners. Founder talks. Closed-door investor sessions."
6. **Contact/Apply**: Simple form placeholder or mailto link. Email: stockholm@founders-house.com
7. **Footer**: Minimal. Links: Helsinki | Stockholm. © Founders House 2026.

### Interactions
- Smooth scroll between sections
- Subtle parallax on images/elements
- Text fade-in on scroll (IntersectionObserver)
- Optional: subtle Three.js particle/noise background on hero (keep it minimal and performant)
- Hover effects on buttons (scale + glow)

### Images
Use CSS gradients, abstract shapes, or placeholder divs with aspect ratios for image slots. No external images needed.

### Mobile
Must be fully responsive. Clean mobile experience.

### Technical
- Vanilla HTML/CSS/JS or minimal library usage
- Google Fonts loaded from CDN
- No build step required
- Performance: fast load, smooth 60fps animations
