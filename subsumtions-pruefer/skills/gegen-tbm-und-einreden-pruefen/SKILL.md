---
name: gegen-tbm-und-einreden-pruefen
description: "Prueft rechtshindernde, rechtsvernichtende und rechtshemmende Einwendungen und Einreden: Nichtigkeitsgründe, Anfechtung, Erfuellung, Aufrechnung, Verjährung, Zurueckbehaltungsrecht, Verwirkung, Verzicht. Strukturierte Gegenprüfung nach Anspruchsaufbau."
---

# Gegen-TBM und Einreden prüfen

## Zweck

Nach der positiven Subsumtion (Anspruch entstanden dem Grunde nach) prüft dieser Skill, ob Einwendungen oder Einreden des Anspruchsgegners den Anspruch ausschließen, vernichten oder hemmen. Dieser Schritt ist zwingend, bevor ein Ergebnis ausgegeben wird.

## Systematik der Gegenrechte

### 1. Rechtshindernde Einwendungen (Anspruch entsteht gar nicht)

Rechtshindernde Einwendungen verhindern die Entstehung des Anspruchs:
- **Geschäftsunfähigkeit** (§ 104 BGB): Rechtsgeschäft nichtig; Anspruch nie entstanden
- **Formmangel** (§ 125 BGB): Nichtigkeit bei Nichteinhaltung der gesetzlichen Form
- **Sittenwidrigkeit / Gesetzesverstoß** (§§ 134/138 BGB): Nichtigkeit
- **Anfechtung** (§§ 119/120/123 BGB i. V. m. § 142 Abs. 1 BGB): Nichtigkeit ex tunc (rückwirkend); Frist für Anfechtungserklärung beachten
- **AGB-Unwirksamkeit** (§§ 305 ff. BGB): Klausel nicht wirksam einbezogen oder inhaltlich unwirksam
- **Unmöglichkeit bei Vertragsschluss** (§ 311a BGB): Primärleistungspflicht entfällt

### 2. Rechtsvernichtende Einwendungen (Anspruch ist erloschen)

- **Erfüllung** (§ 362 BGB): Leistung bewirkt; Anspruch erloschen
- **Aufrechnung** (§§ 387 ff. BGB): Gegenforderung des Schuldners; Fälligkeit, Gleichartigkeit, Aufrechnungslage
- **Erlass** (§ 397 BGB): Vertraglicher Verzicht auf Forderung
- **Novation / Schuldübernahme**: Altes Schuldverhältnis durch neues ersetzt
- **Rücktritt** (§§ 346 ff. BGB): Rückabwicklung; Rücktrittsrecht muss vorliegen
- **Widerruf** (§§ 355 ff. BGB): Verbraucherverträge; Widerrufsfrist 14 Tage; beginnt mit Belehrung

### 3. Rechtshemmende Einreden (Anspruch besteht, ist aber nicht durchsetzbar)

- **Verjährung** (§§ 194 ff. BGB): Einrede, nicht Einwendung; muss erhoben werden (§ 214 BGB). Details in Skill `verjaehrung-fristen-pruefen`.
- **Zurückbehaltungsrecht** (§ 273 BGB / § 320 BGB): Leistung Zug-um-Zug; Fälligkeit der Gegenforderung
- **Einrede des nicht erfüllten Vertrags** (§ 320 BGB): Vorleistungspflicht beachten
- **Stundung**: Fälligkeit noch nicht eingetreten

### 4. Verwirkung (§ 242 BGB)

Zeit- und Umstandsmoment (Details in Skill `generalklauseln-pruefen`).

### 5. Mitverschulden (§ 254 BGB)

Kein vollständiger Ausschluss, aber Kürzung des Anspruchs. Das System fragt: Hat der Anspruchsteller selbst zum Schaden beigetragen? Welcher Anteil?

## Prüfungsschema

Das System geht folgende Fragen durch:

1. Liegt ein Nichtigkeitsgrund vor? (rechtshindernde Einwendung)
2. Liegt ein Erlöschensgrund vor? (rechtsvernichtende Einwendung)
3. Liegt eine Einrede vor? (rechtshemmende Einwendung — muss erhoben werden)
4. Liegt Mitverschulden vor? (§ 254 BGB — Anspruchsminderung)

Jede Einwendung / Einrede wird nach dem Vier-Schritt-Schema geprüft (Obersatz → Definition → Untersatz → Ergebnis).

## Ausgabe

Tabelle aller geprüften Gegenrechte mit Ergebnis (eingreifend / nicht eingreifend / fraglich). Gesamtergebnis: Anspruch besteht vollständig / gemindert / nicht durchsetzbar / nicht entstanden.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
