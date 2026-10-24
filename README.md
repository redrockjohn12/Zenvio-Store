# Zenvio Store — Modern Lifestyle Frontend

A responsive, frontend-only lifestyle storefront built with Next.js, React and Tailwind CSS. The visual design uses sage green, warm neutrals, editorial typography and large lifestyle photography.

## Features
- Mobile, tablet and desktop responsive layouts
- Announcement strip and responsive navigation
- Image-led hero and three clickable collection tiles
- Searchable and filterable product catalog
- Shopping bag with add/remove/quantity controls and subtotal
- Demo newsletter form (no data stored)

## Architecture
- `app/page.jsx` — home page, collection filtering and shopping bag state
- `app/layout.jsx` — app metadata and root layout
- `app/globals.css` — base styles and font choices
- `components/Header.jsx` — navigation and search input
- `components/ProductCard.jsx` — reusable product display
- `components/CartDrawer.jsx` — interactive cart drawer
- `lib/products.js` — demo catalog data
- `tailwind.config.js` — design colors and Tailwind configuration

## Design decisions
- Sage and warm neutrals provide a calm modern-lifestyle identity.
- A high-contrast hero improves headline readability over photography.
- Responsive grids adapt from one to two to three columns.
- Reusable components isolate the navigation, catalog cards and cart.
- Accessible labels and visible focus outlines support keyboard navigation.

## Run locally
```bash
npm install
npm run dev
```

## Deploy
Import the repository into Vercel as a Next.js project with root directory `./`.

## Notes
This is a portfolio/demo storefront. Checkout is intentionally disabled. Newsletter sign-up is simulated. Product and lifestyle photography is loaded from Unsplash URLs and requires an internet connection. Product imagery is illustrative, not guaranteed to match listed merchandise. No backend or payment processing is implemented.
