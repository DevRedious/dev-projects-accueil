# Dev project's — Accueil

Page d'accueil immersive **« Dev project's »** — thème *circuit-board organique* (bois + circuits + lumière néon), copie en français.

Implémentée en HTML/CSS/JS **autonome** (vanilla, sans build ni dépendance) à partir d'un handoff Claude Design.

## Aperçu

🌐 **[devredious.github.io/dev-projects-accueil](https://devredious.github.io/dev-projects-accueil/)**

## Contenu

- Fond circuit-board procédural (dégradé sombre, trame animée, halo « respirant », spores, vignette)
- 6 boutons-branches néon avec balancement de feuilles, courant lumineux sur les traces et glow par bouton
- Apparition en grandissant décalée, états de survol, `prefers-reduced-motion` respecté

## Lancer en local

Aucun build. Ouvrir `index.html` dans un navigateur, ou :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

Seules les Google Fonts sont chargées à distance ; tout le reste est local.
