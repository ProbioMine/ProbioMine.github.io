# ProbioMine.github.io

Official website of **ProbioMine Biotechnology Co., Ltd. (金华宝脉生物科技有限公司)**.

**Live site: https://probiomine.github.io/**

ProbioMine is an innovation-driven biotech company focused on low-biomass
microbiome profiling and functional probiotic discovery. Built on proprietary
**2bRAD-M** reduced-metagenomics sequencing, **Raman-activated single-cell
sorting (FlowRACS)** coupled with culturomics, **MiX** AI-driven chronic-disease
early-warning models, and an **AI-agent automated analysis platform**, the
company delivers precision microbial analysis for challenging clinical samples
(oral, tumor, FFPE, blood, skin, etc.) and mines functional strains for
personalized probiotics.

公司基于先进宏基因组和单细胞功能分选技术，依托自主研发的 2bRAD-M 简化
宏基因组测序技术，针对低生物量临床样品提供高精度微生物组分析服务，
并开展功能益生菌挖掘与个性化益生菌产品开发。

## Site structure

The site is **bilingual**: English pages live at the repository root, the
Chinese version lives under `zh/`. Both versions share `assets/` (CSS, JS,
images) and cross-link via the 中/EN switch in the navbar.

| English | 中文 | Content / 内容 |
| --- | --- | --- |
| `index.html` | `zh/index.html` | Home — hero, key metrics, platform overview, pipelines, partners / 首页 |
| `about.html` | `zh/about.html` | Company story, vision & mission, founding team, ecosystem / 关于我们 |
| `technology.html` | `zh/technology.html` | Core platforms: 2bRAD-M, single-cell RACS, MiX models, AI-agent platform / 核心技术 |
| `solutions.html` | `zh/solutions.html` | Research services, personalized probiotic plan, product pipelines / 解决方案 |
| `resources.html` | `zh/resources.html` | Databases, scientific validation, collaboration network / 资源 |
| `contact.html` | `zh/contact.html` | Address, email, collaboration inquiries / 联系我们 |

```
├── index.html / about.html / technology.html / solutions.html / resources.html / contact.html
├── zh/                     # 中文版页面（与根目录页面一一对应）
├── assets/
│   ├── css/style.css       # 全站样式（中英共用）
│   ├── js/main.js          # 导航交互、页脚年份
│   └── img/                # logo、团队照片、合作伙伴 logo
└── package.json            # 仅用于本地预览（vite dev server）
```

## Tech stack

- Plain HTML / CSS / JavaScript — **no build step required**
- Typography: Inter, Cormorant Garamond, JetBrains Mono, Noto Sans/Serif SC
- Local preview via [Vite](https://vitejs.dev/) (dev only, not needed for deployment)

## Local preview

```bash
# option 1: any static file server
python3 -m http.server 7100

# option 2: vite dev server
npm install
npm run dev
```

Then open `http://localhost:7100/`.

## Deployment

The site is hosted with **GitHub Pages** directly from the `main` branch of
this repository (`ProbioMine/ProbioMine.github.io`) — pushing to `main`
automatically redeploys within about a minute.

To update the site:

```bash
git add -A
git commit -m "Describe the change"
git push origin main
```

## Contact

- Website: https://probiomine.github.io/
- Email: contact@probiomine.com
- Address: Pan'an Precision Medicine Industrial Park, Jinhua, Zhejiang, China
  （浙江省金华市磐安县精准医学产业园区）

---

© 2026 ProbioMine Biotechnology Co., Ltd. (金华宝脉生物科技有限公司)
