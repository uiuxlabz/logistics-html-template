# LOGISTICA — Logistics Template

**Moving the World, On Time.**

A premium, framework-free logistics and supply chain template built with semantic HTML, modern CSS custom properties, and vanilla JavaScript. Designed for freight forwarders, logistics companies, and supply chain providers that demand a professional, conversion-focused web presence.

---

## Live Pages

| Page | Description |
|------|-------------|
| [Home](index.html) | Full-screen hero with animated stats, service cards, real-time shipment tracking demo, testimonials, and CTA |
| [About](about.html) | Company story, mission and vision, core values grid, leadership team, fleet infrastructure stats |
| [Services](services.html) | Six detailed service showcases: Air Freight, Ocean Freight, Road Freight, Warehousing, Customs Clearance, Supply Chain Consulting |
| [Contact](contact.html) | Multi-field quote request form with validation, contact info cards, embedded map, and shipment tracking widget |

---

## Brand Identity

- **Primary:** Orange `#F97316` — energy, urgency, action
- **Secondary:** Navy `#1E293B` — trust, professionalism, stability
- **Dark:** `#0F172A` — depth, premium feel
- **Typography:** Barlow (headings) + Inter (body) via Google Fonts
- **Icons:** Font Awesome 6.5.1 via CDN

---

## Features

- **Zero dependencies** — no build tools, no frameworks, no npm
- **Responsive design** — mobile-first with breakpoints at 720px and 980px
- **Scroll animations** — IntersectionObserver-based reveal, stagger, and slide effects with reduced-motion support
- **Animated counters** — statistics count up when they enter the viewport
- **Interactive tracking demo** — simulate shipment tracking with animated progress steps
- **Contact form** — client-side validation with success/error status messages
- **Newsletter form** — email subscription in footer
- **Mobile navigation** — burger menu with overlay, smooth transitions
- **Back-to-top button** — appears after scrolling, smooth scroll to top
- **Header scroll effect** — shadow added on scroll for depth
- **Active nav highlighting** — current page automatically marked in navigation

---

## File Structure

```
logistics-html-template/
  index.html              Home page
  about.html              About / company page
  services.html           Services detail page
  contact.html            Contact / quote request page
  README.md               This file
  assets/
    css/
      style.css           Complete design system (1933 lines)
    js/
      main.js             All interactive behaviors (399 lines)
    img/
      carousel-1.jpg      Hero background
      carousel-2.jpg      Alternate hero
      about.jpg           About split image
      feature.jpg         Mission section image
      map.png             Contact page map
      service-1.jpg       Air freight
      service-2.jpg       Ocean freight
      service-3.jpg       Road freight
      service-4.jpg       Warehousing
      service-5.jpg       Customs clearance
      service-6.jpg       Supply chain consulting
```

---

## CSS Architecture

The stylesheet uses a custom properties system organized into clear sections:

- **Custom Properties** — colors, typography, spacing, shadows, transitions
- **Reset & Base** — clean slate with consistent defaults
- **Typography** — heading scale, text utilities, color helpers
- **Layout** — container, grid system, flex utilities
- **Buttons** — primary, outline, dark, arrow variants with hover states
- **Header/Nav** — fixed header with glassmorphism, mobile burger
- **Hero** — full-viewport hero with overlay gradient
- **Page Hero** — inner page banners with breadcrumb navigation
- **Split Layout** — two-column image + text sections
- **Services** — card grid and detailed alternating service blocks
- **Stats** — dark background counter section
- **Tracking** — shipment tracker with step progress
- **Testimonials** — client review cards
- **CTA** — gradient call-to-action with decorative circles
- **Contact** — form, info cards, map
- **Footer** — four-column grid with newsletter
- **Values / Team / Fleet** — about page specialized components
- **Reveal Animations** — fade, slide, scale, stagger with reduced-motion
- **Responsive** — two breakpoints for tablet and mobile

---

## JavaScript Capabilities

All JavaScript is framework-free vanilla ES5-compatible code inside a single IIFE:

- **Burger navigation** — toggle mobile menu with body scroll lock
- **Active nav detection** — highlights current page link
- **Header scroll** — adds `.scrolled` class for shadow effect
- **Back to top** — show/hide button, smooth scroll
- **Year auto-fill** — `[data-year]` elements updated automatically
- **Scroll reveal** — IntersectionObserver triggers `.revealed` class
- **Counter animation** — eased count-up with cubic timing
- **Tracking form** — simulates lookup, animates progress steps
- **Contact/quote form** — validation, loading state, success message
- **Newsletter** — email validation on submit
- **Smooth scroll** — anchor links offset for fixed header
- **Lazy loading** — native `loading="lazy"` with fallback

---

## Usage

1. Open any `.html` file directly in a browser — no server required
2. Replace images in `assets/img/` with your own photography
3. Edit text content, contact details, and service descriptions in the HTML files
4. Customize colors by changing CSS custom properties in `:root`
5. Add or remove service cards, testimonials, or team members by duplicating existing card markup

---

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile Safari / Chrome on iOS and Android

---

## License

Custom template built for LOGISTICA. Free to use and modify.
