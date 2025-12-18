
# Library Dashboard (HTML/CSS/JS)

A responsive **Library Management Dashboard UI** built with **HTML + CSS + JavaScript**.  
Includes a sidebar navigation, multi-page sections (Dashboard / Books / Categories / Members / Borrowing / Reports / About / Settings), modals for CRUD-like actions, charts via **Chart.js**, and UI toggles for **language** and **theme**.

---

## ✨ Features

- ✅ Collapsible Sidebar (toggle button)
- ✅ Multi-page layout using sections (`.page`) + active state switching
- ✅ Dashboard stats cards + Recent Activity table
- ✅ Books Management table + filters + pagination UI
- ✅ Categories Management + category distribution chart
- ✅ Members Management table + filters + pagination UI
- ✅ Borrowing/Loans management table
- ✅ Reports tabs (Monthly / Category / Member) with charts
- ✅ Modals:
  - Add Book
  - Add Member
  - New Loan
  - Add Category
- ✅ Theme Toggle (Light/Dark) *(UI-ready in HTML)*
- ✅ Language Toggle + translation attributes (`data-translate`, `data-translate-placeholder`)

---

## 🧱 Tech Stack

- **HTML5**
- **CSS3** (custom stylesheet: `styles.css`)
- **Vanilla JavaScript** (`script.js`)
- **Font Awesome 6.4.0** icons
- **Chart.js** for charts

---

## 📁 Project Structure

```bash
library-dashboard/
├── index.html
├── styles.css
└── script.js
````

> Your HTML already links:

* `styles.css`
* `script.js`
* Font Awesome CDN
* Chart.js CDN

---

## 🚀 Getting Started

### 1) Run Locally

Just open `index.html` in the browser:

* Double click `index.html`, or
* Use VS Code **Live Server** (recommended)

---

## 🧭 Pages / Sections

The UI is divided into sections like:

* `#dashboard`
* `#books`
* `#categories`
* `#users`
* `#borrowing`
* `#reports`
* `#about-us`
* `#settings`

Sidebar items contain `data-page="..."` to switch between pages by adding/removing `.active`.

---

## 📊 Charts

This dashboard uses **Chart.js** with canvases:

* `#borrowingChart`
* `#categoryDistributionChart`
* `#monthlyActivityChart`
* `#categoryChart`
* `#memberDistributionChart`



---

## 🌙 Theme Toggle

Buttons in the UI:

* `#theme-toggle-btn` (sidebar)
* `.theme-toggle-icon` (header)

---

## 🌍 Language / Translations

 already have translation hooks like:

* `data-translate="..."`
* `data-translate-placeholder="..."`


---

## 🪟 Modals

Modals included:

* `#add-book-modal`
* `#add-member-modal`
* `#add-loan-modal`
* `#add-category-modal`

Expected behavior (to implement in `script.js`):

* Open modal on button click (`#add-book-btn`, etc.)
* Close modal on `.close-modal` click or outside click
* Handle form submit (currently UI-only)



