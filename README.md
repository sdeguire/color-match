# Ma garde-robe couleur

Petite app web (PWA) : ajoute la photo d'un vêtement, l'app détecte sa couleur et la compare à ta palette personnelle. Tout reste dans ton téléphone (IndexedDB), sans compte ni serveur.

## Mise en ligne sur GitHub Pages
1. Crée un dépôt (`color-match`) et ajoutes-y tous les fichiers de ce dossier, à la racine.
2. Settings > Pages > Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`.
3. L'app sera à `https://sdeguire.github.io/color-match/`.

## Sur iPhone
Ouvre l'adresse dans Safari > Partager > « Sur l'écran d'accueil ».

## Mises à jour
Après une modification, change `VERSION` dans `sw.js` pour forcer le rafraîchissement du cache.

## Sauvegarde
Les données vivent dans le navigateur du téléphone. Utilise « Exporter une copie » de temps en temps (fichier .json avec les photos).
