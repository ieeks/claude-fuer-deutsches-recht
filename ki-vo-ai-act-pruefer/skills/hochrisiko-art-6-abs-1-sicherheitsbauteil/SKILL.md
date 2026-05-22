---
name: hochrisiko-art-6-abs-1-sicherheitsbauteil
description: "Entscheidungsbaum Hochrisiko-KI nach Art. 6 Abs. 1 KI-VO: KI-System als Sicherheitsbauteil eines Produkts das unter Anhang-I-Sektorrecht faellt und Konformitaetsbewertung durch Dritte erfordert. Vollstaendige Anhang-I-Liste und Prueffragen."
---

# Hochrisiko-KI: Sicherheitsbauteil — Art. 6 Abs. 1 KI-VO

## Zweck

Art. 6 Abs. 1 KI-VO ist einer von zwei Pfaden zur Hochrisiko-Einstufung. Ein KI-System ist Hochrisiko, wenn es Sicherheitsbauteil eines Produkts ist, das unter Anhang-I-Sektorrecht fällt und einer Drittprüfung unterzogen werden muss. Dieser Skill prüft beide Voraussetzungen im Entscheidungsbaum.

## Zwei kumulativ zu erfüllende Voraussetzungen

### Voraussetzung 1 — Sicherheitsbauteil oder Produkt selbst

**Frage:** Ist das KI-System:
- (A) Ein Sicherheitsbauteil eines Produkts? Ein Sicherheitsbauteil ist nach Art. 3 Nr. 14 KI-VO eine Komponente eines Produkts oder Systems, die eine Sicherheitsfunktion für das Produkt oder System erfüllt, oder deren Ausfall oder Fehlfunktion die Gesundheit und Sicherheit von Personen oder Sachen gefährdet.
- (B) Oder selbst ein Produkt, das unter Anhang-I-Sektorrecht fällt?

**Abgrenzung:**
- Ein KI-System zur Qualitätskontrolle in einer Maschine: Sicherheitsbauteil, wenn es die Maschinensicherheit gewährleistet
- Ein autonomes Fahrzeugsystem: Kann selbst Produkt nach Anhang I sein
- Ein KI-System für die Verwaltung (z.B. HR-Software): Kein Sicherheitsbauteil

### Voraussetzung 2 — Anhang-I-Sektorrecht

Das Produkt (oder der Bereich des Sicherheitsbauteils) muss unter eines der in Anhang I aufgeführten Sektorrechtsakte fallen. Vollständige Liste:

| Nr. | Sektorrechtsakt |
|---|---|
| 1 | Maschinenverordnung (EU) 2023/1230 |
| 2 | Spielzeugrichtlinie 2009/48/EG |
| 3 | Richtlinie 2006/42/EG (aufgehoben durch Maschinenverordnung, Übergangsregeln beachten) |
| 4 | Richtlinie 2014/53/EU (Funkanlagen) |
| 5 | Richtlinie 2014/34/EU (ATEX — Geräte in explosionsgefährdeten Bereichen) |
| 6 | Richtlinie 2006/42/EG (Druckgeräte) — Verordnung (EU) 2014/68/EU |
| 7 | Verordnung (EU) 2016/424 (Seilbahnen) |
| 8 | Richtlinie 2013/29/EU (pyrotechnische Gegenstände) |
| 9 | Richtlinie 2014/90/EU (Schiffsausrüstung) |
| 10 | Richtlinie 2016/797/EU (Eisenbahnsystem) |
| 11 | Verordnung (EU) 2018/858 (Kraftfahrzeuge) |
| 12 | Verordnung (EU) 2019/2144 (Fahrzeugsicherheit) |
| 13 | Verordnung (EU) 2018/1139 (Luftfahrt) |
| 14 | Verordnung (EU) 2017/745 (Medizinprodukte — MDR) |
| 15 | Verordnung (EU) 2017/746 (In-vitro-Diagnostika — IVDR) |

**Prüffragen:**
- Fällt das Produkt, in das das KI-System integriert ist, unter einen dieser Sektorrechtsakte?
- Falls ja, welcher konkret?

### Voraussetzung 3 — Drittprüfung nach Sektorrecht erforderlich

Die dritte kumulativ erforderliche Voraussetzung: Das Produkt oder das KI-System als Sicherheitsbauteil muss nach dem einschlägigen Sektorrechtsakt einer Konformitätsbewertung durch eine dritte Partei (benannte Stelle) unterzogen werden.

**Prüffragen:**
- Sieht das einschlägige Sektorrecht eine Konformitätsbewertung durch eine benannte Stelle vor?
- Ist die benannte Stelle für das KI-System zuständig oder nur für das Gesamtprodukt?

**Wenn nur Selbstkonformitätsbewertung vorgesehen:** Art. 6 Abs. 1 KI-VO greift nicht. Prüfen Sie Art. 6 Abs. 2 KI-VO.

## Ergebnis des Entscheidungsbaums

**Hochrisiko nach Art. 6 Abs. 1 KI-VO, wenn:**
- KI-System ist Sicherheitsbauteil oder Produkt nach Anhang I UND
- Einschlägiges Sektorrecht erfordert Drittkonformitätsbewertung

**Keine Hochrisiko-Einstufung nach Art. 6 Abs. 1, wenn:**
- KI-System ist kein Sicherheitsbauteil oder kein Produkt nach Anhang I (→ prüfe Art. 6 Abs. 2)
- Sektorrecht erfordert keine Drittprüfung

**Folge bei Hochrisiko-Einstufung nach Art. 6 Abs. 1:**
- Konformitätsbewertung durch benannte Stelle (kein reines Selbstbewertungsmodul möglich für das KI-System)
- Koordination zwischen KI-VO-Konformitätsbewertung und Sektorrechts-Konformitätsbewertung

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
