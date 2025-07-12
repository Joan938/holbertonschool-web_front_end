Advanced CSS Project

This project is part of the Holberton School Front End curriculum and focuses on advanced CSS techniques. You will apply CSS fundamentals and advanced concepts to style a multi-section homepage for a fictional digital agency, Techium. The project is designed to deepen your understanding of custom properties (CSS variables), layout techniques, responsive design preparation, and CSS transitions.

Table of Contents

Project Overview

Learning Objectives

Prerequisites

Project Structure

Setup & Usage

Tasks

Resources

License

Project Overview

You will style the provided index.html using CSS only. There is no requirement for CSS frameworks—everything must be handwritten. The final design should follow the wireframe and include elements such as:

Header with logo and navigation menu

Hero section with a call-to-action button

Services, Works, About, Latest News, Testimonials and Contact sections

Footer with social icons and site links

Learning Objectives

By completing this project, you will be able to:

Use CSS custom properties (variables) for colors, typography, spacing, and more

Understand CSS specificity and selector mechanics

Apply reset/normalize styles for cross-browser consistency

Layout elements using floats and box-sizing techniques

Use pseudo-classes and pseudo-elements for hover states, decorations, and quotes

Integrate Google Fonts and custom font stacks

Implement smooth transitions and animations

Prepare your stylesheet for responsive design (future project)

Prerequisites

Basic knowledge of HTML5 and CSS3

Familiarity with the command line and file system navigation

A modern browser (Chrome 78+ recommended)

Project Structure

CSS_advanced/
├── images/                  # All project images
│   ├── favicon.jpg
│   ├── logo-black.png
│   ├── logo-white.png
│   ├── pic-about-01.jpg
│   ├── pic-work-01.jpg
│   ├── pic-work-02.jpg
│   ├── pic-work-03.jpg
│   ├── pic-article-01.jpg
│   ├── pic-article-02.jpg
│   ├── pic-article-03.jpg
│   ├── pic-person-01.jpg
│   ├── pic-person-02.jpg
│   └── pic-person-03.jpg
├── styles/                  # CSS files for each incremental task
│   ├── 1-style.css
│   ├── 2-style.css
│   ├── ...
│   └── 32-style.css
└── index.html               # Starter HTML file (do not rename)

Setup & Usage

Clone the repository:

git clone https://github.com/holbertonschool-web_front_end.git
cd holbertonschool-web_front_end/CSS_advanced

Open index.html in your browser.

Edit the corresponding styles/*.css files to complete each numbered task.

Include your stylesheet by replacing the <link rel='stylesheet' href='#'> in the <head> of index.html with:

<link rel="stylesheet" href="styles/32-style.css">

Refresh the page after each change to validate your CSS.

Tasks

Each CSS file in styles/ corresponds to one or more incremental tasks:

Images: Download and add 10 high-res images plus the provided logos and favicon.

Smooth Scrolling: Apply scroll-behavior: smooth to html.

Color Values: Define base colors for body, links, and specific classes.

Variables: Create and use CSS custom properties for colors.

Font Families: Define custom properties for base and title fonts.

Font Sizes: Set root and body font sizes using variables.

Font Weights: Define regular and bold custom properties.

Google Fonts: Integrate Open Sans and Raleway.

Line Heights: Create variables for line-height and apply to body.

Link Decoration: Remove default text-decoration from links.

Section Header Alignment: Center titles.

Section Tagline Styles: Typography and transform.

Section Title Styles: Font size, color, and margins.

Pseudo-Classes: Style :link, :visited, :hover, :active.

Normalize CSS: Include normalize.css.

Box-Sizing: Add universal box-sizing: border-box.

Container: Center wrapper with max-width and auto margins.

Section Padding: Define spacing variables and apply.

Navbar: Float menu, style list, and nav items.

Grid Layout: Style row and column classes.

Clearfix: Add clearfix after rows.

Simplify Columns: Use attribute selectors for col- classes.

Dark Theme: Style [data-section-theme="dark"].

Dark Theme Fixes: Footer address and social icons.

Services Hover: Background, padding, and hover states.

Buttons: Define variables and style .button.

Testimonials: Avatar radius and quote citation.

Hero Section: Background sizing, spacing.

Header & Logo: Positioning and padding variables.

Nav Hover Decor: Pseudo-elements for underline effect.

Works Section: Image cropping, overlay, and hover transitions.

Testimonials Quotes: Decorative opening quotes.

Transitions & Animations: Add transforms and transitions.

Resources

CSS Reference

Can I Use…

Google Fonts

Normalize.css

License

This project is for educational purposes under Holberton School curriculum guidelines.

