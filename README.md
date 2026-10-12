# cordiaz.github.io

Personal portfolio website of **Muhammad Cordiaz, S.Si., M.Kom.** — Cloud Solution Architect & Multi-Cloud Certified Engineer (AWS, Alibaba Cloud MVP, Huawei Cloud).

Live site: **https://cordiaz.github.io/**

## About

A static one-page portfolio covering:

- **About** — background and current role
- **Experience** — career timeline (Huawei Cloud Indonesia, AWS Trainer at Westcon-Comstor Asia, 17+ years of infrastructure roles at PT Kompas Media Nusantara)
- **Skills** — cloud platforms, infrastructure, web/database stacks, operating systems
- **Certifications & Achievements** — Alibaba Cloud MVP (since 2019), AWS, Huawei Cloud, and other credentials
- **Projects & Case Studies** — pre-sales cloud solutioning, cloud migration, and training program delivery
- **Community & Speaking**
- **Contact** — email, WhatsApp, LinkedIn, resume

The full resume with complete certification list is maintained separately at [github.com/cordiaz/resume](https://github.com/cordiaz/resume).

## Project structure

```
.
├── index.html                          # Main portfolio page
├── style.css                           # Site styles
├── script.js                           # Nav toggle & footer year
├── projects/                           # Case study detail pages
│   ├── pre-sales-cloud-solutioning.html
│   ├── cloud-migration-project.html
│   └── training-program-delivered.html
└── assets/                             # Images used by the project pages
    ├── pre-sales-cloud-solutioning/
    ├── cloud-migration-project/
    └── training-program-delivered/
```

## Tech stack

Plain **HTML5 / CSS3 / vanilla JavaScript** — no build step, no framework, no dependencies. Fonts are loaded from Google Fonts (Inter).

## Running locally

Since this is a static site, just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Hosted via **GitHub Pages**, serving directly from the `main` branch.

## License

Personal portfolio content — not licensed for reuse without permission.
