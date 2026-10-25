# Runatechs — Vercel-ready website

## Deployment
Extract this folder, commit its contents to a Git repository and import into Vercel. Framework: Other. Build command: npm run build. Output directory: public. No dependencies or environment variables required. Add www.runatechs.com and runatechs.com in Vercel, then apply the DNS records Vercel provides. No Vercel deployment or domain connection has been performed.

## Easy catalogue updates
Open /catalog-editor.html on the hosted website. Add or choose a product, edit its fields, click Save to working catalogue, then Download products.json. Replace public/products.json in the repository. Put new photos in public/assets and use paths like /assets/new-cooker.webp. Commit and redeploy. Changes in the editor are local working edits, not live server writes. Download before closing the editor. This is not an authenticated CMS dashboard.

Each product supports name, unique ID, description, category, condition, price, image paths, featured status and availability. Blank prices show Confirm price. Supply accurate specifications and additional photos: some supplied items have only one view. Verify provisional photo groupings before launch. Product prices and most conditions were not supplied and remain for confirmation. Gold-tone jewellery is not represented as solid gold.

## Text, pricing and testimonials
Page copy: public/*.html. Service packages and currency estimate factors: public/app.js. Currency equivalents are illustrative fixed estimates, not live exchange rates. Confirm service prices and scope before launch. Domain, hosting, advertising and licences are separate.

Ten empty testimonial slots: public/testimonials.json. Enter genuine client quotes, names and businesses and set approved to true. Approved entries appear in the swipe carousel. No testimonials were invented.

Project cards link to the two provided sites. TeesCloset catalogue features were reviewed; EkoTechCentre could not be retrieved. Actual project screenshot galleries remain to be supplied; the existing visual panels are title artwork. Confirm all project scope descriptions before launch.

Main brand: RUNATECHS DIGITAL SERVICE. Shop: RUNATECHS NIG LTD / Runatechs Nigeria Limited. Confirm legal entity details before adding registration claims.

## Shopping
The basket is saved in the visitor's browser. Checkout validates name, phone, address, city and state/country. It prepares a WhatsApp message with product names, IDs, quantities, prices and delivery information for the visitor to review and send. It does not automatically accept an order or collect payment. Unlisted prices, availability, delivery and terms must be confirmed in conversation. Primary WhatsApp: +234 916 255 8431.

## Speed and SEO
Static HTML, local system fonts, deferred JavaScript, WebP images and lazy-loaded product images. No framework runtime or third-party scripts. Vercel caching/security headers, metadata, canonical links, sitemap, robots and Organization schema included. Sub-second loading is a target, not a guarantee. Measure the deployed site with Lighthouse/PageSpeed on mobile networks.

## Checks
JavaScript syntax, all product image paths, unique product IDs, catalogue data and local page links verified. Desktop homepage and basket reviewed in browser. Actual mobile device checks and production performance testing remain outstanding. No WhatsApp messages sent.

Local preview: npm run dev (or python3 -m http.server 3000 --directory public)
Open http://localhost:3000. File:// opening will not load JSON catalogues.
