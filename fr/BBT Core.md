---
title: BBT Core – Installation et appairage
nav_order: 2
lang: fr
page_id: bbt-core
permalink: "/BBT Core.html"
---

# BBT Core – Installation et appairage

*Manuel d'utilisation pour l'installation, l'appairage et l'utilisation*

**BBT Core – Le cerveau ultime du baitboat.** Un guide pratique pour connecter le BBT Core, l'appairer avec Raymarine, installer l'application WiFish et l'utiliser au quotidien.

![BBT Core – Le cerveau ultime du baitboat](/assets/bbt_core_cover.png)

> **Important :** à chaque fois que les paramètres du BBT Core sont modifiés, le BBT Core doit être redémarré pour que les modifications prennent effet.

## Table des matières

- [1. Connexion du BBT Core](#1-connexion-du-bbt-core)
- [2. Suppression de l'application Wi-Fish standard (si installée)](#2-suppression-de-lapplication-wi-fish-standard-si-installée)
- [3. Appairage du BBT Core avec Raymarine](#3-appairage-du-bbt-core-avec-raymarine)
- [4. Téléchargement de l'application Wi-Fish spéciale](#4-téléchargement-de-lapplication-wi-fish-spéciale)
- [5. Utilisation](#5-utilisation)
- [6. Aperçu des autres connexions](#6-aperçu-des-autres-connexions)
- [7. Mode constructeur via un code de service](#7-mode-constructeur-via-un-code-de-service)

## 1. Connexion du BBT Core

1. Branchez l'alimentation électrique (5 à 24 V).
2. Connectez la sortie **WAN** du BBT Core à l'entrée **LAN** du Skydroid GR01.

![Alimentation du BBT Core (5–24 V)](/assets/bbt_core_power_supply.jpg)

![Sortie WAN du BBT Core connectée à l'entrée LAN du Skydroid GR01](/assets/bbt_core_wan_lan.jpg)

## 2. Suppression de l'application Wi-Fish standard (si installée)

1. Ouvrez **Paramètres**.
2. Allez dans **Applications**.
3. Sélectionnez l'**application WiFish**.
4. Touchez **Supprimer**.

## 3. Appairage du BBT Core avec Raymarine

1. Ouvrez l'application **BaitBoat Autopilot**.
2. Sous **Aide**, vérifiez que vous utilisez au moins la version 1.470.
3. Vérifiez que vous êtes connecté via **Skydroid Connect**.
4. Allez dans **Boat Setup**.
5. Allez dans **BBT Core**.
6. Cochez la case **Skydroid G-Series**.
7. Réglez **Transmit Power** sur **1 dB**.
8. Allez dans **Pair WiFi Device**.
9. Recherchez **Raymarine** et touchez-le.
10. Saisissez le mot de passe et confirmez.
11. Touchez **NEXT**.
12. Attendez de recevoir le message indiquant que la configuration a été terminée avec succès.
13. Touchez **CLOSE**.
14. Redémarrez tout : le BBT Core et l'émetteur portable Skydroid.

## 4. Téléchargement de l'application Wi-Fish spéciale

1. Vérifiez que vous êtes connecté à Internet.
2. Lancez l'application **BaitBoat Autopilot**.
3. Allez dans **Boat Set-up**.
4. Sélectionnez **BBT Core**.
5. Touchez **Install WiFish App**.
6. Touchez **INSTALL**.
7. Balayez vers le bas depuis le haut de l'écran, en partant du milieu de l'écran.

![Balayage vers le bas depuis le haut de l'écran, en partant du milieu](/assets/wifish_swipe_down.png)

8. Touchez **Download complete**.

![Notification « Download complete » pour l'application Raymarine Wi-Fish](/assets/wifish_download_complete.png)

9. Touchez **Install**.

![Boîte de dialogue « Do you want to install this app? » – Wi-Fish](/assets/wifish_install.png)

10. Sélectionnez **More details**.

![Google Play Protect – « Unsafe app blocked »](/assets/wifish_more_details.png)

11. Touchez **Install anyway**.

![Google Play Protect – « Install anyway »](/assets/wifish_install_anyway.png)

12. Fermez l'application Raymarine.

L'installation est terminée.

> **Remarque :** après avoir modifié les paramètres du BBT Core, redémarrez le BBT Core.

## 5. Utilisation

> **Remarque :** lors de la première utilisation, la connexion Raymarine peut être interrompue brièvement à quelques reprises. Dans la plupart des cas, la connexion est rétablie automatiquement en moins d'une seconde. Cela se produit parce que le protocole Skydroid recherche automatiquement la bande passante la plus adaptée. Pendant cette recherche, la connexion peut être temporairement interrompue. Attendez calmement que la connexion redevienne stable.

## 6. Aperçu des autres connexions

![Aperçu des connexions du BBT Core](/assets/bbt_core_connections.png)

> **Remarque :** la connexion et l'étalonnage de la boussole sont encore en cours de développement.

- Les connexions de caméra fonctionnent.
- La communication WiFi fonctionne.
- La connexion de l'antenne GPS fonctionne.
- La boussole est encore en cours de développement.

## 7. Mode constructeur via un code de service

Lors de la configuration du BBT Core, la tablette ou le Skydroid ne contient parfois pas le compte constructeur (par exemple sur un appareil fraîchement configuré). Dans ce cas, vous pouvez toujours déverrouiller le **mode constructeur complet** avec un code de service.

1. Ouvrez l'application **BaitBoat Autopilot**.
2. Allez dans l'onglet **Aide / Commentaires**.
3. Touchez **Code de service**.
4. Saisissez le code de service et confirmez.

Un code de service valide déverrouille le mode constructeur complet (Real Builder). Les codes de service sont fournis par Baitboat — contactez-nous pour en demander un. Les constructeurs peuvent également consulter le code du jour dans l'application : il s'affiche sous le bouton **Code de service** tant que le mode constructeur est actif.

## 8. Checklist pour les constructeurs

Parcourez cette checklist avant de remettre un bateau équipé d'un Skydroid au client.

1. **Câblage** — alimentation du BBT Core branchée (5–24 V) et sortie **WAN** du BBT Core reliée à l'entrée **LAN** du Skydroid GR01.
2. **Appairage** — BBT Core appairé avec Raymarine (voir section 3) : **Skydroid G-Series** coché, **Puissance d'émission** à 1 dB, puis redémarrage du BBT Core et de l'émetteur Skydroid.
3. **Application Wi-Fish** — l'application Wi-Fish spéciale installée via **Boat Setup → BBT Core → Install WiFish App** (voir section 4).
4. **Test de navigation** — bateau sur banc, actionner brièvement chaque moteur avec les sticks du Skydroid et vérifier que le sens de rotation et la réponse du gouvernail sont corrects pour ce bateau (voir le [guide Ardupilot de test moteur et servo](https://ardupilot.org/rover/docs/rover-motor-and-servo-configuration.html#rover-motor-and-servo-configuration-testing)). Sur les bateaux bimoteurs, vérifier les deux moteurs.
5. **Vérification de la connexion** — laisser le bateau connecté quelques minutes et confirmer que le lien **Skydroid Connect** reste stable (quelques brèves coupures pendant les premières minutes sont normales — voir section 5).
6. **Mode constructeur** — si l'appareil n'a pas le compte constructeur, le déverrouiller avec un code de service (voir section 7), puis remettre le bateau en mode client.
7. **Dernier redémarrage** — redémarrer une dernière fois le BBT Core et le Skydroid et vérifier que le bateau se connecte immédiatement.

Une fois tout coché, le bateau est prêt pour le client.
