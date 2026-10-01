# Marcus Dziersan

**Junior Anwendungsentwickler** mit starkem Praxisfokus auf schlanke Webanwendungen, nachvollziehbare Softwarearchitektur, Datenhaltung und eigenständig entwickelte Tools.

Ich entwickle bevorzugt Anwendungen, die ohne unnötigen technischen Ballast auskommen: klar strukturiert, verständlich dokumentiert, auf normalem Webhosting betreibbar und nah an realen Anwendungsfällen.

Ein besonderer Schwerpunkt meiner Arbeit liegt inzwischen nicht mehr nur auf einzelnen Anwendungen, sondern auch auf der **Weiterentwicklung und Architektur größerer Softwaresysteme**. Mit **MD Clean Distribution** entwickle ich einen eigenen CMS-Fork, bei dem ich mich intensiv mit Softwarearchitektur, PDO/MySQL, Repositories und Services, Migrationen, Transaktionen, Sicherheit, Backup/Recovery und Erweiterungsschnittstellen beschäftige.

## Schwerpunkt

* **Backend & Webentwicklung:** PHP, PDO, MySQL, MariaDB, JSON, REST-nahe APIs
* **Softwarearchitektur:** OOP, Repository-/Service-Strukturen, Storage-Abstraktion, Migrationen und modulare Systeme
* **Frontend:** HTML5, CSS3, JavaScript, AJAX, responsive Oberflächen
* **Datenhaltung:** relationale Datenmodelle, SQL, Flatfile-/JSON-Systeme und Migration zwischen unterschiedlichen Persistenzmodellen
* **Java:** Konsolenanwendungen, Swing, JavaFX, Lern- und Toolprojekte
* **Embedded & Hardware:** Arduino, ESP8266, ESP32, OLED, Sensorik, OTA-Experimente
* **Qualität & Betrieb:** Dokumentation, Backup/Recovery, Fehleranalyse, Sicherheitsbetrachtung und nachvollziehbare Release-Prozesse
* **Arbeitsweise:** pragmatisch, dokumentationsstark, lösungsorientiert und ohne Framework-Overhead dort, wo er keinen konkreten Mehrwert bietet

## Ausgewählte Projekte

### MD Clean Distribution

**Eigenständig weiterentwickelter CMS-Fork auf Basis von Bludit 3.22.0 mit eigener technischer Ausrichtung und SQL-nativer Business-Architektur.**

MD Clean begann mit der Frage, wie sich die Einfachheit eines schlanken CMS erhalten lässt, während zentrale Schwächen einer eng gekoppelten Flatfile-Architektur systematisch beseitigt werden.

Aus dem ursprünglichen Fork entwickelte sich schrittweise eine eigene CMS-Distribution mit klarer Trennung von **Repositories, Services und Storage**, einer **PDO/MySQL-basierten SQL-Datenhaltung**, versionierten Datenbankmigrationen, Transaktionen und Mechanismen für Mehrbenutzerbetrieb.

Weitere Schwerpunkte sind ein eigenes Installations- und Migrationssystem, Core-Integritätsprüfungen, sichere Plugin- und Theme-Pakete sowie ein Backup- und Recovery-Konzept, das die SQL-Datenbank als festen Bestandteil der Anwendung behandelt.

Eine zentrale Medienbibliothek mit SQL-gestützten virtuellen Ordnern ergänzt die Architektur. Themes und Plugins folgen dabei einer festen Erweiterungsregel: Sie arbeiten ausschließlich über vorgesehene Schnittstellen und verändern keine Core-Dateien.

MD Clean befindet sich derzeit in der **Public-Beta-Phase**. Die weitere Roadmap umfasst unter anderem Zwei-Faktor-Authentifizierung, einen Blockeditor, ein Galerie-System und den weiteren Ausbau der Backend- und Mehrbenutzerfunktionen.

Das Projekt ist zugleich mein umfangreichstes Architektur- und Portfolio-Projekt und dokumentiert den Weg von der Analyse einer bestehenden Codebasis über Refactoring und Migration bis hin zu einer zunehmend eigenständigen Softwarearchitektur.

### PolarisNova

Selbst hostbare Projekt-, Aufgaben-, Kunden-, Zeit-, Rechnungs-, EÜR-, Nachrichten- und Ticketverwaltung auf Basis von PHP, MySQL/MariaDB und Vanilla JavaScript.

Das Projekt verbindet typische Geschäftsprozesse in einer eigenständig entwickelten Webanwendung und legt besonderen Wert auf einfache Installation, nachvollziehbare Datenhaltung und den Betrieb ohne umfangreiche Framework-Infrastruktur.

### MD-CyberFun XP

Browserbasierte Desktop- und Web-PDA-Umgebung im Stil klassischer Betriebssystemoberflächen. Das Projekt kombiniert einen virtuellen Desktop, einen Explorer mit Dateiverwaltung, modular aufgebaute Anwendungen und responsive Bedienkonzepte für Desktop-, Tablet- und Mobilansichten.

Zu den integrierten Werkzeugen gehören unter anderem Text- und Markdown-Verarbeitung, Bild- und Dateivorschauen, eine Farbpipette, Screenshot-Funktionen sowie ein kategorisiertes Anwendungsmenü. Ein besonderer Schwerpunkt liegt auf der technischen Umsetzung typischer Desktop-Funktionen innerhalb einer reinen Webanwendung.

Das Projekt wird derzeit privat auf GitHub weiterentwickelt.

### DOS Banana

Java-Swing-Retro-Jump’n’Run mit eigener Game-Loop, Kollisionserkennung, Physik, Levelsystem und klassischer 2D-Rendering-Logik.

Das Projekt dient insbesondere der praktischen Vertiefung objektorientierter Java-Entwicklung und der Umsetzung zeitkritischer Anwendungslogik außerhalb klassischer Webanwendungen.

### ICE Notfall QR System

Privates Demo-Projekt für QR-basierte Notfallinformationen mit PHP, JSON-Datenhaltung, Administrationsbereich und QR-Druck-Anbindung.

### YHK Print Tool

Leichtgewichtiges Windows-Tool zum direkten Drucken von Texten und QR-Codes auf günstigen Bluetooth-Thermodruckern.

### MiniDeviceHub8266

ESP8266-Testprojekt mit Weboberfläche, Konfiguration, LittleFS, JSON-Statusausgabe und OTA-Firmware-Upload.

## Was mich auszeichnet

Ich arbeite mich gerne tief in praktische Problemstellungen ein und entwickle Lösungen, deren Aufbau ich selbst nachvollziehen und erklären kann.

Dabei interessiert mich nicht nur, **dass** eine Funktion funktioniert, sondern auch, was darunter passiert: Wie fließen Daten durch eine Anwendung? Wo liegen Verantwortlichkeiten? Was geschieht bei einem fehlgeschlagenen Schreibvorgang? Wie lassen sich Daten sicher migrieren und wiederherstellen? Wie verhalten sich mehrere Bearbeiter gleichzeitig? Wo sollte eine Schnittstelle liegen, damit ein System später erweiterbar bleibt?

Gerade die Arbeit an MD Clean hat meinen Schwerpunkt deshalb zunehmend von der reinen Umsetzung einzelner Funktionen in Richtung **Softwarearchitektur, Datenintegrität und langfristige Wartbarkeit** verschoben.

Meine Projekte entstehen häufig aus konkreten Alltagsproblemen, Lernzielen oder technischen Experimenten. Dadurch verbinde ich Softwareentwicklung mit praktischer Umsetzung, Fehleranalyse, Dokumentation und kontinuierlicher Verbesserung.

## Technische Haltung

Software muss nicht automatisch groß, komplex oder cloudabhängig sein, um professionell entwickelt zu sein.

Ich bevorzuge Lösungen, die:

* verständlich aufgebaut sind,
* klare Verantwortlichkeiten besitzen,
* lokal oder selbst gehostet betrieben werden können,
* möglichst wenige unnötige Abhängigkeiten benötigen,
* sauber dokumentiert und wiederherstellbar sind,
* reale Probleme lösen,
* und auch nach Monaten noch nachvollziehbar und wartbar bleiben.

Dabei lehne ich Frameworks nicht grundsätzlich ab. Ich setze jedoch bevorzugt nur die Abstraktionen und Werkzeuge ein, deren Nutzen für das jeweilige Projekt nachvollziehbar ist. Wo ich bewusst ohne großes Framework arbeite, beschäftige ich mich entsprechend intensiver mit den technischen Grundlagen, die ein Framework andernfalls übernehmen würde.

## Aktueller Fokus

Mein aktueller Schwerpunkt liegt auf der weiteren Vertiefung von **PHP, PDO, MySQL/MariaDB, JavaScript, Java und objektorientierter Anwendungsentwicklung** sowie auf Softwarearchitektur, Datenintegrität und sicheren Webanwendungen.

Mit MD Clean Distribution arbeite ich derzeit intensiv an einem langfristigen Softwareprojekt, das Themen wie bestehende Codebasen, Refactoring, Repository-/Service-Architektur, SQL-Migration, Transaktionen, Mehrbenutzerbetrieb, Sicherheit, Backup/Recovery, Erweiterbarkeit und Releaseplanung miteinander verbindet.

Parallel entwickle ich weitere Web-, Java- und Embedded-Projekte und dokumentiere meine Arbeit als praktisches Portfolio. GitHub nutze ich dabei sowohl für öffentlich einsehbare Projekte als auch als Entwicklungsplattform. Einige umfangreichere Projekte befinden sich bewusst in privaten Repositories; Architektur, technische Dokumentation und ausgewählte Einblicke sind dennoch Bestandteil meines Portfolios.
