---
title: Guide de cartographie bathymétrique
nav_order: 1
parent: Maps
lang: fr
page_id: maps-bathymetric
permalink: "/Maps/Bathymetric Depth Maps.html"
---

# Guide de cartographie bathymétrique

## Table des matières

- [Introduction](#introduction)
- [Qu'est-ce que la cartographie bathymétrique ?](#quest-ce-que-la-cartographie-bathymetrique-)
- [Configuration requise](#configuration-requise)
- [Créer votre première carte de profondeur](#creer-votre-premiere-carte-de-profondeur)
- [Comprendre la vue 3D](#comprendre-la-vue-3d)
- [Problèmes connus et limitations](#problemes-connus-et-limitations)
- [Explication des paramètres de cartographie](#explication-des-parametres-de-cartographie)
- [Gestion de vos cartes](#gestion-de-vos-cartes)
- [Conseils pour une meilleure cartographie](#conseils-pour-une-meilleure-cartographie)
- [Dépannage](#depannage)

## Introduction

Bienvenue dans la fonctionnalité de cartographie de votre application Baitboats ! Ce guide vous aidera à comprendre comment créer des cartes bathymétriques détaillées de vos zones de pêche. Les cartes bathymétriques montrent le relief sous-marin, y compris les profondeurs et les contours, ce qui peut vous aider à trouver les meilleurs coins de pêche.

## Qu'est-ce que la cartographie bathymétrique ?

La cartographie bathymétrique est le processus de mesure et de cartographie des profondeurs des plans d'eau. En termes simples, c'est comme créer une carte topographique du paysage sous-marin. Ces cartes peuvent révéler :

- Des trous profonds où les poissons pourraient se cacher
- Des crêtes sous-marines et des cassures
- Des zones peu profondes à éviter
- Des changements de profondeur qui attirent différentes espèces de poissons

## Configuration requise

- Les cartes 3D nécessitent Android 13 ou une version plus récente.
- Un bateau amorceur avec un sonar compatible :
    - Wi-Fish
    - Vexilar
    - Pulse
    - Horizon

## Créer votre première carte de profondeur

### Étape 1 : Préparer votre équipement

1. Assurez-vous que votre bateau amorceur est correctement connecté à l'application.
2. Assurez-vous que votre sonar fonctionne correctement :
    - **Wi-Fish** : Gardez l'application Wi-Fish ouverte pendant la cartographie.
    - **Vexilar** : Fermez l'application Vexilar pendant la cartographie.
    - **Pulse** : Gardez ouverte pendant la cartographie et assurez-vous que le transfert NMEA est activé et réglé sur le port 3500.
    - **Horizon** : Pour l'instant : fermez pendant la cartographie, ils travaillent sur une mise à jour logicielle pour corriger cela.

### Étape 2 : Activer la cartographie

1. Mettez d'abord le bateau à l'eau.
2. Allez dans l'onglet Settings (icône d'engrenage).
3. Trouvez la section "Depth Mapping".
4. Activez l'option "Enable mapping".
5. Assurez-vous que "Show depth map" est également activé.

### Étape 3 : Collecter des points de profondeur

Pour créer une carte détaillée, vous devez collecter des relevés de profondeur en différents points de l'eau :

1. Utilisez votre pilote automatique ou votre télécommande pour déplacer le bateau sur le lac.
2. L'application collecte automatiquement des points de profondeur au fur et à mesure que le bateau se déplace.
3. Essayez de couvrir toute la zone que vous souhaitez cartographier en vous déplaçant selon un quadrillage.
4. Pour de meilleurs résultats, déplacez-vous lentement et maintenez une vitesse constante.

> **Conseil** : L'application collecte des points de profondeur lorsque votre bateau se déplace d'au moins 0,25 mètre par rapport à la dernière position enregistrée. Se déplacer en quadrillage avec des passages qui se chevauchent créera les cartes les plus détaillées.

### Étape 4 : Visualiser votre carte

Au fur et à mesure que vous collectez des points de profondeur, l'application construit automatiquement une carte bathymétrique :

1. La carte apparaîtra comme une superposition de couleurs sur votre carte habituelle.
2. Différentes couleurs représentent différentes profondeurs.
3. Pour voir la carte en 3D, inclinez votre vue en plaçant deux doigts sur l'écran et en les faisant glisser vers le haut.

## Comprendre la vue 3D

Lorsque vous inclinez la carte, vous verrez une représentation tridimensionnelle du terrain sous-marin :

- L'eau apparaît comme des "découpes" dans la carte 3D, montrant le profil de profondeur réel.
- Les zones plus profondes apparaissent plus bas dans la vue 3D.
- Le schéma de couleurs et le relief aident à visualiser les différentes plages de profondeur en 2D.

### L'effet de "Découpe"

L'effet de "découpe" signifie que les zones d'eau sont affichées "sous" la terre dans la carte 3D, avec la profondeur représentée avec précision. Cela vous donne une vue réaliste du paysage sous-marin.

Cependant, cela peut parfois causer des problèmes visuels :
- Des zones profondes soudaines peuvent apparaître comme des chutes abruptes et être masquées par la rive ; assurez-vous de faire pivoter la carte pour obtenir un angle différent.
- Si des lacs manquent sur la carte ou ont changé au fil du temps, la terre mal tracée pourrait masquer la vue de la profondeur.
    - Dans ce cas, assurez-vous d'essayer l'autre carte (Region maps ou Google maps).

## Problèmes connus et limitations

### Problème de rendu en mode incliné

Parfois, si vous commencez la cartographie alors que vous êtes en mode incliné (vue 3D), la carte ne s'affichera pas correctement. Pour corriger cela :

1. Faites glisser vers le bas pour revenir à la vue de dessus (non inclinée).
2. Attendez un moment que la carte s'actualise.
3. Inclinez à nouveau la vue.

### Limitation de la vue satellite

Actuellement, la vue satellite et les cartes de profondeur ne peuvent pas être utilisées ensemble. Si vous souhaitez visualiser votre carte de profondeur :

1. Assurez-vous que la vue satellite est désactivée (OFF) dans les paramètres.
2. Utilisez la vue carte standard à la place.

## Explication des paramètres de cartographie

### Paramètres de base

- **Enable mapping** : Active ou désactive la fonction de cartographie.
- **Show depth map** : Affiche ou masque vos cartes de profondeur créées.
- **Color scheme** : Choisissez différents motifs de couleurs pour représenter les profondeurs.

> Note : Pour de meilleures performances, en particulier sur les appareils avec un processeur ou une mémoire limités, désactivez la cartographie une fois que vous êtes satisfait de votre carte actuelle. Désactiver "Enable mapping" arrête la collecte de nouveaux points de profondeur mais garde votre carte existante visible si "Show depth map" est activé. Vous pouvez toujours réactiver la cartographie plus tard si vous souhaitez ajouter plus de données.

## Gestion de vos cartes

### Exporter des cartes

Pour sauvegarder vos données de cartographie pour une sauvegarde ou un partage :

1. Allez dans Settings.
2. Faites défiler jusqu'à la section Depth Mapping.
3. Appuyez sur "Export Mapping Data".
4. Choisissez un emplacement pour enregistrer le fichier.

Pour des instructions d'exportation détaillées et des informations sur les types de fichiers, voir :
- [Import & Export → Export depth maps (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap)

### Importer des cartes

Pour importer des données de cartographie sauvegardées :

1. Allez dans Settings.
2. Faites défiler jusqu'à la section Depth Mapping.
3. Appuyez sur "Import Mapping Data".
4. Sélectionnez le fichier de données de cartographie que vous souhaitez importer.

Plus de détails et de conseils sont disponibles ici :
- [Import & Export → Import depth maps (.bbtmap)](/Import%20And%20Export.html#import-depth-maps-bbtmap)

### Supprimer des cartes

Pour supprimer la carte de profondeur actuelle :

1. Allez dans Settings.
2. Faites défiler jusqu'à la section Depth Mapping.
3. Appuyez sur "Delete Current Map".
4. Confirmez la suppression lorsque vous y êtes invité.

> **Attention** : La suppression d'une carte est permanente et ne peut être annulée. Exportez toujours vos cartes avant de les supprimer si vous pensez en avoir besoin plus tard.

Vous pouvez [exporter vos cartes ici](/Import%20And%20Export.html#export-depth-maps-bbtmap).

## Conseils pour une meilleure cartographie

- Cartographiez par temps calme pour des relevés de profondeur plus précis.
- Couvrez la même zone plusieurs fois pour augmenter la densité des données.
- Déplacez-vous en quadrillage pour la couverture la plus complète.
- Commencez par une petite zone pour vous familiariser avec le processus.
- Exportez vos cartes régulièrement pour éviter toute perte de données.

Apprenez comment [exporter des cartes de profondeur (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap).
- Utilisez des vitesses de bateau plus lentes pour des relevés de profondeur plus précis.
- Concentrez-vous sur les zones présentant des caractéristiques intéressantes comme des cassures ou des structures sous-marines.

## Dépannage

- **La carte n'apparaît pas** : Assurez-vous que "Show depth map" est activé dans les paramètres.
- **Profondeurs inexactes** : Vérifiez la connexion de votre sonar et assurez-vous qu'il est correctement calibré.
- **Problèmes de performance de l'application** : Essayez de réduire le paramètre "Render Resolution".
- **La carte semble déformée** : Vous pourriez avoir besoin de plus de points de données ; essayez de couvrir la zone plus minutieusement.
- **La carte est principalement d'une seule couleur** : La plage de profondeur est automatiquement déterminée à partir des points le plus haut et le plus bas sous l'eau. Il peut y avoir eu un mauvais relevé qui a poussé la plage basse vers les extrêmes. Assurez-vous de ne collecter des points de profondeur que lorsque votre bateau est dans l'eau pour éviter les faux relevés.
- **Cartes plus grandes** : La construction de cartes plus grandes peut prendre plus de temps. Ainsi, particulièrement sur les appareils plus anciens, un peu de patience est nécessaire. Aucun indicateur n'est actuellement affiché pendant la construction de la carte.

---

Nous espérons que ce guide vous aidera à tirer le meilleur parti de la fonctionnalité de cartographie de votre application Baitboats. Bonne pêche et bonne cartographie !
