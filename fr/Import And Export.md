---
title: Sauvegarde et restauration des waypoints et cartes de profondeur
nav_order: 6
lang: fr
page_id: import-export
permalink: "/Import And Export.html"
---

# Sauvegarde et restauration des waypoints et cartes de profondeur

## Table des matières

- [Introduction](#introduction)
- [Waypoints](#waypoints)
    - [Exporter des waypoints (.gpx)](#exporter-des-waypoints-gpx)
    - [Importer des waypoints (.gpx)](#importer-des-waypoints-gpx)
- [Cartes de profondeur](#cartes-de-profondeur)
    - [Exporter des cartes de profondeur (.bbtmap)](#exporter-des-cartes-de-profondeur-bbtmap)
    - [Importer des cartes de profondeur (.bbtmap)](#importer-des-cartes-de-profondeur-bbtmap)
- [Meilleures pratiques](#meilleures-pratiques)
- [Dépannage](#depannage)
- [Résumé des types de fichiers](#resume-des-types-de-fichiers)

## Introduction
Ce guide explique comment sauvegarder (exporter) et restaurer (importer) vos waypoints de pêche et vos cartes de profondeur créées dans l'application Baitboats.

- Les waypoints sont exportés dans un fichier standard `.gpx`.
- Les cartes de profondeur sont exportées dans un fichier `.bbtmap` (archive de cartographie Baitboats).

> Conseil : Nous vous recommandons de vous envoyer les fichiers exportés par e-mail ou de les enregistrer sur Google Drive. Cela garde vos données en sécurité et facilite leur restauration sur un nouveau téléphone.

## Waypoints

### Exporter des waypoints (.gpx)
1. Ouvrez l'application et allez dans l'onglet Settings (icône d'engrenage).
2. Appuyez sur "Import / Export".
3. Appuyez sur "Export Waypoints".
4. Choisissez où envoyer/enregistrer le fichier :
    - Envoyez-le vous par e-mail, ou
    - Enregistrez-le sur Google Drive (ou un autre service cloud), ou
    - Partagez-le via votre application préférée.

Résultat : Un fichier similaire à `spots.gpx` qui contient tous vos waypoints actuels (nom + emplacement).

### Importer des waypoints (.gpx)
Option A — Depuis l'application :
1. Ouvrez Settings → "Import / Export".
2. Appuyez sur "Import Waypoints".
3. Choisissez un fichier `.gpx` depuis votre appareil ou votre stockage cloud (par exemple, Google Drive).

Option B — Depuis une autre application (partager/ouvrir dans) :
1. Trouvez le fichier `.gpx` dans votre application d'e-mail ou de cloud.
2. Ouvrez le fichier et choisissez Baitboats si cela vous est demandé.
3. L'application importera les waypoints automatiquement.

Notes :
- Les noms de waypoints en double sont autorisés ; vous pouvez les renommer plus tard dans l'application.
- Les coordonnées sont importées exactement à partir du `.gpx` (latitude/longitude WGS84).

## Cartes de profondeur

### Exporter des cartes de profondeur (.bbtmap)
1. Ouvrez Settings → "Import / Export".
2. Appuyez sur "Export Mapping".
3. Choisissez comment partager/enregistrer le fichier :
    - Envoyez-le vous par e-mail, ou
    - Enregistrez-le sur Google Drive (recommandé), ou
    - Utilisez toute autre option de stockage/partage.

Résultat : Un fichier `.bbtmap` contenant vos clusters de cartes de profondeur. Gardez ce fichier en sécurité.

### Importer des cartes de profondeur (.bbtmap)
1. Ouvrez Settings → "Import / Export".
2. Appuyez sur "Import Mapping".
3. Sélectionnez le fichier `.bbtmap` depuis votre appareil ou votre stockage cloud.

Après l'importation : Vos cartes de profondeur précédemment créées seront à nouveau disponibles dans l'application.

> Important : Le fichier `.bbtmap` est spécifique à Baitboats. Ne le décompressez pas et ne l'ouvrez pas avec d'autres applications. Utilisez l'option "Import Mapping" dans l'application pour le restaurer.
> {: .warning}

## Meilleures pratiques
- Sauvegardez régulièrement :
    - Après une session de pêche, exportez à la fois les Waypoints et le Mapping.
    - Envoyez les fichiers vous-même par e-mail ou enregistrez-les sur Google Drive.
- Utilisez des noms clairs (ex: `LacTranquille-2025-06-15.gpx`, `LacTranquille-2025-06-15.bbtmap`).
- Faites un test rapide une fois : exportez puis importez sur le même appareil pour vous familiariser avec le processus.

## Dépannage
- Je ne trouve pas mon fichier lors de l'importation :
    - Assurez-vous que l'extension correspond : `.gpx` pour les waypoints, `.bbtmap` pour les cartes de profondeur.
    - Si vous utilisez Google Drive, vous pouvez essayer de télécharger le fichier d'abord ou choisir "Ouvrir avec" → Baitboats.

- Rien ne se passe lors de l'ouverture depuis un e-mail/cloud :
    - Téléchargez le fichier localement, puis utilisez Settings → "Import Waypoints" ou "Import Mapping".

- L'importation a échoué ou les données semblent incomplètes :
    - Assurez-vous que le fichier n'est pas corrompu et qu'il est entièrement téléchargé.
    - Pour les waypoints, vérifiez qu'il s'agit d'un fichier GPX valide. Pour la cartographie, assurez-vous qu'il s'agit du fichier `.bbtmap` original créé par l'application.

- Passage à un nouvel appareil :
    - Sur l'ancien appareil, exportez les Waypoints et le Mapping et envoyez-les vous (e-mail/Drive).
    - Sur le nouveau appareil, installez l'application et importez les deux fichiers depuis votre e-mail/Drive.

## Résumé des types de fichiers
- Waypoints : `.gpx` (standard ouvert)
- Cartes de profondeur : `.bbtmap` (archive de cartographie Baitboats)

Gardez les deux en sécurité en vous les envoyant par e-mail ou en les stockant dans Google Drive.
