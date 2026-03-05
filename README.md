# Royan Apparels — Official Website

> **Crafting Threads of Trust** — Premium knit garment sourcing & manufacturing from Dhaka, Bangladesh.

[![Live Site](https://img.shields.io/badge/Live%20Site-Netlify-00C7B7?style=flat-square&logo=netlify)](https://royangroupbd.com)
[![HTML](https://img.shields.io/badge/HTML-Single%20File-E34F26?style=flat-square&logo=html5&logoColor=white)](./royan-apparels.html)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=flat-square)](./LICENSE)

---

## Overview

This is the official website for **Royan Apparels**, a knit garment sourcing and manufacturing company based in Uttara, Dhaka, Bangladesh. The site is built as a single self-contained HTML file with all assets embedded, plus a downloadable company profile PDF.

**Founded:** 2022 &nbsp;|&nbsp; **Location:** Dhaka, Bangladesh &nbsp;|&nbsp; **Contact:** royangroupbd@gmail.com

---

## Project Structure

```
royan-apparels/
├── royan-apparels.html              # Main website (all CSS, JS & images embedded)
├── Royan_Company_Profile_Booklet.pdf  # Downloadable company profile (17 MB)
└── README.md                        # This file
```

> ⚠️ **Important:** `royan-apparels.html` and `Royan_Company_Profile_Booklet.pdf` must remain in the **same directory** for the download button to work correctly.

---

## Features

- **Single-file website** — all CSS, JavaScript, and product images embedded as base64
- **Fully responsive** — mobile, tablet, and desktop layouts
- **Mobile hamburger menu** — animated drawer navigation for small screens
- **Scroll progress bar** — page reading indicator at the top
- **Custom cursor** — branded green dot + ring cursor
- **Book-style product gallery** — 7 categories with page-flip navigation
- **Scroll reveal animations** — elements animate in as you scroll
- **Contact / booking form** — with validation and WhatsApp integration
- **Downloadable company profile PDF** — accessible from hero, mid-page banner, and footer
- **Back to top button** — appears after scrolling 500px
- **WhatsApp direct links** — pre-filled message for quick buyer contact

---

## Sections

| Section | Description |
|---|---|
| Hero | Brand headline, CTAs, key stats, and PDF download |
| About | Company overview, vision & mission cards |
| Founder | Portrait, nameplate, bio, and credentials |
| Services | 4-card services grid (sampling, manufacturing, QC, delivery) |
| Products | Interactive 7-category book gallery with product photos |
| Why Royan | 7 differentiators |
| Clients | Buyer logo grid (11 global brands) |
| Download | Company profile PDF download banner |
| Booking | Contact form with WhatsApp fallback |
| Footer | Full sitemap, contact details, PDF link |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript (ES5-compatible) |
| Fonts | Cormorant Garamond · DM Sans · Bebas Neue (Google Fonts) |
| Images | Embedded as base64 data URIs |
| PDF | Served as a separate static file |

No frameworks. No build tools. No dependencies. Drop the two files anywhere and it works.

---

## Local Preview

No server required — just open the file directly:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/royan-apparels.git
cd royan-apparels

# Open in browser (macOS)
open royan-apparels.html

# Open in browser (Windows)
start royan-apparels.html

# Open in browser (Linux)
xdg-open royan-apparels.html
```

Or drag `royan-apparels.html` into any browser window.

---

## Deployment

### Netlify (Recommended)

See the step-by-step guide below in this README, or visit [netlify.com](https://netlify.com).

### Any Static Host

Since the site is a plain HTML file with no build step, it works on:
- **Netlify** — drag & drop deploy, free tier
- **Vercel** — import GitHub repo, zero config
- **GitHub Pages** — enable Pages on this repo
- **Hostinger / Bluehost / cPanel** — upload via File Manager
- **AWS S3** — enable static website hosting
- **Cloudflare Pages** — connect repo, auto-deploy

---

## Netlify Deployment Guide

### Option A — Drag & Drop (Fastest, no account needed)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Sign up for a free account (GitHub, Google, or email)
3. On your dashboard, scroll to the **"Want to deploy a new site without connecting to Git?"** section
4. Drag the **entire project folder** (containing both files) into the drop zone
5. Netlify deploys instantly and gives you a URL like `https://random-name-123.netlify.app`
6. To set a custom domain: **Site settings → Domain management → Add custom domain**

### Option B — Deploy via GitHub (Recommended for updates)

1. Push this repo to GitHub (see below)
2. Go to [app.netlify.com](https://app.netlify.com) → **"Add new site" → "Import an existing project"**
3. Connect your GitHub account
4. Select the `royan-apparels` repository
5. Configure build settings:
   - **Build command:** *(leave blank)*
   - **Publish directory:** `.` *(or leave blank — root)*
6. Click **"Deploy site"**
7. Every future `git push` to `main` will auto-redeploy the site

### Setting a Custom Domain on Netlify

1. In Netlify dashboard → **Site settings → Domain management**
2. Click **"Add custom domain"** → enter `royangroupbd.com`
3. Netlify will show you nameserver records
4. Log into your domain registrar (e.g. GoDaddy, Namecheap)
5. Replace existing nameservers with Netlify's:
   ```
   dns1.p01.nsone.net
   dns2.p01.nsone.net
   dns3.p01.nsone.net
   dns4.p01.nsone.net
   ```
6. Wait 24–48 hours for DNS propagation
7. Netlify automatically provisions a **free SSL certificate** (HTTPS)

---

## Pushing to GitHub

```bash
# 1. Create a new repo on github.com (name it: royan-apparels)
#    Make it Private if you prefer

# 2. Initialize and push from your local folder
cd path/to/royan-apparels

git init
git add .
git commit -m "Initial commit — Royan Apparels website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/royan-apparels.git
git push -u origin main
```

> Replace `YOUR_USERNAME` with your actual GitHub username.

---

## Updating the Site

After making changes to `royan-apparels.html`:

```bash
git add royan-apparels.html
git commit -m "Update: describe your change here"
git push
```

If connected to Netlify via GitHub, the live site updates automatically within ~30 seconds.

---

## Contact

**Royan Apparels**
5th Floor, House #125, Road No. 13, Sector 10
Uttara, Dhaka 1230, Bangladesh

- 📞 01966646889 / 01796955655
- 📧 royangroupbd@gmail.com
- 🌐 www.royangroupbd.com
- 💬 [WhatsApp](https://wa.me/8801966646889)

---

## License

© 2026 Royan Apparels. All rights reserved.
This codebase and all assets are proprietary. Unauthorized copying, redistribution, or use is prohibited.
