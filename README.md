# 🎟️ EventTix — Event Ticketing Web Application

A web-based event ticketing system with an admin dashboard interface, built using HTML, CSS, Bootstrap 5, and JavaScript.

---

## 📁 Project Structure

```
EventTix/
├── index.html        # Login page
├── dashboard.html    # Admin dashboard (overview & charts)
├── events.html       # Events management page
├── tickets.html      # My Tickets page
├── style.css         # Global stylesheet
├── script.js         # JavaScript logic (login, navigation, etc.)
└── 123.jpg           # Background image
```

---

## 📄 Pages

### 1. `index.html` — Login Page
- Glassmorphism login card with blurred background
- Email & password fields with show/hide password toggle (👁)
- Remember Me checkbox and Forgot Password link
- Error message display for invalid credentials
- Demo credentials hint: **admin / 1234**

### 2. `dashboard.html` — Admin Dashboard
- Overview statistics and charts
- Fixed left sidebar navigation
- Glassmorphism UI style consistent with login page

### 3. `events.html` — Events Management
- Browse and manage events
- Sidebar navigation layout

### 4. `tickets.html` — My Tickets
- View purchased/managed tickets
- Sidebar + main content layout with glassmorphism styling

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Custom styling, glassmorphism effects |
| Bootstrap 5.3.3 | Responsive layout, utility classes |
| JavaScript (Vanilla) | Login logic, interactivity |
| Chart.js *(if used)* | Dashboard charts |

---

## 🎨 Design

- **Theme:** Glassmorphism — frosted glass cards with `backdrop-filter: blur()`
- **Colour Palette:** Pink/purple gradient (`#a78bfa → #ec4899`), dark teal background (`#1a4a50`)
- **Font:** Segoe UI
- **Background:** Full-cover image (`123.jpg`) with fixed attachment

---

## 🔐 Demo Login

```
Email    : admin
Password : 1234
```

> ⚠️ This is a demo/prototype system. No real authentication backend is connected.

---

## 🚀 How to Run

1. Download or clone this project folder.
2. Make sure all files (`index.html`, `style.css`, `script.js`, `123.jpg`) are in the **same folder**.
3. Open `index.html` in any modern browser.
4. Log in using the demo credentials above.

> No installation or server required — runs fully in the browser.

---

## 📌 Notes

- Responsive design is supported via Bootstrap grid and custom media queries.
- The sidebar is fixed on desktop view.
- Background image (`123.jpg`) must be present in the root folder for the background to display correctly.

---

## 👩‍💻 Developer

**Nursyaza Amira binti Ahmad Ghazali**
Universiti Teknologi MARA (UiTM)
Course: IMS566 — Advanced Web Design, Development and Content Management
