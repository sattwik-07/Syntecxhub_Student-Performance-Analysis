# Syntecxhub_Student_Performance_Analysis

**Data Analysis Internship @ Syntecxhub**

An interactive, single-file dashboard analyzing academic performance across 1,000 students using three subjects: Math, Reading, and Writing.

---

## 📊 What This Does

- Loads a 1,000-student dataset (gender, ethnicity, parental education, lunch program, test preparation, subject scores)
- Renders 8 interactive charts — histogram, grouped bars, horizontal bars, doughnut
- Live filters: gender / test prep / parental education / lunch — all KPIs and charts update instantly
- Surfaces key insights: test prep score lift, lunch program gap, top-performing groups

---

## 📁 Files

| File | Description |
|------|-------------|
| `Student_Performance_Analysis_Syntecxhub.html` | Complete dashboard — open in any browser, no server needed |
| `README.md` | This file |

---

## 🚀 How to Run

No setup required. Open `Student_Performance_Analysis_Syntecxhub.html` directly in a browser.

All 1,000 student records and Chart.js (loaded via CDN) are bundled inside the single HTML file.

---

## 📌 Dataset Fields

| Field | Values |
|-------|--------|
| gender | female, male |
| race/ethnicity | group A, B, C, D, E |
| parental level of education | some high school → master's degree |
| lunch | standard, free/reduced |
| test preparation course | completed, none |
| math score | 0–100 |
| reading score | 0–100 |
| writing score | 0–100 |

Dataset structure mirrors the [Kaggle Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) schema.

---

## 📈 Charts Included

1. Average scores by subject (grouped by gender)
2. Test preparation impact — score lift across all three subjects
3. Score distribution histogram
4. Parental education vs. average composite score
5. All three subjects broken down by parental education level
6. Gender split (doughnut)
7. Ethnicity group performance (A–E)
8. Lunch program impact (standard vs. free/reduced)
9. Grade category breakdown (A/B/C/D/F) with percentage bars
10. Key insights panel (auto-calculated from filtered data)

---

## 🛠 Tech Stack

- Vanilla HTML / CSS / JavaScript
- [Chart.js 4.4.1](https://www.chartjs.org/) via CDN
- No frameworks, no build step

---
---

## 👤 Author

Sattwik Sahu

Submitted as part of the **Syntecxhub Internship Program** — Data Analysis Track.

**Connect:** [Syntecxhub](https://www.syntecxhub.com) | `@Syntecxhub`

---
