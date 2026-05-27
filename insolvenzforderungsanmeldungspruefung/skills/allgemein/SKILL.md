---
name: allgemein
description: "Einstieg und Orientierung fuer das Insolvenzforderungsanmeldungspruefungs-Plugin: Intake, Formalprüfung nach § 174 InsO, Belege, Grund, Betrag, Rang, vbuH, Nachforderungen, Tabellenimport, Pruefungstermin, Bestreiten, Feststellung, Tabellenauszug und Verteilung nach InsO."
---

# Insolvenzforderungsanmeldungspruefung — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Insolvenzverwalter, Pruefungsstellen und Kanzleien bei der strukturierten Pruefung von Insolvenzforderungsanmeldungen nach §§ 174-189 InsO. Es deckt den gesamten Pruefpfad ab: vom kanaluebergreifenden Eingang der Anmeldungen ueber Formalprüfung, Belegprüfung, Anspruchsgrundlage, Betrag, Zinsen, Rangprüfung und vorsaetzlich begangene unerlaubte Handlung (vbuH) bis hin zu Pruefungstermin, Bestreitungsverfahren, Tabelleneintrag, Tabellenauszug und Verteilung.

Das Plugin ist freistehend und eignet sich sowohl fuer Einzelforderungen als auch fuer Massenverfahren mit strukturiertem Batchregister.

## Wann brauchen Sie diese Skill?

- Sie sind Insolvenzverwalter und erhalten einen neuen Stapel von Forderungsanmeldungen nach § 174 InsO.
- Sie muessen Formalmaengel in einer Forderungsanmeldung identifizieren und ein Maengelschreiben erstellen.
- Sie bereiten den Pruefungstermin nach § 176 InsO vor und benoetigen eine strukturierte Terminmappe.
- Ein Glaeubiger hat die Forderung als vbuH gekennzeichnet und Sie muessen die Restschuldbefreiungsrelevanz pruefen.
- Sie bereiten die Schlussverteilung vor und muessen bestrittene Forderungen nach § 189 InsO korrekt behandeln.

## Fachbegriffe (kurz erklaert)

- **Forderungsanmeldung** — Erklaerung des Glaeubiger gegenueber dem Insolvenzgericht oder Insolvenzverwalter ueber seine Insolvenzforderung (§ 174 InsO).
- **Tabelle** — Das vom Insolvenzgericht gefuehrte Verzeichnis aller angemeldeten Insolvenzforderungen (§ 175 InsO).
- **Pruefungstermin** — Termin beim Insolvenzgericht, in dem Forderungen auf Feststellung oder Bestreitung geprüft werden (§ 176 InsO).
- **Feststellungswirkung** — Die anerkannte Forderung wirkt wie ein rechtskraeftiger Titel gegen den Schuldner (§ 178 InsO).
- **vbuH** — Vorsaetzlich begangene unerlaubte Handlung; Forderungen aus vbuH sind von der Restschuldbefreiung ausgenommen (§ 302 Nr. 1 InsO).
- **Nachrang** — Insolvenzforderungen, die erst nach den einfachen Insolvenzforderungen befriedigt werden (§ 39 InsO).
- **Absonderungsrecht** — Recht bestimmter Glaeubiger, aus bestimmten Gegenstanden der Insolvenzmasse vorab befriedigt zu werden (§§ 49-51 InsO).

## Rechtsgrundlagen

- §§ 38-39 InsO — Insolvenzforderungen und Nachrang
- §§ 47-51 InsO — Aussonderung und Absonderungsrechte
- §§ 53-55 InsO — Masseverbindlichkeiten
- §§ 174-177 InsO — Anmeldung und Nachtragsanmeldung
- §§ 178-183 InsO — Feststellung, Bestreiten und Wirkung
- §§ 184-186 InsO — Schuldnerwiderspruch
- §§ 188-196 InsO — Verteilung und Schlussverteilung
- § 302 InsO — Ausnahmen von der Restschuldbefreiung (vbuH)
- § 850f Abs. 2 ZPO — Pfaendungsfreigrenze bei vbuH

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Verwalterrolle, Verfahrensstand (Eroeffnung, Pruefungstermin, Verteilung), Forderungstyp.
2. Phase des Mandats bestimmen: Eingangserfassung, Formalprüfung, inhaltliche Pruefung, Entscheidung, Termin oder Verteilung.
3. Passenden Skill auswaehlen (siehe Skill-Tour).
4. Eilfristen pruefen: Pruefungstermin-Termin, Frist Schuldnerwiderspruch (§ 184 InsO Monatsfrist), Verteilungs-Nachweis (§ 189 InsO).
5. Anschluss-Skill bestimmen: nach Formalprüfung folgt inhaltliche Pruefung; nach Pruefungstermin folgt Tabelleneintrag oder Streitverfahren.

## Skill-Tour (was gibt es hier?)

**Einstieg und Steuerung**

- `ifap-kommandocenter` — Steuerung des gesamten Pruefpfads von Eingang bis Tabelle; zeigt naechste Schritte und Fristen an.
- `ifap-intake-kanalcheck` — Kanaluebergreifende Eingangserfassung: Post, E-Mail, Portal, Tabellenexport und Nachtrag.
- `ifap-aktenanlage-batchregister` — Strukturiertes Batchregister fuer Massenverfahren mit Glaeubigerstamm, Fristen und Audit-Trail.

**Formalprüfung**

- `ifap-formalpruefung-174` — Formalprüfung nach § 174 InsO: Pflichtinhalt, Glaeubiger, Anspruchsgrund, Betrag, Urkundenvorlage.
- `ifap-beleg-und-urkundencheck` — Prueft Belegkette (Rechnungen, Vertraege, Titel) auf Vollstaendigkeit und Beweiswert.
- `ifap-dubletten-serienforderungen` — Erkennt Doppelerfassungen und Serienforderungen (z.B. Inkasso und Originalglaeubiger parallel).
- `ifap-nachtraegliche-anmeldung-177` — Behandlung verspaeteter Forderungsanmeldungen nach § 177 InsO mit Kostenpflicht und Sondertermin.
- `ifap-nachforderung-maengelschreiben` — Erstellt praezises Maengelschreiben bei unvollstaendiger Anmeldung mit konkreten Nachforderungen.

**Inhaltliche Pruefung**

- `ifap-grund-betrag-zinsen` — Prueft Anspruchsgrundlage, Betrag und Zinsberechnung der angemeldeten Forderung.
- `ifap-rang-nachrang-absonderung` — Klassifiziert Forderung nach Rang: einfach, Nachrang, Absonderungsrecht oder Aussonderungsrecht.
- `ifap-masseverbindlichkeit-abgrenzen` — Grenzt Masseverbindlichkeiten von Insolvenzforderungen nach Entstehungszeitpunkt ab.
- `ifap-vbuh-pruefung` — Prueft Kennzeichnung als vbuH, Restschuldbefreiungsrelevanz und Begruendungsanforderungen.

**Pruefungsentscheidung und Termin**

- `ifap-pruefentscheidung` — Entscheidung ueber Feststellung, Teilfeststellung, Bestreiten oder Rueckstellung.
- `ifap-pruefungstermin-176` — Vorbereitung des Pruefungstermins nach § 176 InsO: Terminmappe, Widersprueche, schriftliches Verfahren.
- `ifap-quality-gate` — Qualitaetsgate vor Tabelleneintrag, Pruefungstermin und Verteilung: Vollstaendigkeit und Plausibilitaet.

**Bestreiten und Streit**

- `ifap-streitige-forderung-179-180` — Nachverfolgung bestrittener Forderungen: Feststellungsklage (§ 179 InsO), Tabellenklage (§ 180 InsO).
- `ifap-schuldnerwiderspruch-184` — Schuldnerwiderspruch nach § 184 InsO pruefen und Monatsfrist fuer Aufnahme des Rechtsstreits einhalten.

**Tabelle und Verteilung**

- `ifap-tabellenimport-175` — Tabelleneintrag und CSV-Import nach § 175 InsO mit tabellenfaehiger Ausgabe.
- `ifap-tabellenauszug-178` — Tabellenauszug als vollstreckbaren Titel nach § 178 InsO erstellen.
- `ifap-verteilung-bestrittene-189` — Verteilung bei bestrittenen Forderungen nach § 189 InsO: Rueckbehalt-Berechnung.

## Worauf besonders achten

- **Formalmaengel fruehzeitig behandeln.** Eine formal unvollstaendige Anmeldung nach § 174 InsO kann nicht festgestellt werden; Maengelschreiben sofort nach Eingang erstellen.
- **vbuH-Kennzeichnung erfordert Tatsachengrundlage.** Nicht jede Deliktsforderung ist automatisch vbuH; der Glaeubiger muss Tatsachen darlegen (§ 174 Abs. 2 InsO).
- **Masseverbindlichkeiten nicht als Insolvenzforderungen behandeln.** Entstehungszeitpunkt (vor oder nach Eroeffnung) und Verwalterhandeln sind entscheidend.
- **Monatsfrist nach Pruefungstermin beachten.** Bei Schuldnerwiderspruch zu titulierten Forderungen laeuft die Aufnahme-Frist nach § 184 InsO ab Pruefungstermin.
- **Verteilung korrekt berechnen.** Bestrittene Forderungen nach § 189 InsO koennen nur beruecksichtigt werden, wenn der Glaeubiger rechtzeitig Nachweis erbringt.

## Typische Fehler

- Rang wird nicht geprueft; Nachrang-Forderungen (§ 39 InsO) werden als einfache Insolvenzforderungen eingetragen.
- Belegkette ist unvollstaendig; Forderung wird festgestellt ohne dass Anspruchsgrundlage belegt ist.
- Dubletten werden nicht erkannt; Doppelzahlung im Verteilungsverfahren ist moegliche Folge.
- Pruefungstermin wird ohne Terminmappe angegangen; streitige Forderungen koennen nicht geordnet behandelt werden.
- Schuldnerwiderspruch bei titulierten Forderungen wird nicht nachverfolgt; Glaeubiger verliert Feststellungswirkung durch Fristversaeumnis.

## Querverweise

- `fortbestehensprognose` — Wenn der Insolvenzschuldner noch in der Fruehphase ist und Insolvenzreife gerade erst festgestellt wird.
- `mittelstand-corporate-ma` — Fuer Distressed-M&A-Transaktionen, bei denen Insolvenzforderungen eine Rolle spielen.
- `gesellschaftsrecht` — Fuer gesellschaftsrechtliche Aspekte bei der Insolvenz einer GmbH oder AG.
- `subsumtions-pruefer` — Fuer Einzelfragen der Anspruchsgrundlage und Beweislast bei streitigen Forderungen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum (InsO, ZPO, BGB)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
