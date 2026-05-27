---
name: allgemein
description: "Einstieg in die Legistik-Werkstatt fuer Bundes- und Landesministerien: Referentenentwuerfe, Kabinettsentwuerfe, Verordnungen, Satzungen, Synopsen, Folgenabschaetzung, Verfassungscheck und XML im HdR-Layout."
---

# Legistik-Werkstatt — Allgemein

## Worum geht es?

Die Legistik-Werkstatt ist ein Plugin fuer Referentinnen und Referenten in Bundes- und Landesministerien, fuer Verfassungsrechtlerinnen und Verfassungsrechtler sowie fuer Verbandsvertreter, die Gesetzesentwuerfe, Rechtsverordnungen und Satzungen erstellen, pruefen und in den parlamentarischen Prozess einbringen.

Das Plugin deckt alle Phasen des Gesetzgebungsverfahrens ab: von der Auftragsaufnahme ueber den Referentenentwurf, die Ressortabstimmung, Verbandeanhoerungen, die Kabinettsreife, Synopsen und Lesefassungen bis zur XML-Paralleldarstellung. Es enthaelt ausserdem Quercheckmodule fuer Verfassungsmaessigkeit, Europarechtskonformitaet, Erfuellungsaufwand und Goldplating-Vermeidung.

## Wann brauchen Sie diese Skill?

- Ein Referat im Bundesministerium erstellt einen Referentenentwurf und braucht eine strukturierte Auftragsaufnahme mit Regelungszielen.
- Eine Normenkontrollrats-Vorlage muss fristgerecht vorbereitet und mit einem KMU-Check versehen werden.
- Ein Ministerium will einen bestehenden Entwurf auf Verfassungsmaessigkeit und Europarechtskonformitaet pruefen.
- Eine Rechtsverordnung wird entworfen und die Verordnungsermaechtigung nach Art. 80 GG muss geprueft werden.
- Nach Inkrafttreten soll eine konsolidierte Lesefassung des geaenderten Stammgesetzes erstellt werden.

## Fachbegriffe (kurz erklaert)

- **HdR** — Handbuch der Rechtsfoermlichkeit; Leitfaden des Bundesjustizministeriums fuer die Formulierung von Rechtstexten.
- **GGO** — Gemeinsame Geschaeftsordnung der Bundesministerien; regelt Verfahren und Fristen fuer die Ressortabstimmung.
- **NKR** — Nationaler Normenkontrollrat; unabhaengiges Gremium, das Erfuellungsaufwand und buerokratische Belastungen prueft.
- **Goldplating** — Ueberimplementierung von EU-Richtlinien: nationale Zusatzanforderungen ueber das EU-Mindestmass hinaus.
- **Synopse** — Gegenueberststellung von bisherigem Recht, neuem Recht und Aenderungsbefehl in einer Dreispalten-Tabelle.
- **LegalDocML** — Maschinenlesbares XML-Format fuer deutsche Rechtstexte; Standard des Bundesjustizministeriums.
- **Normenkartierung** — Systematische Erfassung aller durch ein Vorhaben beruehrten Normen und ihrer Aenderungsbedarfe.
- **Kabinettsentwurf** — Abgestimmter Regierungsentwurf, der dem Kabinett zur Beschlussfassung vorgelegt wird.

## Rechtsgrundlagen

- Art. 70-74 GG (Gesetzgebungskompetenzen Bund und Laender)
- Art. 80 Abs. 1 GG (Verordnungsermaechtigung)
- Art. 76-78 GG (Gesetzgebungsverfahren im Bund)
- GGO (Gemeinsame Geschaeftsordnung der Bundesministerien)
- Art. 288 AEUV (Wirkung von EU-Verordnungen und Richtlinien)
- Art. 267 AEUV (Vorabentscheidungsverfahren EuGH)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Legistischen Auftrag aufnehmen und Regelungsziele klaeren (`legistik-auftragsaufnahme`).
2. Normhierarchie und Kompetenzgrundlage bestimmen (`normhierarchie-routing`, `gesetzgebungskompetenz-pruefen`).
3. Geeigneten Entwurfstyp auswaehlen: Referentenentwurf, Rechtsverordnung oder Satzung.
4. Quercheck-Module nutzen: Verfassungsmaessigkeit, Europarecht, Goldplating, Erfuellungsaufwand.
5. Ressortabstimmung und Verbandeanhoerung steuern, dann zur Kabinetts- oder Parlamentsreife fuehren.

## Skill-Tour (was gibt es hier?)

- `legistik-auftragsaufnahme` — Legistischen Auftrag strukturiert aufnehmen und in Regelungsziele umwandeln.
- `normhierarchie-routing` — Richtige Normbene bestimmen: Bundesgesetz, Landesgesetz, Rechtsverordnung oder Satzung.
- `gesetzgebungskompetenz-pruefen` — Gesetzgebungskompetenz nach Art. 70-74 GG pruefen bevor Entwurf aufgesetzt wird.
- `satzungskompetenz-pruefen` — Satzungskompetenz fuer Koerperschaften und Anstalten des oeffentlichen Rechts pruefen.
- `verordnungsermaechtigung-art80` — Verordnungsermaechtigung nach Art. 80 Abs. 1 GG pruefen bevor Rechtsverordnung entworfen wird.
- `referentenentwurf-bauen` — Vollstaendigen Referentenentwurf des Bundes oder Landes aufbauen.
- `gesetzesentwurf-kabinett` — Kabinettsentwurf nach Ressortabstimmung aus dem Referentenentwurf erstellen.
- `formulierungshilfe-bauen` — Formulierungshilfe aus der Mitte des Bundestages oder Landtages aufbauen.
- `begruendung-allgemein-und-besonders` — Zweiteilige Begruendung zu Gesetzesentwurf oder Verordnung (Allgemeiner Teil, Besonderer Teil) verfassen.
- `verfassungsmaessigkeit-quercheck` — Querschnittspruefung Verfassungsmaessigkeit eines Gesetzesentwurfs oder einer Verordnung.
- `europarechtskonformitaet` — Gesetzesentwurf oder Verordnung auf Vereinbarkeit mit EU-Recht pruefen.
- `goldplating-vermeiden` — Goldplating bei nationaler EU-Richtlinien-Umsetzung identifizieren und bewerten.
- `folgenabschaetzung-erfuellungsaufwand` — Erfuellungsaufwand fuer Buerger, Wirtschaft und Verwaltung ermitteln und darstellen.
- `folgenabschaetzung-nachhaltigkeit` — Weitere Folgen und Nachhaltigkeitspruefung fuer Gesetzesentwurf erstellen.
- `normenkontrollrat-kmu-check` — Vorlage an den NKR vorbereiten und KMU-Check durchfuehren.
- `normenkartierung` — Alle durch ein legistisches Vorhaben beruehrten Normen kartieren und Aenderungsmatrix aufbauen.
- `terminologie-konsistenz` — Terminologie-Konsistenz im legistischen Entwurf pruefen und Begriffstabelle aufbauen.
- `zirkelschluss-pruefen` — Zirkelschluesse und kreisfreie Verweisketten im legistischen Entwurf aufspueren.
- `inkrafttreten-uebergangsrecht` — Inkrafttretens- und Uebergangsregelungen fuer Gesetze und Verordnungen formulieren.
- `verbaendeanhoerung-ressortabstimmung` — Verbandeanhoerung und Ressortabstimmung nach GGO steuern und auswerten.
- `synopse-erstellen` — Synopse als Dreispalten-Tabelle (bisheriges Recht, neues Recht, Aenderungsbefehl) erstellen.
- `lesefassung-konsolidiert` — Konsolidierte Lesefassung des geaenderten Stammgesetzes nach Inkrafttreten erstellen.
- `xml-paralleldarstellung` — Maschinenlesbare Paralleldarstellung in LegalDocML.de oder eNorm-XML erstellen.
- `dokumente-rendern-docx-pdf` — Legistische Dokumente als DOCX oder PDF im offiziellen HdR-Layout rendern.
- `schulung-legistik` — Trainerleitfaden fuer Legistik-Schulungen mit der Schulungsakte erstellen.

## Worauf besonders achten

- Kompetenzgrundlage zuerst: Ohne geklarte Gesetzgebungskompetenz nach Art. 70 ff. GG darf kein Entwurf aufgesetzt werden.
- Goldplating ist politisch und juristisch heikel: Nationale Mehrbelastungen ueber EU-Mindestanforderungen hinaus muessen explizit begruendet werden.
- NKR-Fristen sind verbindlich: Vorlage muss mit vollstaendigen Erfuellungsaufwands-Angaben rechtzeitig erfolgen.
- Terminologie-Konsistenz ist elementar: Verschiedene Begriffe fuer dasselbe Konzept koennen zu Auslegungsstreitigkeiten fuehren.
- Uebergangsrecht nicht vergessen: Altfallregelungen und Bestandsschutz sichern Rechtsicherheit und vermeiden Verfassungsruegen.

## Typische Fehler

- Referentenentwurf ohne Verfassungsmaessigkeits-Check: Entwurf wird in der Ressortabstimmung oder im Parlament wegen Grundrechtsverletzung zurueckgewiesen.
- Verordnungsermaechtigung zu unbestimmt: Art. 80 Abs. 1 GG verlangt Inhalt, Zweck und Ausmass — Blankoermaechtigung ist nichtig.
- Goldplating unerkannt: Nationale Umsetzung geht ueber die Richtlinienpflichten hinaus, ohne dass dies im Entwurf kenntlich gemacht wird.
- Synopse fehlt: Ressortabstimmung und parlamentarische Beratung werden durch fehlende Gegenueberststellung ernsthaft erschwert.
- Inkrafttreten ohne Uebergangsrecht: Adressaten koennen sich nicht rechtzeitig auf neue Pflichten einstellen.

## Querverweise

- `datenschutzrecht` — DSGVO-Umsetzungsgesetze und datenschutzrechtliche Folgenabschaetzungen bei neuen Regelungsvorhaben.
- `regulatorisches-recht` — Nationale Umsetzung von Finanzmarkt-Richtlinien (KWG, ZAG, DORA) als legistisches Vorhaben.
- `energierecht` — Gesetzgebungsverfahren fuer EEG-Novellen, EnWG-Aenderungen und GEG-Fortentwicklung.

## Quellen und Aktualitaet

- Stand: 05/2026
- GG (Grundgesetz) in der zum Stand-Datum geltenden Fassung
- GGO (Gemeinsame Geschaeftsordnung der Bundesministerien) in der geltenden Fassung
- HdR (Handbuch der Rechtsfoermlichkeit) 3. Auflage des Bundesjustizministeriums

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
