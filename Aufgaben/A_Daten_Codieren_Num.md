# Aufgaben

## 1. Erstellen sie eine leere Tabelle mit 6 Kolonnen und 16 Zeilen. Füllen sie diese wie folgt aus:
 1. Kolonne: Dezimalzahlen von 0 bis 15
 2. Kolonne: Hexadezimalzahlen von 0 bis F
 3. Kolonne, 4. Kolonne, 5. Kolonne und 6. Kolonne die entsprechenden Binärzahlen

Studieren sie nun ihre fertig ausgefüllte Tabelle, insbesondere die Kolonnen mit den 
Binärwerten. Was stellen sie fest?

#### Lösung
| Dezimal | Hexadezimal | Binär       | Binär       | Binär       | Binär       |
|---------|-------------|-------------|-------------|-------------|-------------|
| 0       | 0           | 0000        | 0000        | 0000        | 0000        |
| 1       | 1           | 0001        | 0001        | 0001        | 0001        |
| 2       | 2           | 0010        | 0010        | 0010        | 0010        |
| 3       | 3           | 0011        | 0011        | 0011        | 0011        |
| 4       | 4           | 0100        | 0100        | 0100        | 0100        |
| 5       | 5           | 0101        | 0101        | 0101        | 0101        |
| 6       | 6           | 0110        | 0110        | 0110        | 0110        |
| 7       | 7           | 0111        | 0111        | 0111        | 0111        |
| 8       | 8           | 1000        | 1000        | 1000        | 1000        |
| 9       | 9           | 1001        | 1001        | 1001        | 1001        |
| 10      | A           | 1010        | 1010        | 1010        | 1010        |
| 11      | B           | 1011        | 1011        | 1011        | 1011        |
| 12      | C           | 1100        | 1100        | 1100        | 1100        |
| 13      | D           | 1101        | 1101        | 1101        | 1101        |
| 14      | E           | 1110        | 1110        | 1110        | 1110        |
| 15      | F           | 1111        | 1111        | 1111        | 1111        |

Ich stelle fest, dass ich vier Kolonen für Binär-Zahl machen musste, welche aber immer dieselbe ist. Was meiner Meinung nach weniger Sinn ergibt.

Das Dezimalsystem ist "normal" (wie wir es im Alltag verwenden).

Das Hexa-Dezimal-System geht nicht auf 10 wie beim Dezimalsystem, sondern auf 16.

Das binäre System besteht nur aus "0" und "1". Die erste Stelle von Rechts hat den Wert 1. Dieser Wert wird nach links immer verdoppelt. Wenn die Ziffer durch eine "1" repräsentiert wird, dann wird diese gezählt. Bei einer "0" nicht. Sprich 0101 = 0 + 4 + 0 + 1 = 5 (Dezimal (und auch Hexadezimal hier))

## 2. Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende Binärzahl um: 911

#### Rechenweg

911 = 512 + 256 + 128 + 8 + 4 + 2 + 1 = 911

512 + 256 = 768
768 + 128 = 896
896 + 16 = 912
896 + 8 = 904 
904 + 4 + 2 + 1 = 911 

(Es gäbe einen anderen Rechenweg, bei welchem man die Zahl durch 2 rechnet und dann immer denn Rest, welcher nur 0 oder 1 ist nimmt, und so die Binärzahl erhält)

#### Lösung

911 = 0011 1000 1111

## 3. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 1011'0110

#### Rechenweg

1011 0110 = 2 + 4 + 16 + 32 + 128 = 1011 0110

2 + 4 + 16 = 22
32 + 128 = 160 

160 + 22 = 182

#### Lösung

1011 0110 = 182

## 4. Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Hexadezimalzahl um: 1110'0010'1010'0101

#### Rechenweg

1110 0010 1010 0101

1110 = 14 = E
0010 = 2  = 2
1010 = 10 = A
0101 = 5  = 5

E2A5

#### Lösung

1110 0010 1010 0101 = E2A5

## 5. Was ergibt die Addition der beiden binären Zahlen 1101'1001 und 0111'0101?
Beachten sie, dass für das Resultat ebenfalls nur 8 Binärstellen zur Verfügung 
stehen.

#### Rechenweg

1101 1001 +
0111 0101 = 2 + 4 + 8 + 32 + 32 + 128 + 128 = 256 + 64 + 14 = 334 = 0001 0100 1110

#### Lösung

Da nur 8 Binärstellen für das Ergebnis zur Verfügung stehen, wird der Übertrag ignoriert. Die Lösung lautet also:
0100 1110

## 6. Was könnten die beiden folgenden binären Wert für eine Bedeutung haben?
(Tipp: a. ins Dezimalsystem umrechnen, b. ins Hexadezimalsystem umrechnen)

#### a. 1100’0000.1010’1000.0100’1100.1101’0011

1100'0000 -> 192
1010'1000 -> 168
0100'1100 -> 76
1101'0011 -> 211

Also:
1100'0000.1010'1000.0100'1100.1101'0011 = 192.168.76.211 

192.168.76.211 sieht aus wie eine IP-Adresse.

#### b. 1011’1110-1000’0011-1000’0101-1101’0101-1110’0100-1111’1110

1011'1110 -> BE
1000'0011 -> 83
1000'0101 -> 85
1101'0101 -> D5
1110'0100 -> E4
1111'1110 -> FE

Also: 1011'1110-1000'0011-1000'0101-1101'0101-1110'0100-1111'1110 = BE-83-85-D5-E4-FE

BE-83-85-D5-E4-FE sieht aus wie eine MAC-Adresse


## 8. Dimensionieren sie für den Matterhorn-Express, wo insgesamt 107 Gondeln die Touristen von Zermatt auf den Trockenen-Steg befördern, die Codebreite des Binärcodes für die Kabinenzählung.

#### Rechenweg

107 = 0110 1011

#### Lösung 

Es werden 7 Stellen für den Binärcode benötigt.

## 9. Sie untersuchen einen Arbeitsspeicher mit 12-Bit-Adress- bzw. 16-Bit-Datenbus.
Welche Speicherkapazität in kiB besitzt dieser? (Hinweis: 1kiB=1024B)

#### Rechenweg + Lösung

2^12 = 4'096 
4096 * 16-Bit-Datenbus = 65'536 

65'536 / 1024 = 64kiB

## 10. Zwei Geräte sind mit einer seriellen Leitung und zusätzlichem Taktsignal verbunden. Das Taktsignal beträgt 1MHz.

#### a. Wie viele Bytes können damit pro Sekunde übertragen werden?

1MHz / Byte (8 Bits) = 8MBits = 1MB

#### b. Wie viele Bytes pro Sekunde könnten übertragen werden, wenn die Verbindung der beiden Geräte nicht seriell, sondern 8 Bit-parallel wäre?

Genau gleich, da 8 Bit gesendet werden, also einen Byte. Da die Taktfrequenz immernoch 1MHz ist, werden pro Takt 8 Bit (parallel) versendet. Also wieder:

1MHz / 8 Bits = 8MBits = 1MB

## 13. Erstellen sie die Wahrheitstabellen für die folgenden Funktionen:

#### a. Logisch UND/AND (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 0       |
| 1         | 0         | 0       |
| 1         | 1         | 1       |

#### b. Logisch ODER/OR (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 1       |
| 1         | 0         | 1       |
| 1         | 1         | 1       |

#### c. Logisch NICHT/NOT (mit einer Eingangs- und einer Ausgangsvariablen)
| Eingang | Ausgang |
|---------|---------|
| 0       | 1       |
| 1       | 0       |

#### d. Logisch EXOR (mit zwei Eingangs- und einer Ausgangsvariablen)
| Eingang A | Eingang B | Ausgang |
|-----------|-----------|---------|
| 0         | 0         | 0       |
| 0         | 1         | 1       |
| 1         | 0         | 1       |
| 1         | 1         | 0       |

## 14. Eine in der Computertechnik wichtige mathematische Funktion ist die Restwert- oder Modulo-Funktion mit dem in z.B. Java und C verwendeten Operationszeichen %. 

Versuchen sie nun die folgende Berechnungen auszuführen. Was stellen sie fest?
 a. 11 % 2 = 1
 b. 10 % 2 = 0
 c. 10 % 3 = 1
 d. 10 % 5 = 0
 e. 10 % 9 = 1