---
name: hochrisiko-zuordnung-art-6-und-anhang-i-iii
description: "Uebersicht Hochrisiko-Zuordnung nach Art. 6 KI-VO: Sicherheitsbauteil plus Anhang I (Art. 6 Abs. 1) oder eigenstaendige Nennung in Anhang III (Art. 6 Abs. 2). Alle acht Anhang-III-Bereiche und die vier Rueckausnahmen nach Art. 6 Abs. 3 KI-VO."
---

# Hochrisiko-Zuordnung — Art. 6 KI-VO und Anhang I/III

## Zweck

Dieser Skill ist die erste Orientierung zu Art. 6 KI-VO. Er zeigt beide Pfade zur Hochrisiko-Einstufung und verweist auf die detaillierten Prüfskills für jeden Pfad. Vertiefende Entscheidungsbäume finden sich in `hochrisiko-art-6-abs-1-sicherheitsbauteil`, `hochrisiko-art-6-abs-2-anhang-iii` und `rueckausnahme-art-6-abs-3`.

## Zwei Pfade zur Hochrisiko-Einstufung

### Pfad 1 — Art. 6 Abs. 1 KI-VO: Sicherheitsbauteil + Anhang I + Drittprüfung

Ein KI-System gilt als Hochrisiko-KI-System, wenn beide Voraussetzungen erfüllt sind:
1. Es ist ein Sicherheitsbauteil eines Produkts oder ist selbst ein Produkt, das unter die in Anhang I aufgeführten Unionsvorschriften fällt.
2. Das Produkt (oder die Sicherheitskomponente) muss nach diesen Unionsvorschriften einer Konformitätsbewertung durch Dritte unterzogen werden.

**Anhang I enthält unter anderem:** Maschinen (VO (EU) 2023/1230), Spielzeug (Richtlinie 2009/48/EG), Luftfahrt-Bauteile (VO (EU) 2018/1139), Medizinprodukte (VO (EU) 2017/745), In-vitro-Diagnostika (VO (EU) 2017/746), Druckgeräte, Aufzüge, Funkanlagen, Kraftfahrzeuge, Schifffahrt, Eisenbahn.

→ Detailprüfung: `hochrisiko-art-6-abs-1-sicherheitsbauteil`

### Pfad 2 — Art. 6 Abs. 2 KI-VO: Eigenständige Nennung in Anhang III

Ein KI-System gilt als Hochrisiko-KI-System, wenn es in Anhang III der KI-VO aufgeführt ist oder eine der dort genannten Verwendungsweisen aufweist.

**Anhang III — Acht Bereiche:**

1. Biometrische Identifikation und Kategorisierung natürlicher Personen (außer Ausnahmen)
2. Kritische Infrastruktur: Betrieb und Verwaltung kritischer Infrastruktur (Wasser, Gas, Strom, Verkehr)
3. Bildung und Berufsausbildung: Zulassung, Bewertung, Prüfungsergebnisse, Lernfortschritt
4. Beschäftigung und Arbeitnehmerverwaltung: Personalauswahl, Beförderung, Kündigung, Überwachung
5. Wesentliche private und öffentliche Dienstleistungen: Kreditwürdigkeit, Sozialleistungen, Notfalldienste
6. Strafverfolgung: Risikoabschätzung von Personen, Polygraphen, Zuverlässigkeit von Beweismitteln, Profiling
7. Migration, Asyl, Grenzkontrolle: Risikoabschätzung, Identitätsprüfung, Entscheidungen zu Asyl und Grenzübertritt
8. Justiz und demokratische Prozesse: Anwendung der Rechtsvorschriften, Auslegung von Tatsachen, Wahlbeeinflussung

→ Detailprüfung: `hochrisiko-art-6-abs-2-anhang-iii`

## Rückausnahme Art. 6 Abs. 3 KI-VO

Auch bei Vorliegen eines Anhang-III-Tatbestands können KI-Systeme ausnahmsweise nicht als Hochrisiko eingestuft werden, wenn sie keine erhebliche Risiken für Gesundheit, Sicherheit oder Grundrechte darstellen. Vier Fallgruppen:
1. Enge Verfahrensaufgabe
2. Verbesserung des Ergebnisses einer menschlichen Tätigkeit
3. Erkennung von Mustern ohne Ersetzung menschlicher Bewertung
4. Vorbereitende Aufgabe

**Sicherungsklausel:** Profiling natürlicher Personen ist stets Hochrisiko — keine Rückausnahme.

→ Detailprüfung: `rueckausnahme-art-6-abs-3`

## Folgen der Hochrisiko-Einstufung

Liegt eine Hochrisiko-Einstufung vor, greifen für Anbieter folgende Pflichten:
- Risikomanagementsystem (Art. 9 KI-VO)
- Datenqualität und Data Governance (Art. 10 KI-VO)
- Technische Dokumentation (Art. 11 und Anhang IV KI-VO)
- Logging und Aufzeichnung (Art. 12 KI-VO)
- Transparenz gegenüber Betreibern (Art. 13 KI-VO)
- Menschliche Aufsicht (Art. 14 KI-VO)
- Genauigkeit und Cybersicherheit (Art. 15 KI-VO)
- Konformitätsbewertung und CE-Kennzeichnung (Art. 43 bis 49 KI-VO)
- Registrierung in EU-Datenbank (Art. 49 i.V.m. Art. 71 KI-VO)

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
