# MedModr

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/medmodr/MedModr-Logo.png" alt="MedModr Hero" width="300" height="300">
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES2020-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-lightgrey.svg)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0.0-teal.svg)](https://github.com/shinyhealthtools/medmodr)

**MedModr** is a browser-based application for mediation, moderation, and conditional process analysis. All computations execute locally in the user's browser, ensuring complete privacy.

## Interface

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/screenshots/analysis-panel.png" alt="MedModr Analysis Panel" width="800">
  <br>
  <em>The main analysis panel showing variable assignment, analysis options, and results display.</em>
</p>

## Features

| Category | Capabilities |
|:---|:---|
| **Analysis** | 9 statistical tests with PROCESS macro equivalents |
| **Inference** | Bootstrap confidence intervals (Percentile or Bias-Corrected) with 1K–10K samples |
| **Data Import** | CSV (fully offline) or Excel (requires internet only for upload) |
| **Output** | Path diagrams, simple slopes plots, Word/PNG export, APA summaries |

## Statistical Tests and PROCESS Macro Equivalents

| MedModr Performs This Test | Equivalent PROCESS Model |
|:---|:---:|
| Simple Mediation (X → M → Y) | Model 4 |
| Parallel Mediation (X → M₁...Mₖ → Y) | Model 4 |
| Serial Mediation (X → M₁ → M₂ → Y) | Model 6 |
| Simple Moderation (X × W → Y) | Model 1 |
| First Stage Moderated Mediation (W moderates X → M) | Model 7 |
| Second Stage Moderated Mediation (W moderates M → Y) | Model 14 |
| Both Stages Moderated Mediation (W moderates X→M and M→Y) | Model 58 |
| Moderated Moderation / Three-Way Interaction (X × W × Z → Y) | Model 3 |
| Moderated Serial Mediation (W moderates X → M₁ → M₂ → Y) | Model 83 |

## Offline Use

After downloading `index.html`, all statistical computations run offline with **no internet required**.

**Data file requirements:**
- **CSV files:** Complete offline support — upload and analyze without internet
- **Excel files (.xlsx, .xls):** Internet connection is needed **only during file upload** (to parse the Excel format). After the data is loaded, disconnect from the internet and run the full analysis offline.

## Links

| Resource | URL |
|:---|:---|
| Live App | [shinyhealthtools.github.io/medmodr](https://shinyhealthtools.github.io/medmodr/) |
| Mirror | [medmodr.vercel.app](https://medmodr.vercel.app/) |
| Full Documentation | [shinyopensource.github.io/medmodr-documentation](https://shinyopensource.github.io/medmodr-documentation/) |
| MIT License | [View License](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE) |

## Author

Mudasir Mohammed Ibrahim
- Website: [mudasiribrahim.github.io/gh](https://mudasiribrahim.github.io/gh/)
- ResearchGate: [Mudasir Ibrahim](https://www.researchgate.net/profile/Mudasir-Ibrahim)
- Email: [mudassiribrahim30@gmail.com](mailto:mudassiribrahim30@gmail.com)

## Citation

```bibtex
@software{Ibrahim_MedModr_2026,
  author = {Ibrahim, Mudasir Mohammed},
  title = {MedModr: Mediation and Moderation Analysis Tool},
  year = {2026},
  version = {1.0.0},
  url = {https://shinyhealthtools.github.io/medmodr/}
}
