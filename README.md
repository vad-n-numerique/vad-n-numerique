<div align="center">

<img src="public/logo.png" alt="VAD-N Numérique" width="320" />

<br />

# VAD-N Numérique

**Développement d'applications · Logiciels · Jeux vidéo**

[![Site en ligne](https://img.shields.io/website?url=https%3A%2F%2Fvad-n.fr&label=vad-n.fr&style=flat-square&color=4F46E5)](https://vad-n.fr)
[![Astro](https://img.shields.io/badge/Astro-6.x-FF5D01?style=flat-square&logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vercel](https://img.shields.io/badge/Déployé_sur-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com)

</div>

---

## À propos

Site vitrine de **VAD-N Numérique**, entreprise indépendante de développement numérique spécialisée dans :

- **Applications** web et mobiles
- **Logiciels** desktop et outils métiers
- **Jeux vidéo** 2D / 3D

---

## Stack technique

| Technologie | Rôle |
|-------------|------|
| [Astro 6.x](https://astro.build) | Framework SSG — zéro JS par défaut |
| [Tailwind CSS 4.x](https://tailwindcss.com) | Styles utilitaires via plugin Vite |
| [TypeScript 5.x](https://www.typescriptlang.org) | Typage strict |
| [Vercel](https://vercel.com) | Hébergement, CDN, HTTPS automatique |

---

## Structure du projet

```
src/
├── components/
│   ├── layout/     # Header, Footer
│   ├── sections/   # Hero, Services
│   └── ui/         # Button, Card, SectionTitle, Badge
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   ├── index.astro
│   └── mentions-legales.astro
└── styles/
    └── global.css
```

---

## Développement local

```bash
# Installer les dépendances
npm install

# Lancer le serveur de dev (http://localhost:4321)
npm run dev

# Vérifier les types
npx astro check

# Build de production
npm run build

# Prévisualiser le build
npm run preview
```

---

## Déploiement

Le site est déployé automatiquement sur **Vercel** à chaque push sur `main`.

```bash
git push origin main   # → déploiement automatique
```

Domaine : **[vad-n.fr](https://vad-n.fr)**

---

## Fonctionnalités

- Réseau de particules interactif (canvas)
- Curseur lumineux custom (desktop)
- Effet typewriter sur la tagline
- Tilt 3D sur les cartes au survol
- Animations fade-in au scroll
- SEO complet (meta, Open Graph, JSON-LD, sitemap)
- PWA-ready (manifest, theme-color, apple-touch-icon)
- Score Lighthouse 90+
- 100% responsive

---

<div align="center">

© 2026 VAD-N Numérique · [vad-n.fr](https://vad-n.fr)

</div>
