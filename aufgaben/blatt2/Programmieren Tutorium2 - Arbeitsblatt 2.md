# **Programmieren Tutorium \- Arbeitsblatt 2**

# **Wiederholung 0**

# a) Die Variable foo enthält eine ganze Zahl. Übersetzen Sie: Wenn foo größer 5 oder wenn sie kleiner ‐8 ist, wird die Hälfte von foo ausgegeben. Andernfalls wird foo mit 10 multipliziert. 

# b) Die Variable dzahl ist eine Gleitkommazahl, st ein String. Übersetzen Sie: Solange dzahl kleiner oder gleich 11,3 ist, wird das gemacht: An st wird ein Ausrufezeichen angehängt und dzahl um 1 größer gemacht. 

# c) Für Fortgeschrittene: die Variable t1 ist vom Typ string, anz von Typ int. Übersetzen Sie: Für jedes Zeichen von t1 wird das gemacht: Wenn das Zeichen ein Kleinbuchstabe ist, wird der Wert von anz um 1 erhöht. Tipp: Informieren Sie sich über die foreach‐Schleife. 

# d) Die Variablen i1 und i2 enthalten ganze Zahlen. Übersetzen Sie: Wenn die Differenz aus i1 und i2 kleiner oder gleich 2 ist, dann wird die Hälfte von i1 ausgegeben. Andernfalls wird i2 verdoppelt. 

# e) Die Variable d1 ist eine Gleitpunktzahl. Übersetzen Sie: Solange d1 größer als 5 ist, wird das gemacht: Der Wert von d1 wird um 3 vermindert. Wenn dann das Quadrat von d1 kleiner als 10 ist, wird das Dreifache von d1 ausgegeben.

# ***Wiederholung 1*****: Spritkosten-Rechner**

**Szenario:** Du planst eine lange Autofahrt und möchtest wissen, wie viel Geld du für Benzin ausgeben musst. Schreibe ein Programm, das den Preis für eine Fahrt basierend auf der Entfernung berechnet. Der Benzinverbrauch deines Autos ist **8.2 Liter pro 100 Kilometer**, und der Preis pro Liter Benzin beträgt **1.82 Euro**.

**Aufgabe**: Lass den Benutzer die Entfernung in Kilometern (`km`) eingeben. Berechne dann die Gesamtkosten der Fahrt basierend auf den vorgegebenen Werten für den Verbrauch und den Preis pro Liter Benzin und gib das Ergebnis aus.

# ***Wiederholung 2*****: Wer ist älter?**

**Szenario:** Du und deine Freundin/Freund `Y` seid neugierig, wer von euch älter ist. Schreibe ein Programm, das euer Alter vergleicht und anzeigt, wer älter ist, oder ob ihr gleich alt seid.

**Aufgabe**: Lass den Benutzer zwei Altersangaben eingeben: Dein Alter und das von `Y`. Vergleiche die beiden Alterswerte und gib eine passende Nachricht aus, wer älter ist oder ob ihr gleich alt seid. Gebe auch die Altersdifferenz aus.

# **Aufgabe 1: Rückwärtszählen in 10er-Schritten**

**Szenario:** Schreibe ein Programm, das mit einer `while`\-Schleife die Zahlen von 100 bis 0 in 10er-Schritten rückwärts auf der Konsole ausgibt.

**Aufgabe**: Verwende eine `while`\-Schleife, um von 100 rückwärts zu zählen, bis die Zahl 0 erreicht ist. Reduziere die Zahl in jeder Runde um 10\.

# **Aufgabe 1b: For Schleife**

**Szenario:** Schreibe ein Programm, das mit einer `for`\-Schleife die Zahlen von 100 bis 0 in 10er-Schritten rückwärts auf der Konsole ausgibt.

**Aufgabe**: Verwende eine `for`\-Schleife, um von 100 rückwärts zu zählen, bis die Zahl 0 erreicht ist. Reduziere die Zahl in jeder Runde um 10\.

# **Aufgabe 2: Berechne gerade Quadratzahlen bis 100**

**Szenario**: Schreibe ein Programm, das die Quadratzahlen von 1 bis 100 berechnet. Verwende eine for-Schleife, um die Quadratzahlen zu berechnen, und eine if-Bedingung, um nur die geraden Quadratzahlen auszugeben.

**Aufgabe**: Verwende eine for-Schleife, um die Quadratzahlen von 1 bis 100 zu berechnen. Wenn das Quadrat eine gerade Zahl ist, soll diese Zahl in der Konsole ausgegeben werden.

###  **Aufgabe 3: Zeichne ein Rechteck aus Sternen (mit For-Schleifen)**

**Szenario:** Schreibe ein Programm, das ein Rechteck aus Sternen (`*`) in der Konsole "zeichnet". Der Benutzer gibt die Höhe und Breite des Rechtecks ein, und das Programm zeichnet das entsprechende Rechteck.

**Aufgabe**: Lass den Benutzer die Höhe und Breite des Rechtecks eingeben. Verwende verschachtelte **Schleifen**, um das Rechteck Zeile für Zeile aus Sternen zu zeichnen.

## 

## **Aufgabe 4: Multiplikationstabelle erstellen**

*Info: string.**`PadLeft(4)`** sorgt dafür, dass die Zahlen in der Ausgabe gleichmäßig ausgerichtet werden, damit die Tabelle ordentlich aussieht.*

**Szenario:** Schreibe ein Programm, das eine **Multiplikationstabelle** von 1 bis 10 erstellt. Verwende dafür zwei **verschachtelte for-Schleifen**: eine Schleife für die Zeilen (Multiplikator) und eine Schleife für die Spalten (Multiplikand). Jede Zelle der Tabelle soll das Ergebnis der Multiplikation von Zeile und Spalte enthalten.

**Aufgabe**: Verwende verschachtelte for-Schleifen, um die Multiplikationstabelle (1 bis 10\) zu berechnen und auf der Konsole auszugeben.

**Multiplikationstabelle von 1-3**

**1	2	3**

**2	4	6**

**1	6	9**

# **Aufgabe 4b:**

Nutzer geben an, von welcher Zahl X bis zu welcher Zahl Y die Tabelle sein soll.

z.B ( 8 bis 11\)

# **Aufgabe 5: Finde die kleinste Zahl größer als 0**

**Szenario:** Der Benutzer soll mehrere Zahlen eingeben, und das Programm soll die **kleinste Zahl größer als 0** aus den eingegebenen Zahlen finden und ausgeben.

**Aufgabe**:

* Lasse den Benutzer eingeben, wie viele Zahlen er eingeben möchte.  
* Sammle die eingegebenen Zahlen in einer Schleife.  
* Verwende eine **if-Bedingung**, um die kleinste Zahl zu finden, die größer als 0 ist.  
* Gib die kleinste Zahl, die größer als 0 ist, in der Konsole aus.

Beispiel:

Eingabe: 2 8 9 \-1

Ausgabe: 2

Eingabe: \-1 \-99 \-2

Ausgabe: Keine Zahl größer 0