---
name: hochrisiko-datenqualitaet-und-data-governance-art-10
description: "Anforderungen an Trainings- Validierungs- und Testdatensaetze fuer Hochrisiko-KI nach Art. 10 KI-VO: Relevanz Repraesentativitaet Vollstaendigkeit Fehlerfreiheit Bias-Minderung. Data-Governance-Pflichten und Ausnahme fuer besondere Datenkategorien nach Art. 10 Abs. 5 KI-VO."
---

# Datenqualität und Data Governance — Art. 10 KI-VO

## Zweck

Art. 10 KI-VO stellt spezifische Anforderungen an die Daten, mit denen Hochrisiko-KI-Systeme trainiert, validiert und getestet werden. „Garbage in, garbage out" ist keine Entschuldigung — mangelhafte Datenqualität begründet einen Pflichtverstoß.

## Pflichten im Überblick (Art. 10 Abs. 2 KI-VO)

### Anforderung 1 — Geeignete Datenverwaltungspraktiken

Anbieter müssen geeignete Datenverwaltungspraktiken umsetzen, die Folgendes umfassen:
- Klare Festlegung des Entwicklungsziels und der vorgesehenen Verwendungszwecke
- Verfahren zur Datenerhebung
- Analyse auf mögliche Verzerrungen (Bias)
- Erkennung und Behebung von Datenlücken und Mängeln

**Prüffragen:**
- Gibt es eine schriftlich dokumentierte Datenstrategie?
- Wurden Herkunft, Erhebungsmethode und Qualitätsmerkmale der Datensätze dokumentiert?

### Anforderung 2 — Relevanz und Repräsentativität (Art. 10 Abs. 3 KI-VO)

Trainings-, Validierungs- und Testdatensätze müssen:
- Relevant für den vorgesehenen Zweck des Systems sein
- Repräsentativ für die Bedingungen sein, unter denen das System eingesetzt werden soll
- Hinreichend vollständig und fehlerfrei sein (unter Berücksichtigung des Einsatzbereichs)
- Die spezifischen Eigenschaften und Merkmale der vorgesehenen Einsatzsituation aufweisen

**Prüffragen:**
- Deckt der Datensatz die Vielfalt der Einsatzbedingungen ab?
- Sind bestimmte Bevölkerungsgruppen, Szenarien oder Randfälle unterrepräsentiert?
- Wurden bekannte Datenmängel dokumentiert und ihr Einfluss auf die Systemleistung bewertet?

### Anforderung 3 — Bias-Erkennung und Bias-Minderung (Art. 10 Abs. 2 lit. f KI-VO)

Anbieter müssen Daten auf mögliche Verzerrungen analysieren und geeignete Maßnahmen zur Bias-Minderung ergreifen. Dies gilt insbesondere bei Systemen, die auf Merkmale wie Alter, Geschlecht, ethnische Zugehörigkeit oder andere geschützte Kategorien zugreifen können.

**Prüffragen:**
- Wurden Bias-Analysen durchgeführt (z.B. Fairness-Metriken, Subgruppen-Analysen)?
- Sind die Maßnahmen zur Bias-Minderung dokumentiert und auf ihre Wirksamkeit geprüft?
- Welche Restverzerrungen verbleiben nach den Minderungsmaßnahmen?

### Anforderung 4 — Trennung der Datensätze

Trainings-, Validierungs- und Testdatensätze müssen klar voneinander getrennt sein. Insbesondere darf der Testdatensatz nicht für das Training oder die Parameteroptimierung verwendet worden sein.

**Prüffragen:**
- Sind die drei Datensätze klar getrennt und dokumentiert?
- Wurde der Testdatensatz ausschließlich für die abschließende Leistungsbeurteilung verwendet?

## Ausnahme für besondere Datenkategorien (Art. 10 Abs. 5 KI-VO)

Für die Zwecke der Erkennung und Korrektur von Verzerrungen in Hochrisiko-KI-Systemen ist die Verarbeitung besonderer Kategorien personenbezogener Daten nach Art. 9 Abs. 1 DSGVO (Rasse, Gesundheit, Religion, sexuelle Orientierung usw.) unter engen Voraussetzungen erlaubt:
- Wirksame technisch-organisatorische Sicherheitsvorkehrungen müssen vorhanden sein
- Die Verarbeitung darf ausschließlich zu diesem Zweck erfolgen
- Die Daten dürfen nicht zu anderen Zwecken verarbeitet werden
- Die Daten dürfen nicht übermittelt werden
- Die Daten sind nach Abschluss der Bias-Analyse zu löschen

**Prüffragen:**
- Liegt eine DSGVO-konforme Rechtsgrundlage für die Verarbeitung besonderer Kategorien vor?
- Sind die Sicherheitsvorkehrungen dokumentiert?
- Wird die Verarbeitung strikt auf den Bias-Korrekturzweck beschränkt?

## Verhältnis zu anderen Pflichten

Art. 10 KI-VO ist eng verzahnt mit:
- Art. 9 KI-VO (Risikomanagement — schlechte Daten erzeugen Risiken)
- Art. 11 und Anhang IV KI-VO (Technische Dokumentation — Datensätze sind zu beschreiben)
- DSGVO — Datenschutz gilt parallel für alle personenbezogenen Trainingsdaten

## Typische Praxisprobleme

- Trainingsdaten wurden nicht dokumentiert; keine Herkunftsnachweise.
- Test- und Validierungsdaten überlappen mit Trainingsdaten.
- Bias-Analyse wurde durchgeführt, aber Ergebnisse nicht dokumentiert.
- Besondere Datenkategorien wurden ohne DSGVO-Rechtsgrundlage verarbeitet.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
