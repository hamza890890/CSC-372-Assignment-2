# Travel Blog Website - CSC372 Assignment 2

## Overview

This repository contains a small travel blog website created as part of the CSC372 Web Development course assignment. The site features a fictional traveler’s blog about Japan, with a focus on the Tohoku region. The project demonstrates the use of basic HTML and CSS, along with deploying the website using GitHub Pages.

---

## Files and Structure

- `index.html`  
  The homepage introducing the travel blog. It includes a welcoming message, an introduction to Japan as a travel destination, and a link to the detailed destination page. The page contains at least 5 different HTML elements and has over 30 lines of content.

- `destination.html`  
  A detailed travel blog post about Japan’s Tohoku region. This page includes:
  - A main heading ("Travelogue: Japan")
  - Three subheadings:
    - Overview: A brief description of the destination
    - Must-See Spots: An ordered list of popular locations with tooltips showing visiting hours
    - Visitor Tips: An unordered list styled with custom bullet icons
  - An image of the main attraction with a caption
  - A testimonial inside a styled blockquote
  - A link back to the homepage
  - Two extra features implemented:  
    1. Background image that repeats and stays fixed during scrolling  
    2. Custom bullet images for the Visitor Tips list  
  - A favicon is also included for the page

- `style.css`  
  The CSS stylesheet for styling `destination.html` according to the specified guidelines. It includes styles for typography, layout, colors, backgrounds, lists, and tooltips. All styling is external and adheres to coding standards.

- `images/`  
  A subfolder containing all images used in the website (e.g., `destination1.png`, background images, favicon, and custom bullet icons).

---

## Deployment

The website is deployed using **GitHub Pages** and can be accessed at:  
`https://your-username.github.io/your-repository-name/`

To update the site, push changes to the `main` branch of this repository. GitHub Pages automatically publishes the latest version.

---

## Features and Compliance

- **HTML/CSS Standards**  
  The code validates with W3C standards. Proper semantic HTML tags are used for content structure, and CSS is maintained in an external stylesheet.

- **Accessibility and Usability**  
  Tooltips provide additional information on must-see spots. Alt attributes are used for images, and links are clear and descriptive.

- **Design Guidelines**  
  - Headings follow specified font sizes, weights, alignments, and underlining  
  - Body background is white with specified text color and font families  
  - Links use the designated color (#A4A400) matching headings  
  - Blockquotes styled with italic text, background color, and bold emphasis on select words

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
