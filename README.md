# Dagag Restaurant Website

## Description

The Dagag Restaurant Website is a responsive web application designed for a restaurant specializing in delicious chicken meals. Built using HTML, Tailwind CSS, and DaisyUI, the website provides an intuitive interface for users to explore the restaurant's offerings, learn about its mission, and contact the team. The site features a modern design with a focus on user experience, including navigation, menu display, and a contact form.

## Features

- **Responsive Navigation**: A sticky navbar with a dropdown menu for mobile devices and horizontal menu for larger screens, linking to Home, About, and Contact pages.
- **Home Page**: 
  - A hero section with a background image and a "Book Now" call-to-action.
  - A services section highlighting Dine-In, Takeaway, Delivery, and Catering options.
  - A main menu showcasing six chicken dishes with images, descriptions, prices, and "Order Now" buttons.
- **About Page**: 
  - Details the restaurant’s mission and passion for quality ingredients.
  - Includes images of the restaurant and a welcoming message.
- **Contact Page**: 
  - A form for users to send messages with fields for name, email, phone, and message.
- **Footer**: Consistent across all pages, featuring the restaurant logo, description, social media links (Twitter, YouTube, Facebook), and copyright information.
- **Styling**: Utilizes Tailwind CSS and DaisyUI for a modern, responsive, and visually appealing design with a cohesive orange-red color scheme.

## File Structure / Folder Layout

The project is organized as follows:

```
dagag-restaurant/
├── images/
│   ├── logo.png        # Restaurant logo used in navbar and footer
│   ├── hero.jpg        # Hero section background image
│   ├── about.jpg       # Image for About page
│   ├── 1.jpg           # Image for Grilled Chicken Platter
│   ├── 2.jpg           # Image for Spicy Chicken Wings
│   ├── 3.jpg           # Image for Chicken Burger
│   ├── 4.jpg           # Image for Chicken Caesar Salad
│   ├── 5.jpg           # Image for Fried Chicken Plate
│   ├── 6.jpg           # Image for Chicken Curry Dish
├── pages/
│   ├── home.html       # Home page with hero, services, and menu sections
│   ├── about.html      # About page with restaurant details and images
│   ├── contact.html    # Contact page with a message form
```

- **images/**: Contains all static image assets referenced in the HTML files.
- **pages/**: Contains the HTML files for the website’s core pages.

## How to Install and Run Locally

To run the Dagag Restaurant Website locally, follow these steps:

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., VS Code) for viewing or editing files (optional).
- No server or dependencies are required as the project is purely HTML and CSS-based.

### Steps
1. **Clone or Download the Project**:
   - Download the project files or clone the repository to your local machine.
   - Ensure the folder structure includes `images/` and `pages/` as described above.

2. **Navigate to the Project Directory**:
   ```bash
   cd dagag-restaurant
   ```

3. **Open the Website**:
   - Open any HTML file (`pages/home.html`, `pages/about.html`, or `pages/contact.html`) in a web browser.
   - For example, right-click `pages/home.html` and select "Open with" your preferred browser, or drag the file into the browser window.
   - Alternatively, double-click the HTML file to open it in your default browser.

4. **Explore the Website**:
   - Navigate between pages using the navbar links (Home, About, Contact).
   - Note: The "Log In", "Sign Up", "Book Now", "Order Now", and "Send Message" buttons are placeholders and not functional in this static version.

5. **Optional: Serve Locally with a Web Server**:
   - For a more realistic testing environment, you can use a local web server.
   - Install a simple server like `http-server` (Node.js) or use Python’s built-in server:
     ```bash
     # Using Python
     python -m http.server 8000
     ```
     Or, with Node.js:
     ```bash
     npm install -g http-server
     http-server
     ```
   - Open `http://localhost:8000/pages/home.html` in your browser.

### Notes
- The website uses CDN links for Tailwind CSS (`@tailwindcss/browser@4`) and DaisyUI (`daisyui@5`), so an internet connection is required to load styles.
- Ensure the `images/` folder is at the same level as `pages/` to avoid broken image links.

## Additional Information

- **Technologies Used**:
  - **HTML5**: For the website structure.
  - **Tailwind CSS**: For utility-first styling, loaded via CDN.
  - **DaisyUI**: For pre-built components (e.g., navbar, cards, buttons), loaded via CDN.
  - **SVG Icons**: Social media icons in the footer for Twitter, YouTube, and Facebook.

- **Limitations**:
  - The website is static and does not include backend functionality. Buttons like "Log In", "Sign Up", "Order Now", and the contact form’s "Send Message" are non-functional and would require a backend (e.g., JavaScript, PHP, or Node.js) to process data.
  - Social media links in the footer are placeholders and do not point to actual URLs.

- **Customization**:
  - To add more menu items, edit the `pages/home.html` file’s "Main Menu" section by duplicating a card and updating the image, title, description, and price.
  - To modify colors or styles, adjust the Tailwind classes (e.g., `bg-orange-500`) or add custom CSS.
  - To make the contact form functional, integrate a backend service or API.

- **Deployment**:
  - The website can be deployed to any static hosting platform (e.g., GitHub Pages, Netlify, Vercel).
  - Ensure the folder structure (`images/` and `pages/`) is maintained during deployment.
  - Update the CDN links to specific versions for production to avoid breaking changes (e.g., `daisyui@5.0.0` instead of `daisyui@5`).

- **Browser Compatibility**:
  - Tested on modern browsers (Chrome, Firefox, Edge). Ensure users have JavaScript enabled for Tailwind’s browser script to work.

- **Future Enhancements**:
  - Add a backend for form submissions and user authentication.
  - Implement a dynamic menu system with a database for easier updates.
  - Add interactive features like a reservation system or online ordering.

For any questions or contributions, feel free to contact the project maintainer or open an issue in the repository (if applicable).

---

*Generated on December 31, 2025*
