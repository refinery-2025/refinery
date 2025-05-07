---
layout: default
---

[PDF](https://openreview.net/attachment?id=zuOKFYcfUT&name=pdf) | [Code (Coming Soon!)](https://refinery-2025.github.io/refinery/) 

<img src="assets/teaser.pdf" alt="Teaser Image" width="100%" style="margin-bottom:2em"/>

---

## Abstract

Simulation-based learning has enabled policies for precise, contact-rich tasks (e.g., robotic assembly) to reach high success rates (∼80%) under high levels of observation noise and control error; although such performance may be sufficient for research applications, it falls short of industry standards and makes policy chaining exceptionally brittle. A key limitation is the high variance in individual policy performance across diverse initial conditions. We introduce **Refinery**, a simple yet effective framework that bridges this performance gap, robustifying policy performance across initial conditions. We propose Bayesian Optimization-guided fine-tuning to improve individual policies, and Gaussian Mixture Model-based sampling during deployment to select initializations that maximize execution success. Using Refinery, we improve mean success rates by 10.98% over state-of-the-art methods in simulation-based learning for robotic assembly, reaching 91.51% in simulation and comparable performance in the real world. Furthermore, we demonstrate that these fine-tuned policies can be chained to accomplish long-horizon, multi-part assembly—successfully assembling up to 8 parts without requiring explicit multi-step training.

---

