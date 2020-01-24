# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.94] - 2020-01-22

Task
----

*   \[[GSD-854](https://dreebit.atlassian.net/browse/GSD-854)\] - Automatisches aktualisieren von Button

## [0.5.93] - 2020-01-23

Bug
---

*   \[[GSD-800](https://dreebit.atlassian.net/browse/GSD-800)\] - Messungen Scan Buttons EM + FIL ohne Funktion
*   \[[GSD-821](https://dreebit.atlassian.net/browse/GSD-821)\] - Im Menü Messung starten Anzeige oben rechts EM und Fil nicht klickbar
*   \[[GSD-822](https://dreebit.atlassian.net/browse/GSD-822)\] - Anzeige Ordniate und Abszisse bei laufender Messung
*   \[[GSD-828](https://dreebit.atlassian.net/browse/GSD-828)\] - Bei Rezepterstellung Selected Masses -> Bins existieren EM und Leadin im Tabellenkopf sind aber nicht auswählbar
*   \[[GSD-829](https://dreebit.atlassian.net/browse/GSD-829)\] - Fehlen des Messwertes bei zweiter Y-Achse bei MID Messung mit Specials im Rezept
*   \[[GSD-839](https://dreebit.atlassian.net/browse/GSD-839)\] - Bei Änderung Name Rezept wird dieser nach Speichern nicht automatisch in der Rezeptliste links aktualisiert
*   \[[GSD-840](https://dreebit.atlassian.net/browse/GSD-840)\] - Bei der Änderung des Mode bei einem bereits erstellten Rezept fehlt die aktualisierung des Fensters

## [0.5.92] - 2020-01-15

Task
----

*   \[[GSD-793](https://dreebit.atlassian.net/browse/GSD-793)\] - Netzwerkeinstellung: Option DHCP herausnehmen

## [0.5.90] - 2020-01-15

Verbesserung
------------

*   \[[GSD-762](https://dreebit.atlassian.net/browse/GSD-762)\] - VSM GraphQL API Integration

Bug
---

*   \[[GSD-782](https://dreebit.atlassian.net/browse/GSD-782)\] - Änderung IP-Adresse funktioniert nicht

## [0.5.88] - 2020-01-14

Task
----

*   \[[GSD-773](https://dreebit.atlassian.net/browse/GSD-773)\] - Dropdown-Menü um Logineintrag erweitern

Bug
---

*   \[[GSD-752](https://dreebit.atlassian.net/browse/GSD-752)\] - Updatefunktion des Screens durch das Server-Archive geht nicht

## [0.5.83] - 2020-01-13

Verbesserung
------------

*   \[[GSD-728](https://dreebit.atlassian.net/browse/GSD-728)\] - Anpassung Widget-Titel für Heizer
*   \[[GSD-730](https://dreebit.atlassian.net/browse/GSD-730)\] - Webseitentitel vom Frontend anpassen
*   \[[GSD-731](https://dreebit.atlassian.net/browse/GSD-731)\] - Menüpunkt Alerts ändern in Alarm

Bug
---

*   \[[GSD-727](https://dreebit.atlassian.net/browse/GSD-727)\] - Web: Anzeige Wert "0" auf log. Scala ist nicht erlaubt
*   \[[GSD-733](https://dreebit.atlassian.net/browse/GSD-733)\] - Parameter Manager: Mehrfachauswahl bei "Wert in Geräteliste"

## [0.5.82] - 2020-01-09

Sub-Task
--------

*   \[[GSD-723](https://dreebit.atlassian.net/browse/GSD-723)\] - Umsetzung Web

Verbesserung
------------

*   \[[GSD-523](https://dreebit.atlassian.net/browse/GSD-523)\] - GSD Measurement Control: zweite Y-Achse
*   \[[GSD-661](https://dreebit.atlassian.net/browse/GSD-661)\] - Eingabefelder in den Views Service und Settings können weniger breit sein

## [0.5.81] - 2020-01-08

Verbesserung
------------

*   \[[GSD-654](https://dreebit.atlassian.net/browse/GSD-654)\] - Inhalt "System Status" mit Abstand darstellen
*   \[[GSD-660](https://dreebit.atlassian.net/browse/GSD-660)\] - Parameter Manager: Weiterleiten nur möglich bei Adress-Typ "Prisma Web API"

Bug
---

*   \[[GSD-639](https://dreebit.atlassian.net/browse/GSD-639)\] - Lade/Loading in UI vertauscht bei deutscher oder englische Spracheinstellung
*   \[[GSD-643](https://dreebit.atlassian.net/browse/GSD-643)\] - Vakuum-Widget: Ausgabe von "null" in Y-Achse
*   \[[GSD-644](https://dreebit.atlassian.net/browse/GSD-644)\] - Versatz im Widget Vakuum
*   \[[GSD-656](https://dreebit.atlassian.net/browse/GSD-656)\] - Parameter Manager: Verbundene Parameter bei zusammengesetzten Parametern werden nicht angezeigt oder sind einstellbar

## [0.5.80] - 2020-01-03

### Added
- Change system time within system settings (requires host os update)

### Changed
- Device forms improved
- Recipe: Update forms improved

### Issues
- GSD-387	Automatische Aktualisierung der Werte nach Übernahme neuer Werte
- GSD-457	Integration der Systemzeit in RTC-Modul	
- GSD-503	Druckwert (exp. Werte generell) darstellen mit E anstatt e	
- GSD-508	GSD Device Ventile: Darstellung im Devicetree an Bedingung knüpfen
- GSD-517	GSD Measurement Control: Statusmeldung ändern
- GSD-518	GSD Meassurement Control: Steuerbuttons und Druckanzeige einfügen	
- GSD-519	GSD Mesurement Control: Rezeptnamen und Rezepttyp anzeigen	
- GSD-520	GSD Measurement Control Dropdown umbenennen
- GSD-521	GSD Rezept erstellen / konfigurieren Dialog anpassen	
- GSD-522	GSD Measurment Control: Log und Lin Umschaltung bei beiden Rezepttypen	
- GSD-628	Netzwerkeinstellungen abspeichern	
- GSD-629	Parameter Werte in Exp. Schreibweise	

## [0.5.76] - 2019-12-10

### Changed
- Recipe creation form

## [0.5.74] - 2019-12-04

### Added
- Sytem Settings: Time (beta)

### Changed
- Heater Widget improved
- Measurement Dashboard
- Device Settings
- Service Menu
- DWell times select options
- Navigation improvements

## [0.5.71] - 2019-10-22

### Added
- Sytem Info: Firmware Version
- Sytem Info: Parameter Database Version

### Changed
- Recipe update form

## [0.5.69] - 2019-10-22
### Changed
- Recipe create and update form

## [0.5.68] - 2019-10-17
### Changed
- Data DB cleared on start up

## [0.5.65] - 2019-10-07
### Changed
- Control panel: Heating widget parameter changed

## [0.5.63] - 2019-09-30
- Status number colors changed

## [0.5.59] - 2019-09-23
### Added
- Control panel: Autostart Widget
- Unit W added
### Changed
- Modbus communication extention for more than 125 parameters
- Control panel: Heating widget extended
- Config database and parameter database changes

## [0.5.52] - 2019-09-20
### Added
- Translation Service integration
- Parameter Manger Import / Export
### Changed
- Mobus queue improvements
- Form improvements

## [0.5.29] - 2019-07-26
### Changed
- Update Script

## [0.5.28] - 2019-07-26
### Added
- Update Script

### Changed
- Section about "CHANGELOG".
