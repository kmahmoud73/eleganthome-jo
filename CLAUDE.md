# البيت الأنيق | The Elegant Home

**Created**: March 10, 2026
**Last Updated**: March 10, 2026 — Full site build complete

---

## Project Overview

Premium Arabic-first website for **Bahjat**, a master builder / construction & maintenance contractor in Amman, Jordan.

**Brand**: البيت الأنيق | The Elegant Home
**Phone**: 0799715150
**Location**: Amman, Jordan

## Files

| File | Purpose | Status |
|------|---------|--------|
| `index.html` | Full single-page site — multilingual AR/EN, RTL/LTR toggle, services tabs, quote form, contact form | Complete |
| `BRAND_IDENTITY.md` | Brand identity doc (colors, typography, voice, style) | Complete |
| `BRAND_NAME_OPTIONS.md` | 10 brand name options with analysis (final pick: البيت الأنيق) | Complete |
| `images/hero.jpg` | Leonardo AI — luxury Jordanian villa exterior, golden hour | Generated |
| `images/interior.jpg` | Leonardo AI — premium Jordanian home interior | Generated |
| `images/craftsmanship.jpg` | Leonardo AI — master craftsman hands on stone | Generated |
| `images/logo_1.png` | Logo option 1 — house + triple Gothic arch in gold | Generated |
| `images/logo_2.png` | Logo option 2 — clean house + Islamic arch in gold — **PRIMARY** | Generated |

## Tech Stack

- Single HTML file (no framework, no build step)
- Vanilla CSS + JS
- Google Fonts (Noto Naskh Arabic, Noto Sans Arabic, Cinzel, Jost)
- FormSubmit.co for form → email delivery
- Inline SVG icons (zero dependencies)

## Brand Palette

| Name | Hex |
|------|-----|
| Bahjat Black | `#1A1A2E` |
| Petra Gold | `#C8983D` |
| Sandstone | `#D4A574` |
| Marble White | `#FAF8F5` |
| Slate | `#2D2D3A` |

## Site Features

- Full bilingual AR/EN with one-click language toggle
- RTL/LTR auto-switching (layout, fonts, everything flips)
- 12 services with 5-tab category filtering (All, Build, Maintenance, Renovation, Cleaning)
- Quotation request form (name, phone, email, service type, budget, location, details)
- Contact form (name, phone, message)
- WhatsApp direct link (wa.me/962799715150)
- Scroll-triggered fade-up animations (IntersectionObserver)
- Mobile responsive (375px+)
- Smooth scroll navigation
- Toast notifications on form submit

## Decisions Made

- **Brand name**: البيت الأنيق | The Elegant Home (owner's choice)
- **Logo**: Option 2 (clean house + Islamic arch) selected as primary
- **Forms**: Using FormSubmit.co (free, no backend needed, delivers to Gmail)
- **Reference site**: tem-servic.com used for services data/content structure

## TODO

- [ ] **Get Bahjat's Gmail** — replace `BAHJAT_EMAIL@gmail.com` in both form actions
- [ ] Replace AI images with real project photos when available
- [ ] Add more gallery items from real projects
- [ ] Domain setup and hosting
- [ ] Git init + push to GitHub
