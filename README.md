# 🎟 EventTix — Online Event Ticketing System

A fully functional front-end web application built for IMS566 Advanced Web Design Development and Content Management.

## 📌 Project Description

EventTix is a sleek, dark-themed online event ticketing system that allows users to browse events, purchase tickets, and manage their bookings — all through a professional front-end interface without any backend.

## ✨ Features

- **Authentication** — Login with hardcoded credentials (`admin` / `1234`) with error feedback
- **Dashboard** — Summary stats (Total Events, Tickets Sold, Upcoming Events, Revenue) + 2 charts
- **Events Page** — Browse 6 events with category filter and search; buy tickets with one click
- **My Tickets Page** — View all booked tickets in a table; cancel tickets
- **Data Visualisation** — Bar chart (ticket sales per event) + Doughnut chart (categories) via Chart.js
- **Responsive Design** — Mobile-friendly with a hamburger nav drawer
- **Toast Notifications** — Live feedback when tickets are booked

## 🔐 Login Credentials

| Username | Password |
|----------|----------|
| admin    | 1234     |

## 🛠 Frameworks & Libraries

| Library | Version | Purpose |
|---------|---------|---------|
| Bootstrap | 5.3.3 | UI framework, responsive grid |
| Chart.js | 4.4.3 | Data visualisation (bar + doughnut charts) |
| Google Fonts | — | Typography (Syne + DM Sans) |

## 📁 File Structure

```
EventTicketing/
├── index.html       ← Login page
├── dashboard.html   ← Dashboard with charts
├── events.html      ← Browse & book events
├── tickets.html     ← View & manage bookings
├── style.css        ← All custom styles
├── script.js        ← All application logic
└── README.md        ← This file
```

## 🚀 Running Locally

1. Clone or download the repository
2. Open `index.html` in **Google Chrome**
3. Log in with `admin` / `1234`

No build tools or backend required — runs entirely in the browser.

## 🌐 GitHub Pages Deployment

1. Push all files to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site will be live at `https://username.github.io/projectname/`

## 📊 Assignment Info

- **Course:** IMS566 Advanced Web Design Development and Content Management
- **Project Weight:** 20%
- **Student:** Your Name
- **Year:** 2025
