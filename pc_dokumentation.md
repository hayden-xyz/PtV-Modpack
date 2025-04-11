<h1 align="center">Anleitung PC Bau</h1>

1. [Vorbereitung](#vorbereitung)
2. [Arbeitsschutz und Sicherheit](#arbeitsschutz-und-sicherheit)
3. [Benötigte Werkzeuge und Materialien](#benötigte-werkzeuge-und-materialien)
4. [Allgemeines Zubehör](#allgemeines-zubehör)

1. [Gehäuse](#gehäuse)
2. [Netzteil](#netzteil)
3. [Mainboard](#mainboard)
4. [Prozessor / Kühler](#prozessor--kühler)
5. [Arbeitsspeicher (RAM)](#arbeitsspeicher-ram)
6. [Datenspeicher](#datenspeicher)
7. [Zusätzliche Laufwerke](#zusätzliche-laufwerke)
8. [Erweiterungskarten](#erweiterungskarten)

6. [Montage](#montage)
7. [Inbetriebnahme](#inbetriebnahme)
8. [Entsorgung](#entsorgung)
___
<h2 align="center">Vorbereitung</h2>

Vor dem Beginn des Montageprozesses ist sicherzustellen, dass sämtliche Komponenten vollständig und kompatibel vorliegen. Eine antistatische Unterlage und ggf. ein ESD-Armband sind bereitzulegen. Der Arbeitsbereich sollte sauber, gut beleuchtet und frei von elektrostatischer Aufladung sein.
<!--#### 1. Komponeten heraussuchen und Preise vergleichen (z.B. auf [Geizhals](https://geizhals.de)).
   - Falls nötig, [PC-Konfigurator](https://alternate.de/configurator.xhtml) benutzen, um die Kompatibilität der Komponenten zu gewährleisten.

#### 2. Arbeitsplatz aufräumen:
   - nicht benötigte Sachen wegräumen
   - Anti-Statik Unterlage auslegen
   - Anti-Statik Armband benutzen

#### 3. Benötigte Komponenten und Werkzeuge bereitlegen
   - Sammelschüssel für Kleinteile
   - Kabelbinder + Schere
   - Kreuzschlitzschraubendreher-->
___
<h2 align="center">Arbeitsschutz und Sicherheit</h2>

- aufgeräumter / ordentlicher Arbeitsplatz 
- Tragen eines ESD-Armbands, um Schäden durch elektrostatische Entladungen an empfindlichen Bauteilen zu vermeiden
- Antistatik / ESD-Matte auslegen
- Arbeiten ausschließlich bei <b>Netztrennung</b> (keine Stromzufuhr)
- Vorsicht beim Umgang mit scharfkantigen Gehäuseteilen
___
<h2 align="center">Benötigte Werkzeuge und Materialien</h2>

- Sammelaufbewahrung für Kleinteile
- Kabelbinder oder Klettverschlüsse für Kabelmanagement
- Kreuzschlitzschraubendreher (Größe PH2 empfohlen)
- Wärmeleitpaste (falls nicht bereits auf dem CPU-Kühler aufgetragen)
- ggf. Isopropanol und Mikrofasertuch zur Reinigung
___
<h2 align="center">Allgemeines Zubehör</h2>

- Monitor
- Tastatur & Maus
- Lautsprecher und/oder Kopfhörer
- Netzkabel
- Betriebssystem-Installationsmedium (z.B. USB-Stick)
___
<h2 align="center">Gehäuse</h2>

> <b>Das Gehäuse ist die physische Struktur, die alle internen Komponenten eines Computers beherbergt. Es gibt verschiedene Formfaktoren, die die Größe und den Aufbau des Gehäuses bestimmen:​</b>

   - ATX: Standardgröße für Desktop-PCs mit ausreichend Platz für Erweiterungen.​
   - Micro-ATX: Kompakter als ATX, bietet weniger Erweiterungssteckplätze.​
   - Mini-ITX: Sehr klein und für kompakte Systeme geeignet, jedoch mit eingeschränkten Erweiterungsmöglichkeiten.
___
<h2 align="center">Netzteil</h2>

> <b>Das Netzteil versorgt alle Komponenten mit elektrischer Energie. Wichtige Aspekte sind:​</b>

#### Bauarten:
   - Nicht-modular: Alle Kabel sind fest mit dem Netzteil verbunden.​
   - Semi-modular: Einige Kabel sind fest verbunden, andere können bei Bedarf angeschlossen werden.​
   - Modular: Alle Kabel können individuell angeschlossen oder entfernt werden, was das Kabelmanagement erleichtert.​

#### Anschlüsse: 
   - 24-Pin ATX (Mainboard)
   - 8/4/4+4-Pin EPS (CPU)
   - PCIe 6/6+2/8-Pin (GPU, Andere
#### Leistung: 
   - Die benötigte Wattzahl hängt von den verbauten Komponenten ab. Starke CPUs und GPUs erhöhen den Energiebedarf.
___
<h2 align="center">Mainboard</h2>

> <b>Das Mainboard ist die zentrale Platine, die alle Komponenten miteinander verbindet</b>
<b>Wichtige Merkmale sind:​</b>

#### Formfaktoren:
   - ATX: Standardgröße mit vielen Erweiterungssteckplätzen.​
   - Micro-ATX: Kompakter mit weniger Steckplätzen.​
   - Mini-ITX: Sehr klein mit minimalen Erweiterungsmöglichkeiten.​

#### CPU-Sockel: 
   - Der CPU-Sockel bestimmt, welche Prozessoren kompatibel sind (z.B. Intel LGA1200 oder AMD AM4).​

#### Speicherbänke: 
   - Anzahl der Steckplätze für RAM-Module, die die maximale Menge und Art des unterstützten Arbeitsspeichers bestimmen.​

#### Anschlüsse: 
   - USB-Ports,
   - SATA-Anschlüsse für Laufwerke,
   - M.2-Steckplätze für SSDs
   - weitere Schnittstellen für Peripheriegeräte.​

#### Erweiterungsslots: 
   - PCIe-Steckplätze für Grafikkarten, Soundkarten oder andere Erweiterungskarten.
___
<h2 align="center">Prozessor / Kühler</h2>

> <b>Die CPU führt die Berechnungen und Prozesse aus. Es gibt Unterschiede in:​</b>

#### Kerne und Threads: 
   - Mehr Kerne und Threads ermöglichen bessere Multitasking-Fähigkeiten und Leistung in parallelisierten Anwendungen.​

#### Taktfrequenz: 
   - Höhere Frequenzen bedeuten schnellere Verarbeitungsgeschwindigkeiten.​

> <b>Der Kühler hält die CPU auf optimaler Betriebstemperatur:</b>​

#### Luftkühlung: 
   - Verwendet Lüfter und Kühlkörper, um Wärme abzuführen.​

#### Wasserkühlung: 
   - Setzt auf Flüssigkeitskreisläufe zur effizienteren Kühlung, oft leiser und effektiver bei hoher Wärmeentwicklung.
___
<h2 align="center">Arbeitsspeicher (RAM)</h2>

> <b>Der RAM speichert temporäre Daten für den schnellen Zugriff durch die CPU​</b>

#### Typen: 
   - DDR4, DDR5 usw., wobei neuere Generationen höhere Geschwindigkeiten und Effizienz bieten.​

#### Kapazität: 
   - Mehr RAM ermöglicht besseres Multitasking und Leistung in speicherintensiven Anwendungen.​

#### Geschwindigkeit: 
   - Höhere MHz-Werte bedeuten schnelleren Datenzugriff, was die Gesamtleistung verbessern kann.
___
<h2 align="center">Datenspeicher</h2>

> <b>Hierzu zählen Festplatten (HDDs) und Solid-State-Drives (SSDs)</b> 
   - SSDs sind schneller, während HDDs oft mehr Speicherplatz für weniger Geld bieten
   - Anschlüsse können SATA oder M.2 sein
___
<h2 align="center">Zusätzliche Laufwerke</h2>

> <b>Dazu gehören optische Laufwerke (z.B. DVD/Blu-ray) oder zusätzliche Speicherlaufwerke</b> 
   - Achten Sie auf verfügbare Anschlüsse und Einbauplätze im Gehäuse.
___
<h2 align="center">Erweiterungskarten</h2>

> <b>Beispiele sind Grafikkarten, Soundkarten oder Netzwerkkarten</b>
   - Stellen Sie sicher, dass genügend Platz und passende Slots auf dem Mainboard vorhanden sind
___
<h2 align="center">Montage</h2>

#### 1. Vorbereitung:
   - Stelle sicher dass dein Arbeitsplatz sauber, ordentlich und staubfrei ist
   - Entlade statische Elektrizität, indem du einen geerdeten Metallgegenstand (z.B. Heizkörper) berührst
   - Lege dir alle benötigten Teile bereit

#### 2. Mainboard vorbereiten:
   - Lege das Mainboard auf eine nicht leitende Oberfläche (z.B. den Produktkarton)
   - Installiere den Prozessor, indem du den Sockelhebel anhebst, die CPU korrekt ausrichtest, und vorsichtig einsetzt, danach den Hebel wieder schließen
   - Stecke den RAM in die dafür vorgesehenen Slots
   - Falls eine m.2-SSD verwendet wird, stecke diese in den entsprechenden Slot
   - Falls eine SATA SSD/HDD verwendet wird, befestige diese im Festplattenkäfig des Gehäuses

#### 3. Mainboard ins Gehäuse einbauen:
   - Bringe die I/O Blende des Mainboards (falls nötig) im Gehäuse an
   - Setze das Mainboard vorsichtig ein und verschraube es mit den Abstandshaltern im Gehäuse
   - Falls der Kühler keine voraufgetragene Wärmeleitpaste hat, trage eine erbsengroße Menge auf die CPU auf
   - Setze den Kühler auf die CPU und befestige ihn laut Anleitung des Herstellers

#### 4. Netzteil einbauen:
   - Setze das Netzteil an den vorgesehenen Platz im Gehäuse und befestige es mit Schrauben

#### 5. Lüfter 
   - An den ensprechenden Stellen im Gehäuse festschrauben

#### 6. Grafikkarte installieren:
   - Setze die Grafikkarte in den PCIe-Slot auf dem Mainboard ein
   - Befestige sie mit Schrauben am Gehäuse

#### 7. Verkabelung:
   - Verbinde das Mainboard mit dem Netzteil (24-Pin ATX-Stecker + 8/4/4+4-Pin CPU-Stecker)
   - Frontpanel-Kabel des Gehäuses (Power/Reset-Button, USB-Ports, Audio) am Mainboard anschließen
   - Falls vorhanden, Lüfter mit den entsprechenden Anschlüssen am Mainboard verbinden
___
<h2 align="center">Inbetriebnahme</h2>

#### 1. Erster Testlauf:
   - Überprüfe alle Verbindungen noch einmal
   - Schließe Monitor, Tastatur und Maus an
   - Schalte das Netzteil ein und drücke den Power-Button
   - Falls sich nichts tut, überprüfe die Verkabelung und alle Anschlüsse

#### 2. Betriebssystem installieren:
   - Stecke einen bootfähigen USB-Stick oder lege eine Installations-DVD mit dem gewünschten Betriebssystem ein
   - Starte den PC und rufe das BIOS/UEFI auf (meist durch drücken von F2, F10, DEL oder ESC beim Start)
   - Stelle die Boot-Reihenfolge ein, sodass der PC vom Installationsmedium startet
   - Folge den Anweisungen zur Installation des Betriebssystems
___
<h2 align="center">Entsorgung</h2>

- Elektroschrott fachgerecht entsorgen
- Verpackungen können recycelt werden
- funktionsfähige alte Hardware kann gespendet oder verkauft werden
___
