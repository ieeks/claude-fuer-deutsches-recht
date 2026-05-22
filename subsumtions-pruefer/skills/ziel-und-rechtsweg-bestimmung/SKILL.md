---
name: ziel-und-rechtsweg-bestimmung
description: "Ermittelt interaktiv das Nutzerziel (Anspruchsdurchsetzung, Abwehr, Antrag, Beschwerde, Strafverfolgung, Verwaltungsakt-Anfechtung) und leitet daraus den einschlaegigen Rechtsweg ab: ZPO, VwGO, SGG, FGO, StPO, FamFG. Warnt bei Zweifelsfaellen."
---

# Ziel- und Rechtsweg-Bestimmung

## Zweck

Bevor Normen geprüft werden, muss klar sein, was der Nutzer mit der Prüfung erreichen will. Das Ziel bestimmt den Rechtsweg, die Verfahrensart, die Klageart und letztlich die einschlägigen Normen. Dieser Skill erfasst das Ziel strukturiert und gibt einen ersten Rechtsweg-Hinweis.

## Zielfragen

Das System fragt:

**Was möchten Sie erreichen?**

| Nr. | Ziel | Typischer Rechtsweg |
|-----|------|---------------------|
| 1 | Anspruch durchsetzen (Zahlung, Unterlassung, Herausgabe) | ZPO / ordentliche Gerichtsbarkeit |
| 2 | Anspruch abwehren (Klageabweisung, Widerklage) | ZPO |
| 3 | Verwaltungsentscheidung anfechten (Bescheid, Genehmigung) | VwGO (Anfechtungsklage § 42 Abs. 1 Alt. 1 VwGO) |
| 4 | Verwaltungsentscheidung erzwingen (Verpflichtungsklage) | VwGO § 42 Abs. 1 Alt. 2 |
| 5 | Sozialleistung durchsetzen oder anfechten | SGG |
| 6 | Steuerbescheid anfechten | FGO |
| 7 | Strafanzeige erstatten / Strafverfolgung initiieren | StPO / Staatsanwaltschaft |
| 8 | Verfassungsbeschwerde erheben | BVerfGG § 90 |
| 9 | EuGH-Vorabentscheidung anregen | Art. 267 AEUV |
| 10 | Einstweiligen Rechtsschutz beantragen | § 935 ff. ZPO / § 80 Abs. 5 VwGO / § 86b SGG |
| 11 | Familienrechtliche Entscheidung (Sorge, Unterhalt, Scheidung) | FamFG |
| 12 | Sonstiges / unklar | → Rückfragen |

## Rechtsweg-Abgrenzung (Überblick)

**Ordentliche Gerichtsbarkeit (ZPO):** Zivilrecht (BGB, HGB, WEG), Privatrecht allgemein. Klageart: allgemeine Leistungsklage, Feststellungsklage, Gestaltungsklage.

**Verwaltungsgerichtsbarkeit (VwGO):** Öffentliches Recht, Verwaltungsakte, Normerlass (§ 47 VwGO). Abgrenzung Verwaltungsakt/Realakt/öffentlich-rechtlicher Vertrag beachten.

**Sozialgerichtsbarkeit (SGG):** Sozialversicherung, SGB I–XII, AsylbLG. Widerspruchspflicht (§§ 83 ff. SGG).

**Finanzgerichtsbarkeit (FGO):** Steuer- und Zollrecht. Einspruch vor Klage (§ 44 FGO).

**Strafgerichtsbarkeit (StPO):** Nur staatliche Strafverfolgung. Kein privatrechtlicher Anspruch hier — ggf. Nebenklage.

**BVerfG:** Grundrechtsverletzung durch staatliche Gewalt, Erschöpfung des Rechtswegs (§ 90 Abs. 2 BVerfGG).

## Warnmechanik

Das System warnt bei folgenden Konstellationen:

- Nutzer nennt Ziel im Zivilrecht, Sachverhalt klingt nach öffentlichem Recht (z. B. Baugenehmigung): Hinweis auf VwGO.
- Nutzer möchte Strafanzeige, aber Sachverhalt betrifft nur Zivilrecht (Vertragsstreit): Hinweis auf fehlende Strafbarkeit im Zivilrecht.
- Mehrere Rechtswege möglich (z. B. Presserecht: Unterlassung ZPO, Gegendarstellungsanspruch VwGO bei öffentlich-rechtlichem Rundfunk): Hinweis auf Wahlmöglichkeit.
- Rechtsweg noch nicht erschöpft: Hinweis auf Widerspruchspflicht oder Vorverfahren.

**Das System trifft keine verbindliche Rechtswegentscheidung.** Es liefert einen Orientierungshinweis. Die endgültige Bestimmung des Rechtswegs obliegt dem zuständigen Gericht (§ 17a GVG).

## Ausgabe

Strukturierter Hinweis:
- Erkanntes Ziel
- Wahrscheinlicher Rechtsweg
- Klageart (soweit bestimmbar)
- Erforderliche Voraussetzungen (Widerspruch, Frist, Beschwer)
- Nächster Skill im Workflow

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
