# Vzorový firmware Repetier pro 3D tiskárnu RebeliX s elektronikou RUMBA a dvěma extrudéry

## Vzorová konfigurace

* Elektronika: [RUMBA](http://reprap.org/wiki/RUMBA)
* Drivery: 6x DRV8825 (microstepping 1/32)
* Heatbed: ano (svorkovnice HB-OUT)
* Ventilátor na chlazení objektů: ano, 2x (svorkovnice FAN0, FAN1)
* Hotend: 2x RebelMOD v3.0 (svorkovnice HE0, HE1)
* Řemeničky: GT2/20
* Závitové tyče: M5
* Motory: X,Y,Z (SX17-1003), E (SX17-1005), druhý motor osy Z připojte na driver extruderu 2!
* Termistory: 100k NTC, Beta = 3950
* LCD: RepRapDiscount Full Graphic Smart Controller 128x64
* LED osvětlení: ano (svorkovnice HE2)
* EEPROM: Povolena
* Teplota hotendu: MAX 248°C (omezení kvůli teflonové vložce heatbreaku)

Úpravy ve firmware dělejte přes konfigurátor [http://www.repetier.com/firmware/v092](http://www.repetier.com/firmware/v092).

## Zapojení elektroniky

Prozatím generické schéma zapojení, časem přidám konkrétní zapojení.

![alt tag](http://reprap.org/mediawiki/images/1/17/Rumba4.jpg)

## Ovládání tiskárny

AstroPrint

* [Ovládání tiskárny přes WiFi či ethernet vč. záznamu tisku za pomoci Raspberry Pi](https://www.astroprint.com/)

Repetier-Host:

* [Repetier-Host pro Windows/Linux/Mac](https://www.repetier.com/download-now/)

Pronterface:

* [Pronterface pro Windows/Mac] (http://koti.kapsi.fi/~kliment/printrun/)
* [Pronterface pro Linux] (http://reprap.org/wiki/Printrun)
