---
title: BBT Core – Installation und Pairing
nav_order: 2
lang: de
page_id: bbt-core
permalink: "/BBT Core.html"
---

# BBT Core – Installation und Pairing

*Benutzerhandbuch für Installation, Pairing und Nutzung*

**BBT Core – Das ultimative Baitboat-Gehirn.** Ein praktischer Leitfaden zum Anschließen des BBT Core, zum Pairing mit Raymarine, zum Installieren der WiFish-App und zur Nutzung im Alltag.

![BBT Core – Das ultimative Baitboat-Gehirn](/assets/bbt_core_cover.png)

> **Wichtig:** Immer wenn BBT-Core-Einstellungen geändert werden, muss der BBT Core neu gestartet werden, damit die Änderungen wirksam werden.

## Inhaltsverzeichnis

- [1. Anschließen des BBT Core](#1-anschließen-des-bbt-core)
- [2. Entfernen der Standard-Wi-Fish-App (falls installiert)](#2-entfernen-der-standard-wi-fish-app-falls-installiert)
- [3. Pairing des BBT Core mit Raymarine](#3-pairing-des-bbt-core-mit-raymarine)
- [4. Herunterladen der speziellen Wi-Fish-App](#4-herunterladen-der-speziellen-wi-fish-app)
- [5. Nutzung](#5-nutzung)
- [6. Übersicht der weiteren Verbindungen](#6-übersicht-der-weiteren-verbindungen)
- [7. Baumodus per Servicecode](#7-baumodus-per-servicecode)

## 1. Anschließen des BBT Core

1. Schließen Sie das Netzteil (5 bis 24 V) an.
2. Verbinden Sie den **WAN**-Ausgang des BBT Core mit dem **LAN**-Eingang des Skydroid GR01.

![Stromversorgung des BBT Core (5–24 V)](/assets/bbt_core_power_supply.jpg)

![WAN-Ausgang des BBT Core, verbunden mit dem LAN-Eingang des Skydroid GR01](/assets/bbt_core_wan_lan.jpg)

## 2. Entfernen der Standard-Wi-Fish-App (falls installiert)

1. Öffnen Sie **Einstellungen**.
2. Gehen Sie zu **Apps**.
3. Wählen Sie die **WiFish-App** aus.
4. Tippen Sie auf **Entfernen**.

## 3. Pairing des BBT Core mit Raymarine

1. Öffnen Sie die **BaitBoat Autopilot**-App.
2. Prüfen Sie unter **Hilfe**, dass Sie mindestens Version 1.470 verwenden.
3. Stellen Sie sicher, dass Sie über **Skydroid Connect** verbunden sind.
4. Gehen Sie zu **Boat Setup**.
5. Gehen Sie zu **BBT Core**.
6. Aktivieren Sie das Kontrollkästchen für **Skydroid G-Series**.
7. Stellen Sie **Transmit Power** auf **1 dB**.
8. Gehen Sie zu **Pair WiFi Device**.
9. Suchen Sie **Raymarine** und tippen Sie darauf.
10. Geben Sie das Passwort ein und bestätigen Sie.
11. Tippen Sie auf **NEXT**.
12. Warten Sie, bis die Meldung erscheint, dass die Konfiguration erfolgreich abgeschlossen wurde.
13. Tippen Sie auf **CLOSE**.
14. Starten Sie alles neu: sowohl den BBT Core als auch den Skydroid-Handsender.

## 4. Herunterladen der speziellen Wi-Fish-App

1. Stellen Sie sicher, dass Sie mit dem Internet verbunden sind.
2. Starten Sie die **BaitBoat Autopilot**-App.
3. Gehen Sie zu **Boat Set-up**.
4. Wählen Sie **BBT Core** aus.
5. Tippen Sie auf **Install WiFish App**.
6. Tippen Sie auf **INSTALL**.
7. Wischen Sie von der Mitte des oberen Bildschirmrands nach unten.

![Wischen vom oberen Bildschirmrand, beginnend in der Mitte](/assets/wifish_swipe_down.png)

8. Tippen Sie auf **Download complete**.

![Benachrichtigung „Download complete“ für die Raymarine Wi-Fish-App](/assets/wifish_download_complete.png)

9. Tippen Sie auf **Install**.

![Dialog „Do you want to install this app?“ – Wi-Fish](/assets/wifish_install.png)

10. Wählen Sie **More details** aus.

![Google Play Protect – „Unsafe app blocked“](/assets/wifish_more_details.png)

11. Tippen Sie auf **Install anyway**.

![Google Play Protect – „Install anyway“](/assets/wifish_install_anyway.png)

12. Schließen Sie die Raymarine-App.

Die Installation ist abgeschlossen.

> **Hinweis:** Starten Sie den BBT Core nach dem Ändern von BBT-Core-Einstellungen neu.

## 5. Nutzung

> **Hinweis:** Während der ersten Nutzung kann die Raymarine-Verbindung kurzzeitig einige Male abbrechen. In den meisten Fällen wird die Verbindung innerhalb einer Sekunde automatisch wiederhergestellt. Das liegt daran, dass das Skydroid-Protokoll automatisch nach der am besten geeigneten Bandbreite sucht. Während dieser Suche kann die Verbindung vorübergehend unterbrochen werden. Warten Sie ruhig, bis die Verbindung stabil bleibt.

## 6. Übersicht der weiteren Verbindungen

![Übersicht der Anschlüsse des BBT Core](/assets/bbt_core_connections.png)

> **Hinweis:** Kompassverbindung und -kalibrierung befinden sich noch in der Entwicklung.

- Kameraverbindungen funktionieren.
- Die WiFi-Kommunikation funktioniert.
- Die GPS-Antennenverbindung funktioniert.
- Der Kompass befindet sich noch in der Entwicklung.

## 7. Baumodus per Servicecode

Bei der Einrichtung des BBT Core enthält das Tablet oder der Skydroid manchmal kein Bauerkonto (zum Beispiel auf einem frisch konfigurierten Gerät). In diesem Fall können Sie den **vollen Baumodus** trotzdem mit einem Servicecode freischalten.

1. Öffnen Sie die **BaitBoat Autopilot**-App.
2. Gehen Sie zum Tab **Hilfe/Feedback**.
3. Tippen Sie auf **Servicecode**.
4. Geben Sie den Servicecode ein und bestätigen Sie.

Ein gültiger Servicecode schaltet den vollen Baumodus frei (Real Builder). Servicecodes werden von Baitboat bereitgestellt – kontaktieren Sie uns, um einen anzufordern. Wer den Baumodus aktiviert hat, kann den heutigen Servicecode auch in der App einsehen: Er wird unter dem Button **Servicecode** angezeigt, solange der Baumodus aktiv ist.

> **Hinweis:** Starten Sie den BBT Core nach dem Freischalten des Baumodus neu.

## 8. Checkliste für Bootsbauer

Gehen Sie diese Checkliste durch, bevor Sie ein Boot mit Skydroid an den Kunden übergeben.

1. **Verkabelung** — BBT-Core-Stromversorgung angeschlossen (5–24 V) und der **WAN**-Ausgang des BBT Core mit dem **LAN**-Eingang des Skydroid GR01 verbunden.
2. **Kopplung** — BBT Core mit Raymarine gekoppelt (siehe Abschnitt 3): **Skydroid G-Series** angehakt, **Sendeleistung** auf 1 dB, danach BBT Core und Skydroid-Handsender neu gestartet.
3. **Wi-Fish-App** — die spezielle Wi-Fish-App über **Boat Setup → BBT Core → Install WiFish App** installiert (siehe Abschnitt 4).
4. **Fahrttest** — bei Boot auf dem Ständer kurz jeden Motor mit den Skydroid-Sticks antreiben und prüfen, ob Drehrichtung und Ruderantwort für dieses Boot stimmen (siehe [Ardupilot-Anleitung für Motor- und Servotest](https://ardupilot.org/rover/docs/rover-motor-and-servo-configuration.html#rover-motor-and-servo-configuration-testing)). Bei Zweimotor-Booten beide Motoren prüfen.
5. **Verbindungsprüfung** — das Boot einige Minuten verbunden lassen und bestätigen, dass die **Skydroid-Connect**-Verbindung stabil bleibt (einige kurze Unterbrechungen in den ersten Minuten sind normal — siehe Abschnitt 5).
6. **Baumodus** — fehlt auf dem Gerät das Bauerkonto, mit einem Servicecode freischalten (siehe Abschnitt 7) und das Boot danach im Kundenmodus übergeben.
7. **Letzter Neustart** — BBT Core und Skydroid ein letztes Mal neu starten und prüfen, dass sich das Boot sofort verbindet.

Wenn alles abgehakt ist, ist das Boot bereit für den Kunden.
