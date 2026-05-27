---
name: allgemein
description: "Einstieg und Überblick für das Wandeldarlehen-Lebenszyklus-Plugin: Vertragsgestaltung bilingual/einsprachig, Beurkundungsprüfung, Wandelereignisse, Wandlungsberechnung, Cap-Table, Gesellschafterbeschluss, Notarpaket und Handelsregister für GmbH und UG."
---

# Wandeldarlehen Lebenszyklus — Allgemein

## Worum geht es?

Das Plugin begleitet den vollstaendigen Lebenszyklus eines Wandeldarlehens (Convertible Note oder SAFE) fuer GmbH und UG: von der Ersterfassung der Parteien und der Konditionenverhandlung ueber die Vertragserstellung (bilingual oder einsprachig) und Beurkundungspruefung bis hin zur Wandlungsberechnung, dem Cap-Table-Update und der notar- und handelsregistergerechten Dokumentation der Kapitalerhoehung.

Zielgruppe sind Anwaelte und Steuerberater im Startup- und Venture-Capital-Bereich sowie Inhouse-Juristen, die Wandeldarlehen als Finanzierungsinstrument einsetzen. Das Plugin begleitet sowohl die Darlehensgeber- als auch die Gesellschaftsseite.

## Wann brauchen Sie diese Skill?

- Startup-GmbH und Investor verhandeln ein Wandeldarlehen oder SAFE; Vertrag muss von Grund auf erstellt werden.
- Bestehendes Wandeldarlehen lauft ab oder ein Wandelereignis (qualifizierte Finanzierungsrunde, Exit) tritt ein.
- Mehrere Wandeldarlehen von verschiedenen Investoren muessen parallel koordiniert und auf Kollisionspunkte geprueft werden.
- Kapitalerhoehung durch Wandlung erfordert Notartermin, Gesellschafterbeschluss und Handelsregisteranmeldung.
- Formfehler in Wandeldarlehen- oder Kapitalerhoehungs-Dokumenten muessen identifiziert und geheilt werden.

## Fachbegriffe (kurz erklaert)

- **Wandeldarlehen** — Darlehen nach §§ 488 ff. BGB, das unter bestimmten Bedingungen (Trigger) in Gesellschaftsanteile umgewandelt wird.
- **SAFE** — Simple Agreement for Future Equity; Y-Combinator-Vorlage; kein Darlehen im Rechtssinne, sondern Vereinbarung auf zukuenftige Kapitalbeteiligung.
- **Wandlungspreis** — Preis je neu ausgegebenen Geschaeftsanteil; ergibt sich aus Bewertungs-Cap, Discount oder Finanzierungsrunde.
- **Cap-Table** — Gesellschafterliste inkl. aller voll verwasserten Anteile (fully diluted); zeigt Beteiligungsstruktur vor und nach Wandlung.
- **Qualified Financing** — Qualifiziertes Finanzierungsereignis; haeufigster Wandlungs-Trigger; meist definiert als neue Finanzierungsrunde ab einer Mindestbetrag-Schwelle.
- **Rangruecktritt** — Nachrangabrede nach § 39 InsO; stellt Wandeldarlehen insolvenzrechtlich nachrangig, um Ueberschuldungsausweis zu verhindern.
- **Beurkundungserfordernis** — Kapitalerhoehungen bei GmbH beduerften notarieller Beurkundung nach § 55 GmbHG; Formmangel fuehrt zu Nichtigkeit.
- **SAFE-Y-Combinator** — US-Standardvorlage fuer Seed-Investitionen; in Deutschland-Transaktionen oft angepasst oder ersetzt.

## Rechtsgrundlagen

- §§ 488 491 BGB — Darlehensrecht
- §§ 53 55 56 57 GmbHG — Satzungsaenderung, Kapitalerhoehung, Sacheinlage, Anmeldung
- § 40 GmbHG — Gesellschafterliste; Anmeldepflicht nach Aenderung
- § 15 GmbHG — Abtretung von Geschaeftsanteilen (Formpflicht)
- § 39 InsO — Nachrang; Rangruecktrittserklaerung
- §§ 125 126 BGB — Form; Schriftform
- GwG §§ 10 11 — KYC/AML-Pflichten bei Investoren
- eIDAS-VO (EU) 910/2014 — Elektronische Signatur

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Neue Vertragserstellung oder laufendes Mandat mit Wandelereignis?
2. Parteien und Konditionen erfassen: Darlehenshoehe, Zinssatz, Laufzeit, Wandlungspreis-Mechanik.
3. Beurkundungserfordernis pruefen: Liegt ein Formerfordernis vor? Notartermin erforderlich?
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Nach Wandlung: Cap-Table aktualisieren, Gesellschafterliste einreichen, Handelsregister anmelden.

## Skill-Tour (was gibt es hier?)

- `mandat-triage-wandeldarlehen` — Wandeldarlehensmandat einordnen, Verfahrensroute bestimmen und erste Prioritaeten setzen.
- `parteien-erfassen` — Vertragsparteien vollstaendig identifizieren und dokumentieren; KYC-Vorab-Check.
- `darlehenshoehe-konditionen` — Darlehenshoehe, Zinsen, Laufzeit und Konditionen verhandeln und dokumentieren.
- `einsprachige-vertragsfassung-de` — Wandeldarlehensvertrag auf Deutsch erstellen oder ueberarbeiten.
- `bilinguale-vertragserstellung` — Wandeldarlehensvertrag zweisprachig deutsch/englisch fuer internationale Transaktionen erstellen.
- `textform-vs-schriftform-vs-notariell` — Formerfordernis fuer einzelne Wandeldarlehens-Dokumente bestimmen und zuordnen.
- `beurkundungserfordernis-pruefung` — Beurkundungserfordernis pruefen; ob Notartermin erforderlich ist klaeren.
- `vertraulichkeit-und-sprachklausel` — Vertraulichkeits- und Sprachklauseln in Wandeldarlehensvertrag pruefen oder formulieren.
- `unterzeichnung-elektronisch-docusign` — Elektronische Unterzeichnung organisieren; eIDAS-Konformitaet pruefen.
- `kyc-aml-geldwaesche` — KYC- und AML-Anforderungen bei Investor-Onboarding pruefen.
- `rangruecktritt-formulieren` — Rangruecktrittserklaerung fuer insolvenzrechtlichen Nachrang formulieren.
- `wandlungsmechanik-konzipieren` — Wandlungsmechanik konzipieren: Preis, Verwasserungsschutz, Sonderrechte.
- `wandlungspreis-berechnung` — Wandlungspreis auf Basis der vertraglich vereinbarten Parameter berechnen.
- `wandelereignis-trigger-dispatcher` — Wandlungstrigger kategorisieren und an den richtigen Folge-Skill weiterleiten.
- `wandelereignis-eingang` — Eingehende Wandelereignis-Notification pruefen und naechste Schritte bestimmen.
- `wandlungspruefung-trigger-qualified-financing` — Wandlung bei qualifizierter Finanzierungsrunde als Trigger pruefen.
- `wandlungspruefung-trigger-maturity` — Wandlung bei Laufzeitablauf des Wandeldarlehens pruefen.
- `wandlungspruefung-trigger-liquidation` — Wandlung bei Liquidationsereignis oder Exit pruefen.
- `wandlungsausschluss-pruefung` — Pruefen, ob Wandlung gesperrt oder ausgeschlossen ist.
- `mehrere-wandeldarlehen-parallel` — Mehrere parallele Wandeldarlehen von verschiedenen Investoren koordinieren; Konflikte erkennen.
- `cap-table-update-pre-post` — Cap-Table vor und nach Wandlung aktualisieren; Verwasserungseffekte berechnen.
- `gesellschafterbeschluss-vorbereiten` — Gesellschafterbeschluss fuer Wandeldarlehensaufnahme oder Satzungsaenderung vorbereiten.
- `gesellschafterbeschluss-kapitalerhoehung` — Gesellschafterbeschluss fuer Kapitalerhoehung nach Wandlung vorbereiten.
- `gesellschafterversammlung-einberufen` — Gesellschafterversammlung einberufen und Tagesordnung aufstellen.
- `sacheinlagebericht-werthaltigkeit` — Sacheinlagebericht erstellen und Werthaltigkeit pruefen.
- `notar-paket-uebermittlung` — Notarpaket fuer Beurkundungstermin zusammenstellen und uebermitteln.
- `handelsregisteranmeldung-kapitalerhoehung` — Handelsregisteranmeldung nach Kapitalerhoehung durch Wandlung vorbereiten.
- `gesellschafterliste-aktualisieren` — Gesellschafterliste nach Kapitalerhoehung aktualisieren und einreichen.
- `post-eintragung-checkliste` — Nacharbeiten nach Handelsregistereintragung abschliessen.
- `wandlung-kommunikation-paketverteilung` — Kommunikation und Dokumentenversand an alle Beteiligten nach Wandlungsentscheidung.
- `formfehler-heilungs-timeline` — Formfehler in Wandeldarlehen- oder Kapitalerhoehungs-Dokumenten identifizieren und Heilungsmassnahmen planen.
- `dokumenten-upload-extraktion` — Hochgeladene Wandeldarlehens-Dokumente analysieren und Kerndaten extrahieren.

## Worauf besonders achten

- Beurkundungserfordernis nach § 55 GmbHG ist zwingend fuer Kapitalerhoehungen; formlose Wandlung fuehrt zur Nichtigkeit des Kapitalerhoehungsbeschlusses.
- Verwasserungsschutzklauseln (Anti-Dilution) muessen praesize formuliert sein; Broad-Based vs. Narrow-Based-Methode kann erhebliche Unterschiede im Wandlungspreis bewirken.
- Rangruecktritt muss vor Wandlung vorliegen, wenn Ueberschuldung droht; ex-post-Rangruecktritt schuetzt nicht rueckwirkend.
- KYC/AML-Pflichten des GwG gelten ab bestimmten Beteiligungsschwellen; fehlende Pruefung des Investors kann Haftung ausloesen.
- Mehrere parallel laufende Wandeldarlehen koennen Kollisionspunkte bei Triggern und Cap-Berechnung haben; Konsistenzpruefung ist unverzichtbar.

## Typische Fehler

- Wandlungspreis-Formel zu unpraezise: Fehlende Definition von Ausgangsgroessen (pre-money valuation, fully diluted cap) fuehrt zu Streit bei Wandlung.
- Notartermin zu spaet eingeplant: Notariatliche Termine bei DNOTA und Notaren brauchen Vorlaufzeit; Last-Minute-Beurkundung ist haeufig nicht moeglich.
- Gesellschafterliste nicht aktualisiert: Nach Wandlung und Eintragung muss Gesellschafterliste innerhalb eines Monats eingereicht werden (§ 40 GmbHG).
- Sacheinlagebericht fehlt: Bei Sachkapitalerhoehung durch Wandlung ist Sacheinlagebericht Pflicht (§ 56 GmbHG); fehlender Bericht blockiert Eintragung.
- SAFE als Darlehen klassifiziert: Falsches Bilanzierungsurteil fuer SAFE (kein Darlehen, sondern Eigenkapital-Instrument unter US-GAAP; unter HGB haeufig als Verbindlichkeit zu bilanzieren) kann steuerliche Folgen haben.

## Querverweise

- Plugin `liquiditaetsplanung` — Bei Wandeldarlehens-Mandat in Krisennaeher: Rangruecktritt und Insolvenzpruefung parallel.
- Plugin `grosskanzlei-corporate-ma` — Wandeldarlehen als Brückenfinanzierung vor M&A-Transaktion oder Exit.
- Plugin `aussenwirtschaft-zoll-sanktionen` — KYC/Sanktionsscreening des Investors bei internationalen Wandeldarlehen.

## Quellen und Aktualitaet

- Stand: 05/2026
- BGB, GmbHG, InsO, GwG, eIDAS-VO in aktuell geltender Fassung
- SAFE-Vorlage des Y-Combinators (Post-Money SAFE, aktuelle Version 2018)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
