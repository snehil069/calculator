# 🎓 AIT Pune Semester 1 SGPA Calculator

A modern, aesthetic, component-aware SGPA calculator designed specifically for **Army Institute of Technology (AIT), Pune** First Year (FE) Semester 1 students.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![AIT Pune](https://img.shields.io/badge/AIT%20Pune-Autonomous-indigo.svg)

---

## ✨ Features

- **⚡ Component-Aware Dynamic Evaluation:**
  Unlike traditional calculators that penalize pending exams with a 0 and drag your SGPA down, this calculator dynamically computes your standing based **strictly on the exams and components you have completed so far** (e.g. CI-1, CI-2, Practicals) without penalizing future exams like End Sem.
- **🎨 Modern Aesthetic UI:**
  Built with a sleek design system, dark/light theme switcher, gradient accents, fluid micro-interactions, responsive card layouts, and progress bars.
- **🎯 Semester Target Forecaster:**
  Enter your goal SGPA (e.g., 9.0) and instantly find out the exact average percentage/grade point you need in your remaining exams to achieve it.
- **📊 Real-time Visual Analytics:**
  Displays evaluated marks vs total semester marks, evaluated credits count, components completion percentage, and maximum achievable potential.
- **💾 Automatic Local Storage:**
  Never lose your marks. Your inputs are safely auto-saved locally in your browser session.
- **🖨️ Clean Print / PDF Export:**
  Instant formatted one-page grade summary ready for printing or saving to PDF.
- **🔒 Switchable Modes:**
  Toggle between **Progressive Mode** (evaluates based on entered fields only) and **Strict Final Mode** (treats unfilled components as 0 for final grade verification).

---

## 📚 Semester 1 Subject & Credit Breakdown (Total: 22 Credits)

### 4-Credit Subjects (100 Theory + 25 Practical)
- **Theory (3 Credits weight, 100 Marks total):**
  - CI-1: 20 Marks
  - CI-2: 20 Marks
  - CI-3: 10 Marks
  - End Sem: 50 Marks
- **Practical (1 Credit weight, 25 Marks total):**
  - Practical exam / submission: 25 Marks

| Subject | Theory Max | Practical Max | Total Marks | Credits |
| :--- | :---: | :---: | :---: | :---: |
| **Engineering Mathematics** | 100 | 25 | 125 | 4 |
| **PST (Problem Solving & Thinking)** | 100 | 25 | 125 | 4 |
| **Applied Science (Chemistry)** | 100 | 25 | 125 | 4 |
| **BMAC (Basics of Mech & Civil)** | 100 | 25 | 125 | 4 |

---

### 2-Credit Subjects
| Subject | Evaluation Scheme | Total Marks | Credits |
| :--- | :--- | :---: | :---: |
| **IKS (Indian Knowledge Systems)** | CI-1 (20) + CI-2 (20) + CI-3 (10) | 50 | 2 |
| **DTI (Design Thinking & Innovation)** | PPT 1 (10) + PPT 2 (10) + Quiz (10) + Project (20) + Practical (25) | 75 | 2 |
| **CHSV (Constitution, Ethics & Human Values)** | CI-1 (20) + CI-2 (20) + CI-3 (10) + Homework (25) | 75 | 2 |

---

## 📈 Grading Scale

Standard 10-Point UGC / Autonomous University Scale:

| Percentage Range | Grade | Grade Point | Performance Description |
| :---: | :---: | :---: | :--- |
| **90% – 100%** | **O** | **10.0** | Outstanding |
| **80% – 89.9%** | **A+** | **9.0** | Excellent |
| **70% – 79.9%** | **A** | **8.0** | Very Good |
| **60% – 69.9%** | **B+** | **7.0** | Good |
| **50% – 59.9%** | **B** | **6.0** | Above Average |
| **40% – 49.9%** | **C / P** | **5.0** | Pass |
| **Below 40%** | **F** | **0.0** | Fail |

---

## 🚀 How to Use / Host via GitHub Pages

1. Go to your repository settings on GitHub: **Settings** -> **Pages**.
2. Under **Build and deployment** -> **Branch**, select `main` (root) and click **Save**.
3. Your calculator will be live at `https://snehil069.github.io/calculator/`!

---

## 💻 Tech Stack

- **HTML5 & Vanilla JavaScript** (Zero external dependencies)
- **Modern CSS3** (Flexbox, CSS Grid, Custom Properties, Glassmorphism)
- **Google Fonts** (Plus Jakarta Sans & JetBrains Mono)
