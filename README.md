# UTrip — Travel Booking Platform

> **Where are you flying?** — A full-featured, frontend-first travel platform offering flight search, hotel booking, restaurant discovery, and destination browsing. Built in vanilla HTML/CSS/JS, designed for progressive backend integration.

---

## Overview

UTrip is a French-language travel web application targeting West African and international travelers. It provides an end-to-end trip planning experience — from searching destinations to submitting booking requests — with a clean, responsive UI and dark mode support.

**Live demo:** [leroykgu.github.io/UTrip](https://leroykgu.github.io/U-Trip-V2/) 

---

## Features

| Feature | Status |
|---|---|
| Flight / Hotel / Restaurant / Package search tabs | ✅ |
| Live city autocomplete with IATA codes | ✅ |
| Destination grid with region filtering | ✅ |
| Booking form with real-time cost summary | ✅ |
| Authentication modal (Login / Register) | ✅ |
| Dark mode with `localStorage` persistence | ✅ |
| Scroll-triggered reveal animations | ✅ |
| Fully responsive (mobile / tablet / desktop) | ✅ |
| Backend API integration | 🔜 Planned |
| Real payment gateway | 🔜 Planned |
| Database connectivity | 🔜 Planned |

---

##  Project Structure

```
UTrip/
├── index.html           # Main entry point (single-page layout)
├── register.html        # Registration / onboarding page
├── site de voyage.html  # Destination detail page
├── assets/
│   ├── css/             # Stylesheets (if extracted)
│   ├── js/              # Scripts (if extracted)
│   └── img/             # Images and icons
└── README.md
```

---

## Getting Started

### Prerequisites

No build tools or package managers required. The project runs as a static site.

### Local development

```bash
# Clone the repository
git clone https://github.com/leroykgu/UTrip.git
cd UTrip

# Open directly in your browser
open index.html

# Or serve locally with Python
python3 -m http.server 8000
# → http://localhost:8000
```

### Deploy to GitHub Pages

The project is already configured for GitHub Pages. Any push to the `main` branch updates the live site automatically.

---

## Roadmap

The following enhancements are planned for future iterations:

### Frontend
- [ ] Advanced search filters (price range, airline, star rating)
- [ ] Interactive map for destination browsing
- [ ] Multi-language support (EN / FR / AR)
- [ ] Progressive Web App (PWA) support — offline caching

### Backend
- [ ] REST API with **Flask** or **Django**
- [ ] User authentication (JWT tokens, session management)
- [ ] PostgreSQL / SQLite database connectivity
- [ ] Booking management system (create, update, cancel)
- [ ] Email confirmation via SMTP or SendGrid

### Integrations
- [ ] Live flight data via Amadeus / Skyscanner API
- [ ] Hotel availability via Booking.com / Hotels.com API
- [ ] Secure payment gateway (Stripe, CinetPay, Orange Money)
- [ ] Google Maps / Leaflet.js for interactive maps

### Infrastructure
- [ ] Docker containerization
- [ ] CI/CD pipeline (GitHub Actions)
- [ ] Environment-based configuration (`.env`)

---

## Tech Stack

**Current**
- HTML5, CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts (Playfair Display, DM Sans)

**Planned**
- Python 3 — Flask or Django (backend)
- PostgreSQL (database)
- REST / JSON API
- Docker (deployment)

---

## Partners

- **KGUcorp** — Product & strategy
- **Datacorp** — Data infrastructure

---

## License

This project is proprietary. All rights reserved © 2026 UTrip — KGUcorp.

---

## Contact

| Channel | Link |
| GitHub | [@leroykgu](https://github.com/leroykgu) |  
| LinkedIn | [www.linkedin.com/in/kouakou-guillaume] |

---

<p align="center">Made by KGU in Yamoussoukro — <strong>U T R I P</strong></p>
