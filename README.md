# NUMWHAN SWEET CAFÉ — Menu & Ordering Starter

A mobile-friendly, static web app prototype for a café menu and pickup-order flow.

## Included
- Responsive menu with search and category filters
- Sample products, prices, and descriptions
- Add/remove items and cart total
- Name/contact, pickup/delivery preference, time, sweetness, ice, and notes fields
- English/Thai toggle
- Prepares an order message using LINE's message URL

## Important before publishing
This is a front-end starter, not a complete order-processing system:
- Sample prices and product details are placeholders; confirm every item and price.
- Emoji are placeholders for product photography.
- No database, owner dashboard, live stock, payment processing, or order notifications are included.
- The LINE message URL may open LINE/share flow, but it does not send the order automatically to the café. Customers must choose a recipient/send, and the café must confirm the order.
- For a dependable live ordering flow, add a known LINE Official Account destination or a backend/form service, plus order notifications.

## Run locally
Open `index.html` in a browser. No build tools required.

## Publish free with GitHub Pages
1. Create a GitHub repository named `numwhan-cafe`.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for the Pages URL to appear in Settings → Pages.

## Customize
Open `index.html` and edit the `products` array near the bottom:
- `name`: English product name
- `th`: Thai product name
- `category`: Coffee, Tea & Matcha, Other, or Sweets
- `emoji`: temporary icon
- `price`: price in THB
- `desc`: short description
- `tag`: optional label, such as Popular or Special

Keep customer privacy in mind: this prototype does not store customer details on a server.
