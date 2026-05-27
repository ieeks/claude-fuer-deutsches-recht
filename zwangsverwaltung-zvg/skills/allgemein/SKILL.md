---
name: allgemein
description: "Einstieg und Ueberblick fuer das ZVG-Plugin: Zwangsverwaltung und Versteigerung von Immobilien — Beschlagnahme, Besitzerlangung, Miet- und Pachtverwaltung, Treuhandkonto, Rechnungslegung, Verteilungsplan, Insolvenzschnittstelle, ZVG-Portal-Recherche, Bieterangebote und Versteigerungsteilnahme."
---

# Zwangsverwaltung ZVG — Allgemein

## Worum geht es?

Das Plugin unterstuetzt Zwangsverwalter und Zwangsversteigerungsbeteiligte bei der rechtssicheren Durchfuehrung von Zwangsverwaltungen und Zwangsversteigerungen nach dem Gesetz ueber die Zwangsversteigerung und die Zwangsverwaltung (ZVG). Es deckt den vollstaendigen Lebenszyklus ab: von der Pruefung des Bestellungsbeschlusses und der Besitzerlangung ueber die laufende Mietverwaltung, Konten- und Kassenfuehrung sowie Berichterstattung bis zur Jahresrechnung, dem Verteilungsplan und der Schnittstelle zur Zwangsversteigerung.

Zielgruppe sind Rechtsanwaelte und Verwalter, die als Zwangsverwalter bestellt sind, sowie Glaeubiger und Investoren, die an Zwangsversteigerungsterminen teilnehmen wollen.

## Wann brauchen Sie diese Skill?

- Sie wurden als Zwangsverwalter bestellt und muessen das Objekt vollstaendig erfassen und das Verfahrenscockpit aufbauen.
- Mieter zahlen nicht und Sie muessen Rueckstaende einziehen, mahnen oder Klagen einleiten.
- Die Rechnungslegungsperiode endet und die Jahres- oder Schlussrechnung muss gerichtsfaehig erstellt werden.
- Der Schuldner wird insolvent und Sie muessen die Koordination mit dem Insolvenzverwalter sicherstellen.
- Ein Mandant will an einem Zwangsversteigerungstermin teilnehmen und benoetigt Vorbereitung und Bieterangebotsanalyse.

## Fachbegriffe (kurz erklaert)

- **Beschlagnahme** — Rechtliche Wirkung der Anordnung der Zwangsverwaltung: Der Schuldner verliert die Verfuegungsmacht ueber Fruechte und Nutzungen (§§ 146 148 ZVG).
- **Zwangsverwalter** — Vom Vollstreckungsgericht bestellte Person, die das Objekt im Interesse der Glaeubiger verwaltet (§§ 150 ff. ZVG).
- **Treuhandkonto** — Getrenntes Konto fuer Einnahmen und Ausgaben der Zwangsverwaltung; Zwangsverwalter fuehrt es treuhänderisch.
- **Rechnungslegung** — Pflicht des Zwangsverwalters nach § 161 ZVG, dem Gericht jaehrlich Rechenschaft ueber Einnahmen und Ausgaben abzulegen.
- **Verteilungsplan** — Verteilung der Einnahmen nach gesetzlicher Rangfolge des § 155 ZVG auf Kosten, Glaeubiger und sonstige Berechtigte.
- **Geringstes Gebot** — Mindestgebot in der Zwangsversteigerung nach § 74a ZVG: Massstab fuer 7/10-Grenze und Zuschlagsversagung.
- **Absonderungsrecht** — Recht eines Glaeubigers, Befriedigung aus einem bestimmten Gegenstand vorrangig zu verlangen (§ 49 InsO im Kontext der Insolvenzschnittstelle).
- **Rangklassen** — Gesetzliche Rangfolge der Befriedigung im ZVG-Verfahren nach § 10 ZVG.

## Rechtsgrundlagen

- §§ 146-161 ZVG — Kernvorschriften der Zwangsverwaltung
- § 155 ZVG — Einnahmen und Ausgaben; Verteilung
- § 161 ZVG — Rechnungslegungspflicht
- § 10 ZVG — Rangklassen im ZVG-Verfahren
- § 74a ZVG — Geringstes Gebot und Wertgrenzen
- § 81 ZVG — Sicherheitsleistung
- § 85a ZVG — Zuschlagsversagung
- §§ 535 543 573 BGB — Mietrecht (Mieteinzug, Kuendigung)
- § 165 InsO — Absonderungsrecht des Grundpfandglaeubigers
- § 823 BGB — Verkehrssicherungspflicht bei Objektmaengeln

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Bestellungsbeschluss pruefen und Objektcockpit anlegen (Aktenanlage, Beteiligtenregister, Mieterliste, Treuhandkonto).
2. Besitzerlangung vor Ort protokollieren und Gericht informieren.
3. Laufende Verwaltung: Mieteinzug, Betriebskosten, Instandhaltung, Versicherungen und Konten fuehren.
4. Berichterstattung an Gericht und Glaeubiger; Qualitaetsgate vor Versand.
5. Rechnungslegung und Verteilungsplan am Ende der Periode oder bei Aufhebung erstellen.

## Skill-Tour (was gibt es hier?)

- `zvg-aktenanlage-objektcockpit` — Aktenanlage und Objektcockpit aufbauen: Objektkarte, Beteiligtenregister, Mieterliste und Fristen.
- `zvg-berichtswesen-gericht` — Besitzerlangungsbericht, Sachstandsbericht und Entscheidungsvorlagen fuer das Vollstreckungsgericht erstellen.
- `zvg-besitzuebernahme` — Besitzerlangung am Objekt protokollieren: Vor-Ort-Termin, Objektbeschreibung, Schluesselliste und Gericht informieren.
- `zvg-bestellung-beschlagnahme` — Bestellungsbeschluss und Beschlagnahme rechtlich pruefen: Vollstaendigkeitsvermerk und naechste Schritte.
- `zvg-betriebskosten-hausgeld` — Betriebskosten, WEG-Hausgeld und laufende Objektkosten pruefen und abrechnen.
- `zvg-bieterangebot-bewertung` — Zwangsversteigerungsobjekte aus Investorensicht bewerten: Bietlimit, geringstes Gebot und Risikoeinschaetzung.
- `zvg-glaeubiger-schuldner-kommunikation` — Schriftwechsel mit Schuldner, Glaeubiger, Mieter, Gericht, Versicherern und Dienstleistern.
- `zvg-insolvenz-schnittstelle` — Koordination mit Insolvenzverwalter bei Insolvenz des Schuldners waehrend laufender Zwangsverwaltung.
- `zvg-instandhaltung-sicherung` — Instandhaltung, Sicherung und Gefahrenabwehr am Objekt; Verkehrssicherungspflichten.
- `zvg-kommandocenter` — Triage und Routing zu allen ZVG-Skills; Statusampel und Tagesaufgaben.
- `zvg-konten-kassenfuehrung` — Treuhandkonto und Buchfuehrung: Einnahmen, Ausgaben, Saldo und Belegverzeichnis.
- `zvg-miet-und-pachtverwaltung` — Miet- und Pachtverwaltung einschliesslich Vertragsuebernahme und Zahlungseinzug.
- `zvg-mieteinzug-rueckstaende` — Mietrueckstaende einziehen: Mahnung, Ratenvereinbarung, Klage und Einzugsnachweis.
- `zvg-oeffentliche-lasten` — Grundsteuer, Erschliessungsgebuehren und oeffentliche Abgaben in der Rangklassenlogik behandeln.
- `zvg-portal-recherche` — ZVG-Portal-Recherche zu Versteigerungsterminen, Gutachten-Downloads und Terminlisten.
- `zvg-quality-gate` — Qualitaetsgate vor Versand oder Rechnungslegung: Ampelstatus und Freigabeentscheidung.
- `zvg-raeumung-kuendigung` — Raeumung, Kuendigung und Besitzkonflikte mit Schuldner oder Mieter bearbeiten.
- `zvg-rechnungslegung` — Jahresrechnung und Schlussrechnung gerichtsfaehig erstellen.
- `zvg-simulation-training` — Zwangsverwaltungs-Workflows im Simulationsmodus trainieren und demonstrieren.
- `zvg-verkauf-versteigerung-schnittstelle` — Schnittstelle zwischen laufender Zwangsverwaltung und Zwangsversteigerungsverfahren.
- `zvg-versicherungen-gefahren` — Versicherungsschutz pruefen und Schadenfall melden; Deckungsnachweis und Sicherungsmassnahmen.
- `zvg-versteigerungsteilnahme` — Vorbereitung der Teilnahme am Zwangsversteigerungstermin: Ausweis, Sicherheitsleistung, Bietstrategie.
- `zvg-verteilungsplan-155` — Verteilungsplan nach § 155 ZVG: Rangfolge, Betraege, Auszahlungsnachweis und Gerichtsbericht.

## Worauf besonders achten

- **Besitzerlangungsbericht zeitnah**: Das Gericht erwartet sofortige Meldung nach Besitzuebernahme; Verzoegerung kann zu Rueckfragen fuehren.
- **Treuhandkonto strikt getrennt**: Verwaltungseinnahmen duerfen nicht mit Eigengeldern des Verwalters vermischt werden.
- **WEG-Hausgeld als vorrangige Ausgabe**: § 10 ZVG stellt laufendes Hausgeld in eine besondere Rangklasse; Zahlungsverzug kann Schadensersatzpflicht ausloesen.
- **Insolvenzschnittstelle fruehzeitig klaeren**: Bei Insolvenz des Schuldners aendert sich das Absonderungsrecht; Abstimmung mit Insolvenzverwalter ist unverzueglich erforderlich.
- **Quality Gate vor jedem Gerichtsversand**: Bericht oder Rechnungslegung ohne vorherigen Gate-Lauf riskiert Rueckfragen und Gerichtsmaengel.

## Typische Fehler

- Vorausverfuegungen des Schuldners (Mietvorauszahlungen, Abtretungen) nicht geprueft; unbekannte Belastungen reduzieren auszahlbare Einnahmen.
- Mietrueckstaende zu lange belassen ohne Mahnung und Klageeinleitung; Forderungspraeskription und Insolvenz des Mieters drohen.
- Rechnungslegung ohne vollstaendige Belegpruefung; Gericht fordert Nachbesserungen.
- Bei Aufhebung der Zwangsverwaltung kein Uebergabebericht fuer das Versteigerungsverfahren erstellt.
- Versicherungsschutz erst nach Schadenfall geprueft; rueckwirkende Deckungsluecken sind unvermeidlich.

## Querverweise

- `insolvenzverwaltung` — Bei Insolvenz des Schuldners; Absonderungsrechte und Masseschnittstelle.
- `immobilienrechtspraxis` — Fuer mietrechtliche Grundlagen und Vertragsanalyse.
- `aktenauszug-gerichtsverfahren` — Fuer schnelle Einarbeitung in das zugrunde liegende Vollstreckungsverfahren.
- `kanzlei-allgemein` — Allgemeines Kanzlei-Workflow-Plugin fuer Fristen und Schriftsaetze.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum
- ZVG in der aktuellen Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
