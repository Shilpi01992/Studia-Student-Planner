# Studia-Student-Planner
# 🎓 Studia — Student AI Planner

Studia is a **student-focused planner** that starts as a simple responsive web app and evolves through **four phases** into a full-stack AI-powered assistant for study and self-learning.

---

## 🚀 Project Phases

### 📍 Phase 1 — Responsive Planner (HTML + CSS + Tailwind)
- Build responsive static pages:
  - Home
  - Monthly / Weekly / Daily planners
  - Subject pages
  - Self-learning & habit trackers
- Features:
  - Checklists
  - Collapsible notes
  - Progress bars
  - Print-ready layouts (A4/Letter)
- Tech: **HTML5, CSS3, Tailwind CSS**

---

### 📍 Phase 2 — Interactive Client (React + Local Persistence)
- Migrate static pages into **React.js components**
- Add **localStorage** persistence for:
  - Tasks
  - Notes
  - Stickers
  - Themes (light/dark/high-contrast)
- Subject-specific progress tracking
- Reusable UI components
- Tech: **React.js**, **Tailwind CSS**

---

### 📍 Phase 3 — Full-Stack Planner (Express + MySQL)
- Introduce backend API + database
- Features:
  - Authentication (signup/login)
  - CRUD for Tasks, Subjects, Habits
  - Store progress and notes in DB
  - Calendar & reminders (Google Calendar integration)
- Tech:
  - **Node.js + Express.js**
  - **MySQL** (with Prisma)
  - **REST API**

---

### 📍 Phase 4 — AI Assistant (OpenAI + Calendar Sync)
- Add **AI chatbot** with file upload:
  - Parse syllabus/assignment files
  - Extract deadlines and tasks
  - Auto-save deadlines to the right Subject & Calendar
  - Create reminders automatically
- Features:
  - Chat-based planner interaction
  - Auto-population of planner pages
  - Weekly summaries & study suggestions
- Tech:
  - **OpenAI API** (chat + file parsing)
  - **Google/Microsoft Calendar APIs**
  - Secure handling of tokens (OAuth 2.0)

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, Tailwind CSS, React.js  
- **Backend:** Node.js, Express.js, REST API, MySQL  
- **AI Integration:** OpenAI (for chat + file parsing, task extraction)  
- **Calendar Integration:** Google Calendar (later Microsoft Graph)  
- **Prototyping & Design:** Figma (UI/UX system, components)

---

## 🗺️ Features by Phase

| Feature                         | Phase 1 | Phase 2 | Phase 3 | Phase 4 |
|---------------------------------|---------|---------|---------|---------|
| Responsive planner pages        | ✅      |         |         |         |
| Checklists / collapsibles       | ✅      |         |         |         |
| Progress bars                   | ✅      |         |         |         |
| Print-ready PDF export          | ✅      |         |         |         |
| Local persistence               |         | ✅      |         |         |
| React components                |         | ✅      |         |         |
| Auth (signup/login)             |         |         | ✅      |         |
| Tasks, Subjects, Habits (CRUD)  |         |         | ✅      |         |
| Calendar + Reminders            |         |         | ✅      |         |
| AI chatbot (file upload + chat) |         |         |         | ✅      |
| Auto deadline + reminder sync   |         |         |         | ✅      |

---


