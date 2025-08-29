# 📦 My CDN

This repository serves as a **personal CDN** for hosting images, icons, CSS, JS, and other static files using **GitHub Pages**.  
It provides **stable public URLs** that can be used in projects, websites, documentation, or apps.

---

## 🚀 Getting Started

### 1. Repository Setup
- Repository name: `my-cdn`
- Make sure it is **public** to allow access to the files.

### 2. Add Your Files
- Place all files inside the `assets/` folder.
- Organize by project or shared resources:

```
assets/
├── project1/
│   ├── logo.png
│   └── banner.jpg
├── project2/
│   ├── icon.svg
│   └── background.png
└── shared/
    ├── favicon.ico
    └── loading.gif
```

### 3. Enable GitHub Pages
1. Go to **Settings → Pages**.
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/root`
3. Click **Save**.

GitHub will provide a URL such as:
```
https://YOUR-USERNAME.github.io/my-cdn/
```

---

## 📌 Accessing Files

Files in the `assets/` folder will have a public URL. Examples:

```
https://YOUR-USERNAME.github.io/my-cdn/assets/project1/logo.png
https://YOUR-USERNAME.github.io/my-cdn/assets/project2/background.png
https://YOUR-USERNAME.github.io/my-cdn/assets/shared/favicon.ico
```

---

## 🔹 Usage Examples

**Markdown**:
```md
![Project Logo](https://YOUR-USERNAME.github.io/my-cdn/assets/project1/logo.png)
```

**HTML**:
```html
<img src="https://YOUR-USERNAME.github.io/my-cdn/assets/project2/background.png" alt="Background">
```

**CSS**:
```css
body {
  background-image: url("https://YOUR-USERNAME.github.io/my-cdn/assets/project2/background.png");
}
```

---

## 🔹 Best Practices

- Use **descriptive file names**: `logo-dark.png`, `banner-2025.jpg`.  
- Organize by **projects** and **shared resources**.  
- Use **versioning** for updates: `logo-v2.png` to avoid breaking links.  
- Optional: organize by file type within projects:
```
assets/project1/images/
assets/project1/icons/
assets/project1/videos/
```

---

## ✅ Advantages

- Free hosting via GitHub Pages.  
- Stable links for websites, apps, and documentation.  
- Easy to update (commit → push).  
- Supports images, CSS, JS, fonts, JSON, and other static files.

---

✍️ Created to simplify asset hosting and management using **GitHub Pages**.
