# Zufall im Griff – Lernspiel Wahrscheinlichkeit (Klasse 8)

Eine Lern-App im Browser zu den Themen:

- Laplace-Experimente
- Baumdiagramme (Knotenregel, Anzahl der Pfade)
- Pfadregel
- Summenregel
- Gegenereignis
- Ziehen mit und ohne Zurücklegen

## Funktionen

- **Einstufungstest** (12 Aufgaben): Danach zeigt die App für jedes Thema den Wissensstand (Einsteiger, Auf dem Weg, Sicher, Profi) und empfiehlt, womit man weitermacht.
- **Übungsrunden** mit 8 Aufgaben pro Thema oder gemischt. Die Aufgaben werden jedes Mal neu erzeugt, und ihre Schwierigkeit (Stufe 1–3) richtet sich nach dem Wissensstand.
- **Hilfe bei Fehlern:** Die App erkennt typische Fehler (z. B. „addiert statt multipliziert“, „1 − vergessen“, „gerechnet wie mit Zurücklegen“) und gibt einen passenden Tipp. Man hat einen zweiten Versuch. Danach gibt es den Lösungsweg mit Baumdiagramm und einen Spickzettel zum Weiterlernen.
- **Motivation:** XP und Level mit Titeln, Serien, Tagesziel (10 Aufgaben), Tage-Serie, 12 Abzeichen, Sterne pro Runde und Konfetti.
- Antworten als Bruch (`3/8`), Dezimalzahl (`0,375`) oder Prozent (`37,5 %`).

## Wo die App liegt

Die App liegt im Repository `FrauOTB/Mathe` im Ordner `Klasse8/`. Mit GitHub Pages ist sie erreichbar unter
`https://frauotb.github.io/Mathe/Klasse8/`

Lokal kann man die `index.html` auch einfach per Doppelklick im Browser öffnen.

## Technik

- Eine einzige Datei (`index.html`) mit HTML, CSS und JavaScript. Es gibt keinen Build-Schritt und keine Abhängigkeiten.
- Nur die Schriftarten werden von Google Fonts geladen. Ohne Internet werden Ersatzschriften verwendet.
- Der Fortschritt wird im `localStorage` des Browsers gespeichert. Er bleibt also nur auf dem jeweiligen Gerät und im jeweiligen Browser erhalten. Es werden keine Daten an einen Server geschickt.
