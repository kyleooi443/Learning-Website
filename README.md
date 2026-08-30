# DeskMate 🗂️

> **A productivity app built for students** — organize tasks, manage study time, and stay on top of school life in one place.

---

## Idea

Students juggle assignments, exams, deadlines, and personal time across too many disconnected tools (notes apps, calendars, reminders, sticky notes). **DeskMate** brings the essentials into **one lightweight, distraction-free web app** designed specifically around a student's routine — not a generic project-management tool repurposed for school.

---

## Target Users

- **High school and university students**
- Students juggling **multiple classes/subjects and deadlines**
- Anyone who wants a **simple, focused (not bloated)** productivity tool

---

## Core Features (MVP)

- [ ] **Task Manager**
  - Add, edit, complete, and delete tasks
  - Group tasks by subject/class
- [ ] **Assignment Tracker**
  - Due dates with visual urgency indicators
  - Color-coded by how soon a task is due
- [ ] **Study Timer**
  - Built-in Pomodoro-style timer
  - Short/long break cycles
- [ ] **Daily/Weekly Planner View**
  - See everything due at a glance
- [ ] **Progress Dashboard**
  - Simple stats: tasks completed, study hours logged, streaks

## Stretch Features (Post-MVP)

- [ ] Dark mode
- [ ] Local storage or account-based sync (data persists between sessions)
- [ ] Subject/class color tagging
- [ ] Notifications/reminders for upcoming deadlines
- [ ] Calendar integration (Google Calendar sync)
- [ ] Grade tracker / GPA calculator
- [ ] Study streak gamification (badges, milestones)
- [ ] Collaborative study groups or shared task lists

---

## 🛠️ Tech Stack

| 🧱 Markup | **HTML5** | | 🎨 Styling | **Tailwind CSS** |
| ⚛️ Frontend Framework | **React.js** | | 🔧 Version Control | **Git + GitHub** |

---

## Project Structure

```
deskmate/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── TaskCard.jsx
│   │   ├── Timer.jsx
│   │   ├── Dashboard.jsx
│   │   └── Navbar.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Tasks.jsx
│   │   └── Planner.jsx
│   ├── App.jsx
│   ├── index.js
│   └── styles/
│       └── index.css
├── tailwind.config.js
├── package.json
└── README.md
```

---

## Getting Started

**1. Clone the repo**
```bash
git clone https://github.com/your-username/deskmate.git
```

**2. Move into the project folder**
```bash
cd deskmate
```

**3. Install dependencies**
```bash
npm install
```

**4. Run the dev server**
```bash
npm start
```

---

## Contributors

- **[Mark Daniel C. Commendador]** — Pogi 1
- **[Kyle Andrew B. Masilang]** — Pogi 2

---

## 📄 License

This project is licensed under the **MIT License** — feel free to adapt as needed.
