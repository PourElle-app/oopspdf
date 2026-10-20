# OopsPDF

OopsPDF est une maquette web de traitement de PDF. Elle fonctionne côté navigateur et ne nécessite pas de compte utilisateur.

## Fonctions présentes

- Fusionner des PDF et extraire des pages
- Convertir un PDF en images JPG ou PNG
- Créer un PDF à partir d’images JPG/PNG
- Compresser un PDF (optimisation sans perte ou conversion visuelle)
- Réorganiser, tourner ou supprimer des pages
- Ajouter une numérotation, un filigrane ou du texte
- Redimensionner les pages
- Extraire le texte d’un PDF
- Séparer un PDF page par page dans un ZIP

## Essai local

Ouvrir `index.html` dans un navigateur moderne avec une connexion Internet. Les bibliothèques utilisées par la page sont chargées depuis jsDelivr : PDF-Lib, PDF.js et JSZip.

Les fichiers sélectionnés sont traités dans le navigateur par cette maquette. Les bibliothèques JavaScript, elles, sont téléchargées depuis le CDN. Les PDF protégés, endommagés, très volumineux ou complexes peuvent ne pas être pris en charge. La compression visuelle rasterise les pages et peut retirer le texte sélectionnable, les liens et les formulaires.

## Publication avec GitHub Pages

1. Créer un dépôt GitHub public, par exemple `oopspdf`.
2. Déposer `index.html` et `README.md` à la racine du dépôt.
3. Ouvrir **Settings → Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**, puis la branche `main` et le dossier `/(root)`.
5. Enregistrer, attendre la fin du déploiement, puis ouvrir l’URL fournie par GitHub Pages.

GitHub Pages publie des fichiers statiques HTML/CSS/JavaScript. Les conditions et limites du service sont documentées par GitHub :
- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## État du projet

Version de test. Les traitements ont passé des essais sur des PDF simples. La vérification dans plusieurs navigateurs et sur des documents complexes reste nécessaire avant de présenter le service comme prêt pour tous les usages.
