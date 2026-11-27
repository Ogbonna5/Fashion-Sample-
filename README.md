# VELORA — Fashion Store Demo

Responsive React + Vite fashion catalogue demo with category filters, product search, quick-view details, size/color selection, persistent cart and WhatsApp checkout.

## Run locally
1. Install Node.js (LTS).
2. Open this project folder in VS Code.
3. Run `npm install`
4. Run `npm run dev`
5. Open the URL Vite prints.

## Customize
- Edit product data and image URLs in `src/main.jsx` (`products`).
- Set `WA_NUMBER` in `src/main.jsx` to the shop WhatsApp number in international format, digits only (e.g. `2348012345678`).
- Edit prices, available colors, sizes, descriptions and images in the product data.
- Edit styles in `src/style.css`.

## Functional limitations
This demo routes checkout to WhatsApp. It does not process online payments, authenticate customers, manage real inventory or send newsletter email. The newsletter form is clearly marked as a demo. Replace demo details before client use.
