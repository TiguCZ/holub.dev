# holub.dev — Design & Development Guidelines

## Purpose

This website is a personal homepage.
It is not a portfolio, résumé, landing page, or marketing site.
The goal is to help visitors quickly understand who I am, what I currently build, and how to get in touch.

## Current implementation

The site is a small static website built with plain HTML, CSS, SVG, and a little inline JavaScript.
It currently includes:

- a homepage with hero, about, current work, and contact sections
- a dedicated Yolk Timer project page
- a privacy policy page for Yolk Timer

No build step is required. Opening the homepage directly in a browser should work as expected.

## Philosophy

Keep the site calm, readable, and durable.
Favor simplicity over cleverness, and clarity over visual effects.
The design should feel understated and intentional, with enough whitespace to stay easy to read for years.

## Technology

Use only:

- HTML5
- CSS3
- SVG
- static assets

Avoid:

- build systems
- bundlers
- transpilers
- npm
- Node.js
- frameworks
- Tailwind
- Bootstrap
- React
- Vue
- Astro
- Svelte

## JavaScript

Keep JavaScript minimal.
Use it only when a feature genuinely needs it, such as:

- collapsing the mobile navigation after a link is clicked
- decoding an obfuscated email address from a data attribute

If the same thing can be done with semantic HTML or CSS, prefer that approach.

## HTML

Use semantic HTML and keep the structure simple.
Prefer elements such as:

- header
- nav
- main
- section
- article
- footer

Accessibility matters. Use proper heading hierarchy, meaningful link text, alt text where appropriate, and keyboard-friendly interactions.

## CSS

Use modern CSS and keep the styling centralized in the shared stylesheet.
Prefer:

- CSS variables
- Grid
- Flexbox
- clamp()
- min()
- max()

Support both light and dark color schemes and respect prefers-reduced-motion.

## Layout

Keep the layout centered and restrained.
Use a maximum content width of 760px, generous whitespace, and the existing spacing scale of 8, 16, 24, 32, 48, 64, and 96.
The site should adapt cleanly to mobile with a single-column layout.

## Typography

Use a clean sans-serif stack:

- Inter
- system-ui
- sans-serif

Typography should carry the design. Avoid decorative fonts and excessive visual weight.

## Color and visual language

The current implementation uses a warm orange accent rather than the earlier blue accent.
Use the current palette as the baseline:

- light background: #FFFFFF
- light text: #1D1D1F
- light secondary text: #6E6E73
- light accent: #f08a1f
- dark background: #000000
- dark text: #F5F5F7
- dark secondary text: #A1A1A6
- dark accent: #f29b3d

Keep borders subtle and surfaces understated. Avoid gradients, glossy effects, glassmorphism, and neumorphism.

## Components

Use simple, quiet components.
The current site favors:

- pill-shaped header treatment
- plain text links
- simple cards and section spacing
- small inline SVG icons for links

Avoid overdecorating interfaces. Content and spacing should do most of the work.

## Homepage

The homepage is a single-page experience with these sections:

- Hero
- About
- Current Work
- Contact

Navigation uses anchor links on desktop and a native details-based menu on mobile.

## Hero

Keep the existing personal identity and image treatment.
Display:

- Petr Holub
- Senior Software Engineer
- a short sentence about building usable software for mobile, backend, and AI-powered tools

Primary links should remain GitHub, LinkedIn, and Email.

## About

Keep the about section as a single concise paragraph.
Focus on software people enjoy using, mobile development, backend experience, data-driven systems, AI, and usability.
Do not turn this into a chronology or a list of technologies.

## Current Work

Highlight Yolk Timer as the main current project.
Do not create a portfolio grid or add unnecessary project cards.

## Yolk Timer page

Use the same design language as the homepage.
Sections should be:

- Hero
- Screenshots
- About
- Download
- Footer

The privacy policy lives as a separate discreet subpage.

## Content

Write naturally and keep copy concise.
Avoid marketing language, clichés, buzzwords, timelines, skill ratings, and progress bars.
If a sentence does not improve understanding, remove it.

## Overall feeling

The site should feel calm, trustworthy, professional, timeless, minimal, and human.
Visitors should remember the software, not the website.