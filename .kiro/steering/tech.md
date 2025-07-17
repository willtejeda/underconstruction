---
inclusion: always
---

# Sound Shuttle Studios - Technology Stack

## Frontend Technologies
- **HTML5**: Semantic markup with accessibility features
- **Tailwind CSS**: Used via CDN for styling with custom configuration
- **JavaScript**: Modern ES6+ syntax
- **Preact**: Lightweight alternative to React, loaded via CDN (Skypack)
- **HTM**: JSX alternative for Preact templates

## Development Approach
- **Static Site**: Currently a single-page static site
- **No Build System**: Direct browser execution without bundling
- **CDN Dependencies**: All libraries loaded from CDNs (no npm packages)

## Accessibility
- Enhanced keyboard navigation support
- WCAG 2.1 AA compliance focus
- Reduced motion support
- Screen reader optimizations
- Semantic HTML structure

## Common Commands
No build commands are currently needed as the site uses direct browser execution without compilation.

### Local Development
To preview the site locally:
```bash
# Using Python's built-in HTTP server
python -m http.server

# Or using Node.js with http-server (if installed)
npx http-server
```

## External Integrations
- **EngineEars**: External booking system integration via direct link