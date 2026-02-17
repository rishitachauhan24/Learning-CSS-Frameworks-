# TechVista - Custom Brand Website with TailwindCSS

A fully responsive, accessible website built with TailwindCSS featuring a custom brand theme.

## Features

- ✨ Custom TailwindCSS theme with brand colors, typography, and spacing
- 📱 Fully responsive design (mobile, tablet, desktop)
- ♿ Accessibility optimized (ARIA labels, keyboard navigation, semantic HTML)
- 🎨 Pre-built reusable components (navbar, cards, buttons, forms)
- 🎯 Cohesive design language across all pages
- ⚡ Fast and optimized

## Brand Style Guide

**Colors:**
- Primary: Deep Blue (#0F172A)
- Secondary: Electric Blue (#3B82F6)
- Accent: Vibrant Orange (#F97316)
- Success: Green (#10B981)
- Warning: Amber (#F59E0B)
- Danger: Red (#EF4444)

**Typography:**
- Headings: Inter (Bold)
- Body: Inter (Regular)

**Spacing:**
- Uses TailwindCSS's extended spacing scale

## Setup Instructions

1. Install dependencies:
   ```bash
   npm install
   ```

2. Build CSS (production):
   ```bash
   npm run build
   ```

3. Watch for changes (development):
   ```bash
   npm run watch
   ```

4. Open `index.html` in your browser

## Project Structure

```
├── index.html          # Homepage
├── about.html          # About page
├── products.html       # Products showcase
├── contact.html        # Contact form
├── src/
│   ├── input.css      # TailwindCSS source
│   └── script.js      # Interactive components
├── dist/
│   └── output.css     # Compiled CSS
└── tailwind.config.js # Custom theme configuration
```

## Pages

1. **Home** - Hero section, features, testimonials
2. **About** - Company information, team section
3. **Products** - Product cards with filters
4. **Contact** - Accessible contact form

## Customization

All brand customizations are in `tailwind.config.js`. Modify colors, fonts, spacing, and more to match your brand identity.
