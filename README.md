# PT Semesta Olah Lestari Website

Official static website for **PT Semesta Olah Lestari (SOL)**, a footwear-component manufacturer based in Tangerang, Indonesia.

The site presents SOL's company profile, products, production capabilities, quality-control process, selected clients, and contact information in a clean, responsive format for local and international visitors.

## Features

- **Three languages:** Bahasa Indonesia, English, and Simplified Chinese
- Audience-specific English and Chinese copy rather than literal word-for-word translations
- Responsive desktop, tablet, and mobile layouts
- Product showcase for **Outsole, Foxing, and Rubber Tile**
- Production-process and quality-control sections
- Client-logo carousel
- Factory and production photography
- Email, WhatsApp, and Google Maps contact links
- Accessible navigation labels and image descriptions
- Language preference saved in the browser when local storage is available
- No framework, package manager, or build step required

## Project Structure

```text
PT-Semesta-Olah-Lestari-Website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── sol-logo.jpg
    ├── clients/
    └── company/
        ├── factory-entrance.jpg
        ├── factory-production-line.jpg
        ├── foxing-application.jpg
        ├── outsole-pair.jpg
        ├── production-operator.jpg
        └── rubber-tile.jpg
```

## Local Preview

For a quick preview, open `index.html` in a browser.

For the most reliable local preview, serve the folder with a simple local server such as **VS Code Live Server**. No installation or build process is otherwise required.

## Deployment

The website can be deployed directly to any static hosting service, including:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel

For GitHub Pages, upload the contents of this project folder to the repository used for the site. Keep the folder structure intact so all local assets resolve correctly.

## Editing Content

### Bahasa Indonesia

The main Indonesian page content is stored in `index.html`.

### English and Simplified Chinese

English and Chinese translations are stored in `script.js`. Translation keys correspond to the Indonesian source text, while the translated copy is written naturally for each audience.

When changing Indonesian text in `index.html`, update the matching translation entry in `script.js` as well.

### Styling

Layout, typography, responsive behavior, and brand styling are defined in `styles.css`.

### Images

Website images are stored under `assets/`.

The current foxing product image is also embedded directly in `index.html` as a data URI. This prevents the image from breaking if the external foxing JPG is accidentally omitted during deployment. The original `assets/company/foxing-application.jpg` file is still included for future editing.

## Contact Information

The website currently displays:

**Factory address**  
Jl. Raya Rajeg-Mauk No.8, RT.02/RW.07, kelurahan Rajeg Mulya, Kec. Rajeg, Kabupaten Tangerang, Banten 15540, Indonesia

The Indonesian postal address is intentionally kept unchanged across all three language versions to make mapping and directions more reliable.

**WhatsApp**  
(021) 59350530  
`https://wa.me/622159350530`

The site uses WhatsApp instead of a separate phone-call contact option. Before public launch, confirm that this number is active on WhatsApp or WhatsApp Business so visitors can successfully start a chat.

## Updating the Live Site

When publishing a new version:

1. Replace `index.html`, `styles.css`, and `script.js` with the latest files.
2. Upload any new or changed files inside `assets/`.
3. Preserve the existing directory structure and filename capitalization.
4. Refresh the deployed site and test all three languages.
5. Test the WhatsApp, email, and Google Maps links.
6. Check the site on both desktop and mobile after deployment.

## Notes

- The website is intentionally lightweight and framework-free.
- Product and company copy is based on the supplied PT Semesta Olah Lestari company profile and subsequent website revisions.
- The site uses supplied company/product imagery and does not display stock-photo attribution text in the product cards.

---

© PT Semesta Olah Lestari. All rights reserved.
