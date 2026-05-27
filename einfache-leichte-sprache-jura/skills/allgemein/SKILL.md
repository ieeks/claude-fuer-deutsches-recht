---
name: allgemein
description: "Einstieg in das Plugin Einfache und Leichte Sprache Jura: Zielgruppe klaeren, Modus waehlen (Einfache Sprache B1 oder Leichte Sprache A2), Rechtsinhalt sichern und verfuegbare Werkzeuge ueberblicken."
---

# Einfache und Leichte Sprache Jura — Allgemein

## Worum geht es?

Juristische Texte — Bescheide, Vertraege, Urteile, Merkblaetter — sind fuer viele Buergerinnen und Buerger schwer verstaendlich. Dieses Plugin unterstuetzt Kanzleien und Behoerden dabei, solche Texte in Einfache Sprache (Zielniveau B1) oder Leichte Sprache (Zielniveau A2 gemaess BITV 2.0) zu uebertragen, ohne dabei Rechtsinhalt, Fristen oder Rechtswirkungen zu verlieren.

Das Plugin unterscheidet strikt zwischen Verstaendlichkeit und inhaltlicher Absicherung: Vereinfachungen muessen stets gegen das Original geprueft werden. Das Qualitaetsgate am Ende des Workflows sichert die Konformitaet vor Veroeffentlichung.

## Wann brauchen Sie diese Skill?

- Eine Behoerde will Bescheide oder Widerspruchsbeschluesse fuer Buerger mit eingeschraenkter Lesekompetenz aufbereiten.
- Eine Kanzlei erklaert Mandanten verstaendlich, welche Rechte und Pflichten ein Vertrag begruendet.
- Ein Unternehmen muss seine Datenschutzerklaerung barrierefrei gestalten (BITV 2.0, WCAG 2.1).
- Ein Pflegeheim oder eine Sozialeinrichtung will Heimvertraege in Leichte Sprache uebersetzen.
- Ein Verband prueft, ob sein oeffentlich zugaengliches Rechtsmerkblatt verstaendlich genug ist.

## Fachbegriffe (kurz erklaert)

- **Einfache Sprache** — Schriftsprachliche Vereinfachung auf ca. Niveau B1 des Europaeischen Referenzrahmens; kurze Saetze, gebraeuchliche Woerter, aktive Formulierungen.
- **Leichte Sprache** — Stark vereinfachte Sprache auf Niveau A2 nach BITV 2.0 und dem Regelwerk des Netzwerks Leichte Sprache; standardisierte Regeln zu Wortlaenge, Satzstruktur und Bildunterstuetzung.
- **BITV 2.0** — Barrierefreie-Informationstechnik-Verordnung; verpflichtet oeffentliche Stellen zur barrierefreien Gestaltung digitaler Angebote einschliesslich Leichter Sprache.
- **Rechtsinhalt-Sicherung** — Pruefung, dass nach der Vereinfachung keine Rechte, Pflichten, Fristen oder Rechtsfolgen verloren gegangen sind.
- **Qualitaetsgate** — Abschlusspruefung vor Veroeffentlichung: Verstaendlichkeit, Gleichgewicht zum Original, Glossar-Konsistenz, Barrierefreiheit.
- **Zielgruppe** — Definierte Personengruppe (z. B. Menschen mit Lernschwierigkeiten, Buerger ohne Rechtskenntnisse), nach der Schwierigkeitsgrad und Modus gewaehlt werden.

## Rechtsgrundlagen

- § 11 BGG (Barrierefreiheitsgebot oeffentlicher Stellen)
- BITV 2.0 — Barrierefreie-Informationstechnik-Verordnung
- § 3 BMAS-Richtlinie zu Leichter Sprache in Behoerden
- Art. 7 Abs. 2 DSGVO (Anforderungen an Einwilligungserklaerungen in verstaendlicher Sprache)
- § 305 Abs. 2 BGB (Einbeziehungsvoraussetzungen fuer AGB — Deutlichkeitsgebot)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Wer ist die Zielgruppe des vereinfachten Textes?
2. Modus festlegen: Einfache Sprache (B1) oder Leichte Sprache (A2)?
3. Rechtsinhalt erfassen: Alle relevanten Rechte, Pflichten, Fristen und Rechtsfolgen des Originaltexts sichern (Skill `elsj-juristische-sicherung`).
4. Vereinfachung erstellen: Passenden Skill waehlen (`elsj-einfache-sprache` oder `elsj-leichte-sprache`).
5. Qualitaetsgate durchlaufen: Fertige Fassung vor Veroeffentlichung pruefen (`elsj-qualitaetsgate`).

## Skill-Tour (was gibt es hier?)

- `elsj-kommandocenter` — Navigationszentrum: Zielgruppe und Modus klaeren, Workflow starten, alle Skills koordinieren.
- `elsj-einfache-sprache` — Juristischen Text auf Einfache Sprache Niveau B1 uebertragen fuer Buerger ohne Fachkenntnisse.
- `elsj-leichte-sprache` — Juristischen Text auf Leichte Sprache Niveau A2 uebertragen fuer Menschen mit Lernschwierigkeiten oder kognitiven Einschraenkungen.
- `elsj-juristische-sicherung` — Sicherstellt, dass kein Rechtsinhalt (Rechte, Pflichten, Fristen, Betraege, Rechtsfolgen) bei der Vereinfachung verloren geht.
- `elsj-qualitaetsgate` — Abschlusspruefung der vereinfachten Fassung vor Veroeffentlichung auf Verstaendlichkeit, Glaeubigkeit und Vollstaendigkeit.

## Worauf besonders achten

- Einfache Sprache und Leichte Sprache sind verschiedene Standards mit unterschiedlichen Regelwerken — Modus am Anfang festlegen, nicht waehrend der Bearbeitung wechseln.
- Kein Rechtsinhalt darf durch Vereinfachung verloren gehen: Fristen, Betraege und Rechtsfolgen muessen exakt erhalten bleiben.
- Leichte Sprache erfordert typischerweise die Einbindung von Prueferinnen und Pruefern mit kognitiven Einschraenkungen — das Plugin kann nur den Text liefern, nicht die Pruefung ersetzen.
- Bei Bescheiden und amtlichen Dokumenten gilt: Vereinfachungen sind Informationshilfen, kein rechtsverbindlicher Ersatz des Originaldokuments.
- AGB-Vereinfachungen koennen auf Einbeziehungsfragen nach § 305 BGB wirken — rechtliche Wechselwirkungen bedenken.

## Typische Fehler

- Zielgruppe nicht definiert: Text wird zu stark oder zu wenig vereinfacht, weil unklar ist, fuer wen er bestimmt ist.
- Rechtsinhalt-Sicherung uebersprungen: Fristen oder Rechtswirkungen gehen in der Vereinfachung unter.
- Einfache und Leichte Sprache verwechselt: Leichte Sprache hat deutlich strengere Regeln (Satzlaenge, Bildunterstuetzung, Glossar).
- Qualitaetsgate nicht durchgefuehrt: Vereinfachter Text wird veroeffentlicht, ohne auf Korrektheit geprueft zu werden.
- Vereinfachung als rechtsverbindlich behandelt: Mandant glaubt, der vereinfachte Text ersetzt das Original.

## Querverweise

- `datenschutzrecht` — DSGVO-Einwilligungen und Datenschutzerklaerungen muessen verstaendlich formuliert sein (Art. 7 Abs. 2 DSGVO).
- `vertragsrecht` — AGB-Einbeziehung nach § 305 BGB erfordert klare, verstaendliche Formulierungen.
- `selbstvertreter-amtsgericht` — Buerger ohne Rechtskenntnisse koennen von vereinfachten Gerichtsdokumenten profitieren.

## Quellen und Aktualitaet

- Stand: 05/2026
- BITV 2.0 in der Fassung vom 21.05.2019
- Gesetzesfassungen zum Stand-Datum
- Regelwerk Leichte Sprache des Netzwerks Leichte Sprache (netzwerk-leichte-sprache.org)
- WCAG 2.1 (Web Content Accessibility Guidelines)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
