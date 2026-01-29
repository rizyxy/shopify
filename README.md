# Shopify Fullstack: Next.js + React Admin + Go-Gin 🛍️

A high-performance, fullstack e-commerce ecosystem featuring a premium **Next.js 16 Storefront**, a dedicated **React 19 Admin Dashboard**, and a scalable **Go-Gin REST API**.

---

## 🏗️ Architecture Overview

The project follows **Clean Architecture** principles across all layers, ensuring a strict separation of concerns through Controller-Service-Repository patterns.



### 1. Storefront (Next.js 16)
* **Framework:** Next.js 16 (App Router) + React 19.
* **State Management:** Zustand for a persistent, lightweight shopping cart.
* **Performance:** Infinite scrolling (Intersection Observer), Image optimization, and SSR.
* **Styling:** Tailwind CSS 4 & Lucide Icons.

### 2. Admin Dashboard (React 19)
* **Framework:** React 19.
* **Purpose:** Centralized management for product lifecycles and inventory.
* **UX:** Modern interface built with Tailwind CSS 4 for rapid internal management.

### 3. Backend API (Go-Gin)
* **Language:** Go (v1.25.3).
* **Web Framework:** Gin Gonic.
* **Database:** SQLite with GORM (Object Relational Mapper).
* **Features:** Advanced filtering (price range, case-insensitive search), offset-based pagination, and auto-seeding.