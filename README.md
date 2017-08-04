# Vzorový firmware Repetier pro 3D tiskárnu RebeliX s elektronikou RUMBA a dvěma extrudéry

## Vzorová konfigurace

* Elektronika: [RUMBA](http://reprap.org/wiki/RUMBA)
* Drivery: 6x DRV8825 (microstepping 1/32)
* Heatbed: ano (svorkovnice HB-OUT)
* Ventilátor na chlazení objektů: ano, 2x (svorkovnice FAN0, FAN1)
* Hotend: 2x RebelMOD v3.0 (svorkovnice HE0, HE1)
* Řemeničky: GT2/20
* Závitové tyče: TR8x8 
* Motory: X,Y,Z (SX17-1003), E (SX17-1005), druhý motor osy Z připojte na driver extruderu 2!
* Termistory: 100k NTC, Beta = 3950
* LCD: RepRapDiscount Full Graphic Smart Controller 128x64
* LED osvětlení: ano (svorkovnice HE2)
* EEPROM: povolena (nezapomeňte po instalaci firmwaru data z EEPROM načíst)
* Teplota ext1 hotendu: MAX 248°C (omezení kvůli teflonové vložce heatbreaku)
* Teplota ext2 hotendu: MAX 260°C (vhodné pro PETG)



## Zapojení elektroniky

Prozatím generické schéma zapojení, časem přidám konkrétní zapojení.

![alt tag](http://reprap.org/mediawiki/images/1/17/Rumba4.jpg)

## Ovládání tiskárny přes WiFi či ethernet vč. záznamu tisku za pomoci Raspberry Pi

Remote přístup/load
* [OctoPrint](http://octoprint.org/)


## Slicer

Osobně používám placený Simplify3D, který je na špičce pomyslného žebříčku slicerů,zejména podpory jsou tam dobre udelane

* [Simplify3D - placený](https://www.simplify3d.com/)
* [Slic3r - zdarma](http://slic3r.org/)
