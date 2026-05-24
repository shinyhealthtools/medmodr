# MedModr: Mediation & Moderation Analysis Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-brightgreen)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0-blue)](https://github.com/shinyhealthtools/medmodr)

**MedModr** is a free browser-based tool for mediation, moderation, and conditional process analysis. All computations run locally. **Your data never leaves your device.**

## 🔌 Offline Capability — Important Distinction

> After downloading `index.html`, MedModr runs **all statistical computations offline** (regression, bootstrap, diagrams, plots).

**File upload requirements:**
- ✅ **CSV files: 100% offline** — No internet connection required
- ⚠️ **Excel files (.xlsx, .xls): Require internet connection** — Uses SheetJS CDN for parsing

> 💡 **Recommendation for offline use:** Save your data as CSV before disconnecting from the internet.

**To use completely offline:**
1. Download `index.html` (single file)
2. Convert Excel data to CSV format
3. Disconnect internet
4. Open `index.html` and upload CSV files
5. Analyze — **no server. no tracking. no cloud.**

## 📊 Statistical Tests (PROCESS Macro Models)

All 9 tests support **bootstrap CIs** (Percentile or BC) for indirect effects:

| PROCESS Model | Test |
| :--- | :--- |
| **Model 4** | Simple Mediation (X → M → Y) & Parallel Mediation (X → {M₁...Mₖ} → Y) |
| **Model 6** | Serial Mediation (X → M₁ → M₂ → Y) |
| **Model 1** | Simple Moderation (X × W → Y) |
| **Model 7** | First Stage Moderated Mediation (W moderates X → M) |
| **Model 14** | Second Stage Moderated Mediation (W moderates M → Y) |
| **Model 58** | Both Stages Moderated Mediation (W moderates X→M and M→Y) |
| **Model 3** | Moderated Moderation / Three-Way Interaction (X × W × Z → Y) |
| **Model 83** | Moderated Serial Mediation (W moderates X → M₁ → M₂ → Y) |

**Bootstrap options:** 1K/5K/10K samples, Percentile or Bias-Corrected, reproducible with custom seed.

## 🔗 Links

| Resource | Link |
| :--- | :--- |
| **Live App** | [https://shinyhealthtools.github.io/medmodr/](https://shinyhealthtools.github.io/medmodr/) |
| **Mirror** | [https://medmodr.vercel.app/](https://medmodr.vercel.app/) |
| **Documentation** | [https://shinyopensource.github.io/medmodr-documentation/](https://shinyopensource.github.io/medmodr-documentation/) |

---

**MedModr** — Transparent, private, professional mediation and moderation analysis.

**📁 One file. CSV works offline. Excel needs internet. All computations run locally.**
