---
name: output-pruefdokument-ki-vo-mit-warnhinweisen
description: "Generiert das abschliessende Pruefdokument des KI-VO-Workflows: Pflicht-Header keine Rechtsberatung Ergebnistabelle mit Risikoklasse Rolle Pflichten offene Punkte. Strukturierter Bericht mit Warnhinweisen und Handlungsempfehlungen."
---

# Output: Prüfdokument KI-VO mit Warnhinweisen

## Zweck

Dieser Skill generiert das abschließende Prüfdokument am Ende des KI-VO-Workflows. Es fasst alle ermittelten Erkenntnisse zu Risikoklasse, Rolle, Pflichten und offenen Punkten zusammen.

## Pflicht-Header (IMMER voranstellen)

```
══════════════════════════════════════════
MECHANISCHES PRÜFDOKUMENT — KI-VO
Verordnung (EU) 2024/1689 des Europäischen
Parlaments und des Rates

ACHTUNG: Dieses Dokument ist KEINE
Rechtsberatung. Es handelt sich um eine
mechanische Prüfung anhand der vom Nutzer
behaupteten Tatsachen. Die Richtigkeit der
Tatsachenangaben wurde nicht überprüft.

Für verbindliche Rechtsauskunft wenden Sie
sich an einen zugelassenen Rechtsanwalt.
══════════════════════════════════════════
```

## Ergebnistabelle — Risikoklasse

| Prüfpunkt | Ergebnis | Fundstelle |
|---|---|---|
| KI-System nach Art. 3 Nr. 1 KI-VO | Ja / Nein / Unklar | Art. 3 Nr. 1 KI-VO |
| Territorialer Anwendungsbereich | Gegeben / Nicht gegeben / Unklar | Art. 2 KI-VO |
| Sachliche Ausnahme | Ja (welche) / Nein | Art. 2 Abs. 3-12 KI-VO |
| Verbotene Praktik Art. 5 | Ja (welche) / Nein / Unklar | Art. 5 KI-VO |
| Hochrisiko Art. 6 Abs. 1 | Ja / Nein / Unklar | Art. 6 Abs. 1 i.V.m. Anhang I KI-VO |
| Hochrisiko Art. 6 Abs. 2 | Ja (Anhang-III-Bereich) / Nein / Unklar | Art. 6 Abs. 2 i.V.m. Anhang III KI-VO |
| Rückausnahme Art. 6 Abs. 3 | Greift / Greift nicht / Unklar | Art. 6 Abs. 3 KI-VO |
| Begrenztes Risiko Art. 50 | Ja / Nein | Art. 50 KI-VO |
| GPAI-Modell Art. 3 Nr. 63 | Ja / Nein / Unklar | Art. 3 Nr. 63 KI-VO |
| Systemisches Risiko Art. 51 | Ja / Nein / Unklar | Art. 51 KI-VO |

## Ergebnistabelle — Rolle

| Rolle | Trifft zu | Fundstelle |
|---|---|---|
| Anbieter | Ja / Nein / Unklar | Art. 3 Nr. 3 KI-VO |
| Betreiber | Ja / Nein / Unklar | Art. 3 Nr. 4 KI-VO |
| Einführer | Ja / Nein / Unklar | Art. 3 Nr. 6 KI-VO |
| Händler | Ja / Nein / Unklar | Art. 3 Nr. 7 KI-VO |
| Bevollmächtigter | Zu benennen / Nicht erforderlich | Art. 22 KI-VO |
| Produkthersteller | Ja / Nein | Art. 25 Abs. 1 KI-VO |
| Anbieter durch Rollenwechsel | Ja / Nein / Prüfen | Art. 25 KI-VO |

## Pflichtenkatalog nach Rolle und Risikoklasse

Das System listet die einschlägigen Pflichten auf Basis der ermittelten Risikoklasse und Rolle:

**Bei Hochrisiko-Anbieter:**
- Risikomanagementsystem Art. 9 KI-VO
- Datenqualität Art. 10 KI-VO
- Technische Dokumentation Art. 11 / Anhang IV KI-VO
- Logging Art. 12 KI-VO
- Transparenz gegenüber Betreibern Art. 13 KI-VO
- Menschliche Aufsicht Art. 14 KI-VO
- Genauigkeit/Robustheit/Cybersicherheit Art. 15 KI-VO
- Konformitätsbewertung Art. 43 bis 49 KI-VO
- EU-Konformitätserklärung Art. 47 / Anhang V KI-VO
- CE-Kennzeichnung Art. 48 KI-VO
- Registrierung EU-Datenbank Art. 49 / 71 KI-VO
- Post-Market-Monitoring Art. 72 KI-VO

## Offene Punkte — Klärungsbedarf

Das System listet Punkte auf, die nicht abschließend bewertet werden konnten:
- Nicht beantwortete Fragen des Nutzers
- Unklare Sachverhalte
- Punkte, die fachanwaltliche Prüfung erfordern

## Zeitplan-Hinweis

Das System weist auf anwendbare Übergangsfristen hin:
- Verbote Art. 5: seit 2. Februar 2025 anwendbar
- GPAI: seit 2. August 2025 anwendbar
- Hochrisiko Anhang III: ab 2. August 2026 anwendbar

## Abschluss-Disclaimer

```
Dieses Prüfdokument wurde auf Basis der vom
Nutzer gemachten Angaben erstellt. Es ersetzt
keine anwaltliche Beratung. Die KI-VO und ihre
Auslegung durch Leitlinien und Rechtsprechung
sind laufend im Blick zu behalten.
```

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
