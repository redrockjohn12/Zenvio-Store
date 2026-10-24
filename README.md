# Zenvio Store

A polished, responsive e-commerce landing page built as a frontend interface project.

## Tech stack
- Next.js App Router
- React functional components and hooks
- Tailwind CSS
- Lucide icons

## Features
- Mobile-first layout with tablet and desktop breakpoints
- Accessible responsive navigation
- Product search and category filtering
- Reusable product cards
- Interactive shopping bag with quantity controls and subtotal
- Newsletter form UI (demonstration only; no data is saved)
- SEO page metadata and semantic HTML

## Run locally

Install Node.js 20+ and then:

```bash
npm install
npm run dev
```

Open the local development URL shown in the terminal. To check production compilation:

```bash
npm run build
npm start
```

## Project structure

- `app/layout.jsx` — document shell and metadata
- `app/page.jsx` — homepage composition and interactive state
- `app/globals.css` — Tailwind layers and global styles
- `components/Header.jsx` — navigation, mobile menu and search
- `components/ProductCard.jsx` — reusable product card
- `components/CartDrawer.jsx` — interactive shopping bag
- `lib/products.js` — sample product catalog
- `tailwind.config.js` — design tokens and source scanning

## Design decisions

The visual system uses generous spacing, rounded cards, a restrained violet accent, bold headings and soft gradient product panels. The grid shifts from one column on narrow screens to two and three columns on wider screens. The catalog is intentionally static: this assessment focuses on frontend composition and responsive behavior rather than backend integrations.

Product visuals use emoji placeholders to avoid dependence on remote assets. Pricing and products are illustrative. Cart state is in memory and resets on reload; checkout is intentionally disabled. The newsletter form does not send or store email addresses.

## Deployment

1. Create a new GitHub repository named `zenvio-store`.
2. Upload the contents of this project directory to the repository root.
3. In Vercel, import the GitHub repository and keep the detected Next.js settings.
4. Deploy, then test the live site on phone, tablet and desktop screen widths.

## Suggested demonstration video

Show mobile navigation, scrolling, product filters, search, adding two products to the bag, quantity adjustments, and a desktop-width layout. Mention the static demo limitations.
