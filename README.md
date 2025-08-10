
---

## Brand & Design

**Palette**
- Primary (eggplant): `#1e0930`
- Accent (gold): `#d2941f`
- Paper/light: `#eee2cf`
- Complement (blue): `#1f5dd2`
- Hot (pink): `#FF4FB7`

**Logo**
- Path: `/assets/logo-full.png`  
- Do not modify, stretch, recolor, or place on busy backgrounds.

---

## Copyright & Trademark Notice

© **2025–Present E-MAZING Commerce Group. All rights reserved.**

E-MAZING Commerce Group™, E-MAZING™, “Digital Redefined,” and associated logos, marks, and trade dress are trademarks of E-MAZING Commerce Group (some marks may be pending registration).  
All other trademarks are the property of their respective owners.

**Usage policy**
- No reproduction, redistribution, sublicensing, or use of brand assets without prior written permission.
- The contents of `/assets/` are proprietary unless a file includes its own license header.
- Code in this repository is provided for the company’s website operation and is **not** open-source unless a LICENSE file states otherwise.

---

## Accessibility

Built with semantic HTML, keyboard-focus states, reduced-motion safety, and color-contrast targets intended to meet WCAG 2.1 AA where feasible. Please report any issues (see Contact).

---

## Analytics (optional)

The template includes commented GA4 hooks for email and booking clicks.  
To enable:
1. Add your GA4 snippet with Measurement ID in `index.html`.
2. Uncomment the event listeners for `email_click` and `book_intro_click`.

---

## Deployment

This site is static and compatible with hosts like **Cloudflare Pages**, **GitHub Pages**, Netlify, or any S3/CDN.

**Cache busting:** when updating `styles.css`, append a version query in the HTML once, e.g.:
```html
<link rel="stylesheet" href="styles.css?v=2025-08-10">
