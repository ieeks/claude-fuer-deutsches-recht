---
name: allgemein
description: "Einstieg und Ueberblick fuer das Patentrecherche-Plugin: agentische Datenbankrecherche in Espacenet, Google Patents, DEPATISnet, EPO-Register und USPTO, Neuheitspruefung nach § 3 PatG und Art. 54 EPUe, erfinderische Taetigkeit, FTO, Patentfamilien und Rechtsstandpruefung."
---

# Patentrecherche — Allgemein

## Worum geht es?

Das Plugin unterstuetzt Patentanwaelte, Patentassistenten und technische Berater bei der systematischen Patentrecherche in nationalen und internationalen Datenbanken. Es deckt die gesamte Bandbreite von der Neuheitspruefung vor Anmeldung ueber die Pruefung erfinderischer Taetigkeit bis zur Freedom-to-Operate-Recherche (FTO) ab.

Das Plugin arbeitet agentisch: Es steuert Datenbankabfragen in Espacenet, Google Patents, DPMAregister, DEPATISnet, EPO Register, WIPO und USPTO nach den CPC/IPC-Klassifikationen und dem Problem-Solution-Approach der EPA-Beschwerdekammern. Ergebnisse werden in formalen Rechercheberichten und Anmelde-Antwort-Paketen dokumentiert.

## Wann brauchen Sie diese Skill?

- Mandant hat neue Erfindung und will wissen, ob sie neuheitlich und erfinderisch genueg fuer eine Patentanmeldung ist.
- Unternehmen plant Markteintritt mit neuem Produkt und braucht FTO-Recherche zu aktiven Schutzrechten von Wettbewerbern.
- Patentanwalt erhaelt Pruefungsbescheid des DPMA oder EPA und muss Antwort mit Stand-der-Technik-Analyse vorbereiten.
- Mandant will Patentportfolio eines Konkurrenten laufend beobachten (Ueberwachung Neuanmeldungen).
- Rechtsstandpruefung eines Patents: Ist das Schutzrecht noch in Kraft? Sind Jahresgebuehren bezahlt?

## Fachbegriffe (kurz erklaert)

- **Neuheit (§ 3 PatG / Art. 54 EPUe)** — Eine Erfindung gilt als neu, wenn sie nicht zum Stand der Technik gehoert; jeder Voroffenbarung (weltweit, zeitlos) schadet.
- **Erfinderische Taetigkeit (§ 4 PatG / Art. 56 EPUe)** — Erfindung darf sich fuer den Fachmann nicht in naheliegender Weise aus dem Stand der Technik ergeben.
- **Problem-Solution-Approach (PSA)** — Standardmethode der EPA-Beschwerdekammern: naechster Stand der Technik, objektive technische Aufgabe, naheliegend?
- **CPC / IPC** — Cooperative Patent Classification / International Patent Classification; hierarchische Klassifikationssysteme fuer Patentdokumente.
- **Freedom to Operate (FTO)** — Pruefung, ob ein Produkt oder Verfahren in einen Anspruch eines Drittpatents faellt und damit Verletzungsrisiko besteht.
- **INPADOC** — Internationaler Patenddokumentationsdienst; liefert Familienzusammenhaenge und Rechtsstanddaten ueber EPO.
- **Patentfamilie** — Alle nationalen und regionalen Schutzrechte, die auf dieselbe Prioritaetsanmeldung zurueckgehen.

## Rechtsgrundlagen

- §§ 1-5 PatG — Patentierbarkeit (Neuheit, erfinderische Taetigkeit, gewerbliche Anwendbarkeit)
- § 3 PatG — Neuheit
- § 4 PatG — Erfinderische Taetigkeit
- §§ 34 ff. PatG — Patentanmeldung beim DPMA
- §§ 44 45 PatG — Pruefungsverfahren DPMA
- Art. 52-57 EPUe — Patentierbarkeit nach Europaeischem Patentrecht
- Art. 94 EPUe — Pruefungsverfahren EPA

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Neuanmeldung, FTO, Pruefungsbescheid-Antwort oder Konkurrenzueberwachung?
2. Erfindungsmaterial aufnehmen: Anspruchsentwurf, Beschreibung oder technisches Dokument hochladen.
3. Klassifikation bestimmen: CPC/IPC-Klassen fuer gezielte Datenbanksuche festlegen.
4. Passenden Skill auswaehlen (siehe Skill-Tour).
5. Recherchebericht erstellen und Ergebnisse dem Mandanten kommunizieren.

## Skill-Tour (was gibt es hier?)

- `patentrecherche-kaltstart-interview` — Erstkontakt und Aufnahme der Rechercheanforderungen: Wer recherchiert, was ist das Ziel, welches Material liegt vor?
- `klassifikation-cpc-ipc` — CPC- und IPC-Klassen fuer die Datenbankrecherche bestimmen und Klassifikationsdossier erstellen.
- `agentische-datenbank-recherche` — Agentische Suche in natuerlicher Sprache ueber Espacenet, Google Patents, DEPATISnet, WIPO und USPTO.
- `stand-der-technik-recherche` — Stand der Technik vor Patentanmeldung identifizieren und bewerten.
- `neuheit-pruefen` — Neuheit nach § 3 PatG und Art. 54 EPUe systematisch pruefen; Merkmal-fuer-Merkmal-Abgleich.
- `erfinderische-taetigkeit-pruefen` — Erfinderische Taetigkeit nach § 4 PatG und Art. 56 EPUe mit Problem-Solution-Approach pruefen.
- `freedom-to-operate-recherche` — FTO-Recherche vor Markteintritt: aktive Drittpatente mit relevantem Scope identifizieren.
- `patentfamilien-analyse` — Alle Familienmitglieder eines Schutzrechts ueber INPADOC und Espacenet ermitteln.
- `rechtsstand-pruefen` — Aktuellen Rechtsstand eines Patents oder einer Anmeldung im jeweiligen Register pruefen.
- `pruefungsbescheid-vorbereiten` — Antwort auf DPMA-Pruefungsbescheid (§ 45 PatG) oder EPA-Bescheid (Art. 94 EPUe) systematisch vorbereiten.
- `recherchebericht-erstellen` — Formalen Recherchebericht mit Methodik, Datenbanken, Suchstrategien und Ergebnissen erstellen.
- `ueberwachung-konkurrenten` — Watch-Profile fuer laufende Ueberwachung neuer Patentanmeldungen von Wettbewerbern anlegen.
- `rueckfragen-mandant` — Rueckfragen an den Mandanten generieren, wenn Erfindungsmaterial unvollstaendig oder ambivalent ist.

## Worauf besonders achten

- Neuheitsschaedlichkeit ist weltweit und zeitlich unbegrenzt: Auch 20 Jahre alte Veroeffentlichungen koennen Neuheit zerstoeren.
- FTO und Anmelderecherche sind unterschiedliche Aufgaben mit unterschiedlichem Scope; Verwechslung fuehrt zu falschen Ergebnissen.
- Pruefungsbescheide haben feste Fristen (§ 45 PatG: 4 Monate, verlaengerbar; Art. 94 EPUe: aehnlich); versaeumte Fristen fuehren zu Zurueckweisung.
- Patentfamilien-Analyse ist essenziell: Ein nationales Schutzrecht kann international wirken; nur Famille-Pruefung zeigt Gesamtscope.
- Veroeffentlichungen des Anmelders vor dem Prioritaetstag koennen neuheitsschaedlich sein (Ausnahme: 6-Monats-Schonfrist in manchen Systemen, z.B. USPTO).

## Typische Fehler

- Recherche nur in einer Datenbank: Relevante Dokumente sind oft nur in DEPATISnet oder USPTO-Datenbanken, nicht in Espacenet.
- Falschen Zeitschnitt gesetzt: FTO-Recherche erfordert nur noch in Kraft befindliche Schutzrechte; Neuheitsrecherche erfordert alle Veroeffentlichungen bis zum Anmeldetag.
- CPC-Klassifikation zu eng gewaehlt: Aehnliche Technologien in Nachbarklassen werden uebersehen.
- Pruefungsbescheid-Argumente zu schwach: Ohne detaillierten Merkmals-Abgleich (Feature-by-Feature-Analysis) akzeptiert EPA keine summarischen Stellungnahmen.
- Rechtsstand nicht gecheckt: FTO-Recherche gegen abgelaufene oder fallen lassene Patente liefert unnoetigen Aufwand.

## Querverweise

- Plugin `markenrecht-fashion-luxus` — Bei Design- und Markenstreitigkeiten ergaenzt Patentrecherche Schutzrechtspruefung.
- Plugin `grosskanzlei-corporate-ma` — Bei M&A-Transaktionen ist IP-Due-Diligence (Patentportfolio des Targets) ein Kernthema.
- Plugin `umweltrecht` — Greentech-Patente koennen mit Genehmigungspflichten nach BImSchG zusammentreffen.

## Quellen und Aktualitaet

- Stand: 05/2026
- PatG und EPUe in aktuell geltender Fassung
- Espacenet, DEPATISnet, DPMAregister, USPTO, WIPO PatentScope (Stand 05/2026)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
