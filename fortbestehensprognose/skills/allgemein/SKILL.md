---
name: allgemein
description: "Einstieg und Orientierung fuer das Fortbestehensprognose-Plugin: Fortbestehensprognose nach § 19 Abs. 2 InsO als Geschaeftsfuehrer-Selbstdokumentation, bilanzieller Status, Annahmen, Plausibilisierung, Zwoelf-Monats-Liquiditaet, Sanierungsbausteine und Eskalation bei negativer Prognose."
---

# Fortbestehensprognose — Allgemein

## Worum geht es?

Dieses Plugin begleitet Geschaeftsfuehrer und Vorstande bei der Erstellung einer Fortbestehensprognose nach § 19 Abs. 2 InsO. Es dokumentiert Schritt fuer Schritt: ausloesende Ereignisse, bilanziellen Status, Fortfuehrungsannahmen, Plausibilisierung, rollende Zwoelf-Monats-Liquiditaet, Sensitivitaetsszenarien und Sanierungsbausteine (Patronatserklaerung, Comfortletter, Rangruecktritt, Stundung, Forderungsverzicht). Wenn die Prognose negativ ausfaellt, eskaliert das Plugin zum Pflichtenkatalog des Geschaeftsfuehrers nach §§ 15a, 15b InsO.

Das Plugin richtet sich an Eigenverantwortliche: Geschaeftsfuehrer, Vorstande und Finanzleiter — nicht als Ersatz fuer die Beauftragung eines Insolvenzrechtsanwalts.

## Wann brauchen Sie diese Skill?

- Der Steuerberater oder Wirtschaftspruefer weist auf negatives Eigenkapital oder bilanziellen Ueberschuldungsverdacht hin (§ 102 StaRUG).
- Das Unternehmen zeigt Liquiditaetsengpaesse und Sie als Geschaeftsfuehrer muessen dokumentieren, dass Sie aktiv gehandelt haben.
- Gesellschafter oder Banken verlangen eine Fortbestehensprognose als Voraussetzung fuer Unterstuetzungsmassnahmen.
- Sie pruefe Sanierungsbausteine (Gesellschafterdarlehen, Rangruecktritt, Patronatserklaerung) und wollen die insolvenzrechtliche Wirkung verstehen.
- Die Prognose ist knapp positiv oder negativ und Sie benoetigen den Pflichtenkatalog fuer die naechsten Schritte.

## Fachbegriffe (kurz erklaert)

- **Fortbestehensprognose** — Einschaetzung, ob das Unternehmen im Prognosezeitraum (ueblicherweise 12 Monate) ueberwiegend wahrscheinlich zahlungsfaehig bleiben wird (§ 19 Abs. 2 InsO, Massstab IDW S 11).
- **Ueberschuldung** — Passiva uebersteigen Aktiva nach bilanzieller Bewertung; bei positiver Fortbestehensprognose kein Insolvenzgrund nach § 19 Abs. 2 InsO.
- **Rangruecktritt** — Erklaerung des Gesellschafters, seine Darlehensforderung hinter alle anderen Glaeubiger zurueckzustellen; fuehrt zur Nichtpassivierung im insolvenzrechtlichen Status.
- **Patronatserklaerung (hart)** — Rechtsverbindliche Erklaerung des Gesellschafters oder Mutterunternehmens, die Tochtergesellschaft so auszustatten, dass sie zahlungsfaehig bleibt; beruecksichtigungsfaehig im Status.
- **Comfortletter** — Weiche Erklaerung des Patrons; nicht rechtsverbindlich; nicht ausreichend fuer insolvenzrechtlichen Status.
- **IDW S 11** — Institut der Wirtschaftspruefer, Standard 11: Massstab und Methodik fuer die Fortbestehensprognose.
- **StaRUG** — Gesetz ueber den Stabilisierungs- und Restrukturierungsrahmen; Option vor formeller Insolvenz.

## Rechtsgrundlagen

- § 17 InsO — Zahlungsunfaehigkeit (Insolvenzgrund)
- § 18 InsO — Drohende Zahlungsunfaehigkeit (nur Eigenantrag)
- § 19 InsO — Ueberschuldung und Fortbestehensprognose
- § 15a InsO — Insolvenzantragspflicht (sechs Wochen bei Ueberschuldung, drei Wochen bei Zahlungsunfaehigkeit)
- § 15b InsO — Zahlungsverbot und Haftung bei Insolvenzverschleppung
- § 43 GmbHG — Haftung des Geschaeftsfuehrers
- §§ 1-93 StaRUG — Restrukturierungsrahmen
- § 19 Abs. 2 S. 2 InsO — Qualifizierter Rangruecktritt (BGH II ZR 18/19)
- § 3a EStG — Steuerliche Behandlung Sanierungsgewinn

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Wer nutzt das Plugin (GF, Vorstand, Finanzleiter), Rechtsform, Geschaeftsjahr, Buchhaltungssystem.
2. Phase des Mandats bestimmen: Ausloeser erfassen, bilanzieller Status, Annahmen, Plausibilisierung, Liquiditaetsplanung oder Sanierungsbaustein-Erstellung.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: Dreiwochenfrist Zahlungsunfaehigkeit, Sechswochenfrist Ueberschuldung nach § 15a InsO.
5. Anschluss-Skill bestimmen: Wenn Prognose negativ, sofort `wenn-prognose-negativ-naechste-schritte` und Insolvenzanwalt einbinden.

## Skill-Tour (was gibt es hier?)

**Konfiguration und Einstieg**

- `fortbestehensprognose-kaltstart-interview` — Ersteinrichtung: Rolle, Rechtsform, Ansprechpartner, Buchhaltungssystem und Profil schreiben.

**Aufnahme und Analyse**

- `ausloesendes-ereignis-erfassen` — Dokumentiert Anlass, Datum, Hinweisgeber und Mitteilungsform der Fortbestehenspruefung.
- `bilanzieller-status-aufnehmen` — Nimmt Aktiva, Passiva, Eigenkapital und ausserbilanzielle Verpflichtungen auf; prueft bilanziellen Ueberschuldungsverdacht.
- `annahmen-sammeln-fortfuehrung` — Sammelt Fortfuehrungsannahmen zu Umsatz, Kosten, Personal, Investitionen und Working Capital.
- `annahmen-belastbarkeit-plausibilisieren` — Plausibilisiert Annahmen gegen Vergangenheit und Marktentwicklung; erzeugt Plausibilitaetsprotokoll.
- `liquiditaet-12-monate` — Rollende Zwoelf-Monats-Liquiditaetsvorschau mit Einzahlungen, Auszahlungen und Linienverbleib.

**Sanierungsbausteine (Dokumente erzeugen)**

- `sanierungsbausteine-vorschlagen` — Empfehlungsmatrix fuer Sanierungsmassnahmen nach Effekt und Umsetzungszeit.
- `patronatserklaerung-extern-hart-erzeugen` — Harte externe Patronatserklaerung als DOCX zur Unterzeichnung erzeugen.
- `comfortletter-weich-erzeugen` — Comfortletter (weich, nicht rechtsverbindlich) erstellen mit Warnhinweis zur insolvenzrechtlichen Wirkung.
- `gesellschafterdarlehen-rangruecktritt` — BGH-konforme Rangruecktrittserklaerung nach § 19 Abs. 2 S. 2 InsO erzeugen.
- `forderungsverzicht-besserungsschein` — Forderungsverzicht mit Besserungsschein erstellen mit steuerlichen Hinweisen.
- `stundungsanfrage-glaeubiger` — Stundungsanfragen an Glaeubiger (Lieferanten, Bank, Finanzamt, Sozialversicherung) individuell erstellen.

**Prognose und Dokumentation**

- `fortbestehensprognose-zusammenfuehren` — Alle Bausteine zusammenfuehren und Gesamtbewertung nach IDW S 11 erstellen.
- `prognose-dokumentation-stichtag` — Abschliessende Selbstdokumentation zum Stichtag als Haftungsbeleg.

**Eskalation**

- `wenn-prognose-negativ-naechste-schritte` — Pflichtenkatalog bei negativer Prognose: § 15a InsO, § 15b InsO, StaRUG-Option, Insolvenzanwalt.

## Worauf besonders achten

- **Selbstdokumentation ersetzt keinen Insolvenzrechtsanwalt.** Das Plugin hilft GF bei Eigenverantwortung; bei negativer oder knapp positiver Prognose ist Fachanwaltskonsultation zwingend.
- **Rangruecktritt muss BGH-konform formuliert sein.** Fehlformulierungen sind insolvenzrechtlich wirkungslos; Skill `gesellschafterdarlehen-rangruecktritt` liefert BGH-konforme Formulierung.
- **Nur harte Patronatserklaerung ist beruecksichtigungsfaehig.** Comfortletter reicht nicht aus; das Plugin weist explizit darauf hin.
- **Dreiwochenfrist laeuft ohne Hemmung.** Sobald Zahlungsunfaehigkeit eingetreten ist, laeuft § 15a InsO-Frist ohne Moeglichkeit der Verlaengerung.
- **Steuerliche Folgen von Sanierungsgewinn beachten.** Forderungsverzicht loest beim Schuldner Ertrag aus; Skill `forderungsverzicht-besserungsschein` enthaelt entsprechenden Hinweis.

## Typische Fehler

- Prognose wird auf der Basis zu optimistischer Annahmen erstellt ohne Plausibilisierung gegen Vergangenheit und Markt.
- Bilanzieller Status wird mit insolvenzrechtlichem Status gleichgesetzt; beide koennen abweichen (stille Reserven, Rangruecktritt).
- Comfortletter wird als ausreichend fuer positiven Status behandelt; fuehrt zu fehlerhafter Prognose.
- Dokumentation erfolgt nach dem Ereignis (nachtraeglich), nicht zum Stichtag; Haftungsschutz entfaellt.
- Steuerwirkung des Sanierungsgewinns (§ 3a EStG) wird nicht beachtet; unerwartete Steuerlast.

## Querverweise

- `insolvenzforderungsanmeldungspruefung` — Wenn das Verfahren eroeffnet wird und Forderungen geprueft werden muessen.
- `mittelstand-corporate-ma` — Wenn die Krise im Kontext einer M&A-Transaktion entsteht (Distressed M&A, StaRUG-Begleitung).
- `gesellschaftsrecht` — Fuer Haftungsfragen des GF und Gesellschafterbeschluesse im Krisenkontext.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum (InsO, StaRUG, GmbHG, EStG, BGB)
- IDW S 11 (Fortbestehensprognose) und IDW S 6 (Sanierungskonzept) in geltender Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
