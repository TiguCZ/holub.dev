# holub.dev — Design & Development Instructions

## Purpose

This website is a personal homepage.

It is **not** a portfolio, résumé, landing page or marketing website.

The goal is for visitors to quickly understand:

- who I am
- what I currently build
- where they can find me

Nothing more.

---

## Philosophy

Build something that still feels good ten years from now.

Choose simplicity over cleverness.

Choose readability over visual effects.

Choose maintainability over frameworks.

The design should feel calm, understated and intentional.

The overall aesthetic should be inspired by Apple's attention to typography and whitespace, **without attempting to imitate Apple's website**.

---

## Technology

The website must consist only of:

- HTML5
- CSS3
- SVG
- static assets

Do **not** use:

- build systems
- bundlers
- transpilers
- npm
- node.js
- frameworks
- Tailwind
- Bootstrap
- React
- Vue
- Astro
- Svelte

Opening `index.html` directly in a browser should render the website correctly.

Deploying the website should only require copying files to a web server.

No build step should ever be required.

---

## JavaScript

Prefer zero JavaScript.

If a feature can be implemented using HTML or CSS, do not use JavaScript.

Native HTML elements are preferred.

Examples:

- `<details>`
- `<dialog>` (if ever needed)
- anchor navigation
- CSS animations
- CSS variables

---

## HTML

Use semantic HTML.

Examples:

- header
- nav
- main
- section
- article
- footer

Accessibility is mandatory.

Use proper heading hierarchy.

Use alt text where appropriate.

Support keyboard navigation.

---

## CSS

Use modern CSS.

Prefer:

- CSS Variables
- Grid
- Flexbox
- clamp()
- min()
- max()

Support:

- prefers-color-scheme
- prefers-reduced-motion

Avoid browser-specific hacks whenever possible.

---

## Design language

Every page must share the same visual language.

The website should feel like a single coherent product.

Avoid visual inconsistency.

---

## Layout

Maximum content width:

760px

Centered layout.

Generous whitespace.

Spacing scale:

- 8
- 16
- 24
- 32
- 48
- 64
- 96

Use only these values.

---

## Typography

Font stack:

Inter,

system-ui,

sans-serif

Typography should carry the design.

Avoid decorative fonts.

Avoid excessive font weights.

---

## Colors

### Light

Background

#FFFFFF

Surface

#F5F5F7

Text

#1D1D1F

Secondary text

#6E6E73

Accent

#007AFF

### Dark

Background

#000000

Surface

#111111

Text

#F5F5F7

Secondary text

#A1A1A6

Accent

#0A84FF

---

## Components

Border radius:

16px

Shadows:

None or extremely subtle.

Buttons:

Simple.

No gradients.

No glossy effects.

No glassmorphism.

No neumorphism.

Cards should rely on spacing and typography rather than decoration.

---

## Animations

Keep animations subtle.

Allowed:

- opacity
- translateY

Duration:

150–250ms

Respect prefers-reduced-motion.

---

## Homepage

The homepage is a single-page website.

Sections:

- Hero
- About
- Current Work
- Contact

Desktop navigation uses anchor links.

Mobile navigation may use a native `<details>` menu.

---

## Hero

Keep the existing stylized personal icon.

Display:

Petr Holub

Senior Software Engineer

Short description:

"I build software with a focus on usability, mobile platforms and AI-powered tools."

Primary links:

- GitHub
- LinkedIn
- Email

---

## About

One concise paragraph.

Focus on:

- building software people enjoy using
- mobile development
- backend experience
- data-driven systems
- AI
- usability

Avoid listing technologies.

Avoid chronological career history.

---

## Current Work

Highlight Yolk Timer.

Future projects can be added later.

Do not create a portfolio grid.

---

## Yolk Timer page

Use exactly the same design language.

Sections:

- Hero
- Screenshots
- Features
- Download
- Footer

Privacy Policy should be a discreet footer link.

---

## Content

Write naturally.

Avoid marketing language.

Avoid buzzwords.

Avoid clichés.

Avoid "Hire Me".

Avoid skill ratings.

Avoid progress bars.

Avoid timelines.

Avoid unnecessary text.

If content does not improve understanding, remove it.

---

## Overall feeling

The website should feel:

- calm
- trustworthy
- professional
- timeless
- minimal
- human

Visitors should remember the software, not the website.