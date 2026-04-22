||Daten|
|:---|---:|
|**Name**|Justus Decker|
|**Ausbildung**|Elektroniker fuer Betriebstechnik|
|**Zeitraum**|$07.04.2026 - 30.04.2026$|
|**Zusammenfassung-Nr.**|$1$|
|**Umschulungsjahr**|$1/2$|
|**Wochen-Zusammenfassungen**|$1, 2, 3, 4$|
***

## 1. Strom und Gefahr

> [!CAUTION]
> Freischalten, Gegen Wiedereinschalten sichern, Spannungsfreiheit prüfen, Erden & Kurzschließen, Abdecken / Abschranken.

> [!WARNING]
> #### Strom ist:
> * geruchslos
> * geräuschlos
> * unsichtbar
> * schnell
> * leicht zu transportieren
> * leichte Umwandlung in andere Energieformen - Siehe thermisch, kinetisch.
> * ohne Rückstände einsetzbar

> [!NOTE]
> Beim elektrischen Schlag ist der Körperstrom und die Dauer entscheidend.
> |Strom|Wirkung|
> |:---:|---|
> |1mA|Reizschwelle|
> |5mA|Elektrisieren|
> |15mA|Krampfschwelle|
> |50mA|Gefahrenschwelle|
> |80mA|Todesschwelle - 0.3 - 1s wahrscheinlich|

## 2. Formeln

* **Leiterwiderstand**: $\frac{l}{\gamma * A}$
* **Wechselspannung**: *Effektivwert*, *Amplitude* & *Spitze-Spitze*
    * **Spannung**
        * Effektivwert: $U_{eff} = \frac{û}{\sqrt{2}}$
        * Amplitude: $û = U_{eff}*\sqrt{2}$
        * Spitze-Spitze: $2 * û$
    * **Strom**
        * Folgt
* **URI**:
    * **U**: $U = R * I$
    * **R**: $R = \frac{U}{I}$
    * **I**: $I = \frac{U}{R}$
* **Fehlenden Widerstand berechnen (Parallelschaltung)**: $\frac{1}{\frac{1}{R_{ges}}-(\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}})}$
* **Widerstand in einer Parallelschaltung**: $R_0 = \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}}}$
* **Widerstand in einer Reihenschaltung**: $R_0 = R_1 + R_2 + R_{...}$
* **Fehlenden Widerstand berechnen (Reihenschaltung)**: $R_2 = R_0 - R_1$
    
## 3. Grundbegriffe
* **Spannung**: Potentialunterschied zwischen zwei Polen.
* **Spannungsarten**
    * **AC**: Wechselspannung, Drehstrom
    * **DC**: Gleichspannung
    * **UC**: Mischspannung
* **Stromrichtungen**
    * **technische Stromrichtung**: $+$ nach $-$
    * **elektronische Stromrichtung**: $-$ nach $+$
* **Einheiten umrechnen**
    * **von klein zu groß**: $\frac{Wert}{1000}$
    * **von groß zu klein**: $Wert * 1000$
* **Schaltungen**
    * **Parallel**: Spannung $U$ bleibt gleich. Der Strom $I_0$ summiert sich aus Teilströmen.
    * **Reihe**: Strom $I$ bleibt gleich. Die Spannung $U_0$ summiert sich aus den Teilspannungen.
        * Nachteile einfügen
    * **Misch**
* **E-Reihen**: Mehr dazu [hier](https://de.wikipedia.org/wiki/E-Reihe)

