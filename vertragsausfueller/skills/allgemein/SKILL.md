---
name: allgemein
description: "Einstieg und Orientierung im Vertragsausfueller-Plugin. Klaert Eingabedokument-Typ (Vorlage, Altvertrag, Term Sheet), Ausfuellworkflow, Feldinventar, Klauselentscheidungen, Quality Gate und Track-Changes-Handling."
---

# Vertragsausfueller — Allgemein

## Worum geht es?

Dieses Plugin fuehrt Anwaelte und ihre Mandanten durch den vollstaendigen Workflow zum Ausfullen, Aktualisieren und Qualitaetssichern von Vertragsvorlagen und Altvertraegen. Es erkennt automatisch den Eingabedokument-Typ (DOCX-Vorlage, Altvertrag, Term Sheet, Freitext), erstellt ein Feldinventar, fuehrt ein strukturiertes Ruckfrageninterview, trifft Klauselentscheidungen, prueft Plausibilitaet und gibt eine bereinige Clean-Version aus. Track-Changes-Fassungen werden nur nach ausdrucklicher Bestaetigung erstellt.

Das Plugin deckt alle gaengigen deutschen Vertragstypen ab: Mietvertraege, Arbeitsvertraege, Kaufvertraege, Dienstleistungsvertraege und individualvertragliche Sondergestaltungen. Es wendet AGB-Recht und Schriftformerfordernisse automatisch an.

## Wann brauchen Sie diese Skill?

- Anwalt oder Mandant uebergibt eine unbekannte DOCX-Vorlage und moechte wissen, welche Felder ausgefallt werden mussen.
- Ein Term Sheet liegt vor und soll systematisch in die entsprechende Vertragsvorlage uebertragen werden.
- Altvertrag soll auf eine neue Vorlage nachgezogen oder aktualisiert werden (Parteienwechsel, Gesetzesaenderungen).
- Gegenentwurf liegt vor und soll auf Vollstandigkeit, versteckte Aenderungen und ungeklartel Klauselentscheidungen geprueft werden.
- Fertig ausgefullter Vertragsentwurf soll vor Unterschrift oder Versand auf Rechenfehler, Inkonsistenzen und AGB-Verstoeasse geprueft werden.

## Fachbegriffe (kurz erklaert)

- **Feldinventar** — Strukturierte Liste aller ausfullbaren Felder einer Vertragsvorlage mit Pflicht/Optional-Status, Quelle und Risikohinweis.
- **Term Sheet** — Vorvertragliches Eckpunktepapier; Letter of Intent oder Term Sheet werden auf Vertragsfelder gemappt.
- **Track Changes** — Dokumenten-Aenderungsmarkierung in Word (DOCX); wird nur nach ausdrucklicher Bestaetigung ausgegeben.
- **AGB-Kontrolle** — Pruefung von allgemeinen Geschaeftsbedingungen nach §§ 305 bis 310 BGB; strenger Massstab bei B2C, geringer bei B2B.
- **Schriftformerfordernis** — § 550 BGB bei Mietvertraegen laenger als ein Jahr; § 125 BGB bei gesetzlicher Schriftform; Fehler macht Vertrag unwirksam.
- **Redline** — Uberarbeitete Vertragsfassung mit sichtbaren Aenderungen gegenuber dem Ausgangsdokument.
- **Clean Output** — Bereinigter Vertragsentwurf ohne Platzhalter und Track-Changes fuer Unterzeichnung oder Versand.
- **Plausibilitaetscheck** — Pruefung von Betragen, Fristen, Querverweisen und interner Konsistenz vor Ausgabe.

## Rechtsgrundlagen

- §§ 305 bis 310 BGB — AGB-Recht; Inhaltskontrolle.
- §§ 125 ff. BGB — Schriftformerfordernisse und Nichtigkeitsfolge.
- § 550 BGB — Schriftformerfordernis bei Mietvertrag laenger als ein Jahr.
- § 622 BGB — Kundigungsfristen Arbeitsvertraege.
- § 2 NachwG — Nachweispflichten im Arbeitsvertrag (Pflichtfelder).
- § 557b BGB — Indexmiete.
- § 9 UStG — Umsatzsteueroption bei Immobilienvermietung (Vorsteuerabzug).

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Eingabedokument-Typ bestimmen: Skill `vaf-kommandocenter` erkennt Vorlage, Altvertrag, Term Sheet oder Freitext.
2. Vorlage analysieren: `vaf-template-erkennung` oder `vaf-docx-stripper` fuer DOCX-Dokumente.
3. Feldinventar erstellen: `vaf-feldinventar`.
4. Ruckfrageninterview fuer offene Felder: `vaf-rueckfrageninterview`.
5. Klauselentscheidungen treffen: `vaf-klauselentscheidung`.
6. Quality Gate und Clean Output: `vaf-quality-gate` dann `vaf-clean-output`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Routing**

- `vaf-kommandocenter` — Eingabedokument-Typ erkennen, Workflow starten, Track-Changes-Bestaetigung einholen.

**Vorlage und Dokumentanalyse**

- `vaf-template-erkennung` — Vertragstyp, Klauselstruktur, Pflichtfelder und Wahlklauseln identifizieren.
- `vaf-docx-stripper` — DOCX-Vorlage in strukturierten Text zerlegen: Absaetze, Tabellen, Platzhalter, Anlagen.
- `vaf-feldinventar` — Feldinventar erstellen: Pflichtfelder, optionale Felder, Risikofelder.

**Daten- und Inhaltserfassung**

- `vaf-rueckfrageninterview` — Ruckfrageninterview fuer fehlende Vertragsdaten; mandantenfreundliche Fuehrung.
- `vaf-termsheet-mapping` — Term Sheet auf Vertragsfelder mappen; Lucken und Widersprueche erkennen.

**Klauselentscheidungen**

- `vaf-klauselentscheidung` — Wahlklauseln und Klauselalternativen entscheiden (Indexierung, USt-Option, Konkurrenzschutz).

**Aktualisierung**

- `vaf-altvertrag-nachziehen` — Altvertrag auf neue Vorlage nachziehen; Gesetzesaenderungen einpflegen.
- `vaf-bsag-mietvertrag` — BSAG-Kiosk-Mietvertrag spezifisch ausfullen.

**Qualitaetssicherung und Output**

- `vaf-plausibilitaetscheck` — Betrage, Fristen, Querverweise und interne Widersprueche pruefen.
- `vaf-quality-gate` — Gesamtpruefung: alle Pflichtfelder, AGB-Zulaessigkeit, Anlagen, Freigabe.
- `vaf-clean-output` — Bereinigter finaler Vertragsentwurf mit Ausfullprotokoll und Annahmenregister.

**Redline und Track Changes**

- `vaf-redline-qa` — Redline oder Gegenentwurf auf Vollstandigkeit und versteckte Aenderungen pruefen.
- `vaf-track-changes-nur-nach-frage` — Track-Changes-Fassung nur nach ausdrucklicher Bestaetigung erstellen.

## Worauf besonders achten

- **Schriftformerfordernis ist Fallstrick** — § 550 BGB bei Mietvertraegen laenger als ein Jahr; fehlende Unterschrift oder fehlende Anlage macht den Langzeitmietvertrag in ein Jahresvertrag ohne Kuendigungsschutz umzudeuten.
- **AGB oder Individualvertrag klaeren zuerst** — Die Intensitaet der AGB-Kontrolle haengt davon ab; ein Verhandlungsprotokoll kann Individualvertragscharakter begruenden.
- **Track-Changes-Bestaetigung nicht vergessen** — Das Plugin fragt explizit nach, bevor eine Redline erstellt wird; ohne Bestaetigung wird Clean Output ausgegeben.
- **Term Sheet ist oft unvollstaendig** — Steuerliche Punkte, USt-Option und Wettbewerbsverbote sind im Term Sheet haeufig nicht geregelt; `vaf-termsheet-mapping` markiert Lucken.
- **NachwG-Pflichtfelder bei Arbeitsvertraegen** — § 2 NachwG schreibt bestimmte Angaben vor; Fehlen kann Bussgeld ausloesen.

## Typische Fehler

- Vorlage wird direkt ausgefullt, ohne Schriftformerfordernis und AGB-Kontrolle vorab zu pruefen.
- Track-Changes-Fassung wird ausgegeben, ohne dass Quality Gate gruene Ampel gezeigt hat.
- Term Sheet wird eins zu eins uebernommen, ohne Widersprueche zur Vertragsvorlage zu prufen.
- Wahlklauseln bleiben unentschieden (Leerfelder in der Endfassung).
- Plausibilitaetscheck wird uebersprungen; Rechenfehler bei Mietbetrag oder Indexierung erst vom Mandanten bemerkt.

## Querverweise

- `bereicherungs-und-anfechtungsrecht-pruefer` — Wenn ausgefullter Vertrag angefochten oder rueckabgewickelt werden soll.
- `insolvenzrecht` — Wenn Vertragspartner insolvent ist und Vertragsfortsetzung oder Kuendigung zu pruefen ist.
- `europarecht-kompass` — Bei grenzueberschreitenden Vertraegen mit EU-Rechtsbezug (Richtlinien, AGB-Richtlinie).

## Quellen und Aktualitaet

- Stand: 05/2026
- BGB §§ 125 ff. und §§ 305 bis 310 in der geltenden Fassung
- NachwG § 2 in der geltenden Fassung
- UStG § 9 in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
