## Overview

Static website presenting contact details for a portfolio company. The goal is to provide contact information to potential customers in a professional manner.

**Tech stack:** Plain HTML/CSS (no framework)

## Page Layout

### Header (top)
- Main heading: **stegosaurus s.r.o.**
- Subtitle: Specializing in Node.js

### Center
- 3D Stegosaurus model in IDLE animation state (eye-catcher)

### Footer (bottom)
Contact details:
- Company name: stegosaurus s.r.o.
- Address: (sourced from Finstat)
- VAT number: (sourced from Finstat)
- Email: juraj.zovinecc@gmail.com
- Phone: +421 915 859 604

## Business Details

Company information sourced from: https://finstat.sk/56000812

## Stegosaurus 3D Model

Interactive 3D model embedded via Sketchfab, displayed in IDLE state by default.

- **Model URL:** https://sketchfab.com/3d-models/stegosaurus-80d282abed5041e49aef86a4c1af8091
- **Embed endpoint:** `https://sketchfab.com/models/80d282abed5041e49aef86a4c1af8091/embed`
- **Attribution:** Model by Mark Cao on Sketchfab (CC license - requires attribution)

### Future Enhancement

Trigger tail whip animation on aggressive mouse movements. The model supports two animation states:
- **IDLE** - default calm state
- **ATTACK** - triggered on rapid mouse movements

This requires Sketchfab API integration to control animation playback.
