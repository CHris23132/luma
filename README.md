# Luma landing page

A responsive, standalone landing and order page. Open `index.html` in a browser or upload this folder to a static web host. All five supplied images are included in `assets/`.

The visible **Order now** buttons link directly to the Stripe checkout supplied by the owner: `https://buy.stripe.com/bJeaEX1Yda34gf23wH6c00h`. The checkout was observed listing **Luma for CA$1,995 before applicable tax**, with **Play 3D Inc.** as the merchant. The payment link's product description still mentions the previous name, **Aster**, and should be corrected in Stripe before sharing the page with customers.

## Before sharing publicly

- Confirm the price, tax behavior, availability, shipping, returns, warranty, and any ongoing service fees match the checkout and fulfillment plan.
- Verify all product, privacy, alert, and reliability claims against the finished device and backend. Replace the testimonial placeholder only with consented, real feedback.
- Build a secure post-purchase pairing flow with device ownership and phone-number verification before alerts are enabled.
- Keep Twilio credentials, Render service secrets, payment keys, and customer phone numbers on the server. Never place them in this public HTML file.
- Publish an accurate privacy policy covering event contents, storage, retention, access, and deletion.

The page does not collect phone numbers or payment details. Stripe handles payment on its hosted checkout page. The product illustrations and alert example remain concept previews.
