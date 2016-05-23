# Vzorový firmware Repetier pro 3D tiskárnu RebeliX 

## Vzorová konfigurace

* Elektronika: Arduino Mega 2560 + RAMPS 1.4
* Drivery: DRV8825 (microstepping 1/32)
* Heatbed (svorkovnice D10)
* Ventilátor na chlazení objektů (svorkovnice D9)
* Hotend: RebelMOD v3.0 (svorkovnice D8)
* Řemeničky: GT2/20
* Motory: X,Y,Z (SX17-1003), E (SX17-1005)
* Termistory: 100k NTC, Beta = 3950
* LCD: RepRapDiscount Full Graphic Smart Controller 128x64
* EEPROM: Povolena
* Teplota hotendu: MAX 248°C (omezení kvůli teflonové vložce heatbreaku)

Úpravy ve firmware dělejte přes konfigurátor [http://www.repetier.com/firmware/v092](http://www.repetier.com/firmware/v092).

## Zapojení elektroniky

[Návod](http://reprap4u.cz/navod-na-stavbu-3d-tiskarny-rebelix/)

## Ovládání tiskárny

Repetier-Host:

* [Repetier-Host pro Windows/Linux/Mac](https://www.repetier.com/download-now/)

Pronterface:

* [Pronterface pro Windows/Mac] (http://koti.kapsi.fi/~kliment/printrun/)
* [Pronterface pro Linux] (http://reprap.org/wiki/Printrun)