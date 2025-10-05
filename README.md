# 🛍️ StyleHub — Modern Fashion E-Commerce Website (HTML + CSS)

A fully responsive, modern front-end design for an online fashion store.  
Built entirely with **pure HTML and CSS** (no JavaScript, no frameworks).

---

## 📋 Overview

**StyleHub** is a multi-page static e-commerce website designed to showcase a fashion brand.  
The project includes core pages such as Home, Product Categories, Product Details, About Us, and Customer Support.

Every page is mobile-responsive and styled consistently with a modern minimalist design.

---

## 🌐 Live Pages (Structure)

| Page                  | File              | Description                                                         |
| --------------------- | ----------------- | ------------------------------------------------------------------- |
| 🏠 Home               | `index.html`      | Hero banner, product grid, social proof section, footer             |
| 🛒 Product Categories | `categories.html` | Breadcrumb navigation, filter sidebar, responsive product grid      |
| 👗 Product Details    | `product.html`    | Product gallery, thumbnails, description, reviews                   |
| 🏢 About Us           | `about.html`      | Brand story, sustainability info, team section, timeline, map embed |
| 📞 Customer Service   | `support.html`    | FAQ accordion, contact options, self-service tools                  |
| 💬 Global Styles      | `css/styles.css`  | Global layout, typography, responsive design                        |
| 🧱 Reset              | `css/reset.css`   | CSS reset for consistent base styling                               |

---

## 🎨 Key Features

### 🖼️ Home Page (`index.html`)

- Full-width **hero banner** with promotional message and overlay
- **Responsive image scaling** — hero image adjusts perfectly on all screens
- **Social Proof section** with:
  - Customer testimonial
  - Responsive **Instagram grid** (6–9 images)
- Clean **footer** with brand info, navigation, and social links — fully responsive

---

### 🛍️ Categories Page (`categories.html`)

- **Breadcrumb navigation** with clickable links and highlighted current page  
  `Home > Women’s Clothing > Dresses`
- **Filter Sidebar (Desktop)** and responsive layout
  - Category filters (expandable sections)
  - Price range, size, color, brand, and rating filters
  - Sale, new arrivals, in-stock, and free shipping toggles
- **Product Display Area**
  - Sort dropdown
  - Grid view (3–4 columns)
  - Responsive product cards with hover effect
  - Pagination with previous/next and load more
- **Fully responsive** grid and filter layout

---

### 👗 Product Page (`product.html`)

- **Product Image Gallery**
  - Main large image
  - Clickable thumbnails (when clicked, updates main image)
- **Product Info Section**
  - Title, price, color, size, description
  - Add to cart and wishlist buttons
  - Customer rating stars
- **Responsive Layout**
  - Two-column desktop layout, stacked on mobile

---

### 🏢 About Us Page (`about.html`)

- **Brand Story & Mission** — includes vision, values, and company milestones
- **Timeline Visualization**
  - Vertical alternating layout for company events
  - Styled markers, arrows, and animation-ready structure
- **Sustainability & Ethics**
  - Environmentally responsible and ethical practices
- **Team Section**
  - Leadership profiles and team highlights
- **Store Locations**
  - Embeddable map section (Google Maps or OpenStreetMap)
  - Optional `<iframe>` snippet for easy integration
- **Responsive & Accessible** layout throughout

> 💡 Map Embedding Options:
>
> - Google Maps (with `YOUR_API_KEY`)
> - OpenStreetMap (no key required)

---

### 💬 Customer Service Page (`support.html`)

- **Accordion FAQ System** (pure CSS structure)
  - Shipping & Delivery
  - Returns & Exchanges
  - Size & Fit
  - Payment & Billing
  - Account & Orders
- **Contact Options**
  - Contact form with category & priority fields
  - Phone and email support info
  - Mock “live chat” info section
- **Self-Service Tools**
  - Order lookup
  - Return/exchange request
  - Size guide
  - Product care & shipping calculator
- Fully **responsive layout** — FAQs and forms adjust for mobile

---

## 📱 Responsive Design

All pages are designed for:

- **Desktop (≥1024px)** — multi-column layouts, sidebars visible
- **Tablet (768–1023px)** — grids compress gracefully
- **Mobile (≤767px)** — stacked layouts, menus hidden, filters collapse

Media queries ensure the design adapts to every screen size.

---

## 🧩 Tech Stack

| Technology                | Purpose                                 |
| ------------------------- | --------------------------------------- |
| **HTML5**                 | Semantic page structure                 |
| **CSS3 (Flexbox + Grid)** | Layout and responsiveness               |
| **Reset.css**             | Normalize styles across browsers        |
| **No JavaScript**         | Lightweight, static-only implementation |
| **Images**                | Local `/images/` directory for assets   |

---

## 🧠 Folder Structure

```
stylehub/
│
├── index.html
├── categories.html
├── product.html
├── about.html
├── support.html
├── account.html
├── cart.html
├── checkout.html
├── support.html
│
├── css/
│   ├── pages/
│   ├── reset.css
│   ├── base.css
│   ├── components.css
│   ├── ecommerce-features.css
│   ├── layout.css
│   ├── variables.css
│   ├── reset.css
│   └── styles.css
│
└── images/
    ├── about/
    ├── social/
    ├── products/
    └── product/
```

---

## ⚙️ How to Run Locally

1. Clone or download the project folder.
2. Open `index.html` directly in your browser.

---

## 🧾 License

This project is for **educational and portfolio use only**.  
All design and code authored by [Your Name].

---

## 🏁 Future Enhancements (Optional)

- Add JavaScript for:
  - Accordion interactivity
  - Product filtering
  - Image slider for hero banner
- Add backend (Node.js or Django) for real product data
- Implement user accounts and cart system

---

**© 2025 StyleHub — Modern Fashion Front-End Design**
