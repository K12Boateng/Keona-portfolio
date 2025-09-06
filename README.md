# Keona's Portfolio - Young Robotics Prodigy & Creative Designer

A modern, responsive **portfolio website** showcasing the projects of *Keona*, a young prodigy passionate about **robotics, creative design, and playful innovation**.  
This project combines **clean UI design**, **dark/light theme switching**, and **interactive project previews** to highlight creativity and enthusiasm for learning.  

---

## Features

- **Modern UI** — Minimal, glassy design with accent gradients and smooth animations.  
- **Dark & Light Mode** — Automatic theme detection + toggle with persistence.  
- **Projects Showcase** — Responsive grid with images, short descriptions, and tags.  
- **Filter Projects** — Quickly filter projects by category (Robotics, Design, Wearable, Creative Art).  
- **Modal Previews** — Click project images to see details, tech stack, and demo links.  
- **Download Catalog** — CTA button for requesting a project catalog.  
- **Performance Optimized** — Lazy-loaded images, reveal animations via `IntersectionObserver`.  
- **Responsive** — Works beautifully on mobile, tablet, and desktop.  

---

## Tech Stack

- **HTML5** — Semantic and accessible structure.  
- **CSS3** — Custom properties, responsive grid, glassmorphism styles.  
- **Vanilla JavaScript (ES6+)** — Interactive features (theme toggle, filtering, modal).  
- **Google Fonts** — Lexend (primary typography).  
- **Unsplash** — Free stock images for project previews.  

---

## Project Structure

```
portfolio/
│
├── index.html       # Main HTML file
├── imgs/            # Local image assets (profile, icons, etc.)
│   └── smiling-girl-with-graduation-cap-cartoon-style1.png
└── README.md        # This file
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/keona-portfolio.git
cd keona-portfolio
```

### 2. Open in Browser

Simply open `index.html` in your favorite browser:

```bash
open index.html    # macOS
start index.html   # Windows
```

No build tools required! It’s pure HTML/CSS/JS.

---

## Customization

- **Profile Image:** Replace `imgs/smiling-girl-with-graduation-cap-cartoon-style1.png` with your own.  
- **Projects:** Edit the `projects` array inside `index.html` (or `script.js`) to add/remove projects.  
- **Theme Colors:** Update CSS variables (`:root`) for custom accent gradients or background colors.  
- **Fonts:** The project uses *Lexend* via Google Fonts. Change the link in `<head>` to use another font.  

---

## Example Projects

Some example projects included:  
- **Robo-Pal:** A hugging companion robot.  
- **PaperBot:** Origami-inspired folding bot.  
- **SunChaser Rover:** Solar-tracking rover.  
- **Glow Jacket:** Wearable LED art jacket.  
- **StoryBot:** Interactive robotic storybook.  
- **Robot Art Studio:** A drawing bot inspired by music.  

---

## Roadmap / Ideas

- [ ] Add animations when switching themes.  
- [ ] Add blog section for tutorials & stories.  
- [ ] Deploy to **GitHub Pages** or **Vercel**.  
- [ ] Add contact form with backend support (EmailJS or Netlify Forms).  

---

## License

This project is open-source under the **MIT License** — free to use, modify, and share.  

---

## Author

**Keona** — *Young Robotics Prodigy & Designer*  
📧 [keona@ghana.com](mailto:keona@ghana.com)  

> *“I bridge circuits and color — from tiny rovers that follow the sun to interactive storybooks that move when you turn the page.”*  
