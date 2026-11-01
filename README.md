# Northern Peaks Kitchen — Grab & Go Online Ordering System

Express morning Grab & Go online ordering system and kitchen docket controller for **Northern Peaks Kitchen** (Shop 2, 9 Westralia St, Stuart Park, Darwin, NT).

---

## ⚡ Overview

* **$14.50 Breakfast Combo:** 1 Gourmet Bite (Toasties, Croissants, Bacon & Egg Roll, Cornettos, Cinnamon Scroll) + 1 Regular 8oz Barista Coffee.
* **Paid-First Order Gate:** Only paid orders are transmitted to the kitchen, preventing unpaid waste.
* **Separated Interfaces:**
  * **[`index.html`](index.html)** — Customer-facing mobile ordering & payment app (what the QR code opens).
  * **[`kitchen.html`](kitchen.html)** — Staff kitchen display system (KDS) & direct 80mm thermal docket printer controller (bookmarked on counter iPad).
* **Thermal Docket Printer Integration:** Automatically formats standard 80mm POS dockets with station routing (Grill Station vs Barista Station).

---

## 🚀 Instant 1-Click Deployment Options

### Option 1: GitHub Pages (Free & Built-in)
1. Go to this repository on GitHub: **Settings &rarr; Pages**.
2. Under **Build and deployment**, select:
   * Source: `Deploy from a branch`
   * Branch: `main` / `root`
3. Click **Save**. Within 60 seconds, your site is live at:
   `https://prashantrijal40.github.io/NorthernPeaks_GrabAndGO/`

### Option 2: Vercel / Netlify (Custom Domain)
1. Import this GitHub repository into [Vercel](https://vercel.com) or [Netlify](https://netlify.com).
2. Connect your custom domain: `https://order.northernpeaks.com.au`.

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `index.html` | Customer mobile ordering web app (QR code target). |
| `kitchen.html` | Dedicated Staff Kitchen Display & Docket Printer controller. |
| `Northern_Peaks_Grab_And_Go_Sign.pdf` | Print-ready A5/A4 counter standee with QR code. |
| `Northern_Peaks_Grab_And_Go_Sign.pptx` | Fully editable counter sign template for Canva / PowerPoint. |
| `Northern_Peaks_Grab_And_Go_Sign.svg` | Scalable vector counter artwork. |
| `Northern_Peaks_Grab_And_Go_Sign_Preview.png` | High-resolution preview of the counter QR sign. |
