---
name: risikoklassen-uebersicht-und-triage
description: "Entscheidungsbaum zu den vier Risikoklassen der KI-VO: verbotene Praktiken Art. 5 / Hochrisiko Art. 6 und Anhang III / begrenztes Risiko Art. 50 / minimales Risiko. Systematischer Durchlauf mit klaren Verzweigungen und Weiterleitung zu Detailskills."
---

# Risikoklassen-Übersicht und Triage — KI-VO

## Zweck

Die KI-VO kennt keine einheitlichen Pflichten für alle KI-Systeme. Sie unterscheidet vier Risikokategorien mit stark unterschiedlichen Rechtsfolgen. Dieser Skill liefert den Entscheidungsbaum, mit dem die zutreffende Kategorie ermittelt wird.

## Die vier Kategorien im Überblick

| Kategorie | Rechtsgrundlage | Rechtsfolge |
|---|---|---|
| Verboten | Art. 5 KI-VO | Komplettverbot; keine Ausnahmen für verbotene Praktiken |
| Hochrisiko | Art. 6 i.V.m. Anhang I oder III KI-VO | Umfangreiche Pflichtenkataloge vor Inverkehrbringen |
| Begrenzt | Art. 50 KI-VO | Transparenzpflichten (Chatbot-Hinweis, Deepfake-Kennzeichnung) |
| Minimal | Keine Spezialregelung | Keine zusätzlichen KI-VO-Pflichten; freiwillige Verhaltenskodizes möglich |

## Entscheidungsbaum

### Schritt 1 — Verbotene Praktik?

Frage: Weist das System eines der folgenden Merkmale auf?
- Sublimale oder unterschwellige Techniken zur unbewussten Verhaltensbeeinflussung (Art. 5 Abs. 1 lit. a KI-VO)
- Ausnutzung von Schwächezuständen (Alter, Behinderung, soziale Lage) zur Verhaltensbeeinflussung (Art. 5 Abs. 1 lit. b KI-VO)
- Social-Scoring-Systeme für öffentliche Behörden oder in deren Auftrag (Art. 5 Abs. 1 lit. c KI-VO)
- Predictive Policing auf Basis von Persönlichkeitsmerkmalen ohne individuelle Hinweise (Art. 5 Abs. 1 lit. d KI-VO)
- Biometrische Fernidentifikation in Echtzeit im öffentlichen Raum durch Strafverfolgungsbehörden außerhalb der Ausnahmen (Art. 5 Abs. 1 lit. h KI-VO)
- Biometrische Kategorisierung nach sensiblen Merkmalen (Rasse, politische Meinung, Religion etc.) (Art. 5 Abs. 1 lit. g KI-VO)
- Emotionserkennung am Arbeitsplatz oder in Bildungseinrichtungen (Art. 5 Abs. 1 lit. f KI-VO)
- Untargeted Scraping von Gesichtsbildern aus dem Internet oder Überwachungskameras zum Aufbau von Datenbanken (Art. 5 Abs. 1 lit. e KI-VO)

**Wenn ja zu einem oder mehreren Punkten:** → `verbotene-praktiken-art-5` (Detailprüfung); Ergebnis: System ist verboten, darf nicht in Betrieb genommen werden.

**Wenn nein:** → weiter zu Schritt 2.

### Schritt 2 — Hochrisiko-KI?

**Pfad A (Art. 6 Abs. 1 KI-VO):**
Frage: Ist das KI-System ein Sicherheitsbauteil eines Produkts, das unter eine der in Anhang I genannten Unionsvorschriften fällt, und unterliegt es für dieses Produkt einer Konformitätsbewertung durch Dritte?
- Wenn ja → Hochrisiko nach Art. 6 Abs. 1 KI-VO → `hochrisiko-art-6-abs-1-sicherheitsbauteil`

**Pfad B (Art. 6 Abs. 2 KI-VO):**
Frage: Ist das KI-System in Anhang III der KI-VO in einem der acht Bereiche aufgeführt oder fällt es unter die Beschreibung eines dieser Bereiche?
- Bereiche: biometrische Identifikation, kritische Infrastruktur, Bildung, Beschäftigung, wesentliche Dienstleistungen (Kredit, Sozialleistungen), Strafverfolgung, Migration, Justiz
- Wenn ja → Hochrisiko nach Art. 6 Abs. 2 i.V.m. Anhang III KI-VO → `hochrisiko-art-6-abs-2-anhang-iii`

**Rückausnahme Art. 6 Abs. 3 KI-VO:**
Greift eine der vier Rückausnahmen? → `rueckausnahme-art-6-abs-3`

**Wenn Hochrisiko bestätigt:** → Pflichten nach Art. 9 bis 15 KI-VO (Anbieter), Art. 26 und 27 KI-VO (Betreiber)

**Wenn nein:** → weiter zu Schritt 3.

### Schritt 3 — Begrenztes Risiko?

Frage: Trifft eines der folgenden Merkmale zu?
- Das System ist ein Chatbot oder ein System, das direkt mit natürlichen Personen interagiert, ohne Emotionserkennung oder biometrische Kategorisierung?
- Das System erzeugt Deepfakes (KI-generierte Bilder, Videos, Audio mit Ähnlichkeit zu realen Personen)?
- Das System erzeugt Texte, die öffentlich zugänglich sind, ohne erkennbar als KI-generiert zu sein?

**Wenn ja:** → Transparenzpflichten nach Art. 50 KI-VO → `begrenztes-risiko-art-50-transparenzpflichten`

**Wenn nein:** → Schritt 4.

### Schritt 4 — Minimales Risiko

Alle anderen KI-Systeme haben minimales Risiko. Keine spezifischen KI-VO-Pflichten. Freiwillige Verhaltenskodizes nach Art. 95 KI-VO sind möglich und können empfohlen werden.

## Hinweis zur Parallelprüfung

Ein System kann gleichzeitig mehreren Kategorien zugehören — etwa ein Hochrisiko-KI-System, das zugleich Chatbot-Eigenschaften hat (begrenzt) und damit sowohl umfangreichen Hochrisiko-Pflichten als auch Art. 50-Transparenzpflichten unterliegt.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
