---
name: allgemein
description: "Einstieg und Ueberblick fuer das 3D-Tabellenreview-Plugin: Massenpruefung von Vertragsstapeln als dreidimensionaler Wuerfel aus Spaltenprompts (Datenpunkte), Zeilenprompts (Dokumente) und Arbeitsblatt-Perspektiven (Recht, Steuer, Wirtschaft) mit Excel-Export, Kreuzblatt-Konsistenz, Audit-Trail und Belegkette."
---

# Tabellenreview 3D — Allgemein

## Worum geht es?

Das Plugin strukturiert die Massenpruefung von Vertragsstapeln und Due-Diligence-Unterlagen als dreidimensionalen Wuerfel: Die erste Dimension sind Spaltenprompts, die je einen Pruefpunkt (z. B. Kuendigungsklausel, Laufzeit) abfragen. Die zweite Dimension sind Zeilenprompts, die jedes einzelne Dokument des Stapels repraesentieren. Die dritte Dimension sind Arbeitsblatt-Perspektiven, die denselben Datensatz aus unterschiedlichen fachlichen Blickwinkeln betrachten (Recht, Steuer, Wirtschaft).

Das Ergebnis wird als Excel-Datei mit mehreren Arbeitsblaettern exportiert, enthaelt eine Kreuzblatt-Konsistenzpruefung auf Widersprueche zwischen den Dimensionen, einen lueckenlosen Audit-Trail und eine Belegketten-Dokumentation. Typische Einsaetzgebiete sind M-und-A-Due-Diligence, Immobilien-Portfoliopruefung, Vendor-Onboarding und Arbeitsvertrags-Portfolio-Review.

## Wann brauchen Sie diese Skill?

- Sie muessen 20 oder mehr Vertraege auf dieselben Pruefpunkte hin systematisch analysieren und das Ergebnis auswertbar dokumentieren.
- Eine M-und-A-Due-Diligence erfordert die gleichzeitige Betrachtung von Vertraegen aus rechtlicher, steuerlicher und wirtschaftlicher Perspektive.
- Ein Lieferant soll ongeboardet werden und Vertrag, Compliance-Status und Leistungsindikatoren muessen dokumentiert werden.
- Der Pruefer wechselt und das bisher bearbeitete Paket soll mit vollem Kontext und offenem Status uebergeben werden.
- Zwischenergebnisse sollen gecacht und einzelne Teile ohne Vollneustart erneut ausgefuehrt werden.

## Fachbegriffe (kurz erklaert)

- **Wuerfel** — Metapher fuer die dreidimensionale Pruefstruktur: Zeilen (Dokumente) x Spalten (Pruefpunkte) x Perspektiven (Blickwinkel).
- **Spaltenprompt** — Einzelne Frage oder Pruefanweisung, die fuer jedes Dokument in einer bestimmten Spalte beantwortet wird.
- **Zeilenprompt** — Dokumentspezifische Pruefanweisung, die das einzelne Dokument als Pruefgegenstand definiert.
- **Arbeitsblatt-Perspektive** — Fachlicher Blickwinkel (Recht, Steuer, Wirtschaft), der denselben Wuerfel in einem eigenen Excel-Sheet abbildet.
- **Kreuzblatt-Konsistenzpruefung** — Abgleich der drei Dimensionen auf Widersprueche und fehlende Eintraege.
- **Audit-Trail** — Lueckenlose Protokollierung aller Pruefschritte mit Zeitstempel, Pruefer-ID und Aenderungshistorie.
- **Risikoampel** — Rot-Gelb-Gruen-Bewertung je Pruefposition zur schnellen Risikouebersicht.
- **Belegkette** — Nachverfolgung der Originalbelege hinter jeder Buchung oder Forderung.

## Rechtsgrundlagen

- §§ 174 ff. InsO — Forderungsanmeldung und -pruefung (Stammreferenz der 3D-Review-Skills)
- §§ 238 257 HGB — Buchfuehrungs- und Aufbewahrungspflichten
- GmbHG AktG HGB InsO — Relevante Normen je nach Vorlagen-Typ
- BGB §§ 305 ff. — AGB-Kontrolle bei Vertragsstapeln
- BetrAVG — Bei Arbeitsvertrag-Portfolio-Reviews
- DSGVO Art. 5 — Datensparsamkeit bei Verarbeitung von Vertragsdaten

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Kaltstart-Interview: Fallkategorie, Tabellengroesse, Pruefzweck und Exportformat erfassen.
2. Wuerfelstruktur aufbauen: Spaltenprompts und Zeilenprompts definieren, Perspektiven festlegen.
3. Dokumentstapel einlesen und Inventar erstellen.
4. Review durchfuehren: jede Zeile in allen drei Perspektiven pruefen und Risikoampel setzen.
5. Kreuzblatt-Konsistenzpruefung und Audit-Trail abschliessen; Excel-Export oder PDF-Bericht erzeugen.

## Skill-Tour (was gibt es hier?)

- `arbeitsblatt-perspektiven-definieren` — Die drei Pruefperspektiven (Recht, Steuer, Wirtschaft) fuer den 3D-Wuerfel definieren.
- `audit-trail-protokoll` — Alle Review-Schritte mit Zeitstempel und Pruefer-ID protokollieren.
- `belegkette-rueckverfolgung` — Belegkette fuer Forderungen und Zahlungen zurueckverfolgen.
- `caching-und-teil-rerun` — Zwischenergebnisse cachen und Teilbereiche ohne Vollneustart erneut ausfuehren.
- `dokumentstapel-aufnehmen` — Dokumentenstapel (PDFs, Excel, Word) einlesen und Inventar erstellen.
- `excel-multi-sheet-export` — 3D-Review-Ergebnis als Excel-Datei mit Arbeitsblaettern je Perspektive exportieren.
- `kreuzblatt-konsistenzpruefung` — Abgleich der drei Dimensionen auf Widersprueche und fehlende Eintraege.
- `pdf-bericht-erzeugen` — 3D-Review-Ergebnis als PDF-Bericht mit Zusammenfassung, Tabellen und Risikoampeln erzeugen.
- `prompt-versionierung` — Prompt-Versionen fuer den 3D-Review verwalten und aendern.
- `pruefer-uebergabe-paket` — Uebergabepaket fuer Prueferwechsel mit aktuellem Stand und offenen Positionen.
- `review-durchfuehren` — 3D-Tabellenreview konkret durchfuehren: jede Zeile in allen drei Perspektiven pruefen.
- `risikoampel-aggregation` — Risikoampeln fuer alle geprueften Positionen aggregieren und Gesamtrisiko einschaetzen.
- `spaltenprompts-definieren` — Spaltenprompts fuer die drei Pruefperspektiven definieren.
- `tabellenreview-3d-kaltstart-interview` — Kaltstart-Interview: Fallkategorie, Tabellengroesse, Pruefzweck und Exportformat erfassen.
- `vorlage-arbeitsvertrag-portfolio` — Vorlagetabelle fuer Portfolio-Review von Arbeitsvertraegen im 3D-Format.
- `vorlage-immobilien-portfolio` — Vorlagetabelle fuer Portfolio-Review von Immobilienvertraegen im 3D-Format.
- `vorlage-ma-due-diligence` — Vorlagetabelle fuer M-und-A-Due-Diligence im 3D-Format.
- `vorlage-vendor-onboarding-3d` — Vorlagetabelle fuer Lieferanten-Onboarding-Review im 3D-Format.
- `wuerfel-aufbauen` — 3D-Wuerfelstruktur aufbauen: Zeilen, Spalten und Perspektiven verknuepfen.
- `zeilenprompts-definieren` — Zeilenprompts fuer einzelne Pruefpositionen im 3D-Review definieren.

## Worauf besonders achten

- **Kreuzblatt-Konsistenz vor Export pruefen**: Widersprueche zwischen den Dimensionen koennen die Aussagekraft des Berichts untergraben.
- **Prompt-Versionierung dokumentieren**: Unterschiedliche Prompt-Versionen im selben Review produzieren nicht vergleichbare Ergebnisse.
- **Audit-Trail von Beginn an fuehren**: Nachtraegliches Erganzen des Protokolls ist fehleranfaellig und im Zweifel nicht beweissicher.
- **Caching konservativ einsetzen**: Gecachte Ergebnisse werden nicht neu berechnet; Aenderungen im Dokument werden nicht erfasst.
- **Vorlagen nicht ohne Anpassung verwenden**: Vorlage-Spaltenprompts sind Ausgangspunkte, keine abschliessenden Pruefkataloge.

## Typische Fehler

- Wuerfelstruktur ohne Kaltstart-Interview aufbauen; Pruefzweck und Exportformat werden spaeter nicht erfuellt.
- Alle drei Perspektiven mit identischen Prompts besetzen; der Wuerfel verliert seine Informationstiefe.
- Risikoampel-Schwellenwerte nicht explizit definieren; Ampelbewertungen werden inkonsistent.
- Prueferwechsel ohne Uebergabepaket; Nachfolger muss von vorne beginnen.
- Excel-Export ohne Kreuzblatt-Pruefung; Inkonsistenzen werden erst beim Mandanten entdeckt.

## Querverweise

- `insolvenzverwaltung` — Forderungstabellen sind ein typischer 3D-Review-Anwendungsfall.
- `aktenauszug-gerichtsverfahren` — Gerichtsakte-Bausteine koennen als Zeilen in einen Vertragsstapel einfliessen.
- `bav-strategie-konzern` — bAV-Vertragsstapel eignen sich fuer 3D-Review auf Durchfuehrungswege und Mitbestimmung.
- `immobilienrechtspraxis` — Immobilien-Portfolio-Reviews als Standardanwendungsfall des 3D-Wuerfels.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
