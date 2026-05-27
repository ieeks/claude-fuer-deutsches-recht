---
name: allgemein
description: "Einstieg in den KI-VO-Prüfer (EU 2024/1689): Rollen, Risikoklassen, verbotene Praktiken, Hochrisiko-Diagnose, GPAI, Konformitätsbewertung, EU-Datenbank, Sanktionen und 12-Schritte-Roadmap bis CE-Kennzeichnung."
---

# KI-VO AI-Act-Pruefer — Allgemein

## Worum geht es?

Der KI-VO-AI-Act-Pruefer fuehrt Unternehmen, Kanzleien und Compliance-Beauftragte durch die vollstaendige Pruefung nach der EU-Verordnung 2024/1689 (EU AI Act / KI-VO). Er deckt alle Pruefschritte ab: ob eine Software ueberhaupt ein KI-System ist, welche Risikoklasse zutrifft, welche Rolle das Unternehmen einnimmt (Anbieter, Betreiber, Importeur, Haendler), ob verbotene Praktiken vorliegen, wie die Hochrisiko-Einstufung gehandhabt wird und wie der Weg bis zur CE-Kennzeichnung aussieht.

Zusaetzlich behandelt das Plugin General-Purpose-AI (GPAI)-Modelle, die Ausnahmen vom Hochrisiko nach Art. 6 Abs. 3, das Verhaeltnis zu anderen EU-Rechtsakten, Sanktionen sowie die laufende Marktbeobachtung nach Inverkehrbringen.

## Wann brauchen Sie diese Skill?

- Ein Unternehmen fragt, ob die eigene Software unter die KI-VO faellt und welche Pflichten daraus folgen.
- Ein Anbieter von KI hat die Hochrisiko-Einstufung erhalten und braucht eine vollstaendige Roadmap bis zur CE-Kennzeichnung.
- Ein Betreiber kauft ein KI-System ein und muss seine Betreiberpflichten nach Art. 26 KI-VO kennen.
- Ein Anbieter von GPAI-Modellen (Sprachmodelle, Basismodelle) fragt, ob er unter die GPAI-Pflichten faellt und ob systemisches Risiko vorliegt.
- Compliance-Beauftragter will wissen, welche Sanktionen bei Verstoessen drohen und wie Verfahren ablaufen.

## Fachbegriffe (kurz erklaert)

- **KI-System** — Maschinenbasiertes System nach Art. 3 Nr. 1 KI-VO: inferenzbasiert, Ausgaben erzeugt, die Entscheidungen beeinflussen koennen.
- **Anbieter** — Entwickler oder Vermarkter eines KI-Systems, der es in den Verkehr bringt (Art. 3 Nr. 3 KI-VO).
- **Betreiber** — Unternehmen oder Behoerde, die ein KI-System unter eigener Verantwortung einsetzt (Art. 3 Nr. 4 KI-VO).
- **Hochrisiko-KI** — KI-System in sensiblen Anwendungsbereichen nach Art. 6 Abs. 2 i. V. m. Anhang III KI-VO oder als Sicherheitsbauteil eines regulierten Produkts.
- **GPAI** — General-Purpose-AI-Modell nach Art. 3 Nr. 63 KI-VO; Basismodell mit Allzweck-Faehigkeiten; eigene Pflichtenkategorie.
- **Systemisches Risiko** — Erhebliche Risiken bei GPAI-Modellen mit mehr als 10 hoch 25 FLOP Trainingsaufwand (Art. 51 KI-VO).
- **Konformitaetsbewertung** — Verfahren nach Art. 43 ff. KI-VO zur CE-Kennzeichnung von Hochrisiko-KI.
- **EU-KI-Datenbank** — Oeffentliches Register nach Art. 71 KI-VO, in dem Hochrisiko-KI-Systeme registriert werden muessen.

## Rechtsgrundlagen

- Art. 1-3 KI-VO EU 2024/1689 (Anwendungsbereich, Begriffsbestimmungen)
- Art. 5 KI-VO (Verbotene Praktiken)
- Art. 6 und Anhang I und III KI-VO (Hochrisiko-Einstufung)
- Art. 9-15 KI-VO (Pflichten Anbieter Hochrisiko: Risikomanagement, Daten, Transparenz, Aufsicht)
- Art. 22-26 KI-VO (Pflichten Bevollmaechtigter, Importeur, Haendler, Betreiber)
- Art. 43-49 KI-VO (Konformitaetsbewertung, EU-Konformitaetserklaerung, EU-Datenbank)
- Art. 51-55 KI-VO (GPAI-Pflichten, systemisches Risiko)
- Art. 70-79 KI-VO (Governance, Aufsichtsbehoerden, Marktbeobachtung)
- Art. 99-101 KI-VO (Sanktionen)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Vorpruefung: Liegt ueberhaupt ein KI-System vor? (`liegt-ki-system-vor-art-3-nr-1`)
2. Territorialen und sachlichen Anwendungsbereich pruefen (`territorialer-anwendungsbereich-art-2`, `sachlicher-ausschluss-art-2-abs-3-bis-12`).
3. Rolle bestimmen: Anbieter, Betreiber, Importeur oder Haendler? (`persoenlicher-anwendungsbereich-rollen-art-3`)
4. Risikoklasse bestimmen: Verboten, Hochrisiko, begrenztes Risiko oder GPAI? (`risikoklassen-uebersicht-und-triage`)
5. Roadmap fuer die zutreffende Risikoklasse auswaehlen und durcharbeiten.

## Skill-Tour (was gibt es hier?)

- `triage-ki-vo-vorpruefung` — Einstieg in die KI-VO-Pruefung fuer unklare Faelle; Startpunkt des Gesamt-Workflows.
- `entscheidungsbaum-ki-vo-gesamt-workflow` — Vollstaendige KI-VO-Pruefung von Anfang bis Ende in einem strukturierten Entscheidungsbaum.
- `liegt-ki-system-vor-art-3-nr-1` — Erster Pruefschritt: Ist die eigene Software ueberhaupt ein KI-System nach Art. 3 Nr. 1 KI-VO?
- `abgrenzung-konventionelle-software-vs-ki-system` — Abgrenzung konventioneller Software vom KI-System-Begriff der KI-VO.
- `territorialer-anwendungsbereich-art-2` — Gilt die KI-VO auch fuer Nicht-EU-Unternehmen oder Exporte?
- `sachlicher-ausschluss-art-2-abs-3-bis-12` — Prueft ob das KI-System vollstaendig aus dem Anwendungsbereich faellt.
- `persoenlicher-anwendungsbereich-rollen-art-3` — Wer ist betroffen und welche Rolle nimmt das Unternehmen ein?
- `risikoklassen-uebersicht-und-triage` — Schnelle Ersteinschaetzung der Risikoklasse nach Art. 5, 6, 50, 51 KI-VO.
- `verbotene-praktiken-art-5` — Prueft ob ein KI-Einsatz in den Bereich absolut verbotener KI-Praktiken faellt.
- `falsche-wiese-warnung-ki-vo` — Warnt vor Verwechslungen mit DSGVO, Produkthaftung oder MDR bei KI-VO-Fragen.
- `rolle-anbieter-pruefen-art-3-nr-3` — Prueft ob das Unternehmen als Anbieter im Sinne der KI-VO einzustufen ist.
- `rolle-betreiber-pruefen-art-3-nr-4` — Prueft ob das Unternehmen als Betreiber im Sinne der KI-VO einzustufen ist.
- `anbieter-werden-art-25` — Prueft unter welchen Bedingungen Betreiber, Importeur oder Haendler selbst zum Anbieter werden.
- `hochrisiko-zuordnung-art-6-und-anhang-i-iii` — Gesamtuebersicht der Hochrisiko-Zuordnungsregeln vor der Detailpruefung.
- `hochrisiko-art-6-abs-1-sicherheitsbauteil` — KI als Sicherheitsbauteil eines regulierten Produkts nach Art. 6 Abs. 1 KI-VO.
- `hochrisiko-art-6-abs-2-anhang-iii` — KI in einem der acht sensiblen Anwendungsbereiche nach Anhang III KI-VO.
- `rueckausnahme-art-6-abs-3` — Ausnahmen vom Hochrisiko trotz Anhang-III-Relevanz nach Art. 6 Abs. 3 KI-VO.
- `hochrisiko-bestaetigt-end-to-end-roadmap` — Vollstaendige Roadmap nach bestaetiger Hochrisiko-Einstufung bis CE-Kennzeichnung.
- `hochrisiko-risikomanagementsystem-art-9` — KI-VO-konformes Risikomanagementsystem aufsetzen (Art. 9 KI-VO).
- `hochrisiko-datenqualitaet-und-data-governance-art-10` — Anforderungen an Trainings-, Validierungs- und Testdaten (Art. 10 KI-VO).
- `hochrisiko-technische-dokumentation-art-11-und-anhang-iv` — Inhalt und Aktualitaet der technischen Dokumentation (Art. 11 und Anhang IV KI-VO).
- `hochrisiko-aufzeichnungspflichten-logging-art-12` — Automatische Aufzeichnungspflichten und Aufbewahrungsfristen (Art. 12 KI-VO).
- `hochrisiko-transparenz-und-informationen-fuer-betreiber-art-13` — Informationen in der Gebrauchsanweisung fuer Betreiber (Art. 13 KI-VO).
- `hochrisiko-menschliche-aufsicht-art-14` — Anforderungen an wirksame menschliche Aufsicht ueber Hochrisiko-KI (Art. 14 KI-VO).
- `hochrisiko-genauigkeit-robustheit-cybersicherheit-art-15` — Leistungsstandards fuer Genauigkeit, Robustheit und Cybersicherheit (Art. 15 KI-VO).
- `hochrisiko-konformitaetsbewertung-art-43-bis-49` — Konformitaetsbewertungsverfahren und Einbindung benannter Stellen (Art. 43-49 KI-VO).
- `eu-datenbank-registrierung-art-49-und-71` — Registrierungspflicht in der EU-KI-Datenbank fuer Anbieter und Betreiber.
- `nicht-hochrisiko-bestaetigt-end-to-end-roadmap` — KI-VO-Pflichten und Dokumentation fuer nicht-hochrisiko-eingestufte Systeme.
- `begrenztes-risiko-art-50-transparenzpflichten` — Transparenzpflichten fuer Chatbots, Deepfake-Tools und KI-Textgeneratoren (Art. 50 KI-VO).
- `gpai-vorliegen-art-3-nr-63` — Prueft ob ein KI-Modell ein GPAI-Modell nach Art. 3 Nr. 63 KI-VO ist.
- `gpai-modelle-art-51-bis-55` — GPAI-Pflichten: Verhaltenskodizes, technische Dokumentation, Transparenz (Art. 51-55 KI-VO).
- `gpai-systemisches-risiko-schwelle-10e25-flop` — Prueft ob die Schwelle fuer systemisches Risiko bei GPAI-Modellen ueberschritten ist.
- `bevollmaechtigter-und-produkthersteller-pflichten-art-22-und-25` — Pflichten des EU-Bevollmaechtigten und von Produktherstellern (Art. 22 und 25 KI-VO).
- `einfuehrer-importer-pflichten-art-23` — Sorgfaltspflichten des Importeurs von KI-Systemen aus Drittstaaten (Art. 23 KI-VO).
- `haendler-distributor-pflichten-art-24` — Sorgfaltspflichten des Distributeurs beim Weitervertrieb von Hochrisiko-KI (Art. 24 KI-VO).
- `betreiber-deployer-pflichten-art-26` — Betreiberpflichten beim Einsatz eingekaufter Hochrisiko-KI-Systeme (Art. 26 KI-VO).
- `code-of-practice-und-harmonisierte-normen` — Verhaltenskodizes und technische Normen fuer die KI-VO-Konformitaet nutzen.
- `governance-aufsichtsbehoerden-art-70` — Aufsichtsbehoerden in Deutschland und Europa fuer die KI-VO (Art. 70 KI-VO).
- `marktueberwachung-meldung-vorfaelle-art-72-bis-79` — Pflichten bei schwerwiegenden Vorfaellen und Marktbeobachtung nach Inverkehrbringen (Art. 72-79 KI-VO).
- `sanktionen-art-99-bis-101` — Bussgelddimensionen und Sanktionsrahmen der KI-VO (Art. 99-101 KI-VO).
- `verhaeltnis-zu-anderen-unionsrechtsakten` — Abgrenzung und Zusammenspiel der KI-VO mit DSGVO, MDR, Maschinenverordnung und anderen EU-Rechtsakten.
- `zeitlicher-geltungsbereich-uebergangsfristen` — Uebergangsfristen und zeitlicher Geltungsbeginn je Pflichtenkategorie der KI-VO.
- `output-pruefdokument-ki-vo-mit-warnhinweisen` — Abschliessendes Pruefdokument mit allen Ergebnissen und Warnhinweisen erstellen.
- `output-konformitaetserklaerung-eu-anhang-v` — Muster der EU-Konformitaetserklaerung zum Ausfuellen und Unterzeichnen (Anhang V KI-VO).
- `output-betreiber-checkliste-und-folgenabschaetzung` — Fertige Betreiber-Compliance-Dokumentation und Folgenabschaetzung erstellen.
- `mandatsabbruch-empfehlung-komplexe-faelle` — Erkennung von Faellen, die anwaltliche Spezialkenntnisse erfordern, und Eskalationsempfehlung.

## Worauf besonders achten

- KI-VO hat gestaffelte Uebergangsfristen: Verbotene Praktiken ab 02.02.2025, GPAI ab 02.08.2025, Hochrisiko-Systeme ab 02.08.2026 — Pflichten abfragen, die zum Stichtag gelten.
- Hochrisiko-Einstufung hat zwei Wege: Sicherheitsbauteil (Art. 6 Abs. 1) und Anhang-III-Bereiche (Art. 6 Abs. 2) — beide getrennt pruefen.
- Anbieter-Werden-Risiko: Betreiber, die ein System wesentlich veraendern, werden automatisch Anbieter mit vollen Anbieter-Pflichten.
- GPAI und KI-System-Schnittstelle: Ein GPAI-Modell kann in einem Hochrisiko-System eingebettet sein — dann kumulieren Pflichten.
- EU-Datenbank-Registrierung vor Inverkehrbringen: Zustimmung der Notifizierungsbehoerde abwarten.

## Typische Fehler

- Konventionelle regelbasierte Software irrtuemlicherweise als KI-System eingestuft: Abgrenzungspruefung fehlt.
- Hochrisiko-Rueckausnahme nach Art. 6 Abs. 3 uebersehen: System faellt in Anhang III, aber Rueckausnahme greift.
- Technische Dokumentation als einmaliges Dokument behandelt: KI-VO verlangt laufende Aktualisierung bei wesentlichen Aenderungen.
- GPAI-Pflichten mit Hochrisiko-Pflichten verwechselt: Verschiedene Regelungsregimes mit unterschiedlichen Anforderungen.
- Sanktionsdimensionen unterschaetzt: Bussgelder bis zu 35 Millionen Euro oder 7 Prozent des weltweiten Jahresumsatzes moeglich.

## Querverweise

- `datenschutzrecht` — DSGVO-Anforderungen ueberschneiden sich bei KI-Systemen mit Personendaten (Art. 9 und 22 DSGVO).
- `corporate-kanzlei` — KI-Governance und Berufsrecht in der Corporate-Kanzlei; KI-Einsatz im M&A-Kontext.
- `regulatorisches-recht` — Sektorspezifische Anforderungen fuer KI in Finanz- und Energiemarkt.
- `legistik-werkstatt` — KI-VO als EU-Verordnung im Kontext der nationalen Umsetzungsgesetzgebung.

## Quellen und Aktualitaet

- Stand: 05/2026
- EU KI-VO (EU 2024/1689) in der zum Stand-Datum geltenden Fassung
- Uebergangsfristen gemaess Art. 113 KI-VO
- GPAI Code of Practice der EU-KI-Buero (erste Fassung 2025)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
