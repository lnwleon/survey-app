# SURVEY_OS v1.0 // WAMBUE LEON

```
 ___  _   _  ____  _     _____ _____   ___  ____
/ __)( ) ( )(  _ \( )   ( ___)( ___ ) / __)/ ___)
\__ \ ) V (  )   / )   ) )__)  \   /  \__ \\__ \
(___/ \_/\_/ (_)\_)(____)(_____)(_/(_) (___/(___/
```

> A full-featured survey platform built with a terminal/OS aesthetic — pure HTML, CSS & JavaScript.

**Built by [Wambue Leon](https://github.com/lnwleon) · Nairobi, Kenya · 2025**

---

## $ whoami

A Tier 3 Advanced survey application built from scratch. No frameworks. No build step. No dependencies except Chart.js (loaded via CDN). Inspired by the terminal OS aesthetic of [zui.ooo](https://www.zui.ooo).

---

## $ cat features.txt

### Core
| Feature | Description |
|---|---|
| `COORDINATOR_ROLE` | Admin login with full survey management |
| `RESPONDENT_ROLE`  | Public access to open surveys |
| `CREATE_SURVEY`    | Up to 10 questions × 5 choices each |
| `OPEN / CLOSE`     | Lifecycle control per survey |
| `VALIDATION`       | All questions required before submit |
| `PERSISTENCE`      | Full data stored in `localStorage` |

### Upgrades
| Feature | Description |
|---|---|
| `USER_ACCOUNTS`    | Register, login, duplicate submission prevention |
| `CHART_RENDERER`   | Bar + Pie charts via Chart.js (toggle between them) |
| `CSV_EXPORT`       | Download all responses as a spreadsheet |
| `AUTO_DEADLINE`    | Set a close date/time — survey auto-closes |
| `THEME_TOGGLE`     | Dark (default) / Light mode, saved to localStorage |
| `SHARE_LINK`       | Copy survey URL to clipboard, auto-opens on visit |

### UI / OS Aesthetic
| Feature | Description |
|---|---|
| `BOOT_SEQUENCE`    | Animated system boot screen on load |
| `CRT_SCANLINES`    | CSS scanline overlay for the retro terminal look |
| `LIVE_CLOCK`       | Real-time clock + uptime counter in status bar |
| `STATS_HEADER`     | Live survey count + response count in hero |
| `MONOSPACE_FONT`   | JetBrains Mono throughout |
| `TERMINAL_PROMPTS` | `$`, `cat`, `ls`, `nano` command metaphors in the UI |

---

## $ ls -la /stack/

```
HTML5
CSS3 (custom properties, CRT scanline effect, animations)
Vanilla JavaScript (zero frameworks)
Chart.js 4.4.1 (CDN)
Google Fonts — JetBrains Mono
localStorage (zero backend)
```

---

## $ tree .

```
survey-app/
├── index.html     ← Entire app — HTML + CSS + JS in one file
└── README.md      ← This file
```

---

## $ ./run.sh

```bash
# Clone
git clone https://github.com/lnwleon/survey-app.git
cd survey-app

# Open in browser (no server needed)
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## $ man survey_os

### As a Respondent
```
1. Open the app — boot sequence runs, then home screen loads
2. Register or Login (optional, but prevents duplicate submissions)
3. Click [ OPEN_FILE ] on any open survey
4. Answer all questions and click SUBMIT_RESPONSE
5. View closed survey results under [ RESULTS ] tab
6. Use [ SHARE ] to copy a direct link to any survey
```

### As a Coordinator (Admin)
```
1. Click [ ADMIN ] in the status bar
2. Login: admin / admin123
3. Click + NEW_SURVEY and fill in title, optional deadline, questions
4. Save as draft → click ▶ OPEN to go live
5. Click ■ CLOSE to end the survey
6. Click RESULTS to see responses + charts
7. Click EXPORT_CSV to download all data
```

---

## $ git log --oneline

```
feat: terminal OS aesthetic — boot screen, CRT scanlines, monospace
feat: user accounts — register, login, duplicate prevention
feat: Chart.js results — bar + pie chart toggle
feat: CSV export — download all responses
feat: survey deadline — auto-close at set time
feat: theme toggle — dark/light mode with saved preference
feat: share link — clipboard copy + auto-open on visit
feat: live clock + uptime counter in status bar
init: Survey App Tier 3 Advanced — Wambue Leon
```

---

## $ cat source.txt

Built as an implementation of the [Survey App](https://github.com/florinpop17/app-ideas/blob/master/Projects/3-Advanced/Survey-App.md) from [florinpop17/app-ideas](https://github.com/florinpop17/app-ideas) — **Tier 3: Advanced**.

All user stories implemented. All bonus features included. UI inspired by [zui.ooo](https://www.zui.ooo).

---

## $ cat about.txt

**Wambue Leon** — Diploma in ICT · Nairobi, Kenya

Building at the intersection of web dev, cybersecurity, and the Kenya tech scene.

- GitHub: [@lnwleon](https://github.com/lnwleon)
- Community: iHub · Silicon Savannah · Nairobi Dev Community

---

```
zui@survey_os:~$ _
```
