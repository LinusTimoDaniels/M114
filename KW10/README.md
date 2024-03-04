# KW10 Arbeitsblatt

## Theorie: [B_DATEN_KOMPRIMIEREN](../KW09/B_DATEN_KOMPRIMIEREN.pdf)
## Aufgaben: [B_DATEN_KOMPRIMIEREN_ANNEX](../KW09/B_DATEN_KOMPRIMIEREN_ANNEX.pdf)

## Inhaltsverzeichnis
- [X] [Aufgabe 3](#Aufgabe-3---RLC-Bilder)
- [X] [Aufgabe 5](#Aufgabe-5---LZW-Verfahren)
- [X] [Reflexion](#Reflexion)

### Aufgabe 3 - RLC Bilder
RLC: Wie könnte die Komprimierung ausschauen, wenn es sich anstatt um ein
Schwarz/Weissbild, um ein Farbbild handelt?

Wenn das Bild nur aus einer Farbe bestehen würde, wären 4 bit nicht genügend, da man damit höchstens 15 Pixel darstellen könnte.

### Aufgabe 5 - LZW Verfahren
a). Erstellen sie die LZW-Codierung für das Wort «ANANAS» und überprüfen sie
mit der Dekodierung ihr Resultat.

Codiert:

| Zeichenkette | Gefunden | Gespeichert | Wörterbuch |
|--------------|----------|-------------|------------|
| ANANAS       | A        | A           | AN -> 266  |
| NANAS        | N        | N           | NA -> 267  |
| ANAS         | AN       | 266         | ANA -> 268 |
| AS           | A        | A           | AS -> 269  |
| S            | S        | S           | -          |

b). Versuchen sie den erhaltenen LZW-Code «ERDBE<256>KL<260>» zu
dekomprimieren.

Entcodiert:

| Zeichenkette      | Zeichen | Ausgabe | Wörterbuch |
|-------------------|---------|---------|------------|
| ERDBE<256>KL<260> | E       | E       | -          |
| ERDBE<256>KL<260> | R       | R       | ER -> 256  |
| ERDBE<256>KL<260> | D       | D       | RD -> 257  |
| ERDBE<256>KL<260> | B       | B       | DB -> 258  |
| ERDBE<256>KL<260> | E       | E       | BE -> 259  |
| ERDBE<256>KL<260> | 256     | ER      | EE -> 260  |
| ERDBE<256>KL<260> | K       | K       | ERK -> 261 |
| ERDBE<256>KL<260> | L       | L       | KL -> 262  |
| ERDBE<256>KL<260> | 260     | EE      | lEE -> 262 |

### Reflexion
- Ich habe vieles über UTF-16 und BOM (Byte order) gelernt
- Ich fand, die Prüfung hatte ein wenig zu wenige mögliche Punkte zu erreichen, war aber gut geschrieben.
- Ich habe repetiert, wie man im Oktal-System rechnet und umrechnet