
# Monastery360

**Monastery360** is a 360° interactive virtual tour web application that allows users to explore monastery environments and heritage spaces through immersive panoramic scenes. The project delivers smooth navigation, visual interactivity, and support for rich user experience using modern frontend technologies. :contentReference[oaicite:1]{index=1}

---

## 🧠 Project Overview

Monastery360 was originally forked and adapted as a template for creating a rich virtual-exploration experience. It delivers:

- 📍 360° panoramic viewer
- 🧭 Smooth navigation controls
- 🎨 Immersive UI/UX design
- 🌐 Web-first, client-side application
- ⚡ Fast performance with Vite and modern JavaScript ecosystem

This repository serves as the implementation of that idea with a modern frontend stack. :contentReference[oaicite:2]{index=2}

---

## 🚀 Features

✅ Interactive 360° scene rendering  
✅ Navigation between image panoramas  
✅ Responsive and accessible UI  
✅ Configurable tour setup (via data files)  
✅ Lightweight and fast build using Vite  

---

## 🗂️ Repository Structure

```

monastery360/
├─ public/                  # Static assets (panorama images, icons, etc.)
├─ src/                     # Frontend application source
├─ .gitignore
├─ CHANGES.md
├─ README.md                # This file
├─ package.json             # Dependencies & scripts
├─ postcss.config.js
├─ tailwind.config.ts
├─ tsconfig*.json
├─ vite.config.ts
└─ THEME_VARS.css

````
_(Structure reflected from the repo directory)_ :contentReference[oaicite:3]{index=3}

---

## 🛠️ Tech Stack

This project is built with:

| Category | Technology |
|----------|------------|
| Build Tool | Vite |
| UI Library | React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Package Manager | npm / Bun |

_(Inferred from config files and languages in repo)_ :contentReference[oaicite:4]{index=4}

---

## 📦 Prerequisites

Before running the project, make sure you have installed:

- Node.js (v16+ recommended)
- npm or your preferred package manager (Bun is also supported)

---

## 💻 Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Mahi11313/monastery360.git
cd monastery360
````

### 2. Install Dependencies

Using npm:

```bash
npm install
```

Or using Bun:

```bash
bun install
```

---

## 🚀 Development

Start the development server with:

```bash
npm run dev
```

Open the browser and visit:

```
http://localhost:3000
```

You should see the Monastery360 app live with hot reloading enabled.

---

## 🧪 Build for Production

To create a production build:

```bash
npm run build
```

This outputs an optimized `dist/` folder which you can serve using any static file host or deploy to platforms like Vercel, Netlify, GitHub Pages, etc.

---

## 🛠️ Customizing the Tour

To change or add new 360° scenes:

1. Add your panoramic images (equirectangular format) to the `public/` directory.
2. Update configuration files or JSON lists (if present in the `src/` folder) that define scene data.
3. Customize navigation or controls inside source files under `src/`.

---

## 📝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "feature description"`)
4. Push to your fork (`git push origin feature-name`)
5. Open a Pull Request

---

