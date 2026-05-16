I read the full Markdown build pack. It describes a full restaurant ordering website, not just a visual homepage. Before we build, we need to decide the business details, menu, design direction, assets, and backend/payment setup.

**Website Structure**
The site should have:

1. **Customer Website**
   - Home screen with Dobara Cafe identity, food photos, status, hours, address, phone, order buttons
   - Menu browser with categories, search, item cards, veg/non-veg, availability, add-to-cart
   - Cart drawer with quantity controls, subtotal, GST, delivery fee, total
   - Checkout with delivery/pickup mode, name, phone, address, location confirmation
   - Razorpay payment flow
   - Success modal with tracking link

2. **Tracking Page**
   - Order number
   - Order status timeline
   - ETA
   - Delivery/pickup labels
   - Cancellation reason if needed
   - Feedback and Google review link

3. **Admin Dashboard**
   - Admin login
   - Live order queue
   - Accept/cancel/status controls
   - ETA buttons
   - Receipt print
   - Menu item add/edit/delete
   - Image upload
   - Pause/accept orders
   - Basic analytics

4. **Backend**
   - Firebase Hosting
   - Firebase Auth
   - Firestore
   - Firebase Storage
   - Cloud Functions
   - Razorpay secure payment verification

5. **PWA / SEO**
   - App icons
   - Manifest
   - Service worker
   - Sitemap
   - Robots
   - Open Graph image

**Necessary Details I Need From You**
Please provide whatever you already have. Missing things can be placeholders for now.

1. Restaurant name exactly:
   - Is it `Dobara Cafe`, `Dobara Café`, or another spelling?

2. Short name / order prefix:
   - Example: `DOB`
   - This becomes order numbers like `DOB-20260516-0001`

3. Tagline:
   - Example: `Fresh bites, brewed twice with love`

4. Cuisine type:
   - Cafe, fast food, bakery, Indian, continental, beverages, multi-cuisine?

5. Address, city, phone, WhatsApp, email

6. Opening hours:
   - Weekdays
   - Weekends
   - Any closed day?

7. Ordering modes:
   - Delivery only?
   - Pickup only?
   - Delivery + pickup?
   - Dine-in info also?

8. Delivery rules:
   - Max delivery radius in km
   - Restaurant latitude/longitude
   - Delivery fee rules, or should I use the default 0-1 km, 1-2 km, etc. pattern?

9. Tax:
   - GST percentage
   - Invoice/business name, GSTIN if needed

10. Menu:
   - Categories
   - Item names
   - Prices
   - Descriptions if available
   - Veg/non-veg markers
   - Availability
   - Images if available

11. Visual assets:
   - Logo
   - Food photos
   - Cafe interior/exterior photos
   - Gallery images
   - Favicon/PWA icons if you have them
   - Open Graph/social sharing image

12. Backend/payment:
   - Firebase project ID and web config
   - Razorpay key ID
   - Razorpay key secret later, stored securely only in functions
   - Admin staff emails
   - Domain name
   - Google review URL

**Design References**
Yes, references would help a lot. Please send any of these:

- 2-5 restaurant/cafe websites you like
- Instagram page or brand photos for Dobara Cafe
- Logo/brand colors
- Menu PDF/photo
- Any competitor sites you want to match or beat
- Any design style preference: premium cafe, cozy local, modern fast-food, playful bakery, elegant restaurant, etc.

One important note: the brief is built around **Firebase + Razorpay + static HTML/CSS/JS**. We can follow that exactly, or we can decide to use React/Next if you want a more app-like developer experience. My recommendation for this project: start with the brief’s static structure unless you specifically want a framework.
