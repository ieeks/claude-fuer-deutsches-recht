---
name: allgemein
description: "Einstieg und Orientierung im Insolvenzrecht-Plugin. Klaert Eroeffnungsgründe, Antragspflicht, Gläubigerantrag, Anfechtungsrechte, D-and-O-Haftung, Konzerninsolvenz und Routing zu allen 15 Spezial-Skills."
---

# Insolvenzrecht — Allgemein

## Worum geht es?

Dieses Plugin deckt die insolvenzrechtlichen Grundfragen ab, die in der taeaglichen Beratungspraxis vor und waehrend eines Insolvenzverfahrens entstehen. Im Mittelpunkt stehen die Eroeffnungsgruende (Zahlungsunfaehigkeit, drohende Zahlungsunfaehigkeit, Ueberschuldung), die Insolvenzantragspflicht des Geschaeftsleiters nach § 15a InsO, das Zahlungsverbot nach § 15b InsO, Anfechtungsrechte des Insolvenzverwalters, Forderungsanmeldung durch Glaeubiger, D-and-O-Haftungsfragen und die Koordination von Konzerninsolvenzen.

Das Plugin richtet sich an Anwaelte, Insolvenzverwalter, Sachwalter, Sanierungsberater und Unternehmensberater. Es ist ein strukturiertes Pruefwerkzeug fuer insolvenzrechtliche Triage-Situationen. Fuer vertiefte Planwerkstatt-Arbeit (Insolvenzplan, StaRUG) steht das Plugin `insolvenzplan-starug-planwerkstatt` zur Verfuegung.

## Wann brauchen Sie diese Skill?

- Geschaeftsfuehrer fragt, ob er einen Insolvenzantrag stellen muss und bis wann die Dreiwochenfrist laeuft.
- Glaeubiger moechte wissen, ob er einen Insolvenzantrag stellen kann und was dabei zu beachten ist.
- Arbeitnehmer eines insolventen Unternehmens fragt nach Insolvenzgeld.
- Insolvenzverwalter prueft Anfechtungsansprueche gegen Zahlungen vor Verfahrenseroffnung.
- Mandant ist Mitglied des Glaeubigerausschusses und fragt nach Rechten, Pflichten und Haftung.

## Fachbegriffe (kurz erklaert)

- **Zahlungsunfaehigkeit** — Schuldner kann faellige Zahlungspflichten nicht mehr erfuellen; § 17 InsO; BGH-Schema: zehn Prozent Liquiditaetslucke fuer mindestens drei Wochen.
- **Drohende Zahlungsunfaehigkeit** — Schuldner wird voraussichtlich faellige Zahlungspflichten nicht erfuellen koennen; § 18 InsO; Grundlage fuer freiwilligen Antrag und StaRUG.
- **Ueberschuldung** — Vermoegen des Schuldners deckt bestehende Verbindlichkeiten nicht, sofern keine positive Fortbestehensprognose (§ 19 InsO).
- **Antragspflicht** — Geschaeftsfuehrer und Vorstand muessen bei Zahlungsunfaehigkeit oder Ueberschuldung ohne schuldhaftes Zoegern, spaetestens drei Wochen nach Eintreten, Antrag stellen (§ 15a InsO).
- **Zahlungsverbot** — Nach Insolvenzreife sind Zahlungen nur noch zulasaig, die mit der Sorgfalt eines ordentlichen Kaufmanns vereinbar sind (§ 15b InsO).
- **Insolvenzverschleppung** — Verspaetete Antragstellung; Haftung gegenueber Neuglaeubigeern und Altglaeubigern aus § 823 Abs. 2 BGB iVm § 15a InsO.
- **Bargeschaeft** — Leistungsaustausch mit sofortiger Gegenleistung; schuetzt vor Insolvenzanfechtung nach § 142 InsO.
- **Glaeubigerausschuss** — Kontrollorgan des Insolvenzverfahrens nach §§ 67 ff. InsO; prueft und beaufsichtigt den Insolvenzverwalter.

## Rechtsgrundlagen

- § 17 InsO — Zahlungsunfaehigkeit als Eroeffnungsgrund.
- § 18 InsO — Drohende Zahlungsunfaehigkeit.
- § 19 InsO — Ueberschuldung; zweistufige Pruefung.
- § 14 InsO — Glaeubigerantrag.
- § 15a InsO — Antragspflicht des Geschaeftsleiters; Dreiwochenfrist.
- § 15b InsO — Zahlungsverbot nach Insolvenzreife.
- §§ 67 ff. InsO — Glaeubigerausschuss.
- §§ 129 ff. InsO — Insolvenzanfechtung (Grundtatbestand, Deckungsanfechtung, Vorsatzanfechtung).
- § 142 InsO — Bargeschaeftsprivileg.
- §§ 165 ff. SGB III — Insolvenzgeld fuer Arbeitnehmer.
- §§ 174 bis 179 InsO — Forderungsanmeldung, Pruefungstermin, Tabelle.
- §§ 269a bis 269i InsO — Konzerninsolvenz.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenrolle klaeren: Geschaeftsfuehrer, Glaeubiger, Arbeitnehmer, Ausschussmitglied?
2. Triage-Interview durchfuehren: Skill `mandat-triage-insolvenzrecht`.
3. Sofort-Fristen sichern: Dreiwochenfrist § 15a InsO oder Anmeldefrist § 165 SGB III?
4. Eroeffnungsgruende pruefen: `zahlungsunfaehigkeit-pruefung-17-inso` und/oder `ueberschuldung-pruefung-19-inso`.
5. Anschluss-Skill auswaehlen nach Ergebnis der Triage.

## Skill-Tour (was gibt es hier?)

**Einstieg und Triage**

- `mandat-triage-insolvenzrecht` — Eingangsabfrage; Mandantenrolle und Sofort-Fristen klaeren.
- `insolvenzrecht-kaltstart-interview` — Kaltstart-Interview fuer Plugin-Profil und Praxiskonfiguration.

**Eroeffnungsgruende und Liquiditaet**

- `zahlungsunfaehigkeit-pruefung-17-inso` — Liquiditaetsstatus nach § 17 InsO; BGH-Schema zehn Prozent und drei Wochen.
- `ueberschuldung-pruefung-19-inso` — Zweistufige Ueberschuldungspruefung nach § 19 InsO; Fortbestehensprognose und Liquidationswerte.
- `liquiditaetsvorschau-insolvenzrechtlich` — Rollierende Liquiditaetsvorschau nach IDW S 11; 13-Wochen- und 24-Monats-Vorschau.

**Antragspflicht und Haftung**

- `antragspflicht-15a-inso` — Antragspflicht nach § 15a InsO; Dreiwochenfrist; Zahlungsverbot § 15b InsO; Insolvenzverschleppungshaftung.
- `do-versicherung-manager-haftung` — D-and-O-Versicherungsdeckung bei Insolvenzhaftung; Claims-made-Prinzip; Ausschluesse.

**Glaeubigerantrag und Glaeubigerrechte**

- `glaeubigerantrag-pruefung` — Zulaessigkeit und Begruendetheit des Glaeubigerantrags nach § 14 InsO.
- `glaeubigerausschuss-mitwirkung` — Rechte, Pflichten und Haftung des Glaeubigerausschussmitglieds.
- `forderungsanmeldung-glaeubiger-174-177-inso` — Forderungsanmeldung, Fristen, Form, Rang, Pruefungstermin.

**Anfechtung**

- `anfechtungsrechte-pruefen` — Uebersicht aller InsO-Anfechtungstatbestaende §§ 129 ff. InsO; Betrag, Verteidigungslinien.
- `vorsatzanfechtung-133-inso` — Vorsatzanfechtung nach § 133 InsO; Fassung seit 5. April 2017; Bargeschaeftsprivileg.

**Sanierung und Sondersituationen**

- `uebertragende-sanierung-und-asset-deals` — Unternehmensverkauf aus der Insolvenz; Asset-Deal, Glaeubigerausschuss-Zustimmung.
- `konzerninsolvenz-koordination` — Koordination mehrerer Konzerngesellschaften nach §§ 269a bis 269i InsO.

**Arbeitnehmer**

- `insolvenzgeld-165-sgb-iii` — Insolvenzgeld fuer Arbeitnehmer; Voraussetzungen, Antragsfrist zwei Monate, Vorfinanzierung.

## Worauf besonders achten

- **Dreiwochenfrist laeuft ab Eintritt des Eroeffnungsgrundes** — Nicht ab Kenntnis des Geschaeftsfuehrers; bei unklarem Eintrittszeitpunkt ist das Risiko gross.
- **Zahlungsverbot schon vor Antragstellung** — § 15b InsO greift mit Eintritt der Insolvenzreife, nicht erst mit Eroffnung; Einzelzahlungen muessen ab diesem Zeitpunkt geprueft werden.
- **Glaeubigerantrag: Glaubhaftmachung reicht nicht immer** — § 14 InsO verlangt Nachweis der Forderung und des Eroeffnungsgrundes; bloss drohende ZU genuegt dem Glaeubiger nicht.
- **Anfechtungsreform 2017 beachten** — § 133 InsO wurde durch das AnfRefG 2017 grundlegend geaendert; Fristen und Indizien unterscheiden sich fuer Sachverhalte vor und nach dem 5. April 2017.
- **Insolvenzgeld: Zweimonatsfrist ab Insolvenz-Ereignis** — Arbeitnehmer verlieren den Anspruch, wenn Antrag zu spaet gestellt wird.

## Typische Fehler

- Geschaeftsfuehrer errechnet Dreiwochenfrist ab dem Tag, an dem er Kenntnis erlangt, statt ab Eintritt der Insolvenzreife.
- Glaeubiger stellt Antrag nach § 14 InsO ohne vollstreckbaren Titel und laeuft in Zulaessigkeitsproblem.
- Forderungsanmeldung versaeumt, weil Anmeldefrist nicht im Blick war; nachtraegliche Anmeldung nach § 177 InsO noch moeglich, aber mit Kostenrisiko.
- D-and-O-Versicherung wird nicht informiert, bevor Insolvenzantrag gestellt wird; Claims-made-Risiko.
- Koordinationsplan fuer Konzerninsolvenz wird nicht erwaogen, obwohl mehrere Schwestergesellschaften betroffen sind.

## Querverweise

- `insolvenzplan-starug-planwerkstatt` — Fuer Insolvenzplan- und StaRUG-Plangestaltung.
- `bereicherungs-und-anfechtungsrecht-pruefer` — Fuer vertiefte Anfechtungspruefung nach §§ 129 ff. InsO und AnfG.
- `europarecht-kompass` — Bei grenzueberschreitender Insolvenz nach EuInsVO Art. 56 ff.

## Quellen und Aktualitaet

- Stand: 05/2026
- InsO in der geltenden Fassung (insb. §§ 15a und 15b InsO; §§ 129 und 133 InsO Fassung seit 5. April 2017)
- SGB III §§ 165 ff. in der geltenden Fassung
- IDW S 11 (Beurteilung des Vorliegens von Insolvenzeroefffnungsgruenden)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
