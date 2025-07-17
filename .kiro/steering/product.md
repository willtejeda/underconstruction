---
inclusion: always
---

# Sound Shuttle Studios - Product & Design Guidelines

## Product Overview
Sound Shuttle Studios is a professional recording studio offering mixing, mastering, and production services. The website serves as the online presence for the studio, allowing potential clients to learn about services and book recording sessions.

## Brand Identity
- **Primary Colors**: 
  - Gold: #FFD54F (brand-gold)
  - Gold Light: #FFECB3 (brand-gold-light)
  - Dark: #121212 (brand-dark)
  - Navy: #16213e (brand-navy)
  - Purple: #2a2a4a (brand-purple)
  - Light: #F9FAFB (brand-light)
  - Focus Ring: #4C9AFF
- **Typography**: Inter font family (weights: 300, 400, 700, 900)
- **Brand Voice**: Professional, premium, and approachable

## Design Patterns
- **Background**: Dark gradient backgrounds (from brand-dark to brand-navy)
- **Cards**: Dark backgrounds with subtle borders (border-brand-light/10)
- **Hover Effects**: Subtle animations (scale, translate) with color transitions
- **Focus States**: High visibility focus indicators (#4C9AFF) for accessibility
- **Animations**: Fade-in, pulse, float effects with reduced motion support

## Component Guidelines
- **Buttons**: Gold background (#FFD54F) with dark text for primary actions
- **Icons**: SVG icons with appropriate ARIA attributes
- **Cards**: Rounded corners (rounded-xl) with subtle hover effects
- **Text**: High contrast ratios for WCAG 2.1 AA compliance
- **Sections**: Clear visual hierarchy with consistent spacing

## Content Strategy
- **Headings**: Clear hierarchy with brand gold accents for emphasis
- **CTAs**: Action-oriented language with descriptive text
- **Descriptions**: Concise, professional language highlighting value
- **Metadata**: Comprehensive SEO tags with descriptive content

## External Integrations
- **EngineEars**: External booking system integration via direct link
- **Social Media**: Links to Instagram, Twitter, YouTube (placeholders)

## Current Status
The website is currently in development/beta phase with a "coming soon" landing page that allows visitors to book sessions through EngineEars.

## Implementation Requirements
- **Accessibility**: WCAG 2.1 AA compliance with keyboard navigation, ARIA attributes, and screen reader support
- **Performance**: Optimize images, minimize DOM manipulations, use CDN resources with preconnect
- **Responsive Design**: Mobile-first approach with fluid layouts
- **Animation**: Support reduced motion preferences for accessibility