# Liz Morales Music

A single-page website for Hawaiian musician and wedding officiant Liz Morales, built with Astro.

🔗 **View Live Site:** [lizmoralesmusic.com](https://lizmoralesmusic.com)

## Overview

This site showcases Liz Morales' work as a Native Hawaiian musician, wedding officiant, and music educator. Built from an Astro starter template and extensively customized with responsive design, dynamic scheduling features, and custom payment links.

## Key Features

- **Dynamic Schedule Component** - Automatically updated performance calendar with responsive grid layout and mobile/desktop view optimization
- **Custom Responsive Design** - Mobile-first approach with breakpoint-specific layouts using LESS preprocessing
- **Custom UI Elements** - Venmo QR code display and payment links with custom SVG icons and hover effects
- **Optimized Images** - Responsive picture elements with multiple sources for performance
- **Component Architecture** - Modular Astro components for discography, weddings, contact forms, and scheduling
- **SEO & Social Meta** - Open Graph tags and social media optimization

## Tech Stack

- Astro 5.7
- LESS for advanced CSS preprocessing
- Custom responsive grid layouts
- Google Fonts integration (Roboto, Allura)

## Development

```bash
npm install          # Install dependencies
npm run dev          # Start dev server at localhost:4321
npm run build        # Build for production
npm run preview      # Preview production build
```

## Project Structure

```
src/
├── components/      # Reusable UI components
│   ├── Schedule.astro
│   ├── Discography.astro
│   ├── Weddings.astro
│   ├── ContactForm.astro
│   ├── Header.astro
│   └── Footer.astro
├── layouts/        # Page layouts
│   └── Layout.astro
├── pages/          # Route pages
│   └── index.astro
└── styles/         # Global styles
```
