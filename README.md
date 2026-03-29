# Payapa Wellness & Spa — Website

Static HTML/CSS/JS website for Payapa Wellness & Spa.

## Files

| File | Description |
|---|---|
| `index.html` | Landing page — hero, location carousel, services (koi pond), footer |
| `booking.html` | Booking flow — 6-step appointment booking (location → schedule → service → requests → details → review → confirmation) |

## Structure

All images are embedded as base64 inline — no external image dependencies.  
Fonts load from Google Fonts (Cormorant Garamond + Jost).

## Hosting

Deploy both files to the root of any static host (GitHub Pages, Netlify, Vercel).  
No build step required.

## Next steps

- [ ] Connect SimplyBook.me API for live scheduling
- [ ] Replace hardcoded time slots with real availability
- [ ] Wire up booking form submission to SimplyBook.me
- [ ] Add email confirmation via SimplyBook.me notifications
- [ ] Update branch addresses and contact numbers
- [ ] Set Google Maps links per branch

## Design system

Dark forest theme — `#1C2318` background, `#F0EAD8` cream text, `#C8A96E` gold accent.  
Typography: Cormorant Garamond (display/headings) + Jost (UI/body).
