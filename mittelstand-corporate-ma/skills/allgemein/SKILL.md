---
name: allgemein
description: "Einstieg und Orientierung für das Mittelstand-Corporate-MA-Plugin: Deal-Kommandocenter, Aktenanlage, Datenraum, Legal DD, SPA/APA, W&I, Public M&A, Umwandlung, StaRUG/Insolvenzplan, CP-Kalender, E-Rechnung und PMI im Mittelstandsmandat."
---

# Mittelstand Corporate M&A — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Anwaelte und Wirtschaftsjuristen bei der Abwicklung von Unternehmenstransaktionen im Mittelstand. Es deckt den gesamten Transaktionszyklus ab: von der ersten Aktenanlage und dem Datenraumaufbau ueber Legal Due Diligence, SPA/APA-Entwurf, Signing und Closing bis hin zur Post-Merger-Integration. Ergaenzend sind Querschnittsfunktionen integriert: Insolvenzreife-Pruefung, Liquiditaetsvorschau, E-Rechnung nach GoBD, Fristen- und CP-Kalender sowie KI-Governance im Transaktionsmandat.

Das Plugin ist freistehend konzipiert und benoetigt keine externen Datenbanken. Alle Skills koennen isoliert oder im Verbund genutzt werden. Zielgruppe sind Transaktionsanwaelte, Junior-Counsel und Kanzleien mit Mittelstandsfokus.

## Wann brauchen Sie diese Skill?

- Sie erhalten ein neues M&A-Mandat und muessen schnell Aktenstruktur, Datenraum und Teamrollen aufsetzen.
- Sie fuehren eine Legal Due Diligence durch und benoetigen strukturierte DD-Workflows, Red-Flag-Reports und Disclosure-Schedules.
- Sie verhandeln oder pruefen einen SPA/APA und brauchen Markup-Analyse, Key-Issues-Listen und Garantiekatalog-Unterstuetzung.
- Sie begleiten den Signing-to-Closing-Prozess und muessen CP-Tracking, Fristen und Closing-Bible-Aufbau organisieren.
- Das Zielunternehmen zeigt Insolvenzanzeichen und Sie muessen Insolvenzreife, Fortbestehensprognose oder StaRUG-Optionen parallel pruefen.

## Fachbegriffe (kurz erklaert)

- **Share Deal** — Kauf von Gesellschaftsanteilen; Kaeufer erwirbt die Gesellschaft mit allen Assets und Verbindlichkeiten.
- **Asset Deal** — Kauf einzelner Wirtschaftsgueter; Verbindlichkeiten bleiben grundsaetzlich beim Veraeusserer.
- **SPA/APA** — Share Purchase Agreement / Asset Purchase Agreement; der zentrale Transaktionsvertrag.
- **Conditions Precedent (CP)** — Vollzugsbedingungen, deren Erfuellung Closing ausloest (z.B. Fusionskontrollfreigabe).
- **W&I-Versicherung** — Warranty and Indemnity Insurance; Versicherung gegen Garantieverletzungen im SPA.
- **Closing Bible** — Archiv aller signierten Transaktionsdokumente nach Vollzug.
- **PMI** — Post-Merger-Integration; Massnahmenplanung nach Closing.
- **StaRUG** — Gesetz ueber den Stabilisierungs- und Restrukturierungsrahmen fuer Unternehmen; Restrukturierungsinstrument vor formeller Insolvenz.

## Rechtsgrundlagen

- §§ 433 ff. BGB — Kaufvertrag (Grundlage SPA/APA)
- § 15 GmbHG — Abtretung von GmbH-Anteilen
- § 179a AktG — Zustimmungspflicht der HV bei Asset Deal (AG)
- §§ 35-44 GWB — Fusionskontrolle national
- Art. 4 FKVO (VO 139/2004) — EU-Fusionskontrolle
- §§ 17-19 InsO — Insolvenzgruende (Zahlungsunfaehigkeit, drohende Zahlungsunfaehigkeit, Ueberschuldung)
- §§ 1-93 StaRUG — Restrukturierungsrahmen
- §§ 2 ff. UmwG — Umwandlungsrecht (Verschmelzung, Spaltung, Formwechsel)
- MAR VO 596/2014 — Marktmissbrauchsverordnung (bei Public M&A)
- GoBD, §§ 14 ff. UStG — E-Rechnung und Buchfuehrungspflichten

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Kaeufer oder Verkaeufer, Share oder Asset Deal, Transaktionsgroesse.
2. Phase des Mandats bestimmen: Erstaufnahme, DD, Vertragsverhandlung, Signing/Closing, PMI oder Krisenbegleitung.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: Insolvenzantragspflicht § 15a InsO, Anmeldefristen Fusionskontrolle, MAR-Ad-hoc-Pflichten.
5. Anschluss-Skill bestimmen: nach DD-Report folgt typischerweise Disclosure-Schedules oder SPA-Entwurf.

## Skill-Tour (was gibt es hier?)

**Deal-Organisation und Einstieg**

- `mittelstand-corporate-ma-kommandocenter` — Schnellstart fuer Corporate/M&A-Mandate; erkennt Deal-Typ und erzeugt Deal-Karte, Ampel und naechste Aktion.
- `mittelstand-corporate-ma-kaltstart` — Nimmt Kanzlei- und Mandantenpraeferenzen fuer Dealtypen, Playbooks und KI-Governance auf.
- `mittelstand-corporate-ma-deal-intake` — Strukturiert neue Transaktionsmandate aus E-Mail, Teaser, NDA, Term Sheet oder Datenraum-Einladung.
- `mittelstand-corporate-ma-deal-team-staffing` — Plant Workstreams, Rollen, Kapazitaeten und Review-Level im Transaktionsteam.
- `mittelstand-ma-aktenanlage` — Eroeffnet neue Deal-Akte mit Aktenzeichen, Ordnerstruktur und Vertraulichkeitsstufen.
- `mittelstand-corporate-ma-matter-file` — Legt Transaktionsakte als Mandat-Workspace mit Workstreams und Datenraumspiegel an.

**Vorbereitung und Screening**

- `mittelstand-corporate-ma-outside-in-target-screening` — Erstellt fruehe Zielobjekt- und Pipeline-Analysen aus oeffentlichen Informationen und Registern.
- `mittelstand-corporate-ma-conflict-gwg-sanctions` — Konflikt-, GwG- und Sanktionscheck bei Mandatsannahme.
- `mittelstand-corporate-ma-handelsregisterabruf` — Offizieller Registerabruf fuer Zielgesellschaft, Kaeufer und Beteiligungsketten.
- `mittelstand-corporate-ma-gesellschaftsrecht-register` — Corporate Housekeeping; prueft HRB/HRA, Gesellschafterlisten, Satzungen und Organkompetenz.

**Datenraum**

- `mittelstand-corporate-ma-datenraum-aufbau` — Strukturiert und bestueckt virtuelle Datenraeume fuer M&A-Prozesse.
- `mittelstand-corporate-ma-datenraum-gap-clean-room` — Prueft Datenraum, Teaser und Information Memorandum auf Luecken, Widersprueche und Clean-Room-Bedarf.
- `mittelstand-corporate-ma-qa-information-requests` — Verwaltet Q&A-Prozess im Datenraum mit Information Request Lists und Follow-ups.
- `mittelstand-corporate-ma-tabellenreview-3d-datenraum` — Verbindet Datenraumprüfung mit interner Review-Matrix aus Rechts-, Steuer- und Wirtschaftsperspektive.

**Due Diligence**

- `mittelstand-corporate-ma-due-diligence-legal` — Standardisierte Legal DD mit Findings, Materiality, Quellenbelegen und Red-Flag-Report.
- `mittelstand-corporate-ma-due-diligence-commercial-contracts` — Prueft Kunden-, Lieferanten-, SaaS- und Lizenzvertraege auf Change of Control und Kuendigungsrisiken.
- `mittelstand-corporate-ma-due-diligence-reporting` — Erstellt Red-Flag-Report, Full DD Report, Legal Fact Book und Executive Summary.
- `mittelstand-corporate-ma-expert-calls-transkripte` — Wertet Management Presentations und Expert Calls fuer DD und SPA-Vorbereitung aus.
- `mittelstand-corporate-ma-datenqualitaet-xai-qualitaetskontrolle` — Sichert KI-gestuetzte M&A-Arbeit gegen Halluzination, Bias und Datenqualitaetsprobleme ab.

**Transaktionsstruktur und Vertragswerk**

- `mittelstand-corporate-ma-transaktionsstruktur` — Entwickelt Strukturvarianten fuer Share Deal, Asset Deal, Carve-out, Joint Venture und Roll-over.
- `mittelstand-corporate-ma-spa-apa-entwurf` — Kaufvertragsentwuerfe fuer Share Deal und Asset Deal aus Term Sheet, DD-Findings und Transaktionsstruktur.
- `mittelstand-corporate-ma-disclosure-schedules` — Ableitung von Disclosure Schedules aus Datenraum, DD-Findings und SPA-Garantien.
- `mittelstand-corporate-ma-vertragsmarkup-key-issues` — Analysiert SPA/APA/NDA-Markups und erstellt Key-Issues-Lists und Gegenmarkup-Vorschlaege.
- `mittelstand-corporate-ma-fair-disclosure-knowledge` — Prueft Wissens- und Fair-Disclosure-Klauseln im Lichte KI-gestuetzter Datenraumprüfung.
- `mittelstand-corporate-ma-wi-insurance` — W&I-Prozess, Underwriting, Deckungsausschluesse und Disclosure Letter fuer M&A.

**Signing und Closing**

- `mittelstand-corporate-ma-signing-closing-conditions` — Signing-to-Closing-Prozess mit CPs, Ordinary Course, Bring-down und Funds Flow.
- `mittelstand-corporate-ma-steps-plan-pmo` — Extrahiert aus Vertraegen und Gremienunterlagen konkrete Steps Plans fuer Pre-Signing bis Post-Closing.
- `mittelstand-ma-fristen-cp-kalender` — Fristen- und CP-Kalender fuer Signing, Closing, Q&A, Regulatory und Board Meetings.
- `mittelstand-corporate-ma-closing-bible-archiv` — Erstellt Closing Bible mit Versionierung, Signaturketten und Registerbelegen.
- `mittelstand-corporate-ma-output-versand-signing` — Bereitet Transaktionsoutput, Signing Packs und Closing Deliverables fuer Versand vor.

**Spezialthemen**

- `mittelstand-corporate-ma-umwandlungsrecht` — Verschmelzung, Spaltung, Ausgliederung und Formwechsel nach UmwG.
- `mittelstand-corporate-ma-umwandlungssteuerrecht` — UmwStG-Strukturfragen, Buchwertantrag, § 8c KStG Verlustuntergang, Einbringung §§ 20-24 UmwStG.
- `mittelstand-corporate-ma-regulatory-fdi-merger-control` — Fusionskontrolle (GWB/FKVO) und AWV-Investitionspruefung mit Multi-Jurisdiction-Filings.
- `mittelstand-corporate-ma-public-ma-kapitalmarkt-mar` — Boersennotierte Transaktionen: WpUEG, Ad-hoc-Pruefung, Insiderlisten und MAR-Compliance.
- `mittelstand-corporate-ma-kg-personengesellschaften` — KG, GmbH und Co. KG, MoPeG, Fondsvehikel und Kommanditistenwechsel.
- `mittelstand-corporate-ma-distressed-ma` — Unternehmenskauf in Krise, StaRUG, Insolvenzplan oder Asset Deal aus der Insolvenz.
- `mittelstand-corporate-ma-restructuring-starug-insolvenzplan` — StaRUG-Restrukturierungsplan, Insolvenzplan und Glaeubigerklassen-Matrix.

**Krisenbegleitung (integriert)**

- `mittelstand-ma-insolvenzreife` — Prueft Zahlungsunfaehigkeit, drohende Zahlungsunfaehigkeit und Ueberschuldung mit Antragspflicht-Timing.
- `mittelstand-ma-liquiditaetsvorschau` — 3-Wochen-Liquiditaet und 13-Wochen-Cash-Bridge mit Warnsignal-Ampel.

**Post-Merger-Integration**

- `mittelstand-corporate-ma-post-closing-integration` — DD-Findings und SPA-Pflichten in PMI-Plan; Earn-Out-Monitoring und Betriebsuebergang § 613a BGB.

**Kanzlei-Infrastruktur**

- `mittelstand-corporate-ma-teaser-im-processdocs` — Unterstuetzt Seller-side bei Teaser, Information Memorandum, NDA und Process Letter.
- `mittelstand-corporate-ma-simulation-bidder-process` — Simuliert einen beschleunigten M&A-Tag mit Datenraum, Q&A, Markup und Board Call.
- `mittelstand-corporate-ma-translations-multijurisdictional` — Koordiniert lokale Kanzleien, Uebersetzungen und Multi-Jurisdiction-Matrizen.
- `mittelstand-corporate-ma-billing-narratives` — Erstellt praezise Time Narratives, Phasenbudgets und Workstream-Rechnungen fuer M&A-Mandate.
- `mittelstand-ma-erechnung-gobd` — GoBD-konforme E-Rechnung (XRechnung/ZUGFeRD) fuer M&A-Mandate.
- `mittelstand-ma-tabellenreview` — Review-Matrix aus Rechts-, Steuer- und Wirtschaftsperspektive fuer Dokumente und Tabellen.
- `mittelstand-ma-schreibcanvas` — Substanzorientierter Feedback-Begleiter fuer SPA, Board Paper, DD-Report und Registertext.
- `mittelstand-corporate-ma-rechtsprechungsrecherche` — Recherchiert Rechtsprechung und amtliche Quellen fuer Corporate/M&A und Kapitalmarkt.
- `mittelstand-corporate-ma-ki-governance-berufsrecht` — Prueft KI-Einsatz im Transaktionsmandat unter Mandatsgeheimnis, Datenschutz und KI-VO.
- `mittelstand-corporate-ma-automation-monitoring` — Trackt Datenraum-Neuzugaenge, Fristen, Q&A, MAR-Signale und PMI-Aufgaben automatisiert.
- `mittelstand-corporate-ma-board-paper-business-judgment` — Erstellt Board Paper und Business-Judgment-Dokumentation fuer M&A-Beschluesse.
- `mittelstand-corporate-ma-freundlicher-copilot` — Unterstuetzender Begleiter fuer Berufseinsteiger und Junior-Counsel durch grosse Transaktionen.
- `mittelstand-corporate-ma-look-and-feel` — Definiert visuelles Erscheinungsbild des Deal-Copiloten (Style-Guide, Farben, Layout).

## Worauf besonders achten

- **Insolvenzantragspflicht parallel pruefen.** Sobald das Zielunternehmen Liquiditaetsengpaesse oder negatives EK zeigt, greift § 15a InsO mit kurzen Fristen (drei bzw. sechs Wochen). Immer Skills `mittelstand-ma-insolvenzreife` und `mittelstand-ma-liquiditaetsvorschau` einschalten.
- **Fusionskontrolle und FDI fruehzeitig pruefen.** Anmeldeschwellen koennen Closing blockieren; AWV-Fristen sind zwingend. Skill `mittelstand-corporate-ma-regulatory-fdi-merger-control` schon bei Signing-Planung verwenden.
- **Disclosure Schedules sind verhandlungsrelevant.** Zu knappe oder widersprüchliche Angaben eroeffnen Garantieansprueche. Abgleich zwischen DD-Findings und Schedules ist Pflicht.
- **GoBD und XRechnung gelten auch im M&A-Mandat.** Honorarabrechnungen muessen revisionssicher gespeichert werden; Skill `mittelstand-ma-erechnung-gobd` nicht uebersehen.
- **KI-Einsatz im Transaktionsmandat erfordert Mandantenfreigabe.** Skill `mittelstand-corporate-ma-ki-governance-berufsrecht` vor Einsatz automatisierter DD-Tools aktivieren.

## Typische Fehler

- CP-Kalender wird erst spaet aufgebaut und Regulatory-Fristen werden verpasst; Skill `mittelstand-ma-fristen-cp-kalender` direkt nach Signing-Entwurf aktivieren.
- Disclosure Schedules werden aus dem SPA-Entwurf abgeleitet, statt aus dem Datenraum; Skill `mittelstand-corporate-ma-disclosure-schedules` separat durchlaufen.
- Insolvenzreife des Zielunternehmens wird erst in der DD erkannt, nicht schon beim Deal-Intake; Skill `mittelstand-ma-insolvenzreife` im Intake-Screening nutzen.
- Closing Bible wird fragmentarisch aufgebaut; Skill `mittelstand-corporate-ma-closing-bible-archiv` fruehzeitig und nicht erst post-Closing anlegen.
- Berufsrechtliche KI-Grenzen werden nicht dokumentiert; fehlende Mandantenfreigabe kann Haftungsrisiken ausloesen.

## Querverweise

- `fortbestehensprognose` — Bei Zielunternehmen in Krise: Fortbestehensprognose nach § 19 Abs. 2 InsO parallel erstellen.
- `gesellschaftsrecht` — Fuer isolierte Gesellschaftsrecht-Fragen zu GmbH/AG und Personengesellschaften ausserhalb M&A.
- `insolvenzforderungsanmeldungspruefung` — Wenn Distressed-M&A-Transaktion aus Insolvenzverfahren heraus stattfindet.
- `common-law-kompass` — Bei UK- oder US-Gegenparteien und bilingualen Transaktionsvertraegen.
- `ki-governance` — Fuer unternehmensseitige KI-Governance-Fragen des Mandanten unabhaengig vom Transaktionsmandat.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum (BGB, GmbHG, AktG, UmwG, InsO, StaRUG, GWB, FKVO, MAR, WpUEG, GoBD, UStG)
- IDW S 11 (Fortbestehensprognose), IDW S 6 (Sanierungskonzept) in geltender Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
