---
name: allgemein
description: "Einstieg und Überblick für das fusionierte Kanzlei-Allgemein-Plugin (mit Cowork): Kommandocenter, Mandatsannahme, GwG, Klage, Replik, Vertrag, Rechtsprechung, Handelsregister, beA-Journal, Rechnung, UStVA, Fristenbuch, Timesheet, RVG, Versand-Vor-Check, Posteingang, Mandantenakte, Mahnwesen, Tagesbrief, Geburtstage, Weihnachtskarten."
---

# Kanzlei Allgemein — Allgemein

## Worum geht es?

Das Kanzlei-Allgemein-Plugin (fusioniert mit Cowork) ist das zentrale Workflow-Plugin fuer den gesamten Kanzleibetrieb. Es vereint alle wesentlichen Tagesoperationen einer Anwaltskanzlei: von der Mandatsannahme mit GwG-Pruefung ueber die Erstellung von Klagen, Repliken und Vertraegen bis zur Zeiterfassung, Rechnungsstellung, Buchhaltung und UStVA-Vorbereitung. Hinzu kommen beA-Versand, Postlauf, Fristenbuch, HR und Sekretariatsfunktionen.

Das Plugin folgt einem nachtblauen Kanzleidesign mit silberner Grundstruktur und orangenem Akzent (Cowork-Designsprache) und gibt alle Outputs als Markdown-Dashboards mit Freigabeampeln und Statuskarten aus. Es richtet sich an Einzelanwaelte, Sozietaeten und anwaltliche GmbHs jeder Groesse.

## Wann brauchen Sie diese Skill?

- Sie erhalten eine neue Mandatsanfrage und wollen Intake, GwG-Pruefung, Konfliktcheck und Aktenanlage in einem strukturierten Ablauf durchfuehren.
- Eine Frist laeuft ab und Sie benoetigen schnellen Zugriff auf Fristenbuch, beA-Versand und Schriftsatzerstellung.
- Der Monat endet und Sie wollen Zeiterfassung, Rechnungserstellung, UStVA-Vorbereitung und DATEV-Uebergabe koordinieren.
- Ein Mitarbeiter ist abwesend und Sie muessen Vertretungsregelungen fuer Postlauf, Fristen und beA sicherstellen.
- Sie moechten Kanzlei-Routinen automatisieren oder im Simulationsmodus testen.

## Fachbegriffe (kurz erklaert)

- **beA** — Besonderes elektronisches Anwaltspostfach; Pflichtkanal fuer elektronischen Schriftverkehr mit Gerichten nach § 31a BRAO.
- **GwG** — Geldwaeschegesetz; verpflichtet Kanzleien bei Kataloggeschaeften zur Identifizierung von Mandanten und wirtschaftlich Berechtigten.
- **EB** — Empfangsbekenntnis; Bestaetigung des Empfangs nach § 174 ZPO bei sicherem Uebermittlungsweg.
- **sUW** — Sicherer Uebermittlungsweg im Sinne des § 130a ZPO; beA-Versand zaehlt nur als sUW, wenn der Inhaber selbst versendet.
- **XRechnung / ZUGFeRD** — Elektronische Rechnungsformate nach EN 16931; bei oeffentlichen Auftraggebern Pflicht.
- **RVG** — Rechtsanwaltsvergaetungsgesetz; regelt gesetzliche Gebuehren nach Streitwert und Gebuehrentatbestaenden.
- **DATEV** — Buchhaltungssoftware-System; Plugin bereitet DATEV-Uebergabepakete fuer Steuerberater vor.
- **GoBD** — Grundsaetze zur ordnungsmaessigen Buchfuehrung; gelten fuer die gesamte digitale Aktenfuehrung der Kanzlei.

## Rechtsgrundlagen

- § 43a BRAO — Allgemeine Berufspflichten (Sorgfalt, Verschwiegenheit)
- § 50 BRAO — Aktenaufbewahrungspflicht (sechs Jahre nach Mandatsende)
- § 31a BRAO — Besonderes elektronisches Anwaltspostfach
- §§ 130a 130d ZPO — Elektronische Schriftsaetze und sicherer Uebermittlungsweg
- §§ 2 10 11 GwG — Anwendungsbereich, Identifizierungspflicht, wirtschaftlich Berechtigte
- § 10 RVG — Pflichtangaben der Rechtsanwaltsrechnung
- §§ 14 18 21 UStG — Rechnungsanforderungen und UStVA-Pflicht
- GoBD — Grundsaetze ordnungsmaessiger Buchfuehrung
- Art. 5 Art. 13 Art. 28 Art. 35 DSGVO — Datenschutz in der Kanzlei
- § 7 BUrlG, § 3 PflegeZG, §§ 16 ff. BEEG — Abwesenheitsregelungen

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Kaltstart-Interview: Kanzleiprofil, Aktenzeichen-Konvention, Eingangskanale und Integrationen einrichten.
2. Kommandocenter: Tages-Routing aus einem Satz; Workflow automatisch bestimmen.
3. Mandatsannahme und GwG-Pruefung bei neuem Mandat durchfuehren.
4. Tagesoperationen: Postlauf, beA-Journal, Fristencheck, Schriftsatzerstellung, Zeiterfassung.
5. Monatliche Abschlussarbeiten: Rechnung, UStVA-Vorbereitung, Payroll, DATEV-Uebergabe.

## Skill-Tour (was gibt es hier?)

**Aktenmanagement und Mandatsannahme**
- `aktenbestand-pflege` — Laufende Pflege des Aktenbestands: Aktenstatus, Mandatsende, Archivierung und DSGVO-Speicherbegrenzung.
- `kanzlei-allgemein-akte` — Anlage oder Zuordnung einer Akte bei neuer Mandatsanfrage oder eingehendem Schriftstueck.
- `kanzlei-allgemein-aktenzeichen` — Erkennung, Normalisierung und Verknuepfung von Aktenzeichen.
- `kanzlei-allgemein-intake` — Strukturiertes Einlesen von Eingaengen aus Brief, Fax, beA, E-Mail, Telefon und Upload.
- `kanzlei-allgemein-mandatsannahme-gwg` — Mandatsannahme und GwG-Pruefung: Intake, Aktenanlage, Konfliktcheck, Identifizierung, PEP, BRAK-Dokumentation.
- `kanzlei-allgemein-mandatsvereinbarung` — Mandatsvereinbarung, Vollmacht, Datenschutzhinweis, Honorarvereinbarung und Vorschuss erstellen.
- `mandantenakte-anlegen` — Mandantenakte nach Kanzleikonvention anlegen: Stammdaten, Konfliktcheck, GwG, Honorar.
- `kanzlei-allgemein-kaltstart` — Kaltstart des Plugins: Kanzleiprofil und Stammprofil einrichten.
- `kanzlei-cowork-kaltstart-interview` — Erweitertes Kaltstart-Interview mit Kanzleiprofil-Datei fuer Cowork-Konfiguration.

**Kommandocenter und Navigation**
- `kanzlei-allgemein-kommandocenter` — Schnellstart: erkennt Workflow aus einem Satz und routet zu Mandatsannahme, Klage, Rechnung, HR und mehr.
- `kanzlei-allgemein-freundlicher-copilot` — Fuehrt junge Anwaelte freundlich durch alle Kanzlei-Workflows mit Nachhilfemodus.
- `kanzlei-allgemein-look-and-feel` — Gestaltet Ausgaben hochwertig im nachtblauen Cowork-Design mit Freigabeampeln.

**Schriftsatz, Vertrag und Schreiben**
- `kanzlei-allgemein-schriftsatz-turbo` — Schnellerstellung von Klage, Replik, Antrag und Klageerwiderung mit Anlagenlogik.
- `kanzlei-allgemein-schreibcanvas` — Freies Canvas fuer Schriftsaetze, Briefe und Mandantenkommunikation mit Substanzcheck.
- `kanzlei-allgemein-vertragsentwurf` — Vertragsentwuerfe aus Term Sheet, Stichpunkten oder Vorlagen erstellen.
- `mandantenbrief-vorlagen` — Standardvorlagen fuer Mandantenbriefe: Mandat, Zwischenbericht, Abschluss, Schlussrechnung.
- `umgang-mit-ki-vorwurf-bei-sachverstaendigengutachten` — Anwaltliche Strategie bei Vorwurf des KI-Einsatzes in gerichtlichen Sachverstaendigengutachten.

**Rechtsprechung und Handelsregister**
- `kanzlei-allgemein-rechtsprechungsrecherche` — Rechtsprechungsrecherche in amtlichen Datenbanken und OpenJur mit Zitier- und Quellenprotokoll.
- `kanzlei-allgemein-handelsregisterabruf` — Handelsregisterabruf fuer GmbH-Vertretung, Gesellschafterstruktur und GwG-Dokumentation.

**beA, Versand und Postlauf**
- `bea-versand-pruefen` — beA-Versand pruefen: sicherer Uebermittlungsweg, qeS, Versandquittung, Wiedereinsetzung.
- `kanzlei-allgemein-bea-journal` — beA-Verbindungen, Nachrichten und EB-Workflow dokumentieren.
- `kanzlei-allgemein-output-versand` — Output und Versand steuern: Schriftsatz, Brief, E-Mail, Fax, beA, Messenger.
- `kanzlei-allgemein-postlauf` — Taeglich um 11 Uhr: neue Eingaenge, beA-Journal, Fristen, Action-Items, Versandbedarf.
- `posteingang-ausgang` — Postein- und Postausgangsbuch mit Audit-Trail und Aktenverknuepfung fuehren.
- `versand-vor-check` — Pflicht-Pre-Check vor jedem Versand: Dokumentidentitaet, Unterschrift, Adressat, Anlagen, Versandweg.

**Fristen und Kalender**
- `fristenbuch-fuehren` — Zentrales Fristenbuch: Haupt- und Vorfristen, PostModG-Fiktionen, Eskalation.
- `kanzlei-allgemein-fristen-monitor` — Akteninhalt auf Fristen, Action-Items und Wiedervorlagen scannen.
- `kanzlei-allgemein-kanzleikalender` — Kanzleikalender fuer Termine, Fristen, HR, Jour fixe und UStVA-Faelligkeiten.
- `sekretariats-tagesbrief` — Tagesbrief: Fristen, Vorfristen, Post, Rueckrufe, Termine, Geburtstage, Honorarrueckstaende.

**Zeiterfassung und Rechnung**
- `kanzlei-allgemein-zeitnarrative` — Zeiterfassung mit abrechenbaren Narrativen im 6-Minuten-Takt.
- `timesheet-aktenzeitung` — Zeiterfassung pro Mandat mit Reports nach Mandat, Anwalt und Zeitraum.
- `kanzlei-allgemein-rechnung` — Kanzleirechnungen, Vorschussrechnungen und Stundenhonorare vorbereiten.
- `rechnungserstellung-rvg` — Honorarrechnungen nach RVG oder Honorarvereinbarung mit Pflichtangaben nach § 10 RVG erstellen.
- `kanzlei-allgemein-erechnung` — XRechnung oder ZUGFeRD vorbereiten und validieren.
- `mahnwesen-honorar` — Mahnwesen fuer eigene Honorarforderungen: gestufte Mahnschreiben, Klageentwurf.

**Buchhaltung und UStVA**
- `kanzlei-allgemein-buchhaltung-konten` — Kanzlei-Buchhaltung: Geschaeftskonto, offene Posten, Debitoren, Bankmatching, DATEV-Export.
- `kanzlei-allgemein-ustva-buchhaltung` — UStVA-Unterlagen fuer ELSTER oder Steuerkanzlei zusammenstellen.
- `kanzlei-allgemein-ustva-simulation` — UStVA-Simulation bei ELSTER-Stoerung oder fehlendem Fachsystem-Zugang.

**HR und Abwesenheiten**
- `kanzlei-allgemein-hr-personal` — Kanzlei-Personal: Stammdaten, Arbeitsvertraege, Onboarding, Offboarding.
- `kanzlei-allgemein-lohn-sv` — Lohnabrechnung, Sozialversicherungsmeldungen und Payroll-Uebergabe vorbereiten.
- `kanzlei-allgemein-abwesenheiten-urlaub` — Abwesenheiten verwalten: Urlaub, Krankheit, Elternzeit, Vertretungsregelungen.

**Qualitaetssicherung und Automationen**
- `kanzlei-allgemein-qualitaetsgate-hardening` — Mehrstufige Qualitaetsgates vor Versand: Substanz, Fristen, Zustaendigkeit, Antraege.
- `kanzlei-allgemein-automationen` — Wiederkehrende Kanzlei-Routinen als datenschutzkonforme Automationen planen.
- `kanzlei-allgemein-integrationen-simulation` — Kanzlei-Integrationen pruefen und Workflows im Simulationsmodus testen.
- `kanzlei-allgemein-kanzleitag-simulation` — Achtstuendigen Kanzleitag fuer Training und Demo simulieren.

**Mandantenpflege und Sonstiges**
- `geburtstage-feiertage` — Mandanten-Geburtstagsverteiler und Glueckwunsch-E-Mail-Vorlagen pflegen.
- `weihnachtskarten` — Weihnachtskartenversand: Verteiler, Texte, Druckliste, Datenschutz.

## Worauf besonders achten

- **beA sicherer Uebermittlungsweg**: Nur der persoenliche Versand durch den beA-Inhaber zaehlt als sUW; Versand durch Mitarbeitende erfordert qeS.
- **PostModG seit 1.1.2025**: Die Zustellungsfiktion bei Brief betraegt jetzt vier Werktage (vorher drei); alle Fristberechnungen anpassen.
- **GwG-Kataloggeschaefte nicht uebersehen**: Truhand, Immobilientransaktionen und Gesellschaftsgruendungen loesen GwG-Pflichten aus, auch wenn kein Gerichtsverfahren anhangig ist.
- **DSGVO-Speicherbegrenzung bei Aktenarchivierung**: Nach Ablauf der sechs-jaehrigen Aufbewahrungsfrist (§ 50 BRAO) muessen Akten geloescht werden.
- **Qualitaetsgate vor beA-Versand immer aktivieren**: Ein einmal versandtes beA-Dokument kann nicht zurueckgezogen werden.

## Typische Fehler

- Fristbeginn bei gerichtlicher Post falsch berechnet; PostModG-Fiktion (vier Tage seit 2025) wird nicht beruecksichtigt.
- GwG-Identifizierung bei Mandatsannahme vergessen; Bussgeldrisiko bei Kataloggeschaeft.
- Rechnung ohne Aktenzeichen und Tatigkeitsbeschreibung versandt; verstosst gegen § 10 RVG.
- beA-Versand ohne Empfangsbekenntnis bei Fristen; Fristnachweis fehlt.
- Zeiterfassung tagesverspaetet nachgetragen; GoBD-Zeitstempel-Anforderung nicht erfuellt.

## Querverweise

- `berufsrecht-ki-vertragspruefung` — Berufsrechtliche Pruefung von KI-Diensten, die in Kanzlei-Workflows eingesetzt werden.
- `ki-richtlinie-kanzleien` — KI-Nutzungsrichtlinie als Rahmen fuer den KI-Einsatz im Kanzleibetrieb.
- `kanzlei-builder-hub` — Installation und Verwaltung weiterer Skills.
- `insolvenzverwaltung` — Wenn Mandate in ein Insolvenzverfahren muenden.
- `selbstvertreter-amtsgericht` — Wenn Mandanten ohne Anwalt vor dem Amtsgericht auftreten wollen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum
- PostModG: Zustellungsfiktion vier Werktage seit 01.01.2025
- § 23 Nr. 1 GVG: AG-Wertgrenze 10.000 EUR seit 01.01.2026

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
