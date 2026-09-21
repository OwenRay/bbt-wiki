---
title: BBT Core – Installatie en koppeling
nav_order: 2
lang: nl
page_id: bbt-core
permalink: "/BBT Core.html"
---

# BBT Core – Installatie en koppeling

*Gebruikershandleiding voor installatie, koppeling en gebruik*

**BBT Core – Het ultieme brein voor je baitboat.** Een praktische gids voor het aansluiten van de BBT Core, het koppelen met Raymarine, het installeren van de WiFish-app en het dagelijks gebruik ervan.

![BBT Core – Het ultieme brein voor je baitboat](/assets/bbt_core_cover.png)

> **Belangrijk:** wanneer BBT Core-instellingen worden gewijzigd, moet de BBT Core opnieuw worden gestart om de wijzigingen van kracht te laten worden.

## Inhoudsopgave

- [1. De BBT Core aansluiten](#1-de-bbt-core-aansluiten)
- [2. De standaard Wi-Fish-app verwijderen (indien geïnstalleerd)](#2-de-standaard-wi-fish-app-verwijderen-indien-geïnstalleerd)
- [3. De BBT Core koppelen met Raymarine](#3-de-bbt-core-koppelen-met-raymarine)
- [4. De speciale Wi-Fish-app downloaden](#4-de-speciale-wi-fish-app-downloaden)
- [5. Gebruik](#5-gebruik)
- [6. Overzicht van de overige verbindingen](#6-overzicht-van-de-overige-verbindingen)
- [7. Bouwersmodus via servicecode](#7-bouwersmodus-via-servicecode)

## 1. De BBT Core aansluiten

1. Sluit de voeding aan (5 tot 24 V).
2. Verbind de **WAN**-uitgang van de BBT Core met de **LAN**-ingang van de Skydroid GR01.

![Voeding van de BBT Core (5–24 V)](/assets/bbt_core_power_supply.jpg)

![WAN-uitgang van de BBT Core, verbonden met de LAN-ingang van de Skydroid GR01](/assets/bbt_core_wan_lan.jpg)

## 2. De standaard Wi-Fish-app verwijderen (indien geïnstalleerd)

1. Open **Instellingen**.
2. Ga naar **Apps**.
3. Selecteer de **WiFish-app**.
4. Tik op **Verwijderen**.

## 3. De BBT Core koppelen met Raymarine

1. Open de **BaitBoat Autopilot**-app.
2. Controleer onder **Help** dat u minimaal versie 1.470 gebruikt.
3. Controleer dat u verbonden bent via **Skydroid Connect**.
4. Ga naar **Boat Setup**.
5. Ga naar **BBT Core**.
6. Vink het vakje aan voor **Skydroid G-Series**.
7. Stel **Transmit Power** in op **1 dB**.
8. Ga naar **Pair WiFi Device**.
9. Zoek **Raymarine** en tik erop.
10. Voer het wachtwoord in en bevestig.
11. Tik op **NEXT**.
12. Wacht tot u het bericht ontvangt dat de configuratie succesvol is voltooid.
13. Tik op **CLOSE**.
14. Start alles opnieuw op: zowel de BBT Core als de Skydroid-handzender.

## 4. De speciale Wi-Fish-app downloaden

1. Controleer dat u verbonden bent met het internet.
2. Start de **BaitBoat Autopilot**-app.
3. Ga naar **Boat Set-up**.
4. Selecteer **BBT Core**.
5. Tik op **Install WiFish App**.
6. Tik op **INSTALL**.
7. Veeg vanaf het midden van de bovenrand van het scherm naar beneden.

![Naar beneden vegen vanaf de bovenkant van het scherm, beginnend in het midden](/assets/wifish_swipe_down.png)

8. Tik op **Download complete**.

![Melding „Download complete“ voor de Raymarine Wi-Fish-app](/assets/wifish_download_complete.png)

9. Tik op **Install**.

![Dialoogvenster „Do you want to install this app?“ – Wi-Fish](/assets/wifish_install.png)

10. Selecteer **More details**.

![Google Play Protect – „Unsafe app blocked“](/assets/wifish_more_details.png)

11. Tik op **Install anyway**.

![Google Play Protect – „Install anyway“](/assets/wifish_install_anyway.png)

12. Sluit de Raymarine-app.

De installatie is voltooid.

> **Opmerking:** start de BBT Core opnieuw op nadat u BBT Core-instellingen hebt gewijzigd.

## 5. Gebruik

> **Opmerking:** tijdens het eerste gebruik kan de Raymarine-verbinding af en toe kort wegvallen. In de meeste gevallen wordt de verbinding binnen één seconde automatisch hersteld. Dit komt doordat het Skydroid-protocol automatisch zoekt naar de meest geschikte bandbreedte. Tijdens dit zoeken kan de verbinding tijdelijk worden onderbroken. Wacht rustig tot de verbinding stabiel blijft.

## 6. Overzicht van de overige verbindingen

![Overzicht van de aansluitingen van de BBT Core](/assets/bbt_core_connections.png)

> **Opmerking:** de kompasaansluiting en -kalibratie zijn nog in ontwikkeling.

- De cameraverbindingen werken.
- De WiFi-communicatie werkt.
- De GPS-antenneverbinding werkt.
- Het kompas is nog in ontwikkeling.

## 7. Bouwersmodus via servicecode

Bij het instellen van de BBT Core bevat de tablet of Skydroid soms niet het bouwersaccount (bijvoorbeeld op een vers geconfigureerd apparaat). In dat geval kun je de **volledige bouwersmodus** toch ontgrendelen met een servicecode.

1. Open de **BaitBoat Autopilot**-app.
2. Ga naar het tabblad **Help/Feedback**.
3. Tik op **Servicecode**.
4. Voer de servicecode in en bevestig.

Een geldige servicecode ontgrendelt de volledige bouwersmodus (Real Builder). Servicecodes worden verstrekt door Baitboat — neem contact met ons op om er een aan te vragen. Bouwers kunnen de servicecode van vandaag ook in de app bekijken: deze wordt onder de knop **Servicecode** weergegeven zolang de bouwersmodus actief is.

## 8. Checklist voor bootbouwers

Loop deze checklist af voordat je een boot met Skydroid aan de klant overdraagt.

1. **Bekabeling** — BBT Core-voeding aangesloten (5–24 V) en de **WAN**-uitgang van de BBT Core verbonden met de **LAN**-ingang van de Skydroid GR01.
2. **Koppeling** — BBT Core gekoppeld met Raymarine (zie sectie 3): **Skydroid G-Series** aangevinkt, **Zendvermogen** op 1 dB, en daarna zowel de BBT Core als de Skydroid-handzender herstart.
3. **Wi-Fish-app** — de speciale Wi-Fish-app geïnstalleerd via **Boat Setup → BBT Core → Install WiFish App** (zie sectie 4).
4. **Vaartest** — met de boot op een bok elke motor kort aansturen met de Skydroid-sticks en controleren of de draairichting en de roerrespons kloppen voor deze boot (zie de [Ardupilot-gids voor motor- en servotest](https://ardupilot.org/rover/docs/rover-motor-and-servo-configuration.html#rover-motor-and-servo-configuration-testing)). Bij tweetaktboten beide motoren controleren.
5. **Verbindingscontrole** — de boot enkele minuten verbonden laten en controleren dat de **Skydroid Connect**-verbinding stabiel blijft (enkele korte onderbrekingen in de eerste minuten zijn normaal — zie sectie 5).
6. **Bouwersmodus** — als het apparaat het bouwersaccount mist, ontgrendel het dan met een servicecode (zie sectie 7) en draag de boot daarna over in klantmodus.
7. **Laatste herstart** — herstart de BBT Core en de Skydroid één laatste keer en controleer dat de boot meteen verbindt.

Als alles is afgevinkt, is de boot klaar voor de klant.
