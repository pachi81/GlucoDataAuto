[<img src='images/en.png' height=10> English version](README.md)  
[<img src='images/pl.png' height=10> Wersja polska](README_PL.md)

# GlucoDataAuto

Nachdem der Android Auto Teil von [GlucoDataHandler](https://github.com/pachi81/GlucoDataHandler/blob/master/README_DE.md) gegen die Richtlinien von Google Play verstosen hat, wurde dieser Teil in eine extra App namens GlucoDataAuto ausgelagert.
Diese App empfängt sowohl die Glukosewerte, als auch die Einstellungen von GlucoDataHandler.

Alternativ kann sie auch als eigenständige App verwendet werden.

## Option #1: Fake Media Player
Wenn sie nicht über Android Auto Musik hören, können sie die Media Player Unterstützung verwenden:

<img src='images/AA_media.png' width=300>

Um den Media Player für die geteilte Ansicht (Coolwalk) zu aktivieren, die Wiedergabe in einen anderen Media Player stoppen und in GlucoDataAuto auf Play drücken.

## Option #2: Benachrichtigungen verwenden

Alternativ zum Media Player kann die Android Auto Benachrichtigung verwendet werden:

<img src='images/AA_notification.png' width=300> <img src='images/AA_notification_view.png' width=300>

INFO: das Benachrichtigungs Popup erscheint bei jedem neuen Wert.

## Option #3: APP verwenden

<img src='images/AA_App.png' width=300>

# Android Auto Installieren

Lade die letzte Version von `GlucoDataAuto_#.#.apk` von [hier](https://github.com/pachi81/GlucoDataAuto/releases) auf das Smartphone herunter und installiere sie (dafür muss die Installation von unbekannten Quellen erlaubt werden).

Um GlucoDataAuto in Android Auto zu verwenden, müssen die folgende Schritte durchgeführt werden:

## 1. Entwicklereinstellungen aktivieren

* Android Auto App öffnen
* bis zu Version scrollen
* mehrfach auf Version drücken bis ein Popup mit "Entwicklereinstellungen zulassen" kommt
* "OK" drücken

## 2. "Unbekannte Quellen" aktivieren

* Android Auto App öffnen
* in den 3-Punkt Menü "Entwicklereinstellungen auswählen"
* bis zu "Unbekannte Quellen" scrollen und aktivieren

## 3. Benachrichtigungen aktivieren

* Android Auto App öffnen
* bis zu "Benachrichtigungen" scrollen
* "Unterhaltungen anzeigen" aktivieren
* "Erste Zeile einer Unterhaltung anzeigen" aktivieren
