# Pro-Dent Club — Welcome Email Template

**Version:** 1.0.0
**Date:** July 21, 2026
**Author:** Pro-Dent Club Team
**Type:** HTML Email Template

---

## Overview

This repository contains the official HTML email template for **Pro-Dent Club**, Canada's #1 fastest-growing dental Group Purchasing Organization (GPO). The template is designed as a welcome email sent to newly onboarded dental clinic partners.

---

## Template Features

- **Single-file architecture** — all styles and content are contained within `index.html`
- **Email client compatible** — built with table-based layout following best practices for Gmail, Outlook, Apple Mail, and mobile clients
- **Responsive design** — adapts gracefully to mobile screen widths (≤600px)
- **Inline SVG icons** — no external icon hosting; icons are embedded directly in HTML
- **MSO (Outlook) conditional comments** — ensures correct rendering in Microsoft Outlook Desktop
- **Preheader text** — hidden preview text optimized for inbox display

---

## Color Palette

| Role | Color | Hex Code |
|------|-------|----------|
| Dark Espresso Brown | Primary Dark | `#2B1B17` |
| Warm Bronze Gold | Accent / Badge | `#A06828` |
| Soft Cream | Card Background | `#F4ECE1` |
| Warm Skin | Page Background | `#F6F1EA` |
| Medium Brown | Body Text | `#5D4C46` |
| Off-White | Icon Stroke | `#F6F1EA` |

---

## Typography

| Font | Usage | Source |
|------|-------|--------|
| `Georgia, serif` | Headings, signature | System font |
| `Dancing Script` | Cursive closing signature | Google Fonts |
| `Encode Sans` | Body text, closing | Google Fonts |
| `Roboto` | Section labels, descriptions | Google Fonts |
| `Inter` | Badges, footer, meta text | Google Fonts |

---

## Template Sections

1. **Header** — Logo + promotional star badge (top-right corner)
2. **Welcome Title** — `Welcome to Pro-Dent Club!`
3. **Opening Text** — Brief GPO value proposition
4. **Your Membership Includes** — Benefit cards with circular SVG icons:
   - Vendor Partner Page
   - Free CE Courses
   - Tools Page
5. **Vendor Outreach Block** — Dark brown segmented section
6. **Sign-Off** — Warm regards + cursive signature + team title
7. **Footer** — Copyright & unsubscribe link

---

## File Structure

```
pro-dent/
├── index.html          # Main email template (single file)
└── README.md           # Project documentation
```

---

## Usage

1. Open `index.html` in any browser to preview the template.
2. Copy the full HTML content and paste it into your email service provider (ESP) such as Mailchimp, HubSpot, or Klaviyo.
3. Replace placeholder `href="#"` links with actual destination URLs before sending.

---

## Links to Update Before Sending

| Element | Location | Action Required |
|---------|----------|-----------------|
| Vendor Partner Page button | Section 1, Item 1 | Add live URL |
| Free CE Courses button | Section 1, Item 2 | Add live URL |
| Tools Page button | Section 1, Item 3 | Add live URL |
| Unsubscribe link | Footer | Add unsubscribe URL |

---

## Browser & Client Compatibility

| Client | Status |
|--------|--------|
| Gmail (Web) | ✅ Supported |
| Outlook 2016–2021 | ✅ Supported (MSO fallback included) |
| Apple Mail | ✅ Supported |
| iOS Mail | ✅ Supported |
| Android Gmail | ✅ Supported |
| Samsung Mail | ✅ Supported |

---

## Notes

- SVG icons are inline and do not rely on external image hosting.
- `Dancing Script` cursive font will fall back to `Georgia, serif` in email clients that block Google Fonts (e.g., Outlook Desktop).
- The `border-radius` on the main container may not render in Outlook Desktop; the MSO conditional table wrapper ensures structural integrity.

---

## License

© 2026 Pro-Dent Club. All rights reserved.
This template is proprietary and intended for internal use by the Pro-Dent Club marketing team only.
