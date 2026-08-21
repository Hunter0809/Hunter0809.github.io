---
title: "DouYun (豆韵)"
date: 2026-07-01
meta: "Independent creator and full-stack developer · National First Prize, China Robot and Artificial Intelligence Competition"
summary: "A controllable artificial-intelligence workflow that turns traditional Chinese cultural themes and images into feasible fuse-bead patterns."
links:
  - label: Live Site
    url: "https://douyun-huazhang-3g29.vercel.app/"
  - label: Source Code
    url: "https://github.com/Hunter0809/DouYun"
---
DouYun is an artificial-intelligence-assisted creative system that converts traditional Chinese cultural themes and user-supplied images into feasible fuse-bead designs. I independently designed and implemented the complete application so that a user can begin with a cultural theme, a local image, or a community work and move from creative intent to a manufacturable pattern rather than stopping at a generated illustration.

The workflow is organized as a controllable four-step pipeline: cultural-theme selection or image upload; subject identification with editable subject regions and colour composition; traditional-culture re-creation with user-editable generation prompts; and pattern production with an exportable grid, palette, material list, cultural explanation, and making plan. I implemented pixel sampling, palette mapping, grid rendering, product-form templates, and image-to-pattern conversion logic required to make generated content usable in an actual handcraft process.

I built the system with Next.js App Router, TypeScript, server-side artificial-intelligence routes, browser-side image processing, and reusable data modules for cultural themes, product templates, aspect ratios, and colour mappings. Lightweight user settings and artificial-intelligence configuration are stored locally, while IndexedDB preserves project history and a community interface supports publication, browsing, search, and importing works for further editing.

DouYun received the **National First Prize, China Robot and Artificial Intelligence Competition** (中国机器人及人工智能大赛).
