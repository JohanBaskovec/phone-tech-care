# Phone Tech Care – site vitrine

Nouvelle version du site https://phonetechcare.fr/ (réparation iPhone & Android à Épernay).

Site statique, sans dépendance ni build :

- `index.html` – page unique (accueil, services, fonctionnement, atouts, marques, FAQ, contact)
- `styles.css` – styles (responsive, animations respectant `prefers-reduced-motion`)
- `script.js` – menu mobile, FAQ, apparition au défilement
- `assets/logo.svg` – nouveau logo (téléphone + ligne de pouls « care »), aussi utilisé comme favicon

Aperçu local : ouvrir `index.html` dans un navigateur, ou `python3 -m http.server`.
Mise en ligne : copier ces fichiers à la racine de l'hébergement.
