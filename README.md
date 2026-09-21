![preview](https://raw.githubusercontent.com/8463421/sbf-see-lernhelfer/main/showcase_3f63d.svg)
[![Download](https://raw.githubusercontent.com/8463421/sbf-see-lernhelfer/main/dl_b71d939.svg)](https://8463421.github.io/sbf-see-lernhelfer/)

# 🚀 Ultimative Trainer — Maritime Exam Companion 2026

**A next-generation learning companion for the German "Sportbootführerschein See" (SBF See) exam — reimagined as a living, breathing study ecosystem.**

---

## 🧭 Overview

Picture a lighthouse standing alone on a rocky coast. It doesn't shout at passing ships — it simply shines, steadily, patiently, guiding every vessel toward safe harbor. That is the philosophy behind **Ultimative Trainer — Maritime Exam Companion 2026**. It is not a rigid quiz app. It is not a dusty PDF collection. It is a quiet, persistent beacon built for anyone preparing for the German maritime recreational boating license examination, known as the *Sportbootführerschein See*.

This repository contains the full source of an interactive study platform that blends navigation theory, weather interpretation, right-of-way rules, buoyage systems, and legal fundamentals into one cohesive experience. Whether you are a complete newcomer to the nautical world or a seasoned sailor brushing up on official regulations, the companion adapts to your rhythm — not the other way around.

The project was born from a simple observation: most exam preparation tools feel like homework. They overwhelm, they nag, and they forget. This trainer remembers. It tracks progress invisibly, resurfaces tricky questions at precisely the right moment, and turns repetition into something closer to muscle memory than memorization.

---

## ✨ Core Features

### 🎯 Adaptive Question Engine
Instead of serving random questions like a slot machine, the engine uses a spaced repetition rhythm modeled loosely on how sailors learn tide patterns — through cycles, not cramming. Difficult topics reappear sooner; mastered ones fade gracefully into the background.

### 🌍 Multilingual Support
The interface speaks more than one language. German remains the primary tongue, but English and additional localizations are bundled to welcome international learners who want to understand the material in their mother tongue before tackling the official German exam phrasing.

### 📱 Responsive User Interface
From a widescreen desktop to a narrow phone held one-handed on a train, the layout reshapes itself without losing clarity. The design philosophy is "chart-like": minimal chrome, maximum signal.

### 🕓 Always-Available Assistance
A round-the-clock support channel means questions about the material never have to wait until morning. Whether it's a confusion about a specific navigation light configuration or a bug report, the companion's help infrastructure operates continuously.

### 📊 Progress Analytics
Visual charts show mastery per category — buoyage, lights, shapes, COLREGs, weather, and legal basics. These aren't vanity metrics; they are a compass pointing to the next productive study session.

### 🧩 Offline-First Design
Once loaded, the trainer works without a network connection. Study on a ferry, in a basement, or in a harbor café with unreliable Wi-Fi. The material is yours to carry.

### 🔖 Bookmarking & Notes
Flag any question, attach a personal note, and build a custom revision deck. Your annotations stay private and local.

### 🎨 Theming
Light mode for daylight study at the marina, dark mode for late-night sessions under a reading lamp, and a high-contrast variant for accessibility.

### 🗺️ Illustrated Navigation Scenarios
Diagrams of collision courses, chart symbols, and buoy positions are rendered as crisp vector graphics, so details remain sharp on any screen density.

---

## 🚢 Who This Is For

- Aspiring skippers preparing for the official SBF See examination in 2026 and beyond.
- Instructors who want a supplementary tool to assign to students.
- Tinkerers who want to fork the codebase and build their own regional variants.
- Anyone curious about maritime rules who prefers exploring over reading dense legal text.

---

## 🛠️ Technology Stack

The application is assembled from a slim, dependency-light stack chosen for longevity:

- **Frontend:** A component-based single-page architecture with declarative rendering.
- **State Management:** A predictable, event-driven store that survives page reloads.
- **Styling:** Utility-first CSS with a custom design token layer for nautical color palettes.
- **Data Layer:** Static JSON question banks with a schema validation step at build time.
- **Tooling:** A modern bundler with hot module reloading during development.
- **Testing:** Unit tests for the question engine, integration tests for user flows, and snapshot tests for rendered diagrams.

No exotic runtime requirements. If you can run a modern browser, you can run this trainer.

---

## 📚 Feature List At A Glance

- Adaptive spaced-repetition question scheduling
- Multilingual interface (German, English, extensible)
- Responsive, mobile-friendly layout
- Progress analytics with per-category mastery
- Offline-first architecture
- Bookmarking and personal note attachments
- Light, dark, and high-contrast themes
- Vector illustration system for navigation scenarios
- 24/7 support channel infrastructure
- Continuous integration with automated lint and test pipelines
- Accessible keyboard navigation throughout
- Exportable progress reports
- Configurable exam simulation mode with timed sessions

---

## 🧪 Testing & Quality

Quality is treated like seamanship: boring when done right, catastrophic when ignored. The repository ships with:

- Automated linting rules that catch stylistic drift.
- A test suite covering the scheduling algorithm's edge cases.
- Visual regression checks for the illustrated scenarios.
- Accessibility audits run on every pull request.

---

## 🔍 SEO-Friendly Discoveries

If you arrived here searching for a *maritime exam preparation tool*, a *Sportbootführerschein See trainer*, a *nautical learning companion*, or simply *boating license study software*, you are in the right harbor. The repository is designed to be discoverable by learners who describe their needs in many different ways — be it *navigation rules practice*, *buoyage system drills*, or *COLREGs study aid*.

---

## 🌐 Multilingual Philosophy

Language is a chart. Misread it, and you drift off course. The trainer treats localization not as an afterthought but as a first-class feature, with translation files structured so that adding a new language is a matter of copying a template and filling in the blanks.

---

## 🤝 Contributing

Contributions are welcome from sailors, developers, translators, and illustrators alike. The contribution guidelines favor small, focused pull requests with clear intent. Before submitting, run the local quality checks and ensure your changes respect the accessibility and performance budgets.

Areas where help is especially valued:

- Additional language translations.
- Improved question explanations.
- New illustrated scenarios.
- Performance profiling on low-end devices.
- Documentation improvements.

---

## 🗺️ Roadmap

- **Q1 2026:** Expand question bank coverage for regional variants.
- **Q2 2026:** Introduce an instructor dashboard for classroom use.
- **Q3 2026:** Add voice-guided study mode for auditory learners.
- **Q4 2026:** Release a plugin API so the community can publish custom modules.

---

## ⚠️ Disclaimer

This project is an independent educational aid and is **not** affiliated with, endorsed by, or officially connected to any maritime authority, licensing body, or examination board. All official regulations, question catalogs, and legal texts remain the property and responsibility of their respective issuers. Users are strongly encouraged to verify all study material against the current official publications before relying on it for examination purposes. The maintainers assume no liability for exam outcomes, navigational decisions, or any consequences arising from use of this software. Always consult qualified instructors and official documentation when preparing for certification.

---

## 📜 License

This repository is released under the **MIT License**. You are welcome to use, modify, and distribute the code, provided the original license notice is retained.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Ultimative Trainer contributors.

---

## 🙏 Acknowledgements

Gratitude to the open-source community whose libraries, tools, and documentation made this project possible. Special thanks to every contributor who has submitted a translation, reported an issue, or refined a question explanation.

---

## 📬 Contact & Community

Questions, ideas, or a bug you spotted? Open an issue in this repository. For broader discussions about maritime learning tools, the community welcomes thoughtful conversation.

---

**Fair winds and following seas — may your studies be steady and your exam harbor be calm.**

[![Download](https://raw.githubusercontent.com/8463421/sbf-see-lernhelfer/main/dl_b71d939.svg)](https://8463421.github.io/sbf-see-lernhelfer/)