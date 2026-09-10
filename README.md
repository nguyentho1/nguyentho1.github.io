# Nguyen Ngoc Tho — Personal Academic Website

A static academic website for GitHub Pages deployment.

## Quick Setup

1. **Create a GitHub repository** named `<your-github-username>.github.io`
2. **Upload these files** to the root of that repository
3. **Enable GitHub Pages** in repo Settings → Pages → Source: `main` branch, `/ (root)`
4. Your site will be live at `https://<your-github-username>.github.io`

## Customizing Content

Edit `index.html` directly — all content is in one file.

### Key sections to update:
- **About**: Update bio text and research interests (search `About Me`)
- **Publications**: Add your real papers with DOI links (search `pub-list`)
- **Projects**: Update project cards with real details
- **CV section**: Fill in your education history; replace `assets/cv.pdf` with your actual CV
- **Sidebar links**: Add your Google Scholar, GitHub, and ResearchGate URLs
- **Stats**: Update the 12+ / 8+ / 20+ numbers to match your profile

### Adding a photo
Replace the avatar initials `TN` with an `<img>` tag in the `.sb-avatar` div, or use a CSS background-image.

### Adding your CV PDF
Place your CV as `assets/cv.pdf` — the download button links there automatically.

## Structure
```
├── index.html          ← main site (edit this)
├── 404.html            ← custom 404 page
├── .nojekyll           ← disables Jekyll on GitHub Pages
├── assets/
│   ├── img/            ← add your photo here
│   └── cv.pdf          ← add your CV here
└── README.md
```

## Contact
Nguyen Ngoc Tho · thon@uda.edu.vn · ORCID: 0000-0002-9612-8476
