# MedModr

<p align="center">
  <img src="https://raw.githubusercontent.com/shinyhealthtools/medmodr/main/favicons/MedModr-Logo.png" alt="MedModr Hero">
</p>

<p align="center">

[![GitHub downloads](https://img.shields.io/github/downloads/shinyhealthtools/medmodr/total.svg)](https://github.com/shinyhealthtools/medmodr/releases)

</p>

## About

The PROCESS macro remains a widely used tool for mediation, moderation, and conditional process analysis. However, its use depends on commercial SPSS or SAS licenses, while R/ Python-based alternatives typically require programming expertise. These barriers limit access for researchers, students, clinicians, and independent scholars, particularly those with limited funding or technical support.

`MedModr` was therefore independently conceptualized and developed by Mudasir Mohammed Ibrahim, a Registered Nurse and health researcher at Tamale Teaching Hospital, Ghana. It was developed to address these challenges by providing a free, browser-based, open-source platform for mediation, moderation, and conditional process analysis that requires no installation, licensing, or coding skills. `MedModr` aims to enhance the accessibility and usability of mediation, moderation, and conditional process analyses for researchers, educators, and students worldwide, with particular benefits for early-career researchers and institutions with limited access to commercial statistical software or advanced programming expertise.

`MedModr` is a peer-reviewed, open-source research software published in **SoftwareX (Elsevier)**. For more information about the software, including its functionality, features, and applications, please refer to the published paper: https://doi.org/10.1016/j.softx.2026.102895. The application currently supports fifteen (15) widely used PROCESS models, with ongoing development focused on expanding model coverage and enhancing functionality to meet the evolving needs of the research community.


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
| **Analysis** | Mediation, moderation, and conditional process analyses based on widely used PROCESS macro models |
| **Inference** | Bootstrap confidence intervals (Percentile or Bias-Corrected) using 1,000, 5,000, or 10,000 bootstrap samples |
| **Data Import** | CSV (fully offline) and Excel (.xlsx, .xls) files (internet required only during upload) |
| **Output** | Path diagrams, simple slopes plots, analysis summaries, and export to Word, PDF, HTML, CSV or PNG |

## Version History

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
