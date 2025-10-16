# Restaurant-design-project
# 📦 CS120 Restaurant Project — GitHub Documentation Pack

Below are ready‑to‑copy docs for this repository. Replace bracketed placeholders like `<Your Name>` and tweak any project‑specific details.

## 📄 README.md ()
🍽️ CS 120 — Restaurant Design Project

A simple, accessible single‑page web app for ordering and picking up meals.

## ✨ Features
- Responsive layout (mobile → desktop)
- Order & pickup flow (`order_pickup.html`)
- Accessible forms with labels & keyboard navigation
- Lightweight, no framework required (HTML/CSS/JS)
- Deployed on GitHub Pages

## 🚀 Live Demo
- **GitHub Pages:** https://<your-username>.github.io/<repo-name>/

## 🏗️ Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JS, Flask
- **Tooling (optional):** VS Code + Live Server, Prettier

## 📁 Project Structure

CS-120-Restaurant-design-project/
├─ index.html
├─ order_pickup.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  ├─ js/
│  │  └─ main.js
│  └─ images/
│     └─ logo.png
├─ docs/
│  └─ images/
│     └─ banner.png
├─ README.md
├─ CONTRIBUTING.md
├─ CODE_OF_CONDUCT.md
└─ LICENSE

````

## 🧑‍💻 Getting Started

### 1) Clone
```bash
git clone https://github.com/Space-Paragon1/CS-120-Restaurant-design-project.git
cd CS-120-Restaurant-design-project

### 2) Open locally

* **Option A (quick):** double‑click `index.html` or `order_pickup.html`.
* **Option B (VS Code):** install *Live Server* → right‑click `index.html` → *Open with Live Server*.
* **Option C (Python server):**

```bash
python -m http.server 5500
# open http://localhost:5500 in your browser
```

## 🕹️ Usage

1. Navigate to the **Order & Pickup** page (`order_pickup.html`).
2. Choose menu items, fill required info, and submit.
3. Review confirmation details and pickup instructions.

> **Accessibility tip:** All inputs have labels and proper `aria-` attributes; you can tab through the form.

## 📸 Screenshots

Add screenshots or GIFs to `docs/images` and reference them here.

| Home                          | Order & Pickup                  |
| ----------------------------- | ------------------------------- |
| ![Home](docs/images/home.png) | ![Order](docs/images/order.png) |


## ✅ Testing (Manual)

* [ ] Form validation blocks empty required fields
* [ ] Invalid email/phone shows helpful error
* [ ] Mobile layout works ≥320px width
* [ ] Links/buttons reachable via **Tab** and **Enter/Space**

## 🌐 Deployment — GitHub Pages

1. Push to `main`.
2. In **Settings → Pages**, set *Source* to `Deploy from a branch`, pick `main`, and `/ (root)`.
3. Wait for the green check → use the **Live Demo** link above.

## 🧭 Roadmap

* [ ] Add menu filtering/search
* [ ] Persist cart to `localStorage`
* [ ] Add unit tests with Vitest/Jest (optional)

## 🐛 Known Issues

* Describe any current bugs/limitations.

## ❓ FAQ

**Q: Why no framework?**
A: The goal is fundamentals (HTML/CSS/JS) to meet CS 120 requirements.

## 🙌 Contributors

* <Alex Chidera Umeasalugo> — @Space-Paragon1
* <Emmanuel Akwasi Opoku> — @emmanuelakwasi
* <Animesh Niraula> — @-------
* <Patrick Selby> — @pat-selby

## 📝 License
This project is licensed under the MIT License — see [`LICENSE`](LICENSE).

## 🤝 CONTRIBUTING.md

```markdown
# Contributing

Thanks for helping improve the CS 120 Restaurant project! 🎉

## Branching
- `main`: production‑ready
- feature branches: `feat/<short-name>` (e.g., `feat/pickup-form`)
- bugfix branches: `fix/<short-name>`

## Commit Messages (Conventional Commits)
- `feat:` new feature
- `fix:` bug fix
- `docs:` documentation only
- `style:` formatting, no code change
- `refactor:`, `test:`, `chore:` as needed

**Examples**
````

feat(order): add phone validation to pickup form
fix(ui): correct button focus outline in Safari
docs(readme): add deployment steps

```

## Code Style
- HTML: semantic tags (`<main>`, `<section>`, `<nav>`, etc.)
- CSS: BEM-ish class names; keep selectors shallow
- JS: no global leaks; prefer functions/modules
- Run Prettier before committing

## Accessibility (must-pass)
- All interactive elements reachable with keyboard
- Visible focus styles
- Labels for every input; descriptive placeholders
- ARIA only when needed (don’t duplicate semantics)

## Pull Request Checklist
- [ ] Linked issue (if any)
- [ ] Screenshots for UI changes
- [ ] Passed manual tests on mobile & desktop
- [ ] No console errors

## How to Submit a PR
1. Fork the repo and create a branch
2. Commit changes with a clear message
3. Open a PR to `main`; fill the PR template
4. Request review from a teammate
```

---

## 👩‍⚖️ CODE_OF_CONDUCT.md

```markdown
# Contributor Covenant Code of Conduct

We are committed to a harassment‑free, inclusive experience for everyone. By participating, you agree to uphold this Code of Conduct.

## Our Standards
- Be respectful and constructive
- Accept feedback gracefully
- Focus on what is best for the community

## Enforcement
Report unacceptable behavior to <maintainer-email>. The maintainers will review and act as appropriate.

This project adopts the [Contributor Covenant](https://www.contributor-covenant.org/).
```

---

## 🐞 .github/ISSUE_TEMPLATE/bug_report.md

```markdown
---
name: Bug report
about: Create a report to help us improve
labels: bug
---

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. See error

**Expected behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**Environment**
- Browser: [e.g. Chrome 141]
- OS: [e.g. Windows 10]

**Additional context**
Add any other context about the problem here.
```

---

## ➕ .github/PULL_REQUEST_TEMPLATE.md

```markdown
## Summary
Explain the change in 1–2 sentences.

## Details
- What problem does this solve?
- Screenshots (if UI)

## Checklist
- [ ] Tests/manual checks added
- [ ] No new console errors
- [ ] Accessibility checked (keyboard + labels)
- [ ] Docs updated (README/Comments)
```

---

## 📜 LICENSE (MIT)

```text
MIT License

Copyright (c) 2025 <Your Name>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🧰 Optional: `.gitignore`

```gitignore
# Logs
*.log

# macOS
.DS_Store

# Node (if you later add tooling)
node_modules/
```

---

## 🔍 What makes “good documentation” on GitHub?

* **Audience‑first:** explain what it is, who it’s for, and how to run it locally.
* **Skimmable:** headings, bullet lists, and screenshots; keep paragraphs short.
* **Actionable:** copy‑paste commands; clear success criteria (checklists).
* **Maintained:** small Roadmap + Known Issues; keep demo link accurate.
* **Assessable:** show how the project meets course requirements (accessibility, responsiveness, etc.).

> Tip: If your current file lives at `C:\Users\DELL\Desktop\...\order_pickup (1).html`, rename it to `order_pickup.html` (avoid spaces/parentheses), commit it, and push to GitHub so teammates and graders can view it online.

---

## 🗺️ Submission Checklist for CS 120

* [ ] README complete with demo link & screenshots
* [ ] Pages deployed and accessible without login
* [ ] Clear instructions to run locally (no frameworks required)
* [ ] Accessibility checklist filled
* [ ] Issue/PR templates present
* [ ] LICENSE added
* [ ] Team members credited in README

---

Need me to tailor the README using your exact filenames/menus and add screenshots placeholders? Paste your repo URL and I’ll customize it in‑place.
