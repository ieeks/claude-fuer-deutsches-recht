---
name: allgemein
description: "Einstieg und Triage im Arbeitsrecht: Mandantenrolle klaeren, Sofort-Fristen pruefen (KSchG-Klage drei Wochen, Entfristung drei Wochen), Schwerpunkt bestimmen (Kuendigung, Befristung, Betriebsrat, Expansion, Untersuchung) und zu Folge-Skills routen."
---

# Arbeitsrecht — Allgemein

## Worum geht es?

Das Arbeitsrecht-Plugin deckt das gesamte Individual- und Kollektivarbeitsrecht fuer Arbeitgeber und Arbeitnehmer ab: Kuendigungsschutzklage (KSchG), Entfristungsklage (TzBfG), Aufhebungsvertrag, Abmahnung, Betriebsratsanhoerung (§ 102 BetrVG), Betriebsuebergang (§ 613a BGB), Massenentlassung (§ 17 KSchG), AGG-Pruefung, HinSchG-Whistleblower, Mindestlohn, Arbeitszeiterfassung sowie interne Untersuchungen und internationale Expansion. Aktuelle BAG-Rechtsprechung 2025/2026 ist eingearbeitet (Equal Pay, Mindesturlaub-Verzicht, Freistellungsklausel).

Das Plugin richtet sich an Kanzleien und Syndikusrechtsanwaelte, die sowohl Arbeitgeber- als auch Arbeitnehmer-Mandate betreuen.

## Wann brauchen Sie diese Skill?

- Ein Mandant hat eine Kuendigung erhalten oder will eine Kuendigung aussprechen und es ist sofort die Drei-Wochen-Frist des § 4 KSchG zu sichern.
- Ein befristetes Arbeitsverhaeltnis laeuft aus und die Befristung soll angegriffen werden (§ 17 TzBfG: Drei-Wochen-Frist gilt ebenso).
- Ein Aufhebungsvertrag ist vorhanden und Sperrzeit-Risiko sowie steuerliche Behandlung der Abfindung sollen geklaert werden.
- Ein Betriebsrat soll angehoert werden oder hat einen Widerspruch eingelegt (§ 102 BetrVG).
- Ein Mitarbeiter hat einen Hinweis auf Missstande gemeldet und der HinSchG-Schutz soll beurteilt werden.

## Fachbegriffe (kurz erklaert)

- **KSchG** — Kuendigungsschutzgesetz; schutzt Arbeitnehmer mit mehr als sechs Monaten Betriebszugehoerigkeit in Betrieben mit mehr als zehn Arbeitnehmern.
- **TzBfG** — Teilzeit- und Befristungsgesetz; regelt sachgrundgebundene und sachgrundlose Befristungen; Schriftformzwang nach § 14 Abs. 4 TzBfG.
- **Sozialauswahl** — Pflicht des Arbeitgebers bei betriebsbedingter Kuendigung, die schutzwuerdigsten Arbeitnehmer zu erhalten (§ 1 Abs. 3 KSchG).
- **Sperrzeit** — vorueberstgehende Verweigerung des Arbeitslosengelds nach § 159 SGB III bei Selbstkuendigung oder Aufhebungsvertrag.
- **Betriebsrat** — gewaehltes Arbeitnehmer-Gremium; bei Kuendigung ist Anhoerung nach § 102 BetrVG Wirksamkeitsvoraussetzung.
- **Betriebsuebergang** — Uebergang eines Betriebs oder Betriebsteils auf einen neuen Inhaber (§ 613a BGB); Kuendigungsverbot wegen Betriebsuebergangs.
- **AGG** — Allgemeines Gleichbehandlungsgesetz; verbietet Diskriminierung nach § 1 AGG; Entschaedigungs- und Schadensersatz nach § 15 AGG.

## Rechtsgrundlagen

- §§ 1 ff. KSchG — Kuendigungsschutz; § 4 KSchG Drei-Wochen-Frist
- §§ 14 ff. TzBfG — Befristungsrecht; § 17 TzBfG Drei-Wochen-Frist; § 14 Abs. 4 TzBfG Schriftformzwang
- § 102 BetrVG — Betriebsratsanhoerung vor Kuendigung
- § 613a BGB — Betriebsuebergang
- § 622 BGB — Kuendigungsfristen
- § 626 BGB — Ausserordentliche Kuendigung aus wichtigem Grund
- § 623 BGB — Schriftformzwang fuer Kuendigung und Aufhebungsvertrag
- §§ 1 ff. AGG — Diskriminierungsschutz
- § 1 MiLoG — Mindestlohn
- HinSchG — Hinweisgeberschutzgesetz seit 02.07.2023
- § 17 KSchG — Massenentlassung; Konsultation und Anzeige

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Arbeitnehmer, Arbeitgeber, Betriebsrat, Geschaeftsfuehrer oder Syndikus?
2. Phase des Mandats bestimmen: Noch keine Kuendigung (praeventiv), Kuendigung ausgesprochen/erhalten (Fristensicherung), laufendes Verfahren oder Abschluss?
3. Passenden Skill auswaehlen (siehe Skill-Tour unten).
4. Eilfristen pruefen: § 4 KSchG drei Wochen ab Zugang der Kuendigung; § 17 TzBfG drei Wochen ab vereinbartem Vertragsende — beide absolute Ausschlussfristen.
5. Anschluss-Skill bestimmen: Nach Triage zu Kuendigungsschutzklage-Skills, Entfristungsklage-Skills oder Aufhebungsvertrag.

## Skill-Tour (was gibt es hier?)

**Einrichtung und Mandatsverwaltung**
- `arbeitsrecht-kaltstart-interview` — Ersteinrichtung: Standortprofil, Tarifbindung, Betriebsratssituation und Eskalationsregeln hinterlegen.
- `arbeitsrecht-anpassen` — Praxisprofil nachjustieren ohne vollstaendiges Erstinterview.
- `arbeitsrecht-mandat-arbeitsbereich` — Mandatsakten verwalten: anlegen, wechseln, schliessen.
- `mandat-triage-arbeitsrecht` — Eingangs-Abfrage: Kuendigung, Aufhebungsvertrag, Abmahnung, Lohn, Befristung oder Betriebsrat? Sofort-Fristen-Check.

**Kuendigungsschutzklage (kueschk-)**
- `kueschk-triage-laie-oder-anwalt` — Kerneinstieg: Anwalt oder Laie? Dringende Empfehlung und Routing.
- `kuendigungs-pruefung` — Rechtliche Pruefung einer ordentlichen oder ausserordentlichen Kuendigung.
- `kuendigungsschutzklage` — Entwurf der Kuendigungsschutzklage nach § 4 KSchG.
- `kueschk-anwendbarkeit-kschg-pruefen` — Wartezeit (sechs Monate) und Schwellenwert (zehn Arbeitnehmer) pruefen.
- `kueschk-frist-und-zugang-pruefen` — § 4 KSchG Fristberechnung und Zugangsbeweis.
- `kueschk-formfehler-pruefen` — Schriftform, Vollmachtsruege § 174 BGB, Betriebsratsanhoerung.
- `kueschk-kuendigungsgrund-personen-verhalten-betrieb` — Drei Kuendigungsgruende nach § 1 Abs. 2 KSchG pruefen.
- `kueschk-sonderkuendigungsschutz-checkliste` — Schwangerschaft, Elternzeit, Schwerbehinderung, BR-Mitglied.
- `kueschk-klageschrift-anwalt-baustein` — Anwaltliche Klageschrift mit Hilfsantraegen und Beweisangeboten.
- `kueschk-klageschrift-laie-baustein` — Klageschrift-Baustein fuer Laien mit Warnkopf.
- `kueschk-output-warnschriftsatz-laie` — Vollstaendige Laien-Klageschrift mit Pflicht-Disclaimer.
- `kueschk-grundwarnung-falsche-wiese-und-haftung` — Pflichtkopf mit Drei-Wochen-Frist-Hinweis fuer Laien-Output.
- `kueschk-allgemeiner-und-besonderer-feststellungsantrag` — Unterschied punktueller und allgemeiner Feststellungsantrag.
- `kueschk-guetetermin-strategie-und-sprechzettel` — Guetetermin nach § 54 ArbGG: Ablauf und Strategie.
- `kueschk-kammertermin-sprechzettel` — Sprechzettel fuer Hauptverhandlung im Kuendigungsschutzprozess.
- `kueschk-muendliche-verhandlung-praxistipps-laie` — Praxistipps fuer Laien in der muendlichen Verhandlung.
- `kueschk-erwiderung-arbeitgeber-strategien-typisch` — Typische Verteidigungsstrategien des Arbeitgebers.
- `kueschk-replik-arbeitnehmer-baustein` — Reaktion auf Klageerwiderung des Arbeitgebers.
- `kueschk-annahmeverzug-loehne-anrechnung-zwischenverdienst` — Annahmeverzugslohn § 615 BGB und Zwischenverdienst-Anrechnung.
- `kueschk-weiterbeschaeftigungsantrag-grosser-senat` — Weiterbeschaeftigungsantrag nach BAG Grosser Senat 1985.
- `kueschk-aufloesungsantrag-arbeitnehmer-9-kschg` — Aufloeungsantrag § 9 KSchG bei Unzumutbarkeit.
- `kueschk-paragraph-12-kschg-neuer-job-einseitig` — § 12 KSchG einseitige Loesung nach neuem Arbeitsverhaeltnis.
- `kueschk-stricken-anwalt-risiko-und-vergleichsdruck` — Warnung vor Stricken-Strategie des Arbeitgeberanwalts.
- `kueschk-abfindung-faustformel-und-spannweite` — Abfindungs-Faustformel und steuerliche Fuenftel-Regelung.
- `kueschk-vergleichsverhandlung-checkliste` — Vergleichs-Checkliste: Abfindung, Freistellung, Zeugnis, Erledigungsklausel.
- `kueschk-zeugnisanspruch-und-vergleich` — Zeugnisanspruch § 109 GewO und Vergleichsformulierungen.
- `kueschk-streitwert-kostenfolge-prozesskostenhilfe` — Streitwert § 42 GKG, § 12a ArbGG, Prozesskostenhilfe.
- `kueschk-berufung-und-revision-lag-bag` — Berufung beim LAG und Revision beim BAG.

**Entfristungsklage (entfristung-)**
- `entfristung-triage-was-will-user` — Einstieg: Befristungskontrollklage oder Entfristungsklage?
- `entfristung-laie-oder-anwalt-frage` — Statusabfrage Anwalt oder Laie fuer Entfristungsklage.
- `entfristung-schriftform-14-abs-4-erkennen` — KERNSKILL: Schriftformmangel nach § 14 Abs. 4 TzBfG als Unwirksamkeitsgrund.
- `entfristung-elektronische-signatur-vorsicht` — qES genuegt nicht fuer Befristungsabrede; Rechtsfolge Unbefristetheit.
- `entfristung-grundwarnung-drei-wochen-frist` — § 17 TzBfG absolute Ausschlussfrist drei Wochen.
- `entfristung-sachgrund-pruefen-14-abs-1` — Acht Sachgruende nach § 14 Abs. 1 TzBfG pruefen.
- `entfristung-sachgrundlos-14-abs-2-vorbeschaeftigung` — Sachgrundlose Befristung und Vorbeschaeftigungsverbot.
- `entfristung-sachgrundlos-14-abs-2a-neugruendung` — Neugründungsprivileg § 14 Abs. 2a TzBfG.
- `entfristung-sachgrundlos-14-abs-3-aelter-52` — Befristung aelterer Arbeitnehmer nach § 14 Abs. 3 TzBfG.
- `entfristung-rechtsfolge-16-tzbfg-unbefristet` — Rechtsfolge unwirksamer Befristung nach § 16 TzBfG.
- `entfristung-klageschrift-anwalt-baustein` — Anwaltliche Entfristungs-Klageschrift.
- `entfristung-klageschrift-laie-baustein` — Entfristungs-Klageschrift fuer Laien Schritt fuer Schritt.
- `entfristung-output-warnschriftsatz-laie` — Vollstaendige Laien-Entfristungs-Klageschrift mit Disclaimer.
- `entfristung-guetetermin-und-kammertermin-sprechzettel` — Sprechzettel fuer Guete- und Kammertermin in der Entfristungsklage.
- `entfristung-vergleichsverhandlung-checkliste` — Vergleichsbausteine in der Entfristungsklage.

**Aufhebungsvertrag und Abmahnung**
- `aufhebungsvertrag` — Entwurf, Pruefung und Verhandlung eines Aufhebungsvertrags.
- `aufhebungsvertrag-sperrzeit-prognose` — Sperrzeit-Risiko beim Aufhebungsvertrag nach § 159 SGB III.
- `abmahnung-arbeitsrecht` — Abmahnungsschreiben oder Gegendarstellung und Widerspruchsschreiben.

**Betriebsrat und kollektives Arbeitsrecht**
- `betriebsrat-anhoerung` — Betriebsratsanhoerung nach § 102 BetrVG: Inhalt, Fristen, Reaktion.
- `betriebsrat-beschluss-heilung-nachtraeglich` — Heilung unwirksamer Betriebsratsbeschluesse; BAG 25.09.2024.
- `betriebsrat-ladung-und-ersatzmitglieder-pruefen` — Ordnungsgemaesse Ladung und Nachrückreihenfolge pruefen.
- `massenentlassung-17-kschg` — Massenentlassungsanzeige und Konsultation Betriebsrat nach § 17 KSchG.

**Status, Expansion und Einstellungspruefung**
- `arbeitnehmer-status` — Statusfeststellung Arbeitnehmer vs. Selbstaendiger, § 611a BGB, Clearingverfahren.
- `einstellungspruefung` — Arbeitsvertrag, Befristung, AGG und Nachweisgesetz bei Neueinstellungen.
- `expansion-auftakt` — Planung einer Neueinstellung in neuem Bundesland oder Zielland.
- `expansion-aktualisierung` — Status eines laufenden Expansionsprojekts aktualisieren.
- `internationale-expansion` — Framework fuer internationale Einstellungen (AUeG-Modell/EOR/Gesellschaft).

**Lohn, Arbeitszeit und sonstige Themen**
- `lohn-arbeitszeit-fragen` — ArbZG, MiLoG, EFZG, Tarifvertraege: standortbezogene Lohn- und Arbeitszeitfragen.
- `mindestlohn-arbeitszeit-erfassung` — Mindestlohn und Pflicht zur Arbeitszeiterfassung (EuGH C-55/18, BAG 1 ABR 22/21).
- `lohnsteuer-sozialversicherung` — Sozialversicherungsrechtlicher Status und lohnsteuerliche Fragen.
- `fehlzeit-erfassen` — Neue Abwesenheit im Register anlegen: BUrlG, EFZG, MuSchG, BEEG.
- `fehlzeiten-register` — Offene Abwesenheiten und Fristen ueberpruefen.
- `agg-pruefung-bewerber-und-beschaeftigte` — AGG: Diskriminierungsmerkmale, Benachteiligungsverbot, Geltendmachungsfrist.
- `betriebsuebergang-613a-pruefen` — Betriebsuebergang: Identitaetswahrung, Widerspruchsrecht, Kuendigungsverbot.
- `hinschg-whistleblower-antwort` — HinSchG: interner Meldekanal, Repressalienverbot, Bussgelder.

**Handbuch, Richtlinien und Untersuchungen**
- `richtlinien-entwurf` — Betriebliche Richtlinie mit standortspezifischen Ergaenzungen entwerfen.
- `handbuch-aktualisierung` — Personalhandbuch auf Folgewirkungen und Mitbestimmungsrechte pruefen.
- `untersuchung-eroeffnen` — Neue interne Untersuchungssache eroeffnen und Protokoll anlegen.
- `untersuchung-ergaenzen` — Laufende Untersuchung mit neuen Daten und Dokumenten erganzen.
- `untersuchung-abfrage` — Fragen gegen das laufende Untersuchungsprotokoll stellen.
- `untersuchungs-memo` — Vertraulichen Untersuchungsvermerk entwerfen.
- `untersuchungs-zusammenfassung` — Zielgruppengerechte Zusammenfassung des Untersuchungsvermerks.
- `interne-untersuchung` — Referenz-Skill fuer das gesamte Untersuchungs-Framework (nicht direkt aufzurufen).

**Aktuelle BAG-Rechtsprechung 2025/2026**
- `bag-equal-pay-paarvergleich-8azr30024` — BAG 23.10.2025: Equal Pay durch Paarvergleich; ein maennlicher Kollege genuegt.
- `bag-freistellungsklausel-unwirksam-5azr10825` — BAG 25.03.2026: pauschale Freistellungsklausel nach Kuendigung unwirksam.
- `bag-mindesturlaub-kein-verzicht-9azr10424` — BAG 03.06.2025: kein Verzicht auf gesetzlichen Mindesturlaub.

## Worauf besonders achten

- **Drei-Wochen-Fristen sind absolute Ausschlussfristen**: § 4 KSchG und § 17 TzBfG dulden keine Versaeumnisse; nachtraegliche Klagezulassung nach § 5 KSchG nur bei unverschuldeter Fristversaeumung.
- **Schriftformzwang bei Kuendigung und Befristung**: § 623 BGB (Kuendigung/Aufhebungsvertrag) und § 14 Abs. 4 TzBfG (Befristungsabrede) verlangen Papier-Schriftform; qES genuegt fuer Befristungsabrede nicht.
- **Betriebsratsanhoerung vor der Kuendigung**: Eine inhaltlich unvollstaendige Anhoerung macht die Kuendigung unwirksam; BAG-Anforderungen an Mitteilung von Kuendigungsgrund und Sozialdaten.
- **Equal Pay Paarvergleich (BAG 23.10.2025)**: Ein einziger besser bezahlter maennlicher Kollege bei gleicher Arbeit begründet bereits die Vermutung des § 22 AGG; Median-Argumente sind nicht mehr ausreichend.
- **Sperrzeit-Risiko beim Aufhebungsvertrag**: Ohne ausdruecklichen wichtigen Grund im Sinne von § 159 SGB III droht eine 12-woechige Sperrzeit; Abfindungs-Faustformel (0.25 bis 0.5 Bruttogehalt pro Jahr) als Schutz.

## Typische Fehler

- Klagefrist § 4 KSchG als Drei-Wochen-Bitte missverstanden: Die Frist laeuft ab Zugang der Kuendigung, nicht ab Erhalt eines Briefes, und ist strikt.
- Betriebsratsanhoerung nach Ausspruch der Kuendigung nachgeholt: Die Anhoerung muss vor der Kuendigung abgeschlossen sein; nachtraegliche Heilung ist ausgeschlossen.
- Aufhebungsvertrag ohne Schriftformkontrolle: § 623 BGB verlangt Papier-Schriftform; muendlich oder per E-Mail geschlossene Aufhebungsvertraege sind nichtig.
- AGG-Fristen versaeumt: Entschaedigungsanspruch nach § 15 Abs. 4 AGG verfaellt in zwei Monaten ab Benachteiligung; Frist wird selten beachtet.
- Massenentlassungsanzeige nach der Kuendigung gestellt: EuGH Junk C-188/03 verlangt die Anzeige vor Ausspruch der Kuendigung; Verstoss macht alle Kuendigungen unwirksam.

## Querverweise

- `arbeitszeugnis-analyse` — Wenn im Rahmen von Kuendigungsschutz oder Aufhebungsvertrag auch ein Zeugnis vereinbart wird.
- `prozessrecht` — Fuer allgemeine prozessrechtliche Fragen, die sich im Arbeitsgerichtsprozess ergeben.
- `krisenfrueherkennung-starug` — Wenn Massenentlassungen im Kontext einer Unternehmensrestrukturierung stattfinden.
- `schriftform-und-textform-bgb` — Fuer Schriftform-Details bei Kuendigung, Befristungsabrede und Aufhebungsvertrag.

## Quellen und Aktualitaet

- Stand: 05/2026
- KSchG, TzBfG, BetrVG, BUrlG, EFZG, MuSchG, BEEG, SGB III, AGG, HinSchG in geltender Fassung
- BAG 23.10.2025 — 8 AZR 300/24 (Equal Pay Paarvergleich)
- BAG 25.03.2026 — 5 AZR 108/25 (Freistellungsklausel unwirksam)
- BAG 03.06.2025 — 9 AZR 104/24 (kein Verzicht auf Mindesturlaub)
- Mindestlohn: 12.82 EUR ab 01.01.2025; 13.90 EUR ab 01.01.2026

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
