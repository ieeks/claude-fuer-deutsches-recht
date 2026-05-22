---
name: triage-ki-vo-vorpruefung
description: "Erster Einstieg in den KI-VO-Pruefer: Erfasst strukturiert, ob der Nutzer eine eigene Software-Entwicklung, einen fremden Dienst, eine Produktintegration oder eine Beratungsanfrage einbringt. Stellt Eingangsfragen und leitet zum naechsten passenden Skill weiter. Warnt vor typischen Fehlzuordnungen."
---

# Triage: KI-VO-Vorprüfung — Was prüft der Nutzer?

## Zweck

Dieser Skill ist der Einstiegspunkt in den vollständigen Prüfungsworkflow der Verordnung (EU) 2024/1689 (KI-VO). Bevor Risikoklassen, Pflichten oder Verbote geprüft werden können, muss das System verstehen, welchen Sachverhalt der Nutzer einbringt und welche Rolle er in Bezug auf das fragliche System einnimmt.

## Eingangsfragen

Das System stellt folgende Fragen der Reihe nach:

**Frage 1 — Art des Gegenstands**

Was wird geprüft?
- (A) Ich habe selbst eine Software oder ein System entwickelt oder lasse es entwickeln.
- (B) Ich nutze einen fremden KI-Dienst (Cloud-Dienst, Drittanbieter-Produkt, API) in meinem Betrieb.
- (C) Ich integriere ein KI-System oder KI-Komponente in ein eigenes Produkt.
- (D) Ich berate Mandanten zu einem KI-System oder einer KI-VO-Fragestellung.
- (E) Ich weiß noch nicht genau — bitte führe mich.

**Frage 2 — Beschreibung des Systems**

Bitte beschreiben Sie in Stichpunkten:
- Was tut das System? (Beispiele: Bilderkennung, Textgenerierung, Scoring, Empfehlung, Entscheidungsunterstützung)
- In welchem Bereich wird es eingesetzt? (Beispiele: Personalwesen, Medizin, Kredit, Strafverfolgung, Bildung, allgemeine Nutzung)
- Wer sind die betroffenen Personen? (Beispiele: Bewerber, Patienten, Kreditnehmer, Bürger)

**Frage 3 — Standort und Markt**

- Wo soll das System eingesetzt werden? (EU / außerhalb EU / unklar)
- Werden Ausgaben des Systems in der EU verwendet, auch wenn das System außerhalb betrieben wird?

## Plausibilitätsprüfung

Das System prüft auf Basis der Eingaben:
- Handelt es sich möglicherweise gar nicht um ein KI-System im Sinne von Art. 3 Nr. 1 KI-VO? → Weiterleitung zu `liegt-ki-system-vor-art-3-nr-1`
- Liegt ein offensichtlicher Ausschluss nach Art. 2 Abs. 3 bis 12 vor (Militär, rein persönliche Nutzung)? → Weiterleitung zu `sachlicher-ausschluss-art-2-abs-3-bis-12`
- Verwechselt der Nutzer die KI-VO mit einem anderen Rechtsgebiet (DSGVO, Produkthaftung)? → Weiterleitung zu `falsche-wiese-warnung-ki-vo`

## Routing-Logik

| Antwort | Nächster Skill |
|---|---|
| Variante A oder C | `liegt-ki-system-vor-art-3-nr-1` → `rolle-anbieter-pruefen-art-3-nr-3` |
| Variante B | `liegt-ki-system-vor-art-3-nr-1` → `rolle-betreiber-pruefen-art-3-nr-4` |
| Variante D | `mandatsabbruch-empfehlung-komplexe-faelle` (Hinweis auf Grenzen des Mechanik-Workflows) |
| Variante E | Rückfragen zu Beschreibung, dann Routing nach Sachverhalt |

## Wichtige Einschränkungen

- Das System akzeptiert keine fiktiven Testdaten oder Mustersachverhalte.
- Unvollständige Sachverhalte führen zu unvollständigen Ergebnissen — das System weist ausdrücklich darauf hin.
- Dieser Workflow ist ein mechanisches Prüfinstrument, kein juristisches Gutachten.

## Warnblock

**Achtung — Keine Rechtsberatung:**
Dieser Skill erfasst nur, was der Nutzer mitteilt. Er kann nicht prüfen, ob die Sachverhaltsdarstellung vollständig oder korrekt ist. Alle Ergebnisse stehen unter dem Vorbehalt der vom Nutzer behaupteten Tatsachen.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
