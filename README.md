# <img src="https://api.iconify.design/lucide:shopping-bag.svg?color=%238A2BE2" width="32" height="32" align="center" /> BIS E-Commerce Frontend

> **A dual-store frontend showcase featuring multi-page e-commerce UIs.**
> Precision-built for mobile retail and premium dining, demonstrating mastery of vanilla HTML/CSS/JS.

<div align="center">

| Project Status | Type                                                                                            | Strategy                                                                                                        | Deployment     |
| :------------- | :---------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------- | :------------- |
| `PRODUCTION`   | ![Static Site](https://img.shields.io/badge/Type-Frontend_Showcase-lightgrey?style=flat-square) | ![JS](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | `Local/Shared` |

</div>

---

## <img src="https://api.iconify.design/lucide:list.svg?color=%238A2BE2" width="20" height="20" align="center" /> Table of Contents

- [Overview](#overview)
- [Stores](#-stores)
  - [Harizon Mobile Store](#1-harizon-mobile-store)
  - [Gourmet Haven Restaurant](#2-gourmet-haven-restaurant)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)

---

## Overview

This repository is the capstone frontend project for the BIS program, containing two complete e-commerce website implementations. Each store is an independent, multi-page, fully navigable website built without any frontend frameworks — demonstrating mastery of raw HTML, CSS, and JavaScript fundamentals.

Both stores share a consistent approach: semantic HTML5 structure, responsive CSS grid and flexbox layouts, and vanilla JavaScript for interactivity.

---

---

## <img src="https://api.iconify.design/lucide:store.svg?color=%238A2BE2" width="20" height="20" align="center" /> Stores

### 1. Harizon Mobile Store

An electronics and mobile phone retail store frontend.

| Page            | Description                                        |
| --------------- | -------------------------------------------------- |
| `index.html`    | Landing page with featured products and promotions |
| `product.html`  | Individual product detail page                     |
| `about.html`    | Brand story and mission                            |
| `contact.html`  | Contact form and store information                 |
| `login.html`    | Member login page                                  |
| `signup.html`   | New user registration form                         |
| `feedback.html` | Customer feedback submission                       |

**Highlights:**

- Product grid with hover effects
- Responsive layout across all breakpoints
- Multi-step navigation flow (browse → detail → checkout entry)

---

### 2. Gourmet Haven Restaurant

A premium restaurant website with menu and reservation flow.

| Page             | Description                           |
| ---------------- | ------------------------------------- |
| `index.html`     | Hero landing with featured dishes     |
| Menu Sections    | Categorized food catalog with visuals |
| Reservation Form | Table booking UI with validation      |
| Contact Page     | Location, hours, and contact details  |

**Highlights:**

- Food photography-first layout
- Warm, appetizing color palette
- Reservation form with input validation

---

---

## <img src="https://api.iconify.design/lucide:cpu.svg?color=%238A2BE2" width="20" height="20" align="center" /> Tech Stack

| Layer             | Technology                                             |
| ----------------- | ------------------------------------------------------ |
| **Structure**     | HTML5 (Semantic elements, forms, tables)               |
| **Styling**       | CSS3 (Flexbox, Grid, custom properties, media queries) |
| **Interactivity** | Vanilla JavaScript                                     |
| **Approach**      | No frameworks, no build tools — zero dependencies      |

---

---

## <img src="https://api.iconify.design/lucide:folder-tree.svg?color=%238A2BE2" width="20" height="20" align="center" /> Project Structure

```
BIS_Ecommerce_Frontend_project/
├── index.html                         # Project root navigation
│
├── harizon-mobile-store/              # Mobile store project
│   ├── index.html                     # Store landing page
│   ├── product.html                   # Product detail page
│   ├── about.html
│   ├── contact.html
│   ├── login.html
│   ├── signup.html
│   ├── feedback.html
│   └── assets/                        # Images and media
│
└── gourmet-haven-restaurant/          # Restaurant project
    ├── index.html                     # Restaurant landing page
    └── [additional pages and assets]
```

---

---

## <img src="https://api.iconify.design/lucide:rocket.svg?color=%238A2BE2" width="20" height="20" align="center" /> Getting Started

```bash
# Clone the repository
git clone https://github.com/AhmedTyson/BIS_Ecommerce_Frontend_project.git

# Navigate into the project
cd BIS_Ecommerce_Frontend_project

# Open Harizon Mobile Store
start harizon-mobile-store/index.html

# Or open Gourmet Haven Restaurant
start gourmet-haven-restaurant/index.html
```

> No dependencies, no build step. Open any `index.html` directly in a modern browser.
