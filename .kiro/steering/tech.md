---
inclusion: always
---

# Sound Shuttle Studios - Technology Stack

## Frontend Technologies
- **HTML5**: Use semantic markup with proper accessibility attributes
- **Tailwind CSS**: Load via CDN with custom configuration for brand colors
- **JavaScript**: Write in modern ES6+ syntax only
- **Preact**: Use as React alternative, loaded via Skypack CDN
- **HTM**: Implement for JSX-like templates with Preact

## Code Style & Patterns
- Use functional components with hooks
- Follow PascalCase for component names
- Use destructuring for component props
- Implement proper error handling for async operations
- Maintain consistent indentation (2 spaces)

## Development Architecture
- **Static Site Architecture**: Single-page static site without server-side rendering
- **No Build System**: All code runs directly in browser without transpilation
- **CDN Dependencies**: Load all external libraries from CDNs (Skypack preferred)
- **Performance**: Implement lazy loading for non-critical resources

## Accessibility Requirements
- Ensure WCAG 2.1 AA compliance in all components
- Implement keyboard navigation with visible focus states
- Support reduced motion preferences via prefers-reduced-motion
- Optimize for screen readers with proper ARIA attributes
- Maintain semantic HTML structure throughout

## Local Development
```bash
# Using Python's built-in HTTP server
python -m http.server

# Or using Node.js with http-server
npx http-server
```

## External Integrations
- **EngineEars**: Integrate booking system via direct link (no API currently)