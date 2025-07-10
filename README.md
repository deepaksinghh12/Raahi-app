# 🚍 Raahi App – Smart Multimodal Public Transport Tracker for India

A smart, unified, and scalable web application to track real-time data for buses, local trains, metros, and monorails across Indian cities, starting with Mumbai. Built using React.js (PWA), Node.js, Python scrapers, and PostgreSQL, **Raahi** addresses key challenges in Indian public transport such as fragmented data, schedule unreliability, overcrowding, and lack of live updates — all through a crowd-sourced, mobile-first, and offline-capable platform.

---

## 🌟 Features

- 🔁 **Multimodal Route Planner:** Plan routes using a combination of bus + metro + local train.
- 🚦 **Live Capacity Indicators:** Green/Yellow/Red icons to show crowd density.
- 📡 **Real-Time Tracking:** Updates from scrapers, APIs, and user reports.
- 📱 **Progressive Web App (PWA):** Installable, offline-capable mobile experience.
- 📶 **Low-bandwidth & Multilingual Modes:** Designed for regional accessibility.
- 🧭 **Women's Safety & Community Alerts**
- 🏆 **Gamified Crowdsourcing:** Incentivized data sharing (capacity, delays, etc.)

---

## 🏗️ Tech Stack

| Layer     | Technology                                |
|-----------|--------------------------------------------|
| Frontend  | React.js (PWA)                            |
| Backend   | Node.js (Express) / Python (Django optional) |
| Database  | PostgreSQL / MongoDB + Redis              |
| Mapping   | Mapbox GL JS                              |
| Hosting   | Vercel / Firebase / Netlify               |
| Scrapers  | Python (BeautifulSoup, Requests)          |
| Data Input| APIs, IoT GPS, Twitter scraping, WhatsApp bots |

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
🌐 Data Sources
🏛️ Official APIs: DTC, BEST, BMTC, MTC (where available)

👥 Crowd-sourced: User GPS, SMS reports, WhatsApp chatbots

📡 Alternative Inputs: Twitter scraping, drivers/conductors, IoT GPS devices

🚀 Roadmap
Phase 1 (MVP – 3–6 Months)
Real-time BEST bus tracking in Mumbai

Scrapers for CR/WR train schedules

Launch basic PWA with offline support

Phase 2 (6–12 Months)
Add support for Metro & Monorail

Integrate SMS/WhatsApp data inputs

Smart planner with ETA and delay prediction

Phase 3 (12+ Months)
AI-based ETA prediction

Ticketing system integration

B2B dashboards & Smart City API

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss your ideas or proposals.

📄 License
MIT License © 2025 Deepak Singh

🙌 Acknowledgements
Indian Railways (CR/WR) APIs & schedule data

BEST Undertaking for public transport resources

Volunteer contributors for crowd-sourced updates

yaml
Copy
Edit

---
