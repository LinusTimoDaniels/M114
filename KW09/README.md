# KW09 Arbeitsblatt

## Theorie: [A_DATEN_CODIEREN_TXT](./A_DATEN_CODIEREN_TXT.pdf)
## Aufgaben: [A_DATEN_CODIEREN_TXT_ANNEX](./A_DATEN_CODIEREN_TXT_ANNEX.pdf)

## Theorie: [B_DATEN_KOMPRIMIEREN](./B_DATEN_KOMPRIMIEREN.pdf)
## Aufgaben: [B_DATEN_KOMPRIMIEREN_ANNEX](./B_DATEN_KOMPRIMIEREN_ANNEX.pdf)

## Inhaltsverzeichnis
- [X] [Aufgabe 1](#Aufgabe-1---ASCII-Tabelle)
- [X] [Aufgabe 2](#Aufgabe-2---UNI-Code-Tabelle)
- [X] [Aufgabe 3](#Aufgabe-3---Codesysteme-Analysieren)
- [X] [Reflexion](#Reflexion)

### Aufgabe 1 - ASCII Tabelle
Besorgen sie sich im Internet eine vollständige ASCII-Tabelle als Bild- oder
PDF-Datei und ergänzen sie damit ihr ePortfolio.

[ASCII Tabelle](./ASCII-Tabelle-alle-ASCII-Codes-im-UEberblick.pdf)

### Aufgabe 2 - UNI Code Tabelle
Suchen sie im Internet nach einer Webseite, wo Unicode-Zeichen gelistet sind
und merken bzw. notieren sie sich den Link. 

[UNI Code Tabelle](https://symbl.cc/de/unicode/table/#ethiopic)

### Aufgabe 3 - Codesysteme Analysieren

Sie erhalten eine ZIP-Datei Textsamples.zip unter folgendem Link:
[Textsamples](https://juergarnold.ch/Codesysteme/Textsamples.zip)
Laden sie die ZIP-Datei auf ihren Notebook und extrahieren sie die drei Dateien
Textsample1, Textsample2 und Textsample3. Eine der drei Dateien ist in
ASCII codiert, die andere in UTF-8 und die dritte in UTF-16. Beantworten sie nun die
folgenden Fragen:

a. Welche der Dateien ist nun ASCII-codiert, welche UTF-8 und welche UTF-16
BE-BOM?

- ASCII / Westeuropäisch (Windows Latin 1): [Textsample 1](./Textsamples/Textsample1)

- UTF-8: [Textsample 2](./Textsamples/Textsample2)

- UTF-16: [Textsample 3](./Textsamples/Textsample3)

b. Alle drei Dateien enthalten denselben Text. Aus wie vielen Zeichen besteht
dieser?

68

c. Was sind die jeweiligen Dateigrössen? (Beachten sie, dass unter Grösse auf
Datenträger jeweils 0 Bytes angegeben wird. Dies darum, weil beim WindowsDateisystem NTFS kleine Dateien direkt in die MFT (Master File Table)
geschrieben werden.) Wie erklären sie sich die Unterschiede?

- 68 Bytes: [Textsample 1](./Textsamples/Textsample1)

- 71 Bytes: [Textsample 2](./Textsamples/Textsample2)

- 138 Bytes: [Textsample 3](./Textsamples/Textsample3)

Die Grösse der Zeichen werden mit unterschiedlich vielen bit gespeichert.

d. Bei den weiteren Fragen interessieren uns nur noch die ASCII- und die UTF8-Datei: Bekanntlich ist UTF-8 in den ersten 128 Zeichen deckungsgleich mit
ASCII. Untersuchen sie nun die beiden HEX-Dumps und geben sie an, welche
Zeichen unterschiedlich codiert sind. Ein kleiner Tipp: Es sind deren zwei.

Das Zeichen "ä" wird unterschiedlich Codiert.

e. Was bedeuten die beiden Ausdrücke, denen wir z.B. bei UTF-16 begegnen:
Big-Endian (BE), Little-Endian (LE)?

Big-Endian und Little-Endian bezieht sich auf die Byteorder, ob die Bytes von Vorne nach hinten oder von hinten nach vorne gelesen werden.

f. Im Notepad++ kann man unter dem Menüpunkt Codierung von ASCII zu UTF
umschalten. Spielen sie damit etwas herum und notieren sie sich, was in der
Darstellung jeweils ändert.

- ASCII -> UTF-8 verändert sich nur "ä"
- UTF-8 -> UTF-16 veränder sich sich die die die ersten Bytes und die grösse der Zeichen

g. Für Anspruchsvolle: Der UTF-8-Code kann je nach Zeichen ein, zwei, drei
oder vier Byte lang sein. Wie kann der Textreader erkennen, wann ein UTF-8
Zeichencode beginnt und wann er endet? Untersuchen sie dies anhand der
beiden Textsamples und lesen sie in z.B. Wikipedia die entsprechende
Theorie zu UTF-8 durch. Tipp: Startbyte und Folgebyte

UTF-8:
- Einzeilige Zeichen (mit einem Codepunkt kleiner als 128) werden mit einem Byte dargestellt, wobei das höchste Bit 0 ist.
- Zeichen mit einem Codepunkt zwischen 128 und 2047 werden mit zwei Bytes dargestellt, wobei das erste Byte die Sequenz mit '110' beginnt und das zweite mit '10'.
- Zeichen mit einem Codepunkt zwischen 2048 und 65535 werden mit drei Bytes dargestellt, beginnend mit '1110' im ersten Byte, gefolgt von zwei Bytes, die mit '10' beginnen.
- Zeichen mit einem Codepunkt zwischen 65536 und 1114111 werden mit vier Bytes dargestellt, beginnend mit '11110' im ersten Byte, gefolgt von drei Bytes, die mit '10' beginnen.

### Reflexion

- Ich habe gelernt was Byteorder ist.
- Ich habe gelernt, was Unterschiede sind zwischen ASCII / ANSI, UTF-8 und UTF-16.
- Ich habe mir die verscheidenen ISO Versionen von ASCII angesehen.
- Ich habe gelernt wie Kompremierung funktioniert (Huffman-Baum)