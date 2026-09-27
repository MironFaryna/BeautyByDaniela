# BeautyByDaniela – Nail Salon Booking Website

>  **Work in progress.** The frontend is being built page by page. The booking system will be added as a full-stack app (Node.js, Express, PostgreSQL).

A booking website for a real nail salon. Clients will be able to browse services, pick a date and an available time slot, and book an appointment online, without messaging back and forth on Instagram.

<!-- Add a screenshot of the home page when the hero image is in place:
![Home page](docs/home.png)
-->

## Goals

- **For clients:** see services, prices and available hours, and book in under a minute from a phone.
- **For the salon:** receive bookings in one place and avoid double bookings.

## Current status

| Part | Status |
|------|--------|
| Design direction (soft pink, white floating card, rounded buttons) | ✅ Done |
| Home page (navbar, hero, services preview) | ✅ Done |
| About page layout | ✅ Done |
| Gallery, Contact | ⏳ Next |
| Booking flow (service → date → time → form → confirmation) | ⏳ Planned |
| Responsive layout for mobile | ⏳ Planned |
| Backend and database | ⏳ Planned |

## Planned architecture

- **Frontend:** HTML, CSS, JavaScript (semantic HTML, one shared stylesheet)
- **Backend:** Node.js + Express REST API
- **Database:** PostgreSQL (services, available time slots, bookings)
- **Main API endpoints (planned):**
  - `GET /api/services` – list services with price and duration
  - `GET /api/availability?date=YYYY-MM-DD&service=ID` – free time slots for a day
  - `POST /api/bookings` – create a booking (with a check against double booking)

## Pages

Home · About · Gallery · Contact · Booking · Booking form · Confirmation

## Run locally

No build step yet. Clone the repo and open `views/index.html` in a browser, or use a local server such as the VS Code Live Server extension.

```bash
git clone https://github.com/MironFaryna/BeautyByDaniela.git
```

## Project structure

```
BeautyByDaniela/
├── views/          # HTML pages
├── css/style.css   # Shared styles
└── Project_plan.md # Design and page plan (Greek)
```

## Author

**Miron Faryna** · [LinkedIn](https://www.linkedin.com/in/miron-faryna-385171339/) · [GitHub](https://github.com/MironFaryna)
