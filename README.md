# 🧱 React + Vite + Tailwind Template

Plantilla base para iniciar proyectos web modernos con **React + Vite +
TailwindCSS (v4)**.  
Incluye modo oscuro y estructura limpia para escalar fácilmente.

---

## 🚀 Requisitos

- **Node.js ≥ 24**
- **Yarn**

---

## ⚙️ Instalación

```bash
git clone https://github.com/Awerito/landing-template.git
cd landing-template
yarn && yarn install
```

---

## 🧩 Estructura

```
.
├── src
│   ├── components
│   │   ├── Button.jsx
│   │   ├── Card.jsx
│   │   ├── Input.jsx
│   │   └── Navbar.jsx
│   ├── sections
│   │   ├── Contact.jsx
│   │   ├── Features.jsx
│   │   ├── Footer.jsx
│   │   └── Hero.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── vite.config.js
└── yarn.lock
```

* **components/** → piezas reutilizables (botones, tarjetas, inputs).
* **sections/** → secciones principales de la landing.
* **App.jsx** → compone toda la página.

---

## 💡 Desarrollo

```bash
yarn dev
```

Aplicación disponible en `http://localhost:5173`

---

## 🏗️ Build y preview

```bash
yarn build
yarn preview
```

Genera el directorio `dist/` listo para subir a cualquier hosting estático
(Netlify, Vercel, Dokploy, etc.).
