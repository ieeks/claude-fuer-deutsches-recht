---
name: allgemein
description: "Einstieg und Orientierung im JVEG-Kostenpruefer-Plugin. Klaert Anspruchsberechtigung, Verguetungskategorien (Sachverstaendige, Dolmetscher, Zeugen), Fristen, Festsetzung, Beschwerde und Routing zu allen 19 Spezial-Skills."
---

# JVEG-Kostenpruefer — Allgemein

## Worum geht es?

Das JVEG-Kostenpruefer-Plugin prueft und berechnet Verguetungsansprueche nach dem Justizvergutungs- und -entschaedigungsgesetz (JVEG) fuer alle gerichtlich herangezogenen Personen: Sachverstaendige, Dolmetscher und Uebersetzer, Zeugen sowie sonstige Beteiligte. Es erstellt belegfeste Rechenprotokolle, prueft Kuerz­ungen durch das Gericht, bereitet Antraege und Beschwerden vor und bewertet die Korrektheit von Gerichtsschreiben zur Kostenfestsetzung.

Das Plugin ist mandatsneutral: Es wird sowohl von Sachverstaendigen genutzt, die ihre Rechnung optimieren wollen, als auch von Gerichten, Anwaelten oder Parteien, die eine Sachverstaendigenrechnung pruefen. Es ersetzt keine Rechtsberatung.

## Wann brauchen Sie diese Skill?

- Sachverstaendiger hat seine Rechnung gestellt und moechte pruefen, ob alle Positionen nach JVEG ansetzbar sind.
- Gericht hat eine Kostenfestsetzung erlassen und Sachverstaendiger oder Zeuge will widersprechen oder Beschwerde einlegen.
- Anwalt prueft, ob die Sachverstaendigenrechnung der Gegenseite korrekt ist und Kuerzungsmoeglichkeiten bestehen.
- Zeuge moechte nach einer Aussage vor Gericht seine Entschaedigung (Fahrtkosten, Zeitversaeumnis, Verdienstausfall) beantragen.
- Dolmetscher oder Uebersetzer will seine Stundenverguetung und Nebenkosten nach JVEG abrechnen.

## Fachbegriffe (kurz erklaert)

- **JVEG** — Justizvergutungs- und -entschaedigungsgesetz; regelt Verguetung und Entschaedigung fuer Sachverstaendige, Dolmetscher, Zeugen und andere vom Gericht herangezogene Personen.
- **Anspruchsberechtigung** — Nur gerichtlich beauftragte Personen (§§ 1 und 2 JVEG) sind anspruchsberechtigt; kein Anspruch fuer privatgutachterliche Taetigkeit.
- **Dreimonatsfrist** — Verguetungsanspruch erlischt, wenn er nicht innerhalb von drei Monaten nach Abschluss der Taetigkeit geltend gemacht wird (§ 2 Abs. 1 JVEG).
- **Verguetungssaetze Anlage 1** — Stundenverguetung fuer Sachverstaendige nach Honorargruppen; fuer Dolmetscher nach § 9 JVEG und Anlage 1 JVEG.
- **Barauslagen** — Erstattungsfaehige Aufwendungen nach § 7 JVEG (Porto, Kopieren, technische Geraete); Belegpflicht.
- **§ 8a JVEG** — Kuerzung oder Wegfall der Verguetung bei verspaetem oder fehlerhaftem Gutachten; Verschuldens- und Kausalitaetserfordernis.
- **Kostenfestsetzungsbeschluss** — Gerichtliche Entscheidung ueber die Hoehe der JVEG-Verguetung; anfechtbar per Beschwerde nach § 4 Abs. 3 JVEG.
- **KI-Deklaration** — Pflicht zur Offenlegung, ob und wie KI-Systeme bei der Gutachtenerstattung eingesetzt wurden; pruefungsrelevant fuer Gutachtenwert.

## Rechtsgrundlagen

- §§ 1 und 2 JVEG — Anwendungsbereich und Anspruchsberechtigung.
- § 2 Abs. 1 JVEG — Dreimonatsfrist Geltendmachung.
- § 3 JVEG — Vorschuss.
- § 4 JVEG — Festsetzung; § 4 Abs. 3 JVEG — Beschwerde.
- § 5 JVEG — Fahrtkosten.
- § 6 JVEG — Uebernachtungs- und Verpflegungskosten.
- § 7 JVEG — Sonstige Aufwendungen.
- § 8 JVEG — Verguetung Sachverstaendige; § 8a JVEG — Kuerzung und Wegfall.
- § 9 JVEG, Anlage 1 JVEG — Dolmetscher und Uebersetzer.
- §§ 19 bis 22 JVEG — Zeugenentschaedigung, Verdienstausfall, Haushaltsfuehrung.
- §§ 165 ff. SGB III (im Kontext) — Insolvenzgeld; nicht JVEG.

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Personenkategorie bestimmen: Sachverstaendiger, Dolmetscher, Uebersetzer oder Zeuge?
2. Verfahrensschritt bestimmen: Erstrechnung, Widerspruch gegen Kuerzung, Beschwerde, Vorschuss?
3. Routing: Skill `jveg-kommandocenter` fuer die Weiterleitung zum richtigen Spezial-Skill.
4. Fristen pruefen: `jveg-fristen-erloeschen` — ist die Dreimonatsfrist noch offen?
5. Rechnung pruefen oder erstellen: `jveg-sachverstaendigenrechnung` oder `jveg-rechenblatt`.

## Skill-Tour (was gibt es hier?)

**Einstieg und Navigation**

- `jveg-kommandocenter` — Navigationszentrum fuer alle JVEG-Skills: Weiterleitung je Personenkategorie und Verfahrensschritt.
- `jveg-anspruchsberechtigung` — Anspruchsberechtigung nach JVEG pruefen: Personenkategorie und gerichtliche Beauftragung.
- `jveg-fristen-erloeschen` — Dreimonatsfrist pruefen; Fristbeginn, Fristende, Wiedereinsetzungsmoeglichkeit.

**Verguetungsberechnung Sachverstaendige**

- `jveg-sachverstaendigenrechnung` — Sachverstaendigenrechnung pruefen oder erstellen: Stundenverguetung und Nebenkosten.
- `jveg-rechenblatt` — Strukturiertes Rechenblatt fuer alle JVEG-Kostenpositionen je Kategorie.
- `jveg-aktenstripper` — JVEG-relevante Daten aus Gerichtsakten und Gutachterunterlagen extrahieren.
- `jveg-kuerzung-wegfall-8a` — Kuerzung oder Wegfall der Verguetung nach § 8a JVEG bei Verspaetung oder Fehlern.
- `pruefung-sachverstaendigengutachten-ki-deklaration` — KI-Deklaration in Sachverstaendigengutachten pruefen.

**Verguetungsberechnung Dolmetscher und Uebersetzer**

- `jveg-dolmetscher-uebersetzer` — Stundenverguetung, Mindestwartezeit, Anfahrt und schriftliche Uebersetzung je Seite.

**Zeugenentschaedigung**

- `jveg-zeugenentschaedigung` — Fahrtkosten, Zeitversaeumnis und Verdienstausfall fuer Zeugen.
- `jveg-verdienstausfall-haushalt-zeit` — Verdienstausfall und Zeitversaeumnis nach §§ 20 ff. JVEG.

**Kostenpositionen**

- `jveg-fahrtkosten` — Fahrtkosten: eigenes Fahrzeug, oeff. Verkehrsmittel, Flug.
- `jveg-uebernachtung-aufwand` — Uebernachtungs- und Verpflegungskosten nach § 6 JVEG.
- `jveg-sonstige-aufwendungen-belege` — Sonstige Aufwendungen nach § 7 JVEG mit Belegpflicht.

**Antrag, Vorschuss und Rechtsmittel**

- `jveg-vorschuss` — Vorschuss nach § 3 JVEG: Voraussetzungen, Formerfordernis, Verfahren.
- `jveg-antragsgenerator` — Verguetungsantrag, Anlagen und Fristen fuer die gerichtliche Kostenfestsetzung.
- `jveg-gerichtsschreiben-pruefung` — Gerichtsschreiben zur Kostenkuerzung rechtlich pruefen und widersprechen.
- `jveg-festsetzung-beschwerde` — Beschwerde gegen Kostenfestsetzungsbeschluss nach § 4 Abs. 3 JVEG.

**Qualitaetssicherung**

- `jveg-quality-gate` — Vollstaendigkeits- und Konsistenzpruefung aller Kostenpositionen vor Einreichung.

## Worauf besonders achten

- **Dreimonatsfrist ist Ausschlussfrist** — § 2 Abs. 1 JVEG kennt keine automatische Verlaengerung; nach Ablauf ist der Anspruch erloschen.
- **Belegpflicht fuer Aufwendungen** — Sonstige Aufwendungen nach § 7 JVEG werden ohne Beleg nicht erstattet; Porto und Kopien muessen belegt sein.
- **§ 8a JVEG ist kein Automatismus** — Kuerzung oder Wegfall setzt Verschulden und Kausalitaet voraus; ein verspaetendes Gutachten fuehrt nicht zwingend zum Verguetungsverlust.
- **KI-Nutzung deklarieren** — Gerichte verlangen zunehmend Offenlegung des KI-Einsatzes; fehlende Deklaration kann Gutachtenwert beeinflussen und Verguetungsstreit ausloesen.
- **Honorargruppe korrekt einordnen** — Falsche Einordnung in Anlage 1 JVEG fuehrt zur Kuerzung; Sachgebiet und Schwierigkeitsgrad des Gutachtens bestimmen die Gruppe.

## Typische Fehler

- Sachverstaendiger stellt Vorschussantrag, aber das Gericht hat keine Vorschussanforderung gestellt; Verfahrensfehler.
- Zeuge beantragt Verguetung nach drei Monaten; Anspruch ist erloschen.
- Fahrtkosten werden mit privatem Pkw abgerechnet, obwohl guenstigeres Bahnticket zumutbar war.
- Sachverstaendiger ordnet sich selbst in eine hoehere Honorargruppe ein, ohne Begrunndung; Gericht kuerzt auf naechste Gruppe.
- Widerspruch gegen Kuerzung wird als formelle Beschwerde nach § 4 Abs. 3 JVEG eingereicht, obwohl Beschwerdesumme unterschritten ist.

## Querverweise

- `normenkontrolle-bauleitplanung` — Bei Sachverstaendigenkosten im oeffentlich-rechtlichen Normenkontrollverfahren.
- `insolvenzrecht` — Bei Sachverstaendigenbeauftragung im Insolvenzverfahren.
- `bereicherungs-und-anfechtungsrecht-pruefer` — Wenn zu Unrecht gezahlte JVEG-Verguetung zurueckgefordert werden soll.

## Quellen und Aktualitaet

- Stand: 05/2026
- JVEG in der geltenden Fassung
- Anlage 1 JVEG (Honorargruppen und Stundensaetze) in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
