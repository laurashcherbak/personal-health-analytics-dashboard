# 🌸✨ Product Requirements Document (PRD) — Personal Health & Analytics Dashboard 💖📊

## 📌 🎀 1. Project Overview & Objective
A modern, app-style Google Sheets analytical dashboard designed to track personal health, habits, and progress through automated calculations, rolling moving averages, and clean visual charts. 🌷✨ 

The primary objective is to deliver a professional, reusable spreadsheet product that serves as both a functional daily tracker and a portfolio-ready showcase of product design and analytical rigor. 💅🌸

---

## 🎯 💖 2. Target Audience & Use Cases
* **Primary Users:** Individuals seeking a structured, aesthetic, and automated way to monitor daily health, weight trajectories, and lifestyle habits. 🌿✨
* **Key Use Cases:** 
  * Tracking daily body weight alongside 7-day smoothed moving averages to filter out water weight noise. 📈📊
  * Monitoring daily calorie intake, step counts, sleep duration, and water intake against predefined target baselines. 💧🛌
  * Visualizing emotional well-being and habit consistency through dynamic charts and milestone trackers. 🏆👑

---

## 🌟 💻 3. Functional Requirements & Architecture
The product consists of 7 interconnected, structured tabs designed for a seamless user experience: 📁✨

1. **`01 — Dashboard`** — Executive KPI summary cards, milestone completion status indicators (`✨ Completed`, `⏳ Pending`, `🎉 Achieved!`), and main trend visual charts. 📊💖
2. **`02 — Daily Log`** — Interactive daily entry table equipped with automated windowed formulas for 7-day moving averages. 📝🌸
3. **`03 — Goals & Settings`** — Configuration center where users define starting weights, target weights, dates, and baseline nutritional/activity targets. 🎯✨
4. **`04 — Analytics`** — Statistical aggregation and period-over-period comparisons of health metrics. 📈🧠
5. **`05 — Habit Tracker`** — Lifestyle consistency breakdowns, mood distribution charts, and step goal distribution tracking. 🌿🎨
6. **`06 — Example Data`** — Pre-populated 30-day realistic demonstration dataset powering dynamic preview charts. 📋💖
7. **`07 — Instructions`** — Step-by-step user navigation and onboarding guide. 📘✨

---

## 🛠️ 🧮 4. Technical Specifications & Formulas
* **Platform Compatibility:** Google Sheets / Microsoft Excel 📊
* **Core Functions Utilized:** `AVERAGE`, `COUNTIFS`, `LOOKUP`, `ROUND`, `IF`, `ISBLANK` 🧮
* **UI Design Standard:** Card-based UI architecture with hidden gridlines on primary overview tabs, styled with a soft blush, cream, and warm brown color palette. 🌸✨
