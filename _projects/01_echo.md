---
layout: page
title: ECHO
description: Dyadic 3D facial motion generation with asymmetric deterministic articulation and stochastic reaction.
img: /assets/img/publication_preview/echo-teaser.png
importance: 1
featured: true
status: Published · ACM MM 2026
category: digital humans
related_publications: true
---

<div class="project-lead">
  <p><strong>ECHO</strong> addresses dyadic 3D facial motion generation under a strict dual-stream audio-only setting. The key observation is that speaking and listening are not symmetric: speech articulation is relatively constrained by phonetic content, while listener reactions remain inherently one-to-many.</p>
</div>

The method therefore decomposes motion into a **deterministic anchor** and a **stochastic residual**. The anchor preserves stable speech-related structure; the residual captures diverse interaction dynamics. A training-only Motion Memory regularizer supplies local motion priors for weakly conditioned listening windows, while semantic-group scaling controls residual injection across facial regions.

This design produces a practical formulation for conversational digital humans without requiring visual input at inference time.

### Highlights

- **Asymmetric modeling:** deterministic articulation for speaking and stochastic interaction dynamics for listening.
- **Training-only motion prior:** Motion Memory strengthens local structure without becoming an inference dependency.
- **Audio-only deployment:** the model generates conversational facial motion from dual-stream audio at inference time.

<div class="project-links">
  <a class="btn btn-sm z-depth-0" href="https://doi.org/10.1145/3767308.3834964" target="_blank" rel="noopener">Paper / DOI</a>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/echo-acmmm2026.pdf' | relative_url }}" target="_blank">PDF</a>
</div>
