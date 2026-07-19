# Ember Website

This is the official marketing website and landing page for **Ember**, an offline-first Android app for organizing your life.

## About Ember

Ember is a personal life companion app built with Flutter that helps you keep track of all parts of your life—from notes and to-dos to journal entries and your bucket list. Everything stays on your device. No accounts, no servers, no tracking.

**Key Features:**
- 9 dedicated modules (Notes, Bucket List, Reading List, Recipes, Reminders, To-dos, Journal, People, Movies)
- Completely offline—all data stays on your device
- No accounts or login required
- No ads, no analytics, no tracking
- No network permissions requested
- 100% free, no subscriptions

## Website Structure

- `index.html` - Landing page with hero section, features, and call-to-action
- `privacy.html` - Privacy policy page
- `css/styles.css` - Design system tokens and component styles
- `assets/images/` - App screenshots and visual assets

## Design System

The website uses the **Organic** design system with the following design tokens:

- **Colors:** Cream background (#f5ead8), Terracotta accent (#c67139), Sage secondary (#7a8a5e)
- **Typography:** Caprasimo (headings), Figtree (body)
- **Spacing:** Modular scale with CSS custom properties
- **Radius:** 16px base, 28px large, pill buttons (999px)
- **Fonts:** Imported from Google Fonts (Caprasimo, Figtree)

## Development

This is a static website—no build step required. Serve the files directly with any static host:

```bash
# Local testing with Python
python -m http.server 8000

# Or with Node.js http-server
npx http-server
```

Then open http://localhost:8000 in your browser.

## GitHub Pages

This site is deployed to GitHub Pages. The website will be automatically published from the repository.

**Site URL:** https://pebblecloud.github.io/Live

## File Organization

```
Live/
├── index.html              # Landing page
├── privacy.html            # Privacy policy
├── css/
│   └── styles.css          # All styles (no build step)
├── assets/
│   └── images/             # App screenshots
├── README.md
└── .gitignore
```

## Technologies

- **HTML5** - Semantic markup
- **CSS3** - Design system tokens and responsive styles
- **JavaScript** - Simple carousel functionality (no framework)
- **Google Fonts** - Caprasimo and Figtree typefaces
- **Static Hosting** - GitHub Pages (free)

## Configuration

The website is fully static and requires no configuration. To update content:

1. Edit the HTML files directly
2. Modify colors or spacing in `css/styles.css`
3. Replace images in `assets/images/`
4. Commit and push to deploy automatically

## Downloads

The download buttons link to the Google Play Store. Update the Play Store URL in the HTML if the app package ID changes.

## Accessibility

The site includes:
- Semantic HTML structure
- Proper heading hierarchy
- Focus states for keyboard navigation
- Sufficient color contrast
- Responsive design for all devices

## License

Website content and design © Ember. All rights reserved.
