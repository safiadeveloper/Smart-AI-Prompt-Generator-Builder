# 🎯 PromptCraft Studio — Smart AI Prompt Generator & Builder

**PromptCraft Studio** is a clean, modern, and developer-focused web application built to streamline prompt engineering workflows. It allows developers, code auditors, and AI builders to structure, customize, and optimize system prompts with real-time feedback, accurate token estimation, and instant formatting.

Designed with an executive light theme and clear element hierarchy, it eliminates messy prompt formatting and improves response quality from LLMs (such as GPT-4, Gemini, and Claude).

---

## 🌟 Key Features

- **Structured Prompt Framework:** Define Persona/Role, Core Task, Tone & Style, Output Format, and Context Constraints separately for maximum prompt precision.
- **Pre-Built Developer Templates:** Includes instant 1-click templates for:
  - 🛡️ **Code Review:** Bug identification & refactoring.
  - 🐛 **Bug Debugger:** Root cause analysis and fixes.
  - 🔌 **API Design:** RESTful endpoint specification and JSON schema creation.
  - 🏗️ **System Architecture:** High-level infrastructure and system design blueprints.
- **Live Analytical Counters:** Real-time character count, word count, and estimated LLM token count ($1 \text{ token} \approx 4 \text{ chars}$).
- **Instant AI Enhancer:** Smart auto-enrichment button that structures and refines raw text into actionable instructions.
- **Dark Terminal Preview Box:** High-contrast output pane that displays the final formatted prompt ready for copying.
- **Zero Configuration:** Single-file architecture using modern Tailwind CSS CDN and Vanilla JS—requires no server, build tools, or `node_modules`.

---

## 🛠️ Tech Stack & Dependencies

- **Frontend Core:** HTML5, Modern Vanilla JavaScript (ES6+)
- **Styling & UI:** [Tailwind CSS CDN](https://tailwindcss.com/)
- **Typography:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Google Fonts)
- **Icons:** [FontAwesome 6.4](https://fontawesome.com/)

---

## 📁 Repository Architecture

```text
PromptCraft-Studio/
├── index.html       # Single-page web application (UI + Logic)
├── README.md        # Comprehensive project documentation
└── LICENSE          # Open-source license (MIT)
