# 🛍️ Myntra Clone

A fully responsive **Myntra e-commerce clone** built using **HTML, CSS, and JavaScript**, replicating core shopping features like product display, add to bag, and cart summary — all on the client-side using browser storage.

## 🚀 Features

- ✅ Interactive homepage with product listings
- 👜 "Add to Bag" functionality using `localStorage`
- 🧮 Real-time cart summary: total MRP, discounts, convenience fee
- ❌ Remove from bag option with live UI updates
- 📦 Product data rendered dynamically using JavaScript
- 💡 Fully responsive layout with clean and modern design

## 🧠 Tech Stack

- **HTML** – Structure and layout  
- **CSS** – Styling and responsiveness  
- **JavaScript (Vanilla)** – DOM manipulation, bag logic, localStorage handling

## 📁 Project Overview

### 🎯 Homepage
Displays all available products dynamically from a JavaScript data array. Each product includes:
- Image
- Name and Brand
- Price details (Original, Discounted, Percentage Off)
- Return and Delivery info
- "Add to Bag" button

### 🛒 Cart Page
Once added to the bag:
- Product IDs are stored in `localStorage`
- Cart page fetches full item data and displays it
- Price summary includes:
  - Total MRP
  - Discount
  - Convenience fee (₹99 fixed)
  - Final payable amount
- "Remove" button updates bag instantly in UI and storage
