# OpenKNX SmartIrrigation Applikation

Eine intelligente KNX-basierte Bewässerungssteuerung, die Bewässerungszonen auf Basis von Echtzeit-Wetterdaten, Vorhersagen und Evapotranspiration (ET0) automatisch steuert.

Funktionsumfang:

- Bis zu 10 Bewässerungszonen mit individueller Konfiguration
- Wetterbasierte Bewässerung (Temperatur, Regen, Luftfeuchtigkeit, Wind, Bodenfeuchtigkeit, UV)
- Wettervorhersagen (aktuell, +48h, +7d)
- Evapotranspiration (ET0) Berechnung
- Konfigurierbare Bewässerungsmodi (automatisch/wetterbasiert, zeitbasiert, manuell)
- Sicherheitsfunktionen: Ventilrückmeldung, Frostsicherung, Durchflusssensor, Tanküberwachung
- Intelligente Planung: Sonnenstandbasierte Zeitfenster, Einweichzyklen, Ruhetage
- Komfortfunktionen: Aktivitätserkennung, Wochentagfilter, Saisonsteuerung, Windpause

## Anwendungsdokumentation

Die detaillierten Beschreibungen der Anwendung sind in folgenden Abschnitten zu finden:

- [OpenKNX Applikationsbeschreibung](https://github.com/OpenKNX/OGM-Common/blob/v1/doc/Applikationsbeschreibung-Common.md)
- [Konfigurationstransfer](https://github.com/OpenKNX/OFM-ConfigTransfer/blob/v1/doc/Applikationsbeschreibung-ConfigTransfer.md)
- [Smart Irrigation Modul](https://github.com/OpenKNX/OFM-SmartIrrigationModule) - Bewässerungssteuerung und Zonenkonfiguration
- [Logikmodule](https://github.com/OpenKNX/OFM-LogicModule/blob/v1/doc/Applikationsbeschreibung-Logik.md)
- [Funktionsblöcke](https://github.com/mgeramb/OFM-FunctionBlocks/blob/v1/doc/Applikationsbeschreibung-FunctionBlocks.md)

## Firmware

Eine vorkompilierte Firmware ist [hier](https://github.com/OpenKNX/OAM-SmartIrrigation/releases) zu finden. ZIP-Datei herunterladen, entpacken und der Anleitung im Readme folgen.

## Hardware

Die vorkompilierte Firmware unterstützt:

- [OpenKNX REG1-BASE V1](https://github.com/OpenKNX/OpenKNX/wiki/REG1-Base) (RP2040)

## Lizenz

Diese Software steht unter der [AGPL-3.0](LICENSE).
