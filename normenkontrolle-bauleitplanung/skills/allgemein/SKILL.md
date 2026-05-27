---
name: allgemein
description: "Einstieg und Orientierung im Normenkontrolle-Bauleitplanung-Plugin. Klaert Statthaftigkeit, Antragsbefugnis, Jahresfrist, Fehlertypen (Verfahren, Abwaegung, Erforderlichkeit), Planerhaltung und Routing zu allen 21 Spezial-Skills."
---

# Normenkontrolle Bauleitplanung — Allgemein

## Worum geht es?

Dieses Plugin begleitet die Pruefung und Anfechtung von Bebauungsplaenen, Flaechennutzungsplaenen und oertlichen Bauvorschriften vor dem Bayerischen Verwaltungsgerichtshof (BayVGH) und den Oberverwaltungsgerichten (OVG) nach § 47 VwGO. Es deckt das Mandat aus der Perspektive des Antragstellers (Eigentuemer, Nachbar, Naturschutzverband) ab.

Das Plugin strukturiert die Zulaessigkeitsvoraussetzungen (Statthaftigkeit, Antragsbefugnis, Jahresfrist), die Fehlertypen nach dem BauGB (Verfahrensfehler, Erforderlichkeit, Abwaegungsmangel, Fehler bei Festsetzungen), die Planerhaltungsregeln der §§ 214 und 215 BauGB sowie den Eilrechtsschutz nach § 47 Abs. 6 VwGO. Es ersetzt keine individuellen Vertretungshandlungen.

## Wann brauchen Sie diese Skill?

- Grundstueckseigentuemer oder Nachbar kommt mit einem neuen Bebauungsplan in die Kanzlei und fragt nach Moeglichkeiten.
- Mandant hat eine Buergerversammlung besucht und moechte das Protokoll auf Vorfestlegungen pruefen lassen.
- Sie muessen schnell beurteilen, ob die Jahresfrist des § 47 Abs. 2 VwGO noch laeuft.
- Mandant moechte die Vollziehung eines gerade bekanntgemachten Bebauungsplans vorlaefig stoppen.
- Naturschutzverband fragt, ob er gegen einen Plan mit unzureichender Artenschutzpruefung vorgehen kann.

## Fachbegriffe (kurz erklaert)

- **Normenkontrolle (§ 47 VwGO)** — Abstraktes Kontrollinstrument; das OVG/VGH prueft die Rechtmaeßigkeit eines Bebauungsplans oder einer oertlichen Bauvorschrift auf Antrag.
- **Antragsbefugnis** — Nur wer in eigenen Rechten verletzt sein koennte, kann Antrag stellen (Moeglichkeitstheorie, § 47 Abs. 2 S. 1 VwGO).
- **Jahresfrist** — Normenkontrollantrag muss innerhalb eines Jahres ab ortsuebl. Bekanntmachung gestellt werden (§ 47 Abs. 2 S. 1 VwGO).
- **Abwaegungsgebot** — Die Gemeinde muss alle betroffenen Belange ermitteln, bewerten und gegeneinander abwaegen (§ 1 Abs. 7 BauGB); vier Fehlerstufen.
- **Planerhaltung** — §§ 214 und 215 BauGB beschraenken, welche Fehler zur Unwirksamkeit fuehren; Verfahrensfehler sind oft heilbar, Ergebnisfehler nicht.
- **Erforderlichkeit** — Bebauungsplan muss einem nachvollziehbaren staedtebaulichen Konzept dienen (§ 1 Abs. 3 BauGB); Gefaelligkeits- und Verhinderungsplanung sind unzulaessig.
- **Veraenderungssperre** — Sicherungsinstrument der Gemeinde nach § 14 BauGB; hemmt Baugenehmigungen waehrend des Aufstellungsverfahrens.
- **VEP** — Vorhabenbezogener Bebauungsplan nach § 12 BauGB mit Vorhaben- und Erschliessungsplan und Durchfuehrungsvertrag.

## Rechtsgrundlagen

- § 47 VwGO — Normenkontrollverfahren, Statthaftigkeit, Antragsbefugnis, Jahresfrist, einstweilige Anordnung.
- §§ 1 bis 13a BauGB — Aufstellungsverfahren, Erforderlichkeit, Abwaegungsgebot, Beteiligung, Veraenderungssperre.
- §§ 214 und 215 BauGB — Planerhaltung: beachtliche Fehler, Ruegefrist, ergaenzendes Verfahren.
- § 9 BauGB — Festsetzungskatalog.
- BauNVO — Art und Mass der baulichen Nutzung, Hoechtsgrenzen.
- § 44 BNatSchG — Artenschutzrechtliche Zugriffsverbote.
- Art. 47 BayBO, Art. 81 BayBO — Stellplaetze und oertliche Bauvorschriften in Bayern.
- § 2 Abs. 4 BauGB, § 2a BauGB — Umweltpruefung und Umweltbericht.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Erstgespraech und Mandatsannahme-Pruefung: Skill `mandat-erstgespraech-normenkontrolle`.
2. Statthaftigkeit und Antragsbefugnis klaeren: `statthaftigkeit-47-vwgo` und `antragsbefugnis-eigentuemer-nachbar`.
3. Jahresfrist berechnen: `jahresfrist-47-abs-2-vwgo`.
4. Fehlersuche nach Prioritaet: Verfahrensfehler, Erforderlichkeit, Abwaegung, Festsetzungen.
5. Eilantrag pruefen bei drohenden Genehmigungen: `einstweilige-anordnung-47-abs-6-vwgo`.
6. Normenkontrollantrag formulieren: `normenkontrollantrag-schriftsatz`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Mandat**

- `mandat-erstgespraech-normenkontrolle` — Erstgespraech, Mandatsannahme-Empfehlung, vorlaeufige Erfolgsaussichten.
- `statthaftigkeit-47-vwgo` — Statthaftigkeit der Normenkontrolle gegen Bebauungsplan, VEP, oertliche Bauvorschriften.
- `antragsbefugnis-eigentuemer-nachbar` — Antragsbefugnis fuer Eigentuemer, Nachbar, Verband.
- `jahresfrist-47-abs-2-vwgo` — Jahresfrist berechnen, Fristbeginn, fehlerhafte Bekanntmachung.

**Verfahrensfehler**

- `aufstellungsbeschluss-bekanntmachung` — Fehler beim Aufstellungsbeschluss und der Bekanntmachung.
- `beteiligung-frueh-foermlich` — Fehler in der fruehzeitigen und foermlichen Beteiligung.
- `buergerversammlung-protokoll-audit` — Niederschrift der Buergerversammlung auf Vollstaendigkeit pruefen.
- `umweltbericht-umweltpruefung` — Umweltpruefung und Umweltbericht auf Fehler pruefen.
- `artenschutz-naturschutz-planung` — Artenschutzpruefung (saP), CEF-Massnahmen, FFH-Vertraeglichkeit.

**Materielle Fehler**

- `erforderlichkeit-1-abs-3-baugb` — Erforderlichkeit und Planrechtfertigung; Gefaelligkeits- und Verhinderungsplanung.
- `abwaegungsgebot-1-abs-7-baugb` — Vier Abwaegungsfehler-Stufen nach § 1 Abs. 7 BauGB.
- `anpassungsgebot-flaechennutzungsplan` — Entwicklungsgebot aus dem Flaechennutzungsplan.
- `festsetzungskatalog-9-baugb-baunvo` — Unzulaessige Festsetzungen ausserhalb des Katalogs.
- `immissionsschutz-laerm-bauleitplanung` — Schallschutz, TA Laerm, § 50 BImSchG.

**Planerhaltung und Ruegefrist**

- `planerhaltung-214-215-baugb` — Welche Fehler fuehren zur Unwirksamkeit, welche sind heilbar? Ruegefrist ein Jahr.

**Spezialkonstellationen**

- `vorhabenbezogener-bebauungsplan-12-baugb` — VEP-Pruefung fuer Vorhabentraeger und Drittbetroffene.
- `veraenderungssperre-zurueckstellung-14-15-baugb` — Anfechtung und Entschaedigung bei Veraenderungssperre.
- `stellplatzsatzung-bay-bauordnung` — Stellplatzsatzung nach Art. 47 BayBO und § 9 Abs. 1 Nr. 4 BauGB.

**Schriftsaetze und Verhandlung**

- `normenkontrollantrag-schriftsatz` — Vollstaendiger Normenkontrollantrag mit Zulaessigkeit, Fehleranalyse, Hilfsantrag.
- `einstweilige-anordnung-47-abs-6-vwgo` — Eilantrag nach § 47 Abs. 6 VwGO gegen Vollziehung des Bebauungsplans.
- `muendliche-verhandlung-vgh-strategie` — Vorbereitung der muendlichen Verhandlung am VGH oder OVG.

## Worauf besonders achten

- **Jahresfrist ist absolut** — Ab ortsuebl. Bekanntmachung laeuft die Jahresfrist unabhaengig von Kenntnis; bei fehlerhafter Bekanntmachung beginnt sie nicht.
- **Planerhaltung filtert viele Fehler** — Nicht jeder Verfahrensfehler fuehrt zur Unwirksamkeit; § 214 Abs. 1 BauGB und die Ruegefrist des § 215 BauGB muessen immer mitbeachtet werden.
- **Ergebnisfehler immer beachtlich** — Fehler bei der Festsetzung ausserhalb des Katalogs oder bei der Erforderlichkeit sind nicht heilbar und nicht ruegepflichtig.
- **Teilunwirksamkeit beantragen** — Bei fehlerhaften Einzelfestsetzungen kann Teilunwirksamkeit Erfolg haben, selbst wenn der Gesamtplan sonst Bestand haelt.
- **Eilantrag und Hauptsache koordinieren** — § 47 Abs. 6 VwGO setzt keinen vor dem Antrag in der Hauptsache voraus; Antragsbefugnis muss aber gegeben sein.

## Typische Fehler

- Normenkontrolle gegen Flaechennutzungsplan beantragt, obwohl dieser grundsaetzlich nicht statthafter Gegenstand ist (Ausnahme: Konzentrationsflaechen).
- Ruegefrist des § 215 BauGB versaeumnt; Verfahrensfehler koennen danach nicht mehr geltend gemacht werden.
- Naturschutzverband meldet sich ohne Verbandsklagebefugnis nach § 64 BNatSchG oder § 2 UmwRG.
- Abwaegungsfehler-Argument wird auf Vorgangs- statt auf Ergebnis-Ebene gefuehrt; § 214 Abs. 3 BauGB filtert nur Vorgangsfehler.
- Eilantrag nach § 47 Abs. 6 VwGO wird eingereicht, obwohl Bebauungsplan noch nicht in Kraft ist.

## Querverweise

- `europarecht-kompass` — Bei FFH- oder Vogelschutz-Richtlinien-Konflikten im Bebauungsplan.
- `normenkontrolle-bauleitplanung` — Dieses Plugin ist bereits das spezialisierte Werkzeug.
- `jveg-kostenpruefer` — Bei Kosten fuer Sachverstaendige im Normenkontrollverfahren.

## Quellen und Aktualitaet

- Stand: 05/2026
- BauGB in der geltenden Fassung
- BauNVO in der geltenden Fassung
- VwGO § 47 in der geltenden Fassung
- BNatSchG §§ 44 und 45 in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
