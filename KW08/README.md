# KW05 Arbeitsblatt

## Theorie: [A_DATEN_CODIEREN_NUM](./A_DATEN_CODIEREN_NUM.pdf)
## Aufgaben: [A_DATEN_CODIEREN_NUM_ANNEX](./A_DATEN_CODIEREN_NUM_ANNEX.pdf)

## Inhaltsverzeichnis
- [X] [Aufgabe 1](#Aufgabe-1)
- [X] [Aufgabe 2](#Aufgabe-2)
- [X] [Aufgabe 3](#Aufgabe-3)
- [X] [Aufgabe 4](#Aufgabe-4)
- [X] [Aufgabe 5](#Aufgabe-5)
- [X] [Aufgabe 6](#Aufgabe-6)
- [X] [Aufgabe 7](#Aufgabe-7)
- [X] [Aufgabe 8](#Aufgabe-8)
- [X] [Aufgabe 9](#Aufgabe-9)
- [X] [Aufgabe 10](#Aufgabe-10)
- [ ] [Aufgabe 11](#Aufgabe-11)
- [ ] [Aufgabe 12](#Aufgabe-12)
- [ ] [Aufgabe 13](#Aufgabe-13)
- [ ] [Aufgabe 14](#Aufgabe-14)
- [X] [Reflexion](#Reflexion)

### Aufgabe 1
1. Erstellen sie eine leere Tabelle mit 6 Kolonnen und 16 Zeilen. Füllen sie diese wie
folgt aus:
1. Kolonne: Dezimalzahlen von 0 bis 15
2. Kolonne: Hexadezimalzahlen von 0 bis F
3. Kolonne, 4. Kolonne, 5. Kolonne und 6. Kolonne die entsprechenden Binärzahlen
   Studieren sie nun ihre fertig ausgefüllte Tabelle, insbesondere die Kolonnen mit den
   Binärwerten. Was stellen sie fest?

| DEZ | HEX | BIN | 8 | 4 | 2 | 1 |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 0 | 0 |  | 0 | 0 | 0 | 0 |
| 1 | 1 |  | 0 | 0 | 0 | 1 |
| 2 | 2 |  | 0 | 0 | 1 | 0 |
| 3 | 3 |  | 0 | 0 | 1 | 1 |
| 4 | 4 |  | 0 | 1 | 0 | 0 |
| 5 | 5 |  | 0 | 1 | 0 | 1 |
| 6 | 6 |  | 0 | 1 | 1 | 0 |
| 7 | 7 |  | 0 | 1 | 1 | 1 |
| 8 | 8 |  | 1 | 0 | 0 | 0 |
| 9 | 9 |  | 1 | 0 | 0 | 1 |
| 10 | A |  | 1 | 0 | 1 | 0 |
| 11 | B |  | 1 | 0 | 1 | 1 |
| 12 | C |  | 1 | 1 | 0 | 0 |
| 13 | D |  | 1 | 1 | 0 | 1 |
| 14 | E |  | 1 | 1 | 1 | 0 |
| 15 | F |  | 1 | 1 | 1 | 1 |

### Aufgabe 2
Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende
Binärzahl um: 911

| 1024 | 512 | 256 | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |   
|------|-----|-----|-----|----|----|----|---|---|---|---|
| 0    | 1   | 1   | 1   | 0  | 0  | 0  | 1 | 1 | 1 | 1 |          

### Aufgabe 3
Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 1011'0110


| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 1 | 0 | 1 | 1 | 0 | 1 | 1 | 0 |

128 + 32 + 16 + 4 + 2 = **182**        


### Aufgabe 4
Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende
Hexadezimalzahl um: **1110'0010'1010'0101**

| 8 | 4 | 2 | 1 | | 8 | 4 | 2 | 1 | | 8 | 4 | 2 | 1 | | 8 | 4 | 2 | 1 |  
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |  
| 1 | 1 | 1 | 0 | - | 0 | 0 | 1 | 0 | - | 1 | 0 | 1 | 0 | - | 0 | 1 | 0 | 1 |  
| **E** | - | - | - | - | **2** | - | - | - | - | **A** | - | - | - | - | **5** | - | - | - |  

### Aufgabe 5
Was ergibt die Addition der beiden binären Zahlen 1101'1001 und 0111'0101?
Beachten Sie, dass für das Resultat ebenfalls nur 8 Binärstellen zur Verfügung
stehen.

| 1024 | 512 | 256 | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |   
|------|-----|-----|-----|----|----|----|---|---|---|---|
| 0    | 0   | 0   | 1   | 1  | 0  | 1  | 1 | 0 | 0 | 1 | 
| 0    | 0   | 0   | 0   | 1  | 1  | 1  | 0 | 1 | 0 | 1 |
| 0    | 0   | 1   | 0   | 1  | 0  | 0  | 1 | 1 | 1 | 0 |


217 + 117 = **334**

### Aufgabe 6
Was könnten die beiden folgenden binären Wert für eine Bedeutung haben?
(Tipp: a. ins Dezimalsystem umrechnen, b. ins Hexadezimalsystem umrechnen)
a. 1100’0000.1010’1000.0100’1100.1101’0011
b. 1011’1110-1000’0011-1000’0101-1101’0101-1110’0100-1111’1110

190-131-133-213-228-254

BE-83-85-D5-E4-FE

### Aufgabe 7
Für Linux-Fans: Was könnte die folgende in einem Bash-Script entdeckte Zeile für
eine Bedeutung haben? chmod 751 CreateWeeklyReport

Der Befehel setzt die read, write, execute Berechtigungsbits für eine Datei oder einen Ordner. Die Berechtigung wird durch Neuen bits gesetzt: "rwxrwxrwx"
Die ersten drei bits sind die Berechtigungen für den Besitzer / Ersteller der Datei / Ordner, die nächsten drei bits für dei Benutzergruppe, welche Zugriff haben und die letzten drei bits für alle anderen Benutzer.

read / r: 4
write / w: 2
execute / x: 1

die Berechtigung für die Datei wäre also: "rwxr-x--x"
und chmod 777 wäre: "rwxrwxrwx" also alle Berechtigungen für alle.

### Aufgabe 8

Dimensionieren sie für den Matterhorn-Express, wo insgesamt 107 Gondeln die
Touristen von Zermatt auf den Trockenen-Steg befördern, die Codebreite des
Binärcodes für die Kabinenzählung.


Die nächsthöhere Potenz von 2, die größer oder gleich 107 ist, ist 128 (2^7). Das bedeutet, dass wir mindestens 7 Bits benötigen, um 107 Gondeln zu repräsentieren.

### Aufgabe 9

Sie untersuchen einen Arbeitsspeicher mit 12-Bit-Adress- bzw. 16-Bit-Datenbus.
Welche Speicherkapazität in kiB besitzt dieser? (Hinweis: 1kiB=1024B)
2^12 * 2^16 =
2^192 = 4096
Speicherkapazität (in Byte) = Anzahl der Adressen * Größe des Datenbusses = 4096 * 16 = 65536 Byte

### Aufgabe 10

Zwei Geräte sind mit einer seriellen Leitung und zusätzlichem Taktsignal verbunden. Das Taktsignal beträgt 1MHz.

a. Wie viele Bytes können damit pro Sekunde übertragen werden?

b. Wie viele Bytes pro Sekunde könnten übertragen werden, wenn die Verbindung der beiden Geräte nicht seriell, sondern 8 Bit-parallel wäre

Bei einer seriellen Verbindung mit einem Taktsignal von 1 MHz
wird pro Takt ein Bit übertragen. Da 1 Byte aus 8 Bits besteht,
können pro Sekunde 1 MHz / 8 = 125.000 Bytes übertragen werden.

Wenn die Verbindung 8 Bit-parallel wäre, würde pro Taktzyklus
ein Byte übertragen werden. Da das Taktsignal immer noch 1 MHz beträgt, können
pro Sekunde auch 1 MHz Bytes übertragen werden. Also könnten in diesem Fall ebenfalls
1.000.000 Bytes pro Sekunde übertragen werden.

### Aufgabe 11

Bei den bisherigen Aufgaben zu Binärcodes, handelte es sich immer um positive,
numerische Werte. Bei den Programmiersprachen spricht man vom Datentyp
"unsigned integer". Hin und wieder möchte man aber auch die negative Zahlenwelt
miteinbeziehen, man nennt dies dann "signed integer", was mit vorzeichenbehafteter
Ganzzahl übersetzt werden kann.
(Wobei man gut beraten ist, abzuwägen, ob der Mehraufwand für negative Zahlen tatsächlich
gerechtfertigt ist, wie folgendes Beispiel aus der Physik zeigt: Die Celsius-Temperaturskala kennt
negative Werte, die Kelvin-Temperaturskala hingegen nicht und beide Skalen messen dieselbe
Temperatur. Zum Beispiel entspricht der absolute Temperatur-Nullpunkt (nichts kann kälter sein, dass ist
in diesem Fall entscheidend) -273 Grad Celsius aber eben auch 0 Grad Kelvin, Wasser schmilzt bei 0
Grad Celsius bzw. 273 Grad Kelvin und der heutige Sommer bot angenehme 35 Grad Celsius oder eben
308 Grad Kelvin)
Möchte man den binären Zahlenstrahl in den negativen Bereich erweitern, liegt die
Versuchung nahe, das erste Bit (MSB) als Vorzeichen zu verwenden. Funktioniert
leider nicht bzw. nicht in allen Fällen! Die Lösung die funktioniert, nennt man
Zweierkomplement. Was darunter zu verstehen ist, wird im Internet unzählige Male
erklärt.
Nun zur Aufgabe: Wir gehen von einer Verarbeitungsbreite von einem Byte aus.
(Datenbusbreite:1Byte)

a. Nennen sie kleinster und grösster Binärwert bzw. Dezimaläquivalent im Falle
von unsigned bzw. Vorzeichenlos.

b. Nennen sie kleinster und grösster Binärwert bzw. Dezimaläquivalent im Falle
von signed bzw. Vorzeichenbehaftet.

c. Wandeln sie die Dezimalzahl +83 in einen vorzeichenbehafteten Binärwert
um. (signed)

d. Wandeln sie die Dezimalzahl -83 in einen vorzeichenbehafteten Binärwert um.
Signed mit 2er-Komplement:

e. Addieren sie die beiden erhaltenen Binärwerte zusammen. Es sollte 0
ergeben!

f. Wandeln sie die Dezimalzahl 0 in einen vorzeichenbehafteten Binärwert um.
(signed). Hat ihre vorangegangene Addition auch diesen Binärwert ergeben?

g. Warum können sie bei der gegebenen Datenbusbreite von 1 Byte die
Dezimalzahl +150 nicht in einen vorzeichenbehafteten Binärwert umwandeln?

(Ziehen sie daraus ihre Lehren für zukünftige Programmiersprachkurse: Immer den korrekten
Datentyp in der verlangten Grösse wählen)

**TBD**

### Aufgabe 12

Bisher haben wir immer von ganzen Zahlen gesprochen. Oft genügt das in der realen
Welt aber nicht. Dazu ein Beispiel: Teile ich die Ganzzahl 1 durch die Ganzzahl 3 und
multipliziere sie darauf wieder mit der Ganzzahl 3 erhalte ich, sofern der
Compiler/Interpreter nicht trickst, die Ganzzahl 0, was bekanntlich falsch ist. Dies weil
das Resultat der Division nicht als 0.3333333 sondern als ganze Zahl 0
(Nachkommastellen werden ignoriert) zwischengespeichert wird. Benötigt wird also
ein Datentyp, der mit Fliesskommazahlen (Floating Point Numbers) klarkommt. Wie
würden sie eine solche Fliesskommazahl definieren, und wie sie digital abspeichern?
Machen sie dazu einen Vorschlag.

**TBD**

### Aufgabe 13

Erstellen sie die Wahrheitstabellen für die folgenden Funktionen:

a. Logisch UND/AND (mit zwei Eingangs- und einer Ausgangsvariablen)

b. Logisch ODER/OR (mit zwei Eingangs- und einer Ausgangsvariablen)

c. Logisch NICHT/NOT (mit einer Eingangs- und einer Ausgangsvariablen)

d. Logisch EXOR (mit zwei Eingangs- und einer Ausgangsvariablen)

**TBD**

### Aufgabe 14

Eine in der Computertechnik wichtige mathematische Funktion ist die Restwert- oder
Modulo-Funktion mit dem in z.B. Java und C verwendeten Operationszeichen %.
Versuchen sie nun die folgende Berechnungen auszuführen. Was stellen sie fest?
a. 11 % 2 = 1
b. 10 % 2 = 0
c. 10 % 3 = 1
d. 10 % 5 = 0
e. 10 % 9 = 1

### Reflexion

- Ich habe gelernt, was ein Adressbus und ein Datenbus ist.
- Ich konnte das Umwandeln von Zahlen in den verschiedenen Zahlensystemen repetieren.
- Ich habe einiges über das Binärsystem und Datenleitungen gelernt (seriell / paralell)