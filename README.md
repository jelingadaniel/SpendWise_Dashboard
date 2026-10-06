# SpendWise Dashboard

SpendWise is a responsive personal finance dashboard designed to provide a clear visual overview of monthly spending and budgeting. This project focuses on building the visual foundation of a financial management application using HTML and modern CSS techniques.

## Project Files

### `index.html`

The `index.html` file contains the structure of the SpendWise dashboard.

It includes:

* A sidebar navigation menu
* SpendWise branding
* Dashboard header and welcome message
* User profile section
* Monthly budget summary
* Total budget, total spent, and remaining balance
* Six spending category cards:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Savings
  * Utilities
* Static spending amounts and progress indicators

The HTML uses semantic elements such as `<aside>`, `<main>`, `<header>`, `<section>`, `<nav>`, and `<article>` to organize the dashboard.

## `style.css`

The `style.css` file controls the appearance and layout of the dashboard.

### CSS Grid

CSS Grid is used to create the main dashboard structure and arrange the spending category cards.

The main dashboard uses a sidebar and a main content area, while the category cards are displayed in a three-column grid on larger screens.

### Flexbox

Flexbox is used for:

* Sidebar navigation items
* Header content
* User profile
* Summary cards
* Category card content
* Responsive navigation

### CSS Custom Properties

The project uses CSS variables inside `:root` to create a consistent theme.

Examples include:

* `--brand-color`
* `--accent-color`
* `--background-color`
* `--surface-color`
* `--primary-text`
* `--secondary-text`

Using CSS variables makes it easier to change the application's color scheme.

### Responsive Design

A media query is included for screens smaller than 768px.

On smaller screens:

* The dashboard changes to a single-column layout
* The sidebar becomes more compact
* Navigation items wrap
* Summary cards stack vertically
* Category cards stack into one column

The layout can be tested using the browser's DevTools Device Toolbar.

### Card Micro-interactions

The spending cards include subtle hover and keyboard-focus effects.

When a user hovers over or focuses on a card:

* The card moves slightly upward
* The box shadow becomes stronger

The animation lasts 200ms, keeping the interaction quick and subtle.

### Dark Theme

The project also includes a dark theme using:

```css
@media (prefers-color-scheme: dark)
```

The dark theme works by overriding the CSS variables defined in `:root`.

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Custom Properties
* CSS Media Queries
* CSS Transitions

## Project Goal

The goal of this project is to create the visual foundation for the SpendWise financial management application. Functionality such as adding expenses, calculating totals, filtering transactions, and storing financial data can be added in future stages.

## How to Run

1. Download or clone the project.
2. Make sure `index.html`, `style.css`, and `README.md` are in the project folder.
3. Open `index.html` in a web browser.
4. Use the browser's DevTools Device Toolbar to test the responsive layout.

## Current Status

This version focuses on the **dashboard shell and visual design**. No JavaScript functionality or database integration has been added yet.

````

### Your final folder should look like this:

```text
SpendWise/
│
├── index.html
├── style.css
└── README.md
````

That will satisfy the **three-file submission requirement** you listed.
