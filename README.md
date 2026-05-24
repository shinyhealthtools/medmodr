# MedModr: Mediation & Moderation Analysis Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-brightgreen)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0-blue)](https://github.com/shinyhealthtools/medmodr)

**MedModr** is a free browser-based tool for mediation, moderation, and conditional process analysis. All computations run locally in your browser. **Your data never leaves your device** — a privacy-first alternative to commercial software.

## 📊 Statistical Tests Performed

The application performs **9 core statistical tests**:

1.  **Simple Mediation** — Tests whether the effect of X on Y is transmitted through a single mediator M (X → M → Y).
2.  **Parallel Mediation** — Tests multiple independent mediators simultaneously (X → {M₁...Mₖ} → Y).
3.  **Serial Mediation** — Tests a causal chain of mediators (X → M₁ → M₂ → Y).
4.  **Simple Moderation** — Tests if the relationship between X and Y depends on a moderator W (X×W interaction).
5.  **First Stage Moderated Mediation** — Tests if the indirect effect (X→M→Y) depends on W moderating the X→M path.
6.  **Second Stage Moderated Mediation** — Tests if the indirect effect depends on W moderating the M→Y path.
7.  **Both Stages Moderated Mediation** — Tests if the indirect effect depends on W moderating both the X→M and M→Y paths.
8.  **Moderated Moderation (Three-Way)** — Tests a three-way interaction where the effect of X on Y is jointly moderated by W and Z (X × W × Z → Y).
9.  **Moderated Serial Mediation** — Tests if a serial indirect effect (X→M₁→M₂→Y) is moderated by W.

## 🔗 Launch & Documentation

| Resource | Link |
| :--- | :--- |
| **Primary Website** | [https://shinyhealthtools.github.io/medmodr/](https://shinyhealthtools.github.io/medmodr/) |
| **Mirror** | [https://medmodr.vercel.app/](https://medmodr.vercel.app/) |
| **Offline Use** | Download `index.html` from this repository, open it in a modern browser, and then analyze your work offline |
| **Full Documentation** | [https://shinyopensource.github.io/medmodr-documentation/](https://shinyopensource.github.io/medmodr-documentation/) (guides) |

---

**MedModr** — Transparent, private, professional mediation and moderation analysis tool.
