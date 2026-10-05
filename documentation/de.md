<!-- ELUCENIA technical documentation · escala-de-katz · de · no clinical/professional/rights approval -->

# Katz-Index (grundlegende Alltagsaktivitäten)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-katz)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Baden (selbstständig: badet allein oder benötigt Hilfe nur für einen Körperteil)

`banho`

- `0` — Abhängig
- `1` — Selbstständig

### Ankleiden (selbstständig: holt Kleidung und zieht sich ohne Hilfe an, außer beim Schuhebinden)

`vestir`

- `0` — Abhängig
- `1` — Selbstständig

### Toilettenbenutzung (selbstständig: geht zur Toilette, reinigt sich und richtet die Kleidung ohne Hilfe)

`higiene`

- `0` — Abhängig
- `1` — Selbstständig

### Transfer (selbstständig: legt sich ins Bett und steht von Bett und Stuhl ohne Hilfe auf)

`transf`

- `0` — Abhängig
- `1` — Selbstständig

### Kontinenz (selbstständig: vollständige Kontrolle von Blase und Darm)

`contin`

- `0` — Abhängig
- `1` — Selbstständig

### Nahrungsaufnahme (selbstständig: führt das Essen vom Teller zum Mund ohne Hilfe)

`alim`

- `0` — Abhängig
- `1` — Selbstständig

## Fassung der Methode

Binärer Katz-ADL: 6 Aktivitäten, Gesamtwert 0–6; HIGN-Formular 2019, geringfügig nach Katz et al. 1970 angepasst; ohne die A–G-Kategorien von 1963

## Dokumentierte Formel

1 Punkt je selbstständiger Aktivität (ohne Aufsicht, Anleitung oder Hilfe anderer): Baden, Ankleiden, Toilette, Transfer, Kontinenz, Essen. Gesamt 0–6.

## Grenzen und Population

Dokumentieren Sie die Indexversion und die Definitionen von Selbstständigkeit je Aktivität. Die brasilianische Anpassung von 2008 wurde auf kulturelle Äquivalenz und Zuverlässigkeit untersucht; dies zertifiziert weder diese binäre Implementierung noch ihre neuen Übersetzungen. Die lokale Summe 0–6 ist nicht die historische Klassifikation A–G. Die binäre Summe von 6 Aktivitäten wurde anhand des HIGN-Formulars von 2019 geprüft, das als geringfügige Anpassung nach Katz et al. 1970 ausgewiesen ist. Diese Quelle ist nicht die A–G-Klassifikation von 1963 und bestätigt weder die brasilianische Anpassung von 2008 noch die aktuellen selbst verfassten Übersetzungen. Ausnahmen bei der Selbstständigkeit und der Zweck der Beurteilung grundlegender Aktivitäten älterer Menschen richten sich nach dem entsprechenden Formular.

## Referenzen

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
