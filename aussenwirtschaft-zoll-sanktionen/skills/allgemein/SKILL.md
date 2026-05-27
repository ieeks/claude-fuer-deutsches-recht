---
name: allgemein
description: "Einstieg und Ueberblick fuer das Aussenwirtschaft-Zoll-Sanktionen-Plugin: Exportkontrolle, Dual-Use, BAFA, TARIC, Zollverfahren, Sanktionen/Embargos, CBAM, AWV-Meldung, AML/KYC, ICP und Begleitung von Pruefungen und Ermittlungen fuer Aussenhandelsunternehmen."
---

# Aussenwirtschaft, Zoll und Sanktionen — Allgemein

## Worum geht es?

Das Plugin deckt das gesamte Aussenwirtschafts- und Zollrecht ab: von der Exportkontrolle fuer Dual-Use-Gueter und Ruestungsgueter ueber Sanktionen und Embargos bis hin zu Zolltarifrecht, Warenursprung, Praeferenznachweisen und dem Carbon Border Adjustment Mechanism (CBAM). Es begleitet Unternehmen beim Aufbau interner Compliance-Programme (ICP) und stuetzt Anwaelte und Compliance-Verantwortliche bei Behoerdenpruefungen und Strafverfahren.

Das Plugin integriert auch AWV-Meldepflichten gegenueber der Deutschen Bundesbank, AML/KYC-Sanktionsscreening, Antidumping sowie WTO-Handelspolitik. Zielgruppe sind Compliance-Abteilungen exportierender Unternehmen, Zollbeauftragte, Anwaelte und Steuerberater im Aussenhandel.

## Wann brauchen Sie diese Skill?

- Unternehmen exportiert Gueter mit potenziellem Dual-Use und muss pruefen, ob eine BAFA-Genehmigung erforderlich ist.
- Handelspartner steht auf Sanktionsliste oder hat Bezug zu embargierten Laendern; Transaktion muss vor Ausfuehrung geprueft werden.
- Zollbehoerde bestreitet Zollwert oder Warenursprung; Praeferenznachweis muss verteidigt werden.
- Unternehmen erhalt Ankuendigung einer Zollpruefung oder Aussenwirtschaftspruefung und muss Verfahrensvorbereitung treffen.
- CBAM-pflichtige Waren werden eingefuehrt; Zertifikatspflichten und CO2-Preisberechnungen muessen implementiert werden.

## Fachbegriffe (kurz erklaert)

- **Dual-Use** — Gueter, Software und Technologien mit ziviler und militaerischer Verwendungsmoeglichkeit; unterstehen der EG Dual-Use-Verordnung (VO (EG) 428/2009, jetzt VO (EU) 2021/821).
- **BAFA** — Bundesamt fuer Wirtschaft und Ausfuhrkontrolle; zentrale Genehmigungs- und Pruefungsbehoerde fuer Exportkontrolle.
- **Sanktionen / Embargos** — Wirtschaftliche Massnahmen der EU, UN oder USA gegen Laender oder Personen; Umgehung ist Straftat.
- **TARIC** — Integrierter Zolltarif der EU; kombiniert CN-Code mit handelspolitischen Massnahmen.
- **Zollwert** — Basis fuer die Berechnung der Eingangsabgaben; grundsaetzlich Transaktionswert nach UZK-Zollwertmethoden.
- **Warenursprung** — Praeferenzielle und nichtpraeferenzielle Herkunft einer Ware; Grundlage fuer Praeferenzzollsaetze und Antidumping.
- **CBAM** — Carbon Border Adjustment Mechanism; CO2-Grenzausgleich fuer Einfuhren aus Drittlaendern seit 01.10.2023 (Uebergangsphase).
- **ICP** — Internal Compliance Programme; strukturiertes internes Exportkontroll-Kontrollsystem nach BAFA-Anforderungen.
- **AWV** — Aussenwirtschaftsverordnung; regelt Meldepflichten gegenueber Bundesbank fuer grenzueberschreitende Zahlungen und Kapitalverkehr.
- **AEO** — Zugelassener Wirtschaftsbeteiligter; EU-weite Bewilligung fuer vereinfachte Zollverfahren und schnellere Abfertigung.

## Rechtsgrundlagen

- AWG — Aussenwirtschaftsgesetz
- AWV — Aussenwirtschaftsverordnung
- VO (EU) 2021/821 — Dual-Use-Verordnung
- UZK (VO (EU) 952/2013) — Unionszollkodex
- VO (EU) 2022/2449 — CBAM-Uebergangsverordnung
- GwG — Geldwaeschegesetz (AML/KYC)
- OFAC-Vorschriften (USA) — US-Sanktionsrecht (extraterritorial relevant)
- 15 CFR (EAR), 22 CFR (ITAR) — US-Exportkontrollrecht

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Exporteur, Importeur, Handelspartner-Sanktionspruefung oder Behoerdenverfahren?
2. Regulierungsrahmen bestimmen: EU-Recht, nationales AWG/AWV oder US-Recht (EAR/ITAR/OFAC) relevant?
3. Gueterklassifizierung pruefen: CN-Code, Dual-Use-Einstufung und Gueterlisten-Nummer festlegen.
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Fristen pruefen: BAFA-Antragsfristen, AWV-Meldefristen (sieben Werktage), CBAM-Quartalsberichte.

## Skill-Tour (was gibt es hier?)

- `aussenwirtschaft-kommandocenter` — Mandats-Intake und Routing fuer alle Aussenhandels- Zoll- Sanktions- und Ermittlungsmandate.
- `aussenwirtschaft-exportkontrolle-dual-use` — Dual-Use-Pruefung fuer Gueter, Software und Technologie mit Doppelverwendungszweck.
- `aussenwirtschaft-gueterlisten-klassifizierung` — Klassifizierungsdossier fuer Exportkontrolle, Zolltarif und Dual-Use-Einordnung erstellen.
- `aussenwirtschaft-bafa-genehmigungen` — BAFA-Genehmigungsverfahren fuer genehmigungs-pflichtige Exporte begleiten.
- `aussenwirtschaft-sanktionen-embargos` — Laenderembargos und personenbezogene Sanktionen pruefen; Umgehungsrisiken identifizieren.
- `aussenwirtschaft-aml-kyc-sanktionen` — GwG-Risikoanalyse, KYC-Pruefung und Sanktionsscreening im Aussenhandel verknuepfen.
- `aussenwirtschaft-zolltarif-vzta` — Wareneinreihung nach TARIC und verbindliche Zolltarifauskunft (VzTA) beantragen.
- `aussenwirtschaft-zollwert-ursprung` — Zollwert, Warenursprung, Praeferenznachweise und Lieferantenerklarungen klaeren und verteidigen.
- `aussenwirtschaft-zollverfahren-bewilligungen` — Zollverfahren nach UZK und Bewilligungen (AEO, vereinfachte Anmeldung) beantragen.
- `aussenwirtschaft-cbam-co2-zoll` — CBAM-Compliance: CO2-Grenzausgleich fuer Einfuhren berechnen und Zertifikatspflichten erfuellen.
- `aussenwirtschaft-awv-bundesbank` — AWV-Meldepflichten gegenueber Bundesbank fuer grenzueberschreitende Zahlungen umsetzen.
- `aussenwirtschaft-verbrauchsteuer` — Verbrauchsteuerrecht fuer Energie, Strom, Tabak und Alkohol im Aussenhandel.
- `aussenwirtschaft-vub-einfuhr-ausfuhr` — Verbote und Beschraenkungen (VuB) fuer besondere Waren: Dual-Use, CITES, F-Gase, Russland/Iran.
- `aussenwirtschaft-antidumping-ausgleich` — Antidumping- und Antisubventionsmassnahmen; Ausgleichszoelle pruefen und anfechten.
- `aussenwirtschaft-wto-handelspolitik` — WTO-Regelwerk, GATT/GATS/TRIPS und Streitbeilegung fuer Aussenhandelsmandate.
- `aussenwirtschaft-us-ear-itar` — US-Exportkontrolle EAR/ITAR und OFAC fuer Unternehmen mit US-Bezug oder US-Waren-Anteilen.
- `aussenwirtschaft-icp-kontrollsystem` — Internes Compliance-Programm (ICP) fuer Exportkontrolle, Zoll, Sanktionen und AML entwerfen.
- `aussenwirtschaft-pruefung-ermittlung` — Begleitung von Zollpruefungen, Aussenwirtschaftspruefungen, Durchsuchungen und Strafverfahren.
- `aussenwirtschaft-presse-krise` — Kommunikative und rechtliche Schadensbegrenzung bei Sanktionsverstoss oder oeffentlichem Vorwurf.

## Worauf besonders achten

- Dual-Use-Pruefung umfasst nicht nur physische Gueter, sondern auch Software, Technologieue und Know-how-Transfer (auch muendlich).
- US-Exportkontrollrecht (EAR/ITAR/OFAC) kann extraterritorial wirken; EU-Unternehmen mit US-Waren-Anteilen oder US-Mitarbeitern sind betroffen.
- AWV-Meldepflichten haben kurze Fristen (z.T. sieben Werktage nach Zahlung); verspaetest gestellte Meldungen sind Ordnungswidrigkeit.
- CBAM-Uebergangsphase laeuft bis Ende 2025; ab 2026 gelten volle Zertifikatspflichten mit Quartalsmeldungen.
- Sanktions-Screening muss alle Vertragsparteien, Endabnehmer und Zwischenhaendler erfassen; alleinige Zahlungsstrom-Pruefung genuegt nicht.

## Typische Fehler

- Genehmigungspflicht uebersehen: Dual-Use-Einordnung ohne Gueterlisten-Check; Export ohne erforderliche BAFA-Genehmigung ist Straftat.
- Praeferenznachweis nicht rechtzeitig eingeholt: Lieferantenerklarung muss vor Ausfuhr vorliegen; nachtragliche Anforderung wird oft abgelehnt.
- Zollwert-Anpassungen vergessen: Lizenzgebuehren und Verguetungen koennen zum Zollwert hinzugerechnet werden (Art. 71 UZK).
- US-Sanktions-Nexus uebersehen: Transaktionen in USD oder mit US-Kreditinstituten koennen OFAC-Pflichten ausloesen.
- ICP nur auf dem Papier: BAFA bewertet Wirksamkeit des ICP in der Praxis; fehlende Schulungen und fehlende Dokumentation fuehren zu Nachforderungen.

## Querverweise

- Plugin `umweltrecht` — CBAM hat Schnittstellen zu TEHG-Emissionshandel; Doppel-Compliance pruefen.
- Plugin `grosskanzlei-corporate-ma` — Bei M&A-Transaktionen mit Auslandstoechtern: Exportkontroll-DD und Sanktions-Screening als Teil der Legal DD.
- Plugin `patentrecherche` — Bei Technologietransfer-Mandaten koennen Exportkontroll- und Patentlizenz-Fragen zusammenfallen.

## Quellen und Aktualitaet

- Stand: 05/2026
- AWG, AWV, UZK, Dual-Use-VO (EU) 2021/821, CBAM-VO (EU) 2023/956, GwG in aktuell geltender Fassung
- BAFA-Merkblaetter und TARIC-Datenbank (Stand 05/2026)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
