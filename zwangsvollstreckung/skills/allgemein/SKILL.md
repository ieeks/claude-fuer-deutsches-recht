---
name: allgemein
description: "Einstieg und Ueberblick fuer das Zwangsvollstreckung-Plugin: Mahnbescheid, PfUeB Bank und Arbeit, Kontensuche, Vermoegeensauskunft, Raeumung, Notar-Urkunde, ZVG-Antrag, EU-Kontenpfaendung, Haertefall-Schutz nach §§ 704 ff. ZPO fuer Glaeubiger und Schuldner."
---

# Zwangsvollstreckung — Allgemein

## Worum geht es?

Das Plugin begleitet die Zwangsvollstreckung aus der Perspektive beider Seiten: Glaeubiger, die einen vorhandenen Titel vollstrecken wollen, und Schuldner, die sich gegen Vollstreckungsmassnahmen wehren. Es deckt das gesamte Spektrum der §§ 704 ff. ZPO ab: vom Mahnbescheid und Vollstreckungsbescheid ueber Pfaendungs- und Uebertragungsbeschluesse (PfUeB) bei Bankkonten und Arbeitseinkommen bis zur Raeumungsvollstreckung und zum ZVG-Antrag bei Immobilien.

Einbezogen sind auch EU-grenzueberschreitende Massnahmen (EuKtPVO) und der Schuldnerschutz nach § 765a ZPO sowie § 802l-Kontensuche. Zielgruppe sind Anwaelte, Inkassobetriebe und Rechtspfleger.

## Wann brauchen Sie diese Skill?

- Glaeubiger hat rechtskraeftiges Urteil oder anderen vollstreckbaren Titel und muss entscheiden, welche Vollstreckungsart am sinnvollsten ist.
- Glaeubiger kennt weder Konto noch Arbeitgeber des Schuldners und muss Vermoegensauskunft oder Drittauskunft beantragen.
- Schuldner hat unrechtmaessigen PfUeB erhalten oder ist besonders schutzbeduerftig (Krankheit, Suizidrisiko) und will Vollstreckungsschutz.
- Vermieter hat rechtskraeftiges Raeumungsurteil und muss Gerichtsvollzieher beauftragen.
- Glaeubiger will Immobilie des Schuldners versteigern lassen (ZVG-Antrag).

## Fachbegriffe (kurz erklaert)

- **Vollstreckbarer Titel (§ 704 ZPO)** — Grundlage jeder Zwangsvollstreckung; typisch: Urteil, Vollstreckungsbescheid, notarielle Urkunde.
- **Vollstreckungsklausel (§ 724 ZPO)** — Formale Bescheinigung auf dem Titel, die Vollstreckbarkeit bestaetigt.
- **PfUeB** — Pfaendungs- und Uebertragungsbeschluss; richterlicher Beschluss, der Forderung des Schuldners gegenueber Drittschuldner pfaendet.
- **P-Konto** — Pfaendungsschutzkonto; schuetzt Existenzminimum des Schuldners bei Kontopfaendung (§ 850k ZPO).
- **Pfaendungsfreigrenze (§ 850c ZPO)** — Betrag des Arbeitseinkommens, der pfaendungsfrei bleibt; Pfaendungstabelle wird regelmaessig angepasst.
- **Vermoegensauskunft (§ 802c ZPO)** — Pflicht des Schuldners, vollstaendiges Vermoegen zu offenbaren; frueherer Name: Eidesstattliche Versicherung.
- **ZVG** — Zwangsversteigerungsgesetz; Grundlage fuer Immobilienvollstreckung durch Versteigerung.
- **EuKtPVO** — EU-Kontenpfaendungsverordnung (VO 655/2014); ermoeglicht vorlaeufige Kontenpfaendung in EU-Mitgliedstaaten.

## Rechtsgrundlagen

- §§ 704 ff. ZPO — Allgemeine Voraussetzungen der Zwangsvollstreckung
- §§ 724 726 ZPO — Vollstreckungsklausel und Zustellung
- §§ 688 ff. ZPO — Mahnverfahren, Vollstreckungsbescheid
- §§ 808 ff. ZPO — Sachpfaendung (Mobiliarpfaendung)
- §§ 829 835 850 ff. ZPO — Forderungspfaendung, Lohn- und Kontopfaendung
- § 850k ZPO — Pfaendungsschutzkonto
- § 802c ff. ZPO — Vermoegensauskunft, § 802l Drittauskunft
- § 765a ZPO — Vollstreckungsschutz in Haertefall
- § 885 ZPO — Raeumungsvollstreckung
- ZVG — Zwangsversteigerung und Zwangsverwaltung
- VO (EU) 655/2014 (EuKtPVO) — EU-Kontenpfaendung
- § 201 InsO — Vollstreckung aus Tabellenauszug nach Insolvenz

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Glaeubiger-Seite (Vollstreckung einleiten) oder Schuldner-Seite (Vollstreckung abwehren)?
2. Titelstatus pruefen: Liegt ein vollstreckbarer Titel mit Klausel und Zustellung vor (§§ 704, 724, 750 ZPO)?
3. Zielobjekt bestimmen: Bankkonto, Arbeitseinkommen, Mobiliarsachen, Immobilie oder sonstige Forderung?
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Eilfristen pruefen: Haertefall-Antrag nach § 765a ZPO sofort bei Vollstreckungstermin; EU-Kontenpfaendung hat eigene Fristen.

## Skill-Tour (was gibt es hier?)

- `zv-kommandocenter` — Routing: Welche Vollstreckungsart ist im konkreten Fall am sinnvollsten? Ueberblick und Weiterleitung.
- `zv-mahnbescheid-online` — Mahnbescheid online beantragen und Vollstreckungsbescheid erwaerken nach §§ 688 ff. ZPO.
- `zv-vollstreckungsbescheid-folge` — Nach Mahnbescheid: Vollstreckungsbescheid beantragen oder auf Widerspruch reagieren.
- `zv-titel-klausel-zustellung` — Formale Trias pruefen: vollstreckbarer Titel, Vollstreckungsklausel, Zustellung an Schuldner.
- `zv-pfueb-bank` — PfUeB fuer Bankkonto beantragen; Drittschuldner-Erklarung, P-Konto-Schutz.
- `zv-pfueb-arbeitsentgelt` — PfUeB fuer Arbeitseinkommen; Pfaendungsfreigrenze nach § 850c ZPO berechnen.
- `zv-pfueb-mieter-finanzamt` — PfUeB fuer Mietforderung, Steuererstattung oder sonstige Drittschuldner-Forderung.
- `zv-pfaendungstabelle-2025` — Pfaendungsfreien Betrag nach aktueller Pfaendungstabelle (Stand 2025) konkret berechnen.
- `zv-kontensuche-drittschuldner` — § 802l-Kontensuche und Drittauskunft wenn Konto oder Arbeitgeber des Schuldners unbekannt sind.
- `zv-vermoegensauskunft-gv` — Vermoegensauskunft nach § 802c ZPO durch Gerichtsvollzieher beantragen.
- `zv-mobiliar-gv-auftrag` — Gerichtsvollzieher mit Sachpfaendung beweglicher Gegenstaende beauftragen (§§ 808 ff. ZPO).
- `zv-raeumung-885` — Raeumungsvollstreckung nach § 885 ZPO; Gerichtsvollzieher-Auftrag, Berliner Raeumung.
- `zv-notarielle-urkunde-grundschuld` — Vollstreckung aus notarieller Grundschuld-Urkunde nach § 794 Abs. 1 Nr. 5 ZPO.
- `zv-zvg-antrag-glaeubiger` — ZVG-Antrag auf Zwangsversteigerung oder Zwangsverwaltung bei Immobilien.
- `zv-tabellenauszug-201-inso` — Vollstreckung aus Insolvenz-Tabellenauszug nach § 201 InsO nach Verfahrensende.
- `zv-eu-kontenpfaendung-655-2014` — Vorlaeufige EU-Kontenpfaendung nach EuKtPVO bei EU-Auslandskonto des Schuldners.
- `zv-vollstreckungsschutz-haertefall-765a` — Haertefall-Schutzantrag fuer besonders schutzbeduerftige Schuldner nach § 765a ZPO.
- `zv-abwehr-schuldner` — Schuldner-Abwehrmassnahmen: sofortige Beschwerde, Vollstreckungserinnerung, Haertefall, P-Konto.
- `zv-elektronische-zustellung-2027` — Digitalisierung der Zwangsvollstreckung ab 2026/2027: neue Pflichten und Verfahren.

## Worauf besonders achten

- Formale Trias ist zwingend: Titel, Klausel und Zustellung muessen vollstaendig vorliegen, bevor Vollstreckung beginnt (§ 750 ZPO).
- P-Konto-Schutz gilt automatisch, wenn Schuldner P-Konto eingerichtet hat; Glaeubiger muss Freibetrag-Erhoehung separat anfechten.
- Pfaendungsfreigrenzen werden jaehrlich angepasst (§ 850c ZPO); immer aktuelle Tabelle verwenden.
- EU-Kontenpfaendung nach EuKtPVO setzt Zustaendigkeit eines deutschen Gerichts voraus; Antrag hat eigene Formalien.
- Haertefall-Antrag nach § 765a ZPO hemmt Vollstreckung nur bei sofortiger Antragstellung vor dem Vollstreckungstermin.

## Typische Fehler

- Vollstreckung ohne Zustellung an Schuldner begonnen: § 750 ZPO erfordert vorherige oder gleichzeitige Zustellung; fehlende Zustellung macht Vollstreckungsmassnahme anfechtbar.
- Pfaendungsfreigrenze falsch berechnet: Falsche Steuerklasse oder Unterhaltspflichten nicht beruecksichtigt; Schuldner kann Erinnerung einlegen.
- Gerichtsvollzieher-Auftrag zu spaet gestellt: Mobiliarsachen koennen veraessert oder abhandengekommen sein.
- Verjaehrung des Titels uebersehen: Vollstreckungsverjaeaehrung nach § 197 BGB betraegt 30 Jahre ab Urteil; Mahnbescheide koennen kuerzere Fristen haben.
- EU-Kontenpfaendung ohne Zustaendigkeitspruefung: Deutsche Gerichte sind nur zustaendig wenn Deutschland Vollstreckungsmitgliedstaat ist.

## Querverweise

- Plugin `forderungsmanagement-klagewerkstatt` — Titulierung der Forderung vor Vollstreckung.
- Plugin `liquiditaetsplanung` — Bei Schuldner-Insolvenznaehe: Zahlungsunfaehigkeits-Pruefung parallel.
- Plugin `grosskanzlei-corporate-ma` — Bei Distressed M&A oder Unternehmensinsolvenz: § 201 InsO-Vollstreckung.

## Quellen und Aktualitaet

- Stand: 05/2026
- ZPO, ZVG, InsO in aktuell geltender Fassung
- Pfaendungsfreibetraege nach § 850c ZPO in der Fassung ab 01.07.2023 (Anpassung 2025 beachten)
- EuKtPVO (VO 655/2014) unmittelbar anwendbar

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
