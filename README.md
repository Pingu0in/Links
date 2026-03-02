Pingu0in — Minimal Generative Linktree

A fully custom minimal, scroll-based Linktree-style landing page built with pure HTML, CSS, and JavaScript — enhanced with generative art powered by p5.js.

This project is not just a link aggregator.
It’s a visual identity experiment combining:

Generative art

Brutalist minimalism

Custom cursor interactions

Scroll-based UI logic

Monochrome aesthetic design

PREVIEW

A vertical snap-scrolling experience where each section represents a platform:

Instagram

TikTok

GitHub

Twitter (X)

Twitch

YouTube

Discord

Each platform includes:

A unique generative artwork

Animated card reveal

Custom-styled button

Large background keyword watermark

CONCEPT

Instead of using a standard Linktree template, this project explores:

Code as visual language

Noise & randomness as design elements

Minimal typography contrast (DM Serif Display × Syne × Space Mono)

Cinematic scrolling

Anti-design inspired layout

Every section includes a custom p5.js sketch reflecting the platform’s identity:

Platform	Art Concept
Instagram	Shattered Grid
TikTok	Vertical Frequencies
GitHub	Recursive Branches
Twitter	Typographic Chaos
Twitch	Signal Interference
YouTube	Cinematic Bars
Discord	Particle Connection Network
🛠 Tech Stack

HTML5

CSS3 (Custom Properties + Scroll Snap)

Vanilla JavaScript

p5.js (Generative Art)

Font Awesome (Icons)

Google Fonts (DM Serif Display, Syne, Space Mono)

No frameworks. No build tools. No dependencies.

FEATURES
Custom Cursor

Smooth trailing ring animation

Expands on hover over links

Uses mix-blend-mode: difference

Scroll System

Scroll snap layout

Dynamic progress bar

Section counter (01 / 07)

Smooth card reveal with IntersectionObserver

Generative Art System

Each section mounts a separate p5 instance using:

new p5(sketchFn, containerElement);

All sketches:

Use seeded randomness

Are static (noLoop)

Follow a monochrome palette

Combine noise-based variation with geometry

PROJECT STRUCTURE
.
└── index.html   # Entire project in a single file

Everything is self-contained inside one HTML file:

Styles

Layout

Scripts

Generative sketches

Perfect for:

GitHub Pages

Portfolio landing

Personal branding site

HOW TO USE

Clone the repository:

git clone https://github.com/your-username/your-repo.git

Open index.html in your browser.

Or deploy directly with:

GitHub Pages

Vercel

Netlify

No configuration required.

CUSTOMIZATION

To personalize:

Change avatar image URL

Update social links

Modify section keywords (data-keyword)

Edit p5 sketches for new visual identity

Adjust color variables in :root

Main color system:

:root {
  --black: #080808;
  --white: #f0ede8;
  --gray: #1a1a1a;
  --mid: #555;
}
POSSIBLE IMPROVEMENTS

Dark / light theme toggle

Animated sketches (remove noLoop())

Sound-reactive visualizations

CMS-based dynamic links

Mobile interaction optimization

LICENSE

Free to use and modify.
Attribution required.

AUTHOR

Pingu0in
Content Creator · Developer · Creative Coder
