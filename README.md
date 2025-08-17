# Harin's Portfolio (Quarto + R)

A fully R-coded portfolio website using **Quarto** that auto-builds on GitHub via **GitHub Actions** and deploys to **GitHub Pages**.

## 🚀 Quick Deploy (no local Quarto needed)

1. **Create a new GitHub repo** named `harin-portfolio` (Public).  
2. Upload *all files and folders* from this project (including `.github/workflows/`).  
3. Go to **Settings → Pages** and set **Source = GitHub Actions**.  
4. Wait ~2 minutes. Your site will be live at `https://YOUR_USERNAME.github.io/harin-portfolio/`.

## 🧑‍💻 Local Editing (optional)

- Install R and RStudio.
- Install Quarto: https://quarto.org
- Render locally: `quarto render`

## ✍️ Update content

- Edit text in `index.qmd`, `about.qmd`, and `projects.qmd`.
- Add projects by editing `data/projects.csv`.
- Replace CV at `files/cv/Harin_Aiyanna_CV.pdf`.

## 🔧 Tech

- Quarto website
- R code chunks (RMarkdown-like)
- GitHub Actions builds and deploys to `gh-pages`
