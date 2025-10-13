# HOPE PPT

A lightweight academic prototyping tool that helps students quickly scaffold presentations, reports, assignments, and projects. Built as a minimal, open-source starting point for automated academic content generation.

Part of the **HOPE Initiative**—supporting grassroots tech education in Kerala.

---

## 🎯 What It Does (Current MVP)

From a single interface, users can initiate the creation of:

- **Interactive 3D Presentations**  
  (with animations & multimedia)
- **Printable PDF Reports**  
  (professionally formatted)
- **Structured Assignments**  
  (with questions, instructions, grading criteria)
- **Complete Projects**  
  (including source code, documentation, workflow diagrams)

> ⚠️ **Note**: This is a **frontend prototype**. Generation logic (PDF export, code scaffolding, etc.) is intended for future implementation or integration via backend services.

---

## 🔗 Live Demo

👉 [https://hope-ppt.vercel.app](https://hope-ppt.vercel.app)

---

## 📁 Current Implementation

- Single static `index.html` (hosted on Vercel)
- No framework (plain HTML/CSS/JS for now)
- Designed for **extensibility**—ready to plug into templating engines, report generators (e.g., Puppeteer), or LLM-powered content pipelines

---

## 🚀 How to Extend

1. Clone the repo
2. Add dynamic handlers (e.g., `/api/generate-report`)
3. Integrate with:
   - **Puppeteer** for PDF reports
   - **Three.js** or **Spline** for 3D slides
   - **GitHub Copilot API** or local templates for project scaffolding
4. Deploy back to Vercel

---

## 🌱 Why This Exists

Many students waste hours on formatting instead of learning.  
HOPE PPT starts as a **minimal interface**—but aims to become a **force multiplier** for:
- IoT camp mentors
- College project guides
- Self-taught developers in resource-limited settings

Already used in early testing during **HOPE Summer IoT Camps**.

---

## 📜 License

MIT — see [LICENSE](./LICENSE)

---

## 👤 Built By

**Justin Alexia Andrew** (Harinandan K.)  
Kadalundi, Kozhikode | IES College of Engineering  
[harinandhan972@gmail.com](mailto:harinandhan972@gmail.com)

> “Tech + coordination = real impact.”
