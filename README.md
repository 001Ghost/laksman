# Laksman Sivaruban — Portfolio Digital Marketing

Site portfolio freelance — 4 pages HTML/CSS/JS vanilla, zéro dépendance.

## Structure

```
├── index.html       → Page d'accueil principale
├── services.html    → Services détaillés + stack outils + pricing
├── pov.html         → Point de vue / article "Le marketing à Paris, c'est cassé"
├── showreel.html    → Démo reel + roadmap vidéo
└── README.md
```

## Deploy sur Vercel via GitHub

1. Push ce repo sur GitHub
2. Aller sur [vercel.com](https://vercel.com) → "Add New Project"
3. Importer le repo GitHub
4. Framework Preset → **Other**
5. Build Command → laisser vide
6. Output Directory → laisser vide (ou `.`)
7. Deploy → done

Vercel sert les fichiers HTML statiques directement.

## Personnalisation avant mise en ligne

Rechercher et remplacer dans tous les fichiers :

| Placeholder | Remplacer par |
|---|---|
| `laksman@exemple.com` | Ton vrai email |
| `linkedin.com/in/laksman` | Ton vrai profil LinkedIn |
| `@laksman.digital` | Ton vrai compte Instagram |
| `xxxxxxxxx` | Ton numéro SIRET |
| `800€ / mois` | Tes vrais tarifs si différents |

## Domaine custom

Dans Vercel → Settings → Domains → ajouter `laksman.fr` ou `laksivaruban.com`

---

Built with HTML/CSS/JS — Fonts: Bebas Neue + DM Sans + Space Mono (Google Fonts)
