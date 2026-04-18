# Pest Pro LLC — Competitor Analysis & Website Rebuild Blueprint
*Researched: 2026-04-18 | Competitors: Orkin, Terminix, Massey Services, Turner Pest, Truly Nolen*

---

## 1. What the Top Sites All Do

### Navigation
- **Sticky nav always** — never scrolls away. Phone number always visible top-right.
- **Dropdown mega menus** for Services (list every pest) and Locations (list every city/region)
- **Separate pages for everything** — no anchor-link-only navigation. Every service and every city = its own URL.
- **Mobile**: hamburger + persistent bottom bar with click-to-call button. This is universal across all premium sites.

### Hero Section
- **Real photography dominates** — technician at door, family in clean home, branded truck. Not just mascots.
- **Headline is 2 lines max**, short, punchy, benefit-led. NOT "We Don't Just Treat Pests. We Eliminate Them." — too long for mobile.
- **Single primary CTA** — "Get a Free Quote" or "Schedule Free Inspection." One button, massive, yellow/orange.
- **ZIP code or phone input in the hero** — Orkin, Terminix, Massey all do this. Reduces friction, instant local routing.
- **Social proof immediately below headline** — "Based on 15,000+ Reviews" (Massey) or star rating inline.
- **Hero image is full-bleed background or split 50/50** — not a floating card.

### Trust Signals
- Review count + stars placed IN THE HERO, not a separate section below.
- License numbers, certifications, years in business — in a trust bar immediately below hero.
- "Satisfaction Guarantee" called out prominently with an icon/badge.
- Better Business Bureau, Google Guaranteed badges where applicable.

### Services Section
- **Each service = clickable card linking to its own page** — never dead anchor links.
- Cards use real pest photography, not just emoji or icons.
- Short 1-line description only — the detail lives on the service page.

### Pricing
- **None of the big players show prices** — they all funnel to a free quote/inspection form.
- Massey is the exception — runs promotional discounts ($50 off, $75 off) as the primary CTA.
- Takeaway: showing pricing gives competitors something to undercut. Lead with "Free Inspection" instead.

### Social Proof
- Reviews distributed throughout the page — not one section at the bottom.
- Inline testimonials between service cards, in the hero, in the about section.
- Google/Yelp brand logos shown next to review count for instant credibility.

### Mobile
- Body text minimum 16px — most use 17-18px for body.
- Hero headline: 28-36px on mobile (clamp from 40px desktop).
- Sticky bottom call bar: "📞 Call Now" full-width button, always visible.
- Section padding: 2.5rem top/bottom on mobile (not 5rem).
- CTAs are full-width buttons on mobile, minimum 54px tap target height.

### Page Architecture
- Homepage = conversion hub, not a content dump.
- `/services/[pest-name]` = one page per pest, fully SEO optimized.
- `/locations/[city]` = one page per city with local schema, local keywords.
- `/blog/` = educational content hub for long-tail keywords.
- Internal linking between all service + location pages = Google authority distribution.

---

## 2. What Separates $50K Sites from $5K Sites

| Factor | $5K Site | $50K Site |
|--------|----------|-----------|
| Mobile CTA | Buried below fold | Sticky bottom bar always visible |
| Hero | Long headline, floating mascot | Short punchy headline, full-bleed photo, ZIP input |
| Trust signals | One reviews section at bottom | Stars in hero, badges in trust bar, testimonials inline |
| Navigation | Anchor links | Dropdown menus, separate pages per service/city |
| Services | Emoji cards on one page | Clickable cards → individual SEO pages |
| Pricing | Transparent pricing table | "Free Quote" funnel, promotional discount |
| Typography | One font, inconsistent sizing | Clear type scale, 16-18px body, large CTAs |
| Images | AI mascot only | Real photography + mascot combination |
| Schema | Basic LocalBusiness | LocalBusiness + Service + FAQ + Review schema per page |
| Speed | Unoptimized images | WebP images, lazy load, preload critical assets |
| Animations | None or heavy | Subtle scroll-triggered fade-ins only |

---

## 3. Recommended Pest Pro Homepage Section Order

```
1. TOP BAR — phone number + "Available 24/7" + license number
2. STICKY NAV — logo + dropdown menus (Services, Locations) + phone + "Free Inspection" CTA
3. HERO — short headline + sub + ZIP input OR single CTA + star rating inline + full-bleed split image
4. TRUST BAR — 4 badges: Licensed & Insured | 35+ Years | 5-Star Rated | 24/7 Available
5. SERVICES GRID — 9 pest cards, each linking to /services/[pest], real images
6. EMERGENCY BAND — dark red strip: "Same-Day Service Available · Call (407) 922-2276"
7. HOW IT WORKS — 3-step process (Schedule → We Treat → You're Protected)
8. COMMERCIAL CALLOUT — navy banner, industries served, "Get Commercial Quote"
9. ABOUT/STORY — split layout, image left, story right. Credibility: Dr. Howell + Daniel.
10. REVIEWS — stars in header, 4 review cards, Google/logo badge
11. FAQ — 6 questions with schema markup for featured snippets
12. SERVICE AREA — county/city grid
13. BLOG PREVIEW — 3 latest articles
14. CONTACT/CTA SECTION — full-width, form + phone + trust badges
15. FOOTER — full 4-column, all service + location links, license number, copyright
16. MOBILE STICKY BAR — fixed bottom, "📞 Call Now" + "Get Free Inspection"
```

---

## 4. Mobile Specifications

- **Body text**: 16px minimum, 17px preferred
- **Hero headline**: clamp(1.8rem, 6vw, 3.8rem)
- **Hero subtext**: 15px, max-width 90%
- **Section padding**: 3rem 4% on mobile
- **CTA buttons**: width: 100%, max-width: 340px, height: 54px minimum
- **Nav height**: 64px on mobile
- **Trust bar**: 2-column grid on mobile
- **Cards**: single column below 600px
- **Sticky bottom bar**: fixed, bottom: 0, full width, z-index: 999, two buttons side by side

---

## 5. SEO Specifications Per Page

### Homepage
- Title: "Pest Control Orlando FL | Pest Pro LLC | (407) 922-2276"
- Description: 155 chars, local keywords, phone number
- Schema: LocalBusiness + AggregateRating + FAQPage
- H1: One, short, contains "pest control [city]"
- H2s: One per section
- Internal links: every service card → service page, every city → location page

### Service Pages (/services/[pest])
- Title: "[Pest] Control [City] FL | Pest Pro LLC"
- Schema: Service + LocalBusiness
- Content: 600-800 words minimum, local references
- H1: "[Pest] Control in [City], FL"
- CTA above fold on every page

### Location Pages (/locations/[city])
- Title: "Pest Control [City] FL | Pest Pro LLC"
- Schema: LocalBusiness with city-specific geo coordinates
- Content: city-specific, mentions neighborhoods/landmarks
- H1: "Pest Control in [City], Florida"

---

*This document drives the Pest Pro website rebuild — reference before every build decision.*
