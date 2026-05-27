---
name: allgemein
description: "Einstieg in das AML/KYC-Plugin: GwG-Verpflichtetencheck, Risikoanalyse, KYC-Onboarding, PEP/Sanktionen, UBO-Ermittlung, Verdachtsmeldung an FIU, Transparenzregister und Behoerdenverfahren."
---

# Geldwaeschepraeventition AML/KYC — Allgemein

## Worum geht es?

Dieses Plugin deckt das gesamte Geldwaesche-Praeventionsrecht nach dem Geldwaeschegesetz (GwG) ab. Es richtet sich an Compliance-Beauftragte, Rechtsanwaelte und Geldwaeschebeauftragte bei Banken, Zahlungsdienstleistern, Kreditinstituten, Immobilienmaklern, Gueterhaendlern und anderen Verpflichteten nach § 2 GwG.

Das Plugin unterstuetzt bei der risikobasierten Risikoanalyse, dem KYC-Onboarding neuer Kunden, der Pruefung politisch exponierter Personen (PEP), dem Sanktionsscreening, der Ermittlung wirtschaftlich Berechtigter (UBO), der Vorbereitung von Verdachtsmeldungen an die FIU ueber goAML sowie bei Behoerdenverfahren und internen Audits.

## Wann brauchen Sie diese Skill?

- Eine Bank oder ein Zahlungsdienstleister nimmt einen neuen Geschaeftskunden auf und muss KYC-Pruefungen nach § 10 GwG durchfuehren.
- Ein Compliance-Beauftragter entdeckt verdaechtige Transaktionen und prueft, ob eine Verdachtsmeldung nach § 43 GwG an die FIU eingereicht werden muss.
- Ein Immobilienmakler fragt, ob er nach § 2 Abs. 1 Nr. 14 GwG verpflichtet ist und welche Sorgfaltspflichten gelten.
- Ein Unternehmen will seine interne GwG-Risikoanalyse nach § 5 GwG aktualisieren.
- Eine Aufsichtsbehoerde (BaFin, Zollkriminalamt) fuehrt eine Pruefung durch und das Unternehmen braucht Verfahrensbegleitung.

## Fachbegriffe (kurz erklaert)

- **GwG** — Geldwaeschegesetz; setzt die 6. EU-Geldwaescherichtlinie um und regelt Sorgfaltspflichten fuer Verpflichtete.
- **KYC** — Know Your Customer; Kundenpruefungspflichten nach §§ 10-17 GwG: Identifizierung, Risikoklassifizierung, Monitoring.
- **UBO** — Ultimate Beneficial Owner (wirtschaftlich Berechtigter); Person mit mehr als 25 Prozent Beteiligung oder Kontrolle nach § 3 GwG.
- **PEP** — Politically Exposed Person (politisch exponierte Person); Personen in herausgehobenen oeffentlichen Aemtern mit erhoehtem Risikoprofil.
- **FIU** — Financial Intelligence Unit (Zentralstelle fuer Finanztransaktionsuntersuchungen); staatliche Behoerde, die Verdachtsmeldungen entgegennimmt.
- **goAML** — Meldeportal der FIU fuer elektronische Verdachtsmeldungen nach § 43 GwG.
- **ICP** — Internal Control Program (interne Sicherungsmassnahmen); Pflicht nach § 6 GwG fuer Verpflichtete ab bestimmter Groesse.
- **Transparenzregister** — Nationales Register der wirtschaftlich Berechtigten nach §§ 18-20 GwG.

## Rechtsgrundlagen

- §§ 1-4 GwG (Begriffsbestimmungen, Risikobasierter Ansatz)
- § 2 GwG (Verpflichtete)
- § 3 GwG (Wirtschaftlich Berechtigte)
- §§ 5-8 GwG (Risikoanalyse, Risikomanagement, interne Sicherungsmassnahmen)
- §§ 10-17 GwG (Allgemeine, vereinfachte und verstaerkte Sorgfaltspflichten)
- §§ 18-20 GwG (Transparenzregister)
- §§ 43-47 GwG (Meldepflichten, Verdachtsmeldung an FIU)
- EU-Sanktionsverordnungen (EU 2580/2001, EU 881/2002, EU 765/2006 u. a.)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Verpflichteten-Status pruefen: Ist das Unternehmen nach § 2 GwG verpflichtet? (`geldwaesche-verpflichteten-check`)
2. Risikoprofil bestimmen: Risikoanalyse nach § 5 GwG erstellen oder aktualisieren (`geldwaesche-risikoanalyse-unternehmen`).
3. Konkreten Anwendungsfall einordnen: KYC-Onboarding, Verdachtspruefung, Sanktionsscreening, Behoerdenverfahren?
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Eilpflichten pruefen: Verdachtsmeldung unverzueglich, Transaktionsstopp sofortig.

## Skill-Tour (was gibt es hier?)

- `geldwaesche-kommandocenter` — Zentrales Steuerungsmodul fuer alle AML/KYC-Faelle vom Intake bis zum Massnahmenplan.
- `geldwaesche-verpflichteten-check` — Prueft ob und in welcher Rolle ein Unternehmen oder Berufsstraeger nach GwG verpflichtet ist.
- `geldwaesche-risikoanalyse-unternehmen` — Risikobasierte AML/CFT-Risikoanalyse nach § 5 GwG erstellen fuer Verpflichtete.
- `geldwaesche-kyc-onboarding` — KYC-Onboarding neuer Kunden mit Identifizierung, Risikoklassifizierung und Freigabe nach GwG.
- `geldwaesche-ubo-wirtschaftlich-berechtigte` — Wirtschaftlich Berechtigte, Kontrollketten und Trust-/Stiftungsstrukturen ermitteln nach GwG.
- `geldwaesche-pep-hochrisikoland` — Verstaerkte KYC-Pruefung fuer PEP, Hochrisikolaender und komplexe Strukturen nach GwG.
- `geldwaesche-sanktionsscreening` — Sanktionsscreening von Kunden, Transaktionen und Beteiligten gegen EU-, US- und UN-Sanktionslisten.
- `geldwaesche-transaktionsmonitoring` — Auffaellige Transaktionsmuster und Red-Flags im Zahlungsverkehr erkennen nach GwG.
- `geldwaesche-transaktionsstopp-freeze` — Transaktionsstopp, Kontosperrung und Nichtdurchfuehrung bei Sanktions- oder Verdachtstreffer.
- `geldwaesche-verdachtsmeldung-fiu-goaml` — Verdachtsmeldungen nach § 43 GwG vorbereiten und ueber goAML-Portal an die FIU einreichen.
- `geldwaesche-transparenzregister` — Transparenzregister-Einsicht, Abgleich und Unstimmigkeitsmeldung nach GwG.
- `geldwaesche-sicherungsmassnahmen-icp` — Interne Sicherungsmassnahmen (ICP) nach § 6 GwG aufbauen und haerten.
- `geldwaesche-gruppenweite-compliance` — Gruppenweite AML/KYC-Policies und Steuerung von Tochtergesellschaften und Dienstleistern.
- `geldwaesche-krypto-zahlungsdienstleister` — AML/KYC-Pruefung fuer Krypto-Assets, Wallets, Travel Rule und Zahlungsdienstleister.
- `geldwaesche-immobilien-gueterhaendler` — AML/KYC-Pruefung fuer Immobilienmakler, Gueterhaendler, Kunsthandel und Edelmetalle.
- `geldwaesche-datenqualitaet-register` — Datenqualitaet im KYC-System und Transparenzregister-Abgleich auf Dubletten und Fehler pruefen.
- `geldwaesche-schulung-awareness` — Zielgruppengerechte AML/KYC-Schulungen und Awareness-Massnahmen nach § 6 Abs. 2 Nr. 6 GwG.
- `geldwaesche-simulation-testlauf` — Simulation eines Compliance-Arbeitstags mit Onboarding, Alerts, Verdachtspruefung und Behoerdenfragen.
- `geldwaesche-behoerdenverfahren` — Begleitung von BaFin-Pruefungen, FIU-Nachfragen und Massnahmenbescheiden.
- `geldwaesche-bussgeld-reputation` — Bussgeldriskien, Geschaeftsleiterhaftung und Reputationsschaeden bei GwG-Verstoessen strukturieren.
- `geldwaesche-audit-internal-revision` — Interne Revision und Audit der AML/KYC-Kontrollen nach GwG durch Compliance-Beauftragten oder externen Pruefer.

## Worauf besonders achten

- Verdachtsmeldepflicht nach § 43 GwG ist unverzueglich — eine verzoegerte Meldung ist selbst bussgeldrelevant.
- Transaktionsstopp nach § 46 GwG greift vor dem Vollzug einer Transaktion — die Pflicht zur Nichtdurchfuehrung muss bekannt sein.
- UBO-Ermittlung bei Kettenstrukturen (Holding-Pyramiden, Trusts) ist besonders komplex; einfaches Gesellschaftsregister reicht nicht.
- Sanktionsscreening muss auch bei Bestandskunden bei neuen Sanktionsereignissen erneut durchgefuehrt werden.
- Krypto-Assets sind seit MiCA und den GwG-Aenderungen 2023 vollumfaenglich verpflichtet — Travel Rule (Art. 14 ff. MiCA-VO) beachten.

## Typische Fehler

- KYC-Onboarding ohne PEP-Screening: Neukunde ist politisch exponiert, wird aber als Standardkunde eingestuft.
- Keine regelmaessige Aktualisierung der Kundendaten: Risikoeinstufung veraltet, obwohl sich Eigentumsstruktur geaendert hat.
- Verdachtsmeldung verzoegert eingereicht: Interne Rechts- und Compliance-Schleife verzoegert Meldung ueber 24 Stunden hinaus.
- Gruppenweite Richtlinien nicht auf Tochterlandniveau heruntergebrochen: Lokale GwG-Anforderungen abweichend zu Gruppenpolicy.
- Immobilienmakler-Pflichten unterschaetzt: Barzahlungsverbot und KYC-Pflicht ab 10.000 Euro werden uebersehen.

## Querverweise

- `corporate-kanzlei` — GwG-Confliktcheck und Sanktionspruefung bei M&A-Transaktionen.
- `regulatorisches-recht` — BaFin-Aufsicht und MaRisk-Anforderungen fuer Finanzunternehmen.
- `datenschutzrecht` — KYC-Datenverarbeitung unterliegt DSGVO; Aufbewahrungspflichten versus Loeschpflicht.
- `vertragsrecht` — Geheimhaltungsklauseln und AML-Representations in Transaktionsvertraegen.

## Quellen und Aktualitaet

- Stand: 05/2026
- GwG in der zum Stand-Datum geltenden Fassung
- Gesetzesfassungen zum Stand-Datum
- FATF Recommendations (2023)
- EU-Geldwaescheverordnung (MLD6) in der Uebergangsphase

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
