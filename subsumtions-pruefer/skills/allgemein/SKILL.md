---
name: allgemein
description: "Einstieg und Orientierung für den Subsumtions-Prüfer: interaktiver Workflow für deutsches Recht und Europarecht, Tatbestandsmerkmale zerlegen, Vier-Schritt-Schema anwenden, Rechtsfolgen und Einreden prüfen. Kein Ersatz für anwaltliche Beratung."
---

# Subsumtions-Pruefer — Allgemein

## Worum geht es?

Dieses Plugin fuehrt Juristen, Referendare und rechtlich Interessierte durch den klassischen juristischen Pruefungsaufbau: Tatbestandsmerkmale werden systematisch zerlegt, jede Norm wird im Vier-Schritt (Obersatz — Definition — Untersatz — Ergebnis) durchlaufen, Einreden und Rechtsfolgen werden getrennt erarbeitet. Das Plugin deckt deutsches Recht (BGB, HGB, StGB, ZPO, VwGO, GG und zahlreiche Nebengesetze) sowie Europarecht (AEUV, EUV, GRCh, EU-Verordnungen, Richtlinien) ab.

Der Schwerpunkt liegt auf mechanisch nachvollziehbarer Subsumtion — nicht auf freier Rechtsberatung. Alle Ausgaben enthalten einen Pflicht-Disclaimer, der auf die Grenzen automatisierter Pruefung hinweist.

## Wann brauchen Sie diese Skill?

- Sie haben einen konkreten Lebenssachverhalt und wollen wissen, welche Normen einschlaegig sein koennten.
- Sie wollen eine Norm systematisch in ihre Tatbestandsmerkmale zerlegen und Schritt fuer Schritt subsumieren.
- Sie muessen Beweislast, Einreden oder Verjaehrung pruefen und suchen eine strukturierte Abarbeitungshilfe.
- Sie benoetigen eine Ausgabe fuer einen Schriftsatz, ein Memo oder einen Mandantenbrief in verschiedenen Sprachstilen.
- Sie wollen eine Rechtsfrage mit EU-Bezug klaeren und pruefen, ob ein Vorabentscheidungsersuchen in Betracht kommt.

## Fachbegriffe (kurz erklaert)

- **Tatbestandsmerkmal (TBM)** — Einzelnes Element einer Rechtsnorm, das vorliegen muss, damit die Rechtsfolge eintritt.
- **Subsumtion** — Der gedankliche Vorgang, bei dem der Sachverhalt unter die Definition des TBM eingeordnet wird.
- **Obersatz** — Erster Schritt der Vier-Schritt-Subsumtion; nennt die Norm und die daran geknuepfte Rechtsfolge.
- **Anspruchskonkurrenz** — Mehrere Normen begruenden nebeneinander denselben Anspruch; jede wird selbstaendig geprueft.
- **Sekundaere Darlegungslast** — Erleichterung der Beweislast der beweispflichtigen Partei, wenn die andere Partei Tatsachen aus ihrem Bereich klaeren koennte.
- **Anwendungsvorrang** — Europarecht geht im Kollisionsfall nationalem Recht vor; nationales Recht wird verdraengt, nicht nichtig.
- **Vorabentscheidungsverfahren** — Verfahren nach Art. 267 AEUV: nationale Gerichte legen dem EuGH Auslegungsfragen des Unionsrechts vor.

## Rechtsgrundlagen

- §§ 195 ff. BGB — Verjaehrung
- §§ 241 ff. BGB — Schuldrecht (Pflichten, Stoerungen)
- §§ 355 ff. ZPO — Beweisrecht
- Art. 267 AEUV — Vorabentscheidungsverfahren EuGH
- Art. 51 ff. GRCh — Anwendungsbereich und Schranken der Grundrechtecharta
- § 138 BGB — Sittenwidrigkeit (Generalklausel)
- § 242 BGB — Treu und Glauben (Generalklausel)
- Art. 103 Abs. 2 GG — Analogieverbot im Strafrecht

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Handelt es sich um eine Rechtsfrage, einen Lebenssachverhalt, eine konkrete Norm oder eine Mischung?
2. Phase des Mandats bestimmen: Normensuche, Tatbestandsanalyse, Subsumtion, Rechtsfolge oder Output-Erstellung.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: Verjaehrungsfristen (§ 195 BGB), prozessuale Notfristen.
5. Anschluss-Skill bestimmen: nach Subsumtion typischerweise Rechtsfolge bestimmen und dann Output-Skill auswaehlen.

## Skill-Tour (was gibt es hier?)

**Einstieg und Triage**

- `triage-rechtsfrage-oder-norm` — Interaktiver Einstieg; erfasst ob ein Sachverhalt, eine Rechtsfrage oder eine Norm vorliegt und leitet weiter.
- `ziel-und-rechtsweg-bestimmung` — Ermittelt Nutzerziel (Anspruchsdurchsetzung, Abwehr, Antrag) und leitet den einschlaegigen Rechtsweg ab.
- `verfahrensart-bestimmen` — Bestimmt die passende Verfahrensart: ZPO, einstweilig, Mahnverfahren, VwGO, StPO und andere.

**Normensuche**

- `einschlaegige-normen-vorschlagen-de` — Schlaegt einschlaegige Normen des deutschen Rechts zu einem Lebenssachverhalt vor.
- `einschlaegige-normen-vorschlagen-eu` — Schlaegt einschlaegige Normen des Unionsrechts vor mit EuGH-Judikatur und curia-Fundstellen.
- `de-eu-recht-abgrenzung` — Klaert wann nationales Recht und wann Unionsrecht unmittelbar gilt oder richtlinienkonforme Auslegung greift.
- `eu-vorabentscheidung-pruefen` — Prueft Voraussetzungen des Vorabentscheidungsersuchens nach Art. 267 AEUV.
- `norm-historie-und-aenderungen` — Prueft Norm-Geltungsfassung, Uebergangsvorschriften und intertemporales Recht.

**Tatbestandsanalyse**

- `norm-zerlegen-in-tatbestandsmerkmale` — Zerlegt eine Norm systematisch in TBM mit Definitionen und Pruefungsreihenfolge.
- `unbestimmte-rechtsbegriffe-pruefen` — Prueft unbestimmte Rechtsbegriffe mit Auslegungsmasssstaeben und Fallgruppen aus Rechtsprechung.
- `ungeschriebene-merkmale-judikatur` — Identifiziert judicativ entwickelte ungeschriebene TBM, Verkehrspflichten und teleologische Reduktion.
- `generalklauseln-pruefen` — Prueft Generalklauseln (§ 242 BGB, § 138 BGB) mit Indizien und Fallgruppen.
- `grundrechte-pruefung-de-und-grch` — Prueft Grundrechte nach GG und GRCh im Drei-Schritt: Schutzbereich, Eingriff, Rechtfertigung.
- `falsche-wiese-warnung` — Warnt vor typischen Falschverortungen (Vertrag statt Delikt, Verwaltungsakt vs. Realakt usw.).

**Subsumtion**

- `subsumtion-obersatz-definition-untersatz-ergebnis` — Fuehrt den klassischen Vier-Schritt je TBM durch.
- `beweisbedarf-und-belege-erfassen` — Erfasst pro TBM den Beweisbedarf mit Beweismittel-Katalog und Belegen.
- `darlegungs-und-beweislast-verteilen` — Verteilt Darlegungs- und Beweislast nach Grundregel, Beweislastumkehr und Anscheinsbeweis.
- `verjaehrung-fristen-pruefen` — Prueft Verjaehrungsfristen inklusive Hemmung, Neubeginn und EU-Verjaehrungsregeln.

**Gegenrechte und Rechtsfolgen**

- `gegen-tbm-und-einreden-pruefen` — Prueft rechtshindernde, rechtsvernichtende und rechtshemmende Einwendungen und Einreden.
- `konkurrenzen-anspruchsgrundlagen` — Klaert Anspruchskonkurrenz, Spezialitaet, Subsidiaritaet und Verhaeltnis Vertrags- zu Deliktsrecht.
- `rechtsfolge-bestimmen` — Bestimmt Anspruchsinhalt, Hoehe, Tenor und Nebenforderungen nach erfolgreicher Subsumtion.

**Output und Recherche**

- `output-juristisch-gestochen-de` — Ausgabe im juristischen Schriftsatzstil mit BGH-konformer Zitierweise.
- `output-memo-und-mandantenbrief` — Erstellt Aktennotiz oder Mandantenbrief mit Pflicht-Haftungshinweis.
- `output-alltagssprache-de` — Gibt Subsumtionsergebnis in verstaendlicher Alltagssprache ohne Fachbegriffe aus.
- `output-antrag-beschwerde-klageschrift` — Erzeugt Tenor-Bausteine und Pflichtangaben fuer Klageschriften und Beschwerden.
- `output-fremdsprachig-en-fr` — Ausgabe auf Englisch oder Franzoesisch mit Hinweis auf nicht-amtliche Uebersetzung.
- `output-pruefungsdokument-mit-warnhinweisen` — Vollstaendiges Pruefungsdokument mit Pflicht-Kopfhinweis und Disclaimern.
- `rechtsprechung-recherche-strategie` — Strategie fuer die Rechtsprechungsrecherche mit Fundstellen-Hinweisen.
- `kommentar-und-literatur-hinweis` — Weist auf Standardkommentare (Palandt, MueKomm, Staudinger usw.) hin.

**Eskalation**

- `mandatsabbruch-empfehlung-an-fachanwalt` — Erkennt Komplexitaetsgrenzen und empfiehlt Weiterleitung an Fachanwalt, Notar oder Behoerde.

## Worauf besonders achten

- **Disclaimer ist Pflicht.** Alle Ausgaben enthalten den Hinweis, dass es sich um mechanische Pruefung handelt, kein Rechtsgutachten und kein Rechtsrat.
- **Normen koennen veraendert sein.** Immer Skill `norm-historie-und-aenderungen` konsultieren, wenn der Geltungszeitpunkt unklar ist.
- **Generalklauseln und unbestimmte Rechtsbegriffe sind fehleranfaellig.** Automatisierte Subsumtion bei § 242 BGB und aehnlichen Normen immer mit Vorbehalt behandeln.
- **Anspruchskonkurrenz nicht vergessen.** Mehrere Anspruchsgrundlagen koennen nebeneinander greifen; jede separat pruefen.
- **Vorabentscheidungspflicht letzter Instanz.** Bei EU-Rechtsfragen vor dem BGH oder BVerwG besteht ggf. Vorlagepflicht; Skill `eu-vorabentscheidung-pruefen` einschalten.

## Typische Fehler

- Sachverhalt wird direkt unter Normen subsumiert ohne vorherige Zerlegung in TBM; fuehrt zu Subsumtionsspruengen.
- Einreden und Einwendungen werden vergessen; geprueft wird nur die anspruchsbegruendende Seite.
- Verjaehrung wird als gegeben angenommen ohne Pruefung von Hemmungstatbestaenden (§§ 203 ff. BGB).
- Deutsches Recht wird angewendet obwohl Unionsrecht Anwendungsvorrang hat; Skill `de-eu-recht-abgrenzung` hilft.
- Output wird ohne Pflicht-Disclaimer weitergegeben; das koennte als Rechtsberatung missverstanden werden.

## Querverweise

- `jurastudium` — Fuer Studium und Examensvorbereitung: Gutachtenstil, Lösungsschemata, Subsumtionsuebungen.
- `verfassungsrecht` — Fuer vertiefte Grundrechts- und Verfassungsmaessigkeitspruefungen.
- `gesellschaftsrecht` — Fuer gesellschaftsrechtliche Tatbestaende im Rahmen der Subsumtion.
- `mietrecht` — Wenn die subsumierte Norm aus dem Mietrecht (BGB §§ 535 ff.) stammt.
- `insolvenzforderungsanmeldungspruefung` — Wenn Insolvenzforderungen rechtlich geprueft und subsumiert werden sollen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum (BGB, HGB, StGB, ZPO, VwGO, GG, AEUV, GRCh)
- Rechtsprechungsdatenbanken: bundesgerichtshof.de, bundesverfassungsgericht.de, curia.europa.eu, dejure.org

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
