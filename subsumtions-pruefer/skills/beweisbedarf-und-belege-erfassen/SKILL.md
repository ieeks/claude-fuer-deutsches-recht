---
name: beweisbedarf-und-belege-erfassen
description: "Erfasst pro Tatbestandsmerkmal den Beweisbedarf: Beweismittel-Katalog (Urkunden, Zeugen, Sachverstaendige, Augenschein, Parteivernehmung), Belege hochladen, Tatsachenbehauptung eintragen oder 'beweise ich spaeter'-Markierung setzen. Strukturiertes Beweis-Tracking."
---

# Beweisbedarf und Belege erfassen

## Zweck

Jede Subsumtion steht und fällt mit dem Beweisergebnis. Dieser Skill erfasst für jedes Tatbestandsmerkmal (TBM), welche Beweismittel benötigt werden, welche der Nutzer bereits hat und welche noch beschafft werden müssen. Er erstellt eine strukturierte Beweisliste.

## Beweismittel-Katalog (ZPO)

| Beweismittel | § ZPO | Typische Nachweise |
|-------------|-------|-------------------|
| Urkundsbeweis | §§ 415 ff. ZPO | Vertrag, Rechnung, E-Mail, Bescheid, Quittung, Protokoll |
| Zeugenbeweis | §§ 373 ff. ZPO | Personen, die den TBM-relevanten Vorgang erlebt haben |
| Sachverständigenbeweis | §§ 402 ff. ZPO | Technische, medizinische, buchhalterische Fragen |
| Augenschein | §§ 371 ff. ZPO | Besichtigung von Sachen, Orten, digitalen Inhalten |
| Parteivernehmung | §§ 445 ff. ZPO | Nur subsidiär; Nutzer als Partei |
| Elektronische Beweismittel | § 371 Abs. 1 S. 2 ZPO | Screenshots, Metadaten, Logs — Echtheit muss dargelegt werden |

Im Verwaltungs- und Strafverfahren gelten die jeweiligen Verfahrensordnungen (VwGO, StPO); das System passt den Katalog an.

## Vorgehen pro TBM

Das System geht jedes TBM der Reihe nach durch und fragt:

1. **Tatsachenbehauptung:** Was behauptet der Nutzer für dieses TBM? (Freitext-Eingabe)
2. **Beleg vorhanden?** Der Nutzer kann angeben:
   - (A) Beleg liegt vor (Dokument, Foto, Screenshot) → Hochladen oder Benennen
   - (B) Zeuge bekannt → Name und Erreichbarkeit notieren
   - (C) Tatsache behaupte ich; Beleg beschaffe ich später → Markierung „offen"
   - (D) Keine Tatsache vorhanden für dieses TBM → TBM als nicht erfüllt markieren

3. **Beweiswert-Hinweis:** Das System gibt einen groben Hinweis auf den typischen Beweiswert des genannten Beweismittels (z. B. öffentliche Urkunde: voller Beweis § 415 ZPO; Privaturkunde: § 416 ZPO begrenzt).

## Besondere Konstellationen

### Elektronische Dokumente

E-Mails, Screenshots und PDFs sind Beweismittel, aber ihre Echtheit kann bestritten werden. Das System empfiehlt:
- Metadaten sichern (Datum, Absender, Header)
- Zeitnahe Sicherung und Archivierung
- Ggf. Datenschutz-Aspekte bei personenbezogenen Drittdaten beachten

### Zeugenbeweis

Das System fragt nach vollständigem Namen und Adresse des Zeugen. Es weist darauf hin, dass das Gericht den Zeugen selbst lädt — der Zeuge muss nicht persönlich zur Kanzlei kommen.

### Urkundsbeweis — Originale vs. Kopien

Das System weist darauf hin, dass Originale stets vorzuziehen sind. Kopien können bestritten werden (§ 420 ZPO).

## Beweis-Tracking-Liste

Am Ende der Beweiserfassung erstellt das System eine tabellarische Übersicht:

| TBM | Behauptete Tatsache | Beweismittel | Status |
|-----|--------------------|--------------|----|
| [TBM 1] | [Nutzerangabe] | [Typ] | vorhanden / offen / fehlt |
| [TBM 2] | … | … | … |

„Offen" markierte TBM werden als Risikopositionen der Klage / des Antrags ausgewiesen.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
