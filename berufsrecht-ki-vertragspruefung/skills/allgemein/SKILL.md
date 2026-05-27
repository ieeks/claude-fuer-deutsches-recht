---
name: allgemein
description: "Einstieg und Überblick für die berufsrechtliche und strafrechtliche Vorprüfung von Vertraegen mit privaten Legal-AI-Anbietern. Für Rechtsanwaelte, Steuerberater, Wirtschaftsprüfer, Patentanwaelte und Notare. Abdeckung von §§ 43e BRAO, 62a StBerG, 50a WPO, 39c PAO, 26a BNotO sowie § 203 StGB."
---

# Berufsrecht KI-Vertragspruefung — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Anwaelte, Steuerberater, Wirtschaftspruefer, Patentanwaelte und Notare bei der berufsrechtlichen und strafrechtlichen Pruefung von Vertraegen mit privaten Legal-AI-Anbietern. Der Einsatz von KI-Diensten in Kanzleien unterliegt strengen berufsrechtlichen Vorgaben, insbesondere den Verschwiegenheitspflichten und den gesetzlichen Dienstleister-Regelungen der jeweiligen Berufsordnung.

Kernproblem ist das Spannungsfeld zwischen dem Wunsch nach KI-Effizienzgewinnen und der Pflicht, Mandatsdaten vor unberechtigtem Zugriff zu schuetzen. § 203 StGB stellt die unbefugte Offenbarung von Berufsgeheimnissen unter Strafe; die berufsrechtlichen Normen verpflichten Kanzleien, Dienstleister explizit zu belehren und vertraglich auf Verschwiegenheit zu verpflichten.

## Wann brauchen Sie diese Skill?

- Sie prufen erstmals einen Vertrag mit einem KI-Anbieter und benoetigen einen strukturierten Pruefrahmen fuer Ihren Berufsstand.
- Ein KI-Dienstleister hat seinen Server in den USA und Sie wollen pruefen, ob der US CLOUD Act oder FISA ein Risiko darstellt.
- Sie moechten einen Rueckfragebrief an den Anbieter schreiben, um fehlende Vertragsklauseln zu Verschwiegenheit, Subunternehmern und Datenloeschung nachzufordern.
- Sie sollen ein zusammenfassendes Gutachten fuer die Kanzleifuehrung erstellen, bevor ein KI-Tool eingefuehrt wird.
- Ihr Kanzleiteam nutzt bereits ein KI-Tool und Sie wollen rueckwirkend pruefen, ob alle berufsrechtlichen Anforderungen erfuellt sind.

## Fachbegriffe (kurz erklaert)

- **§ 203 StGB** — Strafvorschrift zum Schutz von Privatgeheimnissen; erfasst Berufsgeheimnisraeger wie Anwaelte, Aerzte und Steuerberater.
- **Dienstleister-Regelung** — Berufsgruppenspezifische Norm (z. B. § 43e BRAO), die Kanzleien verpflichtet, KI-Anbieter auf Verschwiegenheit zu verpflichten und zu belehren.
- **AVV** — Auftragsverarbeitungsvertrag nach Art. 28 DSGVO; laeuft parallel zur berufsrechtlichen Pruefung, ersetzt diese aber nicht.
- **No-Training-Klausel** — Vertragliche Zusage des Anbieters, Mandatsdaten nicht zum Trainieren von KI-Modellen zu verwenden.
- **Zero-Retention** — Zusage, Daten nicht dauerhaft zu speichern; relevant fuer Loeschkonzept und Audit-Rechte.
- **Cloud Act** — US-amerikanisches Gesetz, das US-Behoerden Zugriff auf bei US-Unternehmen gespeicherte Daten ermoeglichen kann, auch wenn Server in der EU stehen.
- **BSI C5** — Cloud Computing Compliance Criteria Catalogue des Bundesamts fuer Sicherheit in der Informationstechnik; anerkannter Pruefstandard.
- **Norm-Adapter** — Mechanismus im Plugin, der je nach Berufsstand (BRAO, StBerG, WPO, PAO, BNotO) die einschlaegige Dienstleisterregelung auswaehlt.

## Rechtsgrundlagen

- § 43e BRAO — Rechtsanwalt: Inanspruchnahme von Dienstleistern
- § 62a StBerG — Steuerberater: Inanspruchnahme von Dienstleistern
- § 50a WPO — Wirtschaftspruefer: Inanspruchnahme von Dienstleistern
- § 39c PAO — Patentanwalt: Inanspruchnahme von Dienstleistern
- § 26a BNotO — Notar: Inanspruchnahme von Dienstleistern
- § 203 Abs. 1 Abs. 3 Abs. 4 und Abs. 6 StGB — Verletzung von Privatgeheimnissen
- § 204 StGB — Verwertung fremder Geheimnisse
- Art. 28 DSGVO — Auftragsverarbeitung
- Art. 32 DSGVO — Technisch-organisatorische Massnahmen
- §§ 53a 97 StPO — Zeugnisverweigerungsrecht und Beschlagnahmeverbot

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Berufsstand und Anbieter im Kaltstart-Interview erfassen; Norm-Adapter bestimmen.
2. Erforderlichkeit der Offenlegung von Mandatsdaten pruefen und dokumentieren.
3. Verschwiegenheitsklausel im Vertrag lokalisieren und bewerten.
4. Subunternehmer-Regelung, strafrechtliche Belehrung und TOM pruefen.
5. Drittstaat-Risiko (US CLOUD Act, Nicht-EU-Hosting) einschaetzen; ggf. Rueckfragebrief versenden und Gutachten erstellen.

## Skill-Tour (was gibt es hier?)

- `avv-grenzpruefung-datenschutz` — Pruefen ob AVV nach Art. 28 DSGVO die berufsrechtliche Pruefung ersetzt (tut er nicht).
- `berufsrecht-ki-vertragspruefung-kaltstart-interview` — Berufsstand, Anbieter, Vertragsdokument und Normen erfassen; Norm-Adapter aktivieren.
- `cloud-act-und-drittstaat-pruefen` — Auslandsbezug und Drittstaatrisiko (US CLOUD Act, FISA) pruefen; Professional Secrecy Addendum empfehlen.
- `erforderlichkeit-dokumentieren` — Erforderlichkeit der Offenlegung von Berufsgeheimnissen gegenueber dem KI-Dienstleister pruefen und dokumentieren.
- `gutachten-erstellen` — Zusammenfassendes Berufsrechts-Gutachten zum KI-Anbietervertrag erstellen.
- `klauselvorschlaege` — Mustertexte fuer Vertragsklauseln zu Verschwiegenheit, No-Training, Zero-Retention und Subunternehmern liefern.
- `parallelnormen-andere-berufe` — Norm-Adapter-Referenz fuer alle fuenf Berufsgeheimnistraeger mit Mapping der Dienstleisterregelungen.
- `rueckfragebrief-an-anbieter` — Strukturierten Rueckfragebrief an den KI-Anbieter zu offenen berufsrechtlichen Punkten erstellen.
- `strafprozessuale-regelung-pruefen` — Strafprozessuale Absicherung des KI-Dienstleisters nach §§ 53a 97 StPO pruefen.
- `strafrechtliche-belehrung-pruefen` — Belehrung des Dienstleisters ueber § 203 StGB im Vertrag pruefen.
- `subunternehmer-regelung-pruefen` — Subunternehmerklausel auf Zustimmungsvorbehalt, Weiterverpflichtung und Belehrung pruefen.
- `tom-und-zertifizierungen-pruefen` — TOM und Zertifizierungen des Anbieters (ISO 27001, BSI C5, SOC 2) pruefen.
- `verschwiegenheitsklausel-pruefen` — Vertragliche Verpflichtung des Dienstleisters auf Verschwiegenheit lokalisieren und bewerten.

## Worauf besonders achten

- **Berufsrecht und Datenschutzrecht laufen parallel**: Ein vorhandener AVV erfuellt nicht automatisch die berufsrechtlichen Anforderungen nach § 43e BRAO und den Parallelvorschriften.
- **Textformerfordernis**: Die Verschwiegenheitspflicht muss nach § 43e Abs. 3 BRAO in Textform (§ 126b BGB) vereinbart werden; muendliche Zusagen genuegen nicht.
- **Subunternehmer oft uebersehen**: Viele KI-Anbieter nutzen Sprachmodelle grosser US-Konzerne als Subunternehmer; diese muessen ebenfalls verpflichtet werden.
- **Drittstaatrisiko eigenstaendig bewerten**: EU-Sitz des Anbieters genuegt nicht, wenn Muttergesellschaft in den USA dem Cloud Act unterliegt.
- **Strafrechtliche Konsequenzen**: Ein Verstoss gegen § 203 StGB ist eine Straftat, keine Ordnungswidrigkeit.

## Typische Fehler

- Nur den AVV pruefen und berufsrechtliche Parallelvorschriften uebersehen.
- Subunternehmerliste nicht anfordern; Anbieter setzt grosse Sprachmodelle ein, ohne dies offenzulegen.
- Vertrag ohne No-Training-Zusage annehmen; Mandatsdaten koennen in KI-Training einfliessen.
- Erforderlichkeit der Datenweitergabe nicht dokumentieren; interner Compliance-Vermerk fehlt.
- US-Anbieter mit EU-Rechenzentrum als unbedenklich eingestuft, ohne Cloud-Act-Analyse.

## Querverweise

- `ki-richtlinie-kanzleien` — KI-Nutzungsrichtlinie als Rahmen, der die Ergebnisse der Vertragspruefung umsetzt.
- `kanzlei-builder-hub` — Verwaltet und installiert Skills, die ihrerseits KI-Dienste nutzen koennen.
- `kanzlei-allgemein` — Kanzlei-Workflow-Plugin, fuer das KI-Dienste berufsrechtskonform eingebunden werden muessen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum
- DAV-Stellungnahme Nr. 32/2025 zur berufsrechtlichen Einordnung von KI-Tools
- BRAK-Hinweise 12/2024

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
