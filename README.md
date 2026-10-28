# Nutrition Nation — Supplement Store Website

A responsive, single-page website created for **Nutrition Nation**, a sports nutrition and supplement store in Jayanagar 9th Block, Bengaluru, Karnataka.

The site helps visitors explore product categories, learn about the store, find its location, and contact the business through WhatsApp.

## Features

- **Store landing page** with fitness-focused branding and calls to action.
- **Product catalogue** with category filters, brand filtering, and sorting options.
- **Product enquiries** through WhatsApp, including product-specific pre-filled messages.
- **Customer enquiry form** that validates the entered details and opens WhatsApp with the enquiry prepared.
- **Store location links** for Google Maps and directions.
- **Fitness-goal shortcuts** for muscle building, weight management, workout performance, everyday wellness, vegetarian nutrition, and vegan nutrition.
- **Responsive navigation** with a mobile menu.
- **Motion and visual effects**, including reveal animations and pointer-based card/hero effects, with reduced-motion considerations.
- **SEO metadata**, theme color, Google Fonts, and Schema.org store structured data.
- **Embedded image assets** in the HTML file.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (Anton and Inter)
- WhatsApp click-to-chat links
- Google Maps links and embedded map
- Schema.org structured data

> This project is currently a standalone HTML page. No frontend framework, package manager, server-side backend, or database is required for the website as provided.

## Project Structure

```text
nutrition-nation/
└── nutrition-nation.html
```

You can rename `nutrition-nation.html` to `index.html` if you want it to be the default entry page for static hosting.

## Run Locally

1. Download or clone the repository.
2. Open `nutrition-nation.html` in a modern web browser.

For a local development server, you can use the VS Code **Live Server** extension, or run Python from the project folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/nutrition-nation.html
```

## Deployment

This is a static website and can be deployed to GitHub Pages, Netlify, or Vercel.

### Netlify

1. Make sure the HTML file is named `index.html` (recommended).
2. Sign in to Netlify.
3. Choose **Add new site** and deploy the project folder, or connect the GitHub repository.
4. Open the generated site URL and test all links and form interactions.

### Vercel

1. Push the project to a GitHub repository.
2. Import the repository into Vercel.
3. For a plain HTML site, use no build command and set the output directory to the directory containing `index.html` (commonly `.`).
4. Deploy and test the live URL.

### GitHub Pages

1. Push the project to GitHub.
2. Rename the page to `index.html` if you want it served as the repository's default page.
3. In the repository, open **Settings → Pages**.
4. Select the deployment source/branch and folder, then save.
5. Wait for GitHub Pages to publish the site.

Hosting provider settings may change; follow the current instructions shown in the provider dashboard.

## Business Details Shown on the Website

- **Business:** Nutrition Nation
- **Address:** 27th Main, 39th Cross Road, Jayanagar 9th Block, Bengaluru, Karnataka 560041, India
- **Phone / WhatsApp:** +91 98454 17412
- **Instagram:** [nutritionnation_bangalore](https://www.instagram.com/nutritionnation_bangalore/)

Please confirm all business details with the client before publishing or sharing the live website.

## Client Handover Checklist

Before launch, confirm the following with the client:

- [ ] Business name, address, phone number, and Instagram account are correct.
- [ ] The WhatsApp number is the correct number for receiving enquiries.
- [ ] Product names, brands, categories, and images are accurate and approved.
- [ ] Product pricing and availability wording are approved. The current page indicates that prices are available on request and stock should be confirmed in-store.
- [ ] Delivery information is confirmed. The current page indicates that local delivery details are still to be confirmed.
- [ ] The client has reviewed the website on mobile, tablet, and desktop.
- [ ] Google Maps directions and WhatsApp links work on the deployed site.
- [ ] The client has approved the website content, photos, and branding for public use.
- [ ] The final live URL and any required access details have been handed over securely.

## Important Notes

- The enquiry form does **not** submit to a backend or save enquiries in a database. It validates the form and opens WhatsApp with a pre-filled message; the visitor must send the message in WhatsApp.
- Product prices and stock are not dynamically connected to an inventory system.
- The site depends on internet access for externally hosted Google Fonts, Google Maps content, WhatsApp, and Instagram.
- The HTML includes embedded image data, so the source file may be relatively large.
- Do not add private credentials, passwords, or API secrets to this repository.

## License and Usage

This website was prepared for a client project. Confirm ownership and permission for the source code, product imagery, logos, fonts, and other assets with the client before reusing or redistributing them. No open-source license is specified here.

---

**Project:** Nutrition Nation Website  
**Location:** Jayanagar 9th Block, Bengaluru, India
