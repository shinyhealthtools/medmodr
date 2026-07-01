# MedModr

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModr-Logo.png" alt="MedModr Hero">
</p>

## About

MedModr is a free, browser-based, open-source application for mediation, moderation, and conditional process analysis, developed by Mudasir Mohammed Ibrahim, a registered nurse and health researcher at Tamale Teaching Hospital, Ghana. The software was created to address the limited access to affordable statistical tools for advanced modeling, particularly in resource-constrained settings.

While the PROCESS macro remains a widely used approach for mediation and moderation analysis, its use often depends on commercial SPSS or SAS licenses, and R-based alternatives require programming expertise. These barriers can limit access for researchers, students, clinicians, and independent scholars.

MedModr provides an accessible alternative by offering a no-cost, browser-based platform that requires no installation, licensing, or coding skills. All analyses are performed locally within the user's browser, ensuring data privacy and security.

The application currently supports 15 widely used PROCESS models, with ongoing development aimed at expanding model coverage and enhancing functionality to meet the evolving needs of the research community.

## Offline Use

MedModr prioritizes accessibility and data privacy. No libraries, packages, or software installations are required. Users simply download the `index.html` file, open it in any modern web browser, and begin analysis immediately.

All statistical computations are performed locally in the browser. No internet connection is required after the initial download.

**Data file requirements:**
- **CSV files:** Full offline support. Users can upload and analyze without internet connectivity.
- **Excel files (.xlsx, .xls):** Internet connection is required only during file upload to parse the Excel format. After the data is loaded, users can disconnect from the internet and run the complete analysis offline.

## Download the Latest Version

**Get the latest release:** [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases)

Users should always download the newest version from the official releases page and check back regularly for updates, bug fixes, and new features.

## Interface

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModrinterface3.png" alt="MedModr Analysis Panel" width="800">
  <br>
  <em>The main analysis panel showing variable assignment, analysis options, and results display.</em>
</p>

## Features

| Category | Capabilities |
|:---|:---|
| **Analysis** | Mediation, moderation, and conditional process analyses (PROCESS macro equivalents) |
| **Inference** | Bootstrap confidence intervals (Percentile or Bias-Corrected) with 1000, 5000, and 10000 samples |
| **Data Import** | CSV (fully offline) or Excel (internet required only for upload) |
| **Output** | Path diagrams, simple slopes plots, Word/PNG export, summaries |

## Version History

### Version 2.0

- Added 6 new PROCESS models: Double Moderation (Model 2), Mediation with Moderated Direct Effect (Model 5), X→M and X→Y Moderated Mediation (Model 8), Two Moderators Separate Stages (Model 9), M→Y and X→Y Moderated Mediation (Model 15), and X→M, M→Y and X→Y Moderated Mediation (Model 59)
- Automatic logistic regression detection for binary dependent variables. Version 1 used Ordinary Least Squares (OLS) regression. Version 2 introduces logistic regression for binary outcomes.
- Enhanced path diagrams with adjustable line thickness (1px to 4px), adjustable node size (35px to 80px), and variable renaming
- PNG export with high resolution (up to 4800px width) and auto cropping
- SVG export format for path diagrams
- Improved auto sizing and text wrapping for variable names
- Professional export dropdown menu with Word, PDF, HTML, and CSV options
- Simple slopes plots now support binary moderators
- Conditional direct and indirect effects now support binary moderators

### Version 1.0

- Simple Mediation (X → M → Y) — PROCESS Model 4
- Parallel Mediation (X → M₁...Mₖ → Y) — PROCESS Model 4
- Serial Mediation (X → M₁ → M₂ → Y) — PROCESS Model 6
- Simple Moderation (X × W → Y) — PROCESS Model 1
- First Stage Moderated Mediation (W moderates X → M) — PROCESS Model 7
- Second Stage Moderated Mediation (W moderates M → Y) — PROCESS Model 14
- Both Stages Moderated Mediation (W moderates X→M and M→Y) — PROCESS Model 58
- Moderated Moderation / Three-Way Interaction (X × W × Z → Y) — PROCESS Model 3
- Moderated Serial Mediation (W moderates X → M₁ → M₂ → Y) — PROCESS Model 83
- Bootstrap confidence intervals (Percentile or Bias-Corrected)
- CSV and Excel data import
- Path diagrams, simple slopes plots, and Word/PNG export
- Ordinary Least Squares (OLS) regression for all analyses

## Copyright Notice

The PROCESS macro for SPSS, SAS and R, developed by Andrew F. Hayes, is a widely used tool for mediation and moderation analysis. The original PROCESS software and its documentation are proprietary to Dr. Hayes and are distributed through http://www.processmacro.org.

MedModr is an independent, open source implementation inspired by the analytical approaches described in Dr. Hayes's work. This project was developed using native JavaScript matrix algebra from scratch using publicly available statistical methods. MedModr does not use, copy, or derive from the original PROCESS source code.

While MedModr aims to produce results consistent with the PROCESS macro, it is not affiliated with, endorsed by, or connected to Andrew F. Hayes. Any errors, bugs, or inaccuracies in MedModr are solely the responsibility of its developer.

## Contribute

No software is perfect. Continuous testing is encouraged to help identify and resolve issues. Users who find bugs should report them promptly to ensure timely fixes.

To contribute to MedModr, please read the contributing guidelines.

**Read CONTRIBUTING.md** → [github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md](https://github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md)

## Feedback

Found a bug? Open an issue on GitHub.

**Report Bugs** → [github.com/shinyhealthtools/medmodr/issues](https://github.com/shinyhealthtools/medmodr/issues)

## Links

| Resource | URL |
|:---|:---|
| Live App | [shinyhealthtools.github.io/medmodr](https://shinyhealthtools.github.io/medmodr/) |
| Downloads (Releases) | [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases) |
| Documentation | [shinyopensource.github.io/medmodr-documentation](https://shinyopensource.github.io/medmodr-documentation/) |
| MIT License | [View License](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE) |
| GitHub Repository | [github.com/shinyhealthtools/medmodr](https://github.com/shinyhealthtools/medmodr) |

## Original Author

**Mudasir Mohammed Ibrahim**  
Department of Internal Medicine (M3), Tamale Teaching Hospital, Ghana

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
  version = {2.0.0},
  url = {https://shinyhealthtools.github.io/medmodr/}
}
