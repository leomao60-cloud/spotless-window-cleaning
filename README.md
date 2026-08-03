# SPOTLESS — Window Cleaning Landing Page

First-year professional window cleaning business serving **Fresno, CA**.

**Live site:** https://leomao60-cloud.github.io/spotless-window-cleaning/

**Repo:** https://github.com/leomao60-cloud/spotless-window-cleaning

## Features

- Split-screen hero with **draggable before/after** divider
- Sticky nav with scrollspy + mobile hamburger overlay
- Scroll-reveal animations and animated stats counters
- Organized services: Residential · Commercial · Power Washing
- Working testimonial carousel (auto-advance, dots, swipe)
- Book Now modal (FormSubmit → `jerrenmao3@gmail.com`)
- Hover FX: glow cursor, magnetic buttons, 3D tilt cards
- 4K-class photos with responsive `srcset`
- Mobile sticky Call / Book bar
- LocalBusiness JSON-LD, Open Graph, accessibility basics

## Stack

- Single `index.html` (no build step)
- Tailwind CSS (CDN) + vanilla JavaScript
- Google Fonts (Poppins)

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
cd /Users/smao/Downloads/spotless-window-cleaning
python3 -m http.server 8080
```

## Before going fully live

1. Replace phone, email, and FormSubmit address with real business contacts  
2. Swap placeholder testimonials for real reviews (with permission)  
3. Confirm FormSubmit email once from the inbox  
4. Run Lighthouse and fix any contrast/performance flags  
