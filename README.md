# MedModr

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModr-Logo.png" alt="MedModr Hero" width="300" height="300">
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Offline-lightgrey.svg)](https://shinyhealthtools.github.io/medmodr/)
[![Version](https://img.shields.io/badge/Version-1.0-teal.svg)](https://github.com/shinyhealthtools/medmodr/releases)

**MedModr** performs mediation, moderation, and conditional process analysis in the user's browser, ensuring complete privacy.

## Offline Use

Download the `index.html` file, open it in any web browser, and start your analysis. All statistical computations run offline with **no internet required**.

**Data file requirements:**
- **CSV files:** Complete offline support — upload and analyze without internet
- **Excel files (.xlsx, .xls):** Internet connection is needed **only during file upload** (to parse the Excel format). After the data is loaded, disconnect from the internet and run the full analysis offline.

## Download the Latest Version

> **Get the latest release here:** [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases)
>
> Always download the newest version from the official releases page. Check back regularly for updates, bug fixes, and new features.

---

## Interface

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/medmodr/MedModrinterface.png" alt="MedModr Analysis Panel" width="800">
  <br>
  <em>The main analysis panel showing variable assignment, analysis options, and results display.</em>
</p>

## Features

| Category | Capabilities |
|:---|:---|
| **Analysis** | 9 statistical tests with PROCESS macro equivalents |
| **Inference** | Bootstrap confidence intervals (Percentile or Bias-Corrected) with 1000, 5000, and 10000 samples |
| **Data Import** | CSV (fully offline) or Excel (requires internet only for upload) |
| **Output** | Path diagrams, simple slopes plots, Word/PNG export, Summaries |

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

## Contribute

Want to contribute?

🔧 **Please read CONTRIBUTING.md** → [github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md](https://github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md)

## Feedback

Found a bug? Open an issue on GitHub.

**Report Bugs** → [github.com/shinyhealthtools/medmodr/issues](https://github.com/shinyhealthtools/medmodr/issues)

## Links

| Resource | URL |
|:---|:---|
| Live App | [shinyhealthtools.github.io/medmodr](https://shinyhealthtools.github.io/medmodr/) |
| Mirror | [medmodr.vercel.app](https://medmodr.vercel.app/) |
| Downloads (Releases) | [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases) |
| Documentation | [shinyopensource.github.io/medmodr-documentation](https://shinyopensource.github.io/medmodr-documentation/) |
| MIT License | [View License](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE) |
| GitHub Repository | [github.com/shinyhealthtools/medmodr](https://github.com/shinyhealthtools/medmodr) |

## Author

**Mudasir Mohammed Ibrahim**  
*Department of Internal Medicine (M3), Tamale Teaching Hospital, Ghana*

<p align="center">
  <a href="https://mudasiribrahim.github.io/gh/" target="_blank">
    <img src="https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
  <a href="https://linkedin.com/in/mudasir-mohammed-ibrahim-16b5141b0" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.researchgate.net/profile/Mudasir-Ibrahim" target="_blank">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate">
  </a>
  <a href="mailto:mudassiribrahim30@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

## Citation

```bibtex
@software{Ibrahim_MedModr_2026,
  author = {Ibrahim, Mudasir Mohammed},
  title = {MedModr: Mediation and Moderation Analysis Tool},
  year = {2026},
  version = {1.0.0},
  url = {https://shinyhealthtools.github.io/medmodr/}
}
