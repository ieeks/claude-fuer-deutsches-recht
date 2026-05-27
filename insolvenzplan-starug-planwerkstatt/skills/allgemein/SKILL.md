---
name: allgemein
description: "Einstieg und Orientierung im Insolvenzplan-StaRUG-Planwerkstatt-Plugin. Klaert Verfahrenswahl, Planarchitektur, Gruppenbildung, Vergleichsrechnung, Abstimmung, Cramdown und Planvollzug nach InsO und StaRUG."
---

# Insolvenzplan und StaRUG-Planwerkstatt — Allgemein

## Worum geht es?

Dieses Plugin ist das spezialisierte Werkzeug fuer die Erstellung, Pruefung und Begleitung von Insolvenzplaenen nach §§ 217 ff. InsO und Restrukturierungsplaenen nach dem StaRUG (Unternehmensstabilisierungs- und -restrukturierungsgesetz). Es deckt den gesamten Planlebenszyklus ab: vom Kaltstart-Interview und der Verfahrenswahl ueber die Planarchitektur, Vergleichsrechnung und Gruppenbildung bis zur Abstimmung, dem Cramdown-Verfahren und dem Planvollzug.

Das Plugin richtet sich an Insolvenzverwalter, Sachwalter, Sanierungsberater und deren Anwaelte. Es ist kein Rechtsberatungsersatz, sondern ein strukturiertes Pruefwerkzeug fuer komplexe Sanierungsmandate. Fuer die parallele Bearbeitung einfacherer insolvenzrechtlicher Grundfragen steht das Plugin `insolvenzrecht` zur Verfuegung.

## Wann brauchen Sie diese Skill?

- Sie stehen am Beginn eines Restrukturierungsmandats und muessen zwischen Insolvenzplan, Eigenverwaltung, Schutzschirm, StaRUG und aussergerichtlicher Einigung auswaehlen.
- Sie erstellen oder pruefe den darstellenden und gestaltenden Teil eines Insolvenzplans oder StaRUG-Plans.
- Sie muessen Gruppen und Klassen nach §§ 222 f. InsO oder §§ 9 f. StaRUG sachgerecht bilden.
- Sie simulieren Abstimmungsmehrheiten oder pruefen Cramdown-Szenarien nach § 245 InsO oder § 27 StaRUG.
- Sie begleiten den Planvollzug und muessen Abweichungen von Quoten und Covenants dokumentieren.

## Fachbegriffe (kurz erklaert)

- **Insolvenzplan** — Gestaltendes Instrument nach §§ 217 ff. InsO, mit dem Glaeubiger abweichend vom Regelverfahren befriedigt werden; besteht aus darstellendem und gestaltendem Teil plus Anlagen.
- **StaRUG-Plan** — Restrukturierungsplan nach dem StaRUG; ermoeglicht Eingriffe in Glaeubigerpositionen ausserhalb des Insolvenzverfahrens bei bloss drohender Zahlungsunfaehigkeit.
- **Vergleichsrechnung** — Kernbestandteil des Plans; zeigt je Gruppe, dass kein Beteiligter im Plan schlechter steht als ohne Plan (Schlechterstellungsverbot).
- **Cramdown** — Gruppenuebergreifende Mehrheitsentscheidung, die eine ablehnende Gruppe ueberstimmt (§ 245 InsO, § 27 StaRUG); setzt absolute Prioritaet oder angemessene Beteiligung voraus.
- **Planbetroffene** — Im StaRUG-Verfahren ausdrucklich ausgewaehlte Inhaber gestaltbarer Rechtsverhaeltnisse (§§ 2 ff. StaRUG).
- **Sanierungsmoderation** — Aussergerichtliches Verfahren nach §§ 94 ff. StaRUG mit gerichtlich bestelltem Moderator.
- **Integrierte Planung** — Verknuepfte Finanzplanung aus GuV, Liquiditaet und Bilanz als wirtschaftliche Grundlage fuer den Plan.
- **Planvollzug** — Phase nach Planbestaetigung; umfasst Zahlungen, Covenants und Monitoring nach §§ 248 und 261 InsO.

## Rechtsgrundlagen

- §§ 217 bis 269 InsO — Insolvenzplan (Architektur, Gruppen, Anlagen, Abstimmung, Bestaetigung, Vollzug).
- §§ 244 und 245 InsO — Abstimmungsmehrheiten und Obstruktionsverbot (Cramdown).
- § 251 InsO — Minderheitenschutz.
- §§ 261 und 268 InsO — Planueberwachung.
- §§ 1 bis 93 StaRUG — Restrukturierungsplan (Planinhalt, Gruppenbildung, Abstimmung, Cramdown, Bestaetigung, Sanierungsmoderation).
- §§ 3a und 3c EStG — Sanierungsgewinn und steuerliche Folgen.
- § 8c KStG — Verlustvortraege bei Anteilsuebertragung.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Kaltstart-Interview durchfuehren: Skill `ips-kaltstart-interview` fuer fehlende Unterlagen.
2. Verfahrenswahl treffen: Skill `ips-verfahrenswahl` (InsO-Plan, StaRUG, aussergerichtlich).
3. Planarchitektur aufbauen: `ips-insolvenzplan-architektur` oder `ips-starug-plan-architektur`.
4. Vergleichsrechnung und Gruppen: `ips-vergleichsrechnung` und `ips-gruppen-klassenbildung`.
5. Red-Team-Pruefung vor Einreichung: `ips-redteam-qualitygate`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Steuerung**

- `ips-kommandocenter` — Mandat starten, Verfahrensroute und Ampelstatus bestimmen.
- `ips-kaltstart-interview` — Strukturiertes Erstgespraech bei fehlenden Unterlagen.
- `ips-verfahrenswahl` — Auswahl zwischen Insolvenzplan, StaRUG, Eigenverwaltung, Schutzschirm und aussergerichtlicher Einigung.

**Planarchitektur**

- `ips-insolvenzplan-architektur` — Vollstaendigen Insolvenzplan nach §§ 217 ff. InsO strukturieren.
- `ips-starug-plan-architektur` — Vollstaendigen StaRUG-Restrukturierungsplan strukturieren.
- `ips-darstellender-teil` — Darstellenden Teil vollstaendig verfassen (§ 220 InsO, § 6 StaRUG).
- `ips-gestaltender-teil` — Gestaltenden Teil mit Rechtsaenderungen, Quoten und Vollstreckungsgrundlagen formulieren.
- `ips-anlagenpaket` — Pflichtanlagen vollstaendig zusammenstellen.

**Gruppen und Klassen**

- `ips-gruppen-klassenbildung` — Abstimmungsgruppen nach InsO und Klassen nach StaRUG sachgerecht bilden.
- `ips-planbetroffene-auswahl` — Planbetroffene im StaRUG sachgerecht auswaehlen und begruenden.

**Wirtschaftliche Grundlagen**

- `ips-sanierungskonzept` — Sanierungskonzept als wirtschaftliche Grundlage erstellen oder pruefen.
- `ips-integrierte-planung` — Integrierte Planrechnung aus GuV, Liquiditaet und Bilanz erstellen.
- `ips-vergleichsrechnung` — Vergleichsrechnung (Planfall vs. Ohne-Plan-Szenario) je Gruppe erstellen.
- `ips-steuern-bilanz-folgen` — Steuerliche und bilanzielle Folgen des Plans pruefen.

**Sicherheiten und Dritte**

- `ips-sicherheiten-drittsicherheiten` — Absonderungsrechte und Drittsicherheiten planfest behandeln.
- `ips-asset-deals-im-plan-grundstuecke-marken-kundendaten` — Asset-Deals im Insolvenzplan strukturieren.

**Abstimmung und Durchsetzung**

- `ips-abstimmung-mehrheiten` — Abstimmungsmehrheiten simulieren und Abstimmungstermin vorbereiten.
- `ips-cramdown-obstruktion` — Obstruktionsverbot und gruppenuebergreifende Mehrheitsentscheidung pruefen.
- `ips-minderheitenschutz` — Schlechterstellungsrisiken opponierender Beteiligter analysieren.

**Gerichtliche Schritte und Stabilisierung**

- `ips-gerichtliche-schritte` — Gerichtliche Verfahrensschritte von Einreichung bis Planbestaetigung steuern.
- `ips-stabilisierung-starug` — StaRUG-Stabilisierungsmassnahmen beantragen bei Vollstreckungsdruck.

**Kommunikation und Dokumentation**

- `ips-stakeholder-kommunikation` — Glaeubiger, Banken, Arbeitnehmer und Gericht zielgruppengerecht informieren.
- `ips-datenraum-register` — Planbegleitenden Datenraum aufbauen und Dokumentenregister fuehren.

**Qualitaetssicherung und Planvollzug**

- `ips-redteam-qualitygate` — Plan vor Einreichung aus Gegnersicht und Gerichtssicht pruefen.
- `ips-planvollzug-monitoring` — Planvollzug ueberwachen, Zahlungen kontrollieren und Abweichungen dokumentieren.

**Sanierungsmoderation**

- `sanierungsmoderation-94-starug` — Sanierungsmoderation nach § 94 StaRUG vorbereiten und durchfuehren.

## Worauf besonders achten

- **Vergleichsrechnung ist Herzstuck** — Ohne belastbare Vergleichsrechnung wird der Plan nicht bestaetigt; Annahmenregister und Stressszenarien muessen dokumentiert sein.
- **StaRUG nur bei drohender Zahlungsunfaehigkeit** — § 18 InsO ist Voraussetzung; bei eingetretener Zahlungsunfaehigkeit oder Ueberschuldung ist InsO-Antragspflicht zu pruefen.
- **Cramdown-Risiko fruehzeitig managen** — Ablehnende Klassen fruhzeitig identifizieren und Planmehrwert-Argument oder absolute Prioritaet vorbereiten.
- **Steuerfolgen nicht unterschaetzen** — Sanierungsgewinn (§ 3a EStG) und Verlustvortragsbeschraenkung (§ 8c KStG) koennen den Planmehrwert aufzehren; Steuerberater fruehzeitig einbinden.
- **Artverschiedenheit InsO und StaRUG** — Planbetroffene und Gruppenbildung folgen verschiedenen Logiken; Verwechslungen fuehren zu Versagungsgruenden.

## Typische Fehler

- Vergleichsrechnung stuetzt sich auf nicht dokumentierte Annahmen; Gericht verlangt Plausibilitaetsnachweis.
- Gruppenbildung folgt nicht wirtschaftlichen Interessen, sondern praktischen Erwaegungen; Missbrauchsvorwurf.
- Anlagenpaket ist unvollstaendig bei Einreichung; Vorpruefungsversagung nach § 231 InsO.
- Planbetroffene im StaRUG umfassen Arbeitnehmer oder Deliktsglaeubiger, die ausgenommen sein muessen (§ 4 StaRUG).
- Red-Team-Pruefung wird uebersprungen; Fehler werden erst vom gegnerischen Anwalt oder Gericht erkannt.

## Querverweise

- `insolvenzrecht` — Fuer Grundfragen zu Eroeffnungsgruenden, Antragspflicht, Anfechtungsrechten.
- `bereicherungs-und-anfechtungsrecht-pruefer` — Fuer Anfechtungsansprueche gegen Zahlungen vor Antrag.
- `kartellrecht-marktabgrenzung-pruefung` — Bei Restrukturierungen mit kartellrechtlich relevantem Marktaustritt.

## Quellen und Aktualitaet

- Stand: 05/2026
- InsO §§ 217 ff. in der geltenden Fassung
- StaRUG in der geltenden Fassung
- EStG §§ 3a und 3c; KStG § 8c

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
