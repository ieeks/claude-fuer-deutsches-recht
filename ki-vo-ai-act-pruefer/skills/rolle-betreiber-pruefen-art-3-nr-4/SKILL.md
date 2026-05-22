---
name: rolle-betreiber-pruefen-art-3-nr-4
description: "Entscheidungsbaum: Bin ich Betreiber im Sinne von Art. 3 Nr. 4 KI-VO? Wer ein KI-System in eigener Verantwortung verwendet ausser fuer persoenliche nicht berufliche Taetigkeit. Abgrenzung zu Anbieter und zur persoenlichen Nutzung. Folgen der Betreiber-Rolle."
---

# Rolle-Check: Betreiber — Art. 3 Nr. 4 KI-VO

## Zweck

Die Betreiber-Rolle ist die zweithäufigste Rolle in der KI-Wertschöpfungskette. Dieser Skill klärt durch einen Entscheidungsbaum, ob die Nutzer-Rolle als Betreiber qualifiziert.

## Legaldefinition — Art. 3 Nr. 4 KI-VO

Betreiber (deployer) ist eine natürliche oder juristische Person, Behörde, Einrichtung oder sonstige Stelle, die ein KI-System in eigener Verantwortung verwendet, es sei denn, das KI-System wird im Rahmen einer persönlichen, nicht beruflichen Tätigkeit verwendet.

## Entscheidungsbaum

### Schritt 1 — Verwendung eines fremden KI-Systems?

**Frage A:** Nutzen Sie ein KI-System, das nicht von Ihnen entwickelt wurde, und haben Sie es nicht wesentlich verändert?

- Ja → weiter zu Schritt 2
- Nein (eigene Entwicklung oder wesentliche Veränderung) → möglicherweise Anbieter; → `rolle-anbieter-pruefen-art-3-nr-3` oder `anbieter-werden-art-25`

### Schritt 2 — Verwendung in eigener Verantwortung

**Frage B:** Verwenden Sie das System in eigener Verantwortung — das heißt, Sie entscheiden selbst über Einsatzzweck, Bedingungen und Kontext?

- Ja → weiter zu Schritt 3
- Nein (Sie agieren ausschließlich als technischer Dienstleister für einen Dritten, der alle Entscheidungen trifft) → möglicherweise kein Betreiber; Klärung erforderlich

### Schritt 3 — Ausnahme: Persönliche, nicht berufliche Nutzung

**Frage C:** Handelt es sich um eine ausschließlich persönliche, nicht berufliche Nutzung?

- Nein (berufliche, gewerbliche, behördliche Nutzung) → Betreiber-Rolle bestätigt
- Ja (rein private Nutzung durch natürliche Person) → kein Betreiber; KI-VO gilt nicht (Art. 2 Abs. 10 KI-VO)

**Grenzfälle:**
- Freelancer, Selbstständige, Freiberufler, die das System für ihre Arbeit nutzen → Betreiber (nicht rein privat)
- Unternehmen, das das System für interne Prozesse nutzt → Betreiber
- Öffentliche Stellen, die das System für ihre Aufgaben nutzen → Betreiber (mit verschärften Pflichten nach Art. 27 KI-VO)

## Ergebnis

**Betreiber bestätigt, wenn:**
- Sie ein fremdes (nicht selbst entwickeltes, nicht wesentlich verändertes) KI-System nutzen UND
- die Nutzung in eigener Verantwortung erfolgt UND
- die Nutzung nicht ausschließlich privat ist

## Pflichten als Betreiber (Überblick)

Bei Hochrisiko-KI:
- Bestimmungsgemäße Verwendung nach Gebrauchsanweisung des Anbieters (Art. 26 Abs. 1 KI-VO)
- Menschliche Aufsicht sicherstellen (Art. 26 Abs. 2 KI-VO)
- Eingabedaten-Qualität sicherstellen (Art. 26 Abs. 3 KI-VO)
- Protokollaufbewahrung sechs Monate (Art. 26 Abs. 6 KI-VO)
- Informationspflicht gegenüber betroffenen Personen (Art. 26 Abs. 7 KI-VO)
- Meldung schwerwiegender Vorfälle an Anbieter (Art. 26 Abs. 5 KI-VO)
- Grundrechte-Folgenabschätzung für öffentliche Stellen und bestimmte Privatbetreiber (Art. 27 KI-VO)

Detail: → `betreiber-deployer-pflichten-art-26`

## Wann wird der Betreiber zum Anbieter?

Wenn der Betreiber:
- Das System unter eigenem Namen vermarktet
- Das System wesentlich verändert (technisch, im Einsatzzweck, in der Zielgruppe)
- Einen bestimmungsgemäßen Zweck hinzufügt, der sich erheblich vom ursprünglichen unterscheidet

→ dann greift Art. 25 KI-VO: Betreiber wird zum Anbieter → `anbieter-werden-art-25`

## Betreiber und GPAI-Systeme

Wer ein GPAI-System (z.B. einen Chatbot auf Basis eines Foundation-Modells) als Betreiber einsetzt, unterliegt in der Regel den Betreiber-Pflichten nach Art. 26 KI-VO. Die KI-VO-Pflichten des GPAI-Modell-Anbieters liegen beim Modellanbieter — aber der Betreiber muss sicherstellen, dass er das System bestimmungsgemäß einsetzt.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
