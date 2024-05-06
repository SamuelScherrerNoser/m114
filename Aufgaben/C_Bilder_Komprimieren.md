# Aufgaben

## 1. Um ein gewisses Verständnis für die Luminanz-Chrominanz-Beschreibung von Farben zu erhalten, lösen sie die folgenden Aufgaben. 

Benutzen sie dazu dieses pOnline-Tool: https://colorizer.org/

### Codes übersetzen: 

- RGB 255/255/255 entspricht Weiss und ergibt in YCbCr: 100
- RGB 0/0/0 entspricht Schwarz und ergibt in YCbCr: 000
- Y:0, Cb:0.5, Cr:0 entspricht der Farbe: Rot
- Y:0, Cb:-0.5, Cr:0 entspricht der Farbe: Grün
- Y:0, Cb:0, Cr:0.5 entspricht der Farbe: Blau
- Y:0, Cb:0, Cr:-0.5 entspricht der Farbe: Dunkelgrün
- Y:0.3, Cb:0.5, Cr:-0.17 entspricht der Farbe: Hellrot

## 2. Ein RGB-Farbbild benutzt nur die Farbe Weiss als Hintergrund und ein Hellblau mit folgenden Werten: R=33, G=121, B=239 (8 Bit pro Farbkanal). Das Bild soll in ein Graustufenbild umgewandelt werden. Berechnen sie den für das Hellblau entsprechende Grauwert. (8 Bit pro Farbkanal)

### Lösung:

Für das Hellblau mit den RGB-Werten R=33, G=121, B=239 wäre der Grauwert:

Grauwert = ((R * 0.3) + (G * 0.6) + (B * 0.1))

Grauwert = ((33 * 0.3) + (121 * 0.6) + (239 * 0.1))

Grauwert = (9.9 + 72.6 + 23.9)

Grauwert = 106.4

## 3. Berechnen sie, wieviel Speicher eingespart wird, wenn ein Bild mit Subsampling 4:1:1 komprimiert wird.

### Lösung:

Die Einsparung beträgt 3/4.