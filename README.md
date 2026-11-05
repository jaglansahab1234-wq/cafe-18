# Aura & Bean — Artisanal Specialty Coffeehouse

[![License: MIT](https://img.shields.io/badge/License-MIT-C86D51.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A modern, immersive, fully responsive frontend for **Aura & Bean**, an artisanal specialty coffeehouse and micro-roastery based in **Sector 14, Sonipat, Haryana**.

Designed with an earthy luxury visual aesthetic, smooth glassmorphism, responsive micro-interactions, an interactive ordering drawer, table reservations, live sanctuary hours, and a full asymmetric bento gallery.

---

## ☕ Key Features

- **Earthy Luxury Design System**:
  - Warm cream background (`#F9F6F0`)
  - Deep dark roast primary (`#1A1816`)
  - Accent terracotta/rust (`#C86D51`)
  - Soft sage green badges (`#879A78`)
  - Crisp white elevated cards (`#FFFFFF`)
  - Display serif typography (*Playfair Display*) paired with clean body sans-serif (*Plus Jakarta Sans*).
- **Sticky Glassmorphic Navigation & Mobile Drawer**:
  - Live sanctuary opening hours badge (dynamically calculates open/close status).
  - Smooth-scrolling anchor links.
  - Cart button with live counter badge.
  - Mobile off-canvas slide-out drawer with gesture-friendly navigation.
- **Cinematic Full-Viewport Hero**:
  - Slow ambient zoom visual of pour-over extraction.
  - Editorial typography with dual CTAs ("Explore Menu" & "Book a Table").
  - Sensorial micro-badges for fair trade, micro-batch roasts, and SCA 88+ cupping.
- **Interactive Menu Section**:
  - Tab switcher: *All, Specialty Coffee, Artisanal Teas, Fresh Pastries, Breakfast / Brunch*.
  - Dietary filter pills: *Organic, Vegan Option, Gluten-Free*.
  - Rich cards with pricing, roast notes, and quick action "Add to Order".
  - Clickable item quick-view modal with origin altitudes and brewing technique.
- **Story & Craft ("Our Craft & Beans")**:
  - Direct trade transparency highlights (compensating up to 300% above Fair Trade minimums).
  - Four key metric counters (100% Direct Trade, 88+ SCA Cupping, 3 Seasonal Rotations, Zero Net Carbon).
  - Interactive Roast Profile visual scale with switchable flavor notes.
- **Asymmetric Bento Gallery with Lightbox**:
  - High-res photography of cafe interior, latte art microfoam, vintage Diedrich cast iron roaster, reading nook, and community cupping workshops.
  - Interactive lightbox viewer with image enlargement and editorial caption.
- **Customer Reviews Carousel**:
  - Auto-playing reviews carousel with pause-on-hover.
  - Verified local patrons from Ashoka University and O.P. Jindal hub.
  - Prev/Next controls and dot pagination indicators.
- **Location & Operational Hours**:
  - Sonipat, Haryana physical address (Plot 42, Sector 14).
  - Highlighted current day's operational hours.
  - Interactive map card with stylized pin and Google Maps direction links.
  - "Join the Coffee Circle" newsletter subscription with live toast feedback.
- **Interactive Modals & Drawers**:
  - **Slide-Over Cart Drawer**: Quantity adjustment (+/-), subtotal and local tax calculations, service mode toggles (*Dine-in / Takeaway / Curbside*), and simulated checkout receipt modal.
  - **Table Reservation Modal**: Date, time slot, guest count, atmosphere selector (*Sunlit Window Nook, Barista Brew Bar, Quiet Courtyard, Library Harvest Table*), and instant confirmation token.
  - **Non-blocking Toast Engine**: Instant feedback for cart additions, bookings, and newsletter subscriptions.

---

## 📁 Repository Structure

```
.
├── index.html       # Primary entrypoint for GitHub Pages / Web servers
├── code.html        # Modular source template
├── DESIGN.md        # Design system specifications & token dictionary
├── screen.png       # UI aesthetic benchmark preview
└── README.md        # Project documentation
```

---

## 🚀 Quick Start / Local Preview

You can open `index.html` directly in any web browser without any build tools:

```bash
# Clone the repository
git clone https://github.com/jaglansahab1234-wq/cafe-18.git

# Navigate into the project directory
cd cafe-18

# Open in default browser (Windows)
start index.html

# Or run with a local HTTP server (optional)
npx serve .
# or
python -m http.server 8080
```

---

## 🎨 Palette Reference

| Token | Hex | Role |
| :--- | :--- | :--- |
| **Primary** | `#1A1816` | Deep Dark Roast Background / Text |
| **Cream** | `#F9F6F0` | Warm Earthy Canvas |
| **Terracotta** | `#C86D51` | Accent Buttons, Links & Active Highlights |
| **Sage** | `#879A78` | Organic / Natural Micro-Badges |
| **Surface** | `#FFFFFF` | Elevated Card Containers |
| **Border** | `#E8E2D8` | Soft Muted Outlines |

---

## 📜 License

Created for **Aura & Bean Specialty Coffee Roasters**. Open source under the [MIT License](LICENSE).
