# Contributing to MedModr

[![GitHub](https://img.shields.io/badge/Hosted%20on-GitHub-181717?logo=github&logoColor=white)](https://github.com/medmodr/medmodr)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Mission

MedModr is a free, open-source application for mediation, moderation, and conditional process analysis. Inspired by the **Hayes PROCESS framework**, it was developed to reduce the barriers created by commercial statistical software and the programming expertise often required by existing alternatives. The project aims to make advanced statistical methods more accessible to researchers, students, independent scholars, and institutions, particularly in low-resource settings.
To maximize accessibility, MedModr is distributed as a **single self-contained HTML file** that runs directly in any modern web browser without installation, external dependencies, or server requirements.

---

## Open Source and Licensing
MedModr is released under the MIT License, allowing researchers, universities, organizations, and developers to freely use, modify, extend, host, and redistribute the software.
As an open-source project, MedModr welcomes contributions from statisticians, methodologists, developers, educators, and researchers to:
- Validate statistical methods
- Identify and report bugs
- Improve existing features
- Develop new analytical capabilities
- Enhance documentation and educational resources
---

## Ways to Contribute
Contributions of all sizes are welcome, regardless of your background or level of experience. You can help by:
**Reporting bugs** with clear reproduction steps.
**Suggesting new features** or statistical methods.
**Improving documentation** by correcting errors or expanding explanations.
**Writing code** to fix issues or implement new functionality.
**Translating** the application or documentation into additional languages.
**Validating statistical methods** against established literature and software.
**Creating tutorials** (videos, blog posts, articles, or teaching materials) demonstrating MedModr on platforms such as YouTube, Medium, LinkedIn, or personal academic websites.
**Contributing institutional improvements** by submitting pull requests for custom features developed within your organization.

---

## Reporting Bugs
If you discover a bug, such as incorrect statistical results, user interface issues, or unexpected application behavior, please:
1. Search existing issues to avoid duplicate reports.
2. Open a new issue using the **bug** label.
3. Include the following information:
   - Browser and version (e.g., Chrome 120 or Firefox 121)
   - Steps to reproduce the issue
   - Expected result and actual result (including comparisons with PROCESS Macro when appropriate)
   - Screenshots, sample data, or additional information, if available

**Example:**

```markdown
**Bug:** Mean centering produces incorrect interaction term coefficients.
**Browser:** Firefox 121 on macOS
**Steps:**
1. Upload the Psychology dataset with variables X, Y, and W.
2. Run a "Simple Moderation (Model 1)" analysis with mean centering enabled
   ("Continuous-only centered").
3. Compare the interaction term coefficient against manually centered results
   and/or PROCESS Macro output.
**Expected:** The interaction coefficient should match manual mean centering
and/or PROCESS Macro output.
**Actual:** The interaction coefficient in MedModr differs, suggesting centering is applied
incorrectly or post-centering multiplication is flawed.
```

---

## Feature Requests
Suggestions for new features are encouraged. Please open an issue using the `enhancement`  label and include:
- A description of the proposed statistical method or functionality
- The motivation for adding the feature
- Relevant methodological references or supporting literature, where applicable

### Priority Areas

The following areas are considered high-priority for future development.
#### 1. Multilevel Mediation, Moderation, and Conditional Process Analysis

Support mediation and moderation models for hierarchical and nested data structures (e.g., students within schools or patients within hospitals).

#### 2. Structural Equation Modeling (SEM)

Develop comprehensive SEM capabilities, including:

- **Covariance-Based SEM (CBSEM)** with model fit indices (CFI, TLI, RMSEA, SRMR), factor loadings, validity, and reliability assessment.
- **Partial Least Squares SEM (PLS-SEM)** for exploratory analyses and smaller sample sizes.
- **Integrated User Workflow** allowing users to specify measurement models, evaluate model fit, assess validity and reliability, and perform structural analyses within a single interface.

#### 3. Bayesian Mediation, Moderation, and Conditional Process Analysis

Implement Bayesian estimation methods with support for:

- Prior specification (default, weakly informative, and user-defined)
- Posterior distributions and credible intervals
- Bayes factors
- Convergence diagnostics (R-hat and effective sample size)

#### 4. User Interface, Visualization, and Performance

Contributions are encouraged in areas such as:

- Improved error handling and user feedback
- Performance optimization for large datasets
- Accessibility improvements
- Mobile responsiveness
- Dark mode and theme customization
- Keyboard shortcuts
- Localization for additional languages
- Path diagrams for currently unsupported analyses
- Enhanced path diagrams with coefficient and p-value labels
- Improved layout, styling, and interactivity of existing diagrams
- Overall interface redesign to create a more polished, intuitive, and modern user experience

---

## Development Guidelines

Technology Stack

- **Frontend:** Pure HTML, CSS, and JavaScript
- **Distribution:** Single self-contained HTML file
- **Browser Support:** Modern browsers (Chrome, Firefox, Edge, and Safari)

### Statistical Standards

To maintain scientific rigor:

- Statistical methods should be validated against established literature.
- Results should be compared with PROCESS Macro outputs whenever applicable.
- Unit tests should accompany critical statistical calculations.

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Test thoroughly
5. Commit with a clear, descriptive message (`git commit -m "Description of changes"`)
6. Push to your fork (`git push origin feature/your-feature`)
7. Open a pull request with a detailed description of your changes

---

## Testing

Before submitting a pull request, please ensure that:

- Existing functionality continues to work correctly.
- New features have been thoroughly tested.
- Edge cases have been considered.
- The application remains fully functional as a single self-contained HTML file.

---

## Community
Community collaboration is central to the continued development of MedModr. You can participate by:
- **GitHub Issues:** Report bugs and request new features.
- **Pull Requests:** Submit code improvements and enhancements.
- **Discussions:** Share ideas, ask questions, and collaborate with other contributors.

---

Every contribution whether it is code, documentation, testing, or educational material helps make MedModr more accessible and strengthens the global open-science community.

