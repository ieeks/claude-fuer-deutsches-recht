---
name: hochrisiko-aufzeichnungspflichten-logging-art-12
description: "Logging-Pflichten fuer Hochrisiko-KI nach Art. 12 KI-VO: automatische Ereignisaufzeichnung Mindestinhalte der Logs Aufbewahrungsfristen Verantwortung von Anbieter und Betreiber. Besondere Anforderungen fuer biometrische Identifikation."
---

# Aufzeichnungspflichten und Logging — Art. 12 KI-VO

## Zweck

Art. 12 KI-VO verpflichtet Anbieter von Hochrisiko-KI-Systemen, sicherzustellen, dass das System automatisch Ereignisse protokolliert. Diese Logs dienen der Rückverfolgung, der Überwachung nach dem Inverkehrbringen und der Aufklärung von Vorfällen.

## Grundanforderung: Automatische Protokollierung (Art. 12 Abs. 1 KI-VO)

Hochrisiko-KI-Systeme müssen automatisch Ereignisse protokollieren, die für die Kontrolle des Systembetriebs und die Ermittlung von Risiken nach dem Inverkehrbringen relevant sind.

**Grundsatz:** Die Protokollierung muss technisch in das System integriert sein — manuelle Nacherfassung genügt nicht.

## Mindestinhalt der Logs (Art. 12 Abs. 2 KI-VO)

Die Protokolle müssen mindestens enthalten:
- Zeitstempel jedes Ereignisses
- Referenzdatenbankeinträge (wenn das System mit Datenbanken arbeitet)
- Eingabedaten (soweit relevant für die Nachvollziehbarkeit)
- Identität der natürlichen Personen, die an der Überprüfung der Ergebnisse beteiligt sind (wo zutreffend)
- Datum, Uhrzeit und Ort des Betriebs des Systems

**Prüffragen:**
- Protokolliert das System automatisch alle relevanten Ereignisse?
- Sind Zeitstempel, Eingaben und Ausgaben nachvollziehbar erfasst?
- Werden Identitäten der beteiligten Personen (wo relevant) erfasst?

## Besondere Anforderungen — Biometrische Fernidentifikation

Für biometrische Echtzeit-Fernidentifikationssysteme (die nur unter den engen Ausnahmen von Art. 5 Abs. 2 KI-VO zulässig sind) gelten besonders strenge Protokollierungsanforderungen. Jeder Einsatz ist zu protokollieren, und die Protokolle müssen der Datenschutzbehörde auf Anfrage zugänglich gemacht werden.

## Verantwortungsverteilung zwischen Anbieter und Betreiber

**Anbieter:** Muss sicherstellen, dass das System technisch in der Lage ist, die erforderlichen Logs zu erstellen. Die Protokollierungsfähigkeit ist Teil der technischen Spezifikation.

**Betreiber:** Muss sicherstellen, dass die Protokolle tatsächlich erstellt, gespeichert und aufbewahrt werden. Betreiber sind nach Art. 26 Abs. 6 KI-VO verpflichtet, die Protokolle sechs Monate aufzubewahren, es sei denn, andere Vorschriften (z.B. DSGVO, nationales Recht) sehen kürzere oder längere Fristen vor.

**Prüffragen:**
- Welche Partei ist für die Protokollierung verantwortlich — Anbieter, Betreiber oder beide?
- Gibt es vertragliche Regelungen zwischen Anbieter und Betreiber zur Protokollierung (Art. 25 Abs. 4 KI-VO)?

## Aufbewahrungsfristen

- **Betreiber allgemein:** Sechs Monate Aufbewahrungspflicht (Art. 26 Abs. 6 KI-VO)
- **Biometrische Identifikation:** Besondere Fristen nach nationalem Recht oder Behördenanforderungen
- **Anbieter (technische Dokumentation):** Zehn Jahre (Art. 18 KI-VO)
- **Widerspruch mit DSGVO:** Protokolle, die personenbezogene Daten enthalten, müssen datenschutzkonform aufbewahrt und nach Ablauf der Frist gelöscht werden

## Verhältnis zu Post-Market-Monitoring

Die nach Art. 12 KI-VO erstellten Protokolle sind ein wesentliches Instrument für das Post-Market-Monitoring nach Art. 72 KI-VO. Ohne Protokolle kann ein ernsthafter Vorfall nicht aufgeklärt werden.

## Typische Lücken

- Protokollierung ist nicht automatisiert und basiert auf manuellen Einträgen.
- Logs werden nach kurzer Zeit automatisch gelöscht (z.B. für Datensparsamkeit), ohne Berücksichtigung der Aufbewahrungspflichten.
- Kein klarer Verantwortlicher für die Aufbewahrung der Logs.
- Logs enthalten keine ausreichenden Zeitstempel oder Kontextinformationen für die Rekonstruktion von Vorfällen.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
