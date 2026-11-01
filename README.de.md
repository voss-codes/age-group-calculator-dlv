🇬🇧 [English version](README.md)

# Altersklassenrechner für den Laufsport (DLV-Regeln)

Ein einfacher Altersklassenrechner für Laufveranstaltungen nach den Regeln des Deutschen Leichtathletik-Verbands (DLV). Er besteht aus einer einzigen HTML-Datei und lässt sich in WordPress einbetten.

## Funktionen

- Berechnet die Altersklasse aus Wettkampfjahr, Geschlecht und Geburtsdatum
- Deckt Kinder, Jugend, Junioren, U23, Aktive und Masters ab (M/W30 aufwärts in 5-Jahres-Schritten)
- Keine Abhängigkeiten, keine externen Bibliotheken
- Responsives Layout
- Oberflächensprache: Deutsch

## Funktionsweise

Nach der DLV-Wettkampfordnung ist das im Wettkampfjahr erreichte Alter maßgeblich:

```
Alter = Wettkampfjahr − Geburtsjahr
```

Der genaue Geburtstag spielt keine Rolle.

## Verwendung

### In WordPress einbetten

1. Die Seite oder den Beitrag öffnen, in dem der Rechner erscheinen soll.
2. Einen Block **Eigenes HTML** hinzufügen.
3. Den gesamten Inhalt von `age-group-calculator.html` in den Block kopieren.
4. Seite speichern bzw. veröffentlichen.

### Eigenständig nutzen

`age-group-calculator.html` herunterladen und in einem beliebigen modernen Browser öffnen.

## Anpassung

- **Farben und Layout:** CSS im Bereich `<style>` bearbeiten (Klassen beginnen mit `akr-`).
- **Altersklassen:** Die Funktion `ermittleAltersklasse` im Bereich `<script>` anpassen.

## Haftungsausschluss

Dieses Tool wird ohne Gewähr bereitgestellt. Für verbindliche Meldungen bitte immer die aktuelle Ausschreibung bzw. die offizielle DLV-Wettkampfordnung beachten.

## Lizenz

Veröffentlicht unter der [MIT-Lizenz](LICENSE).
