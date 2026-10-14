# Healthy Nut Butters — Cyprus storefront

A responsive Next.js storefront demo using the uploaded HNB logo (with orange background removed for navigation), a bold orange-and-black visual system, and six illustrative peanut butter products.

## Run locally

1. Install Node.js 20 or later.
2. In this folder run `npm install`.
3. Run `npm run dev`.
4. Open http://localhost:3000.

For a production check, run `npm run build` and `npm start`.

## Features

- Responsive homepage and navigation
- Search and flavor category filters
- Product detail modal
- 340g / 500g / 1kg sample price options
- Cart with quantity editing and browser localStorage persistence
- Euro prices and illustrative €5 Cyprus shipping estimate
- Sample newsletter interaction (no email sent)
- Checkout clearly disabled / demo-only

## Important before launch

All products, prices, sizes, nutrition/ingredient claims, ratings, and shipping fees are placeholders and **must be verified**. The stylized jars are CSS illustrations, not real packaging photographs. Confirm ingredients, peanut/allergen labeling, VAT, food business requirements, privacy policy, returns, and delivery zones. Connect inventory, payments, order management, transactional email, and newsletter service before taking orders. The contact email is a placeholder.

## Editing

Edit `products` in `app/page.tsx`, colors in `app/globals.css`, and replace `public/hnb-logo.png` if needed.
