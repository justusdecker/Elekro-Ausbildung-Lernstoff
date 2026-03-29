# Widerstände Farbcodes

## Die Berechnung funktioniert wie folgt

### 4-stellig

$R = (Z_1 | Z_2) * 10^M \Omega$

### 5-stellig

$R = (Z_1 | Z_2 | Z_3) * 10^M \Omega$

### Beispiel:

`Braun, Schwarz, Schwarz, Rot & Braun`, also einen Widerstand mit 5 Ringen.

$1 | 0 | 0 = 100\Omega$

Als nächstes die Nullen:

$100 * 10^2 = 10000 \Omega$

Jetzt noch die Toleranz:

Diese ist einfach abzulesen!
Braun ist $\pm 1%$

## Übersicht

|Farbe|1. Ring|2. Ring|3. Ring|Multiplikator|Toleranz|
|---|---|---|---|---|---|
|Schwarz|$0$|$0$|$0$|$1 \Omega$||
|Braun|$1$|$1$|$1$|$10 \Omega$|$\pm 1\%$|
|Rot|$2$|$2$|$2$|$100 \Omega$|$\pm 2\%$|
|Orange|$3$|$3$|$3$|$1k \Omega$||
|Gelb|$4$|$4$|$4$|$10k \Omega$||
|Grün|$5$|$5$|$5$|$100k \Omega$|$\pm 0.5\%$|
|Blau|$6$|$6$|$6$|$1M \Omega$|$\pm 0.25\%$|
|Lila|$7$|$7$|$7$|$10M \Omega$|$\pm 0.1\%$|
|Grau|$8$|$8$|$8$||$\pm 0.05\%$|
|Weiß|$9$|$9$|$9$|||
|Gold||||$0.1 \Omega$|$\pm 5\%$|
|Silber||||$0.01 \Omega$|$\pm 10\%$|

![Farbcodes](https://www.leifiphysik.de/sites/default/files/2020/12/image/Schichtwiderst%C3%A4nde_Farbcode_von_Widerst%C3%A4nden_0.svg)