---
name: allgemein
description: "Einstieg fuer das Forderungsmanagement-Klagewerkstatt-Plugin: Zustaendigkeitspruefung, Mahnvorlauf, Inkasso-Zahlungsklage und Gatekeeper-Funktion fuer klare, faellige und belegte Forderungen bis zur gerichtlichen Titulierung."
---

# Forderungsmanagement-Klagewerkstatt — Allgemein

## Worum geht es?

Das Plugin begleitet Glaeubiger und Anwaelte vom Forderungsmanagement bis zur gerichtlichen Titulierung. Im Mittelpunkt steht der sogenannte Gatekeeper: Nur Forderungen, die klar beziffert, faellig und belegt sind, werden zur Zahlungsklage freigegeben. So werden aussichtslose Klagen vermieden, die Kosten verursachen ohne Erfolgsaussicht.

Das Plugin unterstuetzt zudem den Aufbau kanzleieigener Klagemuster und ermoeglicht die Integration mit vorhandenen Kanzlei-Klagewerkstatt-Plugins. Zielgruppe sind Anwaelte, Inkassounternehmen und Unternehmensjuristen im Forderungseinzug.

## Wann brauchen Sie diese Skill?

- Glaeubigerseite hat offene, unbezahlte Forderung und muss entscheiden, ob und wie sie klagen soll.
- Kanzlei will den Mahnvorlauf dokumentieren und pruefen, ob Verzug wirksam eingetreten ist.
- Mandant fragt, ob Amtsgericht oder Landgericht zustaendig ist und ob Mahnbescheid oder Klage sinnvoller ist.
- Kanzlei will hauseigene Klagemuster fuer wiederkehrende Forderungstypen strukturieren und wiederverwenden.
- Forderung liegt im Grenzbereich: Verpflichtungseinrede oder Gegenforderung des Schuldners muss vorab geprueft werden.

## Fachbegriffe (kurz erklaert)

- **Gatekeeper** — Vorabpruefung, ob Forderung klar, faellig und belegt ist, bevor Klageerstellung ausgeloest wird.
- **Verzug (§ 286 BGB)** — Schuldner leistet trotz Faelligkeit und Mahnung nicht; Voraussetzung fuer Verzugszinsen und Schadensersatz.
- **Mahnbescheid (§§ 688 ff. ZPO)** — Vereinfachtes gerichtliches Verfahren zur Titulierung unstreitiger Forderungen ohne muendliche Verhandlung.
- **Vollstreckungstitel** — Dokument, das Zwangsvollstreckung erlaubt (z.B. Urteil, Vollstreckungsbescheid, notarielle Urkunde).
- **Streitwert** — Geldwert der Forderung; entscheidet ueber Zustaendigkeit (AG bis 5.000 EUR nach altem Recht; ab 01.01.2026 AG bis 10.000 EUR, § 23 GVG) und Gerichtskosten.
- **Inkasso-Zahlungsklage** — Auf Geldzahlung gerichtete Klage mit standardisierten Pflichtbestandteilen (§§ 253 253 ZPO).

## Rechtsgrundlagen

- §§ 241 280 286 288 BGB — Leistungspflicht, Schadensersatz, Verzug, Verzugszinsen
- §§ 688 ff. ZPO — Mahnverfahren
- §§ 253 313 ZPO — Klageschrift, Urteilsbestandteile
- § 23 GVG — Sachliche Zustaendigkeit Amtsgericht
- § 71 GVG — Sachliche Zustaendigkeit Landgericht

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Forderung pruefen: Ist sie klar beziffert, faellig und belegt (Vertrag, Rechnung, Mahnung)?
2. Zustaendigkeit bestimmen: AG oder LG nach Streitwert; ggf. besonderer Gerichtsstand.
3. Mahnvorlauf dokumentieren: Liegt wirksame Mahnung vor? Ist Verzug eingetreten?
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Klagemuster pruefen oder anpassen: Eigene Kanzleimuster einbinden oder Standardmuster verwenden.

## Skill-Tour (was gibt es hier?)

- `inkasso-zahlungsklage-ersteller` — Erstellt eine vollstaendige Zahlungsklage fuer belegte und faellige Forderungen; Gatekeeper-Pruefung vor Klageerstellung.
- `klage-aus-eigenem-skill` — Verbindet Plugin mit kanzleiinternem Klagewerkstatt-Plugin (klagewerkstatt-kanzlei) fuer mandatsspezifische Klagen aus eigenem Sachverhalt.
- `klagevorlage-aus-eigenen-mustern` — Destilliert kanzleieigene Klagemuster einmalig in ein wiederverwendbares Plugin-Format.

## Worauf besonders achten

- Verzug muss wirksam begruendet sein: Mahnung nach § 286 BGB oder kalendarische Faelligkeit; fehlende Mahnung macht Verzugszinsen unbegruendet.
- Streitwertgrenzen beachten: Seit 01.01.2026 ist das AG bis 10.000 EUR sachlich zustaendig (§ 23 Nr. 1 GVG, Justizstandort-Staerkungsgesetz).
- Gegenansprueche und Einreden des Schuldners vor Klageerhebung ermitteln; unangemeldete Aufrechnung kann Klage entwerten.
- Im Mahnverfahren (§ 688 ZPO) sind von der Hauptforderung abhaengige Nebenforderungen separat zu beziffern.
- Klagemuster aus Kanzlei-Datenbanken muessen auf den konkreten Sachverhalt angepasst werden; blindes Uebernehmen fuehrt zu unzulaessigen oder unschluessigen Antraegen.

## Typische Fehler

- Klage ohne vorherige Mahnung: Ohne wirksame Mahnung kann keine Zahlungsklage auf Verzugszinsen gestellt werden.
- Streitwert falsch angegeben: Neben- und Zinsforderungen koennen Streitwert in eine andere Gerichtsstandskategorie heben.
- Forderung nicht hinreichend substantiiert: Rechnung oder Vertrag fehlt als Anlage; Klage wird unschluessig.
- Verpflichtungseinrede uebersehen: Schuldner hat eigene Gegenansprueche, die aufgerechnet werden koennen.
- Zu spaet zum Massnahmenpaket: Nach Abschluss Mahnverfahren laufen Widerspruchsfristen; versaeumte Folgeschritte fuehren zu Fristversaeumnissen.

## Querverweise

- Plugin `zwangsvollstreckung` — Sobald Titel vorhanden, Vollstreckungsschritte einleiten.
- Plugin `selbstvertreter-amtsgericht` — Klaeger ohne Anwalt; Prozessbegleitung vor dem AG.
- Plugin `grosskanzlei-corporate-ma` — Bei hohen B2B-Forderungen ggf. Konzernhaftung oder Distressed-Aspekte pruefen.

## Quellen und Aktualitaet

- Stand: 05/2026
- § 23 Nr. 1 GVG in der Fassung des Justizstandort-Staerkungsgesetzes (Wertgrenze 10.000 EUR seit 01.01.2026)
- BGB und ZPO in aktuell geltender Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
