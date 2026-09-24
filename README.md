# 🍲 Saffron & Spice — Multi-Page Pakistani Cuisine Web System

A fully responsive, multi-page web platform for a traditional Pakistani homemade food delivery service based in Lahore, built for the **TechSphere PK Virtual Internship (Web Development Track - Week 4 Final Project)**.

---

## 📌 Project Overview

**Saffron & Spice** connects clients in Lahore with home-cooked Pakistani meals delivered daily. This Week 4 refactoring expands the initial single-page layout into a modular, multi-page application featuring active navigation detection, team profiles, detailed service breakdowns, interactive subscription pricing cards, and order inquiry handling.

* **Course Track:** TechSphere PK Web Development Batch 3
* **Task:** Week 4 — Final Multi-Page Web Project
* **Instructor:** Anees Zafar (CEO & Lead Instructor, TechSphere PK)

---

## ✨ Multi-Page Architecture & Features

This project consists of 4 distinct HTML pages sharing unified styling and JavaScript logic:

1. **`index.html` (Home Page):** Brand hero header, value highlights, featured services grid, and direct call-to-actions.
2. **`about.html` (About Us Page):** Brand history, non-commercial kitchen philosophy, and a dedicated **Team Members Section** featuring role cards.
3. **`services.html` (Services & Pricing Page):** 
   * 3 full, itemized service sections (Daily Meal Subscriptions, Event Catering, Weekend Party Packs) with feature lists, pricing tags, and "Book Now" CTAs.
   * Subscription pricing cards section highlighting Weekly, Monthly, and Party Pack tiers.
4. **`contact.html` (Contact Page):** Order inquiry form, physical Lahore kitchen address, operating hours, and direct contact channels.

---

## 🛠️ Technical Specifications

* **Dynamic Active Navigation:** `script.js` checks `window.location.pathname` to automatically highlight the current page in the top navbar.
* **Responsive Mobile Menu:** Mobile-first hamburger toggle drawer working seamlessly across all 4 pages.
* **Modular Stylesheet:** Clean `style.css` divided into 10 structured sections with CSS variables, Flexbox, and CSS Grid.
* **SEO & Metadata:** Page-specific title tags (`<title>`) and description metadata across all pages.

---

## 👤 Author
Developer: Yasir Rasheed

Role: Web Developer Intern at TechSphere PK

---

## 📂 Repository File Structure

```text
📁 saffron-and-spice/
├── index.html       # Primary landing page
├── about.html       # Brand narrative, core philosophy & team profiles
├── services.html    # Itemized service breakdowns & pricing cards
├── contact.html     # Physical location details & inquiry form
├── style.css        # Organized 10-section stylesheet
├── script.js        # Active link detection & mobile drawer logic
└── README.md        # Project documentation
