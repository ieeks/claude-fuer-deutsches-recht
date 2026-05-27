---
name: allgemein
description: "Einstieg und Orientierung im Produktrecht-Plugin. Klaert produktrechtliche Prüfpflichten vor Launch, Impressumspflicht nach DDG, Preisangaben nach PAngV, Werbeaussagen nach UWG und Risikobewertung für Features."
---

# Produktrecht — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Produktmanager, Rechtsabteilungen und externe Anwaelte bei der produktrechtlichen Freigabe von digitalen und physischen Produkten vor dem Launch. Es deckt die zentralen rechtlichen Anforderungen ab: Impressumspflicht nach §§ 5 und 6 DDG und § 18 MStV, Preisangaben nach der Preisangabenverordnung 2022 (PAngV), Werbeaussagen nach UWG und EU-Recht (Omnibus-Richtlinie, Health Claims, ESG-Kommunikation), produktsicherheitsrechtliche Anforderungen (ProdSG, EU-Produktsicherheits-VO 2023/988, CE-Kennzeichnung) sowie UWG-Verstoessrisiken und DSGVO-Schnittstellen.

Das Plugin richtet sich an ein internes Rechts-Ops-Publikum: Entscheider in Rechtsabteilungen, Compliance-Teams und Kanzleien, die schnell und strukturiert produktrechtliche Risiken identifizieren wollen.

## Wann brauchen Sie diese Skill?

- Produkt oder Feature soll gelauncht werden und Rechtsabteilung muss gruene Ampel geben.
- Impressum einer Website, App oder Social-Media-Praesenz soll auf Vollstaendigkeit und Abmahnrisiken geprueft werden.
- Marketing will eine Werbeaussage prufen lassen: Streichpreise, Grundpreise, Health Claims, Klimaneutralitaet.
- Ein Feature des Produkts hat ein Risiko erzeugt, das tiefer analysiert werden muss als eine Checklisten-Zeile.
- Kaltstart: Plugin soll erstmalig konfiguriert und auf das Risikoprofil der Rechtsabteilung kalibriert werden.

## Fachbegriffe (kurz erklaert)

- **DDG** — Digitale-Dienste-Gesetz; nationales Ausfuehrungsgesetz; §§ 5 und 6 DDG regeln Anbieterkennzeichnungspflicht (Impressum).
- **PAngV** — Preisangabenverordnung 2022; regelt Gesamtpreise, Grundpreise, Streichpreise und die 30-Tage-Niedrigstpreisregel bei Preisreduzierungen.
- **UWG** — Gesetz gegen den unlauteren Wettbewerb; Massstab fuer irrefuehrende Werbeaussagen, vergleichende Werbung und aggressive Geschaeftspraktiken.
- **ProdSG** — Produktsicherheitsgesetz; regelt Sicherheitsanforderungen und Marktueberaufsicht.
- **CE-Kennzeichnung** — Konformitaetszeichen fuer Produkte, die EU-Harmonisierungsrecht entsprechen; Pflicht fuer viele Produktkategorien.
- **Health Claims** — Naehrwert- und gesundheitsbezogene Angaben; geregelt in VO (EG) 1924/2006; strenge Zulassungspflicht.
- **30-Tage-Niedrigstpreisregel** — Bei Preisreduzierungen muss als Ausgangspreis der niedrigste Preis der letzten 30 Tage angegeben werden (§ 11 PAngV; Omnibus-Richtlinie 2019/2161).
- **Launch-Review** — Strukturiertes rechtliches Freigabeverfahren vor Produkteinfuehrung mit Ampel-Status und offenem-Punkte-Liste.

## Rechtsgrundlagen

- §§ 5 und 6 DDG — Impressumspflicht.
- § 18 MStV — Impressumspflicht im Rundfunk- und Medienbereich.
- PAngV 2022 — Preisangaben; insb. § 11 PAngV (Streichpreise), § 4 PAngV (Grundpreis).
- UWG §§ 3 bis 7 — Irrefuehrende und aggressive Geschaeftspraktiken.
- ProdSG, EU-Produktsicherheits-VO 2023/988 — Produktsicherheit und CE-Konformitaet.
- VO (EG) 1924/2006 — Health Claims.
- AI Act (EU) 2024/1689 — KI-VO; Risikoklassen fuer KI-Systeme (relevant fuer KI-Features).
- DSGVO — Datenschutz-Schnittstelle fuer Features mit Personenbezug.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Plugin konfigurieren (Erstnutzung): Skill `produktrecht-kaltstart-interview`.
2. Schnelle Plausibilitaetsfrage: Skill `ist-das-ein-problem` fuer Kurzantwort in Minuten.
3. Vollstaendige Launch-Freigabe: Skill `launch-pruefung`.
4. Vertieftes Einzel-Risiko: `feature-risikobewertung`.
5. Spezialthemen: `impressum-pflicht`, `preisangaben` oder `werbeaussagen-pruefung` direkt ansteuern.

## Skill-Tour (was gibt es hier?)

**Konfiguration und Mandatsverwaltung**

- `produktrecht-kaltstart-interview` — Plugin erstmalig einrichten; Risikokalibrierung, Launch-Framework, Eskalationsmatrix.
- `produktrecht-anpassen` — Einzelne Elemente des Praxisprofils aendern ohne Kaltstart-Interview.
- `produktrecht-mandat-arbeitsbereich` — Produktmandate anlegen, wechseln, abschliessen.

**Triage und Launch**

- `ist-das-ein-problem` — Schnelle Kurzantwort fuer PM-Fragen; fuenf Minuten, mit Quellenangabe.
- `launch-pruefung` — Vollstaendige rechtliche Launch-Freigabepruefung mit Ampel-Status.
- `feature-risikobewertung` — Tiefgehende Risikobewertung fuer ein einzelnes Feature oder einen Produktbereich.

**Spezialthemen**

- `impressum-pflicht` — Impressumspflicht nach §§ 5 und 6 DDG und § 18 MStV; konformer Impressumstext; Abmahnrisiken.
- `preisangaben` — PAngV 2022: Gesamtpreise, Grundpreise, Streichpreise, 30-Tage-Niedrigstpreisregel.
- `werbeaussagen-pruefung` — Werbebehauptungen auf UWG-, Health-Claims- und ESG-Risiken pruefen.

## Worauf besonders achten

- **Impressumspflicht gilt auch fuer Social-Media-Profile** — Gewerblich genutzte Profile bei Instagram, LinkedIn oder X muessen vollstaendiges Impressum enthalten oder klar darauf verlinken.
- **30-Tage-Regel ist keine Empfehlung, sondern Pflicht** — Streichpreise muessen auf dem Niedrigstpreis der letzten 30 Tage vor Reduzierung basieren; Verstaesse sind abmahnbar.
- **KI-Features benoetigen KI-VO-Check** — Der AI Act gilt fuer KI-Systeme ab August 2026 in vollem Umfang; Hochrisiko-Systeme und verbotene Praktiken muessen vorab identifiziert werden.
- **Health Claims erfordern Zulassung** — Nicht zugelassene Gesundheitsversprechen sind ohne Ausnahme unzulaessig; Positivliste VO 1924/2006 ist abschliessend.
- **Risikokalibrierung ist Ausgangspunkt** — Ohne konfiguriertes Praxisprofil liefert das Plugin nur generische Ergebnisse; `produktrecht-kaltstart-interview` zuerst ausfuehren.

## Typische Fehler

- Impressum fehlt oder ist unvollstaendig (keine Rechtsform, kein Vertretungsberechtigter, keine USt-IdNr. bei Pflicht); erhoehtes Abmahnrisiko.
- Streichpreis-Aktion wird ohne Pruefung des Niedrigstpreises der letzten 30 Tage gestartet; PAngV-Verstoss.
- Feature mit KI-Komponente wird gelauncht ohne Pruefung, ob es als Hochrisiko-KI-System nach AI Act gilt.
- Werbeaussage zu Klimaneutralitaet oder Nachhaltigkeit wird nicht mit belastbaren Nachweisen unterlegt; Greenwashing-Abmahnrisiko.
- Launch-Pruefung wird als Checkliste abgehakt, ohne Risikokalibrierung und Eskalationsschwellen der eigenen Rechtsabteilung.

## Querverweise

- `dsa-dma-digitalregulierung` — Fuer DSA-Pflichten bei Online-Plattformen und VLOP-Einordnung.
- `europarecht-kompass` — Fuer EU-Rechtsquellen-Einordnung (Verordnung, Richtlinie) bei EU-Produktregulierung.
- `vertragsausfueller` — Fuer Lizenz- und Vertriebsvertraege im Produktkontext.

## Quellen und Aktualitaet

- Stand: 05/2026
- DDG §§ 5 und 6 in der geltenden Fassung
- PAngV 2022 in der geltenden Fassung
- UWG in der geltenden Fassung
- EU-Produktsicherheits-VO 2023/988 in der geltenden Fassung
- AI Act (EU) 2024/1689 in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
