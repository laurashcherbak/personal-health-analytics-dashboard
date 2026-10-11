# 🧪🌸 QA Test Suite & Smoke Test Cases — Personal Health Dashboard 💖📋

## 📌 🎀 1. Overview & Scope

Because the complete workbook contains an exhaustive 27-scenario test suite, this document outlines the **core smoke and regression test cases** designed to showcase high-priority validation workflows for your portfolio. It highlights how core formulas, conditional formatting, and data integrity are verified. 🌷✨

---

## ⚡ 🔍 2. Core Smoke & Regression Test Suite

| Test ID | Module / Type | Test Scenario Description | Expected Result | Status |
| --- | --- | --- | --- | --- |
| **TC-01** | Smoke / Input | Enter a valid numeric weight and calorie count in `02 — Daily Log`. | Values populate correctly with proper number/decimal formatting applied. | ✅ Passed |
| **TC-02** | Smoke / Formulas | Verify the 7-day moving average formula on row 7 of `Daily Log`. | Formula correctly calculates the average of the current row and the preceding 6 rows without `#DIV/0!` errors. | ✅ Passed |
| **TC-03** | Smoke / UI | Check milestone status updates on `01 — Dashboard` when a goal tier (25%, 50%, 75%, 100%) is crossed. | Status text and indicators dynamically update to reflect progress (e.g., `⏳ Pending` to `✨ Completed`). | ✅ Passed |
| **TC-04** | Regression / Edge Case | Leave a full row of daily metrics completely blank in `Daily Log`. | Downstream summary cards and charts gracefully ignore blank cells using `IF`/`ISBLANK` logic without breaking visual layouts. | ✅ Passed |
| **TC-05** | Regression / Formulas | Update baseline parameters (starting weight and target) in `03 — Goals & Settings`. | All dependent progress bars and variance calculations across the dashboard update instantly. | ✅ Passed |
| **TC-06** | Regression / UI | Verify card-based layout rendering and gridline visibility across primary tabs. | Custom blush/cream card containers render cleanly with minimal gridlines for an app-like visual aesthetic. | ✅ Passed |

