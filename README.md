# 🌿 Planificateur de Jardin Visuel

Une application web "front-end" pure (HTML, CSS, JavaScript vanilla) pour planifier visuellement un potager ou un jardin. Cet outil fonctionne entièrement en local dans votre navigateur, ne nécessite aucune installation ni connexion internet, et se compose d'un unique fichier `html`.

![Aperçu du planificateur de jardin](URL_DE_VOTRE_SCREENSHOT.png)
*(Pensez à remplacer cette ligne par une vraie capture d'écran de votre projet !)*

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
- **Compteurs Intégrés** : Gardez un œil sur le nombre total de plantes et le compte pour chaque variété.
- **Sauvegarde Locale** : Sauvegardez et chargez l'intégralité de votre plan (plantes, irrigation, échelle) directement dans votre navigateur via `localStorage`.
- **Export en Image** : Exportez votre plan final (image de fond + plantes + irrigation) en tant que fichier PNG.
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

- [ ] Gestion de "zones" (carrés potagers, massifs) avec des polygones.
- [ ] Rotation des grilles de placement.
- [ ] Une bibliothèque de plantes pré-configurées (tomates, salades, etc.).
- [ ] Une fonction Annuler/Rétablir (Undo/Redo).
- [ ] Export et import du plan en fichier `.json` pour le partage.

N'hésitez pas à forker le projet et à proposer vos propres améliorations !
