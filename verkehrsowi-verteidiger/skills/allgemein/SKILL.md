---
name: allgemein
description: "Einstieg in das VerkehrsOWi-Plugin für Bußgeldbescheid, Anhoerung, Einspruch, Punkte, Fahrverbot, Messverfahren, Akteneinsicht und Hauptverhandlung am Amtsgericht."
---

# VerkehrsOWi-Verteidiger — Allgemein

## Worum geht es?

Dieses Plugin begleitet Verkehrs-Ordnungswidrigkeitsmandate von der ersten Anhoerung bis zur Rechtsbeschwerde. Es richtet sich an Rechtsanwaelte, die Mandanten bei Bussgeldbescheiden, Fahrverboten, Punkteeintragungen und Verfahren vor dem Amtsgericht vertreten. Abgedeckt werden Geschwindigkeitsmessungen, Rotlicht-OWi, Abstandsverfahren, Handyverstaesse, Alkohol und Drogen am Steuer, Fahreridentifizierung sowie die Beweisverwertung standardisierter Messverfahren.

Das Plugin folgt dem Verfahrensablauf: Anhoerung → Bussgeldbescheid → Einspruch → Akteneinsicht/Messakte → Hauptverhandlung → ggf. Rechtsbeschwerde. Jede Phase hat eigene Fristen und Verteidigungsstrategien.

## Wann brauchen Sie diese Skill?

- Mandant erhaelt Anhoerungsbogen oder Bussgeldbescheid wegen Geschwindigkeitsueberschreitung und braucht sofortige Beratung zu Einspruchsfrist und Strategie.
- Mandant ist auf den Fuehrerschein beruflich angewiesen und soll Fahrverbot erhalten — Haertefall-Argumentation pruefen.
- Anwalt hat Akteneinsicht beantragt und will Messakte auf Verfahrensfehler untersuchen.
- Mandant bestreitet Fahrereigenschaft — Fahreridentifizierungsstrategie entwickeln.
- OWi-Urteil des Amtsgerichts ist unbefriedigend und Rechtsbeschwerde zum OLG wird erwaogen.

## Fachbegriffe (kurz erklaert)

- **OWiG** — Gesetz ueber Ordnungswidrigkeiten; Rahmengesetz fuer alle Ordnungswidrigkeitsverfahren einschliesslich VerkehrsOWi.
- **StVG** — Strassenverkehrsgesetz; § 24 StVG Grundnorm fuer Verkehrsordnungswidrigkeiten, § 25 StVG Fahrverbot.
- **FAER** — Fahreignungsregister; Punkteregister in Flensburg beim Kraftfahrt-Bundesamt.
- **Messakte** — Vollstaendige Unterlagen zum Messvorgang: Eichschein, Rohmessdaten, Geraetefoto, Aufstellprotokoll.
- **Standardisiertes Messverfahren** — Pruefstandsgerechtes Verfahren mit amtlich anerkanntem Messgeraet; Gerichte duerfen auf Beweiswert vertrauen, solange keine konkreten Fehlerhinweise vorliegen.
- **Verfolgungsverjaehrung** — Nach §§ 26 StVG und 31 ff. OWiG: Verjaeht die Tat, kann kein Bussgeld mehr verhaengt werden.
- **Rechtsbeschwerde** — Rechtsmittel nach § 79 OWiG zum Oberlandesgericht gegen Urteil des Amtsgerichts im OWi-Verfahren.
- **Haertefall** — Ausnahme vom Fahrverbot nach § 25 StVG, wenn unverhieltnisgemaessige berufliche Folgen drohen.

## Rechtsgrundlagen

- § 24 StVG (Ordnungswidrigkeiten im Strassenverkehr)
- § 25 StVG (Fahrverbot)
- §§ 26 StVG (Verfolgungsverjaehrung)
- §§ 24a StVG (Alkohol- und Drogenfahrten)
- §§ 67 ff. OWiG (Einspruch gegen Bussgeldbescheid)
- § 79 OWiG (Rechtsbeschwerde zum OLG)
- §§ 62-66 OWiG (Akteneinsicht im OWi-Verfahren)
- BKatV (Bussgeldkatalogverordnung mit Regelbuessgeldern und Fahrverboten)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Aktenanlage und Mandat aufnehmen: Tatvorwurf, Verfahrensstadium, Fristen erfassen (`verkehrsowi-aktenanlage`).
2. Einspruchsfrist pruefen: Zwei Wochen ab Zustellung des Bussgeldbescheids — Fristwahrung hat Vorrang (`verkehrsowi-fristen-einspruch`).
3. Akteneinsicht und Messakte beantragen und auswerten (`verkehrsowi-akteneinsicht-messakte`).
4. Verteidigungsstrategie festlegen: Messverfahren angreifen, Fahreridentifizierung, Haertefall?
5. Quality-Gate vor Einspruch und vor Hauptverhandlung durchlaufen (`verkehrsowi-quality-gate`).

## Skill-Tour (was gibt es hier?)

- `verkehrsowi-kommandocenter` — Zentrales Steuerungsmodul: schnelle Orientierung fuer jedes OWi-Mandat vom Intake bis zur Strategie.
- `verkehrsowi-aktenanlage` — Akte im VerkehrsOWi-Mandat anlegen und strukturieren.
- `verkehrsowi-anhoerung-bussgeldbescheid` — Reaktion auf Anhoerungsbogen oder Bussgeldbescheid strategisch vorbereiten.
- `verkehrsowi-fristen-einspruch` — Einspruchsfrist berechnen und wahren; Fristversaeumnis-Risiken erkennen.
- `verkehrsowi-akteneinsicht-messakte` — Vollstaendige Messakte anfordern und auf Verfahrensfehler und Eichluecken pruefen.
- `verkehrsowi-messverfahren-geschwindigkeit` — Geschwindigkeitsmessungen (TraffiStar, Riegl, ESO) auf Verwertbarkeit angreifen.
- `verkehrsowi-beweisverwertung-standardisiert` — Beweisverwertbarkeit im standardisierten Messverfahren angreifen.
- `verkehrsowi-rotlicht-abstand-handy` — Rotlicht-, Abstands- und Handy-OWi verteidigen.
- `verkehrsowi-alkohol-drogen-24a` — Alkohol- und Drogen-OWi nach § 24a StVG verteidigen (0,5-Promille, Drogennachweis).
- `verkehrsowi-fahreridentifizierung` — Fahrereigenschaft angreifen oder Fahreridentifizierung als Verteidigungsstrategieklaeren.
- `verkehrsowi-punkte-fahrverbot-flensburg` — Punkte im FAER und Fahrverbot nach § 25 StVG pruefen und Massnahmen besprechen.
- `verkehrsowi-haertefall-fahrverbot` — Haertefall-Argumentation gegen Fahrverbot bei beruflicher Angewiesenheit entwickeln.
- `verkehrsowi-verjaehrung-zustellung` — Verfolgungsverjaehrung pruefen und Zustellungsfehler identifizieren.
- `verkehrsowi-hauptverhandlung-amtsgericht` — Hauptverhandlung am Amtsgericht vorbereiten und fuehren.
- `verkehrsowi-rechtsbeschwerde` — Rechtsbeschwerde nach § 79 OWiG zum OLG einlegen.
- `verkehrsowi-zeugen-polizei-strategie` — Zeugen-Strategie gegenueber Polizeibeamten in der Hauptverhandlung entwickeln.
- `verkehrsowi-quality-gate` — Checkliste vor Einspruch, nach Akteneingang und vor Hauptverhandlung durchlaufen.
- `verkehrsowi-mandantenkommunikation` — Mandant verstaendlich ueber Verfahren, Kosten und Aussichten informieren.
- `verkehrsowi-rechtsprechungsrecherche` — OLG-Entscheidungen zu Messverfahren, Rohmessdaten und Fahrverboten recherchieren.
- `verkehrsowi-simulation-training` — Simulationstraining fuer OWi-Mandate: Messverfahren, Rotlicht, Handy, Alkohol, Fahreridentifizierung.

## Worauf besonders achten

- Einspruchsfrist ist zwei Wochen ab Zustellung — keine Hemmung, kein Neubeginn bei blossem Schweigen; Fristverpassen = Rechtskraft.
- Verfolgungsverjaehrung nach § 26 StVG betraegt 3 Monate ab Tatbegehung, Unterbrechung durch behordliche Massnahmen — Zeitstrahl pruefen.
- Akteneinsicht in Messakte inklusive Rohmessdaten ist einzufordern; ohne Rohmessdaten ist effektive Verteidigung eingeschraenkt.
- Haertefall-Fahrverbot: Nicht jede berufliche Betroffenheit genuegt — wirtschaftliche Existenzgefaehrdung oder alternativlose Infrastruktur noetig.
- Rechtsbeschwerde setzt Anwaltszwang voraus (§ 79 Abs. 3 OWiG i. V. m. § 341 StPO analog).

## Typische Fehler

- Einspruch ohne gleichzeitige Akteneinsicht: Verteidigung beginnt blind ohne Kenntnis der Messumstaende.
- Schweigen im Anhoerungsbogen unterlassen: Mandant macht Angaben, die spaeter als Beweismittel verwendet werden.
- Fahreridentifizierungsstrategie zu spaet entwickelt: Fotoabgleich wird im Bussgeldbescheid bereits verwendet und nicht mehr angegriffen.
- Haertefall nicht rechtzeitig vorgetragen: Amtsgericht prueft von Amts wegen nicht — Vortrag Sache des Verteidigers.
- Rechtsbeschwerde ohne Zulassungsgrund: Nur bei Verfahrensfehlern oder Rechtsfragen von grundsaetzlicher Bedeutung zulaessig.

## Querverweise

- `selbstvertreter-amtsgericht` — Fuer Mandanten ohne Anwalt gibt es das amtsgerichtliche Selbstvertretungs-Plugin.
- `datenschutzrecht` — Messdaten aus Fahrzeugkameras und Datenerhebung durch Blitzergeraete haben datenschutzrechtliche Dimensionen.

## Quellen und Aktualitaet

- Stand: 05/2026
- StVG in der zum Stand-Datum geltenden Fassung
- OWiG in der geltenden Fassung
- BKatV (Bussgeldkatalogverordnung) in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
