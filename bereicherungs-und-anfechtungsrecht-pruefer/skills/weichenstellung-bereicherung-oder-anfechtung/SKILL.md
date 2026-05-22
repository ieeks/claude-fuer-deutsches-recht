---
name: weichenstellung-bereicherung-oder-anfechtung
description: "Entscheidender Triage-Knoten: Rechtsgrund ja oder nein? Insolvenzverfahren eröffnet oder drohend? Vollstreckungstitel vorhanden? Leitet zum richtigen Regelungskreis weiter."
---

# Weichenstellung: Bereicherung oder Anfechtung?

## Zweck

Nach der Tatsachenerfassung entscheidet dieser Skill, welcher Regelungskreis einschlägig ist. Die drei Hauptpfade schließen sich nicht vollständig aus — Konkurrenzen sind möglich.

## Weichenstellungs-Schema

### Frage 1: Liegt ein Rechtsgrund für die Vermögensverschiebung vor?

**Kein Rechtsgrund** (Vertrag nichtig, nie zustande gekommen, weggefallen):
→ Bereicherungsrecht §§ 812 ff. BGB ist der richtige Pfad.
→ Skill: `leistungskondiktion-grundtatbestand-812-i-1-alt-1` oder `nichtleistungskondiktion-grundtatbestand-812-i-1-alt-2`

**Rechtsgrund vorhanden** (wirksamer Vertrag, gesetzliche Pflicht, behördlicher Bescheid):
→ Weiter zu Frage 2.

### Frage 2: Ist ein Insolvenzverfahren eröffnet oder beantragt?

**Insolvenzverfahren eröffnet oder Antrag gestellt:**
→ Insolvenzanfechtung §§ 129 ff. InsO.
→ Einstieg: `inso-grundtatbestand-129-glaeubigerbenachteiligung`

**Kein Insolvenzverfahren:**
→ Weiter zu Frage 3.

### Frage 3: Liegt ein vollstreckbarer Titel vor?

**Vollstreckbarer Titel vorhanden** (Urteil, Vollstreckungsbescheid, vollstreckbare notarielle Urkunde):
→ AnfG-Anfechtung nach § 2 AnfG möglich.
→ Einstieg: `anfg-grundtatbestand-und-anfechtungsberechtigte`

**Kein Vollstreckungstitel:**
→ AnfG nicht unmittelbar anwendbar; Klage auf Feststellung oder Leistung prüfen.

## Kombinationen und Besonderheiten

- Bereicherungsrecht und AnfG können nebeneinander stehen, wenn der Rechtsgrund nachträglich entfällt.
- Bei eröffnetem Insolvenzverfahren verdrängt § 129 InsO in der Regel den AnfG-Pfad.
- Ein Vorsatzanfechtungsanspruch nach § 133 InsO kann mit § 826 BGB (sittenwidrige Schädigung) konkurrieren.

## Merksatz

Kein Rechtsgrund → Bereicherungsrecht.
Rechtsgrund + kein Insolvenzverfahren + Titel → AnfG.
Rechtsgrund + Insolvenzverfahren → InsO-Anfechtung.
---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Falsche Normwahl oder unvollständiger Sachverhalt kann das Ergebnis vollständig entwerten.
