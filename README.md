# CHOK'BÉTON — Générateur de Devis

Application web PWA de génération de devis pour CHOK'BÉTON.

## Fonctionnalités

- 🤖 Interprétation IA de notes de chantier libres
- 📝 Formulaire guidé de saisie des prestations
- 📄 Aperçu devis au format A4 imprimable / PDF
- 📊 Export CSV compatible Excel
- 📱 Installable sur iPhone (PWA)

## Stack

- React 19 + Vite
- vite-plugin-pwa (Service Worker, manifest)
- Déployé sur Netlify

## Développement local

```bash
npm install
npm run dev
```

## Déploiement Netlify

Connecter ce repo GitHub à Netlify :
- Build command : `npm run build`
- Publish directory : `dist`

Le déploiement est automatique à chaque push sur `main`.

## Structure

```
src/
└── App.jsx       # Application complète (composants + logique + styles)
public/
├── logo.jpg      # Logo CHOK'BÉTON
└── icons/        # Icônes PWA (192, 512, apple-touch)
```
