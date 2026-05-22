# Testakte: Wandeldarlehen Sonnenglas UG / Northstar Pre-Seed Partners

**Fiktiver Beispielfall** zur Demonstration des Plugins `wandeldarlehen-lebenszyklus`.

## Parteien

| Rolle | Partei |
|---|---|
| Gesellschaft | Sonnenglas Solartechnologie UG (haftungsbeschränkt), HRB 123456 B, AG Charlottenburg, Sitz Berlin |
| Gesellschafterin 1 | Dr. Mira Schoeneck, Berlin (40 Geschäftsanteile, 40 %) |
| Gesellschafterin 2 | Lina Habersaat, Hamburg (35 Geschäftsanteile, 35 %) |
| Treasury | Sonnenglas Solartechnologie UG eigene Anteile (25 Geschäftsanteile, 25 %) |
| Darlehensgeber (Lender) | Northstar Pre-Seed Partners GmbH & Co. KG, Frankfurt am Main |

## Stammkapital

EUR 1.000 (eintausend Euro), aufgeteilt in 100 Geschäftsanteile zu je EUR 1,00 Nennwert.

Dr. Schoeneck ist zugleich alleinvertretungsberechtigte Geschäftsführerin.

## Konditionen des Wandeldarlehens

| Parameter | Wert |
|---|---|
| Darlehensbetrag | EUR 250.000 |
| Laufzeit | 2 Jahre (Feste Laufzeit) |
| Zinssatz | 5,0 % p.a. (act/360) |
| Auszahlung | 7 Bankarbeitstage nach Unterzeichnung |
| Valuation Cap | EUR 4.000.000 Pre-Money |
| Discount | 20 % auf Rundenpreis |
| Qualified Financing | Mindest-Pre-Money EUR 4.000.000, Mindest-Investment EUR 500.000 |
| Maturity-Bewertung | EUR 4.000.000 Pre-Money (Fall-back) |

## Unternehmenshintergrund

Sonnenglas Solartechnologie UG entwickelt intelligente Solarmodul-Steuerungssoftware für Kleinanlagen. Gegründet im Jahr 2024 in Berlin. Das Wandeldarlehen dient der Überbrückungsfinanzierung bis zur geplanten Seed-Runde im Q1 2027 mit einer angestrebten Pre-Money-Bewertung von EUR 5–8 Mio.

## Szenarien in den Testdokumenten

1. **Bilingualer Vertrag** (`Wandeldarlehen-Sonnenglas-Northstar-bilingual.docx`) — vollständiger Vertragstext DE/EN mit allen verbesserten Klauseln (Cap/Discount, MFN, Pro-rata, Liquidationspräferenz 1x, BGH-Verweis Rangrücktritt, DIS-Schiedsklausel).

2. **Einsprachiger Vertrag** (`Wandeldarlehen-Sonnenglas-Northstar-nur-deutsch.docx`) — identischer materieller Inhalt, nur auf Deutsch, einspaltig.

3. **Pre-Money Cap-Table** (`Cap-Table-Pre-Money.xlsx`) — Ausgangslage vor Wandlung.

4. **Post-Money Cap-Table** (`Cap-Table-Post-Money.xlsx`) — nach Seed-Runde EUR 1 Mio bei Pre-Money EUR 6 Mio; Northstar wandelt zu Cap-Preis (EUR 40.000 je Anteil) → 7 neue Anteile.

5. **Wandlungserklärung** (`Wandlungserklaerung-Muster.docx`) — Muster-Wandlungserklärung Northstar an Sonnenglas nach Qualified Financing.

6. **Gesellschafterbeschluss** (`Gesellschafterbeschluss-Kapitalerhoehung-Muster.docx`) — Beschluss über Kapitalerhöhung gegen Sacheinlage (Forderung aus Wandeldarlehen).

7. **Notar-Paket** (`Notar-Paket-Inhaltsverzeichnis.docx`) — Inhaltsverzeichnis aller für den Notar einzureichenden Unterlagen.

## Passendes Plugin

`wandeldarlehen-lebenszyklus` — alle 30 Skills von Phase A (Erstellung) bis Phase D (HR-Anmeldung).

## Einstieg in die Akte

Nutze den Skill `mandat-triage-wandeldarlehen` als Einstieg, dann `bilinguale-vertragserstellung` oder `einsprachige-vertragsfassung-de` für die Vertragserstellung. Für die Wandlungsrechnung: `wandlungspruefung-trigger-qualified-financing` → `wandlungspreis-berechnung` → `cap-table-update-pre-post`.

## Disclaimer

Alle Personen, Firmen, Konten, Beträge und Aktenzeichen sind frei erfunden. Übereinstimmungen mit realen Personen oder Unternehmen wären rein zufällig. Die Akte dient ausschließlich dem Testen des Plugins und ist keine Rechtsberatung.
