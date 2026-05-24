# MedModr

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES2020-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-lightgrey.svg)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0.0-teal.svg)](https://github.com/shinyhealthtools/medmodr)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)]()
[![PRs](https://img.shields.io/badge/PRs-Welcome-orange.svg)]()

**MedModr** is a browser-based application for mediation, moderation, and conditional process analysis. All computations execute locally on the user's device. No data transmission occurs — ensuring complete privacy.

---

## 🔧 Features

| Category | Capabilities |
|:---|:---|
| **Analysis** | 9 statistical tests with PROCESS macro equivalents (Models 1, 3, 4, 6, 7, 14, 58, 83) |
| **Inference** | Bootstrap confidence intervals (Percentile / Bias-Corrected) with configurable samples (1K–10K) |
| **Data Handling** | CSV (offline) and Excel (online) import, missing data imputation (7 methods), outlier detection |
| **Output** | Path diagrams, simple slopes plots, Word/PNG export, APA-style summaries |
| **Privacy** | Zero data transmission — all processing occurs client-side |

---

## 📊 Statistical Tests

| Test | PROCESS Model |
|:---|:---:|
| Simple Mediation | 4 |
| Parallel Mediation | 4 |
| Serial Mediation | 6 |
| Simple Moderation | 1 |
| First Stage Moderated Mediation | 7 |
| Second Stage Moderated Mediation | 14 |
| Both Stages Moderated Mediation | 58 |
| Moderated Moderation (Three-Way) | 3 |
| Moderated Serial Mediation | 83 |

---

## 🚀 Quick Start

### Online Access

| Resource | URL |
|:---|:---|
| Primary Host | [shinyhealthtools.github.io/medmodr](https://shinyhealthtools.github.io/medmodr/) |
| Mirror | [medmodr.vercel.app](https://medmodr.vercel.app/) |
| Documentation | [shinyopensource.github.io/medmodr-documentation](https://shinyopensource.github.io/medmodr-documentation/) |

### Offline Usage

| File Type | Offline Support |
|:---|:---:|
| CSV | ✅ Full support |
| Excel (.xlsx, .xls) | ⚠️ Requires internet (SheetJS CDN) |

**Offline setup:**
1. Download `index.html`
2. Convert Excel data to CSV if needed
3. Open file in any modern browser
4. Disconnect from network (optional)

---

## 📦 Dependencies

| Library | Purpose | Load Method |
|:---|:---|:---|
| SheetJS (XLSX) | Excel file parsing | CDN (online only) |
| Chart.js | Diagnostic plots | CDN |
| Font Awesome | UI icons | CDN |

> **Note:** All core statistical computations (regression, bootstrap, matrix operations) use native JavaScript — no external dependencies required for CSV workflows.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for details.

---

## 👤 Author

**Mudasir Mohammed Ibrahim**
- Website: [mudasiribrahim.github.io/gh](https://mudasiribrahim.github.io/gh/)
- ResearchGate: [Mudasir Ibrahim](https://www.researchgate.net/profile/Mudasir-Ibrahim)
- Email: [mudassiribrahim30@gmail.com](mailto:mudassiribrahim30@gmail.com)

---

## 📌 Citation

```bibtex
@software{Ibrahim_MedModr_2026,
  author = {Ibrahim, Mudasir Mohammed},
  title = {MedModr: Mediation and Moderation Analysis Tool},
  year = {2026},
  version = {1.0.0},
  url = {https://shinyhealthtools.github.io/medmodr/}
}
