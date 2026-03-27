## Media Production Company Website


## Overview
The Media Production Company Website is a fully responsive, multi-page site designed to showcase professional media services, including video production, audio recording, photography, and multimedia solutions. Its purpose is to provide clients with a portfolio, detailed service descriptions, contact options, and an immersive browsing experience across devices. The website demonstrates modern web development practices using HTML5, CSS3, Flexbox, Grid, and responsive media integration.


## Issues Found
- Missing semantic HTML tags (<header>, <main>, <section>, <footer>, <figure>, <figcaption>).
- Lack of proper metadata for SEO and accessibility.
- Poor responsive layout; navigation and content did not adapt to mobile screens.
- Form validation missing or incomplete.
- Media elements (video, audio) lacked fallback text and controls.
- CSS lacked structure and modularity; no variables, pseudo-classes, or transitions.
- No animations or hover effects; cards and buttons were static.


## Fixes and Implementations
- Added semantic HTML5 tags and proper metadata (<meta> description, viewport, charset).
- Implemented a sticky header with responsive hamburger menu for mobile.
- Redesigned hero and team sections with overlay for text readability.
- Completed service and portfolio sections with fully functional cards and media elements.
- Built an accessible contact form with fieldsets, legends, placeholders, and validation patterns.
- Added Flexbox layouts for service cards and team section.
- Added CSS Grid layouts for portfolio, video showcase, testimonials, and video containers.
- Created hover effects, transitions, scaling, and rotations for cards and buttons.
- Implemented fade-in animations on hero and about sections.
- Ensured accessibility: alt text for images, ARIA labels for navigation, semantic heading structure.
- Tested cross-browser compatibility in Chrome, and Edge ensured consistent layout and font rendering.


## lexbox Layouts
- Services Section: .services-container uses display: flex; flex-wrap: wrap; justify-content: stretch; to align cards evenly across varying screen sizes.
- Contact Form: Form fields aligned with flex spacing for better responsiveness.
- Header Navigation: Flex used to distribute logo, menu toggle, and links.


## CSS Grid Layouts
- Portfolio & Testimonials: .portfolio and .testimonials utilize grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)) for responsive card arrangement.
- Video Showcase: .video-container displays multiple videos evenly using auto-fit grid.
- Responsive adjustments: Grid columns collapse automatically on smaller screens for mobile-friendly design.


## Selectors and Pseudo-Classes
- Class selectors: .card, .cta-btn, .portfolio, .contact-form.
- Pseudo-classes: :hover, :focus, :active for buttons, links, inputs, and media cards.
- Attribute selectors: [type="radio"], [type="checkbox"], [type="tel"] for styling form elements.


## Animations, Effects, Transforms, Transitions
- Fade-in animations (@keyframes fadeInDown, fadeInUp) for hero and about sections.
- Card hover: transform: translateY(-5px) scale(1.03) rotate(1deg) with smooth transition: all 0.3s.
- Button hover: scaling and box-shadow enhancement.
- Portfolio images zoom on hover with caption fade-in overlay.


## Accessibility Improvements
- Semantic HTML and heading structure.
- Alt text for images and videos.
- ARIA labels for navigation.
- Focus styles for interactive elements.
- Form field validation and placeholders for guidance.


## Cross-Browser Compatibility
- Tested on Chrome and Edge.
- Minor adjustments for iframe and video scaling across browsers.
- No browser-specific CSS required; all modern browsers display layouts consistently.


## Local Viewing Instructions

1. Clone the repository:

- git clone https://github.com/yourusername/media-production-website.git

2. Navigate to the project folder:

- cd media-production-website
3. Open index.html in any modern browser.
4. Optionally, use VS Code Live Server for live reload.


## Screenshots
- Desktop Views: index.html, about.html, media.html, contact.html.
- Mobile Views: index.html, about.html.
- Form with Validation: contact.html with required fields triggered.
- Animations: Hero fade-in and card hover effects.
- Media Functioning: Video, audio, and iframe map.
- Flexbox & Grid Demonstrations: Services and portfolio sections.
- Browser Compatibility: Screenshots from Chrome and Edge showing identical layouts.


## Reflection
- Building this website revealed challenges in responsive layout design, cross-browser testing, and proper semantic structure. Implementing advanced CSS transitions and grid layouts required careful debugging of spacing, scaling, and media responsiveness. Solutions included iterative testing on mobile and desktop, adjusting media queries, and using CSS variables for consistent styling