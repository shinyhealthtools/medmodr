# Contributing to MedModr

[![GitHub](https://img.shields.io/badge/Hosted%20on-GitHub-181717?logo=github&logoColor=white)](https://github.com/medmodr/medmodr)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Mission

MedModr is a free, user-friendly, open-source application for mediation, moderation, and conditional process analysis. Inspired by the **Hayes PROCESS framework**, it was built to lower the barriers created by SPSS/SAS licensing costs and the programming demands that often exclude researchers in low-resource settings. The tool is designed to serve underserved individuals, including researchers with limited institutional support, independent scholars, and students in regions where expensive statistical software remains out of reach.

The application is distributed as a **single self-contained HTML file**, making it easy to share, host, and run directly in any modern web browser with no installation or server requirements.

---

## License and Freedom to Use

Released under the MIT License, MedModr can be freely modified, extended, hosted, and redistributed by researchers, colleges and universities, organizations, and research centers without licensing restrictions.

The open-source design invites statisticians, methodologists, and developers to:
- Validate implemented statistical methods
- Report bugs and inaccuracies
- Contribute improvements that enhance the application over time

### Encouragement for Adopters

If your institution, research center, or organization adopts MedModr for internal use, hosts a customized version, or develops new features for your specific needs, I strongly encourage you to submit a pull request with those improvements to this official repository.

Even features developed for local requirements often have broader applicability. By contributing back, you help to:
- Reduce duplication of effort across institutions
- Improve the tool for underserved researchers globally
- Ensure the long-term sustainability of open-source statistical software
- Receive community feedback and ongoing maintenance support for your contributions

No contribution is too small. Improvements developed for a specific use case frequently prove valuable to the wider research community.

---

## Code of Conduct

This project is committed to providing a welcoming and harassment-free experience for everyone. All participants are expected to engage respectfully, inclusively, and constructively.

---

## How to Contribute

There are many ways to contribute, regardless of your background or skill set:

- **Report bugs** — Open an issue with clear reproduction steps.
- **Suggest features** — Propose new statistical tools or functionality improvements.
- **Improve documentation** — Fix typos, clarify instructions, or expand usage examples.
- **Write code** — Resolve open issues or implement new features.
- **Translate** — Help localize MedModr for non-English-speaking users.
- **Validate methods** — Review statistical implementations against established literature.
- **Create tutorials** — Produce educational content (videos, blog posts, or articles) demonstrating MedModr on platforms such as YouTube, Medium, LinkedIn, or personal academic websites. Tutorials help make advanced statistical methods accessible to wider audiences.
- **Contribute back** — If your institution or organization has developed custom features on top of MedModr, submit a pull request so the broader community can benefit.

---

## Reporting Bugs

To report a bug such as incorrect p-values, UI failures, or calculation errors, please follow these steps:

1. Search existing issues to avoid duplicates.
2. Open a new issue with the label `bug`.
3. Include the following information:
   - Browser and version (e.g., Chrome 120, Firefox 121)
   - Steps to reproduce the issue
   - Expected result versus actual result (reference PROCESS Macro output where applicable)
   - A screenshot, if available

**Example:**

```markdown
**Bug:** Mean centering produces incorrect interaction term coefficients.
**Browser:** Firefox 121 on macOS
**Steps:**
1. Upload a dataset with variables X, M, and Y.
2. Run a simple moderation (Hayes Model 1) analysis with mean centering enabled
   ("Continuous-only centered").
3. Compare the interaction term coefficient against manually centered results
   and/or PROCESS Macro output.
**Expected:** The interaction coefficient should match manual mean centering
and/or PROCESS Macro output.
**Actual:** The interaction coefficient differs, suggesting centering is applied
incorrectly or post-centering multiplication is flawed.
```

---

## Feature Requests

I welcome proposals for new features. Please open an issue with the label `enhancement` and describe:
- The statistical method or functionality you would like to implement
- Why it would benefit researchers, with reference to specific use cases or published research
- Any relevant literature or methodological references

### Priority Features

The following are high-impact areas where contributions are especially encouraged:

#### 1. Multilevel Mediation, Moderation, and Conditional Process Analysis

Extend MedModr to support multilevel and hierarchical data structures, enabling researchers to analyze nested data (e.g., students within schools, patients within clinics) using mediation and moderation models.

#### 2. Structural Equation Modeling (SEM)

- **Covariance-Based SEM (CBSEM):** Allow users to specify latent variable models, assess model fit using indices such as CFI, TLI, RMSEA, and SRMR, and obtain factor loadings, validity, and reliability estimates.
- **Partial Least Squares SEM (PLS-SEM):** Support composite-based estimation suitable for exploratory research and small sample sizes.
- **Integrated User Workflow:** Allow users to enter all items in a single interface, inspect factor loadings, evaluate and refine model fit interactively, assess validity and reliability, and specify the analysis type — all within one seamless workflow.

#### 3. Bayesian Mediation, Moderation, and Conditional Process Analysis

Implement Bayesian estimation methods for mediation and moderation models, including:
- Prior specification options (default, weakly informative, and user-defined)
- Posterior distributions and credible intervals
- Bayes factors for hypothesis testing
- Convergence diagnostics (R-hat and effective sample size)

#### 4. Enhanced UI/UX and Application Robustness

Developers are encouraged to contribute improvements that make the application more robust and intuitive, including:

- Improved error handling and user feedback
- Performance optimizations for large datasets
- Accessibility enhancements
- Mobile responsiveness improvements
- Dark mode and theme customization
- Keyboard shortcuts for power users
- Localization support for additional languages
- Path diagrams for analysis types that currently lack visual output, with coefficient and p-value labels displayed directly on path lines, and customization options consistent with existing diagrams
- Improvements to existing path diagrams, including better layout, styling, and interactivity
- Overall UI redesign and modernization to make the application more visually appealing, polished, and user-friendly across all sections and workflows
---

## Development Guidelines

### Technology Stack

- **Frontend:** Pure HTML, CSS, and JavaScript (no frameworks required)
- **Distribution:** Single self-contained HTML file
- **Browser Support:** Modern browsers (Chrome, Firefox, Edge, and Safari)

### Statistical Accuracy

- All statistical methods must be validated against established literature
- Reference PROCESS Macro outputs for comparison where applicable
- Include unit tests for critical calculations

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
- All existing functionality works as expected
- New features are properly tested
- Edge cases are handled gracefully
- The application continues to function as a single self-contained HTML file

---

## Community

Join the conversation to discuss development, ask questions, and share ideas:
- **GitHub Issues:** Report bugs and request features
- **Pull Requests:** Contribute code and improvements
- **Discussions:** Share ideas and get help from other contributors

---

## Acknowledgments

I am grateful to everyone who helps make MedModr a valuable resource for researchers worldwide. Your time, expertise, and contributions however large or small directly support researchers who lack access to commercial statistical tools.

MedModr was created and is currently maintained by **[Mudasir Mohammed Ibrahim](https://mudasiribrahim.github.io/gh/)**. Community contributions are essential to its growth and sustainability, and every improvement you make helps advance open and accessible science globally.
