||Daten|
|:---|---:|
|**Name**|Justus Decker|
|**Ausbildung**|Elektroniker fuer Betriebstechnik|
|**Zeitraum**|$07.04.2026 - 30.04.2026$|
|**Zusammenfassung-Nr.**|$1$|
|**Umschulungsjahr**|$1/2$|
|**Wochen-Zusammenfassungen**|$1, 2, 3, 4$|
***

# Was fehlt?
* Elektrisches Feld
* Magnetisches Feld
* *3.1 Wechselstrom* Formeln
* PURI - Ersetzt *6. URI*

### 1. Strom und Gefahr

#### 1.1 Sicherheitsregeln
Freischalten, Gegen Wiedereinschalten sichern, Spannungsfreiheit prüfen, Erden & Kurzschließen, Abdecken / Abschranken.
#### 1.2 Strom ist
* geruchslos
* geräuschlos
* unsichtbar
* schnell
* leicht zu transportieren
* leichte Umwandlung in andere Energieformen - Siehe thermisch, kinetisch.
* ohne Rückstände einsetzbar
#### 1.3 Elektrischer Schlag
Beim elektrischen Schlag ist der Körperstrom und die Dauer entscheidend.
|Strom|Wirkung|
|:---:|---|
|1mA|Reizschwelle|
|5mA|Elektrisieren|
|15mA|Krampfschwelle|
|50mA|Gefahrenschwelle|
|80mA|Todesschwelle - 0.3 - 1s wahrscheinlich|

### 2. Spannung $U$
Potentialunterschied zwischen zwei Punkten.

#### 2.1 Spannungsarten
* **AC**: Wechselspannung, Drehstrom
* **DC**: Gleichspannung
* **UC**: Mischspannung

#### 2.2 Wechselspannung
* Effektivwert: $U_{eff} = \frac{û}{\sqrt{2}}$
* Amplitude: $û = U_{eff}*\sqrt{2}$
* Spitze-Spitze: $2 * û$

### 3. Strom $I$
#### 3.1 Stromrichtung
* technisch: $+$ nach $-$
* physikalisch: $-$ nach $+$
#### 3.2 Wechselstrom
*Effektivwert*, *Amplitude* & *Spitze-Spitze*
> [!CAUTION]
> Formel fehlt

### 4. Widerstand
* **Leiterwiderstand**: $\frac{l}{\gamma * A}$
* **Fehlenden Widerstand berechnen (Parallelschaltung)**: $\frac{1}{\frac{1}{R_{ges}}-(\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}})}$
* **Widerstand in einer Parallelschaltung**: $R_0 = \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}}}$
* **Widerstand in einer Reihenschaltung**: $R_0 = R_1 + R_2 + R_{...}$
* **Fehlenden Widerstand berechnen (Reihenschaltung)**: $R_2 = R_0 - R_1$

### 5. Schaltungen
> 
> * **Parallel**: Spannung $U$ bleibt gleich. Der Strom $I_0$ summiert sich aus Teilströmen.
> * **Reihe**: Strom $I$ bleibt gleich. Die Spannung $U_0$ summiert sich aus den Teilspannungen.
> * **Misch**

> [!CAUTION]
> Hier fehlen noch Nachteile!

### 6. PURI
* **U**: $U = R * I$
* **R**: $R = \frac{U}{I}$
* **I**: $I = \frac{U}{R}$

> [!CAUTION]
> Formeln für P fehlen

### 7. E-Reihen
Lässt sich berechnen: $R_n = \sqrt[E]{10^n} \quad \text{oder} \quad R_n = 10^{\frac{n}{E}}$ - Mehr dazu [hier](https://de.wikipedia.org/wiki/E-Reihe)

### 8. Elektrisches Feld

### 9. Magnetisches Feld
* **Ablenkkraft**: $F = B * I * l$
* **Magnetische Feldstärke**
* **Dauermagnet**: Erzeugt ohne Energiezufuhr ein *magnetisches Feld*
* **Homogenes magnetisches Feld**: Identische Flussdichte, Gleiche Richtung - Parallelität und Aquidistanz
* **neutrales Eisen im Wirkungsbereich**: *Ausrichtung der Elementarmagnete*, *Magnetische Influenz*, *Kraftwirkung*.
* **bifilare Spule**: Erzeugte Magnetfelder sind gleich groß, aber entgegengesetzt und heben sich auf.
* **Vorteile Elektromagneten**: Richtung, Betriebszustand & Stärke variabel
#### 9.1 Ursachen für Ablenkkraft
* Richtung des fremden Magnetfeldes
* Stromrichtung des eigenen Magnetfeldes

#### 9.2 Verstärkung - Einflussgrößen
* Leiterstrom
* Leiterlänge
* Magnetische Flussdichte

### 10. WiSo

### 11. Elektrische Leistung
Das Produkt aus Strom $I$ und Spannung $U$

### 12. Elektrische Energie und Arbeit
* $W = U * I * t$

### 13. Induktion
Die Induktion ist stets so gerichtet, dass sie der Ursache entgegen wirkt.

* **Induktionsspannung**: $U_i = -N\frac{\Delta \phi}{\Delta t}$

#### 13.1 Induktionsarten ($\phi$ ändern)
* **Bewegungsinduktion**
    * Bewegung der Spule
    * Bewegung des Magnetfeldes
* **Ruheinduktion**
    * Stromstärke
    * Richtung des Stroms
    * Schalten
    * Wechselstrom

### 14. Wirkungsgrad
|Wirkungsgrad|$P_v = P_{zu} - P_{ab}$|
|---|---|
|$\eta$|Wirkungsgrad / Leistungsverhältnis|
|$P_{ab}$|Leistungsabgabe|
|$P_{zu}$|Leistungsaufnahme|
|$P_v$|Verlustleistung|
|$P_N$|Bemessungsleistung|

> [!NOTE]
> Bei Elektromotor ist $P_N$ die an der Welle abgegebene $P_{ab}$

### L. Wichtige Begriffe
* Ohmsches Gesetz
* kichhoffsches Gesetz
* Lenzsche-regel
* Schraubenregel
* Spulenregel
* UVW-regel
* Hyperbel
