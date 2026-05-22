---
name: subsumtion-obersatz-definition-untersatz-ergebnis
description: "Fuehrt die klassische juristische Vier-Schritt-Subsumtion durch: Obersatz (Norm und Rechtsfolge), Definition (TBM-Inhalt aus h.M./Rspr.), Untersatz (Sachverhalt unter Definition), Ergebnis (TBM erfuellt ja/nein/fraglich). Ein Durchlauf pro Tatbestandsmerkmal."
---

# Subsumtion: Obersatz – Definition – Untersatz – Ergebnis

## Zweck

Dieses Vier-Schritt-Schema ist die Grundmethode juristischer Fallbearbeitung. Dieser Skill führt das Schema für jedes Tatbestandsmerkmal durch. Die Ergebnisse aller TBM werden am Ende zusammengeführt, um ein Gesamtergebnis zu bilden.

## Das Vier-Schritt-Schema

### Schritt 1 — Obersatz

Der Obersatz formuliert, welche Rechtsfolge eintreten soll, wenn der Tatbestand erfüllt ist, und nennt die Anspruchsgrundlage.

**Struktur:** „[Person A] könnte gegen [Person B] einen Anspruch auf [Rechtsfolge] aus [§ Norm] haben."

Beispiel: „K könnte gegen V einen Anspruch auf Schadensersatz in Höhe von EUR 5000 aus § 280 Abs. 1 BGB haben."

### Schritt 2 — Definition

Das TBM wird aus der herrschenden Meinung und/oder der Rechtsprechung definiert.

**Struktur:** „[TBM] liegt vor, wenn [Definition aus h.M./Rspr.]."

Beispiel: „Eine Pflichtverletzung liegt vor, wenn der Schuldner eine ihm obliegende Pflicht aus dem Schuldverhältnis nicht, nicht rechtzeitig oder nicht wie geschuldet erfüllt (§ 241 Abs. 1 BGB; BGH ständige Rechtsprechung)."

Das System gibt die Quelle der Definition an (Gesetz, BGH, EuGH, h.M.). Wenn die Definition unsicher ist, wird dies ausdrücklich markiert.

### Schritt 3 — Untersatz (Subsumtion)

Der Sachverhalt wird unter die Definition subsumiert. Das ist der eigentliche Subsumtionsakt.

**Struktur:** „Hier [hat A / liegt vor / fehlt es an]: [konkrete Sachverhaltsangabe des Nutzers]."

Beispiel: „Hier hat V die Lieferpflicht aus § 433 Abs. 1 BGB nicht erfüllt, indem er die Ware trotz Fälligkeit am 01.03.2025 nicht geliefert hat (Nutzerangabe: keine Lieferung erfolgt)."

Das System verwendet ausschließlich Tatsachen, die der Nutzer angegeben hat. Es erfindet keine Sachverhaltselemente.

**Kennzeichnung von Lücken:** Fehlt eine Tatsachenangabe, markiert das System das TBM als „offen" und listet auf, welche Beweise erforderlich sind (weiter in Skill `beweisbedarf-und-belege-erfassen`).

### Schritt 4 — Ergebnis

Das System schließt mit einem Ergebnis für das jeweilige TBM:
- „TBM [Name] ist erfüllt."
- „TBM [Name] ist nicht erfüllt, weil [Grund]."
- „TBM [Name] ist fraglich; Ergebnis hängt von weiteren Tatsachen / Beweisen / Auslegung ab."

## Gesamtergebnis

Nach Durchlauf aller TBM bildet das System ein Gesamtergebnis:
- Alle TBM erfüllt → Anspruch/Tatbestand besteht dem Grunde nach (vorbehaltlich Einreden und Einwendungen)
- Ein oder mehrere TBM nicht erfüllt → Anspruch/Tatbestand scheitert an [TBM-Name]
- TBM fraglich → Ergebnis offen; Hinweis auf Klärungsbedarf

## Grenzen

Das System subsumiert ausschließlich anhand der Nutzerangaben. Es kann nicht prüfen, ob die Angaben wahr sind, ob Beweise vorhanden sind oder ob eine Gegenseite die Tatsachen bestreiten wird. Jede Subsumtion steht unter dem Vorbehalt des Beweisergebnisses.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
