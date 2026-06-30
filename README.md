# Green Data Center Showcase Website

A highly responsive, multi-page static website designed to explain, contextualize, and highlight the significance of **Green Data Centers** (eco-friendly data storage centers) in the modern digital age.

This project showcases a clean, responsive layout built using semantic HTML5, modern Vanilla CSS (with glassmorphism styling), and Tailwind CSS utilities.

---

## 🎨 Design & Aesthetics

* **Glassmorphic HUD Interface**: Features cards with `backdrop-filter` blur effects, semi-transparent slate overlays, and subtle glowing emerald-green borders.
* **Futuristic Palette**: Employs deep slates (`#0F172A`), crisp off-whites (`#F1F5F9`), and glowing emerald/mint gradients (`#34D399` to `#059669`) for interactive elements.
* **Modern Typography**: Imports and applies the elegant **Outfit** geometric sans-serif typeface from Google Fonts.
* **Micro-Animations**: Smooth transitions on hover for cards, images, and page navigation buttons.

---

## 🏗️ Project Structure & Pages

```
data-center-html-page/
├── src/
│   ├── img/            # Static assets and icons (URL-safe names)
│   ├── styles/
│   │   └── global.css  # Custom style rules and glassmorphism design tokens
│   ├── index.html      # Home: Introduction to data storage hubs
│   ├── datacenter.html # Data Centers: Core definition and Tier system (1-4)
│   ├── greendatacenter.html # Green DC: Efficiency, cost savings, and certifications
│   ├── vantagens.html  # Advantages: Cost reduction, efficiency, carbon minimization
│   └── saibamais.html  # Read More: Curated articles and recent industry news
├── .gitignore          # IDE configuration ignores (VS Code, IntelliJ)
└── README.md
```

---

## 🚀 Key Improvements & Best Practices

1. **SEO Optimization**:
   * Added relevant meta descriptions and viewport settings on every page.
   * Semantic HTML structure (logical `h1`, `h2`, `main`, and `nav` hierarchies).
2. **Active Page Highlights**: Sincronized navigation tab underlines matching the user's active page.
3. **Asset Organization**: Renamed files containing special Portuguese characters (e.g. `reduçãodeCarbono.png` to `reducaoDeCarbono.png`) to ensure URL safety on web servers.
4. **Responsive Layouts**: Flexible CSS grids that collapse on mobile/tablet screens.
5. **No Broken Links**: Set external resources in `saibamais.html` to open in new tabs safely via `target="_blank" rel="noopener noreferrer"`.

---

## ⚡ How to Run

Simply open `src/index.html` in any web browser to view the live site. Alternatively, serve it locally using any static web server extension (e.g., Live Server in VS Code).
