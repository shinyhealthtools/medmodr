# MedModr: Mediation & Moderation Analysis Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-brightgreen)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0-blue)](https://github.com/shinyhealthtools/medmodr)

**MedModr** is a free browser-based tool for mediation, moderation, and conditional process analysis. All computations run locally in your browser. **Your data never leaves your device** — a privacy-first alternative to commercial software.

## 📊 Statistical Tests Performed (with Bootstrap)

The application performs **9 core statistical tests**, all supporting **bootstrap confidence intervals** (Percentile or Bias-Corrected) for indirect effects:

| # | Test | Bootstrap Support |
| :--- | :--- | :--- |
| 1 | **Simple Mediation** — X → M → Y | ✅ Bootstrap CI for indirect effect |
| 2 | **Parallel Mediation** — X → {M₁...Mₖ} → Y | ✅ Bootstrap CI for each indirect path |
| 3 | **Serial Mediation** — X → M₁ → M₂ → Y | ✅ Bootstrap CI for serial and specific indirect effects |
| 4 | **Simple Moderation** — X × W → Y | ✅ Bootstrap CI for interaction term (optional) |
| 5 | **First Stage Moderated Mediation** — W moderates X → M | ✅ Bootstrap CI for conditional indirect effects & Index of Moderated Mediation (IMM) |
| 6 | **Second Stage Moderated Mediation** — W moderates M → Y | ✅ Bootstrap CI for conditional indirect effects & IMM |
| 7 | **Both Stages Moderated Mediation** — W moderates both X→M and M→Y | ✅ Bootstrap CI for conditional indirect effects & IMM |
| 8 | **Moderated Moderation (Three-Way)** — X × W × Z → Y | ✅ Bootstrap CI for three-way interaction term |
| 9 | **Moderated Serial Mediation** — W moderates X → M₁ → M₂ → Y | ✅ Bootstrap CI for conditional serial indirect effects & IMM |

**Bootstrap Features:**
- Adjustable number of bootstrap samples (1,000 / 5,000 / 10,000)
- Two methods: **Percentile** (default) or **Bias-Corrected (BC)**
- Reproducible results with user-configurable random seed

## 🔗 Launch & Documentation

| Resource | Link |
| :--- | :--- |
| **Primary Website** | [https://shinyhealthtools.github.io/medmodr/](https://shinyhealthtools.github.io/medmodr/) |
| **Mirror** | [https://medmodr.vercel.app/](https://medmodr.vercel.app/) |
| **Offline Use** | Download `index.html` from this repository, open it in a modern browser, and then analyze your work offline |
| **Full Documentation** | [https://shinyopensource.github.io/medmodr-documentation/](https://shinyopensource.github.io/medmodr-documentation/) (guides) |

---

**MedModr** — Transparent, private, professional mediation and moderation analysis tool.
