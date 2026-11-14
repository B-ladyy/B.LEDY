# B.LADI

Jeu de quiz à jouer à voix haute entre deux équipes (français, English, العربية).
Une équipe lit la question et valide, l'autre cite 9 réponses en 60 secondes. Attention à la bombe (-5) !

- Un seul fichier : `index.html` (aucune dépendance, fonctionne hors ligne)
- 14 thèmes, jokers (+2, ×2, ?), scores par équipe, revanche

## Publier sur GitHub Pages
1. Crée un dépôt GitHub (ex. `blandi`) et envoie-y ces fichiers.
2. Settings > Pages > Source : « GitHub Actions » (le workflow `.github/workflows/pages.yml` déploie le site).
3. Le jeu sera disponible sur `https://<ton-pseudo>.github.io/blandi/`.

Ajouter des quiz : dans `index.html`, ajoute une ligne `["Thème","titre sans « Citez 9 »","Nom:points,..."]` (9 bonnes réponses à 1, 2 ou 5 points, 1 bombe à -5).
