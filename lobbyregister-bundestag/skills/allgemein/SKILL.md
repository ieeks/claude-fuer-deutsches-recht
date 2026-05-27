---
name: allgemein
description: "Einstieg und Orientierung im Lobbyregister-Bundestag-Plugin. Klaert Registrierungspflicht nach LobbyRG, Ausnahmen, Portalworkflow, Fristen, Verhaltenspflichten und Routing zu allen 50 Spezial-Skills fuer Public-Affairs-Mandate."
---

# Lobbyregister Bundestag — Allgemein

## Worum geht es?

Das Lobbyregister-Bundestag-Plugin unterstuetzt Unternehmen, Verbaende, Agenturen und deren Berater bei der vollstaendigen Erfullung der Pflichten nach dem Lobbyregistergesetz (LobbyRG). Es begleitet den gesamten Lebenszyklus eines Registereintrags: von der Registrierungspflichtpruefung ueber die Erstregistrierung und laufende Aktualisierung bis zur Meldung von Verstoessen und der Erstellung interner Compliance-Strukturen.

Das Plugin adressiert alle Normen der §§ 1 bis 7 LobbyRG sowie ergaenzende Materialien wie das Handbuch der registerfuehrenden Stelle (Bundestag-Verwaltung). Es ist kein Rechtsberatungsersatz, sondern ein strukturiertes Pruefwerkzeug.

## Wann brauchen Sie diese Skill?

- Sie wollen pruefen, ob Ihre Organisation ueberhaupt registrierungspflichtig ist (§ 2 LobbyRG).
- Sie stehen am Anfang eines neuen Lobbyregister-Mandats und suchen den richtigen Einstiegspunkt.
- Sie wollen verstehen, welcher der 50 Skills fuer Ihre aktuelle Fragestellung zustaendig ist.
- Sie haben eine Frist (unverzuegliche Aktualisierung, Quartalsfrist, Jahresbestaetigung) und muessen schnell handeln.
- Sie sind Public-Affairs-Agentur oder Kanzlei und verwalten mehrere Mandate gleichzeitig.

## Fachbegriffe (kurz erklaert)

- **LobbyRG** — Lobbyregistergesetz; Bundesgesetz, das Interessenvertreter verpflichtet, sich beim Deutschen Bundestag zu registrieren.
- **Interessenvertretung** — Jede Kontaktaufnahme zur unmittelbaren oder mittelbaren Einflussnahme auf Willensbildungs- oder Entscheidungsprozesse nach § 1 LobbyRG.
- **Registrierungspflicht** — Besteht bei regelmaessiger, auf Dauer angelegter oder geschaeftsmaessiger Interessenvertretung oder mehr als 30 Kontakten in drei Monaten (§ 2 Abs. 1 LobbyRG).
- **Registerfuehrende Stelle (RfS)** — Die Verwaltung des Deutschen Bundestags; sie prueft Eintraege, fuehrt Bussgeldverfahren durch und ist Ansprechpartnerin bei Korrekturen.
- **Verhaltenskodex** — Verpflichtende Selbstverpflichtung nach § 5 LobbyRG zu Offenheit, Transparenz und Integritaet bei jedem Kontakt mit Adressaten.
- **Drehtuer** — Regelung, die frueheres Amt oder Mandat in Bundestag oder Bundesregierung offenzulegen verlangt (§ 3 LobbyRG).
- **Finanzielle Aufwendungen** — Alle Personal- und Sachkosten im Bereich Interessenvertretung; Angabepflicht in Bandbreiten nach § 3 LobbyRG.
- **Hausausweis** — Tagesausweis fuer Bundestagsgebaeude; nach § 6 LobbyRG nur fuer registrierte Interessenvertreter zugaenglich.

## Rechtsgrundlagen

- § 1 LobbyRG — Begriff der Interessenvertretung und Adressatenkreis.
- § 2 LobbyRG — Registrierungspflicht und Ausnahmen.
- § 3 LobbyRG — Pflichtinhalt des Registereintrags.
- § 4 LobbyRG — Angaben zu Finanzen, Schutzantraegen, Nichtoeffentlichem.
- § 5 LobbyRG — Verhaltenskodex.
- § 6 LobbyRG — Rechtsfolgen der Registrierung (Hausausweis, Anhoerungen).
- § 7 LobbyRG — Bussgeldtatbestaende und Sanktionen.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Unternehmenstyp, Kontaktplaene, Auftraggeber, bestehender Portaleintrag oder Erstregistrierung.
2. Registrierungspflicht pruefen: Skill `registrierungspflicht-schwellen` und `interessenvertretung-begriff` verwenden.
3. Falls Ausnahme moeglich: `ausnahmen-bundestag` oder `ausnahmen-bundesregierung` pruefen.
4. Passendes Themen-Cluster auswaehlen (siehe Skill-Tour unten).
5. Eilfristen beachten: unverzuegliche Aktualisierung oder Quartalsfrist via `fristen-und-quartalsmonitor`.

## Skill-Tour (was gibt es hier?)

**Pflicht und Abgrenzung**

- `registrierungspflicht-schwellen` — Prueft § 2 Abs. 1 LobbyRG: Schwellen fuer Registrierungspflicht (regelmaessig, auf Dauer, 30-Kontakte-Regel).
- `interessenvertretung-Begriff` — Klaert, ob ein Kontakt ueberhaupt Interessenvertretung nach § 1 LobbyRG ist.
- `ausnahmen-bundestag` — Prueft Ausnahmen von der Registrierungspflicht gegenueber Bundestagsadressaten.
- `ausnahmen-bundesregierung` — Prueft Ausnahmen gegenueber Bundesregierung und Ministerien.
- `freiwillige-registrierung` — Beraet zu Rechten und Pflichten bei freiwilliger Eintragung nach § 2 Abs. 5 LobbyRG.
- `adressatenkreis-bundestag-bundesregierung` — Kartiert, wer Adressat nach § 1 LobbyRG ist.

**Erstregistrierung und Portalworkflow**

- `lobbyregister-intake-mandat` — Strukturiertes Erstgespraech vor jeder Lobbyregister-Pruefung.
- `lobbyregister-kommandocenter` — Master-Routing fuer alle Lobbyregister-Mandate.
- `end-to-end-registrierungswizard` — Gefuehrter Gesamtworkflow fuer die komplette Registrierungsmappe.
- `erstregistrierung-ausfuellen` — Schritt-fuer-Schritt durch den Portal-Ersteintrag.
- `portal-account-rollen` — Plant Administrationskonto, Rollen und Zugriffsschutz.
- `personen-organisationstyp` — Bestimmt, welcher Organisationstyp einzutragen ist.
- `bestaetigungsdokument-freigabe` — Unterzeichner, Leitungsperson und Freigabe vor Eintragung.
- `registereintrag-finalcheck` — Prueft vor Freigabe Vollstaendigkeit, Richtigkeit und Aktualitaet.

**Stammdaten und Inhalt**

- `taetigkeitsbeschreibung` — Formuliert die allgemeine Taetigkeitsbeschreibung der Interessenvertretung.
- `interessen-und-vorhabenbereiche` — Ordnet Interessen- und Vorhabenbereiche zu.
- `regelungsvorhaben-erfassen` — Erfasst konkrete Regelungsvorhaben fuer den Eintrag.
- `betraute-personen` — Ermittelt Personen, die mit Interessenvertretung betraut sind.
- `vertretungsberechtigte-personen` — Ermittelt gesetzliche Vertretungen und Zeichnungsberechtigte.
- `mitgliedschaften-mitgliederzahl` — Erfasst Mitgliederzahl und relevante Mitgliedschaften.
- `hauptstadtrepraesentanz` — Prueft, ob eine Berliner Geschaeftsstelle anzugeben ist.

**Finanzdaten**

- `finanzaufwendungen-berechnen` — Berechnet finanzielle Aufwendungen nach § 3 LobbyRG.
- `hauptfinanzierungsquellen` — Strukturiert Hauptfinanzierungsquellen und grenzt Einnahmearten ab.
- `oeffentliche-zuwendungen` — Prueft Zuwendungen der oeffentlichen Hand mit Schwellenwerten.
- `schenkungen-sponsoring` — Prueft Schenkungen und Zuwendungen Dritter.
- `jahresabschluss-rechenschaftsbericht` — Prueft Bereitstellungspflicht fuer Jahresabschluss oder Rechenschaftsbericht.

**Spezialkonstellationen**

- `auftraggeber-ermitteln` — Erfasst Auftraggeber bei Interessenvertretung fuer Dritte.
- `fremdmandat-agenturfall` — Spezialworkflow fuer Public-Affairs-Agenturen mit mehreren Mandanten.
- `konzern-netzwerk-plattform` — Lobbyregisterfragen bei Konzernen, Verbaenden, Netzwerken.
- `unterauftragnehmer-erfassen` — Prueft Unterauftragsverhaeltnisse und eingesetzte Personen.
- `drehtuer-angaben` — Fuehrt durch Angaben zu frueherem Amt oder Mandat in Politik und Verwaltung.
- `anonymisierung-schutzantrag` — Prueft Beschraenkung der Veroeffentlichung bei schutzwuerdigen Interessen.
- `datenschutz-nichtoeffentliche-angaben` — Ordnet oeffentliche und nicht oeffentliche Angaben.

**Aktualisierung und Fristen**

- `aktualisierung-unverzueglich` — Steuert unverzuegliche Updates bei Stammdaten und Personenaenderungen.
- `geschaeftsjahresaktualisierung` — Jaehrliche vollstaendige Ueberpruefung und Bestaetigung.
- `fristen-und-quartalsmonitor` — Baut Fristenkalender fuer alle Updatepflichten und Nachholfristen.
- `nicht-aktualisiert-risiko` — Prueft Kennzeichnung nicht aktualisiert und Rettungsplan.

**Stellungnahmen und Gutachten**

- `stellungnahmen-gutachten-upload` — Prueft Bereitstellungspflicht und Quartalsfrist fuer Stellungnahmen.

**Verhaltenskodex und Compliance**

- `verhaltenskodex-integritaet` — Operationalisiert Offenheit, Transparenz und Integritaet nach § 5 LobbyRG.
- `erstkontakt-offenlegung` — Formuliert Offenlegung beim erstmaligen Kontakt mit Adressaten.
- `hausausweis-und-anhoerung` — Prueft Auswirkungen des Registerstatus auf Tagesausweis und Anhoerungen.
- `interne-lobbyregister-richtlinie` — Erstellt interne Richtlinie fuer Rollen, Meldewege und Schulung.
- `visitenkarte-und-nachweise` — Nutzt Registerauszug und interne Nachweise fuer Compliance-Akte.

**Sanktionen und Meldungen**

- `bussgeld-und-pruefverfahren` — Reaktionsworkflow bei RfS-Pruefung, Anhoerung und Bussgeldrisiko.
- `verstoesse-melden` — Fuehrt durch Meldung moeglicher Verstoesse an die registerfuehrende Stelle.
- `registerfuehrende-stelle-kontakt` — Bereitet Anfragen an die RfS und Korrekturen vor.

**Monitoring und Dokumentation**

- `benachrichtigungskonto-monitor` — Richtet Beobachtung von Registereintraegen und Entwicklungen ein.
- `suche-open-data-monitor` — Nutzt Suche und Open-Data-API fuer Compliance- und Gegenpruefung.
- `dokumentationsakte-revisionsspur` — Baut Aktenstruktur fuer Belege, Freigaben und Portal-Screenshots.

**Beendigung und Archivierung**

- `fruehere-interessenvertretung-exit` — Fuehrt durch Anzeige, dass keine Pflicht mehr besteht, und Archivierung.

## Worauf besonders achten

- **Unverzueglichkeitspflicht** — Jede wesentliche Aenderung (Personen, Taetigkeitsbeschreibung, Auftraggeber) muss ohne schuldhaftes Zoegern im Portal aktualisiert werden; Versaeumnisse erzeugen Bussgeldrisiko nach § 7 LobbyRG.
- **Ausnahmepruefung zuerst** — Viele Kanzleien und Beratungen gehen reflexartig von Registrierungspflicht aus; eine sorgfaeltige Ausnahmepruefung nach § 2 Abs. 2 und 3 LobbyRG spart Aufwand.
- **Irrefuehrungs-Verbot** — Eintraege muessen pruefbar und nicht irrefuehrend formuliert sein; zu allgemeine Taetigkeitsbeschreibungen koennen als Verschleierung gewertet werden.
- **Agenturfall trennen** — Bei Fremdmandaten muessen Auftraggeber und die jeweils beauftragte Interessenvertretung klar getrennt sein; das Vermischen von Mandaten im selben Eintrag ist ein klassischer Fehler.
- **Quartalsfrist Stellungnahmen** — Grundlegende Stellungnahmen oder Gutachten zu Regelungsvorhaben sind innerhalb eines Quartals nach Veroeffentlichung bereitzustellen (§ 3 LobbyRG).

## Typische Fehler

- Kontakte, die tatsaechlich Serviceanfragen oder rein lokale Anliegen sind, werden faelschlicherweise als registrierungspflichtige Interessenvertretung behandelt.
- Die Drehtuer-Angaben werden vergessen oder zu eng ausgelegt (nur letzter Job statt alle relevanten fuenf Jahre).
- Schutzantraege werden nicht gestellt, obwohl schutzwuerdige Interessen von Personen vorliegen.
- Finanzdaten werden ohne Pruefung der aktuellen Schwellenwerte und Bandbreiten eingetragen.
- Portal-Konten werden ohne Zwei-Personen-Freigabeprozess betrieben, was bei Personalwechseln zu Kontrollverlust fuehrt.

## Querverweise

- `insolvenzrecht` — Wenn Auftraggeber insolvent ist und Mandatsbasis wegfaellt.
- `kartellrecht-marktabgrenzung-pruefung` — Wenn Interessenvertretung zu laufenden Kartellverfahren erfolgt.
- `europarecht-kompass` — Bei Interessenvertretung gegenueber EU-Institutionen (kein LobbyRG, aber EU-Transparenzregister).
- `bereicherungs-und-anfechtungsrecht-pruefer` — Bei Rueckabwicklung von Vergutungen aus Lobbymandat.

## Quellen und Aktualitaet

- Stand: 05/2026
- Lobbyregistergesetz (LobbyRG) in der geltenden Fassung
- Handbuch der registerfuehrenden Stelle des Deutschen Bundestags
- Lobbyregister-Portal: www.lobbyregister.bundestag.de

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
