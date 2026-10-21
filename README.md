# MedModr

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModr-Logo.png" alt="MedModr Hero">
</p>

<p align="center">

[![GitHub downloads](https://img.shields.io/github/downloads/shinyhealthtools/medmodr/total.svg)](https://github.com/shinyhealthtools/medmodr/releases)

</p>

## About

The PROCESS macro remains a widely used observed variable path analysis modelling tool for mediation, moderation, and conditional process analysis. However, its use depends on commercial SPSS or SAS licenses, while R/ Python-based alternatives typically require programming expertise. These barriers limit access for researchers, educators, and students, particularly those in low-resource settings or underfunded institutions.

`MedModr` was therefore independently conceptualized and developed by Mudasir Mohammed Ibrahim, a Registered Nurse, self-taught data analyst, and health researcher at Tamale Teaching Hospital, Tamale, Northern Region, Ghana. It was developed to address these challenges by providing a free, browser-based, open-source platform for mediation, moderation, and conditional process analysis that requires no installation, licensing, or coding skills. `MedModr` aims to enhance the accessibility and usability of mediation, moderation, and conditional process analyses for researchers, educators, and students worldwide, with particular benefits for those in low-resource settings or underfunded institutions.

`MedModr` is a peer-reviewed, open-source research software published in **SoftwareX (Elsevier)**. For more information about the software, including its functionality, features, and applications, please refer to the published paper: https://doi.org/10.1016/j.softx.2026.102895.

## Offline Use

`MedModr` is designed with accessibility and data privacy in mind. The application requires no software installation, packages, or additional libraries. Simply download the `index.html` file, open it in any modern web browser, and begin analyzing your data.

All statistical analyses are performed locally within the browser, ensuring that your data never leaves your computer. Once the application has been downloaded, no internet connection is required for statistical analysis.

**Data file requirements:**
- **CSV files:** Fully supported offline. Users can upload and analyze CSV files without an internet connection.
- **Excel files (.xlsx, .xls):** An internet connection is required only during file upload to parse the Excel format. Once the data has been loaded, all analyses can be performed completely offline.

## Download the Latest Version

The latest version of `MedModr` is available on the official GitHub releases page: [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases)

Users are encouraged to download the most recent release to access the latest features, performance improvements, bug fixes, and supported PROCESS models.

## Interface

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModrinterface3.png" alt="MedModr Analysis Panel" width="800">
  <br>
  <em>The main analysis panel showing variable assignment and analysis options.</em>
</p>

## Features

| Category | Capabilities |
|:---|:---|
| **Analysis** | Mediation, moderation, and conditional process analyses based on widely used PROCESS macro models (Models 1–92) |
| **Inference** | Bootstrap confidence intervals (Percentile or Bias-Corrected) using 1,000, 5,000, or 10,000 bootstrap samples |
| **Standard errors** | Classical OLS or heteroskedasticity-consistent robust standard errors (HC0–HC4) for regression tables |
| **Indirect effect contrasts** | Pairwise comparison of specific indirect effects in multi-mediator models, with bootstrap SEs and confidence intervals |
| **Regression diagnostics** | One-click diagnostics for any regression table, exportable to Word |
| **Custom regression** | Fit Model tool for building OLS or logistic regressions with custom predictors and interaction terms |
| **Data Import** | CSV (fully offline) and Excel (.xlsx, .xls) files (internet required only during upload) |
| **Output** | Path diagrams, simple slopes plots, analysis summaries, and export to Word, PDF, HTML, CSV or PNG |
| **Formatting** | Choose 1 to 10 decimal places for on-screen output, downloads, and copied regression tables |
| **Productivity** | Keyboard shortcuts for running analyses, setting centering, and copying output tables |

## Supported Numbers of Moderators and Mediators

| Model(s) | Supported number |
|:---|:---|
| Model 1 | 1 moderator |
| Models 2, 3 | 2 moderators |
| Model 4 | 1 mediator (simple mediation) or 2–10 mediators (parallel mediation) |
| Model 6 | 2–10 mediators (serial, chain, or sequential mediation) |
| Models 5, 7–76 | 1–3 mediators |
| Models 80, 81 | 3–6 mediators |
| Model 82 | 4 mediators |
| Models 83–92 | 2–3 mediators |

## New Tools

### Regression Diagnostics

Click the **Diagnostics** button next to any regression table to open a full diagnostic report. It includes descriptive statistics, dominance analysis, all-subsets regression, residual and influence plots, per-case statistics, the Breusch–Pagan test, and intercorrelations. Every part of the report can be exported to Word.

### Fit Model (Custom Regression)

Build any OLS or logistic regression by combining predictors and adding your own interaction terms. Queue several models and run them together to get full tables and diagnostics for each. To view the queued models, double-click the **Add Model** button.

### Standard Errors: OLS and Robust (HC0–HC4)

Choose classical OLS standard errors or heteroskedasticity-consistent robust standard errors (HC0–HC4). Coefficients stay the same; the standard errors, t/z statistics, p-values, confidence intervals, and F test are recomputed. This option applies to regression tables only.

### Adjustable Decimal Places

Choose how many decimal places your results show, from 1 to 10. The setting applies to on-screen output, downloaded files, and copied regression tables, so the numbers are ready to use in your manuscript or report.

### Pairwise Comparison of Indirect Effects

In multi-mediator models (Models 4, 6, 80, 81, and 82), turn on **Show pairwise comparison** to see contrasts between every pair of specific indirect effects. Each contrast includes its bootstrap standard error and confidence interval, so you can test whether one indirect pathway is significantly stronger than another.

### Keyboard Shortcuts

| Action | Windows / Linux | Mac |
|:---|:---|:---|
| Run the analysis | Ctrl + Enter | ⌘ + Enter |
| Open the centering options | Ctrl + Shift + C | ⌘ + Shift + C |
| Reset centering to the default (no centering) | Ctrl + Shift + R | ⌘ + Shift + R |
| Copy an output table | Hold Ctrl, then click the table | Hold ⌘, then click the table |

While you hold the key, a **Copy Table** overlay appears on every output table. Click the table you want, and it is copied to your clipboard, ready to paste into Word, Google Docs, or Excel.

## Version History

### Version 3.0 (Beta)

Version 3.0 is a Beta release featuring an expanded library of PROCESS models spanning Models 1–92.

- The variable box labels have been revised to X, M, M2, Y, W/Z, and Cov, and the corresponding "Assign to …" labels have also been revised for consistency.
- MedModr now allows users to probe moderators using Mean ± 1 SD (default: −1 SD, mean, and +1 SD) or Percentile (16th, 50th, and 84th) values.
- New regression diagnostics, available from the **Diagnostics** button beside any regression table.
- New **Fit Model** tool for custom OLS and logistic regressions with queued models.
- New choice of classical OLS or robust (HC0–HC4) standard errors for regression tables.
- New adjustable decimal places (1–10) for output, downloads, and copied regression tables.
- New pairwise comparison of indirect effects in multi-mediator models.
- New keyboard shortcuts, including Ctrl/⌘ + click to copy any output table.

Available Analysis Types

- Model 4 — Simple mediation
- Model 4 — Parallel multiple mediation
- Model 6 — Serial mediation
- Model 80 — Multiple mediation with parallel and serial pathways
- Model 1 — Simple moderation
- Model 2 — Two-moderator moderation
- Model 3 — Three-way interaction/moderated moderation
- Model 5 — Moderated direct effect
- Model 7 — W moderates X→M
- Model 8 — W moderates X→M and X→Y
- Model 9 — W and Z moderate X→M
- Model 10 — W and Z moderate X→M and X→Y
- Model 11 — W and Z jointly moderate X→M
- Model 12 — W and Z jointly moderate X→M and X→Y
- Model 13 — W and Z jointly moderate X→M; W moderates X→Y
- Model 14 — W moderates M→Y
- Model 15 — W moderates M→Y and X→Y
- Model 16 — W and Z moderate M→Y
- Model 17 — W and Z moderate M→Y and X→Y
- Model 18 — W and Z jointly moderate M→Y
- Model 19 — W and Z jointly moderate M→Y and X→Y
- Model 20 — W and Z jointly moderate M→Y; W moderates X→Y
- Model 21 — W moderates X→M; Z moderates M→Y
- Model 22 — W moderates X→M and X→Y; Z moderates M→Y
- Model 28 — W moderates X→M; Z moderates M→Y and X→Y
- Model 29 — W and Z moderate X→M and X→Y
- Model 58 — W moderates X→M and M→Y
- Model 59 — W moderates X→M, M→Y, and X→Y
- Model 60 — W moderates X→M and M→Y; Z moderates X→M
- Model 61 — W moderates X→M, M→Y, and X→Y; Z moderates X→M
- Model 62 — W moderates X→M and M→Y; Z moderates X→M and X→Y
- Model 63 — W moderates X→M, M→Y, and X→Y; Z moderates X→M and X→Y
- Model 64 — W moderates X→M and M→Y; Z moderates M→Y
- Model 65 — W moderates X→M, M→Y, and X→Y; Z moderates M→Y
- Model 66 — W moderates X→M and M→Y; Z moderates M→Y and X→Y
- Model 67 — W moderates X→M, M→Y, and X→Y; Z moderates M→Y and X→Y
- Model 68 — W and Z jointly moderate X→M; W moderates M→Y
- Model 69 — W and Z jointly moderate X→M and X→Y; W moderates M→Y
- Model 70 — W moderates X→M; W and Z jointly moderate M→Y
- Model 71 — W moderates X→M; W and Z jointly moderate M→Y and X→Y
- Model 72 — W and Z jointly moderate X→M and M→Y
- Model 73 — W and Z jointly moderate X→M, M→Y, and X→Y
- Model 75 — W and Z moderate X→M and M→Y
- Model 76 — W and Z moderate X→M, M→Y, and X→Y
- Model 80 — Multiple mediation with parallel and serial pathways
- Model 81 — M₁, M₂, ... & Mₖ mediate X→Y in parallel and serial
- Model 82 — M₁, M₂, M₃, M₄ serial-parallel mediation
- Models 83–92 — Moderated serial mediation (moderators on one or more paths of the serial chain, with 2–3 mediators)

### Version 2.0

Version 2.0 introduces major enhancements to `MedModr`, expanding its analytical capabilities, improving visualization, and providing more flexible export options.

New PROCESS models

- Double Moderation (Model 2)
- Mediation with Moderated Direct Effect (Model 5)
- X→M and X→Y Moderated Mediation (Model 8)
- Two Moderators at X→M Stage (Model 9)
- M→Y and X→Y Moderated Mediation (Model 15)
- X→M, M→Y, and X→Y Moderated Mediation (Model 59)

Statistical improvements

- Automatic detection of binary dependent variables and logistic regression for binary outcomes
- Support for conditional direct and indirect effects with binary moderators
- Support for simple slopes plots with binary moderators

Visualization and export

- Enhanced path diagrams with adjustable line thickness (1–4 px), node size (35–80 px), and variable renaming
- High-resolution PNG export (up to 4800 px wide) with automatic cropping
- SVG export for path diagrams
- Improved automatic sizing and text wrapping for variable names
- Professional export menu supporting Word, PDF, HTML, and CSV formats

### Version 1.0

The initial release of `MedModr` included support for nine widely used PROCESS models and core statistical features.

Supported PROCESS models

- Simple Mediation (X → M → Y) — Model 4
- Parallel Mediation (X → M₁...Mₖ → Y) — Model 4
- Serial Mediation (X → M₁ → M₂ → Y) — Model 6
- Simple Moderation (X × W → Y) — Model 1
- First-Stage Moderated Mediation (W moderates X → M) — Model 7
- Second-Stage Moderated Mediation (W moderates M → Y) — Model 14
- Both-Stages Moderated Mediation (W moderates X → M and M → Y) — Model 58
- Moderated Moderation (Three-Way Interaction; X × W × Z → Y) — Model 3
- Moderated Serial Mediation (W moderates X → M₁ → M₂ → Y) — Model 83

Core features

- Ordinary Least Squares (OLS) regression for all analyses
- Bootstrap confidence intervals (Percentile or Bias-Corrected)
- CSV and Excel data import
- Path diagrams, simple slopes plots, and Word/PNG export

## Copyright Notice

The PROCESS macro for SPSS, SAS, and R, developed by Andrew F. Hayes, is a widely used tool for mediation, moderation, and conditional process analysis. The original PROCESS software and its documentation are proprietary to Dr. Hayes and are distributed through http://www.processmacro.org.

`MedModr` is an independent, open-source implementation inspired by the analytical approaches described in Dr. Hayes's work. It was developed from the ground up using native JavaScript matrix algebra and publicly available statistical methods. `MedModr` does not use, copy, or derive from the original PROCESS source code.

Although `MedModr` aims to produce results consistent with those of the PROCESS macro, it is not affiliated with, endorsed by, or associated with Andrew F. Hayes. Any errors, bugs, or inaccuracies in `MedModr` are solely the responsibility of its developer.

## Contribute

`MedModr` is an open-source project, and community contributions are welcome. Continuous testing and feedback help improve the software by identifying bugs, enhancing existing features, and suggesting new functionality.

If you would like to contribute, please read the project guidelines before submitting changes.

**CONTRIBUTING.md** → [github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md](https://github.com/shinyhealthtools/medmodr/blob/main/CONTRIBUTING.md)

## Feedback

If you encounter a bug or have a suggestion for improving `MedModr`, please open an issue on the GitHub repository. When reporting a bug, please use the [bug report template](https://github.com/shinyhealthtools/medmodr/blob/main/.github/ISSUE_TEMPLATE/bug_report.md) to help me address the issue more efficiently.

**Report an Issue** → [github.com/shinyhealthtools/medmodr/issues](https://github.com/shinyhealthtools/medmodr/issues)

## Links

The resources below provide access to the `MedModr` application, documentation, source code, and downloads.

| Resource | URL |
|:---|:---|
| Use `MedModr` Online | [shinyhealthtools.github.io/medmodr](https://shinyhealthtools.github.io/medmodr/) |
| Download the Latest Release | [github.com/shinyhealthtools/medmodr/releases](https://github.com/shinyhealthtools/medmodr/releases) |
| Documentation | [shinyopensource.github.io/medmodr-documentation](https://shinyopensource.github.io/medmodr-documentation/) |
| GitHub Repository | [github.com/shinyhealthtools/medmodr](https://github.com/shinyhealthtools/medmodr) |
| MIT License | [View License](https://github.com/shinyhealthtools/medmodr/blob/main/LICENSE) |

## Original Author

`MedModr` was independently conceptualized, developed, and is maintained without external funding by:

**Mudasir Mohammed Ibrahim**  
Department of Internal Medicine (M3),
Tamale Teaching Hospital, Tamale, Northern Region, Ghana.

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
