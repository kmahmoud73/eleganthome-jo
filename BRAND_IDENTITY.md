# BAHJAT | بهجت — Brand Identity

**Master Builder | Jordan**
*"We don't just build. We build joy."*

---

## 1. Brand Name Treatment

| Language | Name | Tagline |
|----------|------|---------|
| **Arabic (Primary)** | **بهجت** | نبني الفرح — "We Build Joy" |
| **English** | **BAHJAT** | Master Builder \| Jordan |

- Arabic always leads — displayed larger, bolder, right-aligned
- English sits underneath or to the left as secondary
- The name "بهجت" (Bahjat) means "joy / delight" — the entire brand story pivots on this: building is not just concrete — it's building someone's dream, their joy

---

## 2. Color Palette

A Jordanian-rooted palette: Petra's golden sandstone, the authority of basalt, the warmth of desert twilight.

| Name | Hex | RGB | Role |
|------|-----|-----|------|
| **Bahjat Black** | `#1A1A2E` | 26, 26, 46 | Primary — headers, nav, authority |
| **Petra Gold** | `#C8983D` | 200, 152, 61 | Accent / CTA — buttons, highlights, premium touch |
| **Sandstone** | `#D4A574` | 212, 165, 116 | Secondary — warm accents, dividers, hover states |
| **Marble White** | `#FAF8F5` | 250, 248, 245 | Background — clean, warm canvas |
| **Slate** | `#2D2D3A` | 45, 45, 58 | Body text — sophisticated readability |

### Gradient Signatures
```css
/* Hero gradient — desert sunset authority */
background: linear-gradient(135deg, #1A1A2E 0%, #2D2D3A 50%, #C8983D 100%);

/* Gold shimmer — CTA hover */
background: linear-gradient(90deg, #C8983D 0%, #D4A574 50%, #C8983D 100%);

/* Sandstone fade — section backgrounds */
background: linear-gradient(180deg, #FAF8F5 0%, #F0E6D8 100%);
```

---

## 3. Typography

### Arabic Fonts (Primary)
| Use | Font | Weight | Source |
|-----|------|--------|--------|
| **Headings** | **Noto Naskh Arabic** | 600–700 | Google Fonts |
| **Body** | **Noto Sans Arabic** | 300–500 | Google Fonts |

### Latin Fonts (Secondary)
| Use | Font | Weight | Source |
|-----|------|--------|--------|
| **Headings** | **Cinzel** | 500–700 | Google Fonts — monumental, architectural |
| **Body** | **Jost** | 300–500 | Google Fonts — geometric, clean |

### CSS Import
```css
@import url('https://fonts.googleapis.com/css2?family=Noto+Naskh+Arabic:wght@400;500;600;700&family=Noto+Sans+Arabic:wght@300;400;500;700&family=Cinzel:wght@400;500;600;700&family=Jost:wght@300;400;500;600;700&display=swap');
```

### Type Scale
| Element | Arabic | English | Size |
|---------|--------|---------|------|
| Hero Title | Noto Naskh Arabic 700 | Cinzel 700 | 48–72px |
| Section Title | Noto Naskh Arabic 600 | Cinzel 600 | 32–40px |
| Subtitle | Noto Sans Arabic 500 | Jost 500 | 20–24px |
| Body | Noto Sans Arabic 400 | Jost 400 | 16–18px |
| Caption | Noto Sans Arabic 300 | Jost 300 | 14px |

---

## 4. Logo Concept

### Primary Mark: The "بـ" Arch

The Arabic letter **بـ** (Ba) — the first letter of بهجت — is stylized into an **architectural arch**:

- The **curve of the Ba** becomes a grand arch (like Petra's Treasury doorway or a Jordanian stone arch)
- The **dot below** (نقطة) is rendered as a **golden cornerstone** — the foundational stone of every building
- Clean geometric lines — no excessive ornamentation
- The arch subtly frames negative space that suggests a **doorway** — welcoming, inviting, the threshold to your new home

### Lockup Variations
1. **Full lockup**: Arch mark + "بهجت" + "BAHJAT" + tagline
2. **Arabic only**: Arch mark + "بهجت" — for local marketing
3. **Icon only**: The Ba-arch mark alone — for favicons, app icons, stamps
4. **Horizontal**: Mark left + text right — for headers/nav

### Color Applications
- **On dark backgrounds**: Gold arch (#C8983D) + white text
- **On light backgrounds**: Bahjat Black arch (#1A1A2E) + gold dot
- **Monochrome**: All black or all white for print/stamps

---

## 5. Visual Style Direction

### Design Language: "Monumental Minimalism"

The intersection of **Jordanian architectural heritage** and **modern premium minimalism**. Clean, bold, authoritative — but warm.

### Key Visual Principles

| Principle | Execution |
|-----------|-----------|
| **Bold Geometry** | Strong grid, sharp angles, architectural framing |
| **Warm Materiality** | Textures of stone, concrete, sandstone — not cold corporate |
| **Generous White Space** | Let the work breathe — premium = space |
| **Photography Forward** | Large, high-quality project photos are the hero |
| **Gold as Punctuation** | Gold is used sparingly — on CTAs, dividers, key accents. Never overused |
| **RTL-First Layout** | Right-to-left reading flow as default. Every layout conceived in Arabic first |

### Photography Style
- **Hero shots**: Completed projects at golden hour (warm, dramatic)
- **Process shots**: Workers at work — human, honest, skillful
- **Detail shots**: Close-ups of craftsmanship — tile work, stone finish, ironwork
- **Before/After**: Split reveals showing transformation
- **Always**: Natural light, warm tones, slightly desaturated for premium feel

### Patterns & Textures
- Subtle **concrete/stone texture** overlays on dark sections
- **Geometric Islamic patterns** as section dividers (not ornamental — structural)
- **Blueprint line art** as background elements in service sections

### Iconography
- Custom SVG icons — **line style**, 2px stroke, rounded joins
- Architectural/construction themed (hammer, level, ruler, hard hat, house, wrench)
- Always in Petra Gold (#C8983D) or Bahjat Black (#1A1A2E)

---

## 6. Brand Voice & Tone

### Voice: The Master Builder Speaks

| Attribute | How It Sounds |
|-----------|--------------|
| **Authoritative** | "30 years of building Amman's finest homes" — not "we try our best" |
| **Warm** | "Your home is your joy — we protect that" — not cold/corporate |
| **Direct** | "Call now: 0799715150" — no fluff, no filler |
| **Proud** | "Every wall we raise carries our name" — craftsman's pride |
| **Jordanian** | Speaks like a Jordanian — not formal MSA, not slang. Dignified local Arabic |

### Tone by Context

| Context | Tone | Example |
|---------|------|---------|
| **Hero / Headlines** | Bold, aspirational | نبني أحلامكم — حجر حجر |
| **Service Descriptions** | Clear, confident | صيانة شاملة — كهرباء، سباكة، دهان، بلاط |
| **Testimonials** | Warm, personal | "بهجت حوّل بيتنا القديم لقصر" |
| **CTA** | Direct, urgent | اتصل الآن — 0799715150 |

---

## 7. Contact

| Channel | Value |
|---------|-------|
| **Phone** | 0799715150 |
| **Location** | Amman, Jordan |

---

## 8. Services (from reference data)

Based on the reference site, Bahjat offers:

### Core Services
- ترميم وصيانة منازل — Home renovation & maintenance
- أعمال كهرباء — Electrical work
- أعمال سباكة — Plumbing
- دهان وديكورات — Painting & decor
- بلاط وسيراميك — Tiling & ceramics
- عزل مائي وحراري — Waterproofing & insulation
- معالجة تشققات — Crack repair & structural work
- بناء وتشطيبات — Construction & finishing

### Additional Services
- نقل أثاث — Furniture moving
- تنظيف شامل — Deep cleaning
- مكافحة حشرات — Pest control
- صيانة مكيفات — AC maintenance

---

*Brand Identity v1.0 — Created March 10, 2026*
*For: Bahjat Master Builder, Amman, Jordan*
