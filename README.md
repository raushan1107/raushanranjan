# Raushan Ranjan – Portfolio Website

A modern **developer & corporate trainer portfolio website** showcasing professional experience, certifications, technical skills, projects, and global training impact.

This portfolio highlights **Azure, Power Platform, .NET, AI, and enterprise training expertise** in a visually rich and interactive web experience.

---

## Live Preview

- **Azure (Primary):** https://raushan-ranjan.azurewebsites.net/
- **GitHub Pages:** https://raushan1107.github.io/raushanranjan/

---

## About the Project

This portfolio represents the professional journey of **Raushan Ranjan**, a **Microsoft Certified Trainer (MCT)** and **Iconic Corporate Trainer at Koenig Solutions** with experience training **2900+ professionals globally** across modern Microsoft technologies.

The site is designed to highlight:

- Professional background
- Certifications (26+ Microsoft certifications)
- Enterprise training expertise
- Technical skillset
- Real-world projects
- Testimonials
- Contact information

---

## Features

### Modern UI Design
- Clean professional layout with navy + amber color system
- Custom typography (Fraunces serif + Outfit sans-serif)
- CSS custom properties (design tokens)

### Smooth Animations
- GSAP animations with ScrollTrigger
- Scroll-triggered transitions
- Interactive hover effects

### Interactive UX
- Custom cursor
- Scroll progress rail with section dots
- Animated statistics counters
- Hero particle effects
- Preloader animation

### Fully Responsive
- Desktop optimized layout
- Tablet support
- Mobile responsive design

---

## Website Sections

- Hero Introduction
- About Me
- Certifications
- Technical Skills
- Experience / Career Timeline
- Projects Portfolio
- Testimonials
- Contact

---

## Tech Stack

Frontend technologies used:

- HTML5
- CSS3 (custom properties, Grid, Flexbox)
- JavaScript
- GSAP 3.12 Animation Library
- ScrollTrigger plugin
- Google Fonts (Fraunces, Outfit)

CI/CD:

- GitHub Actions → Azure App Service (auto-deploy on push to `main`)

---

## Project Structure

```
raushanranjan/
├── index.html                        # Main portfolio page
├── site.css                          # Standalone stylesheet (alternate)
├── favicon.ico                       # Site favicon
├── raushan.jpg                       # Profile photo
├── preview.png                       # OG / social preview image
├── README.md                         # Project documentation
└── .github/
    └── workflows/
        └── main_raushan-ranjan.yml   # Azure deployment pipeline
```

---

## How to Run Locally

**Clone the repository**

```bash
git clone https://github.com/raushan1107/raushanranjan.git
cd raushanranjan
```

**Open in browser**

```
index.html
```

No build tools or installations required.

---

## Deployment

The site is deployed automatically via **GitHub Actions** on every push to `main`.

**Pipeline:** `.github/workflows/main_raushan-ranjan.yml`  
**Target:** Azure App Service (`raushan-ranjan`)

To deploy to GitHub Pages instead:

```
Settings → Pages → Deploy from branch → main
```

---

## Future Improvements

Planned enhancements:

- Blog integration
- CMS-based content editing
- Project filtering
- Dark / Light mode toggle
- Performance optimization
- SEO improvements

---

## Connect With Me

**Email:** raushanr1107@gmail.com

**LinkedIn:** https://www.linkedin.com/in/raushanranjan

**GitHub:** https://github.com/raushan1107

---

## License

This project is open source and available under the **MIT License**.

---

If you like this project, consider starring the repository.
