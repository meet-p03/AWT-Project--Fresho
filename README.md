# 🌾 Fresho – Local Farmer Marketplace

Fresho is a web-based local farmer marketplace designed to connect local farmers directly with customers across Gujarat (Ahmedabad, Anand, Surat, Rajkot, Vadodara). 

Built as a college project for **Advanced Web Technology (AWT)** and **Software Engineering (SE)**.

---

## 📱 Features & Roles

### 🛒 Customer
- Browse & search local fresh produce (Vegetables, Fruits, Dairy, Grains).
- Select quantities, view stock availability, and filter by local farmers.
- Cart & 3-Step Checkout (Address, UPI/COD Payment, Review).
- Real-time order tracking timeline with estimated delivery ETA.

### 🚜 Farmer
- List new harvest with image uploads, categories, pricing per kg, and stock levels.
- View weekly earnings chart & track pending orders.
- Direct communication with delivery drivers and buyers.

### 🛡️ Administrator
- Platform metrics: Total active users, verified farmers, listed products, and daily order volume.
- Farmer identity and land record verification management.

---

## 🛠️ Tech Stack & Architecture

- **Frontend:** HTML5, CSS3 (Keyframe Animations, Custom Properties), JavaScript
- **Framework Goal:** Designed for AngularJS component & view routing
- **Backend Goal:** Node.js / Express REST API integration
- **Design System:** Plus Jakarta Sans typography, Forest Green (`#17703A`) palette, accessibility-compliant touch targets.

---

## 📂 AngularJS Route Structure

| Route | Description | View |
| :--- | :--- | :--- |
| `/splash` | Onboarding splash screen | Customer |
| `/role-select` | Select Customer, Farmer, or Admin | Auth |
| `/signup` | User & Farmer registration | Auth |
| `/login` | Authentication view | Auth |
| `/home` | Main customer marketplace feed | Customer |
| `/product/:id` | Product detail view | Customer |
| `/cart` | Shopping cart & discount code | Customer |
| `/checkout` | 3-step checkout workflow | Customer |
| `/orders/:id` | Live vertical order tracker | Customer |
| `/farmer/dashboard` | Earnings overview & order stats | Farmer |
| `/farmer/products/new` | Produce listing form | Farmer |
| `/admin/dashboard` | Verification & system stats | Admin |
