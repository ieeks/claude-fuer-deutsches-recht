---
name: norm-historie-und-aenderungen
description: "Prueft die Norm-Historie: geltende Fassung zum massgeblichen Zeitpunkt, Uebergangsvorschriften, intertemporales Recht, aenderungsrelevante Gesetzgebungsverfahren. Warnt bei Normen, die seit dem Wissensstand des Systems geaendert worden sein koennten."
---

# Norm-Historie und Änderungen

## Zweck

Subsumtion setzt voraus, dass die richtige Normfassung angewendet wird. Für zurückliegende Sachverhalte gilt das Recht zum Zeitpunkt des relevanten Ereignisses (Tatzeit, Vertragsschluss, Bescheiderlass). Dieser Skill prüft, welche Normfassung maßgeblich ist und weist auf Änderungen und Übergangsrecht hin.

## Prüfungsschritte

### Schritt 1 — Maßgeblicher Zeitpunkt

Das System fragt: Wann hat das relevante Ereignis stattgefunden?

- **Vertragsrecht:** Datum des Vertragsschlusses (ggf. AGB-Einbeziehung zum Zeitpunkt des Vertrags)
- **Deliktsrecht:** Datum der schädigenden Handlung
- **Strafrecht:** Tatzeitpunkt (§ 2 StGB: mildestes Gesetz von Tatzeit bis Urteil — lex mitior)
- **Verwaltungsrecht:** Datum des Bescheiderlasses oder der Widerspruchsentscheidung
- **Steuerrecht:** Veranlagungszeitraum

### Schritt 2 — Normfassung ermitteln

Das System weist hin auf:
- Die ihm bekannte aktuelle Fassung der Norm
- Bekannte Änderungen seit Inkrafttreten (z. B. Schuldrechtsmodernisierungsgesetz 2002 für BGB; DSGVO ab 25.05.2018; KI-VO ab 01.08.2024)
- Seinen Wissensstand und die damit verbundene Ungewissheit über Änderungen danach

**Empfehlung:** Immer die geltende konsolidierte Fassung auf gesetze-im-internet.de (bundesrecht) oder eur-lex.europa.eu (Unionsrecht) prüfen.

### Schritt 3 — Übergangsvorschriften

Übergangsvorschriften regeln, welche Normfassung auf Altfälle anzuwenden ist. Das System weist auf typische Muster hin:

- Stichtagsregelungen: Anwendung neuen Rechts ab einem bestimmten Datum
- Bestandsschutzklauseln: Altverträge bleiben unter altem Recht
- Rückwirkungsverbote (Art. 103 Abs. 2 GG im Strafrecht; Art. 20 Abs. 3 GG im Verwaltungsrecht)
- EU-Übergangsrecht: Geltungsbeginn von Verordnungen nach Übergangsfrist (z. B. DSGVO: 2-Jahres-Übergangsfrist; KI-VO: gestaffeltes Inkrafttreten)

### Schritt 4 — Intertemporales Recht

Das System unterscheidet:
- **Echte Rückwirkung** (belastend): verfassungsrechtlich grundsätzlich verboten (BVerfG ständige Rechtsprechung)
- **Unechte Rückwirkung** (auf laufende Sachverhalte): grundsätzlich zulässig, aber verhältnismäßig
- **Lex mitior im Strafrecht** (§ 2 Abs. 3 StGB): Bei Gesetzesänderung zwischen Tat und Urteil gilt das mildere Gesetz

### Schritt 5 — Hinweis auf Wissensgrenze

Das System gibt in jedem Fall den Hinweis: „Diese Angaben zur Normfassung entsprechen dem Wissensstand des Systems. Für Änderungen nach diesem Stand ist gesetze-im-internet.de oder eur-lex.europa.eu zu prüfen."

## Ausgabe

- Maßgeblicher Zeitpunkt (Nutzerangabe)
- Bekannte Normfassung zu diesem Zeitpunkt
- Wesentliche Änderungen (soweit systembekannt)
- Übergangsvorschriften (soweit einschlägig)
- Empfehlung zur Verifikation der geltenden Fassung

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
