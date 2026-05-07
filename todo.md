# Green Community 225 - Site ONG Full Stack

## Design Guidelines

### Design References
- Sites ONG modernes : WWF, Greenpeace Africa
- Style : Nature Minimaliste + Zen Garden + Tons Verts Naturels

### Color Palette (Zen Theme + Logo Green Community 225)
- Primary: hsl(24 10% 20%) — Brun foncé naturel
- Accent: hsl(75 15% 40%) — Vert olive naturel
- Background: hsl(40 12% 95%) — Beige crème
- Foreground: hsl(24 10% 15%) — Texte sombre
- Card: hsl(40 12% 96%) — Blanc cassé
- Muted: hsl(35 10% 90%) — Gris doux

### Typography
- Font Sans: 'Noto Sans SC', sans-serif
- Font Serif: 'Noto Serif SC', serif
- Headings: font-serif, bold
- Body: font-sans, regular

### Key Component Styles
- Buttons: bg-primary text-primary-foreground, rounded-sm
- Cards: bg-card border border-border shadow-sm rounded-sm
- Nav: sticky top, bg-background/95 backdrop-blur
- Sections: py-16 md:py-24

### Images Used (CDN URLs)
- Hero: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/eaffed78-555a-4c36-a82a-ca76581a4c63.png
- Green Arts: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/0e07478b-1953-4504-8b86-dc7e9d8b2e1c.png
- Potager: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/5377938c-ca1b-46d0-9104-ebee2a352ace.png
- Green Action: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/6741c10e-bd59-47cf-a82b-806b8be23f81.png
- Avatar Woman: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/93bfe7d5-1a96-42bd-842e-487bee85894d.png
- Avatar Man: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/0aeaa204-6c02-44b0-9d26-9cf1f1e6fef2.png
- Avatar Teacher: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/bcb40305-9cb0-4578-b30a-9c849cd84cb3.png
- Biodiversity: https://mgx-backend-cdn.metadl.com/generate/images/1056504/2026-04-07/318b6620-65dd-41cd-97bb-80561a385984.png

---

## Development Tasks

### Files to Create
1. `src/index.css` — Zen theme CSS variables + Google Fonts
2. `tailwind.config.ts` — Zen theme font config
3. `src/lib/api.ts` — Web SDK client setup
4. `src/components/Navbar.tsx` — Navigation responsive avec logo
5. `src/components/Footer.tsx` — Footer avec contacts et liens
6. `src/pages/Index.tsx` — Page d'accueil complète :
   - Hero section (image de fond, slogan, CTA)
   - Section Activités (Green Arts, Potager, Green Action)
   - Section Statistiques (+500 jeunes, projets, etc.)
   - Section Témoignages (depuis DB)
   - Section Galerie aperçu
   - Section Don rapide
   - Section Contact
7. `src/pages/Projets.tsx` — Page projets depuis DB
8. `src/pages/Don.tsx` — Page formulaire de don
9. `src/pages/Admin.tsx` — Dashboard admin (login + gestion)
10. `src/App.tsx` — Router avec toutes les routes