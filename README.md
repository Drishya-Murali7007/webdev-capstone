Fashionista Landing Page is a simple, responsive fashion e-commerce UI built with semantic HTML5 and external CSS only. It is ideal for practicing layout, component-based UI, and modern styling without JavaScript. 

## Project Overview

Fashionista Landing Page is a single-page fashion e-commerce template featuring a sticky navbar, hero banner, flash sale strip, filters sidebar, product grids, testimonials, newsletter signup, and footer. It focuses on clean structure, responsive design, and visual polish suitable for a real-world fashion brand concept 

## Features

- Fully responsive layout using Flexbox, CSS Grid, and media queries for desktop, tablet, and mobile screens 
- Sticky navigation bar with logo, search bar, cart, and login links for quick access 
- Hero banner with background image overlay and a prominent call-to-action button.  
- Flash sale strip to visually represent time-limited offers and urgency.  
- Filters sidebar (category, price, color) laid out with semantic aside and form controls.  
- Featured categories section for Men, Women, and Accessories with hover card effects.  
- Product grid and Best Seller section using reusable card components with hover transitions.  
- Testimonials section with customer avatars and quotes for social proof.  
- Newsletter signup section with centered form and clear CTA.  
- Multi-column footer with navigation, policy links, and social media.

## Tech Stack

- HTML5 for semantic structure and clearly defined sections.  
- CSS3 for layout, styling, animations, and responsiveness.  
- Google Fonts (Montserrat) for modern typography.  
- Unsplash and RandomUser.me placeholders for product and avatar images.[6]

## Folder Structure

- `assgn.html` – Main landing page markup containing all sections.  
- `styling.css` – External stylesheet for all layout, color, and typography rules.  
  
## How to Run

1) Download or copy `assgn.html` and `styling.css` into the same folder.  
2) Ensure your machine has an internet connection for Google Fonts and external image URLs.  
3) Open `assgn.html` in any modern browser (Chrome, Edge, Firefox, Safari).  
4) Resize the browser window to see the responsive behavior across breakpoints.

## Key Sections

- Sticky Navigation Bar (`<nav.navbar>`) – Always visible header with brand, search, and user actions.  
- Hero Banner (`.hero-banner`) – Seasonal promotion highlight with overlay and CTA.  
- Flash Sale Strip (`.flash-sale`) – Visual “limited offer” band with a simple countdown label.  
- Main Layout (`.main-layout`) – Two-column layout with filters `<aside>` and `<main>` content.  
- Featured Categories (`.featured-categories`) – Grid of category cards with hover scale effects.  
- Product Grid (`.product-grid`) – Responsive product cards for “New Arrivals”.  
- Best Sellers (`.best-sellers`) – Reuses product card styles to emphasize top products.  
- Testimonials (`.testimonials`) – Flex-based layout of customer feedback cards.  
- Newsletter (`.newsletter`) – Email capture form for marketing campaigns.  
- Footer (`.footer`) – Multi-column links and social icons with hover effects.

## Customization

- Colors and theme: Change primary accent (currently pink) and background colors in `styling.css` to match your brand.  
- Fonts: Swap Montserrat with another Google Font by updating the `<link>` and font-family definitions.  
- Images: Replace Unsplash and RandomUser URLs with your own product and customer images.  
- Content: Edit headings, descriptions, prices, and call-to-action texts in `asgn.html` to reflect a real or sample brand.  
- Layout: Adjust grid columns, card sizes, and breakpoints in `styling.css` to better suit your design.

## Limitations and Extensions

- No JavaScript is used; filters and flash sale countdown are purely visual and non-functional.  
- For advanced behavior,we can later add:  
  - Real countdown timer for flash sales.  
  - Interactive product filtering.  
  - Cart functionality and item persistence.  
  - Form validation and backend integration for the newsletter 
