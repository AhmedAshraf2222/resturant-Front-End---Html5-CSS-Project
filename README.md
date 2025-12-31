# Dagag Restaurant Website

## Description
A static, responsive website for Dagag Restaurant, specializing in delicious chicken meals. Built with HTML, Tailwind CSS, and DaisyUI, it offers an intuitive interface to explore the menu, learn about the restaurant, and get in touch.

## Features
- **Responsive Navigation**: Sticky navbar with mobile dropdown and desktop horizontal menu linking to Home, About, and Contact.
- **Home Page**:
  - Hero section with background image and "Book Now" button.
  - Services: Dine-In, Takeaway, Delivery, Catering.
  - Main menu displaying 6 chicken dishes with images, descriptions, prices, and "Order Now" buttons.
- **About Page**: Restaurant mission, quality focus, and images.
- **Contact Page**: Contact form (name, email, phone, message).
- **Footer**: Logo, short description, social media icons (Twitter, YouTube, Facebook), and copyright.
- **Design**: Modern orange-red theme using Tailwind CSS and DaisyUI.

## File Structure
```
dagag-restaurant/
├── images/          # All images (logo.png, hero.jpg, about.jpg, 1.jpg to 6.jpg)
└── pages/
    ├── home.html    # Home page with hero, services, and menu
    ├── about.html   # About page
    └── contact.html # Contact page
```

## How to Run Locally
1. Download or clone the project.
2. Open any file from `pages/` (e.g., `pages/home.html`) directly in a browser.
3. (Optional) Run a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000/pages/home.html`.

**Note**: Requires internet to load Tailwind CSS and DaisyUI via CDN.

## Additional Info
- **Technologies**: HTML5 + Tailwind CSS (CDN) + DaisyUI (CDN).
- **Limitations**: Static site only — buttons (Order Now, Send Message, etc.) are non-functional.
- **Deployment**: Easy to host on GitHub Pages, Netlify, or Vercel.
- **Customization**: Add menu items by editing `home.html`; change colors via Tailwind classes.

For questions or contributions, contact the project maintainer.

---
*Generated on December 31, 2025*
