# PGN Merger — GitHub Pages

Version web statique : aucun Python, aucune installation, aucun terminal pour l'utilisation.

## Mise en ligne avec GitHub Pages (depuis le navigateur)

1. Connecte-toi à https://github.com
2. Clique sur **New repository**.
3. Nomme-le `pgn-merger` et choisis **Public**.
4. Clique sur **Create repository**.
5. Dans le dépôt, clique sur **Add file → Upload files**.
6. Glisse-dépose le fichier `index.html` fourni dans ce dossier.
7. Clique sur **Commit changes**.
8. Ouvre **Settings → Pages**.
9. Dans **Build and deployment**, choisis **Deploy from a branch**.
10. Sélectionne `main` et `/ (root)`, puis **Save**.
11. Attends quelques minutes : GitHub affichera l'adresse de ton site dans la section Pages.

## Important
Cette version 0.1 est un prototype de fusion textuelle de coups PGN. Elle fusionne les préfixes identiques dans l'arbre, sans fusionner les transpositions. Elle ne valide pas encore la légalité des coups sur l'échiquier et ne gère pas encore parfaitement tous les cas PGN avancés (annotations complexes, commentaires structurés, FEN de départ, variantes imbriquées atypiques). Teste les exports avant de les utiliser comme base de données définitive.
