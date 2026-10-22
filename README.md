# Séance 7 — Analyse de documents techniques

Site pédagogique statique, responsive et autonome pour GitHub Pages.

## Contenu
- Cours structuré sur quatre types de documents
- Méthode d'analyse en six étapes
- Étude de cas fictive NOVALYS et pistes de correction
- Fiche d'analyse interactive
- Export du livrable en `.txt`
- Quiz corrigé automatiquement
- Impression / enregistrement PDF via le navigateur
- Aucun backend, aucune dépendance externe, aucune collecte de données

## Déploiement sur GitHub Pages
1. Créez un dépôt GitHub, par exemple `seance-7-analyse-documents`.
2. Ajoutez `index.html` et `README.md` à la racine du dépôt.
3. Dans **Settings → Pages**, sélectionnez **Deploy from a branch**.
4. Choisissez la branche `main` et le dossier `/(root)`, puis enregistrez.
5. Attendez la fin du déploiement. L'URL sera de la forme `https://VOTRE-PSEUDO.github.io/seance-7-analyse-documents/`.

Alternative avec Git :
```bash
git init
git add index.html README.md
git commit -m "Créer le site pédagogique séance 7"
git branch -M main
git remote add origin https://github.com/VOTRE-PSEUDO/seance-7-analyse-documents.git
git push -u origin main
```

Puis activez GitHub Pages dans les paramètres du dépôt.
