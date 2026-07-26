---
title: Waypoints en dieptekaarten opslaan en herstellen
nav_order: 6
lang: nl
page_id: import-export
permalink: "/Import And Export.html"
---

# Waypoints en dieptekaarten opslaan en herstellen

## Inhoudsopgave

- [Inleiding](#inleiding)
- [Waypoints](#waypoints)
    - [Waypoints exporteren (.gpx)](#waypoints-exporteren-gpx)
    - [Waypoints importeren (.gpx)](#waypoints-importeren-gpx)
- [Dieptekaarten](#dieptekaarten)
    - [Dieptekaarten exporteren (.bbtmap)](#dieptekaarten-exporteren-bbtmap)
    - [Dieptekaarten importeren (.bbtmap)](#dieptekaarten-importeren-bbtmap)
- [Beste werkwijzen](#beste-werkwijzen)
- [Problemen oplossen](#problemen-oplossen)
- [Overzicht bestandstypen](#overzicht-bestandstypen)

## Inleiding
Deze gids legt uit hoe u een back-up kunt maken (exporteren) en hoe u uw vis-waypoints en gemaakte dieptekaarten kunt herstellen (importeren) in de Baitboats-app.

- Waypoints worden geëxporteerd naar een standaard `.gpx`-bestand.
- Dieptekaarten worden geëxporteerd naar een `.bbtmap`-bestand (Baitboats mapping-archief).

> Tip: We raden aan om de geëxporteerde bestanden naar uzelf te e-mailen of ze op te slaan in Google Drive. Dit houdt uw gegevens veilig en maakt het eenvoudig om ze te herstellen op een nieuwe telefoon.

## Waypoints

### Waypoints exporteren (.gpx)
1. Open de app en ga naar het tabblad Settings (tandwielpictogram).
2. Tik op "Import / Export".
3. Tik op "Export Waypoints".
4. Kies waar u het bestand heen wilt sturen of wilt opslaan:
    - E-mail het naar uzelf, of
    - Sla het op in Google Drive (of een andere clouddienst), of
    - Deel het via uw favoriete app.

Resultaat: Een bestand vergelijkbaar met `spots.gpx` dat al uw huidige waypoints bevat (naam + locatie).

### Waypoints importeren (.gpx)
Optie A — Vanuit de app:
1. Open Settings → "Import / Export".
2. Tik op "Import Waypoints".
3. Kies een `.gpx`-bestand van uw apparaat of cloudopslag (bijv. Google Drive).

Optie B — Vanuit een andere app (delen/openen in):
1. Zoek het `.gpx`-bestand in uw e-mail of cloud-app.
2. Open het bestand en kies Baitboats als daarom wordt gevraagd.
3. De app zal de waypoints automatisch importeren.

Opmerkingen:
- Dubbele waypoint-namen zijn toegestaan; u kunt ze later in de app hernoemen.
- Coördinaten worden exact geïmporteerd uit de `.gpx` (WGS84 lat/lon).

## Dieptekaarten

### Dieptekaarten exporteren (.bbtmap)
1. Open Settings → "Import / Export".
2. Tik op "Export Mapping".
3. Kies hoe u het bestand wilt delen/opslaan:
    - E-mail naar uzelf, of
    - Sla op in Google Drive (aanbevolen), of
    - Gebruik een andere opslag- of deeloptie.

Resultaat: Een `.bbtmap`-bestand met uw dieptekaartclusters. Bewaar dit bestand goed.

### Dieptekaarten importeren (.bbtmap)
1. Open Settings → "Import / Export".
2. Tik op "Import Mapping".
3. Selecteer het `.bbtmap`-bestand van uw apparaat of cloudopslag.

Na het importeren: Uw eerder gemaakte dieptekaarten zijn weer beschikbaar in de app.

> Belangrijk: Het `.bbtmap`-bestand is specifiek voor Baitboats. Pak het niet uit en open het niet met andere apps. Gebruik de in-app optie "Import Mapping" om te herstellen.
> {: .warning}

## Beste werkwijzen
- Maak regelmatig back-ups:
    - Exporteer na een vissessie zowel de Waypoints als de Mapping.
    - Stuur de bestanden naar uzelf via e-mail of sla ze op in Google Drive.
- Gebruik duidelijke namen (bijv. `LakeTranquil-2025-06-15.gpx`, `LakeTranquil-2025-06-15.bbtmap`).
- Doe eenmaal een korte test: exporteer en importeer vervolgens op hetzelfde apparaat, zodat u bekend bent met het proces.

## Problemen oplossen
- Ik kan mijn bestand niet vinden tijdens het importeren:
    - Controleer of de extensie klopt: `.gpx` voor waypoints, `.bbtmap` voor dieptekaarten.
    - Als u Google Drive gebruikt, kunt u proberen het bestand eerst te downloaden of kies "Open with" → Baitboats.

- Er gebeurt niets bij het openen vanuit e-mail/cloud:
    - Download het bestand lokaal en gebruik vervolgens Settings → "Import Waypoints" of "Import Mapping".

- Importeren mislukt of de gegevens lijken onvolledig:
    - Zorg ervoor dat het bestand niet beschadigd is en volledig is geüpload/gedownload.
    - Controleer voor waypoints of het een geldig GPX-bestand is. Zorg er voor mapping voor dat het het originele `.bbtmap`-bestand is dat door de app is gemaakt.

- Overstappen naar een nieuw apparaat:
    - Exporteer op het oude apparaat de Waypoints en Mapping en stuur ze naar uzelf (e-mail/Drive).
    - Installeer op het nieuwe apparaat de app en importeer beide bestanden vanuit uw e-mail/Drive.

## Overzicht bestandstypen
- Waypoints: `.gpx` (open standaard)
- Dieptekaarten: `.bbtmap` (Baitboats mapping-archief)

Bewaar beide goed door ze naar uzelf te e-mailen of op te slaan in Google Drive.
