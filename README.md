# 📋 Survey App

> A full-featured survey web application — built from scratch with pure HTML, CSS, and JavaScript.

**Built by [Wambue Leon](https://github.com/lnwleon) · Nairobi, Kenya · 2025**

---

## 🚀 Live Demo

> Open `index.html` directly in any browser — no server needed.

**Admin login:** `admin` / `admin123`

---

## ✨ Features

### Core Functionality
| Feature | Details |
|---|---|
| 👤 Two user roles | Survey Coordinator (admin) + Survey Respondent |
| 📝 Create surveys | Up to 10 questions, 5 choices each |
| ▶ Open / ■ Close | Coordinators control survey lifecycle |
| ✅ Take surveys | Radio button selection, full validation |
| ❌ Cancel anytime | Cancel buttons on all forms |
| 💾 Data persistence | All data saved via `localStorage` |

### Upgrades
| Feature | Details |
|---|---|
| 👥 User accounts | Register, login, duplicate submission prevention |
| 📊 Interactive charts | Bar and Pie charts via Chart.js, toggle between them |
| ⬇ CSV export | Download all responses as a spreadsheet |
| ⏰ Survey deadlines | Set auto-close date/time per survey |
| 🌙 Theme toggle | Dark / Light mode with saved preference |
| 🔗 Share link | Copy survey URL to clipboard, auto-opens on visit |

---

## 🛠 Tech Stack

```
HTML5 / CSS3 / Vanilla JavaScript
Chart.js 4.4.1 (via CDN)
localStorage (zero backend)
No frameworks. No npm. No build step.
```

---

## 📁 Project Structure

```
survey-app/
├── index.html     ← The entire app (HTML + CSS + JS)
└── README.md      ← This file
```

---

## 🖥 How to Run

```bash
# Clone the repo
git clone https://github.com/lnwleon/survey-app.git

# Open in browser
cd survey-app
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Or just double-click `index.html`.

---

## 🎮 How to Use

### As a Survey Respondent
1. Open the app — you'll see all **Open Surveys**
2. Optionally **Register / Login** to track your submissions
3. Click **Take Survey** on any open survey
4. Select one answer per question and click **Submit**
5. View results of closed surveys under the **Results** tab
6. Use the **🔗 Share** button to copy a direct link to any survey

### As a Survey Coordinator
1. Click **⚙ Admin** in the nav and login (`admin` / `admin123`)
2. Go to the **Admin** tab and click **+ New Survey**
3. Enter a title, optional deadline, and add 1–10 questions
4. Each question can have 2–5 choices
5. Click **Save Survey** (saves as Draft)
6. Click **▶ Open** to make it live for respondents
7. Click **■ Close** to end the survey
8. Click **📊 Results** to see responses with charts
9. Click **⬇ Export CSV** to download all responses

---

## 📸 Screenshots

> Dark mode (default)

The app ships with a dark cyberpunk-inspired theme. Toggle to light mode anytime with the 🌙 button in the nav.

---

## 🗺 Roadmap / Future Ideas

- [ ] Backend integration (Firebase / Supabase)
- [ ] Email notifications when a survey closes
- [ ] Multiple question types (text input, rating scale)
- [ ] Survey templates
- [ ] Response analytics dashboard
- [ ] Password reset flow

---

## 📄 Project Source

Built as an implementation of the [Survey App idea](https://github.com/florinpop17/app-ideas/blob/master/Projects/3-Advanced/Survey-App.md) from [florinpop17/app-ideas](https://github.com/florinpop17/app-ideas) — **Tier 3: Advanced**.

All user stories from the spec are implemented, plus all bonus features.

---

## 👨‍💻 About the Developer

**Wambue Leon** — Diploma in ICT student, Nairobi, Kenya.
Building projects in web dev, cybersecurity, and the Kenya tech scene.

- GitHub: [@lnwleon](https://github.com/lnwleon)
- Community: iHub · Silicon Savannah · Nairobi Dev Scene

---

> *"Ship it, then improve it."*
