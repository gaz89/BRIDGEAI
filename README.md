# BRIDGE Workshop @ MICCAI 2025

**Bridging Regulatory Science and Medical Imaging Evaluation**

🌐 Live site: https://bridge-regsci.github.io/miccaibridge/

---

## The BRIDGE Pipeline

> **Evaluate it → Measure its clinical value → Deploy it responsibly → Monitor it**

Regulation is not a step in this pipeline — it is the governing framework that makes each stage possible and accountable.

---

## Site Structure

```
bridge-site/
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Shared layout (nav + footer)
├── _includes/
│   ├── nav.html           # Navigation bar
│   └── footer.html        # Footer
├── assets/
│   ├── css/
│   │   └── main.css       # All styles
│   └── img/               # Organizer photos
├── index.html             # Home page
├── about.html             # About & organizers
├── submission.html        # Call for papers
├── schedule.html          # Workshop program
└── Gemfile
```

## Local Development

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/miccaibridge/

## Deploying to GitHub Pages

1. Push this folder to the `main` branch of your repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. GitHub will build and deploy automatically

## Organizer Photos

Place organizer photos in `assets/img/` with these exact filenames:
- `Ghada.jpg`
- `Mariia.jpg`
- `Thijs.jpg`
- `Xiaoxiao.jpg`
- `Annika.jpg`
- `Ehsan.jpg`
- `Marzyeh.jpg`
- `Lena.jpg`
- `Federica.jpg`

If a photo is missing, the card gracefully shows initials instead.

## Contact

📧 BRIDGERegSci@gmail.com

© 2025 BRIDGE Workshop · Made by [Mariia Sidulova](https://www.linkedin.com/in/mariia-sidulova/)
