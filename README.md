# 📚 WackyFlip-DocsSite

**Public Developer Portal & Documentation Hub**

`WackyFlip-DocsSite` is the source repository for Wacky Flip’s official developer and contributor documentation portal. Built on **Docusaurus (React-based)**, it renders live documentation generated from the core [`WackyFlip-Docs`](https://github.com/wackyflipgame/WackyFlip-Docs) repository.

---

## 🎯 Purpose

This site provides **API references, integration guides, SDK documentation, and contribution guidelines** for developers, partners, and community creators building with or contributing to the [Wacky Flip](https://wackyflip.com) platform.

---

## ✨ Key Features

* 📖 **Live Documentation** – Automatically sourced and updated from `WackyFlip-Docs`.
* 🌐 **Static Site Generation** – Optimized for performance and SEO via Docusaurus.
* 🔍 **Search & Indexing** – Powered by Algolia DocSearch.
* 🎨 **Custom Theme** – Tailored to match the Wacky Flip brand style (UI kit support).
* 📜 **Multi-Version Docs** – Versioned releases of API/SDK docs for legacy and latest builds.
* 🌍 **Internationalization (i18n)** – Supports localized documentation (integrates `WackyFlip-Locale`).
* ⚙ **CI/CD Deployment** – Automatic builds via GitHub Actions and `WackyFlip-CI`.

---

## 🛠 Tech Stack

* **Frontend Framework**: Docusaurus v2 (React + MDX)
* **Styling**: TailwindCSS + WackyFlip-UIKit components
* **Search**: Algolia DocSearch
* **CI/CD**: GitHub Actions (deploy to GitHub Pages or custom domain)
* **Content Source**: Synced with [`WackyFlip-Docs`](https://github.com/wackyflipgame/WackyFlip-Docs)

---

## 📂 Repository Structure

```
WackyFlip-DocsSite/
├── docs/               # Markdown docs (synced with WackyFlip-Docs)
├── src/                # Custom React components & layouts
│   ├── components/
│   ├── pages/
│   └── theme/
├── static/             # Static assets (logos, favicons, etc.)
├── i18n/               # Translations and localization files
├── docusaurus.config.js# Site configuration
├── sidebars.js         # Sidebar structure for docs navigation
├── package.json
└── README.md
```

---

## 🚀 Quick Start

### 1. Clone & Install

```bash
git clone https://github.com/wackyflipgame/WackyFlip-DocsSite.git
cd WackyFlip-DocsSite
npm install
```

### 2. Start Local Server

```bash
npm run start
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser.

### 3. Build Static Site

```bash
npm run build
```

The static files will be in the `build/` directory.

---

## 🔗 Integration with `WackyFlip-Docs`

* The content is synced from the `WackyFlip-Docs` repo using a `docs-sync` script (via `npm run sync-docs`).
* Updates to `WackyFlip-Docs` automatically trigger a CI pipeline to rebuild this site.

---

## 🧪 Planned Features

* [ ] Interactive API Playground (Swagger UI or Redoc)
* [ ] Video tutorials & embedded demos
* [ ] Contributor leaderboard & dynamic changelog
* [ ] Dark/light mode toggle

---

## 🤝 Contributing

1. Make edits in `docs/` or `src/`.
2. Follow the Wacky Flip branding and style guidelines.
3. Run `npm run lint` before submitting a pull request.

Refer to [`CONTRIBUTING.md`](docs/contributing.md) for more details.

---

## 📜 License

MIT License © 2025 Wacky Flip Studios

---

**Your one-stop hub for building on Wacky Flip.**
*🌐 Powered by WackyFlip-DocsSite*
