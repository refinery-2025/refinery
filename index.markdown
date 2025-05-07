---
layout: default
---

<!-- [PDF](assets/refinery_paper.pdf) | [Code (Coming Soon!)](https://refinery-2025.github.io/refinery/) | [Video](assets/refinery_5min.mov) -->

<img src="assets/teaser.pdf" alt="Teaser Image" width="100%" style="margin-bottom:2em"/>

---

## Abstract

Simulation-based learning has enabled policies for precise, contact-rich tasks (e.g., robotic assembly) to reach high success rates (∼80%) under high levels of observation noise and control error; although such performance may be sufficient for research applications, it falls short of industry standards and makes policy chaining exceptionally brittle. A key limitation is the high variance in individual policy performance across diverse initial conditions. We introduce **Refinery**, a simple yet effective framework that bridges this performance gap, robustifying policy performance across initial conditions. We propose Bayesian Optimization-guided fine-tuning to improve individual policies, and Gaussian Mixture Model-based sampling during deployment to select initializations that maximize execution success. Using Refinery, we improve mean success rates by 10.98% over state-of-the-art methods in simulation-based learning for robotic assembly, reaching 91.51% in simulation and comparable performance in the real world. Furthermore, we demonstrate that these fine-tuned policies can be chained to accomplish long-horizon, multi-part assembly—successfully assembling up to 8 parts without requiring explicit multi-step training.

---

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1082292584?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="refinery_5min"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
