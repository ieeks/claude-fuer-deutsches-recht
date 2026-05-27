---
name: allgemein
description: "Einstieg und Orientierung fuer das KI-Governance-Plugin: EU-KI-VO und DSGVO, Use-Case-Triage, KI-Inventar, Folgenabschaetzung (FRIA/DSFA), Vendor-Review, Richtlinien-Monitor und interne KI-Richtlinien fuer Unternehmen und Kanzleien."
---

# KI-Governance — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Unternehmen, Kanzleien und Datenschutzbeauftragte bei der Einhaltung der EU-KI-Verordnung (VO 2024/1689, in Kraft seit 01.08.2024) sowie der DSGVO im Kontext von KI-Systemen. Es deckt die gesamte KI-Governance ab: Use-Case-Triage gegen verbotene Praktiken und Hochrisiko-Kategorien, KI-Inventar mit Rollenklassifizierung, Folgenabschaetzung (FRIA nach Art. 27 KI-VO und DSFA nach Art. 35 DSGVO), Vendor-Review fuer KI-Anbietervertraege, Richtlinien-Monitor und Erstellung interner KI-Richtlinien.

Das Plugin ist praxisorientiert: Es arbeitet mit dem Praxisprofil des Nutzers (Risikoeinstellung, Eskalationskontakte, Use-Case-Register) und kann Mandats-Workspaces fuer mehrere Klienten verwalten.

## Wann brauchen Sie diese Skill?

- Ihr Unternehmen moechte ein neues KI-System einfuehren und Sie muessen pruefen, ob es unter die KI-VO faellt und welche Risikoklasse gilt.
- Sie benoetigen eine KI-Folgenabschaetzung (FRIA) nach Art. 27 KI-VO oder eine DSGVO-Folgenabschaetzung (DSFA) nach Art. 35 DSGVO.
- Sie pruefen einen KI-Anbietervertrag auf KI-VO-Konformitaet, Haftung und Transparenzpflichten nach Art. 25 KI-VO.
- Die interne KI-Richtlinie soll gegen neue Regulierungen oder Behoerdenleitlinien geprueft und aktualisiert werden.
- Sie wollen ein vollstaendiges KI-Inventar aller im Unternehmen eingesetzten Systeme nach Art. 3 KI-VO aufbauen.

## Fachbegriffe (kurz erklaert)

- **Anbieter** — Wer ein KI-System entwickelt oder entwickeln laesst und es in Verkehr bringt oder in Betrieb nimmt (Art. 3 Nr. 3 KI-VO).
- **Betreiber** — Wer ein KI-System im eigenen Namen und unter eigener Kontrolle einsetzt (Art. 3 Nr. 4 KI-VO).
- **Hochrisiko-KI** — KI-Systeme nach Anhang III KI-VO (z.B. biometrische Identifikation, Beschaeftigung, kritische Infrastruktur); erfordern umfassende Compliance-Pflichten.
- **FRIA** — Fundamental Rights Impact Assessment nach Art. 27 KI-VO: Folgenabschaetzung fuer Grundrechte bei Hochrisiko-KI durch Betreiber.
- **DSFA** — Datenschutz-Folgenabschaetzung nach Art. 35 DSGVO; erforderlich bei hohem Risiko fuer Betroffene durch Datenverarbeitung.
- **Allzweck-KI (GPAI)** — General Purpose AI Model; gesonderte Pflichten nach Art. 51 ff. KI-VO fuer Modelle mit systemischen Risiken.
- **Verbotene Praktiken** — KI-Anwendungen, die nach Art. 5 KI-VO generell verboten sind (z.B. Sozial-Scoring, manipulative Techniken).

## Rechtsgrundlagen

- VO (EU) 2024/1689 (EU-KI-VO) — Gesamtrahmen, Risikoklassen, Verbote, Pflichten
- Art. 5 KI-VO — Verbotene KI-Praktiken
- Anhang III KI-VO — Hochrisiko-KI-Systeme
- Art. 25 KI-VO — Pflichten der Betreiber
- Art. 27 KI-VO — Folgenabschaetzung Grundrechte (FRIA)
- Art. 51-55 KI-VO — Allzweck-KI-Modelle (GPAI) mit systemischen Risiken
- Art. 35 DSGVO — Datenschutz-Folgenabschaetzung (DSFA)
- Art. 13-14 DSGVO — Transparenzpflichten bei automatisierten Entscheidungen

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Unternehmen als Anbieter oder Betreiber, Branche, Groesse, welche KI-Systeme bereits im Einsatz oder geplant.
2. Phase des Mandats bestimmen: Ersteinrichtung (Inventar, Profil), Triage neues KI-System, Folgenabschaetzung, Richtlinien-Erstellung oder Monitoring.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: KI-VO-Verbote seit 02.02.2025 anwendbar; Hochrisiko-Pflichten seit 02.08.2026; GPAI-Pflichten seit 02.08.2025.
5. Anschluss-Skill bestimmen: nach Triage folgt Folgenabschaetzung oder Richtlinien-Monitor; nach Vendor-Review ggf. Vertragsnachverhandlung.

## Skill-Tour (was gibt es hier?)

**Konfiguration und Einstieg**

- `ki-governance-kaltstart-interview` — Ersteinrichtung: KI-Inventar, Rolle in KI-Lieferkette, regulatorischen Anwendungsbereich erfassen.
- `ki-governance-anpassen` — Praxisprofil aktualisieren: Risikoeinstellung, Eskalationskontakte, Module und Workspace-Pfade.
- `ki-governance-mandat-arbeitsbereich` — Mandats-Workspaces verwalten fuer Mehrfachmandatsbetrieb.

**KI-Inventar und Klassifizierung**

- `ki-inventar` — KI-System-Inventar nach EU-KI-VO: Rolle und Risikoklasse je System erfassen und bewerten.
- `anwendungsfall-triage` — Use-Case gegen Unternehmensregister klassifizieren: freigegeben, bedingt, nicht freigegeben.

**Folgenabschaetzung**

- `ki-folgenabschaetzung` — FRIA nach Art. 27 KI-VO und DSFA nach Art. 35 DSGVO erstellen.

**Vendor und Richtlinien**

- `ki-anbieter-pruefung` — KI-Anbietervertraege auf Governance-Positionen, Training auf Daten, Haftung und Art. 25 KI-VO pruefen.
- `richtlinien-vorlage` — Interne KI-Nutzungsrichtlinie entwerfen auf Basis oeffentlicher Muster und Praxisprofil.
- `richtlinien-monitor` — Interne KI-Richtlinie auf Abweichungen von der Praxis und neuen Regulierungen pruefen.
- `regulierungs-luecken-analyse` — Neue KI-Regulierung oder Behoerdenleitlinie gegen aktuelle Governance-Position abgleichen.

## Worauf besonders achten

- **Anbieter- und Betreiber-Rolle exakt abgrenzen.** Beide Rollen haben unterschiedliche Pflichten nach KI-VO; eine Verwechslung fuehrt zu falschen Compliance-Massnahmen.
- **Zeitplan der KI-VO beachten.** Verbote (Art. 5) seit 02.02.2025, GPAI seit 02.08.2025, Hochrisiko seit 02.08.2026; nicht alle Pflichten gelten gleichzeitig.
- **DSFA und FRIA sind keine Duplikate.** Beide Instrumente haben eigene Anwendungsbereiche und koennen parallel erforderlich sein; Skill `ki-folgenabschaetzung` kombiniert beide.
- **Interne Richtlinie muss gelebte Praxis abbilden.** Eine Richtlinie, die niemand einhalt, schuetzt nicht vor regulatorischer Verantwortung; Skill `richtlinien-monitor` prueft Konsistenz.
- **Allzweck-KI-Modelle erfordern Sonderbehandlung.** Bei Einsatz von GPAI-Modellen mit systemischen Risiken gelten Transparenz- und Sorgfaltspflichten nach Art. 53 ff. KI-VO.

## Typische Fehler

- Unternehmen klassifiziert sich als Anbieter obwohl es nur Betreiber ist; fuehrt zu ueberzogenen Compliance-Massnahmen.
- Use-Case-Triage wird nur einmal durchgefuehrt; bei Weiterentwicklung des KI-Systems ist eine erneute Pruefung erforderlich.
- Folgenabschaetzung wird nach Einfuehrung des Systems erstellt; KI-VO erfordert Vorab-Bewertung.
- KI-Anbietervertrag wird ohne Pruefung der Art. 25 KI-VO-Pflichten akzeptiert; Vertragslücken bei Modellwechsel oder Datenpanne.
- Richtlinie wird erstellt und dann nicht aktualisiert; neue Regulierung und neue Systeme bleiben unberuecksichtigt.

## Querverweise

- `mittelstand-corporate-ma` — Wenn KI-Governance im Kontext einer M&A-Transaktion (DD, Vendor-Pruefung) relevant wird.
- `gesellschaftsrecht` — Fuer Haftungsfragen des GF bei KI-Governance-Versaumnissen.
- `subsumtions-pruefer` — Fuer Einzelnorm-Analysen zu KI-VO-Tatbestandsmerkmalen.

## Quellen und Aktualitaet

- Stand: 05/2026
- VO (EU) 2024/1689 (KI-VO) in geltender Fassung; schrittweise Anwendbarkeit beachten
- VO (EU) 2016/679 (DSGVO) in geltender Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
