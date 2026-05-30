# Kayla Culminating Project Website

A modern, responsive 3-page website built with Material Design principles for GitHub Pages.

## Pages

1. **Home (index.html)** - Welcome page with project overview
2. **About Me (about-me.html)** - Personal facts and reflections
3. **Pitching (pitching.html)** - Information about pitching skills

## Design System

Based on Material Design with the following specifications:

- **Primary Color**: #6442D6 (Purple)
- **Secondary Color**: #C8B3FD (Light Purple)
- **Typography**: Inter (body), Roboto (headings), Fira Code (mono)
- **Spacing Scale**: 4/8/12/16/24/32px
- **Border Radius**: 4px (sm), 8px (md)

## Deployment to GitHub Pages

### Option 1: Using an existing repository

1. Copy all files to your repository:
   ```bash
   git add index.html about-me.html pitching.html styles.css README.md
   git commit -m "Add culminating project website"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Create a new repository

1. Create a new repository on GitHub named `username.github.io` (replace `username` with your GitHub username)

2. Initialize and push:
   ```bash
   cd C:\Users\T912462\git\tmp
   git init
   git add .
   git commit -m "Initial commit: Kayla Culminating website"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. Your site will be automatically available at `https://yourusername.github.io/`

## Files Structure

```
.
├── index.html          # Home page
├── about-me.html       # About Me page
├── pitching.html       # Pitching page
├── styles.css          # Material Design stylesheet
└── README.md           # This file
```

## Features

- ✅ Fully responsive design
- ✅ Material Design components
- ✅ Clean, modern interface
- ✅ Accessible navigation
- ✅ Mobile-friendly
- ✅ Fast loading (no dependencies except Google Fonts)

## Browser Support

Works on all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

This project is open source and available for educational purposes.
