---
name: allgemein
description: "Einstieg in die Arbeitszeugnis-Analyse nach Ampelsystem: Zeugnisart erkennen, Geheimcodes und Steigerungsadverbien decodieren, Notenmatrix erstellen, Gesamtnote aggregieren und Berichtigungs- oder Klagestrategie ableiten."
---

# Arbeitszeugnis-Analyse (Ampelsystem) — Allgemein

## Worum geht es?

Das Ampelsystem fuer die Zeugnisanalyse decodiert die verdeckte Notenskalierung in deutschen Arbeitszeugnissen: Formulierungen werden Ampelfarben zugeordnet (gruen = Note eins bis zwei, orange = Note drei, rot = Note vier bis fuenf). Das Plugin deckt den gesamten Mandatsablauf ab: vom Erstgespraech ueber die satzweise Notenmatrix und Gesamtnotenberechnung bis hin zum Mandantenbericht, dem aussergerichtlichen Aufforderungsschreiben und der Klagestrategie vor dem Arbeitsgericht.

Zielgruppe sind Arbeitsrechts-Anwaelte und deren Sekretariate. Das Plugin ist auf die BAG-Rechtsprechung zum Zeugnisrecht abgestimmt.

## Wann brauchen Sie diese Skill?

- Ein Arbeitnehmer hat ein Zeugnis erhalten, das er fuer inhaltlich oder sprachlich ungenuegend haelt, und sucht anwaltliche Einschaetzung.
- Ein Auszubildender will sein Ausbildungszeugnis nach § 16 BBiG anfechten.
- Ein Mandat im Kuendigungsschutz beinhaltet auch einen Zeugnisanspruch (§ 109 GewO), der in einem Vergleich geregelt werden soll.
- Eine Fuerungskraft erhaelt ein Zeugnis ohne Fuehrungs-Bausteine und fragt, ob das ein Negativsignal ist.
- Die Kanzlei benoetigt ein Schulungsmaterial fuer die Zeugnisanalyse (Musterzeugnisse).

## Fachbegriffe (kurz erklaert)

- **Geheimcode** — Formulierung, die trotz positiv klingendem Wortlaut eine schlechte Bewertung kodiert (z.B. "Er hat sich bemuht" = mangelhaft).
- **Steigerungsadverb** — Adverb, das die Staerke eines Lobs quantifiziert; Fehlen eines Steigerungsadverbs senkt die Note um eine Stufe.
- **Schaufenster-Drift** — einzelne Spitzensaetze (Note eins) in einem Themenbereich, der sonst nur Note drei traegt; systematisch irreführend.
- **Schlussformel** — dreisteiliges Pflichtelement: Bedauern, Dank und Zukunftswuensche; jedes fehlende Element senkt die Gesamtnote.
- **Wohlwollenspflicht** — Pflicht des Arbeitgebers, ein der Wahrheit entsprechendes, aber wohlwollendes Zeugnis auszustellen (§ 109 GewO).
- **Berichtigungsklage** — Klage auf Neufassung des Zeugnisses; Streitwert ein bis drei Bruttomonatsentgelte; Zustaendigkeit: Arbeitsgericht.

## Rechtsgrundlagen

- § 109 GewO — Anspruch auf qualifiziertes Zeugnis
- § 16 BBiG — Anspruch auf Ausbildungszeugnis
- § 241 Abs. 2 BGB — Wohlwollenspflicht (Nebenpflicht aus Arbeitsvertrag)
- § 195 BGB — Verjaehrung drei Jahre
- § 611a BGB — Arbeitsvertrag

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Arbeitnehmer oder Auszubildender? Endzeugniss, Zwischenzeugnis oder Ausbildungszeugnis?
2. Phase des Mandats bestimmen: Erstanalyse, aussergerichtliche Aufforderung, Klage oder Vergleichsformulierung?
3. Passenden Skill auswaehlen (siehe Skill-Tour unten).
4. Eilfristen pruefen: Verjaehrung des Berichtigungsanspruchs nach § 195 BGB; Verjaehrung beginnt mit Zeugniserhalt (§ 199 BGB).
5. Anschluss-Skill bestimmen: Nach Notenmatrix Gesamtnotenberechnung, dann Mandantenbericht, dann Aufforderungsschreiben.

## Skill-Tour (was gibt es hier?)

- `erstgespraech-und-mandatsannahme` — Mandatsannahme mit Unterlagenerfassung, Erstprognose und Fristen-Uebersicht.
- `zeugnisart-erkennung` — Unterscheidung qualifiziertes Endzeugnis, einfaches Zeugnis, Zwischenzeugnis und Ausbildungszeugnis.
- `zeugnis-ueberblick-extraktion` — Kopfdaten aus dem Zeugnis extrahieren: Arbeitgeber, Arbeitnehmer, Zeitraum, Position.
- `notenrelevante-saetze-identifizieren` — Notenrelevante Saetze von neutralen Aufgabenbeschreibungen trennen.
- `satzweise-notenmatrix` — Jeden notenrelevanten Satz mit Schulnote bewerten: Pruefraster Themenbereich, Note, Begruendung.
- `bereichs-drift-detektor` — Schaufenster-Pattern erkennen: Note-eins-Saetze neben Note-drei-Saetzen im gleichen Themenbereich.
- `gesamtnoten-aggregation` — Gewichtete Gesamtnote aus Leistungsteil, Verhaltensteil und Schlussformel aggregieren.
- `ampelsystem-tabellenausgabe` — Standardisierte Ampel-Ausgabetabelle fuer den Mandantenbericht erstellen.
- `geheimcode-katalog` — Zentraler Referenzkatalog aller Standardformulierungen mit Ampelzuordnung.
- `rote-flaggen-katalog` — Katalog Note-vier- und Note-fuenf-Signale mit Erlaeuterungen.
- `orange-flaggen-katalog` — Katalog Note-drei-Signale: fehlende Steigerungsadverbien und eingeschraenkte Lobesformeln.
- `gruen-flaggen-katalog` — Katalog Note-eins- und Note-zwei-Signale: Superlative und vollstaendige Zufriedenheitsformeln.
- `negative-codeworte-katalog` — Erweiterte Katalog kodierter Negativformulierungen (Sucht, Konflikte, Diebstahl, Loyalitaet).
- `steigerungsadverbien-katalog` — Vollstaendige Referenzliste aller Steigerungsadverbien mit Notenwert und Abgrenzung zu Scheinsteigern.
- `zufriedenheitsformel-decodierung` — Fuenfstufige Zufriedenheitsformel decodieren: von "vollste Zufriedenheit" bis "Zufriedenheit".
- `leistungsbeurteilung-analyse` — Saetze zu Arbeitsqualitaet, Arbeitsbereitschaft und Belastbarkeit decodieren.
- `verhaltensbeurteilung-analyse` — Verhaltensbeurteilungen decodieren: Reihenfolge der Genannten, Auslassungen, Qualifikationswoerter.
- `schlussformel-bewertung` — Vollstaendigkeit der drei Schlussformel-Elemente pruefen und Notenauswirkung bestimmen.
- `negationen-und-auslassungen-erkennen` — Fehlende Pflichtaussagen im Zeugnis identifizieren und als Negativsignal bewerten.
- `widerspruechliche-bewertungen` — Widersprueche zwischen Leistungsteil und Schlussformel erkennen und deren Signalwirkung erklaeren.
- `branchen-spezifische-formulierungen` — Branchenspezifische Formulierungen in Vertrieb, IT, Recht, Pflege und anderen Bereichen einordnen.
- `leitende-positionen-zeugnisse` — Zeugnisse fuer Fuehrungskraefte analysieren: fehlende Fuehrungs-Bausteine als Ampelsignal.
- `azubi-zeugnis-analyse` — Ausbildungszeugnisse nach § 16 BBiG analysieren: Lernfortschritt, Berufsschulleistungen, Verhalten.
- `verbesserungsvorschlaege-formulieren` — Konkrete Alternativformulierungen fuer orange und rote Saetze vorschlagen.
- `rechtliche-bewertung-bag-rechtsprechung` — Beweislastverteilung und Rechtsgrundlagen nach § 109 GewO und BAG-Linie fuer Klagebegruendung.
- `mandantenbericht-zeugnisanalyse` — Strukturierter Ergebnisbericht an den Mandanten mit Handlungsoptionen und Empfehlung.
- `aufforderungsschreiben-arbeitgeber` — Aussergerichtliches Berichtigungsverlangen mit BAG-Rechtsprechungs-Pinpoints und Fristsetzung.
- `klage-strategie-zeugnisberichtigung` — Klageschrift-Baustein fuer Zeugnisberichtigungsklage vor dem Arbeitsgericht.
- `muster-arbeitszeugnis-note-1` — Vollstaendiges Musterarbeitszeugnis Note eins als Referenzdokument.
- `muster-arbeitszeugnis-mit-roten-flaggen` — Anonymisiertes Beispielzeugnis mit roten und orangen Bewertungen als Schulungsmaterial.
- `muster-arbeitszeugnis-gemischte-noten` — Schulungszeugnis mit Schaufenster-Pattern und Drift-Analyse als Lernbeispiel.

## Worauf besonders achten

- **Steigerungsadverb-Pruefung**: Ein fehlendes "stets" oder "jederzeit" senkt die Note des gesamten Satzes; auch Frequenzadverbien wie "regelmaessig" oder "gelegentlich" bedeuten Note drei oder schlechter.
- **Schaufenster-Pattern fruehzeitig erkennen**: Einzelne Spitzensaetze koennen den Gesamteindruck bewusst positiver erscheinen lassen; der Bereichs-Drift-Detektor muss jeden Themenbereich separat auswerten.
- **Schlussformel ist Pflichtelement**: Ein fehlendes Bedauern senkt die Gesamtnote messbar; Arbeitgeber koennen nicht auf Schlussformel-Bestandteile verzichten, ohne Notenfolgen zu akzeptieren.
- **Beweislast beim Zeugnisstreit**: Arbeitnehmer muss darlegen, dass seine Leistung besser war als das Zeugnis suggeriert; Arbeitgeber hat dann die schlechtere Note zu substantiieren.
- **Verjaehrung beachten**: Der Berichtigungsanspruch verjaehrt in drei Jahren nach § 195 BGB; bei laengerer Untaetigkeit des Mandanten Fristen rechnen.

## Typische Fehler

- Zeugnisart nicht bestimmt: Eine Zwischenzeugnisanalyse unterscheidet sich vom Endzeugniss; Massstabe sind nicht identisch.
- Notenmatrix ohne Bereichs-Drift erstellt: Die Gesamtnote kann positiver erscheinen, als die satzweise Analyse vermuten laesst; Drift-Pruefung ist Pflicht.
- Verbesserungsvorschlaege zu allgemein formuliert: Das Gericht verurteilt nicht zu einer bestimmten Formulierung, wenn der Antrag zu weit oder zu unkonkret ist; praezise Antragsformulierung ist entscheidend.
- Keine Beweislastanalyse vor dem Aufforderungsschreiben: Wenn die Ausgangsbewertung nicht substantiiert werden kann, ist die Aussicht auf eine Klage gering.
- Schlussformel als optional behandelt: Fehlende Zukunftswuensche sind ein messbares Note-Drei-Signal; Mandanten muessen das verstehen.

## Querverweise

- `arbeitsrecht` — Wenn der Zeugnisanspruch im Rahmen einer Kuendigungsschutzklage oder eines Aufhebungsvertrags geregelt wird.
- `prozessrecht` — Fuer prozessuale Fragen zur Klageschrift, Beweislast und Vollstreckung von Zeugnisurteilen.

## Quellen und Aktualitaet

- Stand: 05/2026
- § 109 GewO in geltender Fassung
- § 16 BBiG in geltender Fassung
- BAG-Rechtsprechung zum Zeugnisrecht (aktuelle Fassung)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
