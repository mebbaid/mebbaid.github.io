# MkDocs Typewriter Theme - Setup Summary

## 🎨 Typewriter Aesthetic Features

### Visual Design
- **Light Mode:** Vintage paper with brown/sepia tones
- **Dark Mode:** Retro terminal with green phosphor text
- **Fonts:** Courier Prime & Special Elite (typewriter fonts)
- **Effects:** 
  - Blinking cursor on H1 headings
  - Paper texture overlay (light mode)
  - CRT scanline effect (dark mode)
  - Typewriter-style borders and buttons

### Typography
- All text in monospace Courier Prime
- Headers in Special Elite (authentic typewriter font)
- Uppercase headers with underlines
- Dotted underlines for links

### Color Schemes
**Light Mode (Vintage Paper):**
- Background: #f4f1e8 (aged paper)
- Text: #2b2b2b (typewriter ink)
- Links: #8b4513 (saddle brown)

**Dark Mode (Old Terminal):**
- Background: #1a1a1a (CRT screen)
- Text: #00ff00 (phosphor green)
- Accent: #ffff00 (terminal yellow)

## 📁 File Structure

```
mebbaid.github.io/
├── mkdocs.yml                    # Main config with typewriter theme
├── docs/
│   ├── index.md                  # Home with ASCII art
│   ├── about.md                  # About page
│   ├── cv.md                     # CV with retro banner
│   ├── projects/
│   │   ├── locomotion.md         # Project pages with headers
│   │   ├── teleoperation.md
│   │   ├── teaching.md
│   │   └── personal.md
│   ├── stylesheets/
│   │   └── extra.css             # Custom typewriter CSS
│   ├── images/                   # Project images
│   └── uploads/                  # PDF files
└── .github/
    └── workflows/
        └── deploy.yml            # Auto-deployment
```

## 🚀 Local Preview

```bash
# Activate virtual environment and run
.venv/bin/mkdocs serve
```

Visit: http://127.0.0.1:8000

## 📤 Deploy to GitHub Pages

```bash
# Add all new files
git add mkdocs.yml docs/ .github/workflows/

# Commit
git commit -m "Add MkDocs with typewriter aesthetic"

# Push
git push origin main
```

GitHub Actions will automatically:
1. Build the site
2. Deploy to GitHub Pages
3. Available at: https://mebbaid.github.io

## 🎯 Features to Try

1. **Toggle Dark/Light Mode** - See the vintage paper vs terminal look
2. **Navigate tabs** - Typewriter key style navigation
3. **Hover links** - Animated underlines
4. **Check ASCII boxes** - Retro project headers
5. **Code blocks** - Terminal-style formatting

## ✏️ Customization

To modify colors, edit `docs/stylesheets/extra.css`:
- `:root` variables for global colors
- `[data-md-color-scheme="default"]` for light mode
- `[data-md-color-scheme="slate"]` for dark mode

Enjoy your retro research portfolio! 🎉
