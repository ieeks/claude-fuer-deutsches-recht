---
name: allgemein
description: "Einstieg und Orientierung im DSA-DMA-Digitalregulierung-Plugin. Klaert welches EU-Digitalregulierungsregime greift (DSA, DMA, Data Act, AI Act, NIS-2, DORA, CRA, eIDAS 2.0, DDG, P2B-VO, Paragraf 19a GWB) und Routing zu allen 9 Spezial-Skills."
---

# DSA DMA und Digitalregulierung EU — Allgemein

## Worum geht es?

Dieses Plugin ist der strukturierte Einstiegspunkt fuer die EU-Digitalregulierung. Es hilft dabei, den richtigen Rechtsakt fuer einen konkreten Sachverhalt zu identifizieren und die jeweils zustaendige Pflichtenmatrix zu aktivieren. Die EU-Digitalregulierung besteht aus einem dichten Regelwerk, das sich nach Akteurstyp, Dienst-Typ, Datentyp und Risikoklasse staffelt: Digital Services Act (DSA, VO 2022/2065), Digital Markets Act (DMA, VO 2022/1925), Data Act (VO 2023/2854), Data Governance Act (DGA), AI Act (VO 2024/1689), NIS-2, DORA, CRA, eIDAS 2.0, Digitale-Dienste-Gesetz (DDG), P2B-VO und § 19a GWB.

Das Plugin richtet sich an Anwaelte, Compliance-Verantwortliche und Unternehmensjuristen, die mit der Pflichtendichte der EU-Digitalregulierung umgehen muessen. Es ist kein Rechtsberatungsersatz.

## Wann brauchen Sie diese Skill?

- Unternehmen fragt, ob es als VLOP (sehr grosse Online-Plattform) oder VLOSE (sehr grosse Suchmaschine) nach DSA einzustufen ist.
- Plattformbetreiber moechte wissen, ob eine DMA-Gatekeeper-Designation droht und welche Pflichten folgen.
- Nutzer oder Unternehmen wurde von einer Plattform gesperrt und will die DSA-Beschwerdewege nutzen.
- Anwalt muss feststellen, welche von mehreren EU-Digitalakten auf einen Sachverhalt gleichzeitig anwendbar sind.
- Grossplattform muss eine Risikobewertung nach Art. 34 DSA dokumentieren oder Forschungsdatenzugang nach Art. 40 DSA einrichten.

## Fachbegriffe (kurz erklaert)

- **DSA (Digital Services Act)** — EU-Verordnung 2022/2065; regelt Haftung und Pflichten von Vermittlungsdiensten, Online-Plattformen, VLOP und VLOSE.
- **DMA (Digital Markets Act)** — EU-Verordnung 2022/1925; regelt Pflichten fuer Gatekeeper bei Kernplattformdiensten.
- **VLOP** — Sehr grosse Online-Plattform nach Art. 33 DSA; Designierungsschwelle 45 Mio. monatlich aktive Nutzer in der EU.
- **Gatekeeper** — Designierter Kernplattformdienst-Betreiber nach Art. 3 DMA; quantitative Schwellen und qualitative Designierung durch die Kommission.
- **Kernplattformdienste** — Abschliessender Katalog in Art. 2 Nr. 2 DMA: soziale Netzwerke, App-Stores, Suchmaschinen, Werbenetzwerke usw.
- **Systemisches Risiko** — Art. 34 DSA: VLOPs muessen jaehrlich vier Risikoarten bewerten (illegale Inhalte, Grundrechte, Diskurs/Wahlen, Minderjaerige).
- **P2B-VO** — Plattform-zu-Business-Verordnung (VO 2019/1150); regelt Bedingungen in Handelsbeziehungen zwischen Plattformen und gewerblichen Nutzern.
- **DDG** — Digitale-Dienste-Gesetz; nationales Ausfuehrungsgesetz zum DSA in Deutschland.

## Rechtsgrundlagen

- DSA (EU) 2022/2065 — Digital Services Act; insb. Art. 13 (Vertreter), Art. 17 (Begruendungspflicht), Art. 20-23 (Beschwerdesystem), Art. 33-43 (VLOP-Pflichten).
- DMA (EU) 2022/1925 — Digital Markets Act; insb. Art. 2-3 (Gatekeeper), Art. 5-7 (Pflichten), Art. 37 (Vertreter).
- Art. 263 Abs. 4 AEUV — Nichtigkeitsklage gegen Designierungsbeschluss.
- P2B-VO (EU) 2019/1150 — Plattform-Nutzer-Beziehungen.
- § 19a GWB — Unterhalb DMA-Schwellen: ergaenzende nationale Regulierung besonders marktmaechtiger Unternehmen.
- DDG §§ 1 ff. — Nationales Ausfuehrungsrecht zum DSA.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Sachverhalt einordnen: Skill `digitalregulierung-pyramide-check` fuer die richtige Regulierungsebene.
2. Schnittstellen identifizieren: `digitalregulierung-schnittstellen-dsgvo-p2b-19a-gwb` bei Mehrrechtsakten.
3. Spezifischen Pflichtenkatalog aktivieren: VLOP-Check, Gatekeeper-Check, Account-Sperre oder Forschungsdatenzugang.
4. Verfahren und Klagewege klaren: Beschwerde, Klage oder Zustellungsfragen.
5. Eilrechtsschutz pruefen bei Sperren oder Designierungsbeschluessen.

## Skill-Tour (was gibt es hier?)

**Einstieg und Triage**

- `digitalregulierung-pyramide-check` — Sachverhalt den richtigen EU-Digitalregulierungs-Rechtsakten zuordnen; Routing.
- `digitalregulierung-schnittstellen-dsgvo-p2b-19a-gwb` — Schnittstellen zwischen DSA/DMA und DSGVO, P2B-VO, § 19a GWB analysieren.

**DSA-spezifisch**

- `dsa-vlop-vlose-einordnung-und-pflichten` — VLOP/VLOSE-Einordnung und Pflichtenkatalog Art. 33 bis 43 DSA.
- `dsa-art-34-systemische-risikobewertung` — Jaehrliche Risikobewertung nach Art. 34 DSA fuer VLOP/VLOSE durchfuehren.
- `dsa-art-40-forschungsdatenzugang-algorithmen` — Forschungsdatenzugang nach Art. 40 DSA beantragen oder einrichten.
- `account-sperre-soziales-netzwerk-rechtsbehelfe-art-20-23-dsa` — Account-Sperre anfechten; Stufenmodell Art. 17-21 DSA; Klageschrift.

**DMA-spezifisch**

- `dma-gatekeeper-schwellen-und-kernplattformdienste` — Gatekeeper-Designation nach Art. 3 DMA pruefen; Pflichtenkatalog.

**Klagewege und Verfahren**

- `klage-gegen-vlop-einordnung-art-263-aeuv` — Nichtigkeitsklage gegen Designierungsbeschluss vor EuG.
- `zustellung-und-vertreter-art-13-dsa-art-37-dma` — Zustellung gegen Plattform mit Sitz ausserhalb der EU; EU-Vertreter-Pflichten.

## Worauf besonders achten

- **DSA und DMA sind parallel anwendbar** — Eine Plattform kann gleichzeitig VLOP (DSA) und Gatekeeper (DMA) sein; die Pflichten kumulieren sich.
- **Schwellenwerte sind dynamisch** — Meldepflicht nach Art. 24 Abs. 3 DSA bei Erreichen der Nutzerschwelle; Kommission designiert unabhaengig von Meldestand.
- **DSA verdraengt DSGVO nicht** — Art. 2 Abs. 4 DSA stellt klar, dass DSGVO vorgeht; DSA-Compliance schutzt nicht vor DSGVO-Bussgeld.
- **§ 19a GWB als Luecken-Fuelung** — Unterhalb DMA-Schwellen greift das BKartA auf § 19a GWB zurueck; Unternehmen muessen beide Ebenen im Blick haben.
- **Zustellung gegen auslaendische Plattformen** — EU-Vertreter-Pflicht nach Art. 13 DSA ist Voraussetzung fuer Zustellung; ohne Vertreter komplexes Auslandsverfahren.

## Typische Fehler

- DSA-Beschwerdepflicht nach Art. 20 DSA wird nicht ausgeschoepft, bevor Klage erhoben wird; Zulassigkeitsproblem.
- VLOP-Meldepflicht nach Art. 24 Abs. 3 DSA wird vergessen; Bussgeldrisiko.
- DMA-Gatekeeper-Designation wird mit kartellrechtlicher Marktbeherrschung gleichgesetzt; verschiedene Rechtsfragen.
- Nichtigkeitsklage nach Art. 263 AEUV wird verspaetet eingereicht; Zweimonatsfrist ab Designierungsbeschluss.
- Schnittstelle zu P2B-VO wird nicht geprueft, obwohl gewerbliche Nutzer betroffen sind.

## Querverweise

- `europarecht-kompass` — Fuer allgemeines EU-Verfahrensrecht (Art. 267 AEUV Vorlage, Klagearten EuGH).
- `kartellrecht-marktabgrenzung-pruefung` — Fuer kartellrechtliche Marktabgrenzung parallel zur DMA-Designation.
- `produktrecht` — Fuer produktrechtliche Pflichten bei digitalen Produkten und KI-VO-Schnittstellen.

## Quellen und Aktualitaet

- Stand: 05/2026
- DSA (EU) 2022/2065 in der geltenden Fassung
- DMA (EU) 2022/1925 in der geltenden Fassung
- P2B-VO (EU) 2019/1150 in der geltenden Fassung
- DDG in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
