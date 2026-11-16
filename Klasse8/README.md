# Klasse 8: Lern-Apps

Der Ordner enthält zwei Lern-Apps für den Browser. Jede App ist eine einzige HTML-Datei mit HTML, CSS und JavaScript. Es gibt keinen Build-Schritt und keine Abhängigkeiten. Nur die Schriftarten werden von Google Fonts geladen. Ohne Internet werden Ersatzschriften verwendet.

Mit GitHub Pages sind die Apps hier erreichbar:

| App | Datei | Adresse |
|---|---|---|
| Gipfelweg Lineare Funktionen | `index.html` | `https://frauotb.github.io/Mathe/Klasse8/` |
| Zufall im Griff – Lernspiel Wahrscheinlichkeit | `ZufallImGriffLernspielWahrscheinlichkeit.html` | `https://frauotb.github.io/Mathe/Klasse8/ZufallImGriffLernspielWahrscheinlichkeit.html` |

Lokal kann man jede Datei auch einfach per Doppelklick im Browser öffnen.

---

## Gipfelweg Lineare Funktionen (`index.html`)

Ein Selbstlernpfad als Bergroute mit sechs Etappen und einem Gipfel:

1. Was ist eine Funktion? (Wiederholung, freiwillig)
2. Proportionale Funktionen (Wiederholung, freiwillig)
3. Lineare Funktionen y = mx + b (Einstieg)
4. Gleichungen bestimmen und zeichnen
5. Nullstellen und Schnittpunkte
6. Anwendungsaufgaben
7. Gipfel: Probearbeiten

### Funktionen

- **Einstieg bei Etappe 3.** Etappe 1 und 2 sind von Anfang an zur Wiederholung offen. Ab Etappe 4 öffnet sich jede Etappe erst mit dem Schlüssel der Etappe davor.
- **Vier Bereiche pro Etappe:** Entdecken, Üben, Schlüsselprüfung, Kristalle.
- **Entdecken:** Werkzeuge mit Schiebereglern und Graphen. In Etappe 3 erforschen die Schüler:innen m und b zuerst an Sachsituationen (Bergwanderung, Taxifahrt, Kerze). Forscherfragen prüfen die Beobachtungen.
- **Merksatz:** Die Schüler:innen formulieren mit Satzanfängen einen eigenen Merksatz. Erst danach erscheint der Merkkasten zum Vergleichen. Dann wird der Merksatz ins Heft übertragen.
- **Üben:** Aufgaben werden jedes Mal neu erzeugt, mit gestuften Hilfen (Tipp 1, Tipp 2, Beispiel). Jeder Aufgabentyp muss 3-mal hintereinander ohne Fehlversuch und ohne Hilfe gelöst werden. Erst dann ist die Schlüsselprüfung frei.
- **Schlüsselprüfung:** 4 Aufgaben ohne Hilfe, ein Versuch pro Aufgabe. Mit 3 richtigen Antworten öffnet sich die nächste Tür.
- **Heft:** Die App fordert Musteraufgaben bei jedem neuen Aufgabentyp, gelegentliche Heft-Momente und einen Merksatz pro Etappe ein. Die Schüler:innen bestätigen selbst, dass der Eintrag im Heft steht.
- **Motivation:** Höhenmeter, Ränge (Wanderer, Bergsteiger, Alpinist, Gipfelstürmer), Tage-Serie, Kristalle aus Bonusaufgaben.
- **Speichern mit 6-stelligem Code** (z. B. `K7M-4QX`). Der Code speichert die Schlüssel ab Etappe 3, die gemeisterten Aufgabentypen der aktuellen Etappe, die Höhenmeter (auf 50 gerundet), den Bestwert der Probearbeit und die Tage-Serie. Kristalle, Merksätze und angefangene Serien bleiben nur auf dem Gerät (localStorage). Bei „Neu starten“, beim Einloggen mit einem Code und bei „Sitzung beenden“ werden die Daten auf dem Gerät gelöscht.

Grundlage ist die App „Gipfelweg Lineare Funktionen“ einer Kollegin, angepasst für diese Klasse.

---

## Zufall im Griff – Lernspiel Wahrscheinlichkeit (`ZufallImGriffLernspielWahrscheinlichkeit.html`)

Eine Lern-App zu den Themen:

- Laplace-Experimente
- Baumdiagramme (Knotenregel, Anzahl der Pfade)
- Pfadregel
- Summenregel
- Gegenereignis
- Ziehen mit und ohne Zurücklegen

### Funktionen

- **Einstufungstest** (12 Aufgaben): Danach zeigt die App für jedes Thema den Wissensstand (Einsteiger, Auf dem Weg, Sicher, Profi) und empfiehlt, womit man weitermacht.
- **Übungsrunden** mit 8 Aufgaben pro Thema oder gemischt. Die Aufgaben werden jedes Mal neu erzeugt, und ihre Schwierigkeit (Stufe 1–3) richtet sich nach dem Wissensstand.
- **Hilfe bei Fehlern:** Die App erkennt typische Fehler (z. B. „addiert statt multipliziert“, „1 − vergessen“, „gerechnet wie mit Zurücklegen“) und gibt einen passenden Tipp. Man hat einen zweiten Versuch. Danach gibt es den Lösungsweg mit Baumdiagramm und einen Spickzettel zum Weiterlernen.
- **Motivation:** XP und Level mit Titeln, Serien, Tagesziel (10 Aufgaben), Tage-Serie, 12 Abzeichen, Sterne pro Runde und Konfetti.
- **Speichern mit Code:** Die App startet beim Öffnen immer bei Null. Über „Speichern“ bekommt man einen 36-stelligen Code (z. B. `550V-G121-…`). Mit „Weiter arbeiten“ auf der Startseite gibt man ihn ein und ist wieder beim eigenen Lernstand. Der Code enthält Chips, Level, Wissensstand je Thema, Abzeichen, Serien und die drei häufigsten Fehler.
- Antworten als Bruch (`3/8`), Dezimalzahl (`0,375`) oder Prozent (`37,5 %`).

### Technik

- Es wird nichts im Browser oder auf einem Server gespeichert. Der Lernstand steckt komplett im Code. Der Code ist mit einer Prüfsumme gesichert, sodass Tippfehler meist erkannt werden. Er ist aber nicht verschlüsselt: Er schützt nicht vor gezieltem Manipulieren.
- Wer die Seite mit ungespeichertem Fortschritt schließen will, wird vom Browser gewarnt.
