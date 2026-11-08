# Sportiva — React E-commerce Frontend

A responsive React + Vite storefront concept for sportswear and fitness equipment.

## Included pages
- Home
- Shop / category listing
- Product details
- Wishlist
- Cart
- Checkout (demo only)
- Login / Register (demo UI only)
- My Account
- About Us
- Contact Us
- Blog
- Blog Article
- Track Order

## Requirements
- Node.js 18+ (recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Notes
- React Router handles page navigation.
- Cart and wishlist are persisted in browser `localStorage`.
- Product data is currently sample data in `src/data.js`.
- Product photos are remote Unsplash images; an internet connection is needed to load them.
- Checkout, authentication, contact form, newsletter and tracking are frontend demos. No real payment, account creation, email delivery, shipping API or backend is connected.
- To make this a production store, connect a backend/API, database, authentication, inventory and a payment provider. Never store payment card details in frontend code.
