||Daten|
|:---|---:|
|**Name**|Justus Decker|
|**Ausbildung**|Elektroniker fuer Betriebstechnik|
|**Zeitraum**|$07.04.2026 - 30.04.2026$|
|**Zusammenfassung-Nr.**|$1$|
|**Umschulungsjahr**|$1/2$|
|**Wochen-Zusammenfassungen**|$1, 2, 3, 4$|
***

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
##### 1.3.1 Einflussfaktoren
*   **Körperwiderstand:** Abhängig von Hautfeuchte und Kontaktfläche; bestimmt die Stromhöhe.
*   **Spannungshöhe:** Höhere Spannungen durchschlagen den Hautwiderstand leichter.
*   **Stromweg:** Wege über das Herz (Hand-Hand) sind besonders lebensgefährlich.
*   **Einwirkdauer:** Je länger der Strom fließt, desto schwerer die Gewebeschäden.

##### 1.3.2 Grenzwerte & Schutz
*   **AC/DC:** Max. 50V AC oder 120V DC sind für Erwachsene zulässig.
*   **Frequenz:** 50Hz (Netzstrom) fördert Herzkammerflimmern besonders stark.

##### 1.3.3 Verhalten nach Unfall
*   **Eigenschutz:** Erst Anlage freischalten, dann Verunfallten retten.
*   **Ärztliche Hilfe:** EKG ist Pflicht, da Herzrhythmusstörungen verzögert auftreten können.

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
* Effektivwert: $I_{eff} = \frac{\hat{i}}{\sqrt{2}}$
* Amplitude: $\hat{i} = I_{eff} \cdot \sqrt{2}$
* Spitze-Spitze: $I_{ss} = 2 \cdot \hat{i}$
#### 3.3 Wirkungen des Stroms
* **Wärmewirkung:** Stromfluss erzeugt Hitze (z. B. Wasserkocher, Bügeleisen).
* **Magnetische Wirkung:** Strom erzeugt Magnetfelder (z. B. Elektromotor, Relais).
* **Chemische Wirkung:** Zersetzung von Stoffen (z. B. Galvanisieren, Akku laden).
* **Lichtwirkung:** Gase oder Halbleiter leuchten (z. B. LED, Glimmlampe).
#### 3.4 Messung
* **Reihenschaltung:** Strommesser müssen immer direkt in den Pfad eingebaut werden.
* **Stromdichte $J$:** Verhältnis Strom zu Leiterquerschnitt ($J = \frac{I}{A}$).

### 4. Widerstand
Gegenkraft, die den Stromfluss in einem Leiter begrenzt.
* **Leiterwiderstand**: $\frac{l}{\gamma * A}$
* **Fehlenden Widerstand berechnen (Parallelschaltung)**: $\frac{1}{\frac{1}{R_{ges}}-(\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}})}$
* **Fehlenden Widerstand berechnen (Reihenschaltung)** $R_x = R_{ges} - \sum R_{bekannt}$
* **Widerstand in einer Parallelschaltung**: $R_0 = \frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_{...}}}$
* **Widerstand in einer Reihenschaltung**: $R_0 = R_1 + R_2 + R_{...}$
* **Fehlenden Widerstand berechnen (Reihenschaltung)**: $R_2 = R_0 - R_1$

### 5. Schaltungen
#### 5.1 Reihenschaltung (Serienschaltung)
*   **Merkmale:** Strom $I$ ist überall gleich. Spannungen addieren sich ($U_{ges} = U_1 + U_2 \dots$).
*   **Vorteil:** Einfache Verdrahtung; alle Komponenten werden mit demselben Strom durchflossen.
*   **Nachteil:** Fällt ein Verbraucher aus (Unterbrechung), ist der gesamte Stromkreis unterbrochen.

#### 5.2 Parallelschaltung
*   **Merkmale:** Spannung $U$ ist überall gleich. Ströme addieren sich ($I_{ges} = I_1 + I_2 \dots$).
*   **Vorteil:** Unabhängigkeit der Verbraucher; fällt einer aus, funktionieren die anderen weiter.
*   **Nachteil:** Hoher Verdrahtungsaufwand; Gesamtstrom steigt mit jedem weiteren Verbraucher an.

#### 5.3 Mischschaltung (Gruppenschaltung)
*   **Kombination:** Besteht aus in Reihe und parallel geschalteten Widerständen.
*   **Analyse:** Muss schrittweise von innen nach außen in Ersatzwiderstände zusammengefasst werden.
*   **Anwendung:** Typisch für komplexe elektronische Schaltungen und Netzwerke.

### 6. PURI & das ohmsche Gesetz
Zusammenhang zwischen Spannung, Strom, Widerstand und Leistung.

#### 6.1 Ohmsches Gesetz (URI)
*   **U**: $U = R \cdot I$
*   **R**: $R = \frac{U}{I}$
*   **I**: $I = \frac{U}{R}$

#### 6.2 Elektrische Leistung (PUI)
*   **P**: $P = U \cdot I$ (Einheit: Watt $W$)
*   **U**: $U = \frac{P}{I}$
*   **I**: $I = \frac{P}{U}$

#### 6.3 Kombinierte Formeln
*   **P aus R und I:** $P = I^2 \cdot R$
*   **P aus U und R:** $P = \frac{U^2}{R}$

#### 6.4 Wirkungsgrad ($\eta$)
*   Verhältnis von abgegebener Leistung ($P_{ab}$) zu zugeführter Leistung ($P_{zu}$):
*   $\eta = \frac{P_{ab}}{P_{zu}}$

### 7. E-Reihen
Lässt sich berechnen: $R_n = \sqrt[E]{10^n} \quad \text{oder} \quad R_n = 10^{\frac{n}{E}}$ - Mehr dazu [hier](https://de.wikipedia.org/wiki/E-Reihe)

### 8. Elektrisches Feld
Raumzustand um geladene Körper, in dem Kräfte auf andere Ladungen wirken.

#### 8.1 Feldstärke $E$
Gibt an, wie stark die Kraftwirkung im Feld ist:
* **Formel:** $E = \frac{F}{Q}$ oder $E = \frac{U}{d}$
* **Einheit:** $\frac{V}{m}$ (Volt pro Meter) oder $\frac{N}{C}$ (Newton pro Coulomb).

#### 8.2 Feldlinien
Visualisierung der Kraftrichtung:
* **Richtung:** Immer von Plus nach Minus.
* **Eigenschaft:** Linien kreuzen sich nie; hohe Dichte bedeutet starkes Feld.

#### 8.3 Homogenes vs. Inhomogenes Feld
* **Homogen:** Feldstärke ist überall gleich (z. B. zwischen zwei parallelen Platten).
* **Inhomogenes:** Feldstärke ändert sich je nach Ort (z. B. bei einer einzelnen Punktladung).

#### 8.4 Elektrischer Fluss $\Phi$
Maß für die Gesamtzahl der Feldlinien, die eine Fläche durchsetzen.

### 9. Magnetisches Feld
#### 9.1 Grundlagen & Kraftwirkung
* **Ablenkkraft (Lorentzkraft):** Kraft auf einen stromdurchflossenen Leiter im Magnetfeld.
  * Formel: $F = B \cdot I \cdot l$
* **Dauermagnet:** Erzeugt permanent ein Feld ohne externe Energiezufuhr.
* **Homogenes Feld:** Feldlinien sind parallel und äquidistant (gleiche Stärke/Richtung überall).

#### 9.2 Materie im Magnetfeld
* **Neutrales Eisen:** Bewirkt Ausrichtung der Elementarmagnete (Magnetische Influenz) und erfährt Kraftwirkung.
* **Bifilare Spule:** Entgegengesetzte Wicklungen heben das Magnetfeld gegenseitig auf (induktionsfrei).

#### 9.3 Elektromagnetismus
* **Vorteile:** Feldstärke (über Strom), Polung (Richtung) und Betriebszustand (An/Aus) sind variabel steuerbar.
* **Ursachen der Ablenkkraft:** Resultiert aus der Überlagerung des Fremdfeldes mit dem Eigenfeld des Leiters.

#### 9.4 Verstärkung – Einflussgrößen
Die Kraft $F$ steigt linear mit:
*   Höherem **Leiterstrom** ($I$).
*   Größerer **Leiterlänge** ($l$) im Wirkungsbereich.
*   Stärkerer **Magnetischer Flussdichte** ($B$).

### 10. WiSo

### 11. Elektrische Leistung $P$
Das Produkt aus Strom $I$ und Spannung $U$. Einheit: Watt ($W$).

*   **Berechnung:** $P = U \cdot I$
*   **Zusammenhang:** Gibt an, wie viel elektrische Energie pro Zeitspanne umgesetzt wird.
*   **Abhängigkeit:** Steigt linear mit der Spannung oder der Stromstärke.

### 12. Elektrische Energie und Arbeit $W$
Beschreibt die über einen Zeitraum verrichtete elektrische Arbeit. Einheit: Wattsekunde ($Ws$) oder Joule ($J$); praxisnah Kilowattstunde ($kWh$).

*   **Grundformel:** $W = U \cdot I \cdot t$
*   **Alternative:** $W = P \cdot t$
*   **Messung:** Erfolgt im Haushalt oder Betrieb durch den Energiezähler (Stromzähler).

### 13. Induktion
Die Induktionsspannung entsteht durch die Änderung eines magnetischen Flusses in einer Leiterschleife.

* **Lenzsche Regel:** Die Induktion wirkt ihrer Ursache stets entgegen (daher das negative Vorzeichen).
* **Induktionsspannung:** $U_i = -N \cdot \frac{\Delta \Phi}{\Delta t}$
  * $N$: Windungszahl
  * $\frac{\Delta \Phi}{\Delta t}$: Geschwindigkeit der Flussänderung

#### 13.1 Induktionsarten ($\Phi$ ändern)

**Bewegungsinduktion (Induktion durch Flächenänderung)**
* **Mechanisch:** Relativbewegung zwischen Leiter und Magnetfeld (Generatorprinzip).
* **Beispiele:** Bewegung der Spule im Feld oder Rotation des Magneten.

**Ruheinduktion (Induktion durch Feldänderung)**
* **Transformatorprinzip:** Der Leiter ruht, aber das Magnetfeld ändert sich zeitlich.
* **Ursachen:** 
    * Änderung der Stromstärke im Primärkreis.
    * Richtungswechsel des Stroms.
    * Ein- und Ausschaltvorgänge.
    * Einsatz von Wechselstrom (stetige Feldänderung).

### 14. Wirkungsgrad $\eta$

Der Wirkungsgrad beschreibt das Verhältnis von nutzbringender abgegebener Leistung zur zugeführten Leistung. Er ist immer kleiner als 1 (bzw. 100 %).

| Formel | $P_v = P_{zu} - P_{ab}$ |
| :--- | :--- |
| **$\eta$ (Eta)** | Wirkungsgrad (Leistungsverhältnis) |
| **$P_{ab}$** | Abgegebene Leistung (Nutzleistung) |
| **$P_{zu}$** | Zugeführte Leistung (Aufnahmeleistung) |
| **$P_v$** | Verlustleistung (meist Wärme) |
| **$P_N$** | Bemessungsleistung (Nennleistung) |

#### 14.1 Wichtige Formeln
*   **Wirkungsgrad:** $\eta = \frac{P_{ab}}{P_{zu}}$
*   **Gesamtwirkungsgrad:** $\eta_{ges} = \eta_1 \cdot \eta_2 \cdot \dots$ (bei hintereinander geschalteten Systemen)

> [!NOTE]
> Bei einem Elektromotor entspricht die Bemessungsleistung $P_N$ immer der mechanisch an der Welle abgegebenen Leistung $P_{ab}$. Die elektrische Aufnahme $P_{zu}$ ist aufgrund der Verluste (Reibung, Wärme) stets höher.

### 15. Wichtige Begriffe

*   **Ohmsches Gesetz:** Beschreibt den linearen Zusammenhang zwischen Spannung, Strom und Widerstand ($U = R \cdot I$).
*   **Kirchhoffsche Gesetze:**
    *   **Knotenpunktregel:** Summe der zufließenden Ströme ist gleich der Summe der abfließenden Ströme.
    *   **Maschenregel:** In einem geschlossenen Umlauf ist die Summe aller Teilspannungen gleich Null.
*   **Lenzsche Regel:** Induktionsvorgänge wirken ihrer Ursache (z. B. Magnetfeldänderung) stets entgegen.
*   **Schraubenregel (Rechte-Hand-Regel):** Bestimmt die Richtung des Magnetfeldes um einen stromdurchflossenen Leiter.
*   **Spulenregel:** Bestimmt die Lage der Magnetpole (Nord/Süd) bei einer stromdurchflossenen Spule.
*   **UVW-Regel:** (Ursache-Vermittlung-Wirkung) Bestimmt die Kraftrichtung (Lorentzkraft) auf einen Leiter im Magnetfeld.
*   **Hyperbel:** Grafische Darstellung des Widerstandsverlaufs bei konstanter Leistung; beschreibt die indirekte Proportionalität.
*   **Spezifischer Widerstand ($\rho$):** Materialabhängiger Kennwert für den elektrischen Widerstand.
*   **Leitfähigkeit ($\gamma$):** Kehrwert des spezifischen Widerstands; Maß für den Stromfluss.
*   **Effektivwert:** Der Wert einer Wechselgröße, der die gleiche Wärmewirkung wie ein entsprechender Gleichwert erzielt.
*   **Amplitude:** Der maximale Ausschlag (Scheitelwert) einer Schwingung.
*   **Wirkungsgrad ($\eta$):** Verhältnis von abgegebener zu zugeführter Leistung; Maß für die Effizienz.
*   **Induktion:** Erzeugung einer Spannung durch Änderung des magnetischen Flusses.
*   **Magnetische Flussdichte ($B$):** Maß für die Stärke und Dichte eines Magnetfeldes.
*   **Lorentzkraft:** Die ablenkende mechanische Kraft auf bewegte Ladungen in einem Magnetfeld.