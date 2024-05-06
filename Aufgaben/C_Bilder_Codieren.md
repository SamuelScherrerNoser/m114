# Aufgaben

## 1. Bestimmen sie die Farben für die folgenden RGB-Farbcodes (in DEZ und HEX). Nutzen sie den RGB-Farbenmixer. 

Benutzern sie dazu die beiden Online-Tools:
- [Color Picker Hexa](https://www.w3schools.com/colors/colors_hexadecimal.asp)
- [Color Picker RGB](https://www.w3schools.com/colors/colors_rgb.asp)

### Codes übersetzen: 

- RGB(255, 255, 255) entspricht Farbe: Weiss
- RGB(0,0,0) entspricht Farbe: Schwarz
- RGB(252,178,91) entspricht Farbe: komisches Orange
- #FF0000 entspricht Farbe: Rot
- #00FF00 entspricht Farbe: Grün
- #0000FF entspricht Farbe: Blau
- #FFFF00 entspricht Farbe: Gelb
- #00FFFF entspricht Farbe: Cyan
- #FF00FF entspricht Farbe: Magenta
- #000000 entspricht Farbe: Schwarz
- #FFFFFF entspricht Farbe: Weiss
- #00BC00 entspricht Farbe: Grün

## 2. Bestimmen sie die Farben für die folgenden prozentualen CMYK-Angaben. 

Nutzen sie den CMYK-Farbenmixer bzw. das folgende Online-Tool:
- [Color Picker cmyk](https://www.w3schools.com/colors/colors_cmyk.asp)

### Codes übersetzen:

- C:0%, M:100%, Y:100%, K:0% entspricht Farbe: Rot
- C:100%, M:0%, Y:100%, K:0% entspricht Farbe: Grün 
- C:100%, M:100%, Y:0%, K:0% entspricht Farbe: Blau
- C:0%, M:0%, Y:100%, K:0% entspricht Farbe: Gelb
- C:100%, M:0%, Y:0%, K:0% entspricht Farbe: Cyan
- C:0%, M:100%, Y:0%, K:0% entspricht Farbe: Magenta
- C:100%, M:100%, Y:100%, K:0% entspricht Farbe: Weiss
- C:0%, M:0%, Y:0%, K:100% entspricht Farbe: Schwarz
- C:0%, M:0%, Y:0%, K:0% entspricht Farbe: Weiss
- C:0%, M:46%, Y:38%, K:22% entspricht Farbe: komisches Pink

## 3. Berechnen sie den theoretischen Speicherbedarf in Bit und in Byte eines unkomprimierten RGB-Bildes mit der Grösse 640 x 480 und 8Bit Auflösung pro Farbkanal.

### Antwort:

640 x 480 = 307'200 Pixel

8 Bit (pro Farbkanal) X 3 Farben = 24 Bit (pro Pixel)

307'200 x 24 Bit = 7'372'800 Bits

7'372'800 / 8 = 921’600 Bytes

Theoretischer Speicherbedarf: 

Ein unkomprimiertes RGB-Bild mit der Größe 640 x 480 und 8 Bit Auflösung pro Farbkanal benötigt etwa 7.37 Megabyte Speicherplatz.


## 4. Sie müssen die Webseite der Firma Muster-GmbH gestalten. Als Hintergrundbild (background-image) soll eine gekachelte Textur verwendet werden. (background-repeat: repeat). Auf diesen Hintergrund wird das Firmenlogo gelegt. Für welche Bildformate werden sie sich entscheiden? Begründen sie!

### Antwort:

Ich würde mich für das PNG-Format entscheiden, da dieses Format Transparenz erlaubt und verlustfrei komprimiert. Es ist ausserdem eines der gängisten Formate.

## 5. Sie haben ein 30-Zoll-Display (Diagonale) im Format 16:10 und 100ppi erworben. Was ist die Pixelauflösung horizontal und vertikal?

### Lösungsweg:

Diagonale: 30 inches
Seitenverhältnis: 16:10 

30 inches = 76.2cm 

a^2 + b^2 = c^2
(16x)^2 + (10x)^2 = 356x^2

356x^2 = 76.2^2
356x^2 = 5806.44
x^2 = 16.3
x = 4.04 

10 * 4.04 = 40.4cm = Höhe
16 * 4.04 = 64.64cm = Breite

40.4 / 2.54 = 15.9 inches
64.64 / 2.54 = 25.4 inches

15.9 * 100 = 1590 Pixel (Höhe)
25.4 * 100 = 2540 Pixel (Breite)

### Antwort:

Vertikal: 1590 Pixel
Horizontal: 2540 Pixel

## 6. Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixel mit 600dpi. Wie gross in cm wird dieses?

### Lösungsweg:

600 / 2.54 = 236 Pixel pro cm

2000 / 236 = 8.48cm

### Antwort: 

Die Kantenlänge ist 8.48cm

## 7. Berechnen sie den Speicherbedarf für ein unkomprimiertes Einzelbild im HD1080p50-Format bei einer True-Color-Farbauflösung.

### Lösungsweg:

1'080 Höhe / 9 Seitenverhältnis-Höhe = 120 Seitenverhältnis-Einzelteil
120 Pixel * 16 Seitenverhältnis-Breite = 1'920 Breite

1'080 Höhe * 1'920 Breite * 3 Byte = 6'220'800 Bytes

6'220'800 Bytes * 25 Bilder pro Sekunde = 155'520'000 Bytes 

155'520'000 Bytes * (90min * 60) = 839'808'000'000 Bytes 

839'808'000'000 Bytes = 820'125'000 Kilobytes = 800'903,3 Megabytes = 782,13 Gigabytes

### Antwort:

Der Speicherbedarf beträgt 782,13GB

## 8. Welchen Speicherbedarf aus einer HD (Massvorsatz im IEC-Format) hat das Video aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten?

### Lösungsweg:

155'520'000 Bytes * 180 Sekunden = 27'993'600'000 Bytes

27'993'600'000 Bytes = 27'337'500 Kilobytes = 26'696,78 Megabytes = 26.07 Gigabytes

### Antwort: 

Der Speicherbedarf beträgt 26.07 Gigabytes

## 14. Nach wie vielen Minuten unkomprimierten HD1080i50 Video wäre eine DVD-5 (Single-Layer DVD mit 4.7GB) voll?

### Lösungsweg:

155'520'000 Bytes = 151'875 Kilobytes = 148,315 Megabytes = 0.145 Gigabytes = 1 Minute Film

4.7 / 0.145 = 32.4 Minuten pro Single-Layer DVD

### Antwort: 

Auf einer Single-Layer DVD hat es für 32.4 Minuten unkomprimierte Film-Daten platz.