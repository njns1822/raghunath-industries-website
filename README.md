# Raghunath Industries Website Project

## Project Goal
Build a production-ready, single-page website for deployment on Netlify.
Must work as static HTML (no build step, no npm install required).

## Company Quick Facts
- **Company**: Raghunath Industries (RI)
- **Location**: Plot No. 950-955, Sector-D, Village Sarora, Urla Industrial Area, 
  Raipur-493221, Chhattisgarh, INDIA
- **Registered Office**: LG-27, Samvet Shikhar Complex, Rajbandha Maidan, Raipur
- **Email**: info@raghunathindustries.co.in
- **WhatsApp**: +91 93295 91163
- **Founded**: 2020
- **Industry**: Exotic fats, specialty butters, minor forest oil seeds

## Founders / Board Members
1. Shri Padam Chand Jain
2. Mr. Ameet Kumar Shrishrimal
3. Mr. Vivek Shrishrimal
4. Mr. Karan Pramod Gupta

## Product Portfolio
- Sal Fat
- Sal Stearin
- Mango Fat
- Mango Stearin
- Shea Stearin
- Kokum Fat
- Rice Bran Oil Wax
- Sunflower Wax

Featured hero product: **Sal Stearin (Sal Butter)** — key ingredient in Cocoa Butter Equivalent (CBE) for premium chocolate manufacturing.

## Manufacturing Capabilities
- Refinery Plant: 30 TPD installed capacity
- Acetone Fractionation Plant: 22 TPD installed capacity
- Process: refining and fractionating of exotic oils (Sal, Shea, Mango, Kokum)
- Exports: UK, Malaysia, and expanding to Europe and Africa

## Vision
"To achieve excellence in production of Exotic Fats and various minor forest oil 
seeds through continuous R&D and optimise utilisation of by-products thereby 
creating value."

## Key Differentiators
- State-of-the-art infrastructure
- Strong R&D team
- Competitive pricing with International Quality Standards
- Sustainable sourcing from Chhattisgarh, Odisha, Madhya Pradesh, Jharkhand
- Strong domestic + international clientele with repeat orders

## Design Direction (Per Full Brief)
- **Theme**: Gold + Green (per client preference)
- **Palette**: Warm gold/amber (#D4A574), deep green (#2D5016), cream (#F5F1E8), 
  charcoal (#2B2B2B)
- **Typography**: Serif display font for headlines (Playfair Display), 
  clean sans-serif for body (Lato or Source Sans Pro)
- **Aesthetic**: Professional minimalism + visual richness, NOT generic AI look
- **Inspiration**: fff.co.in, unilever.com, manoramagroup.co.in

## Full Design Brief
See `professional_website_design_prompt.md` in the repo root for complete 
specifications on sections, layouts, colors, motion, accessibility requirements.

## Technical Requirements
- Single `index.html` file with inline CSS and minimal JS (or split into 
  index.html / style.css / script.js — your call based on file size)
- Must work when opened directly (file://) AND when served from Netlify
- Responsive: mobile-first, breakpoints at 768px and 1024px
- WCAG 2.1 AA compliant
- Fast-loading, optimized images from the /assets folder
- No external build tools (no webpack, no npm install)

## Asset Locations
- Product/factory images: `./assets/IMG_*.jpg` and `./assets/WhatsApp_Image_*.jpeg`
- Board info & company narrative: `./Company_Mission_and_Board_of_directors_and_other_information.docx`

## Deployment
Target: Netlify (auto-deploys from this GitHub repo on push to `main`).