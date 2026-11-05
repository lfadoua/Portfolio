# Fadoua Lachhab — Creative Interactive Portfolio v2

Portfolio bilingue FR/EN (HTML, CSS, JavaScript), prêt pour un hébergement statique.

## Utilisation

1. **Extraire complètement le ZIP** dans un dossier local. Ne pas ouvrir index.html à l’intérieur de l’archive.
2. Vérifier que `index.html`, `styles.css` et `script.js` se trouvent **dans le même dossier**.
3. Ouvrir `index.html` dans Chrome ou utiliser un serveur local (`python -m http.server 8000`).
4. Pour GitHub Pages, placer ces trois fichiers à la racine du dépôt (ou dans le dossier de publication configuré).

## Contenu

- Bento projects avec détails, catégories et recherche scientifique.
- Expertise IA, ML, Data Science, Operations Research.
- Timeline de formation et parcours.
- AI Lab pédagogique : courbes synthétiques, **pas des résultats du PFE**.
- Français / English, animations légères et respect de reduced-motion.
- Contact email + LinkedIn uniquement. Lien GitHub du projet Data Job Market Intelligence ; aucun CV.

## À vérifier avant publication

Vérifier toutes les informations biographiques, métriques, descriptions de projets et statuts des publications. Remplacer les visuels illustratifs par des captures réelles quand elles sont disponibles.

## Correctif V3
Les sections sont désormais visibles par défaut, même si JavaScript ou IntersectionObserver échoue. Extraire le ZIP avant ouverture de index.html.


V4: SVG graph has default paths in HTML and independent inline scenario handlers; curves appear even if the main JS fails.


## Ajout du 5 novembre 2026 — Data Job Market Intelligence

- Nouvelle fiche bilingue FR/EN, capture réelle et étude de cas détaillée.
- Code : https://github.com/lfadoua/Data-Projects
- Filtres : Tous, Data & SQL, GenAI et Software affichent la nouvelle fiche.
- Les 12 217 annonces et 30 955 chunks V2 sont des comptes documentés du projet.
  Le corpus a été collecté du 12 au 17 janvier 2024 ; ce n’est pas un flux actuel.
- Génération Ollama/Qwen optionnelle ; aucune API ni base de données n’est incluse
  dans ce portfolio statique. Le bouton GitHub ouvre le code, pas une démo hébergée.
- `assets/data-job-market-intelligence.jpg` doit rester avec les trois fichiers
  HTML/CSS/JS. Extraire tout le ZIP avant d’ouvrir `index.html`.
- Correction ciblée d’un accès à `.linkedin-note` absent, qui interrompait le JS.

Le ZIP d’origine et les autres fiches de projets sont conservés.
