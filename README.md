# SpendWise Dashboard Shell

A clean, responsive personal finance dashboard built with HTML and CSS only. This is the foundation for the SpendWise capstone project.

## What I Built
A modern dashboard with a sidebar navigation, header, summary section, and 6 category cards showing realistic static financial data for Food, Transport, Rent, Entertainment, Savings, and Utilities.

## Structure
- **index.html** - Page structure: sidebar, header, summary, and cards.
- **style.css** - All styling, layout, theme, responsiveness, and animations.

## What Each Part Does
- **CSS Grid** - Used for the overall page layout (sidebar + main) and for the 6 category cards grid.
- **Flexbox** - Used inside the header, sidebar nav, user card, summary row, and inside each card to align content.
- **CSS Variables (:root)** - Defines brand, accent, surface/background, and text colors. Used consistently so the theme can be changed in one place.
- **Responsive Design** - Media query at 768px collapses the layout to a single column, stacks cards, and simplifies the sidebar for mobile.
- **Micro-interactions** - Cards lift with `transform` + `box-shadow` on hover and focus in 250ms for better UX and keyboard accessibility.
- **Dark Theme** - Overrides only the `:root` variables inside `@media (prefers-color-scheme: dark)` so the dashboard auto-switches to dark mode.

## How to View
Open `index.html` in a browser, or use VS Code Live Server.
Test responsiveness with DevTools Device Toolbar below 768px.