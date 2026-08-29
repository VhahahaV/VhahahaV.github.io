---
layout: page
title: Focus Pet
permalink: /projects/focus-pet/
description: A local-first desktop focus companion that turns attention rhythms into a responsive virtual pet.
img: /assets/img/projects/focus-pet-dashboard.webp
importance: 3
featured: true
status: Public Source · Tauri · React · Rust · Swift
category: engineering
related_publications: false
links:
  - label: Primary repository
    url: https://github.com/VhahahaV/focus_pet_tauri
  - label: Original Swift prototype
    url: https://github.com/VhahahaV/focus_pet
---

<div class="project-lead">
  <p><strong>Focus Pet</strong> is a local-first desktop focus companion that observes real working rhythms and translates them into a virtual pet that responds with lightweight actions, bubbles, and timely reminders.</p>
</div>

The primary implementation uses Tauri, React, TypeScript, and Rust to support a cross-platform desktop architecture. The project began as a native Swift and SwiftUI macOS prototype, whose product model and release notes remain available as the previous implementation.

Instead of asking users to constantly start timers or maintain task forms, Focus Pet combines foreground-app context, input rhythm, idle time, and switching frequency into four understandable states: **focused**, **distracted**, **on break**, and **away**. Those states are mapped to pet intents so different pet resource packs can express the same focus semantics with their own personalities.

### Highlights

- **Local-first by design:** attention signals, timelines, and statistics remain on the user's device.
- **State before dashboards:** the product first answers “What rhythm am I in right now?” before presenting historical metrics.
- **Responsive desktop companion:** pet actions, reminders, widgets, and dashboard views share one focus-state engine.
- **Cross-platform native layer:** dedicated macOS, Windows, and Linux adapters expose one stable command surface to the React application.
- **Verification as a product feature:** Vitest, Rust tests, and Playwright cover state logic, native contracts, import validation, persistence, and core UI flows.
- **Validated pet-pack importer:** resource packs are checked for manifests, actions, frames, previews, licensing metadata, and idle-action references before installation.

<div class="project-links">
  <a class="btn btn-sm z-depth-0" href="https://github.com/VhahahaV/focus_pet_tauri" target="_blank" rel="noopener">Primary: Tauri + React + Rust</a>
  <a class="btn btn-sm z-depth-0" href="https://github.com/VhahahaV/focus_pet" target="_blank" rel="noopener">Previous: Swift + SwiftUI</a>
</div>

<figure class="project-showcase">
  <img src="{{ '/assets/img/projects/focus-pet-dashboard.webp' | relative_url }}" alt="Focus Pet today dashboard" width="1600" height="1141" loading="lazy">
</figure>
