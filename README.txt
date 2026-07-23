COONEY PROVISIONS — STATIC SITE
================================

FILES
  index.html
  styles.css
  images/  (logo.png, hero-truck.jpg, fleet-bays.jpg, warehouse.jpg, crew.jpg)

DEPLOY TO CLOUDFLARE PAGES
  1. Cloudflare dashboard > Workers & Pages > Create > Pages > Upload assets
  2. Drag this entire folder in
  3. Deploy. No build command, no framework, no dependencies.

TO CHANGE THE PHONE NUMBER
  Search index.html for 6109486900 and 610-948-6900. Four places total.

TO CHANGE THE EMAIL
  Search index.html for info@cooneyprovisions.com. Two places.

TO SWAP A PHOTO
  Drop a new file in images/ using the same filename. Nothing else changes.

TO UPGRADE THE MAILTO FORM TO A REAL FORM
  The "Email a Visit Request" button is a mailto link. Replacing it with a
  Cloudflare Pages Function + Resend does not require changing anything else
  on the page.
