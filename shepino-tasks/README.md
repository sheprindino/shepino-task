# 🚀 Shepino Tasks

> **Premium Task Manager, Second Brain & Event Calendar** — a complete productivity app in a single file.

![Version](https://img.shields.io/badge/version-3.0-7C5CFC)
![License](https://img.shields.io/badge/license-MIT-34D399)
![No Dependencies](https://img.shields.io/badge/dependencies-zero-60A5FA)

---

## ✨ Features

### 📋 Task Manager
- Create, edit, delete tasks
- Priority levels: Low · Medium · High · Urgent
- Status tracking: To Do → In Progress → Done → Archived
- Categories, tags, subtasks with progress bars
- Pin important tasks to the top
- Color coding per task
- Quick preset due dates (Today, Tomorrow, 1 Week, 1 Month)

### 🧠 Second Brain (Notes)
- Rich note-taking with categories
- Pin, tag, and color-code notes
- Full-text search across all notes
- Edit & **Delete** buttons visible on every note card
- Delete option inside the note editor modal too

### 📅 Event Calendar
- **Full-size professional calendar** with events displayed inside day cells
- Monthly navigation with ← →
- Colored event blocks showing time & title inside each day
- Tasks with due dates auto-appear on their calendar day
- Click any day to see full event details below
- Create events with: title, start/end time, location, description, repeat, reminder, color
- Edit & delete events
- Up to 3 events per cell + "+N more" overflow indicator

### 🔔 Notifications & Reminders
- **Auto permission request** on first login
- Real device push notifications (Android, iOS Safari 16.4+, Desktop)
- Phone vibration pattern on notification
- Sound chime using Web Audio API
- In-app fallback banner if browser notifications denied
- **What triggers notifications:**
  - 🔔 Task reminders at exact set time
  - ⏰ 15-minute warning before due date
  - ⚠️ Instant alert when a task goes overdue
  - 📅 Event reminders (5/15/30/60 min before)
  - 🔁 Recurring reminders (daily/weekly/monthly)
- Background checker every 15 seconds
- Test notification button in Settings

### 🔐 User Accounts
- Sign up with name, email, password
- Password hashed with SHA-256
- Sign in with same credentials to get all your data back
- Per-user isolated data (each user has their own tasks, notes, events)
- Show/hide password toggle
- Remember me checkbox

### 🎨 Premium UI
- Glassmorphism dark theme
- Animated gradient blobs background
- Floating particles and geometric shapes
- Fully responsive: Android, iOS, Windows, Mac, Linux
- Smooth hover and click animations
- Professional date picker cards with quick presets

---

## 🚀 How to Use

### Option 1: Just open the file
```
Double-click index.html → Opens in your browser → Done
```

### Option 2: Serve locally
```bash
# Python
python3 -m http.server 3000

# Node.js
npx serve .

# Then open http://localhost:3000
```

### Option 3: Deploy free
| Platform | How |
|----------|-----|
| **GitHub Pages** | Push to repo → Settings → Pages → Deploy from main branch |
| **Netlify** | Drag and drop the folder → instant URL |
| **Vercel** | `vercel --prod` |
| **Cloudflare Pages** | Connect repo → auto deploy |

---

## 📱 Device Support

| Platform | How to access |
|----------|--------------|
| **Desktop** (Win/Mac/Linux) | Open `index.html` in any browser |
| **Android** | Open URL in Chrome → tap ⋮ → "Add to Home Screen" |
| **iPhone/iPad** | Open URL in Safari → Share → "Add to Home Screen" |
| **Any device on network** | Serve locally, open `http://<your-ip>:3000` |

---

## 📂 Project Structure

```
shepino-tasks/
├── index.html          ← The complete app (single file, ~100KB)
├── README.md           ← This file
├── LICENSE             ← MIT License
├── .gitignore          ← Git ignore rules
└── screenshots/        ← App screenshots
    ├── dashboard.png
    ├── tasks.png
    ├── calendar.png
    └── notes.png
```

---

## 🛠 Tech Stack

- **Zero dependencies** — no npm, no frameworks, no build step
- **Pure HTML + CSS + JavaScript** in a single file
- **LocalStorage** for persistent per-user data
- **Web Notifications API** for push notifications
- **Web Audio API** for notification sounds
- **SHA-256** (Web Crypto API) for password hashing
- **CSS glassmorphism** with backdrop-filter blur

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

**Built with ❤️ — Shepino Tasks**
