---
inclusion: always
---

# Sound Shuttle Studios - Project Structure

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

### Component Structure
The site uses a simple Preact component structure:
- **App**: Main component that renders the entire page
- **Sections**: Organized as semantic HTML sections within the App component

## Conventions

### Styling
- Use Tailwind utility classes for styling
- Custom theme configuration extends Tailwind's default theme
- Follow the established color scheme and typography

### Accessibility
- Include proper ARIA attributes for all interactive elements
- Maintain semantic HTML structure
- Ensure keyboard navigation works properly
- Provide screen reader support

### JavaScript
- Use ES6+ syntax
- Prefer functional components with hooks
- Use the HTM template literal syntax for JSX-like templates

## Future Structure
As the site expands beyond the landing page, consider organizing into:
```
/
├── assets/          # Static assets (images, icons, etc.)
├── css/             # CSS files if separated from HTML
├── js/              # JavaScript files if separated from HTML
├── pages/           # Additional HTML pages
└── index.html       # Main landing page
```