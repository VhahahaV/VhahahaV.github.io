---
layout: page
title: Focus Pet
description: A local-first desktop focus companion that turns attention rhythms into a responsive virtual pet.
img: /assets/img/projects/focus-pet-dashboard.png
importance: 1
featured: true
status: Open Source · Vibe Coding
category: desktop software
related_publications: false
links:
  - label: Native macOS
    url: https://github.com/VhahahaV/focus_pet
  - label: Tauri + React
    url: https://github.com/VhahahaV/focus_pet_tauri
---

<div class="project-lead">
  <p><strong>Focus Pet</strong> is a local-first desktop focus companion that observes real working rhythms and translates them into a virtual pet that responds with lightweight actions, bubbles, and timely reminders.</p>
</div>

The project began as a native macOS application built with Swift and SwiftUI. I later migrated it to a Tauri + React architecture, preserving the original focus-state model while extending the product toward a cross-platform desktop experience.

Instead of asking users to constantly start timers or maintain task forms, Focus Pet combines foreground-app context, input rhythm, idle time, and switching frequency into four understandable states: **focused**, **distracted**, **on break**, and **away**. Those states are mapped to pet intents so different pet resource packs can express the same focus semantics with their own personalities.

### Highlights

- **Local-first by design:** attention signals, timelines, and statistics remain on the user's device.
- **State before dashboards:** the product first answers “What rhythm am I in right now?” before presenting historical metrics.
- **Responsive desktop companion:** pet actions, reminders, widgets, and dashboard views share one focus-state engine.
- **Two implementations, one product:** a native Swift/macOS foundation and a cross-platform Tauri + React evolution.

<div class="project-links">
  <a class="btn btn-sm z-depth-0" href="https://github.com/VhahahaV/focus_pet" target="_blank" rel="noopener">Native macOS / Swift</a>
  <a class="btn btn-sm z-depth-0" href="https://github.com/VhahahaV/focus_pet_tauri" target="_blank" rel="noopener">Tauri + React</a>
</div>

<figure class="project-showcase">
  <img src="{{ '/assets/img/projects/focus-pet-dashboard.png' | relative_url }}" alt="Focus Pet today dashboard" loading="lazy">
</figure>
