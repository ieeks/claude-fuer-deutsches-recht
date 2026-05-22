---
name: einschlaegige-normen-vorschlagen-de
description: "Schlaegt anhand eines Lebenssachverhalts einschlaegige Normen des deutschen Rechts vor: BGB, HGB, StGB, StPO, ZPO, VwGO, GG, AO, SGB und Nebengesetze. Gibt Pruefungsreihenfolge und Hinweise auf Spezialitaet und konkurrierende Anspruchsgrundlagen."
---

# Einschlägige Normen vorschlagen — Deutsches Recht

## Zweck

Dieser Skill unterstützt den Nutzer bei der Identifikation einschlägiger Normen des deutschen Rechts anhand eines geschilderten Lebenssachverhalts. Das System macht Vorschläge auf der Grundlage des im Sachverhalt beschriebenen Rechtsgebiets und der typischen Anspruchsgrundlagen. Die endgültige Normwahl liegt beim Nutzer.

## Vorgehen

**Schritt 1 — Sachverhalts-Kategorisierung**

Das System kategorisiert den Sachverhalt nach Rechtsgebiet:

| Kategorie | Typische Normen |
|-----------|----------------|
| Vertragsrecht | §§ 433 ff. BGB (Kauf); §§ 611 ff. BGB (Dienst/Arbeitsvertrag); §§ 631 ff. BGB (Werkvertrag); §§ 535 ff. BGB (Miete) |
| Deliktsrecht | § 823 Abs. 1 BGB; § 823 Abs. 2 BGB i. V. m. Schutzgesetz; § 826 BGB; § 831 BGB |
| Bereicherungsrecht | §§ 812 ff. BGB — Leistungskondiktion, Nichtleistungskondiktion |
| Sachenrecht | §§ 854 ff. BGB (Besitz); §§ 903 ff. BGB (Eigentum); §§ 985 ff. BGB (Herausgabe) |
| Strafrecht | § 263 StGB (Betrug); § 303 StGB (Sachbeschädigung); § 223 StGB (Körperverletzung); § 242 StGB (Diebstahl); § 266 StGB (Untreue) |
| Arbeitsrecht | KSchG; § 623 BGB (Schriftform Kündigung); ArbGG; MuSchG; AGG |
| Verwaltungsrecht | § 35 VwVfG (Verwaltungsakt); § 48 VwVfG (Rücknahme); § 49 VwVfG (Widerruf); § 42 VwGO (Klagen) |
| Sozialrecht | SGB I–XII; § 44 SGB X (Rücknahme); § 45 SGB X (Aufhebung) |
| Steuerrecht | § 38 AO (Entstehung der Steuerschuld); §§ 172 ff. AO (Bestandskraft) |
| Erbrecht | §§ 1922 ff. BGB; §§ 2303 ff. BGB (Pflichtteil) |
| Familienrecht | §§ 1353 ff. BGB; §§ 1601 ff. BGB (Unterhalt); §§ 1564 ff. BGB (Scheidung) |

**Schritt 2 — Normvorschlag mit Prüfungshinweis**

Das System nennt:
1. Primäre Anspruchsgrundlage (wahrscheinlichste Norm)
2. Konkurrierende Normen (Anspruchskonkurrenz oder -idealkonkurrenz)
3. Ausschlussnormen (Spezialität: z. B. Kaufgewährleistung § 437 BGB geht § 823 BGB vor, wenn nur Äquivalenzinteresse betroffen)
4. Vorfragen (z. B. Wirksamkeit des Vertrags, Geschäftsfähigkeit)

**Schritt 3 — Hinweis auf Rechtsprechung**

Das System weist darauf hin, dass für die Auslegung der vorgeschlagenen Normen aktuelle Rechtsprechung zu prüfen ist (BGH, BAG, BVerwG, BSG, BFH je nach Rechtsgebiet). Für aktuelle Entscheidungen empfiehlt es: dejure.org, openjur.de, bundesgerichtshof.de, rechtsprechung-im-internet.de.

**Schritt 4 — Normwahl durch Nutzer bestätigen**

Das System listet Vorschläge auf und bittet den Nutzer, die zu prüfende Norm zu bestätigen oder eine andere Norm anzugeben. Erst nach Bestätigung wird die Norm in `norm-zerlegen-in-tatbestandsmerkmale` übergeben.

## Grenzen

Das System kennt seinen Wissensstand und weist ausdrücklich darauf hin, dass:
- Gesetzesänderungen nach dem Wissensstand nicht erfasst sind
- Landesrecht (z. B. Landesbauordnungen, kommunales Satzungsrecht) nur eingeschränkt vorgeschlagen werden kann
- Sondergesetze (z. B. EnWG, TKG, AMG, LFGB) nur grob kategorisiert werden

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
