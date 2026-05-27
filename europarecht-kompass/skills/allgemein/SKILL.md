---
name: allgemein
description: "Einstieg und Orientierung im Europarecht-Kompass-Plugin. Klaert Vorrang, unmittelbare Wirkung, Richtlinien, Verordnungen, Grundfreiheiten, Charta, Beihilfen, Vorabentscheidung und typische deutsche Denkfehler im EU-Recht."
---

# Europarecht-Kompass — Allgemein

## Worum geht es?

Dieses Plugin korrigiert typische deutsche Denkfehler im Umgang mit EU-Recht und unterstuetzt Anwaelte, Berater und Behoerden bei der systematischen Bearbeitung europarechtlicher Mandate. Es deckt die Kernbereiche des EU-Primaerrechts (AEUV, EUV, GRC) und des Sekundaerrechts (Verordnungen, Richtlinien, Beschluesse, Soft Law) ab.

Schwerpunkte sind: Vorrangprinzip und unmittelbare Wirkung, Richtlinienumsetzung und -konforme Auslegung, Grundfreiheiten des Binnenmarkts, EU-Grundrechtecharta, Beihilfen- und Vergaberecht, Vorlageverfahren nach Art. 267 AEUV, Klagearten vor EuGH und EuG sowie effektiver nationaler Rechtsschutz. Das Plugin richtet sich ausdrucklich gegen die Tendenz, EU-Recht durch nationale Brillen zu lesen.

## Wann brauchen Sie diese Skill?

- Ein nationales Gericht oder eine Behoerde wendet nationales Recht an, das moeglicherweise EU-Recht widerspricht.
- Sie wollen pruefen, ob eine EU-Richtlinie in Deutschland korrekt umgesetzt wurde oder ob ein Umsetzungsdefizit besteht.
- Sie begleiten ein Unternehmen mit grenzueberschreitender Taetigkeit und muessen Grundfreiheitsverstoss pruefen.
- Ein nationales Gericht steht vor der Frage, ob es den EuGH nach Art. 267 AEUV anrufen muss.
- Sie arbeiten ein EU-Rechtsgutachten oder einen Schriftsatz und wollen es vor Versand auf typische Fehler pruefen.

## Fachbegriffe (kurz erklaert)

- **Vorrang des EU-Rechts** — EU-Recht geht nationalem Recht vor; entgegenstehendes nationales Recht ist unanwendbar (Costa v. ENEL, EuGH 1964).
- **Unmittelbare Wirkung** — EU-Normen koennen Rechte und Pflichten fuer Einzelne begruenden, ohne nationalem Umsetzungsrecht zu beduerfan (Van Gend en Loos, EuGH 1963); Richtlinien nur vertikal unmittelbar wirksam.
- **Richtlinienkonforme Auslegung** — Nationales Recht ist so weit wie moeglich im Licht des Wortlauts und Zwecks der Richtlinie auszulegen.
- **Francovich-Staatshaftung** — Mitgliedstaat haftet fuer Schaden durch fehlerhafte oder ausgebliebene Richtlinienumsetzung.
- **Vorlagepflicht** — Letztinstanzliche Gerichte muessen EU-Rechtsfragen dem EuGH vorlegen (Art. 267 Abs. 3 AEUV); Ausnahme: acte-clair-Doktrin.
- **Grundfreiheiten** — Warenverkehr (Art. 34 AEUV), Personenfreizuegigkeit (Art. 45 AEUV), Niederlassungsfreiheit (Art. 49 AEUV), Dienstleistungsfreiheit (Art. 56 AEUV), Kapitalverkehr (Art. 63 AEUV).
- **Art. 51 GRC** — EU-Grundrechtecharta gilt nur, wenn Mitgliedstaat EU-Recht vollzieht oder im Anwendungsbereich des EU-Rechts handelt.
- **Beihilfeverbot** — Art. 107 AEUV verbietet staatliche Beihilfen, die den Wettbewerb verfaelschen; notifizierungspflichtig bei Kommission.

## Rechtsgrundlagen

- Art. 267 AEUV — Vorlageverfahren; Vorabentscheidung des EuGH.
- Art. 258 und 260 AEUV — Vertragsverletzungsverfahren der Kommission.
- Art. 263 und 265 AEUV — Nichtigkeitsklage und Untaetigkeitsklage vor EuGH/EuG.
- Art. 288 AEUV — Rechtsquellen: Verordnung, Richtlinie, Beschluss, Empfehlung.
- Art. 289 und 294 AEUV — Ordentliches Gesetzgebungsverfahren und Trilog.
- Art. 290 und 291 AEUV — Delegierte Rechtsakte und Durchfuehrungsrechtsakte.
- Art. 34 und 36 AEUV — Warenverkehrsfreiheit und Rechtfertigungsgruende.
- Art. 51 und 52 GRC — Anwendungsbereich und Schranken der EU-Grundrechtecharta.
- Art. 107 und 108 AEUV — Beihilfeverbot und Notifizierungspflicht.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandat aufgleisen: Skill `europarecht-kommandocenter` fuer EU-Rechtsbezug, Rechtsgebiet und Route.
2. Deutschen Denkfehler ausschliessen: `europarecht-deutscher-denkfehler-scanner`.
3. Rechtsquelle einordnen: `europarecht-verordnung-beschluss-soft-law` oder `europarecht-richtlinie-umsetzung`.
4. Materielles Rechtsproblem pruefen: Grundfreiheiten, Charta, Beihilfen, Kartell je nach Mandat.
5. Verfahren bestimmen: Vorlage, Klage, Vertragsverletzung, Simulation je nach Konstellation.

## Skill-Tour (was gibt es hier?)

**Einstieg und Qualitaetssicherung**

- `europarecht-kommandocenter` — Rechtsgebiet bestimmen, relevante Normen identifizieren, Bearbeitungsroute festlegen.
- `europarecht-deutscher-denkfehler-scanner` — Typische deutsche Fehler im EU-Recht erkennen und korrigieren.
- `europarecht-quality-gate` — EU-Rechtsgutachten oder Schriftsatz auf Fehler und Luecken pruefen.
- `europarecht-mandantenmemo` — Mandantenmemo zu EU-Rechtsfragen praxisorientiert verfassen.

**Rechtsquellen und Normenhierarchie**

- `europarecht-vorrang-unmittelbare-wirkung` — Vorrang des EU-Rechts und unmittelbare Wirkung von EU-Normen pruefen.
- `europarecht-richtlinie-umsetzung` — Umsetzungsdefizit pruefen, Direktwirkung, richtlinienkonforme Auslegung, Francovich.
- `europarecht-verordnung-beschluss-soft-law` — Verordnungen, Beschluesse und Soft-Law einordnen und Verbindlichkeit pruefen.
- `europarecht-delegierte-durchfuehrungsakte` — Delegierte Rechtsakte und Durchfuehrungsrechtsakte einordnen.

**Grundfreiheiten und Grundrechte**

- `europarecht-grundfreiheiten-binnenmarkt` — Grundfreiheiten pruefen bei grenzueberschreitender Taetigkeit oder nationaler Beschraenkung.
- `europarecht-grundrechte-charta` — EU-Grundrechtecharta anwenden; Anwendungsbereich Art. 51 GRC.

**Wettbewerb und Beihilfen**

- `europarecht-wettbewerb-kartell` — Kartell- und Wettbewerbsrecht nach Art. 101 und 102 AEUV.
- `europarecht-beihilfen-vergaben` — Beihilfenrecht Art. 107 und 108 AEUV und Vergaberecht §§ 97 ff. GWB.

**Verfahren vor EuGH und nationalem Gericht**

- `europarecht-vorlageverfahren-art-267` — Vorabentscheidungsersuchen nach Art. 267 AEUV vorbereiten oder Vorlagepflicht pruefen.
- `europarecht-klagearten-eugh` — Klagemoeglichkeiten vor EuGH und EuG; Nichtigkeitsklage, Untaetigkeit, Schadensersatz.
- `europarecht-vertragsverletzung-durchsetzung` — Vertragsverletzungsverfahren einordnen und Reaktion vorbereiten.
- `europarecht-nationales-verfahren-effektivitaet` — Effektivitaets- und Aequivalenzgrundsatz im nationalen Verfahren.
- `europarecht-simulation-behoerde-gericht` — Argumentation vor EU-Behoerde oder nationalem Gericht simulieren.

**Gesetzgebung**

- `europarecht-gesetzgebung-trilog` — EU-Gesetzgebungsverfahren und Trilog-Verhandlungen einordnen.

## Worauf besonders achten

- **Richtlinie ist kein Gesetz** — Eine nicht umgesetzte Richtlinie wirkt nur vertikal (gegen den Staat), nicht horizontal zwischen Privaten; die direkte Anwendbarkeit gegenueber Privaten ist kein Automatismus.
- **Vorlagepflicht ernst nehmen** — Letztinstanzliche Gerichte muessen vorlegen; die acte-clair-Doktrin ist eng auszulegen; Ablehnung ohne Vorlagepruefung ist ein Verfahrensfehler.
- **GRC-Anwendungsbereich pruefen** — Die EU-Grundrechtecharta gilt nicht bei rein nationalem Sachverhalt; Art. 51 GRC ist Anwendungsvoraussetzung, nicht Option.
- **Beihilfe: Notifizierung vor Auszahlung** — Nicht notifizierte Beihilfen koennen zurueckgefordert werden; der Vertrauensschutz des Beguenstigten ist eng.
- **Soft Law und Durchfuehrungsrechtsakte unterscheiden** — Empfehlungen und Leitlinien sind nicht verbindlich, haben aber Auslegungsrelevanz; delegierte Rechtsakte und Durchfuehrungsrechtsakte hingegen sind verbindlich.

## Typische Fehler

- Richtlinienkonforme Auslegung wird nicht versucht, obwohl das nationale Recht noch Auslegungsspielraum laesst.
- Vorlage nach Art. 267 AEUV wird verweigert, obwohl acte-clair-Kriterien nicht erfullt sind.
- GRC wird angewendet, obwohl kein EU-Recht vollzogen wird (rein nationaler Sachverhalt).
- Beihilfe wird ausgezahlt, ohne Notifizierungspflicht nach Art. 108 Abs. 3 AEUV zu pruefen.
- Delegierter Rechtsakt und Durchfuehrungsrechtsakt werden verwechselt, was zu falschen Widerrufsfristen fuehrt.

## Querverweise

- `dsa-dma-digitalregulierung` — Fuer DSA und DMA als EU-Rechtsakte mit spezifischen Pflichten.
- `kartellrecht-marktabgrenzung-pruefung` — Fuer vertiefte kartellrechtliche Marktabgrenzung.
- `normenkontrolle-bauleitplanung` — Bei FFH- oder Vogelschutz-Richtlinienkonflikten im Baurecht.

## Quellen und Aktualitaet

- Stand: 05/2026
- AEUV und EUV in der geltenden Fassung
- GRC (EU-Grundrechtecharta) in der geltenden Fassung
- EuGH-Rechtsprechung bis 05/2026

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
