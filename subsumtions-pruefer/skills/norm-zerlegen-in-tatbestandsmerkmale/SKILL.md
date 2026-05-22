---
name: norm-zerlegen-in-tatbestandsmerkmale
description: "Zerlegt eine Norm systematisch in ihre Tatbestandsmerkmale (TBM): geschriebene und ungeschriebene Merkmale, Definitionen aus h.M. und Rechtsprechung, Pruefungsreihenfolge. Grundlage fuer den Vier-Schritt der Subsumtion je TBM."
---

# Norm zerlegen in Tatbestandsmerkmale

## Zweck

Bevor subsumiert werden kann, muss die Norm in ihre Tatbestandsmerkmale (TBM) zerlegt werden. Dieser Skill führt die strukturierte Zerlegung durch, benennt Definitionen aus herrschender Meinung (h.M.) und Rechtsprechung und legt die Prüfungsreihenfolge fest.

## Methodik

### Schritt 1 — Normtext lesen und gliedern

Das System liest den Normtext und unterteilt in:
- **Tatbestand** (Voraussetzungen, die vorliegen müssen)
- **Rechtsfolge** (was bei Vorliegen des Tatbestands gilt)
- **Ausnahmen / Gegenausnahmen** (soweit in der Norm selbst geregelt)

Bei mehrgliedrigen Normen (mehrere Absätze, Alternativen, Nummern) werden alle Varianten einzeln aufgeführt.

### Schritt 2 — TBM-Liste erstellen

Pro Norm wird eine nummerierte TBM-Liste erstellt. Beispiel für § 823 Abs. 1 BGB:

1. Handlung oder Unterlassen
2. Verletzung eines der geschützten Rechtsgüter (Leben, Körper, Gesundheit, Freiheit, Eigentum oder sonstiges Recht)
3. Widerrechtlichkeit
4. Verschulden (Vorsatz oder Fahrlässigkeit § 276 BGB)
5. Schaden
6. Kausalität: haftungsbegründend (Handlung → Rechtsgutsverletzung) und haftungsausfüllend (Rechtsgutsverletzung → Schaden)

### Schritt 3 — Definitionen aus h.M. und Rechtsprechung

Zu jedem TBM nennt das System die Legaldefinition (soweit vorhanden) oder die in Rechtsprechung und h.M. anerkannte Definition. Beispiele:

- „Handlung": jedes menschliche Verhalten, das vom Willen beherrschbar ist (BGH ständige Rechtsprechung)
- „Fahrlässigkeit": Außerachtlassen der im Verkehr erforderlichen Sorgfalt (§ 276 Abs. 2 BGB)
- „Schaden": Differenz zwischen tatsächlichem und hypothetischem Vermögenszustand (Differenzhypothese)

### Schritt 4 — Ungeschriebene TBM

Das System weist auf judikativ entwickelte ungeschriebene Merkmale hin (z. B. bei § 823 Abs. 1 BGB: Verkehrspflichten als ungeschriebenes Pflichtengebot). Details in Skill `ungeschriebene-merkmale-judikatur`.

### Schritt 5 — Prüfungsreihenfolge

Das System legt die Prüfungsreihenfolge nach anerkanntem Schema fest:
- Bei Anspruchsgrundlagen: Entstehung → Erlöschen → Durchsetzbarkeit
- Bei Straftatbeständen: Tatbestand (obj. / subj.) → Rechtswidrigkeit → Schuld
- Bei Grundrechten: Schutzbereich → Eingriff → Rechtfertigung

### Schritt 6 — Übergabe an Subsumtion

Nach der TBM-Liste übergibt das System je TBM an den Skill `subsumtion-obersatz-definition-untersatz-ergebnis`.

## Besonderheiten bei Unionsrecht

Bei EU-Normen benennt das System zusätzlich:
- Erwägungsgründe (ErwGr) als Auslegungshilfe
- EuGH-Leitentscheidungen zur Normauslegung
- Unterschied zwischen autonomer unionsrechtlicher Auslegung und mitgliedstaatlichem Ermessen

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
