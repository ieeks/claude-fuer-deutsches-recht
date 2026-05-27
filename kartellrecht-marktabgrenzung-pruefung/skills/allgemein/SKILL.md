---
name: allgemein
description: "Einstieg und Orientierung im Kartellrecht-Marktabgrenzungs-Pruefer-Plugin. Klaert Verfahrenskontext, SSNIP-Test, Nachfrage- und Angebotsumstellung, raeumlicher Markt, Beherrschungspruefung und Routing zu allen 24 Spezial-Skills."
---

# Kartellrecht-Marktabgrenzungs-Pruefer — Allgemein

## Worum geht es?

Dieses Plugin ist die kritische Pruefinstanz fuer vorgelegte Marktabgrenzungen in kartellrechtlichen Verfahren. Es prueft Marktabgrenzungen nach § 18 GWB sowie Art. 101 und 102 AEUV — unabhaengig davon, ob es sich um Fusionskontrollverfahren, Missbrauchsverfahren oder Kartellverbotsverfahren handelt.

Das Plugin orientiert sich an der EU-Bekanntmachung zur Marktdefinition von Februar 2024 (ABl. 2024/C 1645), an der Rechtsprechung des EuGH und EuG sowie an der Praxis des BKartA. Es identifiziert systematisch methodische Schwachstellen, selektive Datenwahl, Zirkelschluesse und alternative Marktdefinitionen, die prozessual oder behoerdlich angreifbar sind.

## Wann brauchen Sie diese Skill?

- Sie pruefen eine von der Gegenseite oder einer Behoerde vorgelegte Marktabgrenzung auf Angreifbarkeit.
- Sie erstellen eine eigene Marktabgrenzungsargumentation fuer ein Fusionskontroll-, Missbrauchs- oder Kartellverfahren.
- Sie begleiten ein BKartA- oder Kommissionsverfahren und muessen den Verfahrenskontext und die Parteistellung klaeren.
- Sie pruefen, ob eine DMA-Gatekeeper-Designation kartellrechtlich relevante Marktdefinitionen verschiebt.
- Sie wollen die Qualitaet und Belastbarkeit oekonomischer Gutachten zu Elastizitaeten oder Diversion Ratios beurteilen.

## Fachbegriffe (kurz erklaert)

- **SSNIP-Test** — Hypothetischer-Monopolisten-Test (Small but Significant Non-transitory Increase in Price): Klaert, welche Produkte und Regionen so nah substituierbar sind, dass ein Monopolist keinen profitablen Preisaufschlag von 5 bis 10 Prozent erzielen koennte.
- **Nachfragesubstitution** — Kernschritt der Marktabgrenzung: Welche Produkte wechseln Nachfrager bei einem kleinen Preisanstieg? Bestimmt den sachlichen Markt.
- **Angebotsumstellung** — Supply-Side-Substitution: Koennen andere Anbieter kurzfristig und ohne erhebliche Kosten auf den relevanten Markt wechseln?
- **Marktbeherrschung** — Erheblicher Wettbewerbsdruck fehlt; Vermutung bei 40-Prozent-Einzelmarktanteil nach § 18 Abs. 4 GWB.
- **Cellophane-Fallacy** — Methodischer Fehler beim SSNIP-Test: Pruefung von der bereits ueberhoeahten Marktmacht-Position aus fuehrt zu kuenstlich weitem Markt.
- **Inkongruente Deckung** — Begriff aus dem Anfechtungsrecht; hier nicht relevant.
- **Diversion Ratio** — Oekonomisches Mass fuer den Anteil der Nachfrage, der bei einem Preisanstieg zu einem bestimmten Wettbewerber abwandert; hohe Ratio spricht fuer engen Markt.
- **Gatekeeper** — Designierter Plattformbetreiber nach DMA; Designation beeinflusst kartellrechtliche Marktdefinition in parallelen Verfahren.

## Rechtsgrundlagen

- § 18 GWB — Marktbeherrschung, Marktanteils-Vermutungen, Plattformen.
- § 19 GWB — Missbrauch marktbeherrschender Stellung.
- § 20 GWB — Relative Marktmacht.
- § 35 GWB und FKVO 139/2004 — Fusionskontrolle und SIEC-Test.
- Art. 101 AEUV — Kartellverbot.
- Art. 102 AEUV — Missbrauchsverbot.
- EU-Bekanntmachung zur Marktdefinition 2024 (ABl. 2024/C 1645) — Methodischer Rahmen.
- DMA (VO 2022/1925) Art. 2 und 3 — Kernplattformdienste und Gatekeeper-Designation.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Verfahrenskontext und Parteistellung klaeren: Skill `marktabgrenzung-kontextanalyse`.
2. Verfahrensmodus auswaehlen: `fusionskontrolle-modus`, `missbrauchsverbot-modus` oder `kartellverbot-modus`.
3. Sachlichen Markt pruefen: `produktmarkt-nachfragesubstitution` und `produktmarkt-angebotsumstellung`.
4. Raeumlichen Markt pruefen: `raeumlicher-markt-abgrenzung`.
5. Marktanteile und Beherrschung bewerten: `auswirkungen-marktanteile-marktbeherrschung` und `paragraf-18-gwb-pruefung`.
6. Gesamturteil und Angreifbarkeit: `gesamtbewertung-tragfaehigkeit`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Kontext**

- `marktabgrenzung-kontextanalyse` — Verfahrensart und Zielrichtung bestimmen, Routing-Empfehlung.
- `fusionskontrolle-modus` — SIEC-Test, Phase I und II, horizontale und nicht-horizontale Fusionen.
- `missbrauchsverbot-modus` — Marktabgrenzung im Kontext von Art. 102 AEUV und § 19 GWB.
- `kartellverbot-modus` — Marktabgrenzung im Kontext von Art. 101 AEUV und § 1 GWB.

**Sachlicher Markt**

- `produktmarkt-nachfragesubstitution` — Sachlicher Markt aus Nachfragersicht; Kernschritt jeder Marktabgrenzung.
- `produktmarkt-angebotsumstellung` — Angebotsseitige Substitution; kurzfristiger Marktzutritt anderer Anbieter.
- `ssnip-test-anwendung` — SSNIP-Test (Hypothetischer-Monopolisten-Test) anwenden.
- `elastizitaeten-diversion-ratios` — Belastbarkeit oekonomischer Elastizitaetsdaten und Diversion-Ratio-Analysen pruefen.

**Raeumlicher Markt**

- `raeumlicher-markt-abgrenzung` — Raeumlich relevanter Markt: national, europaeisch oder global.

**Spezialmaerkte**

- `cluster-und-systemmaerkte` — Cluster-Maerkte und Aftermarket-Doktrin (Pelikan-Doktrin, Kyocera-Doktrin).
- `mehrseitige-maerkte-plattformen` — Zweiseitige Marktdefinition, indirekte Netzwerkeffekte, Plattform-Spezifika.
- `innovations-und-technologiemaerkte` — Innovationsmaerkte, SEPs, FuE-Maerkte in dynamischen Technologiesektoren.
- `dma-und-gatekeeper-markt` — DMA-Gatekeeper-Designation und Auswirkungen auf Marktdefinition.

**Marktanteile und Beherrschung**

- `paragraf-18-gwb-pruefung` — Marktbeherrschung nach § 18 GWB: Einzelbeherrschung, Schwellen, gemeinsame Beherrschung.
- `auswirkungen-marktanteile-marktbeherrschung` — Sensitivitaetsanalyse Marktanteil je Marktabgrenzungs-Szenario.
- `potenzieller-wettbewerb-marktzutritt` — Markteintrittsbarrieren und potenzieller Wettbewerb im Zeitrahmen zwei bis drei Jahre.

**Alternative Marktdefinitionen**

- `alternative-marktdefinition-eng` — Engere Marktdefinition argumentieren fuer niedrigere Marktanteile.
- `alternative-marktdefinition-weit` — Weitere Marktdefinition argumentieren gegen Beherrschungsvermutung.

**Evidenz und Qualitaet**

- `evidenz-qualitaet-bewertung` — Qualitaet und Belastbarkeit der Belege fuer eine Marktabgrenzung beurteilen.
- `eu-bekanntmachung-marktdefinition-2024` — Neue EU-Bekanntmachung Februar 2024 und Vergleich zur Bekanntmachung von 1997.
- `eugh-rechtsprechung-leitentscheidungen` — EuGH/EuG/BGH/BKartA-Leitentscheidungen zur Marktdefinition.

**Konsistenz und Gesamturteil**

- `konsistenzpruefung-marktdefinition` — Interne Widerspruchsfreiheit einer Marktabgrenzung pruefen.
- `red-flags-checkliste` — Problematische Muster in Marktabgrenzungen: ergebnisgetriebene Argumentation, Zirkelschluesse.
- `gesamtbewertung-tragfaehigkeit` — Gesamturteil zur Tragfaehigkeit; Angreifbarkeit und Prozesstaktik.

## Worauf besonders achten

- **Verfahrenskontext bestimmt Marktdefinition** — Die Richtung der Marktabgrenzungsargumentation haengt davon ab, ob Mandant Klaeger, Beklagter oder Zusammenschlusspartei ist; `marktabgrenzung-kontextanalyse` immer zuerst.
- **Cellophane-Fallacy** — Beim SSNIP-Test immer pruefen, ob Ausgangspreis bereits Marktmacht-Preis ist; Fehler fuehrt zu kuenstlich weitem Markt.
- **EU-Bekanntmachung 2024** — Seit Februar 2024 gelten neue Methodik-Standards fuer digitale Maerkte und Innovationswettbewerb; aeltere Marktabgrenzungen koennen veraltet sein.
- **DMA-Designation nicht gleichsetzen** — Eine DMA-Gatekeeper-Designation ist kein kartellrechtlicher Marktbeherrschungs-Befund; die Rechtsfragen sind trennbar.
- **Potenzielle Anbieter nicht uebergewichten** — Markteintrittsbarrieren muessen realistisch im Zeitfenster zwei bis drei Jahre bewertet werden; bloss theoretische Marktzutrittsmoeoglichkeit genuegt nicht.

## Typische Fehler

- Nachfragesubstitution und Angebotsumstellung werden verwechselt oder zusammengeworfen.
- SSNIP-Test wird ohne Cellophane-Fallacy-Pruefung auf einem bereits durch Marktmacht verzerrten Preisniveau angewendet.
- Leitentscheidungen werden ohne Pinpoint-Zitat zitiert und koennen prozessual nicht verwertet werden.
- Alternative Marktdefinitionen werden nicht erwaehnt, obwohl sie die Anteilsschwellen verschieben wuerden.
- Raeumlicher und sachlicher Markt werden nicht aufeinander abgestimmt (Konsistenzbruch).

## Querverweise

- `europarecht-kompass` — Fuer allgemeine EU-Rechtsfragen, Vorlagenverfahren und EU-Verfahrensrecht.
- `dsa-dma-digitalregulierung` — Fuer DMA-Gatekeeper-Pflichten und DSA-Fragen parallel zum Kartellrecht.
- `insolvenzplan-starug-planwerkstatt` — Bei Restrukturierungen mit kartellrechtlich relevantem Marktaustritt.

## Quellen und Aktualitaet

- Stand: 05/2026
- GWB §§ 18 ff. in der geltenden Fassung
- Art. 101 und 102 AEUV
- EU-Bekanntmachung zur Marktdefinition 2024 (ABl. 2024/C 1645)
- FKVO 139/2004 in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
