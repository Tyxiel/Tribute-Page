# tyxiel-tribute-page

> 🎬 Página de tributo a Sylvester Stallone. Aplicação estática celebrando a trajetória do lendário ator, com biografia, imagens icônicas e design responsivo.

[🇧🇷 Português](#-visão-geral-pt) | [🇺🇸 English](#-overview-en)

---

## 📋 Table of Contents

- [Visão Geral (PT)](#-visão-geral-pt)
- [Overview (EN)](#-overview-en)
- [Tech Stack](#-tech-stack)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
- [Architecture](#-architecture)
- [Content Structure](#-content-structure)
- [Environment Variables](#-environment-variables)
- [Available Scripts](#-available-scripts)
- [Testing](#-testing)
- [Deployment](#-deployment)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🇧🇷 Visão Geral (PT)

Página de tributo estática dedicada a **Sylvester Stallone**, celebrando sua carreira lendária como ator, roteirista e diretor. Desenvolvida como projeto educacional (freeCodeCamp Responsive Web Design Certification), a página apresenta biografia, imagens icônicas de Rocky e Rambo, e design totalmente responsivo com suporte a PWA.

### Principais Funcionalidades

- ✅ Design responsivo com layout adaptável (mobile-first)
- ✅ Suporte a PWA: ícones Apple Touch, manifest.json, browserconfig.xml
- ✅ Acessibilidade: ARIA labels, estrutura semântica HTML5, contraste adequado
- ✅ Performance: CSS otimizado, scroll suave com `prefers-reduced-motion`
- ✅ Imagens externas com alt text descritivo para screen readers
- ✅ Zero JavaScript: funcionalidade completa apenas com HTML/CSS
- ✅ License AGPL v3 para software livre

### Conteúdo em Destaque

| Seção | Descrição |
|-------|-----------|
| **Hero Image** | Foto de Stallone com esposa em evento formal, com legenda descritiva |
| **Biografia** | Texto sobre infância, desafios e ascensão de Stallone em Hollywood |
| **Rocky Era** | Referência ao filme que lançou sua carreira, com imagem icônica |
| **Rambo Era** | Menção à saga First Blood e consolidação como estrela de ação |
| **Footer** | Atribuições a colaboradores e fontes de mídia |

---

## 🇺🇸 Overview (EN)

Static tribute page dedicated to **Sylvester Stallone**, celebrating his legendary career as actor, screenwriter, and director. Built as an educational project (freeCodeCamp Responsive Web Design Certification), the page features biography, iconic images from Rocky and Rambo, and fully responsive design with PWA support.

### Key Features

- ✅ Responsive design with adaptive layout (mobile-first)
- ✅ PWA support: Apple Touch icons, manifest.json, browserconfig.xml
- ✅ Accessibility: ARIA labels, semantic HTML5 structure, proper contrast
- ✅ Performance: Optimized CSS, smooth scrolling with `prefers-reduced-motion`
- ✅ External images with descriptive alt text for screen readers
- ✅ Zero JavaScript: full functionality with HTML/CSS only
- ✅ AGPL v3 license for free software

### Featured Content

| Section | Description |
|---------|-------------|
| **Hero Image** | Photo of Stallone with wife at formal event, with descriptive caption |
| **Biography** | Text about childhood, challenges, and rise to Hollywood stardom |
| **Rocky Era** | Reference to the film that launched his career, with iconic image |
| **Rambo Era** | Mention of First Blood saga and establishment as action star |
| **Footer** | Attributions to contributors and media sources |

---

## 🛠 Tech Stack

| Category | Technology | Version/Purpose |
|----------|-----------|-----------------|
| **Markup** | HTML5 | Semantic structure, ARIA attributes, PWA meta tags |
| **Styling** | CSS3 | Flexbox layout, responsive breakpoints, CSS variables |
| **Icons** | Favicon Generator | Multi-size icons for iOS, Android, Windows |
| **Images** | External CDNs | Unsplash, Pinimg, Globo for content images |
| **Hosting** | Any static host | GitHub Pages, Netlify, Vercel, or local file |
| **License** | GNU AGPL v3 | Copyleft license for network software |

### Why This Stack?

- **Zero build step**: Edit `.html`/`.css` and refresh — no compilation needed.
- **Maximum compatibility**: Works in all modern browsers without polyfills.
- **Lightweight**: ~2KB CSS + ~4KB HTML = instant load times.
- **Educational**: Demonstrates semantic HTML, responsive CSS, and accessibility best practices.
- **PWA-ready**: Includes manifest and touch icons for installability.

---

## 📦 Prerequisites

| Tool | Version | Purpose | Install Command |
|------|---------|---------|----------------|
| **Web Browser** | Chrome 55+, Firefox 52+, Edge 15+, Safari 10+ | Render page and apply CSS | [Download](https://www.google.com/chrome/) |
| **Text Editor** | Any (VS Code recommended) | Edit source files | [VS Code](https://code.visualstudio.com/) |
| **Git** | 2.30+ (optional) | Clone repo and manage versions | `sudo apt install git` / `brew install git` |
| **Node.js** | Not required | — | — |

> 💡 **No package manager, bundler, or runtime needed.** This is a pure static site.

### PWA Icon Requirements

The project includes a complete icon set for cross-platform support:

```
img/icons/
├── apple-icon-57x57.png    # iPhone (non-Retina)
├── apple-icon-60x60.png    # iPhone (Retina)
├── apple-icon-72x72.png    # iPad (non-Retina)
├── apple-icon-76x76.png    # iPad (Retina)
├── apple-icon-114x114.png  # iPhone 4 (Retina)
├── apple-icon-120x120.png  # iPhone 6+/7+/8+
├── apple-icon-144x144.png  # iPad Pro
├── apple-icon-152x152.png  # iPad (Retina)
├── apple-icon-180x180.png  # iPhone X/11/12/13
├── android-icon-192x192.png # Android Chrome
├── favicon-16x16.png       # Browser tab
├── favicon-32x32.png       # Browser tab (HD)
├── favicon-96x96.png       # Google TV
├── ms-icon-144x144.png     # Windows tile
├── manifest.json           # Web App Manifest
└── browserconfig.xml       # IE/Edge config
```

> ⚠️ **Note**: Icon files are referenced but not included in this repo. Generate your own using [RealFaviconGenerator](https://realfavicongenerator.net/) or similar tools.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tyxiel/tyxiel-tribute-page.git
cd tyxiel-tribute-page
```

### 2. Open Locally

**Option A: Direct file open (quick test)**
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

**Option B: Local server (recommended for accurate testing)**
```bash
# Python 3
python3 -m http.server 8000
# Then open: http://localhost:8000

# Or with Node.js (if installed)
npx serve .
```

### 3. Verify Functionality

| Feature | Test Steps | Expected Result |
|---------|-----------|----------------|
| **Page loads** | Open index.html | Title "Tribute of Sylvester Stallone" visible |
| **Hero image** | Scroll to top | Stallone photo loads with caption below |
| **Biography section** | Scroll down | Text about Rocky/Rambo with inline image |
| **Responsive layout** | Resize browser to ≤768px | Content stacks vertically, no horizontal scroll |
| **Smooth scroll** | Click internal link (if added) | Page scrolls smoothly (unless reduced motion enabled) |
| **PWA icons** | Check browser dev tools → Application | Manifest and icons registered (if served via HTTPS) |
| **Accessibility** | Use keyboard Tab navigation | Focus indicators visible on interactive elements |

### 4. Customize Content (Optional)

**Update biography text** in `index.html`:
```html
<div class="biography-info__text">
  <!-- Edit this section with your own tribute content -->
  Sylvester Gardenzio Stallone, born on July 6, 1946...
</div>
```

**Replace images** (ensure proper attribution):
```html
<!-- Hero image -->
<img id="image" src="YOUR_IMAGE_URL" alt="Descriptive alt text"/>

<!-- Biography inline image -->
<img class="biography-info__img" src="YOUR_ROCKY_IMAGE" alt="Stallone as Rocky"/>
```

**Adjust colors** in `styles.css`:
```css
:root {
  /* Add CSS variables for easier theming */
  --color-bg: #E0E1DD;
  --color-text: #0D1B2A;
  --color-accent: #415A77;
}

body {
  background-color: var(--color-bg);
  color: var(--color-text);
}
```

**Fix HTML typo** (optional):
```html
<!-- Current (line 2): dir="lft" is invalid -->
<html dir="lft" lang="en">

<!-- Corrected: -->
<html dir="ltr" lang="en">
```

---

## 🏗 Architecture

### Directory Structure

```
tyxiel-tribute-page/
├── index.html              # Main entry: HTML structure + content + PWA meta
├── styles.css              # All visual styling: layout, responsiveness, theming
├── LICENSE                 # GNU AGPL v3 license text
├── README.md               # This documentation
└── img/
    └── icons/              # PWA icon set (files not included in repo)
        ├── browserconfig.xml   # Windows/IE tile configuration
        ├── manifest.json       # Web App Manifest for Android/Chrome
        ├── apple-icon-*.png    # iOS touch icons (multiple sizes)
        ├── android-icon-*.png  # Android Chrome icons
        ├── favicon-*.png       # Browser tab icons
        └── ms-icon-*.png       # Windows start menu tiles
```

### File Responsibilities

#### `index.html` — Content & Structure

```html
<!-- PWA & SEO Meta Tags -->
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Tribute to Sylvester Stallone...">
  
  <!-- Apple Touch Icons -->
  <link rel="apple-touch-icon" sizes="180x180" href="./img/icons/apple-icon-180x180.png">
  
  <!-- Android/Chrome Manifest -->
  <link rel="manifest" href="/manifest.json">
  
  <!-- Windows Tile Config -->
  <meta name="msapplication-TileColor" content="#ffffff">
  <meta name="msapplication-TileImage" content="./img/icons/ms-icon-144x144.png">
  
  <!-- Theme Color for Browser UI -->
  <meta name="theme-color" content="#ffffff">
</head>

<!-- Semantic Main Content -->
<main id="main" aria-labelledby="title">
  
  <!-- Page Title -->
  <h1 id="title">Sylvester Stallone</h1>
  
  <!-- Hero Figure with Caption -->
  <figure id="img-div">
    <img id="image" src="..." alt="..."/>
    <figcaption id="img-caption">Descriptive caption...</figcaption>
  </figure>
  
  <!-- Biography Section -->
  <section id="tribute-info" aria-labelledby="biography-title">
    <h2 id="biography-title">Biography</h2>
    <div class="biography-info">
      <div class="biography-info__text">
        <!-- Biography text with inline image reference -->
      </div>
      <img class="biography-info__img" src="..." alt="..."/>
    </div>
  </section>
  
  <!-- Additional Content Section -->
  <section>
    <div class="biography-info__text2">...</div>
    <img class="biography-info__img2" src="..." alt="..."/>
  </section>
</main>

<!-- Footer with Attributions -->
<footer>
  Thanks <a href="...">@thedaviddias</a> for front-end best practices...
</footer>
```

#### `styles.css` — Design System

```css
/* 1. Respect user motion preferences */
@media (prefers-reduced-motion: no-preference) {
  * { scroll-behavior: smooth; }
}

/* 2. Reset and base box model */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* 3. Body layout and typography */
body {
  background-color: #E0E1DD;
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.5;
  min-height: 100vh;
}

/* 4. Main content container */
main {
  width: 95%;
  max-width: 1200px;
  margin: 25px auto;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* 5. Responsive image handling */
#image {
  display: block;
  width: 90%;
  max-width: 100%;
  height: auto;
  margin: 0 auto;
}

/* 6. Biography layout (desktop) */
.biography-info {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
}

.biography-info__text {
  width: 70%;
  text-align: justify;
  text-indent: 1em;
}

.biography-info__img {
  width: 25%;
  height: auto;
}

/* 7. Mobile responsiveness */
@media (max-width: 768px) {
  .biography-info {
    flex-direction: column;
  }
  .biography-info__text,
  .biography-info__img {
    width: 100%;
  }
}

/* 8. Footer styling */
footer {
  background: #0d1b2a;
  color: #e0e1dd;
  padding: 10px;
  text-align: center;
}
```

### Content Flow Diagram

```
User loads page
       ↓
Browser parses HTML → loads styles.css → renders layout
       ↓
Main content appears:
1. Title "Sylvester Stallone"
2. Hero image + caption
3. Divider
4. Biography section (text + inline image)
5. Additional content (Rambo reference + full-width image)
       ↓
User scrolls → smooth scroll (if enabled)
       ↓
Footer visible at bottom with attributions
```

### Accessibility Features

```html
<!-- Semantic landmarks -->
<main id="main" aria-labelledby="title">
<section role="region" aria-labelledby="biography-title">

<!-- Descriptive alt text for images -->
<img alt="Sylvester Stallone and his wife, Jennifer Flavin, attending..."/>

<!-- Proper heading hierarchy -->
<h1 id="title">Sylvester Stallone</h1>
<h2 id="biography-title">Biography</h2>

<!-- Link with target and rel for security -->
<a id="tribute-link" target="_blank" rel="noopener noreferrer" href="...">Wikipedia</a>

<!-- Reduced motion support -->
@media (prefers-reduced-motion: reduce) {
  * { scroll-behavior: auto !important; }
}
```

---

## 📝 Content Structure

### Page Sections Reference

| Section | ID | Purpose | Key Elements |
|---------|----|---------|-------------|
| **Header** | — | Page title and metadata | `<h1 id="title">`, PWA meta tags |
| **Hero** | `#img-div` | Featured image with caption | `<img id="image">`, `<figcaption id="img-caption">` |
| **Biography** | `#tribute-info` | Main biographical content | Text block + inline Rocky image |
| **Additional** | — | Rambo era and versatility | Text block + full-width Rambo image |
| **Footer** | — | Attributions and credits | Links to collaborators and sources |

### Image Assets

| Image | Source | Purpose | Alt Text Strategy |
|-------|--------|---------|------------------|
| Hero | `glbimg.com` | Stallone at formal event | Describes subjects, clothing, expressions |
| Rocky inline | `pinimg.com` | Young Stallone as boxer | Describes pose, attire, era context |
| Rambo full-width | `imguol.com.br` | Stallone as Rambo in forest | Describes character, setting, mood |

> ⚠️ **Copyright Note**: External images are hotlinked. For production use, download and host images locally with proper licensing/permissions.

### PWA Configuration

**manifest.json** (simplified):
```json
{
  "name": "App",
  "icons": [
    { "src": "/android-icon-36x36.png", "sizes": "36x36", "type": "image/png" },
    { "src": "/android-icon-192x192.png", "sizes": "192x192", "type": "image/png" }
  ]
}
```

**browserconfig.xml**:
```xml
<browserconfig>
  <msapplication>
    <tile>
      <square70x70logo src="/ms-icon-70x70.png"/>
      <TileColor>#ffffff</TileColor>
    </tile>
  </msapplication>
</browserconfig>
```

> 🔧 **Setup Tip**: Update `manifest.json` `name` and `icons` paths to match your actual icon filenames and deployment path.

---

## 🔐 Environment Variables

**None required.** This is a fully static, client-side page with no backend, server-side rendering, or sensitive configuration.

> ⚠️ **Security Note**: External images are loaded via HTTP/HTTPS from third-party CDNs. Ensure:
> - Images are from trusted sources
> - Alt text is descriptive for accessibility
> - Consider hosting images locally for production to avoid broken links

---

## ⚙️ Available Scripts

| Command | Description | Use Case |
|---------|-------------|----------|
| `python3 -m http.server 8000` | Start local dev server | Test responsive layout and PWA features |
| `npx serve .` | Alternative local server (Node) | Quick preview with clean URLs |
| `open index.html` | Open file directly in browser | Fastest local testing |
| `git add . && git commit -m "msg"` | Stage and commit changes | Version control workflow |
| `git push origin main` | Deploy to GitHub Pages | Trigger auto-deploy (if configured) |

### GitHub Pages Deployment Workflow

```bash
# 1. Ensure you're on the main branch
git checkout main

# 2. Commit your changes
git add .
git commit -m "feat: improve biography section accessibility"

# 3. Push to trigger deployment
git push origin main

# 4. Wait ~1-2 minutes, then visit:
# https://tyxiel.github.io/tyxiel-tribute-page/
```

> 🔄 **Auto-deploy**: GitHub Pages rebuilds automatically on push to `main`. No build step required.

### PWA Installation (After Deployment)

Once deployed to HTTPS:

1. Open site in Chrome/Edge on Android or iOS
2. Look for "Add to Home Screen" prompt
3. Install → Page appears as standalone app with custom icon
4. Launch from home screen → Full-screen experience without browser UI

> ⚠️ **Note**: PWA features require HTTPS. Local testing via `http://localhost` may have limited support.

---

## 🧪 Testing

### Manual Testing Checklist

```markdown
## Layout & Responsiveness
- [ ] Page renders correctly on desktop (≥1200px)
- [ ] Biography section switches to column layout on mobile (≤768px)
- [ ] No horizontal scroll at any breakpoint
- [ ] Images scale proportionally without distortion

## Content & Accessibility
- [ ] All images have descriptive alt text
- [ ] Heading hierarchy is logical (h1 → h2)
- [ ] Links open in new tab with rel="noopener"
- [ ] Color contrast meets WCAG AA (text on background)

## PWA Features (HTTPS only)
- [ ] manifest.json loads without 404
- [ ] Browser shows "Install" prompt (Chrome/Edge)
- [ ] App launches in standalone mode after install
- [ ] Theme color matches browser UI

## Performance
- [ ] Page loads in <2s on 3G connection (Lighthouse)
- [ ] No layout shift after images load
- [ ] CSS is non-render-blocking
```

### Automated Testing (Optional)

```bash
# Install Lighthouse CI
npm install -g @lhci/cli

# Run audit
lhci autorun --collect.url=http://localhost:8000

# Check for:
# - Accessibility score ≥ 90
# - Best Practices score ≥ 90
# - PWA installable criteria met
```

### Cross-Browser Testing

Test in:
- Chrome/Edge (Chromium) — Full PWA support
- Firefox — Verify CSS variables and flexbox
- Safari (macOS/iOS) — Check Apple Touch icons
- Mobile Chrome/Safari — Test touch interactions and install prompt

---

## 🌍 Deployment

### GitHub Pages (Recommended)

**Automatic Setup**:
1. Go to repo **Settings** → **Pages**
2. Set **Source** to `Deploy from branch`
3. Select branch: `main`, folder: `/ (root)`
4. Save → Wait for deployment URL

**PWA Note**: GitHub Pages serves over HTTPS by default, enabling full PWA functionality.

### Fixing manifest.json Path

The current manifest references root-relative paths:
```json
"src": "/android-icon-36x36.png"
```

If deploying to a subpath (e.g., `username.github.io/tribute-page/`), update to relative paths:
```json
"src": "./img/icons/android-icon-36x36.png"
```

### Alternative: Netlify (Drag & Drop)

```bash
# 1. Build (no build step needed)
# 2. Drag the entire folder to Netlify Drop
# 3. Site is live instantly with HTTPS + PWA support
```

### Alternative: Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod

# PWA works automatically with HTTPS
```

### Custom Domain (Optional)

1. Add `CNAME` file to repo root:
   ```
   stallone.seudominio.com
   ```
2. Configure DNS with your registrar:
   ```
   Type: CNAME
   Name: stallone
   Value: tyxiel.github.io
   ```
3. Update `manifest.json` `start_url` if needed.

---

## 🔧 Troubleshooting

### ❌ Ícones PWA não aparecem / "Add to Home Screen" não funciona

**Cause**: Manifest paths incorrect or site not served over HTTPS.

**Solution**:
```json
// In manifest.json, use relative paths for subdirectory deploys:
{
  "icons": [
    {
      "src": "./img/icons/android-icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    }
  ]
}
```

Also ensure:
- Site is served via HTTPS (required for PWA install)
- All icon files exist at referenced paths
- `manifest.json` is accessible (no 404 in Network tab)

### ❌ Imagens externas não carregam

**Cause**: Hotlinked images may be blocked by CORS, removed, or rate-limited.

**Solution**:
```html
<!-- Download images and host locally -->
<img id="image" src="./img/hero-stallone.jpg" alt="..."/>

<!-- Or use a reliable CDN with proper CORS headers -->
<img src="https://reliable-cdn.com/image.jpg" crossorigin="anonymous" alt="..."/>
```

### ❌ Layout quebrado em mobile

**Cause**: Flexbox container doesn't wrap on small screens.

**Solution**: Add responsive breakpoint in `styles.css`:
```css
@media (max-width: 768px) {
  .biography-info {
    flex-direction: column;
    gap: 1.5rem;
  }
  .biography-info__text,
  .biography-info__img {
    width: 100%;
  }
}
```

### ❌ Scroll suave não funciona

**Cause**: Browser doesn't support `scroll-behavior` or user prefers reduced motion.

**Solution**:
```css
/* Fallback for older browsers */
html {
  scroll-behavior: smooth;
}

/* Respect user preference */
@media (prefers-reduced-motion: reduce) {
  * {
    scroll-behavior: auto !important;
    transition: none !important;
    animation: none !important;
  }
}
```

### ❌ HTML validation error: dir="lft"

**Cause**: Typo in `<html>` tag (`lft` is not a valid direction value).

**Solution**:
```html
<!-- Change line 2 in index.html: -->
<html dir="ltr" lang="en">
<!-- Valid values: "ltr" (left-to-right), "rtl" (right-to-left), "auto" -->
```

### ❌ Footer sobrepondo conteúdo em telas curtas

**Cause**: Footer has `position: relative; bottom: 0` which can cause overlap.

**Solution**: Use flexbox for sticky footer:
```css
body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

main {
  flex: 1;
}

footer {
  /* Remove position: relative; bottom: 0 */
  margin-top: auto;
}
```

---

## 🤝 Contributing

Contributions are welcome! This project follows the [GNU AGPL v3](LICENSE) license.

### How to Contribute

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/add-timeline-section`
3. Commit changes: `git commit -m 'feat: add career timeline with milestones'`
4. Push to branch: `git push origin feat/add-timeline-section`
5. Open a Pull Request

### Contribution Guidelines

- ✅ Keep changes focused and atomic (one feature/fix per PR)
- ✅ Test responsiveness manually in at least 2 browsers
- ✅ Follow existing code style:
  - HTML: Semantic tags, `id` selectors for CSS/JS hooks, descriptive alt text
  - CSS: No preprocessors, mobile-first approach, consistent spacing units
- ✅ Maintain accessibility: ARIA labels, heading hierarchy, color contrast
- ✅ Update this README if adding user-facing features

### Suggested Improvements

```markdown
✨ Content Enhancements
- [ ] Adicionar linha do tempo da carreira (década por década)
- [ ] Incluir citações famosas de Stallone em bloco destacado
- [ ] Adicionar seção "Filmografia" com lista expansível
- [ ] Incluir vídeo embed (YouTube) de cena icônica (com lazy loading)

🔧 Technical Improvements
- [ ] Corrigir typo: dir="lft" → dir="ltr"
- [ ] Extrair cores para CSS custom properties (:root)
- [ ] Adicionar meta tags Open Graph para compartilhamento social
- [ ] Implementar lazy loading para imagens fora do viewport
- [ ] Adicionar schema.org structured data (Person, Movie)

♿ Accessibility Enhancements
- [ ] Adicionar skip link para navegação por teclado
- [ ] Garantir foco visível em todos os links
- [ ] Testar com leitor de tela (NVDA, VoiceOver)
- [ ] Adicionar aria-label em links sem texto descritivo

🎨 Design Polish
- [ ] Animação sutil de fade-in para seções ao scroll
- [ ] Efeito hover em imagens com zoom suave
- [ ] Modo escuro via prefers-color-scheme
- [ ] Tipografia mais legível com font-size fluid (clamp)

🌐 PWA Enhancements
- [ ] Adicionar service worker para cache offline básico
- [ ] Configurar manifest.json com name, short_name, start_url
- [ ] Adicionar ícones missing (36x36, 48x48, etc.)
- [ ] Testar instalação em Android e iOS
```

### Reporting Issues

Use the [GitHub Issues](https://github.com/tyxiel/tyxiel-tribute-page/issues) tab with:

- 🐛 **Bug Report**: Steps to reproduce, browser/OS, section affected, expected vs actual
- 💡 **Feature Request**: Use case, proposed solution, priority (low/medium/high)
- ❓ **Question**: Clear description of what you're trying to achieve

---

## 📜 License

Distributed under the **GNU Affero General Public License v3.0**. See [`LICENSE`](LICENSE) for full text.

### What This Means

| You Can | You Must |
|---------|----------|
| ✅ Use commercially | 🔓 Disclose source code if modified and served over network |
| ✅ Modify and redistribute | 🔗 Provide source to network users of modified version |
| ✅ Patent use | 📝 Include license and copyright notices |
| ✅ Private use | 🔄 Share improvements under same license |

> ℹ️ **AGPL Specific**: If you host a modified version on a server and users interact with it over a network (e.g., deploy to Vercel), you **must** make the source code of your modifications available to those users.

### Quick Start with License Compliance

```bash
# When forking/modifying:
# 1. Keep LICENSE file intact
# 2. Add your copyright to modified files:
<!-- Copyright (C) 2026 Your Name -->

# 3. If deploying modified version publicly:
#    - Add a "Source" link in footer pointing to your fork
#    - Or include a modal with source code download option

# Example footer addition in index.html:
<footer>
  <p>
    Tribute page by <a href="https://github.com/Tyxiel">Tyxiel</a>
    | Modified by <a href="https://github.com/you">You</a>
    | <a href="https://github.com/you/tyxiel-tribute-page">Source Code</a>
    | License: AGPL-3.0
  </p>
</footer>
```

---

## 🙏 Acknowledgments

- [freeCodeCamp](https://www.freecodecamp.org/) — For the Responsive Web Design curriculum and certification project
- [Front-End Checklist](https://github.com/thedaviddias/Front-End-Checklist) — For best practices guidance
- [Pixabay](https://pixabay.com/) — For the page icon by [Alexey Marcov](https://pixabay.com/users/alexey_marcov-8003626/)
- [RealFaviconGenerator](https://realfavicongenerator.net/) — For PWA icon generation tooling
- [MDN Web Docs](https://developer.mozilla.org/) — For reliable HTML, CSS, and accessibility documentation

---

> 💡 **Pro Tip**: When creating tribute pages for public figures, always: (1) verify facts with reliable sources, (2) use images with proper licensing or fair use justification, and (3) include attribution for all external content. For educational projects like this, focus on demonstrating technical skills while respecting copyright and privacy.

*Built with ❤️ by [Tyxiel](https://github.com/Tyxiel)*
