[![Version](https://img.shields.io/badge/Symcon-PHPModul-red.svg)](https://www.symcon.de/service/dokumentation/entwicklerbereich/sdk-tools/sdk-php/)
[![Version](https://img.shields.io/badge/Symcon%20Version-5.5%20%3E-green.svg)](https://www.symcon.de/forum/threads/30857-IP-Symcon-5-1-%28Stable%29-Changelog)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  


# Symcon-Modul: ABB EQ Energy Meter B-Serie <!-- omit in toc -->  

## Inhaltsverzeichnis <!-- omit in toc -->

- [1. Funktionsumfang](#1-funktionsumfang)
- [2. Voraussetzungen](#2-voraussetzungen)
- [3. Software-Installation](#3-software-installation)
- [4. Einrichten der Instanzen in IP-Symcon](#4-einrichten-der-instanzen-in-ip-symcon)
- [5. Anhang](#5-anhang)
  - [1. GUID der Module](#1-guid-der-module)
  - [2. Changelog](#2-changelog)
- [6. Lizenz](#6-lizenz)

## 1. Funktionsumfang

Modul zum Einbinden der ABB Stromzähler der B-Serie über ModBus RTU (RS485) in IP-Symcon. Durch eine blockweise Auslesung der ModBus Register wird eine schnellere Auslesung und geringere Systemlast erzielt. Es können mehrere Zähler auf einem physikalischen RS485-Bus betrieben werden.  

Folgende Module beinhaltet das ABBEnergyMeter Repository:

- __ABB B23/B24 Steel__ ([Dokumentation](ABBB23Steel))

	Symcon-Modul zum Einbinden der ABB Stromzähler B23 112-100 und B24 112-100 mit ModBus RTU (RS485).

- __ABB B23/B24 Silver__ ([Dokumentation](ABBB23Silver))

	Symcon-Modul zum Einbinden der ABB Stromzähler B23 312-100 und B24 312-100 mit ModBus RTU (RS485).

## 2. Voraussetzungen

- IP-Symcon ab Version 5.5
- unterstützte Zähler
- ModBus RTU Schnittstelle (RS485)

## 3. Software-Installation

* Über den Module Store das 'ABB Energy Meter'-Modul installieren.
* Alternativ über das Module Control die URL dieses Repositories

## 4. Einrichten der Instanzen in IP-Symcon

Ist direkt in der Dokumentation der jeweiligen Module beschrieben.  

## 5. Anhang

###  1. GUID der Module

 
| Modul   | Typ    | Prefix  | GUID                                   |
| :-----: | :----: | :-----: | :------------------------------------: |
| ABBB23Sliver | Device | ABBEM | {F315CAC7-57EF-E5E8-97DA-A561A5AEA628} |
| ABBB23Steel  | Device | ABBEM  | {C38A4827-563E-57E8-0FF2-7E0B2E4C235F} |



### 2. Changelog

Version 1.0:  
 - Erstes offizielles Release  


## 6. Lizenz ##
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is a derivative of [Symcon-Modul: B+G E-Tech](https://github.com/Nall-chan/BGETech) by [Nall-chan](https://github.com/Nall-chan) used under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

 