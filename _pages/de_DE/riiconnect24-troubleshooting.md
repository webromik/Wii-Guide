---
title: "Riiconnect24-troubleshooting"
---

{% include toc title="Inhaltsverzeichnis" %}

Solltest du hinsichtlich dieses Tutorials Hilfe benötigen, trete bitte dem [RiiConnect24 Discord-Server](https://discord.gg/b4Y7jfD) bei (empfohlen), oder kontaktiere uns [per E-Mail unter support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![RiiConnect24-Logo](/images/WiiRC24Logo.jpg)

Falls du einen der folgenden Fehler erhälst (und keine anderen Fehler), solltest du in der Lage sein, die Kanäle zu reparieren, indem du deine VFF löschst.

+ Nachricht über die Einstellung der Kanäle
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Voraussetzungen
* Eine SD-Karte oder ein USB-Laufwerk
* [WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Zu löschende Ordner

+ Wetterkanal
  + 48414645
  + 4841464a
  + 48414650

+ Nachrichtenkanal
  + 48414745
  + 4841474a
  + 48414750

#### Anleitung

1. Starte WiiXplorer.
2. Go to `Start` -> `Settings` -> `Boot Settings` -> `Enable NAND write access` and then select `Yes` for both dialogues that appear on the screen.
3. Drücke Zurück, bis du Bildschirm mit dem Dateimanager erreicht hast.
4. Wähle das kleine blaue SD-Karten-Symbol aus und wähle dann `NAND`.
5. Navigiere zu `title` -> `00010002` -> XXXXXXXX -> `data`, wobei XXXXXXXX einer der oben genannten Ordner ist.
6. Drücke die Plus-Taste, während der Zeiger über der `wc24dl.vff` ist und wähle dann `Delete`.

Versuche jetzt den Kanal zu starten, mit dem du Probleme hattest.

[Zurückkehren zur RiiConnect24 Installationsseite](riiconnect24)
{: .notice--info}
