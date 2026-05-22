---
name: falsche-wiese-warnung
description: "Warnt vor typischen Falschverortungen im Recht: Vertrag statt Delikt, Verwaltungsakt vs. Realakt, Strafrecht statt Ordnungswidrigkeit, Unionsrecht statt nationales Recht. Mechanisches Durchpruefen der richtigen Pruefungsebene vor Normanwendung."
---

# Falsche-Wiese-Warnung

## Zweck

„Auf der falschen Wiese grasen" ist ein klassisches Problem der Rechtsanwendung: Man prüft eine Norm sorgfältig und korrekt — aber die falsche Norm. Dieses Problem kann durch mechanisches Prüfen nicht gelöst werden; das System kann nur auf typische Muster hinweisen und Nutzereingaben einer Plausibilitätskontrolle unterziehen.

Dieser Skill wird automatisch oder auf Anforderung aktiviert, wenn der Sachverhalt oder die gewählte Norm Anzeichen einer Fehlverortung enthält.

## Typische Falschverortungen

### 1. Vertrag statt Delikt (oder umgekehrt)

**Muster:** Nutzer prüft Vertragsrecht (§§ 280 ff. BGB), obwohl kein Vertrag besteht. Oder: Nutzer prüft § 823 Abs. 1 BGB, obwohl eine vertragliche Sonderbeziehung vorliegt (die ggf. Anspruchskonkurrenz oder Spezialität begründet).

**Indizien für Fehlverortung:** Keine Willenserklärungen beschrieben; kein Vertragsschluss erwähnt; Handlung ist einseitig schädigend ohne Vertragsbezug.

**Hinweis des Systems:** „Ihr Sachverhalt enthält keinen erkennbaren Vertragsschluss. Bitte prüfen Sie, ob eine deliktische Anspruchsgrundlage (§ 823 Abs. 1 oder Abs. 2 BGB, § 826 BGB) primär einschlägig ist."

### 2. Verwaltungsakt statt Realakt (oder öffentlich-rechtlicher Vertrag)

**Muster:** Nutzer möchte ein staatliches Handeln anfechten, das kein Verwaltungsakt ist (z. B. staatliche Warnung, schlicht-hoheitliches Handeln, tatsächliche Vollstreckungsmaßnahme).

**Indizien:** Kein Regelungscharakter beschrieben; keine Einzelfallentscheidung; keine Behördenbezeichnung oder Rechtsbehelfsbelehrung im Bescheid.

**Hinweis des Systems:** „Das beschriebene Handeln könnte ein Realakt (nicht anfechtbarer Verwaltungsakt nach § 35 VwVfG) sein. Prüfen Sie, ob eine allgemeine Leistungsklage oder Unterlassungsklage (§ 40 Abs. 1 VwGO) passender ist."

### 3. Strafrecht statt Ordnungswidrigkeit (oder umgekehrt)

**Muster:** Nutzer prüft § 303 StGB (Sachbeschädigung), obwohl es sich um eine Ordnungswidrigkeit nach OWiG handeln könnte. Oder: Nutzer will Strafanzeige erstatten bei einem Bußgeldtatbestand.

**Indizien:** Kein Vorsatz beschrieben; Schaden gering; Handlung im Straßenverkehr ohne Verletzung.

**Hinweis des Systems:** „Prüfen Sie zunächst, ob der Sachverhalt eine Ordnungswidrigkeit nach dem OWiG oder einem Nebengesetz erfüllt. Strafrecht (Freiheitsstrafe / Geldstrafe nach StGB) ist subsidiär zu Ordnungswidrigkeitenrecht."

### 4. Unionsrecht statt nationales Recht (oder umgekehrt)

**Muster:** Nutzer prüft nationales Datenschutzgesetz (BDSG), obwohl die DSGVO als EU-Verordnung unmittelbar gilt. Oder: Nutzer prüft DSGVO, obwohl ein rein nationaler Sachverhalt vorliegt.

**Indizien:** Datenverarbeitung; grenzüberschreitender Bezug; Verbraucherrecht mit möglicher Richtlinienumsetzung.

**Hinweis des Systems:** „Bitte prüfen Sie, ob Unionsrecht (Verordnung mit unmittelbarer Geltung oder richtlinienkonforme Auslegung) vorgeht. Der Anwendungsvorrang des Unionsrechts verdrängt entgegenstehendes nationales Recht (EuGH, Rs. Costa/ENEL)."

### 5. Weitere typische Muster

- Schadensersatz statt Unterlassung (und umgekehrt)
- Primäranspruch statt Sekundäranspruch (Erfüllung statt Schadensersatz statt der Leistung)
- WEG-Recht statt BGB-Schuldrecht bei Eigentumswohnungen
- Erbrecht statt Familienrecht bei Güterstand-Fragen
- Insolvenzrecht als Vorfrage bei Ansprüchen gegen insolvente Schuldner

## Ausgabe

Das System gibt strukturierten Hinweis:
- Erkanntes Muster der Fehlverortung
- Empfohlene Alternativnorm oder -rechtsgebiet
- Frage an den Nutzer: Möchten Sie die alternative Norm prüfen?

Das System setzt die Prüfung der ursprünglich gewählten Norm nur auf ausdrücklichen Nutzerwunsch fort.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
