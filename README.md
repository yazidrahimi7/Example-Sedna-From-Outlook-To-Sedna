// Claude conversation

***
MERIDIAN EDITORIAL LANDING PAGE — PROJECT SUMMARY
=====================================================

PROJECT: Vessel email provider landing page ("Meridian Editorial Landing Page")
FILES: Meridian Landing.dc.html (source, edit this), index.html (exported standalone bundle for GitHub Pages), support.js, image-slot.js

DESIGN
- Long-read editorial layout with sticky table of contents (TOC) and scroll-reveal animations.
- Desktop: two-column grid, sticky TOC with purple active state, inertial smooth scrolling.
- Mobile TOC: horizontal layout below navbar; hides on scroll-up with smooth slide animation; active dot auto-scrolls left/right to stay visible.
- Common Concerns section, quote cards 1 & 2: mobile images enlarged 120px taller than desktop/tablet; image frame uses exact photo aspect ratio (398/229) with zero letterboxing. Photo 1 has padding-top: 40px (direct DOM edit mapped back to source).
- Form inputs: 2-column 50/50 layout across all viewports.
- "Why Choose Now" section: decorative bars hidden on tablet/mobile, desktop untouched.
- Footer and navbar: matching padding.
- Mobile-only first sentence ("for too long...strategic advantage"): 100% width; desktop/tablet untouched.
- Animations verified live on desktop, tablet, and mobile.

STATUS: Design complete. Exported index.html (self-contained, offline-ready) for GitHub Pages deployment. No console errors on verification.

NEXT STEPS
- Push index.html to a GitHub repo and enable GitHub Pages.
- To continue editing the design later, edit "Meridian Landing.dc.html" (the DC source) and re-export via the bundler — do not hand-edit index.html directly.
***
