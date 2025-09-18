[English Version](README.en.md)

# 🌿 Planificateur de Jardin Visuel

**Donnez vie au jardin de vos rêves !** Cette application web vous permet de concevoir votre potager ou vos massifs de manière visuelle, simple et intuitive. Entièrement "front-end" (HTML, CSS, JavaScript vanilla), elle fonctionne directement dans votre navigateur, sans installation ni connexion internet. Un seul fichier `html` pour une portabilité maximale.

![Aperçu du planificateur de jardin](URL_DE_VOTRE_SCREENSHOT.png)
*(Pensez à remplacer cette ligne par une vraie capture d'écran de votre projet !)*

## 🚀 Accès Direct

[**Lancer le Planificateur de Jardin (Démo Live)**](https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/planificateur_jardin.html)
*(Ce lien fonctionnera une fois l'application hébergée, par exemple avec GitHub Pages. Voir les instructions à la fin.)*

## ✨ Fonctionnalités

- **Chargement d'Image de Fond** : Utilisez un plan satellite, une photo de drone ou un plan cadastral comme base pour votre jardin.
- **Mise à l'Échelle Précise** : Définissez une échelle en traçant une ligne sur une distance connue (ex: un mur de 10m). Une ligne de mesure visuelle vous guide pendant le tracé.
- **Plantes Personnalisables** : Ajoutez vos propres types de plantes avec un nom, une couleur, un emoji et l'espacement recommandé.
- **Actions sur les Plantes** :
    - **Ajouter** : Sélectionnez un type de plante et cliquez sur le plan pour l'ajouter.
    - **Déplacer** : Activez le mode "Déplacer" pour bouger les plantes par glisser-déposer (`drag & drop`).
    - **Supprimer** : Activez le mode "Supprimer" pour effacer une plante d'un simple clic, ou utilisez le clic droit comme raccourci à tout moment.
- **Représentation Visuelle** : Chaque plante est représentée par un cercle translucide correspondant à son encombrement (diamètre = espacement), avec son emoji au centre.
- **Placement en Grille Automatique** : Placez des dizaines de plantes parfaitement alignées en un seul clic en définissant un nombre de lignes et de colonnes.
- **Planification de l'Irrigation** : Dessinez votre système de goutte-à-goutte point par point, créez des ramifications et obtenez la longueur totale de tuyau nécessaire en temps réel.
- **Dessin des Allées** : Tracez les chemins et allées de votre jardin et obtenez leur longueur totale.
- **Calcul de Paillage** : Délimitez des zones polygonales pour calculer le volume de paillage (en litres) nécessaire en fonction de l'épaisseur souhaitée.
- **Compteurs Intégrés** : Gardez un œil sur le nombre total de plantes et le compte pour chaque variété.
- **Sauvegarde Locale** : Sauvegardez et chargez l'intégralité de votre plan (plantes, irrigation, échelle, etc.) directement dans votre navigateur via `localStorage`.
- **Export en Image** : Exportez votre plan final (image de fond + tous les éléments dessinés) en tant que fichier PNG.
- **Zéro Dépendance** : Construit avec du HTML5, CSS et JavaScript pur. Pas de framework, pas de librairie, pas de compilation. Léger, rapide et facile à modifier.

## 🚀 Comment l'utiliser

C'est incroyablement simple :

1.  Téléchargez le fichier `planificateur_jardin.html`.
2.  Ouvrez-le avec n'importe quel navigateur web moderne (Firefox, Chrome, Edge, etc.).
3.  Commencez à planifier !

## 🏗️ Structure du code

Le projet est volontairement contenu dans un seul fichier pour une portabilité maximale. La structure interne est la suivante :

- **`<head>`** : Contient le bloc `<style>` avec tout le CSS nécessaire pour l'interface.
- **`<body>`** : Contient la structure HTML du panneau de contrôle (`#controls`) et de la zone de dessin (`#canvas-container`).
- **`<script>`** : Contient tout le code JavaScript qui donne vie à l'application. La logique est commentée pour faciliter la compréhension et les modifications.

## 💡 Pistes d'amélioration

Ce projet peut encore évoluer ! Voici quelques idées :

- [ ] Rotation des grilles de placement.
- [ ] Une bibliothèque de plantes pré-configurées (tomates, salades, etc.).
- [ ] Une fonction Annuler/Rétablir (Undo/Redo).
- [ ] Export et import du plan en fichier `.json` pour le partage.

N'hésitez pas à forker le projet et à proposer vos propres améliorations !
