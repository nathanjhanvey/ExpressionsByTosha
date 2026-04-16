Expressions by Tosha Hanvey
Live site: https://nathanjhanvey.github.io/ExpressionsByTosha/
Original healing art by survivor and speaker Tosha Hanvey. Affirmation prints, apparel, mugs, magnets, digital downloads, and custom commissions — designed to bring calm, hope, and encouragement to people facing anxiety, depression, and trauma.
---
About This Site
This is a complete single-file storefront and portfolio built with HTML, CSS, and JavaScript. It is hosted for free on GitHub Pages with a Firebase Firestore backend for real-time data storage.
Features include:
Full product shop with category filters, options, and per-option pricing
Shopping cart with digital/physical separation
Two-step checkout with CashApp and PayPal payment routing
Gift orders with separate shipping address and handwritten message
Shipping rate calculator with free shipping threshold
Sales tax support
Digital download delivery
Custom commission request form with artwork selector
Newsletter signup
Customer reviews / testimonials
Admin dashboard with real-time KPIs, order tracking, and revenue
Four switchable color themes
Automatic artwork watermarking on upload
Newsletter subscriber management with CSV export
Full SEO meta tags, Open Graph, and structured data
Google Analytics 4 integration
Pinterest verification support
---
File Structure
```
/
├── index.html        ← The entire site (edit this file to make changes)
├── 404.html          ← Custom page not found
├── robots.txt        ← Search engine crawler instructions
├── sitemap.xml       ← Site map for Google Search Console
├── _config.yml       ← GitHub Pages configuration
├── LICENSE           ← Copyright declaration
└── README.md         ← This file
```
---
How to Update the Site
All changes are made by editing `index.html` in this repository.
To update via GitHub web interface:
Click `index.html` in the repository
Click the pencil icon ✏️ (Edit this file)
Make your changes
Scroll down and click Commit changes
The live site updates within about 30 seconds
---
Firebase Setup (One-Time — Required for Orders to Save)
Without Firebase, customer orders are not permanently stored. This setup takes about 10 minutes and is completely free.
Go to console.firebase.google.com and sign in with a Google account
Click Add Project → name it `ExpressionsByTosha` → Create
In the left menu click Firestore Database → Create database → Start in test mode → select a location → Enable
Click the gear icon ⚙ → Project settings → scroll to Your apps → click the web icon `</>` → register the app
Copy the `firebaseConfig` object shown on screen
On the live site, open Admin (⚙ link in the footer) → Settings → paste the config into the Firebase box → click Connect Firebase
The green "Connected" banner confirms it is working. All orders, products, and subscribers now sync live across every device.
---
Google Search Console Setup (Recommended)
Submitting the site to Google Search Console helps it appear in search results faster.
Go to search.google.com/search-console
Click Add property → enter `https://nathanjhanvey.github.io/ExpressionsByTosha/`
Choose HTML tag verification → copy the meta tag content value
On the live site, open Admin → Settings → paste the value into the Pinterest Verification field (works for Google verification too) → Save
Back in Search Console, click Verify
Click Sitemaps in the left menu → enter `sitemap.xml` → Submit
---
Admin Panel
The admin panel is accessible via the small ⚙ Admin link in the footer of the live site.
Default password: `Tosha2024`
Change this immediately in Admin → Settings → Change Password.
Admin tabs:
Tab	What it does
Dashboard	Live KPIs — views, orders, revenue, category breakdown
Products	Add, edit, toggle on/off, delete products
Categories	Add custom product categories
Reviews	Add and manage customer testimonials
Subscribers	View and export newsletter signups
Themes	Switch between four color themes
Settings	Firebase, payment, shipping, tax, SEO, watermark, password
---
Adding a Custom Domain (Optional)
A custom domain like `expressionsbytosha.com` can be connected to this site for free through GitHub Pages.
Buy the domain from Namecheap or Google Domains (~$12/year)
In the domain registrar's DNS settings, add these A records pointing to GitHub:
```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
In this repository, go to Settings → Pages → enter your custom domain → Save
Check Enforce HTTPS
DNS propagation takes up to 48 hours
---
Technology
Frontend: HTML5, CSS3, Vanilla JavaScript (no frameworks)
Backend: Firebase Firestore (free tier)
Hosting: GitHub Pages (free)
Payments: CashApp and PayPal.me direct links
Analytics: Google Analytics 4
---
Copyright
© Tosha Hanvey. All rights reserved. See LICENSE for details.
Built with love for Tosha by her Husband. 💜
