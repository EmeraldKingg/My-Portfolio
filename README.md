<div align="center">

# 🏁 Emerald Edward — Portfolio

### *Lights out and away we go.*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222?style=for-the-badge&logo=github)](#)
[![Status](https://img.shields.io/badge/STATUS-LIGHTS%20OUT-E6394A?style=for-the-badge)](#)

*One page. Zero frameworks. Full send.*

</div>

---

## 🏎️ What's in the garage

This is my personal portfolio, built to feel less like a template and more like a pit wall: telemetry-style readouts, a scroll tracker borrowed from F1 timing screens, and a little car that actually races across the bottom of the page as you scroll. Because why should race engineers have all the fun.

**Live site:** _[add your deployed URL here]_
**CV download:** `Emerald_Edward_CV.pdf` (bundled in this repo — keep it next to `index.html`!)

---

## 🚦 Features

| System | What it does |
|---|---|
| 🟢 **Sector rail** | A sticky progress bar under the nav that fills — teal for done, red-glow for the current section, like an F1 timing screen tracking your scroll |
| 🏎️ **Scroll-driven race car** | A hand-drawn car (pure SVG, no images) drives left → right across a kerb-striped strip as you scroll the whole page |
| 🗺️ **Spielberg circuit graphic** | A stylized Austria track sketch in the hero, with three colored dots lapping it at different speeds, a nod to the Master's plans on the horizon |
| 📇 **CV section** | Experience + education timeline, skills/languages/certs readouts, and a one-click PDF download |
| 🗂️ **Project grid** | Pulled straight from my GitHub repos — status pills, language tags, live/code links |
| ♿ **Reduced motion respected** | Every animation backs off if the visitor has `prefers-reduced-motion` set |

---

## 🛠️ Tech stack

No build step. No dependencies. No `node_modules` the size of a small moon.

- **HTML5** — semantic structure
- **CSS3** — custom properties, `offset-path` motion, `IntersectionObserver`-driven reveals
- **Vanilla JavaScript** — scroll physics for the sector rail and race car
- **Google Fonts** — Space Grotesk (display), Inter (body), JetBrains Mono (telemetry/data)

---

## 🏗️ Track layout (project structure)

```
.
├── index.html              → the whole site (single file, HTML+CSS+JS)
├── Emerald_Edward_CV.pdf   → downloadable CV
└── README.md               → you are here
```

---

## 🔧 Getting your engine started

Clone it, no pit stop required:

```bash
git clone https://github.com/EmeraldKingg/Portfolio.git
cd Portfolio
```

Then just open `index.html` in a browser. That's the whole install process. Seriously.

### Deploying

Any static host works — pick your team:

- **GitHub Pages** → Settings → Pages → deploy from `main`
- **Vercel** → `vercel deploy`
- **Netlify** → drag the folder into the dashboard

Just make sure `index.html` and `Emerald_Edward_CV.pdf` stay in the same directory — the download button links to the PDF by filename.

---

## 📡 Get in touch

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emeraldedward)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EmeraldKingg)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emeraldedwards01@gmail.com)

</div>

---

<div align="center">

*Built with HTML, CSS, and a slightly unreasonable amount of F1 enthusiasm.* 🏁

</div>
