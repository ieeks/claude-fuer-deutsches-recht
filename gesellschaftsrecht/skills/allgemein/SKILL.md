---
name: allgemein
description: "Einstieg und Orientierung für das Gesellschaftsrecht-Plugin: GmbH, AG und Personengesellschaften, M&A-Due-Diligence, Gesellschafterbeschluesse, Handelsregisteranmeldungen, Closing Checklists, Compliance-Fristen und Post-Merger-Integration."
---

# Gesellschaftsrecht — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Anwaelte und Wirtschaftsjuristen bei laufenden gesellschaftsrechtlichen Mandaten: GmbH- und AG-Governance, Personengesellschaften, M&A-Due-Diligence ohne Discovery, Gesellschafterbeschluesse, Handelsregisteranmeldungen, Closing-Checklisten und Compliance-Fristen. Es deckt sowohl die laufende Gesellschaftsverwaltung als auch transaktionsbezogene Mandate ab.

Das Plugin ist auf eine pruefende und beratende Kanzleipraxis ausgerichtet. Es enthaelt einen Kaltstart-Workflow fuer die Einrichtung des Praxisprofils sowie Mandats-Workspaces fuer Mehrfachmandatsbetrieb.

## Wann brauchen Sie diese Skill?

- Sie beraten eine GmbH bei Beschlussfassung, Geschaeftsfuehrer-Haftung oder Gesellschafterstreit.
- Sie begleiten eine M&A-Transaktion auf der Rechtspruefungsseite (Due Diligence, Q&A, Datenraum, Closing Checklist).
- Sie muessen Handelsregisteranmeldungen vorbereiten (Geschaeftsfuehrerwechsel, Prokura, Sitzverlegung, Kapitalmanahmen).
- Sie verwalten gesellschaftsrechtliche Compliance-Fristen (Jahresabschluss, Transparenzregister, Bilanzpublizitaet).
- Ein Gesellschafterstreit droht oder eine Patt-Situation ist eingetreten und Sie benoetigen eine Konfliktstrategie.

## Fachbegriffe (kurz erklaert)

- **Business Judgment Rule** — Haftungsprivileg fuer Geschaeftsfuehrer und Vorstande bei unternehmerischen Entscheidungen (analog § 93 Abs. 1 S. 2 AktG, § 43 GmbHG).
- **Drag-Along** — Mitnahmerecht: Mehrheitsgesellschafter kann Minderheitsgesellschafter zum Verkauf zwingen.
- **Tag-Along** — Mitveraeuserungsrecht: Minderheitsgesellschafter kann beim Verkauf mitziehen.
- **Closing Checklist** — Checkliste aller bis zum Vollzug einer Transaktion zu erfuellenden Bedingungen und Handlungen.
- **Umlaufbeschluss** — Gesellschafterbeschluss ohne Versammlung; bei GmbH nach § 48 Abs. 2 GmbHG zulaessig mit Zustimmung aller Gesellschafter.
- **Prokura** — Umfassende Handlungsvollmacht nach §§ 48 ff. HGB; bedarf der Handelsregistereintragung.
- **Change of Control** — Klausel in Vertraegen, die bei Wechsel der Gesellschafterstruktur besondere Rechte (z.B. Kuendigung) ausloest.

## Rechtsgrundlagen

- §§ 35-43 GmbHG — Geschaeftsfuehrung und Haftung
- §§ 46-49 GmbHG — Gesellschafterversammlung und Beschluesse
- §§ 93 ff. AktG — Vorstandshaftung, Business Judgment Rule
- §§ 107 ff. AktG — Aufsichtsrat (Protokoll, Beschluesse)
- §§ 241, 246 AktG — Nichtigkeits- und Anfechtungsklage (analog GmbH)
- §§ 12 ff. HGB — Handelsregister und Registeranmeldung
- §§ 48 ff. HGB — Prokura
- §§ 15 HGB — Wirkung der Handelsregistereintragung
- § 613a BGB — Betriebsuebergang bei Post-Merger-Integration
- §§ 18 ff. GwG — Transparenzregister

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Gesellschaftsform, Mandantenrolle (Gesellschafter, GF, Aufsichtsrat, Kaeufer, Investor), Sachgebiet.
2. Phase des Mandats bestimmen: Governance, Transaktion (DD, Closing), Streit oder Compliance.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: Insolvenzantragspflicht § 15a InsO, Anfechtungsklagefrist § 246 AktG analog (ein Monat), WEG-Klagefrist.
5. Anschluss-Skill bestimmen: nach Due-Diligence-Extraktion folgt Deal-Team-Briefing und Closing Checklist.

## Skill-Tour (was gibt es hier?)

**Konfiguration und Einstieg**

- `gesellschaftsrecht-kaltstart-interview` — Ersteinrichtung des Praxisprofils: Taetigkeitsbereiche, Wesentlichkeitsschwellen, Hausstil, Eskalationsmatrix.
- `gesellschaftsrecht-anpassen` — Praxisprofil aktualisieren: Risikoprofil, Module, Schwellenwerte, Workspace-Pfade.
- `gesellschaftsrecht-mandat-arbeitsbereich` — Mandats-Workspaces verwalten fuer Mehrfachmandatsbetrieb.
- `mandat-triage-gesellschaftsrecht` — Eingangs-Abfrage fuer gesellschaftsrechtliche Mandate mit Fristen-Ampel und Routing.

**Gesellschafterbeschluesse und Governance**

- `gesellschafterbeschluss` — Erstellung, Pruefung und Anfechtung von Gesellschafterbeschluessen in GmbH und AG.
- `schriftliche-beschlussfassung` — Umlaufbeschluesse im Hausstil mit Stimmverboten und Mehrheitserfordernissen.
- `aufsichtsrat-protokoll` — Protokolle von Vorstandssitzungen, Aufsichtsratssitzungen und GV im Hausformat.

**Haftung und Konflikt**

- `geschaeftsfuehrer-haftung-43-gmbhg` — Prueft persoenliche Haftung des GF nach § 43 GmbHG mit Business Judgment Rule und D&O-Versicherung.
- `gesellschafterstreit-loesungsstrategie` — Konflikt- und Mediationsstrategie bei Gesellschafterstreit, Patt-Situation und Einziehungsverfahren.

**Due Diligence und M&A**

- `dd-findings-extraktion` — Extraktion von DD-Issues aus Datenraum-Dokumenten nach Hauskategorien und Wesentlichkeitsschwellen.
- `dealteam-zusammenfassung` — Gestaffelte Deal-Briefings fuer GF, Deal-Lead und Arbeitsteam aus DD-Findings.
- `vollzugs-checkliste` — Vollzugscheckliste fuer M&A-Transaktionen: kritischer Pfad, CPs, Tage bis Closing.
- `wesentliche-vertraege-anlage` — Verzeichnis wesentlicher Vertraege (Material Contracts Schedule) aus DD-Erkenntnissen.
- `ki-werkzeug-uebergabe` — KI-Tool-Uebergabe fuer Massenvertragsprüfungen an Luminance oder Kira.
- `tabellenpruefung` — Tabellarisches Vertragsreview als Prompt-Matrix pro Dokument und Datenpunkt.

**Register und Compliance**

- `handelsregisteranmeldung` — Vorbereitung von HRB/HRA/GnR/PartGR-Anmeldungen mit Pflichtanmeldungen und Wirkung nach § 15 HGB.
- `gmbh-gruendung` — GmbH-Gruendung von der Satzung bis zur Handelsregistereintragung mit UG-Variante.
- `gesellschafts-compliance` — Compliance-Tracker fuer Einreichungsfristen, Bilanzpublizitaet und Transparenzregister.

**Post-Merger-Integration**

- `integrations-management` — PMI-Tracker: Phasenplan, Zustimmungsverfolgung, § 613a BGB und BetrVG-Mitbestimmung.

## Worauf besonders achten

- **Anfechtungsfrist beachten.** Die Analogie zu § 246 AktG fuer GmbH-Beschluesse setzt typischerweise eine einmonatige Klagefrist; nach laengerer Zeit droht Verwirkung.
- **Insolvenzantragspflicht parallel pruefen.** Sobald der GF Insolvenzanzeichen erkennt, laeuft die Antragspflicht nach § 15a InsO; sofort an `fortbestehensprognose`-Plugin verweisen.
- **Change-of-Control-Klauseln in DD.** Bei M&A-Due-Diligence muessen alle wesentlichen Vertraege auf Change-of-Control-Klauseln durchleuchtet werden; Closing kann sonst scheitern.
- **Umlaufbeschluss erfordert Einstimmigkeit.** Bei GmbH muss jeder Gesellschafter zustimmen (§ 48 Abs. 2 GmbHG); fehlende Stimmen machen Beschluss unwirksam.
- **Transparenzregister und Gesellschafterliste aktuell halten.** Jede Aenderung der Gesellschafterstruktur loest eine Meldepflicht aus (§ 20 GwG).

## Typische Fehler

- GF-Haftung wird nur nach § 43 GmbHG geprueft ohne § 15b InsO Zahlungsverbot bei Insolvenzreife.
- Protokolle von Gesellschafterversammlungen sind unvollstaendig; Abstimmungsergebnisse fehlen oder Stimmverbote werden nicht beachtet.
- Closing-Checklist wird zu spaet aufgebaut; Regulatory-Fristen wurden verpasst.
- Betriebsuebertragung nach § 613a BGB wird in Post-Merger-Integration nicht fristgemaess kommuniziert.
- DD-Findings werden nicht in die SPA-Garantien und Disclosure Schedules uebersetzt.

## Querverweise

- `mittelstand-corporate-ma` — Fuer vollstaendige M&A-Transaktionsbegleitung von DD bis PMI.
- `gesellschaftsgruender` — Fuer Gruendungsfragen vor der laufenden Gesellschaftsverwaltung.
- `insolvenzforderungsanmeldungspruefung` — Bei Insolvenz der Gesellschaft und Forderungsanmeldeverfahren.
- `fortbestehensprognose` — Wenn Insolvenzreife geprueft werden muss.
- `subsumtions-pruefer` — Fuer Einzelnorm-Analysen im gesellschaftsrechtlichen Kontext.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum (GmbHG, AktG, HGB, BGB, InsO, GwG, BetrVG)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
