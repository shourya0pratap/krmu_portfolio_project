# KRMU Web Dev: Personal Portfolio Project

Submitted by - Shourya Pratap Singh  
Roll No. - 30  
Section - A

This project is a fully styled personal portfolio website built for the Web Development lab assignment. It started as a basic HTML structure (Lab 1) and was then fully styled and enhanced using an external CSS stylesheet (Lab 2).

## Project Features

This portfolio demonstrates the following HTML and CSS concepts:

### 1. HTML Structure
* **Semantic HTML:** Uses semantic tags like `<header>`, `<main>`, `<section>`, `<nav>`, `<article>`, and `<footer>` to create a well-structured and accessible webpage.
* **Navigation:** A sticky navigation bar provides smooth-scrolling links to all major sections of the page.
* **Content Sections:**
    * **About:** Includes a styled profile image and a brief introduction.
    * **Skills:** Displays technical skills in a clearly styled `<table>` with alternating row colors.
    * **Projects:** Uses a responsive **CSS Grid** to display projects as modern "cards," a significant improvement over a simple table.
* **Contact Form:** A styled contact form built with `<table>` and includes `<label>`, `placeholder` text, and `required` validation attributes.

### 2. CSS Styling & Layout
* **External Stylesheet:** All styling is managed in a single, well-commented `style.css` file.
* **Modern Design:**
    * **Color Theme:** Uses a consistent, professional color scheme defined in `:root` (CSS variables).
    * **Typography:** Imports and applies the 'Poppins' Google Font for clean, modern text.
    * **Box Model:** Leverages `padding`, `margin`, `border-radius`, and `box-shadow` to create a clean, spaced-out, card-based layout.
* **CSS Positioning:**
    * `position: sticky` is used to create a "sticky" header that stays at the top of the page on scroll.
    * `position: fixed` is used to create a "Back to Top" button in the bottom-right corner.
* **Visual Elements:**
    * Styled `<hr class="section-divider">` elements are used to create full-width visual breaks between sections.
    * All links, buttons, and project cards feature interactive `:hover` effects.
