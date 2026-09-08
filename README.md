# Yug Patel — Portfolio

My personal portfolio site. **Live at → [epicyug.github.io](https://epicyug.github.io)**

Computer & Information Technology student at Purdue University (GPA 3.88, class of 2028), currently seeking a **Summer 2026 software engineering internship**. I build full-stack web and mobile apps — and the hardware they talk to.

## Featured projects

| Project | What it is | Stack |
|---------|-----------|-------|
| **RackRadar** | Smart bike lock + mobile app — 3rd of 170 teams at the Purdue Design & Innovation Challenge | React Native, ESP32, MQTT, firmware, 3D printing |
| **Hours Counter** | AI timesheet digitizer using OCR and a serverless scan-to-email pipeline | Google Cloud Vision, Netlify Functions, IMAP, TypeScript |
| **LocalInn PMS** | Staff property-management system for a walk-in inn | TypeScript, React, Supabase |
| **Iron & Olive** | Offline training tracker with progressive-overload suggestions | PWA, Service Worker, JavaScript |

## About this site

A single, dependency-free `index.html` — no build step, no framework. Just semantic HTML and hand-written CSS.

- **Type:** Bricolage Grotesque (display) + Newsreader (body), via Google Fonts
- **Themes:** respects the visitor's light/dark preference
- **Accessible:** keyboard focus states, reduced-motion support, responsive down to mobile
- **Hosting:** GitHub Pages

## Run locally

No tooling required — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploying changes

The `main` branch is published automatically by GitHub Pages. Edit `index.html`, then:

```bash
git add index.html
git commit -m "docs: update portfolio content"
git push
```

Changes go live at [epicyug.github.io](https://epicyug.github.io) within a minute or two.

## Contact

- **Email:** yug11507@icloud.com
- **GitHub:** [@Epicyug](https://github.com/Epicyug)
- **LinkedIn:** [in/yug-patel-019018332](https://linkedin.com/in/yug-patel-019018332)
