<div align="center">

# Bunny.dev

**Developer portfolio of Shiva Dumpeti (Bunny)**
Full-stack and AI developer · B.Tech CSE (AI & ML) · Hyderabad, India

[Live site](https://dumpeti-shiva.github.io/portfolio/) · [GitHub](https://github.com/dumpeti-shiva) · [LinkedIn](https://www.linkedin.com/in/shiva-dumpeti-5684292bb/)

</div>

---

## About
A fast, single-page portfolio that shows who I am, what I have built and how to reach me. Built with plain HTML, CSS and JavaScript. No framework and no build step.

## Features
- Dark, monochrome design with an orange accent
- Cursor-reactive dot field in the hero (canvas)
- Scroll-driven exploded "chip" that reveals my skills layer by layer
- Projects, education and contact sections with copy-to-clipboard buttons
- Responsive from phone to desktop
- Respects `prefers-reduced-motion`

## Projects featured
| Project | Stack | Link |
|---|---|---|
| Farmer Assistance App | React, Flask, SQLite, Random Forest, CNN, Gemini | Not public yet |
| AI Crime Detection System | Python, Django, PyTorch, REST API | [Repo](https://github.com/dumpeti-shiva/AI-Crime-Detection-System-Python-Django-PyTorch-) |
| Query Lens AI | TypeScript, SQL, AI | [Repo](https://github.com/dumpeti-shiva/Query-lens-ai) |

## Tech used
HTML5 · CSS3 (grid, flexbox, 3D transforms) · Vanilla JavaScript · Canvas API · Google Fonts (Bricolage Grotesque, DM Sans, JetBrains Mono)

## Project structure
```
portfolio/
├── index.html    # the whole site (markup, styles, scripts)
├── README.md
├── LICENSE
└── .gitignore
```

## Run locally
```bash
git clone https://github.com/dumpeti-shiva/portfolio.git
cd portfolio
# open index.html in your browser, or serve it:
python -m http.server 8000
```

## Deploy on GitHub Pages
1. Push the repo to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. Your site goes live at `https://dumpeti-shiva.github.io/portfolio/`.

## Customize
- Colors: edit the `:root` variables at the top of `index.html` (`--neon` is the orange accent).
- Projects: edit the cards inside `<section id="projects">`.
- Contact details: edit the rows inside `<section id="contact">`.

## Contact
- Email: shivadumpti@gmail.com
- GitHub: [dumpeti-shiva](https://github.com/dumpeti-shiva)
- LinkedIn: [shiva-dumpeti](https://www.linkedin.com/in/shiva-dumpeti-5684292bb/)

## License
Released under the [MIT License](LICENSE).
