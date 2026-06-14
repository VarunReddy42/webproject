# Sai Varun Reddy Mettu — Portfolio Website

Personal portfolio website built with HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages.

## 🔗 Live Site

[https://VarunReddy42.github.io](https://VarunReddy42.github.io)

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Main HTML structure |
| `style.css` | All styling — dark theme, responsive |
| `script.js` | Mobile nav, scroll animations, active nav tracking |

## 🚀 Deploy to GitHub Pages

1. Create a repo named `webproject` on GitHub
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/VarunReddy42/VarunReddy42.github.io.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source → main branch** and save
4. Your site will be live at `https://VarunReddy42.github.io` in ~2 minutes

## 🛠 Tech Stack

- HTML5
- CSS3 (CSS Variables, Grid, Flexbox)
- Vanilla JavaScript (IntersectionObserver, scroll events)
- Google Fonts: Space Grotesk + JetBrains Mono

## ✏️ Customisation Tips

- Update project GitHub/live links in `index.html` under the `#projects` section
- Add a profile photo by placing `photo.jpg` in the folder and adding `<img src="photo.jpg">` to the hero section
- Change accent color by editing `--accent: #4f8ef7;` in `:root` inside `style.css`
