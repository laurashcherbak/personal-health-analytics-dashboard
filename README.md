# Personal Health & Analytics Dashboard

A modern, app-style Google Sheets analytical dashboard designed to track personal health, habits, and progress through automated calculations, rolling moving averages, and clean visual charts.

---

## About the Project

This tool is built for comprehensive monitoring of key health metrics (weight, calories, steps, sleep, mood) in one centralized location. Powered by automated formulas and a structured multi-tab architecture, the spreadsheet functions like a fully responsive web application without requiring external software installations.

---

## Core Features

* **Automated 7-Day Moving Average:** Filters out daily water weight fluctuations using windowed average calculations.
* **Milestone Progress Tracker:** Dynamic status indicators (`✨ Completed`, `⏳ Pending`, `🎉 Achieved!`) for goal achievements at 25%, 50%, 75%, and 100%.
* **Habit & Lifestyle Analytics:** Mood distribution breakdowns, step goal completion tracking, and sleep consistency monitoring.
* **Visual Analytics:** Interactive charts tracking weight trends and calorie intake against target baselines.
* **App-Like Design:** Card-based UI layout styled with a clean, modern aesthetic.

---

## Technologies & Formulas

* **Platform:** Google Sheets / Microsoft Excel
* **Functions Used:** `AVERAGE`, `COUNTIFS`, `LOOKUP`, `ROUND`, `IF`, `ISBLANK`
* **Architecture:** 7 interconnected sheets (Dashboard, Daily Log, Goals & Settings, Analytics, Habit Tracker, Example Data, Instructions).

---

## How to Use

1. Copy or download the spreadsheet template to your local drive or cloud storage.
2. Navigate to the `03 — Goals & Settings` tab and enter your personal target parameters.
3. Log your metrics daily in the `02 — Daily Log` tab—all charts, averages, and progress bars will update automatically.
