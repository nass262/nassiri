# Portfolio Professionnel — Badr Eddine Nassiri

Portfolio personnel moderne, responsive et accessible (thème sombre bleu nuit / anthracite `#060a14` avec accents cyan `#06b6d4` et bleu électrique `#3b82f6`), conçu pour **Badr Eddine Nassiri — Data Scientist | AI Engineer**.

## Structure du projet

```text
portfolio-badr-eddine-nassiri/
├── index.html                        # Code principal du portfolio (HTML5 sémantique, Tailwind CSS, JS modulaire)
├── README.md                         # Documentation d'installation, de personnalisation et de déploiement
└── assets/
    ├── CV_Badr_Eddine_Nassiri.pdf    # Véritable CV PDF officiel
    └── images/
        ├── proj1_data_analyst.jpg    # Illustration Projet 1 — AI Data Analyst Multi-Agent
        ├── proj2_multimodal_rag.jpg  # Illustration Projet 2 — Advanced Multimodal RAG
        ├── proj3_travel_planner.jpg  # Illustration Projet 3 — AI Travel Planner Multi-Agent
        ├── proj4_data_quality.jpg    # Illustration Projet 4 — Data Quality Pipeline
        └── proj5_traffic_signs.jpg   # Illustration Projet 5 — Reconnaissance des panneaux de signalisation
```

## Installation et utilisation en local

Aucune étape de compilation lourde n'est requise :

1. Décompressez l'archive `portfolio_badr_eddine_nassiri_source.zip`.
2. Ouvrez directement `index.html` dans votre navigateur ou lancez un serveur local léger :
   ```bash
   python3 -m http.server 8000
   ```
3. Rendez-vous sur `http://localhost:8000`.

## Personnalisation rapide (URLs GitHub, Démonstrations et Certifications)

Pour respecter strictement l'intégrité de votre profil, aucun lien non fourni dans votre CV n'a été inventé. Des emplacements clairement identifiés ont été prévus :

- **Lien GitHub principal** : recherchez `btn-github-info` ou `[URL GitHub à renseigner]` dans `index.html` pour remplacer par votre URL `https://github.com/<votre-profil>`.
- **Dépôts GitHub et démonstrations des projets** : dans l'objet JavaScript `PROJECTS_DATA` (en bas de `index.html`), modifiez la propriété `linksNote` de chaque projet (`proj-1` à `proj-5`).
- **Liens de vérification des certifications** : dans la section `#certifications`, remplacez les badges `Vérification : URL à renseigner` par des balises `<a href="...">Vérifier le certificat</a>` pointant vers Credly / Oracle / Coursera.

## Déploiement sur GitHub Pages / Vercel / Netlify

- **GitHub Pages** : poussez le contenu de ce dossier sur un dépôt `<votre-username>.github.io` (branche `main`), puis activez GitHub Pages dans *Settings > Pages*.
- **Vercel / Netlify** : glissez-déposez simplement le dossier dans l'interface de déploiement statique.
