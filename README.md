
# Muqadas Ejaz · Portfolio

My personal portfolio website. I'm an AI Engineer at ExtreemTek and a Kaggle Grandmaster, working across computer vision, deep learning, RAG, LLMs, AI agents, agentic AI and AI automation.

**Live site:** [muqadasejaz.vercel.app](https://muqadas-ejaz.vercel.app/) 

<img width="1600" height="860" alt="image" src="https://github.com/user-attachments/assets/11230fa9-f0f2-4c62-a927-2ff19e795de7" />

## What's on the site

- **Intro** with my role, areas of work and a few things I've built
- **How I work**, plus my areas of work and how I can help teams, businesses, researchers and learners
- **Experience** at ExtreemTek, DevRolin, Arch Technologies and PMAS Arid Agriculture University
- **Education:** Bachelor of Computer Science (Artificial Intelligence), Arid Agriculture University, 2021 – 2025
- **Projects:** highlighted work (AI Detector Deep Fake PRO, LinkedIn Finder, AIMetaScrubber, Plant Detection, Human Detection, GKS Scholarship Hub) and a filterable grid by category, with live demo links
- **Kaggle:** Datasets Grandmaster, ranked #5 globally, with a leaderboard screenshot
- **Skills** and **certifications** from Anthropic, Google, Simplilearn, Coursera and more
- **Contact** links

## Built with

- Plain HTML, CSS and JavaScript in a single `index.html`. No framework and no build step.
- Google Fonts: Instrument Serif, Manrope and JetBrains Mono
- Black and yellow theme with a light mode toggle
- Responsive layout for desktop, tablet and mobile
- Scroll reveal animations that respect reduced-motion settings

## Project structure

```
.
├── index.html        # the whole site: markup, styles and scripts
├── muqadas.jpg       # profile photo
├── kaggle-rank.png   # Kaggle Dataset Rankings screenshot
├── preview.jpg       # screenshot used in this README
└── README.md
```

## Run it locally

No install needed. Open `index.html` in your browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Updating content

Most content lives in plain JavaScript arrays near the bottom of `index.html`, under the comment `EDIT YOUR CONTENT HERE`:

| Array        | What it controls                                   |
|--------------|----------------------------------------------------|
| `EXPERIENCE` | Job titles, companies, dates, bullet points, tags  |
| `PROJECTS`   | Projects in the category tabs                      |
| `TOP`        | Which projects appear under "All", and their order |
| `ALL_ONLY`   | Extra projects shown only under "All"              |
| `SKILLS`     | Skill groups and tags                              |
| `CERTS`      | Certifications, issuers, dates and links           |

The intro, highlighted projects, Kaggle and education sections are written directly in the HTML.

## Deploy

The site is static, so it deploys anywhere.

**Vercel:** import this repo at [vercel.com/new](https://vercel.com/new), keep Framework Preset as **Other** and click **Deploy**. Every push to the main branch redeploys automatically.

**GitHub Pages:** go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.

## Connect

- Email: muqadasejaz3@gmail.com
- [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)
- [GitHub](https://github.com/muqadasejaz)
- [X](https://x.com/muqadasejaz_ai)
- [Instagram](https://www.instagram.com/muqadasejaz.ai/)
- [LeetCode](https://leetcode.com/u/MuqadasEjaz/)

Have a product idea you want to build with AI? Take a look at my work and get in touch.

---

© 2026 Muqadas Ejaz. Feel free to take inspiration from the design, but please don't copy the content or photos.
