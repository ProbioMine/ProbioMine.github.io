# ProbioMine.github.io

Official website of **ProbioMine Biotechnology Co., Ltd. (金华宝脉生物科技有限公司)** —
precision microbiome analytics and functional probiotic discovery, powered by
2bRAD-M reduced metagenomics, Raman-activated single-cell sorting (RACS),
and AI-agent-driven analysis.

Visual design follows the style of [HuangShiLab.github.io](https://huangshilab.github.io/):
deep navy background, teal accent, Inter / Cormorant Garamond / JetBrains Mono typography.

## Pages

English pages live at the site root; the Chinese version lives under `zh/`.
Both versions share `assets/` and cross-link via the 中/EN switch in the navbar.

| English | 中文 | Content |
| --- | --- | --- |
| `index.html` | `zh/index.html` | Home — hero, key metrics, platform overview, pipelines, partners |
| `about.html` | `zh/about.html` | Company story, vision & mission, founding team, ecosystem |
| `technology.html` | `zh/technology.html` | Core platforms: 2bRAD-M, single-cell RACS + culturomics, MiX models, AI-agent platform |
| `solutions.html` | `zh/solutions.html` | Research services, personalized probiotic plan, product pipelines, roadmap |
| `resources.html` | `zh/resources.html` | Databases & algorithms, scientific validation, collaboration network, links |
| `contact.html` | `zh/contact.html` | Address, email, collaboration inquiries |

## Local preview

Any static file server works, e.g.:

```bash
python3 -m http.server 7100
# open http://localhost:7100/
```

## Deployment (GitHub Pages)

1. Create a repository named `<org-or-user>.github.io` (e.g. `ProbioMine.github.io`)
   under the intended GitHub account/organization.
2. Push this directory to the repository root (`main` branch):

   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin git@github.com:<account>/ProbioMine.github.io.git
   git push -u origin main
   ```

3. In the repository settings, enable **Pages → Deploy from branch → main / (root)**.
4. The site will be live at `https://<account>.github.io/`.

No build step is required — the site is plain HTML/CSS/JS.
