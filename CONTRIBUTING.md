# Contributing to MedModr

[![GitHub](https://img.shields.io/badge/Hosted%20on-GitHub-181717?logo=github&logoColor=white)](https://github.com/medmodr/medmodr)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Mission

MedModr aims to democratize access to mediation, moderation, and conditional process analysis for underserved individuals, including researchers with limited institutional resources, independent scholars, and students in regions where expensive statistical software is inaccessible.

---

## License and Freedom to Use

Released under the MIT License, MedModr can be freely modified, extended, hosted, and redistributed by researchers, colleges and universities, organizations, and research centers without licensing restrictions.

The open-source design allows statisticians, methodologists, and developers to:
- Validate implemented statistical methods
- Report bugs and inaccuracies
- Contribute improvements to enhance the application over time

### Encouragement for Adopters

If your institution, research center, or organization adopts MedModr for internal use, hosts a customized version, or develops new features for your specific needs, we strongly encourage you to submit a pull request with those improvements to this official repository.

Even if a feature was developed for local requirements, it may benefit the broader research community. By contributing back, you help:
- Reduce duplication of effort across institutions
- Improve the tool for underserved researchers globally
- Ensure the sustainability of open-source statistical software
- Receive community feedback and maintenance support for your features

No contribution is too small, and features developed for specific use cases often have wider applicability than anticipated.

---

## Code of Conduct

This project is committed to providing a welcoming, harassment-free experience for everyone. Participants are expected to be respectful, inclusive, and constructive. 

---

## How to Contribute

Contributions can be made in several ways:

- **Report bugs** — Open an issue with clear reproduction steps.
- **Suggest features** — Propose statistical tools or functionality improvements.
- **Improve documentation** — Correct typos or clarify usage examples.
- **Write code** — Fix issues or add new features.
- **Translate** — Help localize MedModr for non-English users.
- **Validate methods** — Review statistical implementations against established literature.
- **Create tutorials** — Produce educational content (videos, blog posts, articles) demonstrating MedModr's functionality on platforms such as YouTube, Medium, LinkedIn, or personal academic websites. Tutorials help popularize the tool and make advanced statistical methods accessible to wider audiences.
- **Contribute back** — If your institution or organization has adopted MedModr and developed custom features, submit a pull request so others can benefit.

---

## Reporting Bugs

To report a bug (incorrect p-values, UI failures, calculation errors):

1. Search existing issues to avoid duplicates.
2. Open a new issue with the label `bug`.
3. Include the following information:
   - Browser version (Chrome 120, Firefox 121, etc.)
   - Steps to reproduce the issue
   - Expected result versus actual result (reference PROCESS Macro where applicable)
   - Screenshot or console error message if applicable

**Example:**

```markdown
**Bug:** Mean centering produces incorrect interaction term coefficients.
**Browser:** Firefox 121 on macOS
**Steps:**
1. Upload dataset with variables X, M, Y.
2. Run moderation analysis with mean centering enabled.
3. Compare interaction term coefficient against manually centered results.
**Expected:** Interaction coefficient should match manual mean centering (X - mean(X)) * (M - mean(M)) and align with PROCESS Macro output.
**Actual:** Interaction coefficient differs, suggesting centering is applied incorrectly or post-centering multiplication is flawed.
