<!--
author:   KRE-DSS

email:    

version:  0.0.1

language: de

narrator: Deutsch Female

classroom: disable

comment:  Try to write a short comment about
          your course, multiline is also okay.

link:     

script:   
-->

# Titration von Essig

[![Shield](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

## Vorbereitung

    {{1-2}}
**********
Materialien
============

Kontrolliere, ob du alle benötigten Materialien auf deinem Tisch hast. Kreuze ab.

-[ ] Mobile-CASSY
-[ ] pH-Box
-[ ] Verbindungskabel
-[ ] pH-Elelktrode
-[ ] Magnetrührer
-[ ] Magnetrührstab
-[ ] Stativ
-[ ] [Muffe 2x](https://de.wikipedia.org/wiki/Doppelmuffe#/media/Datei:Stainless_steel_laboratory_bossheads_13mm.jpg)
-[ ] Klemme 2x
-[ ] Becherglas 50 ml
-[ ] [Vollpipette 10 ml 2x](https://de.wikipedia.org/wiki/Pipette#/media/Datei:Pipette-LF.jpg)
-[ ] [Pipettierhilfe](https://de.wikipedia.org/wiki/Pipettierhilfe#/media/Datei:Pipettierhilfen.jpg)
**********

    {{2-3}}
**********
Chemikalien
=============

+ `Essigsäure` und `Natronlauge` (c = 0,1 mol/L) werden auf dem Lehrerwagen bereitgestellt
+ Bring die Chemikalienflaschen zum Arbeiten zu deinem Platz
+ Verschließe die Flaschen wieder mit dem Deckel und stelle sie zurück

**********
    {{3}}
**********
Aufbau
=============

Baue den Versuch folgendermaßen auf:

![Titration Essig mit Natronlauge](/media/Titration-NaOH-vinager.svg)

 <a href="https://commons.wikimedia.org/wiki/User:Muskid">Muskid</a>, <a href="https://commons.wikimedia.org/wiki/File:Titration-NaOH-HCl.svg">Titration-NaOH-HCl</a>, "Sonde" durch "pH-Elektrode" und "Salzsäure" durch "Essig" ersetzt von KRE, <a href="https://creativecommons.org/licenses/by-sa/4.0/legalcode" rel="license">CC BY-SA 4.0</a> 

 -[ ] Fülle die Bürette mit Natronlauge bis zur 0-mL-Marke
 -[ ] Lasse die Natronlauge in der Bürette in ein Abfall-Becherglas bis zur 4-mL-Marke ab. Entsorge die Natronlauge im Abguss.
 -[ ] Gib in das 50-mL-Becherglas 10 mL Essiglösung und den Magnetrührstab
 -[ ] Schalte den Magnetrührer ein und stelle eine langsame Geschwindigkeit ein
 -[ ] Hänge die pH-Elektrode so in die Flüssigkeit, dass sie den Magnetrührstab nicht berührt

**********

## Durchführung und Beobachtungen
<!--
calc: <script input="number" default="@0">@input</script>
-->

-[ ] Trage den ersten Messwert in die Tabelle ein
-[ ] Gib 0,5 mL Natronlauge zu, warte bis sich der Messwert nicht mehr verändert und trage den Wert in die Tabelle ein
-[ ] Wiederhole den letzten Schritt bis zur 24 mL-Marke
-[ ] Speichere den Titrationsgraphen in OneNote (Download oder Screenshot)

<!-- data-type="line" -->
| Volumen [mL] | pH-Wert |
|---|---|
| 0.0 | @calc(?)  |
| 0.5 | @calc(?)  |
| 1.0 | @calc(?)  |
| 1.5 | @calc(?)  |
| 2.0 | @calc(?)  |
| 2.5 | @calc(?)  |
| 3.0 | @calc(?)  |
| 3.5 | @calc(?)  |
| 4.0 | @calc(?)  |
| 4.5 | @calc(?)  |
| 5.0 | @calc(?)  |
| 5.5 | @calc(?)  |
| 6.0 | @calc(?)  |
| 6.5 | @calc(?)  |
| 7.0 | @calc(?)  |
| 7.5 | @calc(?)  |
| 8.0 | @calc(?)  |
| 8.5 | @calc(?)  |
| 9.0 | @calc(?)  |
| 9.5 | @calc(?)  |
| 10.0 | @calc(?)  |
| 10.5 | @calc(?)  |
| 11.0 | @calc(?)  |
| 11.5 | @calc(?)  |
| 12.0 | @calc(?)  |
| 12.5 | @calc(?)  |
| 13.0 | @calc(?)  |
| 13.5 | @calc(?)  |
| 14.0 | @calc(?)  |
| 14.5 | @calc(?)  |
| 15.0 | @calc(?)  |
| 15.5 | @calc(?)  |
| 16.0 | @calc(?)  |
| 16.5 | @calc(?)  |
| 17.0 | @calc(?)  |
| 17.5 | @calc(?)  |
| 18.0 | @calc(?)  |
| 18.5 | @calc(?)  |
| 19.0 | @calc(?)  |
| 19.5 | @calc(?)  |
| 20.0 | @calc(?)  |

## Calculator
<!--
i: <script input="number">let i = @input</script>
-->
<script input="number" value="1" min="0" max="1000000">
let i = @input // direct usage as a number
let k = @input

"Square of " + i + " = " + i * k
</script>