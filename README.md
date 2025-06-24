# Raahi-app
A smart, unified, and scalable web application to track real-time data for buses, local trains, metros, and monorails across Indian cities, starting with Mumbai. Built with React.js (PWA), Node.js, Python scrapers, and PostgreSQL, the project addresses multimodal public transport challenges,crowd-sourced, and offline-capable platform.

# 🚍 Smart Multimodal Public Transport Tracker for India

A unified, intelligent transport tracking system for Indian cities — starting with Mumbai — that shows real-time updates for buses, metro, local trains (CR/WR), and monorail in a single, mobile-friendly web app.

---

## 🌟 Features

- 🔁 **Multimodal Route Planner:** Plan routes using a combination of bus + metro + train.
- 🚦 **Live Capacity Indicators:** Green/Yellow/Red icons show how crowded each vehicle is.
- 📡 **Real-Time Tracking:** Updates from scrapers, APIs, and user crowdsourcing.
- 📱 **Progressive Web App (PWA):** Works offline and can be installed on mobile.
- 📶 **Low-bandwidth & Multilingual Modes:** Designed for feature phones & regional languages.
- 🧭 **Women's Safety & Community Alerts**
- 🏆 **Gamified Crowdsourcing:** Rewards for sharing data (capacity, delays, etc.).

---

## 🏗️ Tech Stack

| Layer       | Technology                   |
|------------|-------------------------------|
| Frontend    | React.js (PWA)               |
| Backend     | Node.js (Express) / Python (Django optional) |
| Database    | PostgreSQL / MongoDB + Redis |
| Mapping     | Mapbox GL JS                 |
| Hosting     | Vercel / Firebase / Netlify  |
| Scrapers    | Python (BeautifulSoup, Requests) |
| Data        | APIs, IoT GPS, Twitter scraping, WhatsApp bots |

---

## 📊 Architecture

```mermaid
flowchart TB
  A[Frontend: React PWA] -->|API Calls| B[Backend: Node.js]
  B --> C[(PostgreSQL / MongoDB)]
  B --> D[Scrapers: Python]
  C --> E[Train Schedules]
  C --> F[Bus Routes]
  D --> G[CR/WR Websites]
  D --> H[BEST Undertaking]
