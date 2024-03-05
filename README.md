Optimierter Bascoder fuer die Kleincomputer KC85/3-5. Basis meiner Weiterentwicklung war der Bascoder in der Version 1.5 mit Farberweiterung von R. Wetzel 08.12.1992 fuer den KC85/4 sowie der Bascoder in der Version 1.6 von H. Arendt 20.07.1992.

Aenderungen Version 1.5a (11.11.2023):

- die Funktionalitaet, mit GOSUB 280 die STOP/BRK-Taste ein- bzw. auszuschalten entfaellt.
- Die Arbeitszellen des Programms wurden so verschoben, dass es keine Ueberschneidung mehr mit der M052-Software (USB-Tastatur) gibt.

wesentliche Aenderungen der Version 1.5b (19.11.2023):

- Fehlerkorrektur zu Version 1.5a
- BASIC-Programm wird korrekt geloescht bei Kaltstart mit CALL*410
- Standardfarben geaendert (Menue jetzt gelb auf blau, Programmstart weiss auf schwarz)
- Farbverwaltung neu programmiert

wesentliche Aenderungen der Version 1.5c (26.12.2023):

- KC85/3-Version mit identischen Funktionsumfang, kompatibel auch mit CAOS 3.4 und OS/pi
- Test auf "schwaches Kassetteninterface" beim KC85/4 wieder eingebaut
- GOSUB 650: Farb-IRM wird nur beschrieben, wenn erforderlich
- GOSUB 150: Farbe aus CC(0) und CC(1) wird nicht uebernommen

wesentliche Aenderungen der Version 1.5d (04.01.2024):

- Umstellung von ISRI/MBI/CSRI auf MBIN und von ISRO/MBO/CSRO auf MBOUT - dadurch nun auch mit BASEX3.KCC und Diskette nutzbar
- Dateiname des Datenfiles von *.UUU auf *.DDD geaendert um Verwechslungen zu Programmlistings zu vermeiden
- KTAB-Kopie in Programm integriert und GOSUB 280 wieder aktiviert
- 3 Versionen: KC85/3, KC85/4 ohne DEVICE-Umschaltung, KC85/5 mit DEVICE-Umschaltung

Bei Programmfehlern bitte eine Information an den Autor.
