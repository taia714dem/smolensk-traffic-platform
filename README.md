# Smolensk Traffic Platform

A web platform prototype for the **Center for Traffic Management of the Smolensk Region (ЦОДД Смоленской области)**.
This project was developed during a hackathon to create a modern, citizen-oriented digital solution for traffic management.

---

## 🚀 Hackathon Context

The hackathon challenge was to design and implement a **multi-page digital platform** that:

* Improves communication between the institution and citizens.
* Visualizes traffic-related data in a clear and engaging way.
* Provides a foundation for smart analytics and future digital services.

The solution was meant to combine a **public-facing website**, an **admin/editor dashboard**, and a **centralized database**.

---

## ✅ Implemented Features (Frontend)

* Multi-page **public website** with accessible information blocks.
* Layout and structure for main sections (About, Team, Projects, News, Documents, Contacts, Services).
* Connection to backend endpoints for data display.
* Basic login flow for **editor** and **admin** roles (UI + routing).

> ⚠️ The admin dashboard and content editing functionality were **planned but not implemented** within the hackathon timeframe.

---

## 🛠 Tech Stack (Frontend)

* **React** (with hooks & components)
* **TypeScript**
* **Vite** (build tool)
* **CSS Modules**

---

## 📂 Project Structure

```
smolensk-traffic-platform/
 ├── public/           # Static assets
 ├── src/              # React components & pages
 ├── package.json
 └── vite.config.ts
```

---

## ▶️ Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/smolensk-traffic-platform.git
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Run the development server:

   ```bash
   npm run dev
   ```

---

## 🔮 Future Plans

* Implement **admin dashboard** for content and data management.
* Enable **editor role** to update site pages.
* Integrate with backend services for data visualization and statistics.
* Add full **responsive design** and mobile-first support.

---

## 📌 Note

This repository contains only the **frontend** part of the hackathon project.
Backend was developed separately (Go), and the database stack was handled by another team member.

