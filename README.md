# Laundry Services - Mobile Hamburger Menu

## Overview
This project implements a pure CSS mobile hamburger menu for the Laundry Web App without using JavaScript or external frameworks like Bootstrap.

## Features
- **Responsive Navbar**: Displays standard link navigation on desktop displays and toggles to a hamburger icon on mobile viewports (≤ 768px).
- **Pure CSS Click Tracking**: Uses the `:focus` / `:focus-within` pseudo-classes to display the dropdown menu list upon clicking/focusing the button.
- **Positioned Absolute Menu**: The menu list appears on the top-right overlay with styling matching the project output specs.

## Project Structure
- `index.html`: Contains HTML semantics for the header, hamburger button, menu list, and main hero content.
- `style.css`: Contains CSS rules, media queries, and focus pseudo-class toggle logic.
- `Readme.md`: Overview documentation.

## How to Run
1. Open `index.html` in any browser.
2. Open Developer Tools (`F12` or `Ctrl+Shift+I`).
3. Toggle Mobile Device View (or resize browser width below 768px).
4. Click on the Hamburger icon (`☰`) to toggle the menu list.