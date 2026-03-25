# personal_portfolio

# Yashwanth Sai Paladugu — Personal Portfolio

A clean, fully responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript. Features smooth scroll animations, a live 3D Rubik's cube background, project video previews, and a dark contact/footer section.

---

## Live Demo

> Replace with your GitHub Pages or hosted URL once deployed.

---

## Features

- **Responsive Design** — works across desktop, tablet, and mobile
- **Smooth Scroll + Active Nav Highlighting** — nav links highlight based on scroll position
- **Animated Timeline** — intersection-observer-driven work experience layout
- **3D Rubik's Cube** — Three.js wireframe cube rendered on the experience section background
- **Project Video Previews** — autoplay looping video previews for personal projects
- **WIP Card Overlay** — blurred "Soon" stamp for in-progress projects
- **Scroll-to-Top on Refresh** — page always loads at the hero section
- **Mobile Hamburger Menu** — fullscreen nav overlay for small screens

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid, keyframe animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| 3D Graphics | Three.js r128 |
| Fonts | Google Fonts — Raleway, Poppins |

No frameworks. No build tools. No dependencies beyond Three.js and Google Fonts.

---

## Project Structure

```
portfolio/
├── index.html          # Main HTML file (all styles and scripts inline)
├── images/
│   ├── background.jpeg # Hero section photo
│   ├── project_1.mp4   # Video preview — AB de Villiers tribute
│   ├── project_2.mp4   # Video preview — Sandy Pixelz photography
│   └── project_3.mp4   # Video preview — WIP project
└── README.md
```

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, role, CTA buttons, and profile photo |
| **About** | Bio, soft skills pills |
| **Experience** | Two-column timeline with animated cards |
| **Skills** | Six skill category cards (Languages, Frontend, Backend, Databases, Cloud, Tools) |
| **Projects** | Work projects with metric highlights |
| **Personal Projects** | Side projects with video previews, tech tags, GitHub and live demo links |
| **Education** | Degree card |
| **Contact** | Email, phone, LinkedIn links + call-to-action |

---

## Getting Started

No build step required. Just open in a browser:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
open index.html
```

Or serve locally to avoid any video autoplay restrictions:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000`.

---

## Deployment

### GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://your-username.github.io/your-repo/`

### Netlify / Vercel

Drag and drop the project folder into [Netlify Drop](https://app.netlify.com/drop) or connect the GitHub repo for automatic deployments.

---

## Customization

All colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --black:   #1a1a2e;
  --accent:  #e94560;  /* Red — used for highlights, buttons, borders */
  --accent2: #533483;  /* Purple — used for secondary accents */
  --white:   #ffffff;
  --light:   #f5f5f5;
}
```

Change `--accent` to retheme the entire site instantly.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Contact

**Yashwanth Sai Paladugu**
- Email: paladuguyashwanthsai@gmail.com
- Phone: +1 913-238-8827
- LinkedIn: [yashwanth-sai-paladugu](https://www.linkedin.com/in/yashwanth-sai-paladugu-5b9a22225)
