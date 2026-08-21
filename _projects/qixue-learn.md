---
title: "Qixue Learn (启学智伴)"
date: 2026-06-01
cover: "/assets/images/projects/qixue-learn-homepage.png"
meta: "Independent creator and full-stack developer · National final round, China Software Cup · Award results pending"
summary: "A multi-agent personalized-learning system that connects learner profiling, mistakes, planning, resources, and evaluation into a continuous loop."
links:
  - label: Live Site
    url: "https://qixue-learn.vercel.app/"
  - label: Source Code
    url: "https://github.com/Hunter0809/qixue-learn"
---
Qixue Learn is a multi-agent personalized learning system for everyday student learning. I independently designed it around an “observe, diagnose, plan, execute, feedback, and optimize” loop: learning goals, task completion, weak knowledge points, mistakes, assessment outcomes, and resource-use behaviour are accumulated into a dynamic learner profile that informs the next recommendation, plan, and report.

The product connects intelligent question answering, photo-based problem search, homework and composition feedback, speaking practice, translation, document scanning, mistake analysis, staged quizzes, review plans, learning resources, and parent-facing reports. Its central workflows turn a submitted question or mistake into structured analysis, targeted explanation and practice; transform current goals, time availability, and mastery estimates into executable staged tasks; and feed outcomes back into the learner profile rather than treating each interaction as isolated.

I implemented the full-stack architecture with Next.js App Router, React, TypeScript, and server-side application programming interfaces. A multi-agent orchestration layer separates profile analysis, task understanding, resource generation, planning, and effectiveness evaluation; schema validation constrains generated structured data before it reaches the learning workflow. The system combines client state and data fetching with persistent learning records, supports local and PostgreSQL-compatible storage, and uses optical character recognition, mathematical formula rendering, data visualization, and automated route, interface, and interaction tests.

Qixue Learn has advanced to the national final round of the China Software Cup (中国软件杯); award results are pending.
