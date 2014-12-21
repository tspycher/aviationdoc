Unterrichtstag 10 - 13.12.2014
=============================

Navigation
----------
Faustformeln:

NM = KM / 2 +10%

KM = NM * 2 -10%

Eine Fingerbreite = 2 Bogenminuten auf der ICAO Karte

TT - True Track
~~~~~~~~~~~~~~~
geflogene Strecke

TC - True Course
~~~~~~~~~~~~~~~~
mit Navigationskarte geplanter Flugkurs

TH - True Heading
~~~~~~~~~~~~~~~~~
True Course mit Wind Korrektur (Wind Correction Angle = WCA)

MC / MH - Magnetic Course / Heading
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
True Course / True Heading mit Korrektur der Variation

CH - Compass Heading
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
True Heading mit Korrektur von Variation und Deviation

WCA - Wind Correction Angle
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Benötigte Kurskorrektur um bei entsprechendem Wind den True Course zu halten = True Heading

Variation
~~~~~~~~~
Abweichtung des magnetischen Nordpols vom Kartennord.

Ist am unteren Rand der ICAO Karte ablesbar. Für LSZI derzeit 1°30" E.
Jährliche Veränderung +11" / Jahr.

Variation E (east) = muss vom TC substrahiert werden

Variation W (west) = muss dem TC addiert werden


Beispiel 1:

TC = 360°

Var = 1.5° E

Magnetic Course = 358.5°


Beispiel 2:

TC = 360°

Var = 7° W

MC = 7°

+ 5° Wind Correction

MH = 12°


Beispiel 3:

TC = 090°

WCA = +10°

== TH 190°

Var = 10° E

== MH 075°

Alle Angaben via Navigationskarte sind True (True Course / True Heading)
Nach magnetischer Korrektur sind alle werte Magetic (Magnetic Course / Magnetic Heading)

Deviation
~~~~~~~~~

Ungenaugikeit des Kompass durch elektrische Magnetfelder im Flugzeug (zb. Funkgeräte)
Die Abweichungen werden vom Techniker festgestellt und sind in einer Tabelle unter dem Kompass aufgezeichnet.

TODO: Bild einfügen



Beispiel: Berechnung des magnetic headings mit Berücksichtigung der Deviation:

* TC = 180°
* WCA = +10°
* *= TH 190°*
* Var 5W = +5°
* *= MH 195°*
* Dev 5W = +5°
* **= CH 200°**