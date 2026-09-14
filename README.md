<div align="center">

# ✦ Sabiha Ferdousi — Digital Portfolio ✦

### *Still learning. Always building.*

A single-file, hand-crafted personal portfolio — no framework, no build step, just deliberate design and clean HTML/CSS.

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-Custom_Design_System-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile_First-2E8B57?style=for-the-badge)](#)
[![Print Ready](https://img.shields.io/badge/Print--to--PDF-Resume_Mode-C89C50?style=for-the-badge)](#)

**[✨ View Live Site](https://github.com/theSemanticlink/My-Portfolio)**

</div>

---

## 🖋️ About This Site

This isn't a template. It's a personal portfolio built entirely from scratch — one HTML file, one `<style>` block, zero external libraries or frameworks. Every color, every spacing decision, and every section was designed intentionally around a single idea: **a warm, editorial, "personal journal" feel** rather than a generic corporate portfolio look.

It belongs to **Sabiha Ferdousi** (Saba) — a Computer Science & Engineering student with a growing focus on AI, Machine Learning, and Generative AI, currently building chatbot projects and full-stack applications.

---

## 🎨 Design Language

| Element | Choice | Why |
|---|---|---|
| **Palette** | Cream & paper background, rust, teal, and gold accents | Warm and archival — feels like a well-kept notebook, not a SaaS landing page |
| **Typography** | Georgia serif throughout, with an Arial micro-label system for kickers/nav | Editorial gravitas for headings, functional clarity for UI labels |
| **Texture** | Subtle dot-grain overlay (`radial-gradient`, 5% opacity) | Gives the flat cream background quiet depth without distracting |
| **Motion** | Smooth-scroll navigation, tilted "photo frame" portrait | One deliberate, memorable visual moment instead of scattering animation everywhere |
| **Print mode** | A dedicated `@media print` stylesheet hides the nav, form, marquee, and footer | **Ctrl+P turns the site into a clean, ready-to-print resume** — this is not an accident, it's a feature |

---

## 🗂️ Sections

```
Hero (#top)      → Name, role kicker, portrait, primary CTA
Work (#work)     → 4-card grid: AI/ML/GenAI, chatbots, full-stack site, Python foundations
Story (#story)   → Bio, hobbies, quick facts — dark-mode contrast section
Resumé (#resume) → Skills list, academic results table, career timeline (incl. Excelerate internship)
Contact (#contact) → Direct email + a styled inquiry form
```

---

## 🛠️ Tech Stack

- **Pure HTML5** — semantic sectioning, no `<div>` soup
- **Pure CSS3** — custom properties (`:root` variables) for the entire color system, CSS Grid for every layout, no preprocessor
- **Zero JavaScript, zero dependencies** — no CDN calls, no build tooling; it opens and runs identically anywhere
- **Fully responsive** — a single `@media (max-width: 720px)` breakpoint collapses every grid to a clean single column

---

## 🚀 Running It Locally

No installation needed — it's one file.

```bash
cd My-Portfolio
```

Then just open `index.html` in any browser — double-click it, or for live-reload while editing, use VS Code's **Live Server** extension.

> 📌 **Make sure `profile-picture-super-resolution.jpg` is in the same folder as `index.html`** — the hero portrait references it directly.

---

## 🌐 Publishing It (GitHub Pages)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Branch**, select `main` / root, and save
4. Your live link appears in a minute or two:
   ```
   https://theSemanticlink.github.io/My-Portfolio.git
   ```

---

## ✉️ Get In Touch

- 📧 [sabihasaba2123@gmail.com](mailto:sabihasaba2123@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/sabiha-ferdousisaba201891328)
- 💻 [GitHub](https://github.com/theSemanticlink)
- ✕ [Twitter / X](https://x.com/SabihaC243462_)

---

## 📝 Note on the Contact Form

The inquiry form is fully styled and functional in appearance, but currently has no backend wired to it (no `action`/`method`, no JS handler) — it's a visual/UX placeholder for now. To make it actually send messages, the simplest next step is hooking it up to a form-relay service like **Formspree** or **Web3Forms** with a single `action` attribute — no backend server required.

---

<div align="center">

*Designed with intention — one file, no shortcuts.*

</div>
