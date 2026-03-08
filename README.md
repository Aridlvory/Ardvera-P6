# ⬡ ARDVERA P6
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ec1248a0-b361-46b8-88cd-01bf22c7b858" />

### Project Management Information System — Educational Simulation

> **A browser-based Primavera P6 simulator built for Engineering students.**
> Runs entirely in a single HTML file — no installation, no server, no cost.

---

![Made with HTML/CSS/JS](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-00c8ff?style=flat-square&labelColor=020508)
![License](https://img.shields.io/badge/License-MIT-00ffc8?style=flat-square&labelColor=020508)
![For Students](https://img.shields.io/badge/For-TKM%20Students-b06aff?style=flat-square&labelColor=020508)
![Powered By Claude](https://img.shields.io/badge/Powered%20By-Aridlvory%20%26%20Claude-388bfd?style=flat-square&labelColor=020508)

---

## 🚀 Live Demo

👉 **[Open Ardvera P6](https://aridlvory.github.io/Ardvera-P6/)**

**Login Credentials (Bcoz this is what we use in our lab):**
```
Username: Admin
Password: Admin
```

---

## 📌 What is Ardvera P6?

Ardvera P6 is a **free, educational simulation** of Oracle Primavera P6 — the industry-standard project management software used in construction, engineering, and infrastructure projects worldwide.

Since Primavera P6 is expensive and requires installation, this tool was built to help **Mech Engineering students** at TKM College (and beyond) practise for their **Primavera lab exams** using just a web browser.

> ⚠️ This project is **not affiliated with Oracle Corporation** or Oracle Primavera P6®. It is an independent educational tool built for academic use only.

---

## ✨ Features

### 🔐 Login System
- Sci-fi cyberpunk login screen with animated grid, scan beam, floating particles, and glitch effects
- System boot readout animation
- Live clock display

### 📋 Activity Management
- Create, edit, and delete activities
- Set Activity ID, Name, Original Duration, Type (Task / Milestone / LOE)
- Assign WBS, Resource, Calendar, and % Complete
- Set constraints (SNET, SNLT, MFO, MSO)

### 🔗 Logical Relationships
- All four relationship types:
  - **FS** — Finish to Start
  - **SS** — Start to Start
  - **FF** — Finish to Finish
  - **SF** — Start to Finish
- Positive and negative **Lag** support
- Multiple predecessors per activity

### ⚡ CPM Scheduling (Press F9)
- Full **Critical Path Method** engine
  - Forward pass → Early Start (ES), Early Finish (EF)
  - Backward pass → Late Start (LS), Late Finish (LF)
  - Total Float (TF) and Free Float (FF) for every activity
- **Critical Path** highlighted in red (TF = 0)
- Total project duration calculated automatically

### 📊 Gantt Chart
- Auto-generated Gantt with colour-coded bars
- Critical activities shown in red with glow
- Progress overlay per activity
- TODAY marker line
- Drag-to-resize split panel

### 🗂 Work Breakdown Structure (WBS)
- Hierarchical WBS tree (up to 3 levels)
- Add / Edit / Delete nodes
- Budget and OBS assignment per node

### 🏢 Enterprise Project Structure (EPS)
- Multi-level EPS hierarchy
- Attach projects to EPS nodes

### 👥 Organizational Breakdown Structure (OBS)
- Define responsible managers
- Link OBS to WBS nodes and resources

### 👤 Resources
- Add Labor / Material / Equipment / Subcontractor resources
- Set unit cost and max allocation
- Link to OBS

### 📅 Calendars
- Create custom calendars (Standard 5-day, 7-day, 24-hour)
- Set working days, start/end times, lunch break
- Add holiday exceptions

### 📈 Reports Tab
- Total project duration
- Critical path display
- Full float report table (ES, EF, LS, LF, TF, FF for all activities)
- Activity status summary (Not Started / In Progress / Completed)

### 💾 Export
- Export project data as JSON (XER simulation)

---

## 🖥️ How to Use
Just Open the link

---

## 🎓 Exam Guide
All the best... I pray for you

---

## 📁 Project Structure

```
ardvera-p6/
│
└── index.html        ← Entire application (single file)
└── README.md         ← This file
```

Everything — HTML, CSS, JavaScript, fonts (via CDN) — lives in one self-contained file.

---

## ⚠️ Disclaimer

> Ardvera P6 is an **independent educational simulation** created for academic use only.
> It is **not affiliated with, endorsed by, or connected to Oracle Corporation** or Oracle Primavera P6® in any way.
> All Oracle Primavera P6® trademarks belong to Oracle Corporation.

---

## 🤝 Credits

| Role | Credit |
|------|--------|
| Concept & Design | **Aridlvory** |
| AI Development | **Claude** by Anthropic |
| Inspiration | Oracle Primavera P6® |
| Made for | TKM College Students |

---

> *For TKM Students — by a TKM Student* 🎓

---

## 📜 License

MIT License — free to use, share, and modify for educational purposes.
