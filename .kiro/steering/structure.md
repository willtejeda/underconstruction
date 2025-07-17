---
inclusion: always
---

# Sound Shuttle Studios - Project Structure & Code Conventions

## Current Structure
```
/
├── index.html       # Main landing page with "coming soon" content
└── README.md        # Project documentation (currently minimal)
```

## Code Organization

### HTML Structure
- **Head Section**: Contains meta tags, SEO optimization, font loading, and script imports
- **Body Section**: Contains the main application container with the Preact mount point
- **JavaScript**: Embedded in the HTML file using a module script tag
- **CSS**: Custom styles embedded in the HTML with Tailwind utility classes

### Component Architecture
- **Component Pattern**: Functional Preact components with hooks
- **Component Hierarchy**:
  - App (root component)
  - Layout components (Header, Footer)
  - Section components (HeroSection, ServicesSection, BookingSection)
  - UI components (Logo, ServiceCard, SocialLink)
- **Accessibility Components**: SkipLink and screen reader optimizations

## Coding Conventions

### Styling
- Use Tailwind utility classes for all styling
- Follow established color scheme: brand-gold (#FFD54F), brand-dark (#121212), brand-navy (#16213e)
- Custom Tailwind theme configuration extends default theme
- Maintain consistent spacing and typography (Inter font family)

### Accessibility Requirements
- Include proper ARIA attributes for all interactive elements
- Maintain semantic HTML structure with appropriate roles
- Ensure keyboard navigation works properly (tab order, focus states)
- Provide screen reader support with sr-only classes
- Support reduced motion preferences

### JavaScript Patterns
- Use ES6+ syntax exclusively
- Prefer functional components with hooks
- Use the HTM template literal syntax for JSX-like templates
- Component props should use destructuring
- Follow consistent naming conventions (PascalCase for components)

### Performance Guidelines
- Optimize images before adding to the project
- Minimize DOM manipulations
- Use CDN resources with preconnect for performance
- Implement lazy loading for non-critical resources

## Development Workflow
- No build system - direct browser execution
- All dependencies loaded via CDN (Preact, HTM, Tailwind)
- Test across multiple devices and screen sizes
- Validate HTML for accessibility compliance

## Future Structure
As the site expands beyond the landing page, organize into:
```
/
├── assets/          # Static assets (images, icons, etc.)
├── css/             # CSS files if separated from HTML
├── js/              # JavaScript files if separated from HTML
├── pages/           # Additional HTML pages
└── index.html       # Main landing page
```