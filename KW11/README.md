# KW10 Arbeitsblatt

## Theorie: [B_DATEN_KOMPRIMIEREN](C_BILDER_CODIEREN.pdf)
## Aufgaben: [B_DATEN_KOMPRIMIEREN_ANNEX](C_BILDER_CODIEREN_ANNEX.pdf)

## Inhaltsverzeichnis
- [X] [Aufgabe 3](#Aufgabe-3---RLC-Bilder)
- [X] [Aufgabe 5](#Aufgabe-5---LZW-Verfahren)
- [X] [Reflexion](#Reflexion)

### Aufgabe 1 - RGB-Farbcodes
Bestimmen sie die Farben für die folgenden RGB-Farbcodes (in DEZ und HEX).
   Nutzen sie den RGB-Farbenmixer. Benutzern sie dazu die beiden Online-Tools:
   https://www.w3schools.com/colors/colors_hexadecimal.asp
   https://www.w3schools.com/colors/colors_rgb.asp
   • RGB(255, 255, 255) entspricht Farbe: Weiss
   • RGB(0,0,0) entspricht Farbe: Schwarz
   • RGB(252,178,91) entspricht Farbe: Hautfarbe
   • #FF0000 entspricht Farbe: Rot
   • #00FF00 entspricht Farbe: Grün
   • #0000FF entspricht Farbe: Blau
   • #FFFF00 entspricht Farbe: Gelb
   • #00FFFF entspricht Farbe: Hellblau / Türkis
   • #FF00FF entspricht Farbe: Pink
   • #000000 entspricht Farbe: Schwarz
   • #FFFFFF entspricht Farbe: Weiss
   • #00BC00 entspricht Farbe: Hellgrün

### Aufgabe 2 - CMYK-Angaben
Bestimmen sie die Farben für die folgenden prozentualen CMYK-Angaben. Nutzen
   sie den CMYK-Farbenmixer bzw. das folgende Online-Tool:
   https://www.w3schools.com/colors/colors_cmyk.asp
   • C:0%, M:100%, Y:100%, K:0% entspricht Farbe:
   • C:100%, M:0%, Y:100%, K:0% entspricht Farbe:
   • C:100%, M:100%, Y:0%, K:0% entspricht Farbe:
   • C:0%, M:0%, Y:100%, K:0% entspricht Farbe:
   • C:100%, M:0%, Y:0%, K:0% entspricht Farbe:
   • C:0%, M:100%, Y:0%, K:0% entspricht Farbe:
   • C:100%, M:100%, Y:100%, K:0% entspricht Farbe:
   • C:0%, M:0%, Y:0%, K:100% entspricht Farbe:
   • C:0%, M:0%, Y:0%, K:0% entspricht Farbe:
   • C:0%, M:46%, Y:38%, K:22% entspricht Farbe:


### Aufgabe 3 - Speicherbedarf
Berechnen sie den theoretischen Speicherbedarf in Bit und in Byte eines
unkomprimierten RGB-Bildes mit der Grösse 640 x 480 und 8Bit Auflösung pro Farbkanal

2457600 bit oder 307200 Byte

### Aufgabe 4 - Bildformat
Sie müssen die Webseite der Firma Muster-GmbH gestalten. Als Hintergrundbild
(background-image) soll eine gekachelte Textur verwendet werden.
(background-repeat: repeat). Auf diesen Hintergrund wird das Firmenlogo gelegt.
Für welche Bildformate werden sie sich entscheiden? Begründen sie!

16 : 9, 4 : 3 (1920 * 1080)

### Aufgabe 5 - Pixelauflösung
Sie haben ein 30-Zoll-Display (Diagonale) im Format 16:10 und 100ppi erworben.
Was ist die Pixelauflösung horizontal und vertikal?

30^2 = 10x^2 + 16x^2

### Aufgabe 6 - Kantenlänge
Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixel mit 600dpi.
Wie gross in cm wird dieses?

2000 / 600 = 3.333333333 Inches = 8.466666667 Centi Meter

### Aufgabe 7 - Speicherbedarf HD
Berechnen sie den Speicherbedarf für ein unkomprimiertes Einzelbild im
HD1080p50-Format bei einer True-Color-Farbauflösung.

1920 * 1080 * 24 = 49766400 bit = 6220800 Byte

### Aufgabe 8 - Speicherbedarf Video
Welchen Speicherbedarf aus einer HD (Massvorsatz im IEC-Format) hat das Video
aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten?

6220800 * 180 * 50 = 55987200000 Byte = 559872000 Hecto Byte

### Aufgabe 9 - Digitalkamera
Ihre Digitalkamera bietet für die Speicherung ihrer Bilder die beiden Formate RAW
und JPG an. Wo liegen die Unterschiede und was sind die Verwendungszwecke?

- **RAW-Format**:
   - Unkomprimiertes Dateiformat mit allen Rohdaten vom Bildsensor.
   - Bietet maximale Bildqualität und Flexibilität bei der Nachbearbeitung.
   - Größere Dateigröße, erfordert mehr Speicherplatz.
   - Erfordert Nachbearbeitung für optimale Ergebnisse.
   - Geeignet für professionelle Fotografen oder fortgeschrittene Benutzer, die volle Kontrolle über die Bildbearbeitung wünschen.

- **JPG-Format**:
   - Komprimiertes Dateiformat, das von den meisten Digitalkameras verwendet wird.
   - Platzsparend und leicht zu teilen, da Dateigrößen klein sind.
   - Die Kamera wendet während der Aufnahme bereits Bildbearbeitungseinstellungen an.
   - Einige Bildinformationen gehen aufgrund der Komprimierung verloren.
   - Geeignet für den allgemeinen Gebrauch, schnelle Aufnahmen oder Situationen, in denen eine schnelle Verarbeitung und Freigabe der Bilder erforderlich ist.


### Reflexion
- Ich habe gelernt, wie Bilder Komprimiert werden
- Ich habe gelernt, wie BWT funktioniert