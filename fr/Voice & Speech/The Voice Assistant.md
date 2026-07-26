---
title: L'assistant vocal
nav_order: 1
parent: Voice & Speech
lang: fr
page_id: voice-assistant
permalink: "/Voice & Speech/The Voice Assistant.html"
---

# Configurer l'assistant vocal sur votre appareil Android pour Baitboat Autopilot

## Table des matières

- [Prérequis](#prerequis)
- [Guide de configuration étape par étape](#guide-de-configuration-etape-par-etape)
   - [1. Installer les fichiers de reconnaissance vocale hors ligne](#1-installer-les-fichiers-de-reconnaissance-vocale-hors-ligne)
   - [2. Activer l'assistant vocal dans l'application Baitboats](#2-activer-lassistant-vocal-dans-lapplication-baitboats)
   - [3. Accorder l'autorisation du microphone](#3-accorder-lautorisation-du-microphone)
   - [4. Tester l'assistant vocal](#4-tester-lassistant-vocal)
   - [5. Commandes supportées](#5-commandes-supportees)
- [Dépannage](#depannage)
- [Note importante](#note-importante)

Ce guide vous aidera à configurer votre appareil Android pour utiliser la fonction d'assistant vocal dans l'application Baitboats. Veuillez noter que **seule la langue anglaise est actuellement supportée** pour les commandes vocales.

## Prérequis
- Appareil Android avec les services Google installés
- Application Google installée et mise à jour
- Application Baitboat Autopilot installée

## Guide de configuration étape par étape

### 1. Installer les fichiers de reconnaissance vocale hors ligne

1. Ouvrez les paramètres de votre appareil.
2. Recherchez "Google voice typing" et ouvrez ce menu.
3. Appuyez sur "Add a language".
4. Téléchargez le pack de langue anglais (English).
5. Appuyez ensuite sur "Languages" et assurez-vous que English (US) est coché.
6. Appuyez sur "Primary language" et assurez-vous que English est sélectionné.

### 2. Activer l'assistant vocal dans l'application Baitboats
1. Ouvrez l'application Baitboats.
2. Allez dans Settings -> App behavior.
3. Trouvez et activez l'option "Voice Commands".

### 3. Accorder l'autorisation du microphone
Lorsque l'application vous le demande :
1. Appuyez sur "Allow" pour accorder l'accès au microphone.
2. Si vous avez refusé l'autorisation par erreur, allez dans les Paramètres de votre appareil > Applications > Baitboat Autopilot > Autorisations > Microphone et activez-le.

### 4. Tester l'assistant vocal
1. Ouvrez l'application Baitboats.
2. Dites "Hey Boat" pour activer l'assistant vocal.
3. Lorsque l'assistant répond, vous pouvez utiliser des commandes comme :
    - "Toggle mapping"
    - "Enable satellite view"
    - "Save waypoint"
    - "Navigate to waypoint 1"

### 5. Commandes supportées
Voici quelques exemples de commandes supportées :

1. **Activation vocale** :
    - Commande : "Hey boat" (suivie des opérations souhaitées)
    - Action : Active l'assistant vocal et le prépare à accepter d'autres commandes.

2. **Changer le mode de cartographie** :
    - Commande : "Toggle mapping"
    - Action : Active ou désactive la fonction de cartographie de profondeur.

3. **Activer la vue satellite** :
    - Commande : "Enable satellite view"
    - Action : Active la vue satellite.

4. **Désactiver la carte de profondeur** :
    - Commande : "Disable depth map"
    - Action : Masque la carte de profondeur de l'affichage.

5. **Enregistrer la position actuelle** :
    - Commande : "Save this spot" ou "Create a waypoint"
    - Action : Enregistre l'emplacement actuel du bateau en tant que waypoint/spot.

6. **Maintenir la position** :
    - Commande : "Stop" ou "Hold position"
    - Action : Maintient le bateau stationnaire à sa position actuelle.

7. **Passer en contrôle manuel** :
    - Commande : "Switch to manual" ou "Set to manual control"
    - Action : Passe le bateau en mode de contrôle manuel.

8. **Naviguer vers le point de départ (Home)** :
    - Commande : "Navigate home" ou "Go to home"
    - Action : Ordonne au bateau de retourner à son point de départ.

9. **Naviguer vers un waypoint spécifique** :
    - Commande : "Go to waypoint 3" ou "Navigate to spot 5"
    - Action : Dirige le bateau vers un waypoint ou un spot spécifié.

## Dépannage
- Si vous voyez l'erreur "Language not supported", assurez-vous que votre appareil est réglé sur l'anglais.
- Si vous voyez l'erreur "Could not start assistant", suivez l'étape 2 pour installer le pack de langue hors ligne.
- Pour de meilleurs résultats, parlez clairement dans un environnement calme.
- Assurez-vous que votre appareil dispose d'une connexion Internet stable pour la configuration initiale.
- Vous pourriez entendre un son de notification de temps en temps. Cela se produit lorsque la détection vocale redémarre. Nous corrigerons cela ultérieurement.

## Note importante
**Seule la langue anglaise est actuellement supportée** pour les commandes vocales. L'utilisation d'autres langues peut entraîner une reconnaissance incorrecte ou une absence de réponse de l'assistant.
