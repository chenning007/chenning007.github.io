# BrowserDesktop Landing Page

This folder contains the landing page for BrowserDesktop extension.

## Structure

```
docs/
├── index.html      # Main landing page (multi-language)
├── assets/
│   ├── icon128.png # Extension icon
│   ├── favicon.png # Favicon
│   ├── preview.png # Screenshot of the extension (ADD THIS)
│   ├── hero-bg.jpg # Hero background image (optional)
│   ├── chrome.svg  # Browser icons
│   ├── edge.svg
│   ├── brave.svg
│   └── opera.svg
```

## Required Assets

Before deploying, add these files to the `assets/` folder:

1. **preview.png** - A screenshot of BrowserDesktop in action (recommended: 1280x800 or similar)
2. **hero-bg.jpg** (optional) - A background image for the hero section

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Set source to "Deploy from a branch"
4. Select "main" branch and "/docs" folder
5. Save

Your landing page will be available at:
`https://chenning007.github.io/BrowserDesktop/`

### Custom Domain

Add a `CNAME` file in this folder with your custom domain.

## Download Link

The download button links to:
```
https://github.com/chenning007/BrowserDesktop/releases/latest/download/BrowserDesktop.zip
```

Make sure to create a release with the ZIP file attached.

## Creating a Release

1. Run `.\build.ps1` to create the ZIP package
2. Go to GitHub → Releases → "Create a new release"
3. Create a tag (e.g., `v1.1.0`)
4. Upload `dist/BrowserDesktop-v1.1.0.zip` as `BrowserDesktop.zip`
5. Publish the release
