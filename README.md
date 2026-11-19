# Grab Your Desire — upgraded website

A responsive, single-page shopping showcase with four individual store views:
- Grocery Shop
- Pharmacy
- General Store
- Home Décor

## Run the website
1. Extract this ZIP file.
2. Open the `grab-your-desire-upgraded` folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the VS Code **Live Server** extension.
4. Keep the `assets` folder beside `index.html` — it contains the custom homepage hero image.

The site uses remote Unsplash images for the four shop cards, so those images need an internet connection. The custom hero image and logo are local / embedded.

## Features
- Custom logo and matching brand palette
- Lifestyle hero image
- Four store categories with their own product collections and contact sections
- Product search within each store
- Add-to-cart, quantity controls, remove-at-zero and total calculation
- Enquiry forms that open the visitor's email application
- Responsive mobile navigation and layouts

## Important: update before publishing
Open `index.html` and edit the `BUSINESS` settings near the bottom of the file:
- `phone`
- `email`
- `address` is shown in the contact section; replace the visible sample address text too
- `whatsapp` (digits only, country code included, e.g. 92...)

Also update the individual store phone, email and address values inside the `stores` object. Replace sample products and prices with your real stock and verified prices.

## Important limitations
This is a front-end showcase, not a complete ecommerce backend. The cart is held in the visitor's browser session, checkout sends an enquiry (WhatsApp only after a real WhatsApp number is configured, otherwise email), and no payment gateway, inventory system, user accounts, or order database is connected. The forms rely on the visitor having an email app configured.

Pharmacy listings are placeholders, not medical advice. Only list lawful products and ensure medicines are sold and dispensed under appropriate professional oversight.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `grab-your-desire`.
2. Upload `index.html`, `README.md`, and the complete `assets` folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages URL to appear in the Pages section.
