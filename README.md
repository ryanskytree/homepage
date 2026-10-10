# Xuling Zhang · Personal Homepage

<p align="center">
  <img src="images/profile.png" alt="Xuling Zhang" width="150" />
</p>

<p align="center">
  <b>Algorithm Engineer @ 360 Company</b><br/>
  Multimodal LLMs · Multi-Agent Collaboration · World Models
</p>

<p align="center">
  <a href="https://ryanskytree.github.io/homepage"><img src="https://img.shields.io/badge/Website-Live-2ea44f?logo=githubpages&logoColor=white" alt="Website" /></a>
  <a href="https://scholar.google.com/citations?user=ON-RcMgAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar" /></a>
  <a href="https://orcid.org/0009-0004-7358-8076"><img src="https://img.shields.io/badge/ORCID-A6CE39?logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="mailto:xling.zhang@outlook.com"><img src="https://img.shields.io/badge/Email-xling.zhang@outlook.com-D14836?logo=maildotru&logoColor=white" alt="Email" /></a>
</p>

---

## About

This repository hosts my personal academic & professional homepage, built with the
[Academic Pages](https://academicpages.github.io/) theme (a Jekyll fork of Minimal Mistakes).

I am an **Algorithm Engineer at 360 Company**, with a strong interest in **Multimodal Large
Language Models, Multi-Agent Collaboration, and World Models**. My research expertise spans
Graph Machine Learning, Continual Learning, and AI Security, focusing on developing efficient,
scalable, and interpretable learning systems.

I received my Master of Computer Science from **Universiti Sains Malaysia (USM)**, and have
worked with the **Shenzhen Institute of Advanced Technology (SIAT), Chinese Academy of Sciences**
and **The Hong Kong University of Science and Technology (Guangzhou)**. My work has been
published at venues such as **ICML** and **ICASSP**.

📫 Reach me at [xling.zhang@outlook.com](mailto:xling.zhang@outlook.com).

## Research Interests

- Multimodal Large Language Models
- Multi-Agent Collaboration & World Models
- Continual Learning & Continual Graph Learning
- Graph Neural Networks & Graph Diffusion Models
- Dynamic Graph Learning
- AI Security & Endpoint Detection and Response (EDR)
- Explainable AI & Retrieval-Augmented Intelligence

## Selected Publications

| Year | Venue | Title |
| :--- | :---- | :---- |
| 2026 | ICML 2026 | **WatchLog: From a Glimpse to Decision** — Rapid Event Reasoning in EDR Logs with Multimodal LLMs |
| 2026 | TPAMI (subm.) | **AL-GNN: Privacy-Preserving and Replay-Free Continual Graph Learning via Analytic Learning** |
| 2026 | ICASSP 2026 *(oral)* | **Enhanced Graph Neural Networks Using K-Hop Gaussian Diffusion** |
| 2021 | AEECA 2021 *(oral)* | **A COVID-19 Prediction Model Based on Neural Network** |

See the [Publications page](https://ryanskytree.github.io/homepage/publications/) for the full list.

## Site Structure

```
├── _config.yml           # Site-wide settings (title, author, links, collection…)
├── _data/
│   ├── navigation.yml    # Top navigation menu items
│   ├── ui-text.yml       # UI label strings
│   └── authors.yml       # Author profile data
├── _pages/               # Standalone pages
│   ├── about.md          # Homepage       →  /
│   ├── publications.html # Publications   →  /publications/
│   ├── cv.md             # CV             →  /cv/
│   └── 404.md            # Not-found page
├── _publications/        # One Markdown file per publication
├── images/               # Avatar, paper posters, institution logos, favicons
├── files/                # Downloadable files (e.g. PDFs)
├── assets/               # CSS / JS / fonts
├── _includes/            # Theme partials
├── _layouts/             # Theme layouts
└── _sass/                # Theme styles (SCSS)
```

## Local Development

Preview the site locally before pushing changes.

### With Docker (recommended)

```bash
docker compose up
```

Then open <http://localhost:4000/homepage/>.

### With Ruby / Jekyll

```bash
# macOS
brew install ruby node
gem install bundler

# install dependencies
bundle install

# serve with live reload at http://localhost:4000/homepage/
jekyll serve -l -H localhost
```

> Changes to Markdown/HTML rebuild automatically. Changes to `_config.yml` require restarting
> the server.

## Editing Content

- **Site title, author info, social links** → `_config.yml`
- **Homepage text & biography** → `_pages/about.md`
- **CV** → `_pages/cv.md`
- **Add a publication** → drop a new Markdown file in `_publications/`
- **Navigation menu** → `_data/navigation.yml`

## License & Credits

Site content © Xuling Zhang. Theme based on
[Academic Pages](https://github.com/academicpages/academicpages.github.io) by Stuart Geiger,
which is a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) by
Michael Rose — both released under the MIT License (see [LICENSE](LICENSE)).
