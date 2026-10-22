# FORZA CONTROL CENTER – Updates

Offizielles Update-Repository für
**FORZA CONTROL CENTER Professional Edition**.

Hier findest du die veröffentlichten Programmversionen,
Download-Archive und wichtige Installationshinweise.

## Aktuelle Version

- **Version:** 4.0
- **Build:** 001
- **Release-Tag:** v4.0.0
- **Plattform:** Windows x64

## Download

[Zum aktuellen GitHub-Release](https://github.com/magicpaolo/ForzaControlCenter-Updates/releases/latest)

Lade dort die Datei
`ForzaControlCenter-4.0.0-win-x64.zip` herunter.

## Installation

1. Lade das ZIP-Archiv aus dem GitHub-Release herunter.
2. Klicke mit der rechten Maustaste auf die ZIP-Datei und wähle
   „Alle extrahieren“.
3. Extrahiere alle Dateien in einen eigenen Programmordner.
4. Lass `ForzaControlCenter.exe` und
   `PresentMonAPI2Loader.dll` im selben Ordner.
5. Starte `ForzaControlCenter.exe`.

Starte das Programm nicht direkt innerhalb des ZIP-Archivs.

## FPS-Anzeige und PresentMon

Die FPS-Erfassung benötigt zusätzlich den separaten
**PresentMon Shared Service**.

Die Datei `PresentMonAPI2Loader.dll` ist im FORZA-CONTROL-CENTER-
ZIP enthalten. Der PresentMon-Dienst selbst wird nicht mitgeliefert
und von FORZA CONTROL CENTER Build 001 nicht automatisch installiert.

### Getestete Version

Für Build 001 wurde PresentMon **v2.5.1** erfolgreich getestet.

[Offizieller PresentMon-Release v2.5.1](https://github.com/GameTechDev/PresentMon/releases/tag/v2.5.1)

Lade auf dieser Seite im Bereich „Assets“ das Installationspaket
`PresentMon-v2.5.1.msi` herunter und folge den Anweisungen des
Installationsprogramms.

Andere PresentMon-Versionen wurden für diese Build-Version nicht
gesondert auf Kompatibilität geprüft.

### Wenn keine FPS angezeigt werden

- **PresentMon-Dienst nicht installiert:** Installiere PresentMon
  über das offizielle Installationspaket.
- **PresentMon-Dienst gestoppt:** Wenn der Dienst installiert,
  aber nicht gestartet ist, zeigt FORZA CONTROL CENTER eine
  Warnmeldung und die Schaltfläche „Hilfe / Download“ an.
- **Dienst wurde neu gestartet:** Wenn der Dienst während einer
  laufenden Anwendung gestoppt und anschließend wieder gestartet
  wurde, schließe FORZA CONTROL CENTER und starte es erneut.
- **Loader-Datei fehlt:** Prüfe, ob `PresentMonAPI2Loader.dll`
  im selben Ordner wie `ForzaControlCenter.exe` liegt.

Die Schaltfläche „Hilfe / Download“ öffnet die offizielle
PresentMon-Release-Seite. Die Installation und der Start des
Windows-Dienstes erfolgen durch den Benutzer.

## Updates

Die Programmversionen werden als vollständige ZIP-Archive über
GitHub Releases bereitgestellt.

Zum Aktualisieren lädst du das gewünschte Release herunter und
extrahierst das vollständige Archiv in einen geeigneten Ordner.

Die automatische Update-Prüfung erfolgt höchstens einmal pro 24 Stunden, wenn sie in den Einstellungen aktiviert ist und eine neue Prüfung fällig ist. Updates werden in Build 001 nicht automatisch installiert. Die Aktualisierung erfolgt manuell durch das Herunterladen des vollständigen ZIP-Archivs und das anschließende Extrahieren in einen geeigneten Ordner.

## Drittanbieter-Komponente

PresentMon ist eine externe Komponente mit eigener Dokumentation,
eigenen Releases und Lizenzbedingungen.

[PresentMon – offizielles GitHub-Repository](https://github.com/GameTechDev/PresentMon)
