## Overview

Static website presenting contact details for a portfolio company. The goal is to provide contact information to potential customers in a professional manner.

**Tech stack:** Plain HTML/CSS (no framework)

## Page Layout

### Header (top)
- Main heading: **stegosaurus s.r.o.**
- Subtitle: Specializing in Node.js
- Node.js logo image

### Center
- Stegosaurus video background with two animation states
- Video uses `object-fit: contain` to always fit within screen width without cropping

### Footer (bottom)
- Background: `ground-layer.png` - determines footer height (scales with viewport width)
- Max height: 20vh with overflow hidden
- Contact info overlayed absolutely and vertically centered

Contact details:
- Company name: stegosaurus s.r.o.
- Address: Rajecká Lesná 257, 013 15
- VAT number: SK2122158610
- Email: juraj.zovinecc@gmail.com
- Phone: +421 915 859 604

## Business Details

Company information sourced from: https://finstat.sk/56000812

## Stegosaurus Animation

Background video with mouse-triggered attack animation:

- **Video files:**
  - `public/animation-stegosaurus-idle.webm` - default calm state (looped)
  - `public/animation-stegosaurus-attack.webm` - triggered on rapid mouse movements
- **Trigger:** Mouse velocity exceeding threshold (half screen height per second, averaged over 5 samples)
- **Cooldown:** 1.5 seconds between attacks
- **Behavior:** Attack plays once, then returns to idle loop
- **Model attribution:** Based on 3D model by Mark Cao on Sketchfab (CC license)
