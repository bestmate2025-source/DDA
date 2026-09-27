# BDS Aesthetic LLC — Premium B2B Distributor Website

A modern, premium, professional B2B product showcase and enquiry website for **BDS Aesthetic LLC**, a UAE-based distributor of aesthetic, laser, and skincare equipment.

> **Live Preview:** Open `index.html` in any modern browser. No build step required.

---

## 📋 Table of Contents

1. [Overview](#-overview)
2. [Features](#-features)
3. [Pages & Sections](#-pages--sections)
4. [Product Catalogue](#-product-catalogue)
5. [File Structure](#-file-structure)
6. [How to Use](#-how-to-use)
7. [Customisation Guide](#-customisation-guide)
8. [WhatsApp Integration](#-whatsapp-integration)
9. [SEO Notes](#-seo-notes)
10. [Performance](#-performance)
11. [Browser Support](#-browser-support)
12. [Roadmap / Future Enhancements](#-roadmap--future-enhancements)
13. [Credits](#-credits)
14. [License](#-license)

---

## 🎯 Overview

This is a **single-file HTML website** (with embedded CSS and JavaScript) designed for a premium B2B aesthetic equipment distributor in the UAE/GCC region.

It is **not an e-commerce site** — there is no cart, no checkout, and no online payment. Instead, the focus is on:

- Product discovery and browsing
- Detailed product information
- Multi-image galleries
- Direct enquiry via WhatsApp and quotation forms

The site uses a sophisticated **navy + gold** colour palette with modern typography (Inter + Playfair Display) to convey trust, premium quality, and regional business professionalism.

---

## ✨ Features

### Core Features
- ✅ Sticky, responsive navigation with dropdown product menu
- ✅ Large premium logo (80px desktop / 55px mobile)
- ✅ Hero section with animated entrance and trust indicators
- ✅ Product categories with visual cards
- ✅ 12 featured products with live search and filters
- ✅ Product detail modal with **multi-image gallery** (thumbnails + next/prev)
- ✅ Tabbed product info (Overview, Features, Specs, Applications)
- ✅ Related products section
- ✅ WhatsApp integration everywhere (product-specific deep links)
- ✅ Request a Quote modal with WhatsApp handoff
- ✅ Full contact page with **WhatsApp QR code**
- ✅ Photo Gallery page
- ✅ Careers (Carrier) page
- ✅ Floating WhatsApp button + Back-to-top button
- ✅ Mobile-first responsive design
- ✅ No external JS libraries (vanilla JS only)

### Technical Features
- Pure HTML + CSS + vanilla JavaScript (single file)
- No build tools required
- Google Fonts (Inter + Playfair Display) via CDN
- Font Awesome icons via CDN
- QR code generated via `api.qrserver.com`
- Lazy-loaded images
- Debounced search input
- Modal-based product detail (SPA-style without routing)

---

## 📄 Pages & Sections

| Page | Trigger | Description |
|---|---|---|
| **Home** | Default | Hero, categories, featured products, search, brands, industries, why-choose-us, stats, CTA |
| **About Us** | Nav / Footer | Company profile, mission, stats |
| **Products** | Nav dropdown | 12 product detail pages (opened in modal) |
| **Carrier** | Nav | Careers page with email CTA |
| **Contact** | Nav / Footer | Full contact info, WhatsApp QR, contact form |
| **Photo Gallery** | Nav | Image grid of products and installations |

Product detail is opened as an **overlay modal** rather than a separate page — this keeps the experience fast and avoids full page reloads.

---

## 🛍 Product Catalogue

The following products are pre-configured in the `productsDB` JavaScript object:

| # | Product Name | Code | Category | Availability |
|---|---|---|---|---|
| 1 | Alexandrite Laser | BDS-ALX-001 | Laser Systems | In Stock |
| 2 | ASP LASER | BDS-ASP-002 | Laser Systems | In Stock |
| 3 | B-TOX | BDS-BTX-003 | Skincare & Mesotherapy | In Stock |
| 4 | Cosmuderm | BDS-CSD-004 | Skincare & Mesotherapy | In Stock |
| 5 | DERMASHINE | BDS-DSH-005 | Skincare & Mesotherapy | In Stock |
| 6 | HIFU Manual | BDS-HFM-006 | HIFU Systems | On Request |
| 7 | HIFU ULTHERAPY | BDS-HFU-007 | HIFU Systems | In Stock |
| 8 | PICOSECOND LASER | BDS-PIC-008 | Laser Systems | In Stock |
| 9 | IPL SHR | BDS-IPL-009 | Laser Systems | In Stock |
| 10 | Machines | BDS-MCH-010 | Machines & Devices | On Request |
| 11 | Meso | BDS-MES-011 | Skincare & Mesotherapy | In Stock |
| 12 | N-Cell | BDS-NCL-012 | Skincare & Mesotherapy | In Stock |

Each product includes:
- Name, code, category, brand
- Short + full description
- **Multiple images** (3–4 per product)
- Specifications table
- Features list
- Applications list
- Availability status

---

## 📁 File Structure
