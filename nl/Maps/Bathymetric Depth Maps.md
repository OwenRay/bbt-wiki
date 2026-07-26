---
title: Gids voor bathymetrische kaarten
nav_order: 1
parent: Maps
lang: nl
page_id: maps-bathymetric
permalink: "/Maps/Bathymetric Depth Maps.html"
---

# Gids voor bathymetrische kaarten

## Inhoudsopgave

- [Inleiding](#inleiding)
- [Wat zijn bathymetrische kaarten?](#wat-zijn-bathymetrische-kaarten)
- [Vereisten](#vereisten)
- [Uw eerste dieptekaart maken](#uw-eerste-dieptekaart-maken)
- [De 3D-weergave begrijpen](#de-3d-weergave-begrijpen)
- [Bekende problemen en beperkingen](#bekende-problemen-en-beperkingen)
- [Uitleg over de mapping-instellingen](#uitleg-over-de-mapping-instellingen)
- [Uw kaarten beheren](#uw-kaarten-beheren)
- [Tips voor een betere mapping](#tips-voor-een-betere-mapping)
- [Problemen oplossen](#problemen-oplossen)

## Inleiding

Welkom bij de Mapping-functie van uw Baitboats-app! Deze gids helpt u begrijpen hoe u gedetailleerde bathymetrische kaarten van uw viswateren kunt maken. Bathymetrische kaarten tonen het onderwaterterrein, inclusief dieptes en contouren, wat u kan helpen de beste visplekken te vinden.

## Wat zijn bathymetrische kaarten?

Bathymetrische mapping is het proces van het meten en in kaart brengen van de diepten van wateren. In eenvoudige bewoordingen is het alsof u een topografische kaart van het onderwaterlandschap maakt. Deze kaarten kunnen het volgende onthullen:

- Diepe gaten waar vissen zich kunnen verschuilen
- Onderwaterruggen en taluds
- Ondiepe gebieden om te vermijden
- Veranderingen in diepte die verschillende vissoorten aantrekken

## Vereisten

- 3D-kaarten vereisen Android 13 of nieuwer
- Een voerboot met een compatibele sonar:
    - Wi-Fish
    - Vexilar
    - Pulse
    - Horizon

## Uw eerste dieptekaart maken

### Stap 1: Uw apparatuur voorbereiden

1. Zorg ervoor dat uw voerboot correct is verbonden met de app.
2. Controleer of uw sonarapparaat correct werkt:
    - **Wi-Fish**: Houd de Wi-Fish-app open tijdens het mappen.
    - **Vexilar**: Sluit de Vexilar-app tijdens het mappen.
    - **Pulse**: Houd deze open tijdens het mappen en zorg ervoor dat NMEA-doorsturen is ingeschakeld en is ingesteld op poort 3500.
    - **Horizon**: Voor nu: sluiten tijdens het mappen; er wordt gewerkt aan een software-update om dit op te lossen.

### Stap 2: Mapping inschakelen

1. Leg de boot eerst in het water.
2. Ga naar het tabblad Settings (tandwielpictogram).
3. Zoek het gedeelte "Depth Mapping".
4. Zet de schakelaar "Enable mapping" aan.
5. Zorg ervoor dat "Show depth map" ook is ingeschakeld.

### Stap 3: Dieptepunten verzamelen

Om een gedetailleerde kaart te maken, moet u dieptemetingen verzamelen van verschillende punten in het water:

1. Gebruik uw autopilot of handzender om de boot over het meer te bewegen.
2. De app verzamelt automatisch dieptepunten terwijl uw boot beweegt.
3. Probeer het hele gebied dat u in kaart wilt brengen te bestrijken door in een rasterpatroon te varen.
4. Voor het beste resultaat vaart u langzaam en houdt u een constante snelheid aan.

> **Tip**: De app verzamelt dieptepunten wanneer uw boot zich ten minste 0,25 meter van de laatst geregistreerde positie verplaatst. Varen in een rasterpatroon met overlappende banen levert de meest gedetailleerde kaarten op.

### Stap 4: Uw kaart bekijken

Terwijl u dieptepunten verzamelt, bouwt de app automatisch een bathymetrische kaart op:

1. De kaart verschijnt als een kleurgecodeerde overlay op uw normale kaart.
2. Verschillende kleuren vertegenwoordigen verschillende diepten.
3. Om de kaart in 3D te bekijken, kantelt u uw weergave door twee vingers op het scherm te plaatsen en omhoog te vegen.

## De 3D-weergave begrijpen

Wanneer u de kaart kantelt, ziet u een driedimensionale weergave van het onderwaterterrein:

- Wateren verschijnen als "uitsparingen" in de 3D-kaart, waardoor het werkelijke diepteprofiel zichtbaar wordt.
- Diepere gebieden verschijnen lager in de 3D-weergave.
- Het kleurenschema en het reliëf helpen om verschillende dieptebereiken in 2D te visualiseren.

### Het "uitsparing"-effect

Het "uitsparing"-effect betekent dat watergebieden "onder" het land worden weergegeven in de 3D-kaart, waarbij de diepte nauwkeurig wordt weergegeven. Dit geeft u een realistisch beeld van het onderwaterlandschap.

Dit kan echter soms visuele problemen veroorzaken:
- Plotselinge diepe gebieden kunnen verschijnen als steile hellingen en worden verborgen door de oeverkant; zorg ervoor dat u de kaart draait om een andere hoek te krijgen.
- Als meren ontbreken op de kaart of in de loop van de tijd zijn veranderd, kan het onjuist weergegeven land de diepteweergave belemmeren.
    - Probeer in dit geval de alternatieve kaart (regionale kaarten of Google Maps).

## Bekende problemen en beperkingen

### Renderingprobleem in gekantelde modus

Soms wordt de kaart niet goed weergegeven als u begint met mappen terwijl de gekantelde modus (3D-weergave) actief is. Om dit op te lossen:

1. Veeg omlaag om terug te keren naar de bovenaanzicht-weergave (niet gekanteld).
2. Wacht een moment tot de kaart is vernieuwd.
3. Kantel de weergave vervolgens opnieuw.

### Beperking van satellietweergave

Momenteel kunnen satellietweergave en dieptekaarten niet samen worden gebruikt. Als u uw dieptekaart wilt bekijken:

1. Zorg ervoor dat de satellietweergave is uitgeschakeld in de instellingen.
2. Gebruik in plaats daarvan de standaard kaartweergave.

## Uitleg over de mapping-instellingen

### Basisinstellingen

- **Enable mapping**: Zet de mapping-functie aan of uit.
- **Show depth map**: Schakelt de zichtbaarheid van uw gemaakte dieptekaarten in of uit.
- **Color scheme**: Kies verschillende kleurpatronen om diepten weer te geven.

> Opmerking: Voor de beste prestaties, vooral op apparaten met beperkte CPU of geheugen, schakelt u mapping uit zodra u tevreden bent met uw huidige kaart. Het uitschakelen van "Enable mapping" stopt het verzamelen van nieuwe dieptepunten, maar houdt uw bestaande kaart zichtbaar als "Show depth map" aan staat. U kunt mapping later altijd weer inschakelen als u meer gegevens wilt toevoegen.

## Uw kaarten beheren

### Kaarten exporteren

Om uw mapping-gegevens op te slaan voor back-up of om ze te delen:

1. Ga naar Settings.
2. Scrol naar het gedeelte Depth Mapping.
3. Tik op "Export Mapping Data".
4. Kies een locatie om het bestand op te slaan.

Voor gedetailleerde, app-specifieke exportinstructies en informatie over bestandstypen, zie:
- [Import & Export → Export depth maps (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap)

### Kaarten importeren

Om opgeslagen mapping-gegevens te importeren:

1. Ga naar Settings.
2. Scrol naar het gedeelte Depth Mapping.
3. Tik op "Import Mapping Data".
4. Selecteer het mapping-gegevensbestand dat u wilt importeren.

Meer details en tips zijn hier beschikbaar:
- [Import & Export → Import depth maps (.bbtmap)](/Import%20And%20Export.html#import-depth-maps-bbtmap)

### Kaarten verwijderen

Om de huidige dieptekaart te verwijderen:

1. Ga naar Settings.
2. Scrol naar het gedeelte Depth Mapping.
3. Tik op "Delete Current Map".
4. Bevestig de verwijdering wanneer daarom wordt gevraagd.

> **Waarschuwing**: Het verwijderen van een kaart is definitief en kan niet ongedaan worden gemaakt. Exporteer altijd uw kaarten voordat u ze verwijdert als u denkt dat u ze later nog nodig hebt.

U kunt [uw kaarten hier exporteren](/Import%20And%20Export.html#export-depth-maps-bbtmap).

## Tips voor een betere mapping

- Map tijdens rustige weersomstandigheden voor nauwkeurigere dieptemetingen.
- Bestrijk hetzelfde gebied meerdere keren om de gegevensdichtheid te verhogen.
- Vaar in een rasterpatroon voor de meest complete dekking.
- Begin met een klein gebied om vertrouwd te raken met het proces.
- Exporteer uw kaarten regelmatig om gegevensverlies te voorkomen.

Leer hoe u [dieptekaarten kunt exporteren (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap).
- Gebruik lagere bootsnelheden voor nauwkeurigere dieptemetingen.
- Focus op gebieden met interessante kenmerken zoals taluds of onderwaterstructuren.

## Problemen oplossen

- **Kaart verschijnt niet**: Zorg ervoor dat "Show depth map" is ingeschakeld in de instellingen.
- **Onnauwkeurige diepten**: Controleer uw sonarverbinding en zorg ervoor dat deze correct is gekalibreerd.
- **Problemen met de prestaties van de app**: Probeer de instelling "Render Resolution" te verlagen.
- **Kaart ziet er vervormd uit**: U hebt mogelijk meer gegevenspunten nodig; probeer het gebied grondiger te bestrijken.
- **Kaart is grotendeels één enkele kleur**: Het dieptebereik wordt automatisch bepaald op basis van het hoogste en laagste punt onder water. Er kan een onjuiste meting zijn geweest die het onderste bereik naar de extremen heeft geduwd. Zorg ervoor dat u alleen dieptepunten verzamelt wanneer uw boot in het water ligt om valse metingen te voorkomen.
- **Grotere kaarten**: Grotere kaarten kunnen langer duren om op te bouwen. Vooral op oudere apparaten is dus wat geduld nodig. Er wordt momenteel geen indicator getoond tijdens het opbouwen van de kaart.

---

We hopen dat deze gids u helpt het meeste uit de mapping-functie in uw Baitboats-app te halen. Veel succes met vissen en mappen!
