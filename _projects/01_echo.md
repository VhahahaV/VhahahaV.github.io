---
layout: page
title: ECHO
permalink: /projects/echo/
description: Dyadic 3D facial motion generation with asymmetric deterministic articulation and stochastic reaction.
img: /assets/img/publication_preview/echo-teaser.png
importance: 1
featured: false
status: ACM MM 2026 · First Author
category: research
related_publications: true
---

<div class="project-facts" aria-label="Publication details">
  <span>ACM Multimedia 2026</span>
  <strong>First Author</strong>
  <span>Conversational Facial Motion</span>
</div>

<figure class="project-showcase project-showcase--paper">
  <img src="{{ '/assets/img/publication_preview/echo-teaser.png' | relative_url }}" alt="ECHO method and conversational facial-motion results" width="1100" height="429" loading="eager">
</figure>

<div class="project-lead">
  <p><strong>Takeaway.</strong> A structured anchor–residual formulation separates speech-constrained articulation from one-to-many listener reactions under dual-stream audio-only input.</p>
</div>

### Problem

Dyadic 3D facial motion generation must model two asymmetric behaviors. Speech articulation is relatively constrained by phonetic content, while listener reactions remain inherently diverse and one-to-many.

### Method

ECHO decomposes facial motion into a **deterministic anchor** and a **stochastic residual**. The anchor preserves stable speech-related structure; the residual captures diverse interaction dynamics. A training-only Motion Memory regularizer supplies local motion priors for weakly conditioned listening windows, while semantic-group scaling controls residual injection across facial regions.

### Contributions

- **Asymmetric modeling:** deterministic articulation for speaking and stochastic interaction dynamics for listening.
- **Training-only motion prior:** Motion Memory strengthens local structure without becoming an inference dependency.
- **Audio-only deployment:** conversational facial motion is generated from dual-stream audio at inference time.

<div class="project-links">
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/echo-acmmm2026.pdf' | relative_url }}" target="_blank">Paper</a>
  <a class="btn btn-sm z-depth-0" href="https://doi.org/10.1145/3767308.3834964" target="_blank" rel="noopener">DOI</a>
</div>

### Citation

```bibtex
@inproceedings{cai2026echo,
  title     = {ECHO: Dyadic 3D Facial Motion Generation with Asymmetric Deterministic Articulation and Stochastic Reaction},
  author    = {Cai, Zhuoqiang and Sun, Yujie and Niu, Chaoyue and Yu, Hongyun and Chen, Zhiwen and Lv, Chengfei and Wu, Fan},
  booktitle = {Proceedings of the 34th ACM International Conference on Multimedia},
  year      = {2026},
  doi       = {10.1145/3767308.3834964}
}
```
