# MedModr: Mediation & Moderation Analysis Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-brightgreen)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0-blue)](https://github.com/shinyhealthtools/medmodr)

**MedModr** is a free browser-based tool for mediation, moderation, and conditional process analysis. All computations run locally. **Your data never leaves your device.**

## 🔌 Offline Capability

> After downloading `index.html`, MedModr runs **all statistical computations offline** (regression, bootstrap, diagrams, plots).

**File requirements:**
- ✅ **CSV files: 100% offline**
- ⚠️ **Excel files (.xlsx, .xls): Require internet connection** (uses SheetJS CDN)

> 💡 **Tip for offline use:** Save your data as CSV before disconnecting.

## 📊 Statistical Tests & PROCESS Macro Equivalents

MedModr performs the following 9 tests with bootstrap CIs (Percentile or Bias-Corrected):

| MedModr Analysis | PROCESS Model | Description |
| :--- | :--- | :--- |
| Simple Mediation | **Model 4** | X → M → Y |
| Parallel Mediation | **Model 4** | X → {M₁...Mₖ} → Y |
| Serial Mediation | **Model 6** | X → M₁ → M₂ → Y |
| Simple Moderation | **Model 1** | X × W → Y |
| First Stage Moderated Mediation | **Model 7** | W moderates X → M path |
| Second Stage Moderated Mediation | **Model 14** | W moderates M → Y path |
| Both Stages Moderated Mediation | **Model 58** | W moderates X→M and M→Y paths |
| Moderated Moderation | **Model 3** | Three-way interaction: X × W × Z → Y |
| Moderated Serial Mediation | **Model 83** | W moderates X → M₁ → M₂ → Y |

**Bootstrap options:** 1000/5000/1000 samples, Percentile or Bias-Corrected, reproducible with custom seed.

## 🔗 Links

| Resource | Link |
| :--- | :--- |
| **Live App** | [https://shinyhealthtools.github.io/medmodr/](https://shinyhealthtools.github.io/medmodr/) |
| **Mirror** | [https://medmodr.vercel.app/](https://medmodr.vercel.app/) |
| **Documentation** | [https://shinyopensource.github.io/medmodr-documentation/](https://shinyopensource.github.io/medmodr-documentation/) |

---

**MedModr** — Transparent, private, professional mediation and moderation analysis. 
