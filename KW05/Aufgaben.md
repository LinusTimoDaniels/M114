# KW05 Arbeitsblatt

## Theorie: [A_DATEN_CODIEREN_NUM](./A_DATEN_CODIEREN_NUM.pdf)
## Aufgaben: [A_DATEN_CODIEREN_NUM_ANNEX](./A_DATEN_CODIEREN_NUM_ANNEX.pdf)

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

### Aufgabe 11

### Aufgabe 12

