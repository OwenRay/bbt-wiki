---
title: Leitfaden zur bathymetrischen Kartierung
nav_order: 1
parent: Maps
lang: de
page_id: maps-bathymetric
permalink: "/Maps/Bathymetric Depth Maps.html"
---

# Leitfaden zur bathymetrischen Kartierung

## Inhaltsverzeichnis

- [Einführung](#einführung)
- [Was ist bathymetrische Kartierung?](#was-ist-bathymetrische-kartierung)
- [Anforderungen](#anforderungen)
- [Erstellen Ihrer ersten Tiefenkarte](#erstellen-ihrer-ersten-tiefenkarte)
- [Die 3D-Ansicht verstehen](#die-3d-ansicht-verstehen)
- [Bekannte Probleme und Einschränkungen](#bekannte-probleme-und-einschränkungen)
- [Erklärung der Kartierungseinstellungen](#erklärung-der-kartierungseinstellungen)
- [Verwalten Ihrer Karten](#verwalten-ihrer-karten)
- [Tipps für eine bessere Kartierung](#tipps-für-eine-bessere-kartierung)
- [Fehlerbehebung](#fehlerbehebung)

## Einführung

Willkommen zur Kartierungsfunktion Ihrer Baitboats-App! Dieser Leitfaden hilft Ihnen zu verstehen, wie Sie detaillierte bathymetrische Karten Ihrer Angelgewässer erstellen. Bathymetrische Karten zeigen das Unterwasser-Gelände, einschließlich Tiefen und Konturen, was Ihnen helfen kann, die besten Angelplätze zu finden.

## Was ist bathymetrische Kartierung?

Bathymetrische Kartierung ist der Prozess des Messens und Aufzeichnens der Wassertiefen. Einfach ausgedrückt ist es so, als würde man eine topografische Karte der Unterwasserlandschaft erstellen. Diese Karten können Folgendes offenbaren:

- Tiefe Löcher, in denen sich Fische verstecken könnten
- Unterwasserrücken und Kanten
- Flache Bereiche, die gemieden werden sollten
- Tiefenänderungen, die verschiedene Fischarten anlocken

## Anforderungen

- 3D-Karten erfordern Android 13 oder neuer
- Ein Futterboot mit einem kompatiblen Echolot:
    - Wi-Fish
    - Vexilar
    - Pulse
    - Horizon

## Erstellen Ihrer ersten Tiefenkarte

### Schritt 1: Ausrüstung vorbereiten

1. Stellen Sie sicher, dass Ihr Futterboot ordnungsgemäß mit der App verbunden ist
2. Stellen Sie sicher, dass Ihr Echolot-Gerät korrekt funktioniert:
    - **Wi-Fish**: Lassen Sie die Wi-Fish-App während der Kartierung geöffnet
    - **Vexilar**: Schließen Sie die Vexilar-App während der Kartierung
    - **Pulse**: Während der Kartierung offen lassen und sicherstellen, dass die NMEA-Weiterleitung eingeschaltet und auf Port 3500 eingestellt ist
    - **Horizon**: Vorerst: Während der Kartierung schließen; es wird an einem Software-Release gearbeitet, um dies zu beheben.

### Schritt 2: Kartierung aktivieren

1. Setzen Sie das Boot zuerst ins Wasser
2. Gehen Sie zum Tab „Einstellungen“ (Zahnrad-Symbol)
3. Suchen Sie den Abschnitt „Depth Mapping“
4. Schalten Sie „Enable mapping“ auf EIN
5. Stellen Sie sicher, dass auch „Show depth map“ auf EIN geschaltet ist

### Schritt 3: Tiefenpunkte sammeln

Um eine detaillierte Karte zu erstellen, müssen Sie Tiefenmessungen an verschiedenen Punkten im Wasser sammeln:

1. Verwenden Sie Ihren Autopiloten oder Ihre Funkfernsteuerung, um das Boot auf dem See zu bewegen
2. Die App sammelt automatisch Tiefenpunkte, während sich Ihr Boot bewegt
3. Versuchen Sie, den gesamten Bereich, den Sie kartieren möchten, abzudecken, indem Sie in einem Rastermuster fahren
4. Bewegen Sie sich für beste Ergebnisse langsam und halten Sie eine gleichmäßige Geschwindigkeit bei

> **Tipp**: Die App sammelt Tiefenpunkte, wenn sich Ihr Boot mindestens 0,25 Meter von der letzten aufgezeichneten Position weg bewegt. Das Fahren in einem Rastermuster mit überlappenden Pfaden erstellt die detailliertesten Karten.

### Schritt 4: Ihre Karte anzeigen

Während Sie Tiefenpunkte sammeln, erstellt die App automatisch eine bathymetrische Karte:

1. Die Karte erscheint als farbcodierte Überlagerung auf Ihrer normalen Karte
2. Verschiedene Farben repräsentieren unterschiedliche Tiefen
3. Um die Karte in 3D anzuzeigen, kippen Sie Ihre Ansicht, indem Sie zwei Finger auf den Bildschirm legen und nach oben wischen

## Die 3D-Ansicht verstehen

Wenn Sie die Karte kippen, sehen Sie eine dreidimensionale Darstellung des Unterwasser-Geländes:

- Gewässer erscheinen als „Ausschnitte“ in der 3D-Karte und zeigen das tatsächliche Tiefenprofil
- Tiefere Bereiche erscheinen in der 3D-Ansicht tiefer
- Das Farbschema und das Relief helfen dabei, verschiedene Tiefenbereiche in 2D zu visualisieren

### Der „Ausschnitt-Effekt“

Der „Ausschnitt-Effekt“ bedeutet, dass Wasserflächen in der 3D-Karte „unter“ dem Land angezeigt werden, wobei die Tiefe genau dargestellt wird. Dies gibt Ihnen eine realistische Sicht auf die Unterwasserlandschaft.

Dies kann jedoch manchmal visuelle Probleme verursachen:
- Plötzliche tiefe Bereiche könnten als steile Abfälle erscheinen und durch die Uferseite verdeckt werden; stellen Sie sicher, dass Sie die Karte drehen, um einen anderen Winkel zu erhalten
- Wenn Seen auf der Karte fehlen oder sich im Laufe der Zeit verändert haben, könnte das falsch eingezeichnete Land die Tiefenansicht verdecken
    - Verwenden Sie in diesem Fall unbedingt die alternative Karte (Region-Karten oder Google Maps)

## Bekannte Probleme und Einschränkungen

### Rendering-Problem im gekippten Modus

Manchmal wird die Karte nicht richtig gerendert, wenn Sie mit der Kartierung beginnen, während Sie sich im gekippten Modus (3D-Ansicht) befinden. Um dies zu beheben:

1. Wischen Sie nach unten, um zur Draufsicht zurückzukehren (ungekippt)
2. Warten Sie einen Moment, bis die Karte aktualisiert wurde
3. Kippen Sie die Ansicht dann erneut

### Einschränkung der Satellitenansicht

Derzeit können Satellitenansicht und Tiefenkarten nicht zusammen verwendet werden. Wenn Sie Ihre Tiefenkarte anzeigen möchten:

1. Stellen Sie sicher, dass die Satellitenansicht in den Einstellungen AUSGESCHALTET ist
2. Verwenden Sie stattdessen die Standard-Kartenansicht

## Erklärung der Kartierungseinstellungen

### Grundeinstellungen

- **Enable mapping**: Schaltet die Kartierungsfunktion ein oder aus
- **Show depth map**: Schaltet die Sichtbarkeit Ihrer erstellten Tiefenkarten um
- **Color scheme**: Wählen Sie verschiedene Farbmuster zur Darstellung der Tiefen

> Hinweis: Für die beste Leistung, insbesondere auf Geräten mit begrenzter CPU oder wenig Speicher, deaktivieren Sie die Kartierung, sobald Sie mit Ihrer aktuellen Karte zufrieden sind. Das Ausschalten von „Enable mapping“ stoppt das Sammeln neuer Tiefenpunkte, lässt aber Ihre vorhandene Karte sichtbar, wenn „Show depth map“ eingeschaltet ist. Sie können die Kartierung später jederzeit wieder aktivieren, wenn Sie weitere Daten hinzufügen möchten.

## Verwalten Ihrer Karten

### Karten exportieren

Um Ihre Kartierungsdaten zur Sicherung oder zum Teilen zu speichern:

1. Gehen Sie zu den Einstellungen
2. Scrollen Sie zum Abschnitt „Depth Mapping“
3. Tippen Sie auf „Export Mapping Data“
4. Wählen Sie einen Speicherort für die Datei

Für detaillierte, appspezifische Exportanweisungen und Informationen zu Dateitypen siehe:
- [Import & Export → Tiefenkarten exportieren (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap)

### Karten importieren

Um gespeicherte Kartierungsdaten zu importieren:

1. Gehen Sie zu den Einstellungen
2. Scrollen Sie zum Abschnitt „Depth Mapping“
3. Tippen Sie auf „Import Mapping Data“
4. Wählen Sie die Kartendatendatei aus, die Sie importieren möchten

Weitere Details und Tipps finden Sie hier:
- [Import & Export → Tiefenkarten importieren (.bbtmap)](/Import%20And%20Export.html#import-depth-maps-bbtmap)

### Karten löschen

Um die aktuelle Tiefenkarte zu entfernen:

1. Gehen Sie zu den Einstellungen
2. Scrollen Sie zum Abschnitt „Depth Mapping“
3. Tippen Sie auf „Delete Current Map“
4. Bestätigen Sie das Löschen, wenn Sie dazu aufgefordert werden

> **Warnung**: Das Löschen einer Karte ist dauerhaft und kann nicht rückgängig gemacht werden. Exportieren Sie Ihre Karten immer, bevor Sie sie löschen, falls Sie sie später noch einmal benötigen könnten.

Sie können [Ihre Karten hier exportieren](/Import%20And%20Export.html#export-depth-maps-bbtmap).

## Tipps für eine bessere Kartierung

- Kartieren Sie bei ruhigem Wetter für genauere Tiefenmessungen
- Fahren Sie denselben Bereich mehrmals ab, um die Datendichte zu erhöhen
- Fahren Sie in einem Rastermuster für die vollständigste Abdeckung
- Beginnen Sie mit einem kleinen Bereich, um sich mit dem Vorgang vertraut zu machen
- Exportieren Sie Ihre Karten regelmäßig, um Datenverlust zu vermeiden

Erfahren Sie, wie Sie [Tiefenkarten exportieren (.bbtmap)](/Import%20And%20Export.html#export-depth-maps-bbtmap).
- Verwenden Sie geringere Bootsgeschwindigkeiten für genauere Tiefenmessungen
- Konzentrieren Sie sich auf Bereiche mit interessanten Merkmalen wie Kanten oder Unterwasserstrukturen

## Fehlerbehebung

- **Karte erscheint nicht**: Stellen Sie sicher, dass „Show depth map“ in den Einstellungen aktiviert ist
- **Ungenaue Tiefen**: Überprüfen Sie Ihre Echolot-Verbindung und stellen Sie sicher, dass es richtig kalibriert ist
- **Leistungsprobleme der App**: Versuchen Sie, die Einstellung „Render Resolution“ zu verringern
- **Karte sieht verzerrt aus**: Möglicherweise benötigen Sie mehr Datenpunkte; versuchen Sie, den Bereich gründlicher abzudecken
- **Karte besteht fast nur aus einer Farbe**: Der Tiefenbereich wird automatisch aus dem höchsten und niedrigsten Punkt unter Wasser ermittelt. Möglicherweise gab es eine Fehlmessung, die den unteren Bereich in die Extreme verschoben hat. Stellen Sie sicher, dass Sie Tiefenpunkte nur sammeln, wenn sich Ihr Boot im Wasser befindet, um Fehlmessungen zu vermeiden.
- **Größere Karten**: Größere Karten können länger zum Aufbauen benötigen. Daher ist besonders auf älteren Geräten etwas Geduld gefragt. Während des Kartenaufbaus wird derzeit kein Indikator angezeigt.

---

Wir hoffen, dass dieser Leitfaden Ihnen hilft, die Kartierungsfunktion in Ihrer Baitboats-App bestmöglich zu nutzen. Petri Heil und viel Erfolg beim Kartieren!
