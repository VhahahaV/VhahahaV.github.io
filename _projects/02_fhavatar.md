---
layout: page
title: FHAvatar
permalink: /projects/fhavatar/
description: Fast, high-fidelity reconstruction of composable face-and-hair 3D head avatars from few casual captures.
img: /assets/img/publication_preview/fhavatar-teaser.png
importance: 2
featured: false
status: CVPR 2026 · Co-author
category: research
related_publications: true
---

<div class="project-facts" aria-label="Publication details">
  <span>CVPR 2026</span>
  <strong>Co-author</strong>
  <span>Animatable 3D Avatars</span>
</div>

<figure class="project-showcase project-showcase--paper">
  <img src="{{ '/assets/img/publication_preview/fhavatar-teaser.png' | relative_url }}" alt="FHAvatar reconstruction, animation, and editing results" width="1237" height="245" loading="eager">
</figure>

<div class="project-lead">
  <p><strong>Takeaway.</strong> A fast few-shot 3D Gaussian avatar framework with composable face and hair representations, supporting real-time animation and editing.</p>
</div>

### Problem

High-fidelity animatable head avatars typically require carefully captured multi-view data or lengthy per-subject optimization, limiting practical personalization from casual observations.

### Method

FHAvatar reconstructs high-fidelity, animatable 3D head avatars from only a few casual captures. It models face and hair as composable components so each region can use a representation suited to its geometry and appearance. An aggregated transformer backbone learns cross-view priors from multi-view data to support fast personalization for new identities.

### Contributions

- **Composable representation:** face and hair are modeled as distinct but coordinated components.
- **Fast personalization:** a learned cross-view prior supports reconstruction from sparse casual observations.
- **Interactive use:** the avatar supports real-time animation, hairstyle transfer, and stylized editing.

<div class="project-links">
  <a class="btn btn-sm z-depth-0" href="https://arxiv.org/abs/2603.23345" target="_blank" rel="noopener">Paper on arXiv</a>
</div>

### Citation

```bibtex
@inproceedings{sun2026fhavatar,
  title     = {FHAvatar: Fast and High-Fidelity Reconstruction of Face-and-Hair Composable 3D Head Avatar from Few Casual Captures},
  author    = {Sun, Yujie and Cai, Zhuoqiang and Niu, Chaoyue and Chen, Jianchuan and Chen, Zhiwen and Lv, Chengfei and Wu, Fan},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year      = {2026},
  arxiv     = {2603.23345}
}
```
