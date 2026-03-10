# 🐄 Alheri Cattle Multi-Purpose Co-operative Society Ltd. — Website

![Society Banner](https://img.shields.io/badge/Alheri%20Cattle%20Co--operative-Website-green?style=for-the-badge&logo=leaf)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Live Preview](#-live-preview)
- [Society Information](#-society-information)
- [Features](#-features)
- [Pages & Sections](#-pages--sections)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customization Guide](#-customization-guide)
- [Design System](#-design-system)
- [Responsive Design](#-responsive-design)
- [JavaScript Functionality](#-javascript-functionality)
- [SEO & Accessibility](#-seo--accessibility)
- [Deployment Guide](#-deployment-guide)
- [Contributing](#-contributing)
- [Contact & Support](#-contact--support)
- [License](#-license)

---

## 🌍 Overview

This is the **official website** for **Alheri Cattle Multi-Purpose Co-operative Society Limited (ACMPCSL)** — a registered agricultural co-operative society based in Jalingo, Taraba State, Nigeria.

The website is built as a **single-file, pure HTML/CSS/JavaScript** application with no external frameworks or dependencies beyond Google Fonts. It delivers a fast, modern, fully responsive multi-page experience simulated through JavaScript-powered page toggling.

The site was designed to serve as a digital presence for the co-operative, enabling:
- Public awareness of the society's mission and services
- Member recruitment and online inquiry submission
- Transparent display of membership tiers and pricing
- Easy access to contact and location information

---

## 🔗 Live Preview

> Open `index.html` directly in any modern web browser — no server required.

```bash
# Simply double-click the file, or open via terminal:
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

---

## 🏢 Society Information

| Detail | Information |
|---|---|
| **Society Name** | Alheri Cattle Multi-Purpose Co-operative Society Ltd. |
| **Short Name** | ACMPCSL |
| **Type** | Multi-Purpose Agricultural Co-operative |
| **Address** | No. Gombe Street, Turaki A' Ward, Jalingo, Taraba State, Nigeria |
| **Email** | alihericattlefatteningmultipur@gmail.com |
| **State** | Taraba State |
| **LGA** | Jalingo Local Government Area |
| **Registration** | Registered under Nigerian Co-operative Societies Law, Taraba State |
| **Office Hours** | Monday – Friday: 8:00am – 5:00pm · Saturday: 9:00am – 1:00pm |

---

## ✨ Features

### 🎨 Design & UI
- **Earthy, nature-inspired colour palette** — deep greens, golden wheat tones, and warm cream backgrounds
- **Playfair Display serif** headings paired with **Lato sans-serif** body text for a refined editorial feel
- **Smooth scroll reveal animations** — elements fade and slide into view as the user scrolls
- **Animated hero emblem** with rotating dashed ring effect
- **Marquee scrolling strip** displaying all key services on a loop
- **Hover micro-interactions** on all cards, buttons, and navigation links
- **Sticky navigation bar** with scroll-aware active link highlighting
- **Gradient mesh backgrounds** and subtle grid overlays for visual depth

### ⚙️ Functionality
- **Multi-page SPA simulation** — Home, About, Services, and Contact pages with smooth transitions
- **Animated stat counters** — numbers count up on page load for visual impact
- **Interactive FAQ accordion** — click to expand/collapse answers
- **Working contact form** with loading state and success confirmation message
- **Mobile hamburger menu** for screens under 640px
- **Scroll reveal observer** using Intersection Observer API for performance

### 📱 Responsiveness
- Fully responsive across desktop, tablet, and mobile devices
- Grid layouts collapse gracefully at breakpoints (900px, 640px)
- Navigation transforms to a hamburger menu on mobile
- Typography scales fluidly using `clamp()` for all headings

---

## 📄 Pages & Sections

### 🏠 Home Page (`#page-home`)

| Section | Description |
|---|---|
| **Hero Banner** | Full-viewport hero with society name, tagline, animated emblem, and CTA buttons |
| **Animated Statistics** | 4 live-counting stats: Members, Cattle Fattened, Years of Service, LGAs Covered |
| **Marquee Strip** | Continuously scrolling banner listing all major service offerings |
| **Features Grid** | 6 cards highlighting core benefits: Co-op Structure, Finance, Fattening, Sustainability, Veterinary, Markets |
| **Testimonials** | 3 member testimonial cards with author avatars and roles |
| **CTA Banner** | Full-width call-to-action encouraging visitors to join the society |

---

### 📖 About Page (`#page-about`)

| Section | Description |
|---|---|
| **Page Hero** | Dark gradient banner with page title and descriptive subtitle |
| **Society Story** | 4-paragraph narrative covering founding, mission, co-operative principles, and multi-purpose scope |
| **Core Values Grid** | 4 value cards: Mission, Vision, Integrity, Sustainability |
| **Impact Cards** | 4 quick-stat cards: Registered Society, Taraba-Based, Multi-Purpose, Credit Access |
| **Featured Card** | Highlighted card summarising agricultural impact achievements |
| **Leadership Section** | 3 board member profile cards: Chairman, Secretary General, Treasurer |
| **Join CTA** | Outro call-to-action linking to Contact page |

---

### ⚙️ Services Page (`#page-services`)

| Section | Description |
|---|---|
| **Page Hero** | Dark header introducing the services overview |
| **Services Grid (2-col)** | 6 detailed service cards, each with coloured header, description, and feature checklist |
| **Membership Pricing** | 3-tier pricing table on dark earth background: Basic (₦5,000), Full (₦15,000), Corporate (₦50,000) |

**Service Cards included:**

1. 🐄 **Cattle Fattening Program** — Feeding protocols, health monitoring, group fattening
2. 💰 **Agricultural Finance & Loans** — Low-interest loans, seasonal credit, savings, dividends
3. 🏥 **Veterinary & Health Services** — Farm visits, vaccination, deworming, AI services
4. 🛒 **Market Linkage & Trade** — Direct buyer matching, collective bargaining, transport
5. 🌱 **Input Supply & Equipment** — Feeds, medicines, farm tools, bulk pricing
6. 📚 **Training & Capacity Building** — Workshops, record-keeping, youth & women programs

---

### 📞 Contact Page (`#page-contact`)

| Section | Description |
|---|---|
| **Page Hero** | Gradient header with contact page introduction |
| **Contact Info Card** | Dark card with address, email, office hours, and registration details |
| **Contact Form** | Full inquiry form: name, phone, email, subject dropdown, LGA, message |
| **Form Success State** | Animated confirmation message shown after form submission |
| **Map Placeholder** | Branded location card with grid overlay and animated pin |
| **FAQ Accordion** | 5 collapsible frequently asked questions with smooth animation |

---

## 🛠 Tech Stack

| Technology | Usage | Version |
|---|---|---|
| **HTML5** | Page structure and semantic markup | HTML5 |
| **CSS3** | All styling, animations, layout, and responsiveness | CSS3 |
| **Vanilla JavaScript** | Page routing, counters, FAQ, form handling, scroll reveal | ES6+ |
| **Google Fonts** | Typography — Playfair Display, Lato, Merriweather | Latest |
| **CSS Grid & Flexbox** | Responsive multi-column layouts | Native |
| **Intersection Observer API** | Scroll-triggered reveal animations | Native |
| **CSS Custom Properties** | Design token system (colours, spacing) | Native |
| **CSS Animations & Keyframes** | Hero animations, marquee, bounce, rotate | Native |

> ⚡ **Zero dependencies** — No npm, no build tools, no frameworks. Just open the HTML file.

---

## 📁 Project Structure

```
alheri-cooperative-website/
│
├── index.html              # Single-file application (all HTML, CSS, JS)
├── README.md               # This documentation file
│
└── assets/                 # (Optional — for future expansion)
    ├── images/
    │   ├── logo.png
    │   ├── hero-bg.jpg
    │   └── team/
    ├── docs/
    │   ├── membership-form.pdf
    │   └── annual-report.pdf
    └── favicon.ico
```

> The current implementation is fully self-contained in `index.html`. Assets can be added as the site grows.

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- A text editor for customisation (VS Code recommended)

### Installation

**Step 1 — Clone or Download the repository**
```bash
git clone https://github.com/your-username/alheri-cooperative-website.git
cd alheri-cooperative-website
```

**Step 2 — Open the website**
```bash
# Option A: Open directly in browser
open index.html

# Option B: Use a local development server (recommended)
npx serve .
# OR
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

**Step 3 — Customise as needed** *(see Customisation Guide below)*

---

## 🎨 Customization Guide

### Updating Society Information

All contact details and society information are hardcoded in the HTML. Search and replace the following values:

| Find (current value) | Replace with |
|---|---|
| `Alheri Cattle Multi-Purpose Co-operative Society` | Your society name |
| `No. Gombe Street, Turaki A' Ward` | Your street address |
| `Jalingo, Taraba State` | Your city and state |
| `alihericattlefatteningmultipur@gmail.com` | Your email address |
| `08012345678` | Your phone number |

---

### Changing Colours

All colours are defined as **CSS custom properties** (variables) in the `:root` block at the top of the `<style>` section. Edit these to change the entire site's colour scheme:

```css
:root {
  --earth:       #2d1a0e;   /* Darkest brown — primary text, nav bg */
  --soil:        #5c3a1e;   /* Medium brown — body text */
  --clay:        #8b5e3c;   /* Light brown */
  --wheat:       #c8a96e;   /* Warm tan */
  --golden:      #d4a843;   /* Gold accent — headings, highlights */
  --hay:         #e8d5a3;   /* Light straw — secondary text on dark */
  --cream:       #faf6ee;   /* Off-white background */
  --green-deep:  #1a3a1a;   /* Darkest green */
  --green-mid:   #2d5a27;   /* Mid green — buttons, cards */
  --green-light: #4a8c3f;   /* Light green — accents, labels */
  --green-pale:  #7ab870;   /* Pale green */
  --sky:         #e8f4ea;   /* Very light green — testimonials bg */
}
```

---

### Updating Statistics

The animated counters on the homepage are configured in the `runCounters()` JavaScript function:

```javascript
const targets = [
  { id: 'count1', end: 350,  suffix: '+' },   // Active Members
  { id: 'count2', end: 2800, suffix: '+' },   // Cattle Fattened
  { id: 'count3', end: 8,    suffix: '+' },   // Years of Service
  { id: 'count4', end: 12,   suffix: '' },    // LGAs Covered
];
```

Change the `end` values to match your actual statistics.

---

### Updating FAQ Content

The FAQ questions and answers are stored in the `faqs` array in JavaScript:

```javascript
const faqs = [
  {
    q: "Your question here?",
    a: "Your detailed answer here."
  },
  // Add more entries as needed...
];
```

---

### Updating Membership Pricing

Pricing cards are in the **Services page** HTML section inside `#page-services`. Locate the `.pricing-card` elements and update the `₦` amounts and perk lists directly in the HTML.

---

### Adding a Real Phone Number

Search for the phone number placeholder in the contact info card and the footer, and replace with your actual number:

```html
<!-- In the contact info card, add a new .contact-info-item block: -->
<div class="contact-info-item">
  <div class="contact-info-icon">📞</div>
  <div>
    <div class="contact-info-label">Phone Number</div>
    <div class="contact-info-value">+234 801 234 5678</div>
  </div>
</div>
```

---

### Adding a Real Google Map

Replace the `.map-placeholder` div in the Contact page with an embedded Google Maps iframe:

```html
<div style="border-radius:16px;overflow:hidden;margin-top:2rem;border:3px solid rgba(212,168,67,0.2);">
  <iframe
    src="https://www.google.com/maps/embed?pb=YOUR_EMBED_URL_HERE"
    width="100%"
    height="350"
    style="border:0;"
    allowfullscreen=""
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>
```

> Get your embed URL from **Google Maps → Share → Embed a map**.

---

### Connecting the Contact Form

The form currently simulates submission. To make it functional, integrate a form service. Here are two options:

**Option A — Formspree (Free, no backend needed):**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- existing form fields -->
</form>
```

**Option B — EmailJS (Send email directly from JS):**
```javascript
// Replace the handleSubmit function with:
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', e.target)
  .then(() => { /* show success */ })
  .catch(() => { /* show error */ });
```

---

## 🎨 Design System

### Typography

| Role | Font | Weight | Usage |
|---|---|---|---|
| Display / Headings | Playfair Display (Serif) | 700, 900 | Section titles, hero text, card titles |
| Body | Lato (Sans-serif) | 300, 400, 700 | Navigation, buttons, captions, UI labels |
| Descriptive | Merriweather (Serif) | 300, italic | Paragraph text, descriptions, testimonials |

### Colour Usage

| Token | Hex | Role |
|---|---|---|
| `--golden` | `#d4a843` | Primary accent — headings, highlights, badges |
| `--green-mid` | `#2d5a27` | Primary action — buttons, icons, cards |
| `--earth` | `#2d1a0e` | Navigation background, darkest UI |
| `--cream` | `#faf6ee` | Primary page background |
| `--hay` | `#e8d5a3` | Secondary text on dark backgrounds |

### Spacing Scale
The site uses a consistent spacing rhythm based on `rem` units, with section padding at `6rem 0` and card padding at `2.5rem`.

### Button Variants

| Class | Style | Usage |
|---|---|---|
| `.btn-primary` | Golden fill, dark text | Primary calls to action |
| `.btn-outline` | Transparent, white border | Secondary CTAs on dark backgrounds |
| `.nav-cta` | Golden nav button | "Contact Us" nav item |
| `.form-submit` | Dark green gradient | Form submission |

---

## 📱 Responsive Design

The website uses **CSS Grid** and **Flexbox** with the following breakpoints:

| Breakpoint | Target Devices | Layout Changes |
|---|---|---|
| `> 900px` | Desktop & large tablets | Full multi-column layouts |
| `≤ 900px` | Tablets & small laptops | 2-column → 1-column grids; hero stacks vertically |
| `≤ 640px` | Mobile phones | Hamburger menu; all grids go single-column; buttons stack |

### Mobile-Specific Adjustments
- Navigation collapses to a hamburger toggle menu
- Hero visual emblem hidden on mobile (text-only hero)
- Stats row wraps to 2×2 grid
- Buttons stack vertically
- Contact grid stacks vertically (info card above form)
- Footer grid becomes single column

---

## ⚙️ JavaScript Functionality

### `showPage(page)`
Handles SPA-style page navigation. Hides all `.page` elements, shows the target page, updates active nav link, scrolls to top, and re-initialises animations.

```javascript
showPage('home')      // Navigate to Home
showPage('about')     // Navigate to About
showPage('services')  // Navigate to Services
showPage('contact')   // Navigate to Contact
```

### `runCounters()`
Animates the four statistics on the homepage from 0 to their target values over ~1.5 seconds using `setInterval`. Triggered on initial load and whenever the home page is shown.

### `initReveal()`
Uses the **Intersection Observer API** to watch `.reveal` elements. When they enter the viewport, the `visible` class is added, triggering a CSS fade-up transition. Elements animate in with a staggered delay (80ms per element).

### `handleSubmit(event)`
Intercepts the contact form submission, prevents default browser behaviour, shows a loading state on the button, then after 1.8 seconds displays the `.form-success` confirmation and hides the form.

### `buildFAQ()`
Dynamically generates the FAQ accordion from the `faqs` data array. Each item gets a click listener that toggles `max-height` for smooth CSS-based expand/collapse animation.

### `toggleMenu()`
Toggles the `.open` class on `#navLinks` to show/hide the mobile navigation menu.

---

## 🔍 SEO & Accessibility

### Current SEO Features
- Semantic HTML5 elements (`<nav>`, `<section>`, `<footer>`, `<h1>–<h3>`)
- Descriptive page `<title>` tag
- `lang="en"` attribute on `<html>`
- Meaningful link text (no "click here" anchors)

### Recommended SEO Enhancements

Add these meta tags inside the `<head>` for better search engine visibility:

```html
<meta name="description" content="Alheri Cattle Multi-Purpose Co-operative Society Ltd — Empowering livestock farmers in Jalingo, Taraba State through cattle fattening, agricultural loans, veterinary support, and market linkage services.">
<meta name="keywords" content="cattle co-operative Taraba State, livestock farming Jalingo, agricultural loans Nigeria, cattle fattening Nigeria, Alheri cooperative society">
<meta name="author" content="Alheri Cattle Multi-Purpose Co-operative Society Ltd">

<!-- Open Graph (for social media sharing) -->
<meta property="og:title" content="Alheri Cattle Multi-Purpose Co-operative Society Ltd.">
<meta property="og:description" content="Empowering livestock farmers across Taraba State, Nigeria.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://your-website-url.com">

<!-- Favicon -->
<link rel="icon" href="assets/favicon.ico" type="image/x-icon">
```

### Accessibility Improvements to Consider
- Add `aria-label` attributes to icon-only buttons (social links)
- Add `alt` attributes to any future images
- Ensure colour contrast ratios meet WCAG AA standards
- Add `role="navigation"` and `aria-current="page"` to nav links

---

## 🌐 Deployment Guide

### Option 1 — GitHub Pages (Free)

```bash
# 1. Create a new GitHub repository
# 2. Push your files
git init
git add .
git commit -m "Initial commit — Alheri Co-operative website"
git remote add origin https://github.com/YOUR_USERNAME/alheri-cooperative.git
git push -u origin main

# 3. Go to Repository Settings → Pages → Source: main branch / root
# Your site will be live at: https://YOUR_USERNAME.github.io/alheri-cooperative
```

### Option 2 — Netlify (Free, Drag & Drop)

1. Visit [netlify.com](https://www.netlify.com) and sign up
2. From your dashboard, drag and drop your project folder into the deploy zone
3. Your site is live instantly with a `.netlify.app` subdomain
4. Optionally connect a custom domain (e.g., `alhericopeartive.com.ng`)

### Option 3 — cPanel / Shared Hosting

1. Log into your hosting control panel (cPanel)
2. Navigate to **File Manager → public_html**
3. Upload `index.html` (and any assets)
4. Your site is live at your domain

### Option 4 — Local Network Sharing

```bash
# Share on your local network using Python:
python3 -m http.server 8080
# Access from other devices at: http://YOUR_IP:8080
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. To contribute:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/add-gallery-section`
3. **Commit** your changes: `git commit -m "Add photo gallery section"`
4. **Push** to the branch: `git push origin feature/add-gallery-section`
5. **Open** a Pull Request with a clear description of changes

### Suggested Future Enhancements

- [ ] Add a **photo gallery** of farm activities and events
- [ ] Integrate **Google Maps embed** for real location display
- [ ] Build a **member portal** with login/dashboard
- [ ] Add a **news/announcements** blog section
- [ ] Connect the contact form to a live email service (Formspree / EmailJS)
- [ ] Add **WhatsApp floating button** for instant messaging
- [ ] Implement a **print-friendly** membership application form
- [ ] Add **Hausa language** translation toggle
- [ ] Integrate **Google Analytics** for visitor tracking
- [ ] Create a downloadable **annual report PDF** page

---

## 📬 Contact & Support

For questions about the website, customisation requests, or technical support:

**Society Contact:**
- 📍 No. Gombe Street, Turaki A' Ward, Jalingo, Taraba State, Nigeria
- ✉️ alihericattlefatteningmultipur@gmail.com
- 🕐 Office Hours: Monday–Friday, 8:00am–5:00pm

**Technical Issues:**
- Open an issue on the GitHub repository
- Or send an email with the subject line: `[Website] Your Issue Here`

---

## 📜 License

```
MIT License

Copyright (c) 2024 Alheri Cattle Multi-Purpose Co-operative Society Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

<div align="center">

**🐄 Alheri Cattle Multi-Purpose Co-operative Society Ltd.**

*Empowering Farmers · Building Prosperity · Growing Together*

No. Gombe Street, Turaki A' Ward, Jalingo, Taraba State, Nigeria

alihericattlefatteningmultipur@gmail.com

---

*Built with ❤️ for the agricultural community of Taraba State*

</div>
