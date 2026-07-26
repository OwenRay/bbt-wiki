---
title: Wegpunkte und Tiefenkarten speichern und wiederherstellen
nav_order: 6
lang: de
page_id: import-export
permalink: "/Import And Export.html"
---

# Wegpunkte und Tiefenkarten speichern und wiederherstellen

## Inhaltsverzeichnis

- [Einführung](#einführung)
- [Wegpunkte](#wegpunkte)
    - [Wegpunkte exportieren (.gpx)](#wegpunkte-exportieren-gpx)
    - [Wegpunkte importieren (.gpx)](#wegpunkte-importieren-gpx)
- [Tiefenkarten](#tiefenkarten)
    - [Tiefenkarten exportieren (.bbtmap)](#tiefenkarten-exportieren-bbtmap)
    - [Tiefenkarten importieren (.bbtmap)](#tiefenkarten-importieren-bbtmap)
- [Best Practices](#best-practices)
- [Fehlerbehebung](#fehlerbehebung)
- [Zusammenfassung der Dateitypen](#zusammenfassung-der-dateitypen)

## Einführung
Diese Anleitung erklärt, wie Sie Ihre Angel-Wegpunkte und Ihre erstellten Tiefenkarten in der Baitboats-App sichern (exportieren) und wiederherstellen (importieren).

- Wegpunkte werden in eine Standard-`.gpx`-Datei exportiert.
- Tiefenkarten werden in eine `.bbtmap`-Datei exportiert (Baitboats-Mapping-Archiv).

> Tipp: Wir empfehlen, die exportierten Dateien per E-Mail an sich selbst zu senden oder sie auf Google Drive zu speichern. Dies hält Ihre Daten sicher und macht die Wiederherstellung auf einem neuen Telefon einfach.

## Wegpunkte

### Wegpunkte exportieren (.gpx)
1. Öffnen Sie die App und gehen Sie zum Tab „Einstellungen“ (Zahnrad-Symbol).
2. Tippen Sie auf „Import / Export“.
3. Tippen Sie auf „Export Waypoints“.
4. Wählen Sie aus, wohin die Datei gesendet/gespeichert werden soll:
    - Per E-Mail an sich selbst senden, oder
    - Auf Google Drive (oder einem anderen Cloud-Dienst) speichern, oder
    - Über Ihre bevorzugte App teilen.

Ergebnis: Eine Datei ähnlich wie `spots.gpx`, die alle Ihre aktuellen Wegpunkte (Name + Standort) enthält.

### Wegpunkte importieren (.gpx)
Option A — Aus der App heraus:
1. Öffnen Sie Einstellungen → „Import / Export“.
2. Tippen Sie auf „Import Waypoints“.
3. Wählen Sie eine `.gpx`-Datei von Ihrem Gerät oder Cloud-Speicher (z. B. Google Drive) aus.

Option B — Aus einer anderen App heraus (Teilen/Öffnen in):
1. Suchen Sie die `.gpx`-Datei in Ihrer E-Mail- oder Cloud-App.
2. Öffnen Sie die Datei und wählen Sie Baitboats aus, falls Sie gefragt werden.
3. Die App importiert die Wegpunkte automatisch.

Hinweise:
- Doppelte Wegpunktnamen sind zulässig; Sie können sie später in der App umbenennen.
- Koordinaten werden exakt aus der `.gpx`-Datei importiert (WGS84 Breite/Länge).

## Tiefenkarten

### Tiefenkarten exportieren (.bbtmap)
1. Öffnen Sie Einstellungen → „Import / Export“.
2. Tippen Sie auf „Export Mapping“.
3. Wählen Sie aus, wie die Datei geteilt/gespeichert werden soll:
    - Per E-Mail an sich selbst senden, oder
    - Auf Google Drive speichern (empfohlen), oder
    - Eine andere Speicher-/Teilungsoption verwenden.

Ergebnis: Eine `.bbtmap`-Datei, die Ihre Tiefenkarten-Cluster enthält. Bewahren Sie diese Datei sicher auf.

### Tiefenkarten importieren (.bbtmap)
1. Öffnen Sie Einstellungen → „Import / Export“.
2. Tippen Sie auf „Import Mapping“.
3. Wählen Sie die `.bbtmap`-Datei von Ihrem Gerät oder Cloud-Speicher aus.

Nach dem Import: Ihre zuvor erstellten Tiefenkarten sind wieder in der App verfügbar.

> Wichtig: Die `.bbtmap`-Datei ist spezifisch für Baitboats. Entpacken Sie sie nicht und öffnen Sie sie nicht mit anderen Apps. Verwenden Sie die In-App-Option „Import Mapping“ zur Wiederherstellung.
> {: .warning}

## Best Practices
- Sichern Sie regelmäßig:
    - Exportieren Sie nach einem Angelausflug sowohl Wegpunkte als auch Mapping.
    - Senden Sie die Dateien per E-Mail an sich selbst oder speichern Sie sie auf Google Drive.
- Verwenden Sie klare Namen (z. B. `LakeTranquil-2025-06-15.gpx`, `LakeTranquil-2025-06-15.bbtmap`).
- Machen Sie einmal einen kurzen Test: Exportieren und importieren Sie auf demselben Gerät, damit Sie mit dem Vorgang vertraut sind.

## Fehlerbehebung
- Ich kann meine Datei beim Importieren nicht finden:
    - Stellen Sie sicher, dass die Erweiterung übereinstimmt: `.gpx` für Wegpunkte, `.bbtmap` für Tiefenkarten.
    - Wenn Sie Google Drive verwenden, können Sie versuchen, die Datei zuerst herunterzuladen oder „Open with“ → Baitboats zu wählen.

- Es passiert nichts, wenn ich die Datei aus der E-Mail/Cloud öffne:
    - Laden Sie die Datei lokal herunter und verwenden Sie dann Einstellungen → „Import Waypoints“ oder „Import Mapping“.

- Der Import ist fehlgeschlagen oder die Daten erscheinen unvollständig:
    - Stellen Sie sicher, dass die Datei nicht beschädigt ist und vollständig hochgeladen/heruntergeladen wurde.
    - Vergewissern Sie sich bei Wegpunkten, dass es sich um eine gültige GPX-Datei handelt. Stellen Sie beim Mapping sicher, dass es sich um die ursprüngliche, von der App erstellte `.bbtmap`-Datei handelt.

- Umzug auf ein neues Gerät:
    - Exportieren Sie auf dem alten Gerät Wegpunkte und Mapping und senden Sie diese an sich selbst (E-Mail/Drive).
    - Installieren Sie auf dem neuen Gerät die App und importieren Sie beide Dateien aus Ihrer E-Mail/Drive.

## Zusammenfassung der Dateitypen
- Wegpunkte: `.gpx` (offener Standard)
- Tiefenkarten: `.bbtmap` (Baitboats mapping archive)

Bewahren Sie beide sicher auf, indem Sie sie an sich selbst mailen oder in Google Drive speichern.
