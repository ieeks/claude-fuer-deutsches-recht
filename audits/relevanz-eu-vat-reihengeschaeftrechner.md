# Relevanz-Memo: Repo `claude-fuer-deutsches-recht` für das Tool `eu-vat-reihengeschaeftrechner`

## 1. Sachverhalt

Es bestehen zwei getrennte Repositories:

- **`claude-fuer-deutsches-recht`** (dieses Repo): Sammlung von Claude-Code-Plugins für deutsche
  Kanzleien (107 Plugins, rund 2.617 Skills), durchgängig deutschsprachig, mit festen
  Methodik- und Zitierkonventionen.
- **`eu-vat-reihengeschaeftrechner`**: separates Tool zur umsatzsteuerlichen Beurteilung von
  Reihengeschäften im EU-Binnenmarkt.

Geprüft wurde, ob Inhalte dieses Repos für den Reihengeschäft-Rechner wiederverwendbar oder
fachlich relevant sind.

> **Zugriffsbeschränkung:** Auf das Repo `eu-vat-reihengeschaeftrechner` bestand kein Zugriff
> (Werkzeuge sind auf `claude-fuer-deutsches-recht` beschränkt). Dieses Memo ist daher eine
> reine Quell-Analyse dieses Repos; Aussagen über die Architektur des Zielrepos sind als
> Annahmen gekennzeichnet.

## 2. Frage

Welche Bestandteile dieses Repos sind für einen EU-USt-Reihengeschäft-Rechner relevant oder
direkt portierbar?

## 3. Kurzantwort

Ein fertiges Reihengeschäft-Modul existiert nicht; wertvoll sind jedoch die Quellen- und
Qualitätsdisziplin (Zitierweise, Methodik, Konventionen) sowie mehrere fachlich angrenzende
USt-, Incoterms- und Zoll-Bausteine, die im Reihengeschäft mitlaufen.

## 4. Relevanzanalyse

### A. Quellen- und Qualitätsdisziplin (direkt übernehmbar)

Diese Artefakte sind tool- und rechtsgebietsunabhängig und lassen sich unmittelbar in das
Zielrepo übernehmen:

- [`references/zitierweise.md`](../references/zitierweise.md) – „Harte Sperren" gegen
  halluzinierte Fundstellen (kein BeckRS/Kommentar/Aufsatz aus Modellwissen; Rechtsprechung nur
  mit Gericht, Entscheidungsform, Datum, Aktenzeichen, prüfbarer Quelle). Enthält die Liste
  amtlicher Primärquellen – darunter `curia.europa.eu` für die für Reihengeschäfte zentrale
  EuGH-USt-Rechtsprechung.
- [`CLAUDE.md`](../CLAUDE.md) – Konventionen, die das Verhalten des Tools prägen können:
  deutsche Ausgaben in Sie-Form, Gutachten- vs. Urteilsstil, feste Memo-Struktur, „jede
  juristische Aussage wird belegt", sowie die SKILL.md-Frontmatter-Regeln (nur `name` und
  `description`; `description` ≤ 1024 Zeichen; keine Dezimal-Kommas wie `1,5`).
- [`references/methodik-buergerliches-recht.md`](../references/methodik-buergerliches-recht.md) –
  Auslegungsmethodik einschließlich unionsrechtskonformer Auslegung; nutzbar als Stil- und
  Qualitätsrahmen für die juristische Begründungstiefe.

### B. Fachlich angrenzende Skills (Bausteine, die im Reihengeschäft mitlaufen)

Diese Skills decken nicht das Reihengeschäft selbst ab, behandeln aber Teilfragen, die in jeder
Reihengeschäft-Beurteilung auftreten – sie taugen als fachliche Vorlage:

- [`steuerrecht-anwalt-und-berater/skills/anw-umsatzsteuer-vorsteuerabzug-pruefen/SKILL.md`](../steuerrecht-anwalt-und-berater/skills/anw-umsatzsteuer-vorsteuerabzug-pruefen/SKILL.md)
  – behandelt die innergemeinschaftliche Lieferung (§ 6a UStG, Steuerbefreiung über
  § 15 Abs. 3 UStG), Reverse-Charge (§ 13b UStG), die USt-IdNr.-Prüfung über das BZSt
  (qualifizierte Bestätigungsanfrage) sowie die eRechnungspflicht. Genau diese Punkte bestimmen,
  ob die **bewegte Lieferung** im Reihengeschäft steuerfrei ist und ob die materiellen
  Voraussetzungen (gültige USt-IdNr. – „Quick Fixes") erfüllt sind.
- [`regulatorisches-recht/skills/ustva/SKILL.md`](../regulatorisches-recht/skills/ustva/SKILL.md)
  – Umsatzsteuer-Voranmeldung nach § 18 UStG; berücksichtigt innergemeinschaftliche Erwerbe und
  Reverse Charge. Relevant für die Melde-/Erklärungsfolgen, die der Rechner ausgeben könnte.
- [`urteilsbauer-relationsmacher/skills/incoterms-und-gefahruebergang/SKILL.md`](../urteilsbauer-relationsmacher/skills/incoterms-und-gefahruebergang/SKILL.md)
  – Incoterms 2020 (EXW, FCA, FOB, CIF, DAP, DDP), Lieferort und Transport-/Kostenverteilung.
  Für Reihengeschäfte zentral, weil die **Transportveranlassung** über die Zuordnung der
  bewegten Lieferung mitentscheidet.

  > **Wichtige Abgrenzung für den Rechner:** Die umsatzsteuerliche Zuordnung der Warenbewegung
  > (§ 3 Abs. 6a UStG) ist **nicht identisch** mit dem zivilrechtlichen Gefahrübergang nach
  > Incoterms/CISG. Incoterms sind ein **Indiz** für die Transportveranlassung, nicht das
  > maßgebliche umsatzsteuerliche Zuordnungskriterium. Der Skill behandelt den Gefahrübergang –
  > beim Übernehmen muss diese Trennung sauber abgebildet werden.

- [`aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-zollwert-ursprung/SKILL.md`](../aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-zollwert-ursprung/SKILL.md)
  und
  [`aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-verbrauchsteuer/SKILL.md`](../aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-verbrauchsteuer/SKILL.md)
  – Drittlandsbezug: Einfuhr-Umsatzsteuer, Abgrenzung innergemeinschaftlicher Erwerb vs.
  Einfuhr. Relevant für Reihengeschäfte mit Drittlandsbeteiligung (Lieferort der Einfuhr-
  Konstellation, § 3 Abs. 8 UStG).

### C. Build- und Konventions-Infrastruktur (optional)

Nur relevant, falls der Reihengeschäft-Rechner selbst als Claude-Code-Skill/Plugin gebaut wird
(Annahme – Architektur des Zielrepos unbekannt):

- [`scripts/validate.py`](../scripts/validate.py),
  [`scripts/validate-yaml-frontmatter.py`](../scripts/validate-yaml-frontmatter.py) –
  Struktur-/Frontmatter-Validierung.
- [`scripts/generate-skills-overview.py`](../scripts/generate-skills-overview.py),
  [`scripts/sync-references.py`](../scripts/sync-references.py) – Übersichts-Generierung und
  Synchronisierung gemeinsamer Referenzdateien.
- [`.claude-plugin/marketplace.json`](../.claude-plugin/marketplace.json) – Muster für ein
  Plugin-Manifest.

## 5. Lücke und Abgrenzung

Der **Kern des Reihengeschäfts** ist im Repo **nicht** abgebildet und müsste im Zielrepo neu
erstellt werden:

- Definition und Zuordnung der Warenbewegung, § 3 Abs. 6a UStG (in Kraft seit 01.01.2020),
- Unterscheidung bewegte vs. ruhende Lieferung und deren Lieferort (§ 3 Abs. 6a i. V. m.
  § 3 Abs. 7 UStG),
- Sonderfall Transport durch den mittleren Unternehmer und Verwendung der USt-IdNr.,
- innergemeinschaftliches Dreiecksgeschäft / Vereinfachung § 25b UStG,
- die unionsrechtlichen „Quick Fixes" (gültige USt-IdNr. und Zusammenfassende Meldung als
  materielle Voraussetzungen der Steuerbefreiung).

Bei der Neuerstellung ist die Quellendisziplin aus `references/zitierweise.md` einzuhalten –
insbesondere **keine halluzinierten EuGH-Aktenzeichen**; einschlägige EuGH-Rechtsprechung ist
über `curia.europa.eu` zu verifizieren.

## 6. Empfehlung

1. **Direkt portieren** (Abschnitt A): `references/zitierweise.md` und die Kernkonventionen aus
   `CLAUDE.md` als Quellen-/Stilrahmen in den Reihengeschäft-Rechner übernehmen.
2. **Als fachliche Vorlage nutzen** (Abschnitt B): Die USt-, Incoterms- und Zoll-Skills als
   Bausteine für die Teilprüfungen (Steuerbefreiung bewegte Lieferung, USt-IdNr.-Prüfung,
   Transportveranlassung, Drittlandsfälle) heranziehen – mit der unter B genannten Abgrenzung.
3. **Optional** (Abschnitt C): Build-/Validierungsskripte übernehmen, falls das Tool als
   Skill-Plugin strukturiert wird.
4. **Folgeschritt (separat):** Bei Bedarf einen dedizierten Reihengeschäft-Skill
   (§ 3 Abs. 6a, § 25b UStG, Quick Fixes) nach den Konventionen dieses Repos erstellen.

## 7. Risiken / offene Punkte

- Kein Zugriff auf `eu-vat-reihengeschaeftrechner` – Annahmen über dessen Architektur und
  bestehende Inhalte konnten nicht verifiziert werden.
- Aktualität: Der im Repo geführte Rechtsstand ist Mai 2026; vor Übernahme den jeweils aktuellen
  Stand prüfen.
- Übernahmehinweis: Beim Portieren juristischer Inhalte die Quellendisziplin strikt einhalten
  (keine ungeprüften Fundstellen).

## 8. Quellenverzeichnis

**Normen (Gesetzestext, verifizierbar):**

- UStG §§ 3 Abs. 6a, 3 Abs. 7, 3 Abs. 8, 6a, 13b, 14, 15, 18, 25b
- UStDV (Klein-Betrag-Rechnung § 33; Dauerfristverlängerung §§ 46 f.)

**Referenzierte Repo-Dateien:**

- `CLAUDE.md`
- `references/zitierweise.md`, `references/methodik-buergerliches-recht.md`
- `steuerrecht-anwalt-und-berater/skills/anw-umsatzsteuer-vorsteuerabzug-pruefen/SKILL.md`
- `regulatorisches-recht/skills/ustva/SKILL.md`
- `urteilsbauer-relationsmacher/skills/incoterms-und-gefahruebergang/SKILL.md`
- `aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-zollwert-ursprung/SKILL.md`
- `aussenwirtschaft-zoll-sanktionen/skills/aussenwirtschaft-verbrauchsteuer/SKILL.md`

> Hinweis gemäß `references/zitierweise.md`: Dieses Memo zitiert bewusst **keine**
> Rechtsprechung, Kommentare oder Aufsätze aus Modellwissen. Einschlägige EuGH- und
> BFH-Rechtsprechung zum Reihengeschäft ist vor Verwendung über amtliche Quellen
> (`curia.europa.eu`, `bfh.bund.de`) zu verifizieren.
