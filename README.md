# Sound Shuttle Studios

A professional recording studio website offering mixing, mastering, and production services.

## Project Overview

Sound Shuttle Studios is a professional recording studio with an online presence that allows potential clients to learn about services and book recording sessions. The website is currently in beta phase with a "coming soon" landing page that directs visitors to an external booking system.

## Technology Stack

### Frontend Technologies
- **HTML5**: Semantic markup with accessibility features
- **Tailwind CSS**: Used via CDN for styling with custom configuration
- **JavaScript**: Modern ES6+ syntax
- **Preact**: Lightweight alternative to React, loaded via CDN (Skypack)
- **HTM**: JSX alternative for Preact templates

### Development Approach
- **Static Site**: Currently a single-page static site
- **No Build System**: Direct browser execution without bundling
- **CDN Dependencies**: All libraries loaded from CDNs (no npm packages)

## Project Structure

```
/
├── index.html       # Main landing page with "coming soon" content
└── README.md        # Project documentation
```

### HTML Structure
- **Head Section**: Contains meta tags, SEO optimization, font loading, and script imports
- **Body Section**: Contains the main application container with the Preact mount point
- **JavaScript**: Embedded in the HTML file using a module script tag
- **CSS**: Custom styles embedded in the HTML with Tailwind utility classes

## Brand Identity
- **Primary Colors**: Gold (#FFD54F) and dark backgrounds (gradient from #121212 to #16213e)
- **Typography**: Inter font family (weights: 300, 400, 700, 900)
- **Brand Voice**: Professional, premium, and approachable

## Accessibility Features
- Enhanced keyboard navigation support
- WCAG 2.1 AA compliance focus
- Reduced motion support
- Screen reader optimizations
- Semantic HTML structure

## External Integrations
- **EngineEars**: External booking system integration via direct link

## Local Development

To preview the site locally:

```bash
# Using Python's built-in HTTP server
python -m http.server

# Or using Node.js with http-server (if installed)
npx http-server
```

## Future Structure

As the site expands beyond the landing page, it will be organized into:

```
/
├── assets/          # Static assets (images, icons, etc.)
├── css/             # CSS files if separated from HTML
├── js/              # JavaScript files if separated from HTML
├── pages/           # Additional HTML pages
└── index.html       # Main landing page
```

## Conventions

### Styling
- Use Tailwind utility classes for styling
- Custom theme configuration extends Tailwind's default theme
- Follow the established color scheme and typography

### JavaScript
- Use ES6+ syntax
- Prefer functional components with hooks
- Use the HTM template literal syntax for JSX-like templates