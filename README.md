# Marginalia — Books, Secondhand & New

A demo bookshop storefront built as a single-file, static website (HTML + CSS + vanilla JavaScript — no backend, no build step required).

## Overview

Marginalia is a fictional neighborhood bookshop selling secondhand and new books across six departments: Fiction, Poetry, Nonfiction, Mystery & Crime, Sci-fi & Fantasy, and Children's. The site includes full browsing, cart, checkout, and an AI-style shop assistant chatbot — all running entirely in the browser.

## Features

- **Home page** — hero section, department grid, featured/new arrivals, shop highlights
- **Shop all / Listing page** — full catalog with category, condition, and price filters, sorting, and live search
- **Product detail page** — full book info, quantity selector, related books
- **Quick view** — modal preview without leaving the current page
- **Cart** — add/remove items, adjust quantities, live subtotal
- **Wishlist** — save books for later via heart icon
- **Checkout flow** — contact, shipping, and (demo/fake) payment form with order summary, card number/expiry auto-formatting
- **Order confirmation & order history** — completed orders are saved and viewable on an "Orders" page
- **Persistence** — cart, wishlist, orders, and newsletter subscription are saved in `localStorage` and survive page refresh
- **Newsletter signup** — simple email capture with persisted subscribed state
- **AI shop assistant (chatbot)** — rule-based local assistant for book recommendations, similar-book suggestions, FAQs (hours, trade-ins, special orders), and can add books to the cart directly from chat
- **Responsive design** — mobile nav, adaptive grid layouts

## Tech Stack

- HTML5
- CSS3 (custom properties / CSS variables, no framework)
- Vanilla JavaScript (no dependencies, no build tools)
- Google Fonts: Fraunces, Literata, IBM Plex Mono
- Unsplash images for book covers (used under the Unsplash License)

## File Structure

This is a **single self-contained HTML file** — all CSS and JavaScript are inline within `index.html`. No installation or build process needed.

```
index.html   ← the entire website (HTML, CSS, JS)
```

## Getting Started

1. Download `index.html`
2. Open it directly in any modern browser (Chrome, Firefox, Safari, Edge)

No server, no `npm install`, no dependencies required.

## Data

All book data (titles, authors, prices, categories, ratings, condition, cover images) is hardcoded in a `BOOKS` array inside the script — this can be edited directly to change the catalog.

## Notes

- This is a **demo storefront**: checkout does not process real payments, and no data is sent to any server — everything (cart, wishlist, orders) is stored locally in the visitor's own browser via `localStorage`.
- Built for demonstration/portfolio purposes.

## License

Demo project — free to use and modify.# -books-week4
Marginalia is a demo bookshop storefront selling secondhand and new books across fiction, poetry, nonfiction, mystery, sci-fi, and children's titles. Features browsing by department, search, wishlist, cart, full checkout flow, order history, and an AI shop assistant chatbot for recommendations and support.
