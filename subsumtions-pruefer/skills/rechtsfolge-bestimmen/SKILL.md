---
name: rechtsfolge-bestimmen
description: "Bestimmt die Rechtsfolge nach erfolgreicher Subsumtion: Anspruchsinhalt, Hoehe, Tenor, Verwaltungsakt-Inhalt, Strafmass-Rahmen. Unterscheidet Primaeranspruch, Sekundaeranspruch und Nebenansprueche. Gibt Berechnungshinweise fuer Schadensersatz und Vertragsstrafen."
---

# Rechtsfolge bestimmen

## Zweck

Ist der Tatbestand erfüllt und sind Einwendungen und Einreden geprüft, bestimmt dieser Skill die konkrete Rechtsfolge. Er unterscheidet Primäransprüche (Erfüllung), Sekundäransprüche (Schadensersatz) und Nebenansprüche (Zinsen, Kosten) und gibt Hinweise auf die Berechnung.

## Kategorien von Rechtsfolgen

### Zivilrecht — Erfüllungsansprüche (Primär)

- Zahlung einer bestimmten Geldsumme (Hauptforderung)
- Herausgabe einer Sache (§ 985 BGB)
- Unterlassung einer Handlung (§ 1004 BGB; §§ 8 ff. UWG)
- Beseitigung einer Beeinträchtigung
- Vornahme einer Handlung (Leistungsurteil nach § 894 ZPO)

### Zivilrecht — Schadensersatz (Sekundär)

**Grundregel:** Naturalrestitution (§ 249 Abs. 1 BGB) — Herstellung des Zustands ohne das schädigende Ereignis.

**Ausnahme:** Geldersatz (§ 249 Abs. 2 BGB) — bei Körperverletzung oder Sachbeschädigung auf Wunsch des Gläubigers.

**Schadensberechnung:**
- Differenzhypothese: Vergleich hypothetischer Zustand ohne Ereignis vs. tatsächlicher Zustand
- Entgangener Gewinn (§ 252 BGB): Wahrscheinlichkeit nach gewöhnlichem Verlauf
- Immaterieller Schadensersatz / Schmerzensgeld (§ 253 Abs. 2 BGB): nur bei Körper-, Gesundheits-, Freiheits- oder sexueller Selbstbestimmungsverletzung; Betrag durch Gericht nach Billigkeitsgesichtspunkten

**Hinweis:** Schadenshöhe ist in EUR anzugeben. Das System gibt keine Prognose für Schmerzensgeldhöhen — es nennt nur Orientierungsrahmen aus der Schmerzensgeldtabelle (Hacks/Wellner/Häcker).

### Vertragsstrafe

§ 339 BGB: Verwirkung bei Pflichtverletzung; Höhe nach Vereinbarung. Das System prüft:
- Ist die Vertragsstrafe vereinbart? (Schriftform beachten)
- Ist sie verwirkt? (Pflichtverletzung nachgewiesen)
- Ist sie nach § 343 BGB herabzusetzen? (unangemessen hoch; Richterrecht)

### Nebenansprüche

- Verzugszinsen § 288 BGB: 5 Prozent über Basiszinssatz (Verbraucher); 9 Prozent über Basiszinssatz (B2B). Basiszinssatz aktuell bei Deutschen Bundesbank (bundesbank.de) prüfen.
- Prozesskosten (§ 91 ZPO): Unterlieger trägt; Berechnung nach GKG und RVG
- Rechtsanwaltskosten als Verzugsschaden (§§ 280/286 BGB): bei Beauftragung eines Anwalts nach Verzugseintritt

### Verwaltungsrecht — Verwaltungsakt-Inhalt

Das System beschreibt den Tenor eines Verwaltungsakts:
- Belastender VA (Gebot, Verbot, Nebenbestimmungen): Prüfung von Bestimmtheit § 37 VwVfG und Verhältnismäßigkeit
- Begünstigender VA (Genehmigung, Zulassung): Prüfung von Auflagen und Bedingungen

### Strafrecht — Strafrahmen

Das System nennt den gesetzlichen Strafrahmen (Mindest- und Höchststrafe nach StGB / Nebenstrafrecht) und weist auf strafzumessungsrelevante Umstände hin (§ 46 StGB). Es gibt keine Prognose für das konkrete Strafmaß.

## Ausgabe

Strukturierter Rechtsfolgenblock:
- Art der Rechtsfolge (Zahlung / Unterlassung / Beseitigung / Herausgabe / Strafrahmen)
- Betragshöhe oder Bandbreite (soweit aus Nutzereingaben berechenbar)
- Nebenansprüche
- Hinweis auf Vollstreckung (§§ 704 ff. ZPO / § 80 VwGO)

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
