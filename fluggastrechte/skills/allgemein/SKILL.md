---
name: allgemein
description: "Einstieg und Triage fuer Fluggastrechte nach VO (EG) Nr. 261/2004: Stoerungsereignis einordnen, Ausgleichszahlung berechnen, Airline-Ausreden widerlegen, Forderungsschreiben und Klage vorbereiten."
---

# Fluggastrechte — Allgemein

## Worum geht es?

Die Verordnung (EG) Nr. 261/2004 gibt Fluggaesten bei Annullierung, erheblicher Verspaetung (ab drei Stunden am Endziel nach EuGH-Sturgeon-Rechtsprechung) und Nichtbefoerderung wegen Ueberbuchung einen Ausgleichsanspruch von 250 bis 600 EUR pro Person gegen das ausfuehrende Luftfahrtunternehmen. Das Plugin deckt den vollstaendigen Mandatsablauf ab: von der Falldaten-Erfassung ueber die Berechnung der Ausgleichszahlung, die Pruefung von Airline-Ausreden, das Forderungsschreiben bis hin zur Klageschrift vor dem Amtsgericht.

Dieses Plugin richtet sich sowohl an Verbraucher, die ihre Ansprueche selbst geltend machen wollen, als auch an Anwalte, die Fluggaeste vertreten.

## Wann brauchen Sie diese Skill?

- Ihr Flug wurde annulliert oder Sie sind wegen Ueberbuchung nicht befoerdert worden und Sie wollen Ihre Ansprueche klaeren.
- Ihr Flug hatte Verspaetung und Sie wollen wissen, ob Sie mehr als drei Stunden am Endziel verspaetet angekommen sind.
- Die Airline hat Ihre Forderung mit einer Standardausrede (technischer Defekt, aussergewoehnliche Umstaende) abgelehnt und Sie wollen dagegen vorgehen.
- Sie vertreten mehrere Familienmitglieder und benoetigen Vollmachten fuer die Durchsetzung.
- Sie wollen eine Klageschrift fuer das Amtsgericht erstellen, nachdem aussergerichtliche Schritte erfolglos waren.

## Fachbegriffe (kurz erklaert)

- **Annullierung** — Streichung eines zuvor geplanten Fluges (Art. 5 VO 261/2004); unterscheidet sich rechtlich von einer Verspaetung.
- **Aussergewoehnliche Umstaende** — Ereignisse, die sich der Kontrolle des Luftfahrtunternehmens entziehen (Art. 5 Abs. 3 VO 261/2004); entlastet die Airline von der Ausgleichspflicht.
- **Grosskreisdistanz** — die fuer die Stufenberechnung der Ausgleichszahlung massgebliche Entfernung zwischen Abflug- und Zielflughafen.
- **Operating Carrier** — das tatsaechlich ausfuehrende Luftfahrtunternehmen; massgeblich fuer die Passivlegitimation, nicht das vermarktende Unternehmen bei Codeshare.
- **PNR** — Passenger Name Record (Buchungscode); identifiziert eine zusammenhaengende Buchung bei Verbindungsfluegen.
- **Sturgeon-Rechtsprechung** — EuGH C-402/07: Verspaetungen ab drei Stunden Ankunftsverspaetung am Endziel sind Annullierungen gleichgestellt.

## Rechtsgrundlagen

- Art. 3 VO (EG) 261/2004 — Anwendungsbereich (EU-Abflug oder EU-Ankunft mit EU-Carrier)
- Art. 4 VO (EG) 261/2004 — Nichtbefoerderung
- Art. 5 VO (EG) 261/2004 — Annullierung
- Art. 6 VO (EG) 261/2004 — Verspaetung
- Art. 7 VO (EG) 261/2004 — Ausgleichszahlung (250/400/600 EUR)
- § 23 Nr. 1 GVG — sachliche Zustaendigkeit Amtsgericht bis 10.000 EUR (seit 01.01.2026)
- EuGH C-402/07 (Sturgeon) — Verspaetung ab drei Stunden gleichgestellt
- EuGH C-11/11 (Folkerts) — Anschlussflug, Endziel-Verspaetung massgeblich

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Einzelperson oder Reisegruppe/Familie? Selbstmandat oder anwaltliche Vertretung?
2. Phase des Mandats bestimmen: Stoerungsereignis noch nicht eingeordnet (Annullierung vs. Verspaetung?), aussergerichtliche Phase oder Klage?
3. Passenden Skill auswaehlen (siehe Skill-Tour unten).
4. Eilfristen pruefen: Verjaebrung der Ansprueche aus VO 261/2004 richtet sich nach nationalem Recht; in Deutschland 3 Jahre (§ 195 BGB) zum Jahresende.
5. Anschluss-Skill bestimmen: Nach Einordnung des Stoerungsereignisses Ausgleichszahlung berechnen, dann Forderungsschreiben.

## Skill-Tour (was gibt es hier?)

- `fluggastrechte-kaltstart-interview` — Ersteinrichtung des Plugins: Anwendungsrolle, Buchungskonvention und Profil anlegen.
- `ticket-und-fluginformationen-erfassen` — Falldaten aus Tickets und Buchungsbestaetigungen extrahieren und Fallakte anlegen.
- `annullierung-oder-verspaetung-einordnen` — Rechtliche Einordnung des Stoerungsereignisses nach Art. 4-6 VO 261/2004 und Sturgeon-Rechtsprechung.
- `distanz-und-ausgleich-berechnen` — Ausgleichszahlung nach Art. 7 VO 261/2004 berechnen (Grosskreis-Distanz, Staffelung 250/400/600 EUR).
- `ausnahmen-aussergewoehnliche-umstaende-pruefen` — Prueft die Einrede aussergewoehnlicher Umstaende (Art. 5 Abs. 3 VO 261/2004) mit EuGH-Pinpoints.
- `airline-standardausreden-pruefen` — Katalog typischer Airline-Ablehnungsgruende mit Gegenargumenten und EuGH-Rechtsprechungs-Pinpoints.
- `anschlussflug-und-reiseplan` — Berechnung bei Verbindungsfluegen: Endziel-Verspaetung nach EuGH Folkerts massgeblich.
- `vollmacht-familienmitglieder` — Vollmachten fuer Mitreisende erstellen, damit ein Hauptansprechpartner alle Ansprueche buendeln kann.
- `forderungsschreiben-erste-stufe` — Erstes Forderungsschreiben an die Airline mit Rechtsbegruendung und Fristsetzung.
- `forderungsschreiben-mahnung` — Zweite Stufe nach Ablauf der Erstfrist; Nachfrist, Verzugszinsen, Klageandrohung.
- `fluggastrechte-anlagen-bauen` — BeA-konformes Anlagenkonvolut (Buchungsbestaetigung, Boardingpass, E-Mails) fuer Schriftsaetze erstellen.
- `klage-amtsgericht-fluggast` — Vollstaendiger Klageschrift-Entwurf fuer das Amtsgericht mit Streitwert und EuGH-Begruendung.

## Worauf besonders achten

- **Operating Carrier identifizieren**: Bei Codeshare-Fluegen ist nicht das vermarktende Unternehmen, sondern der tatsaechliche Ausfuehrungs-Carrier passivlegitimiert; das Ticket nennt bisweilen nur den Verkaeufer.
- **Sturgeon-Dreistunden-Schwelle**: Die Verspaetung wird an der tatsaechlichen Ankunftszeit am Endziel gemessen — nicht an der Abflugverspaetung; der Zeitpunkt, zu dem die Passagiertuer geoeffnet wird, gilt als Ankunftszeit.
- **Anschlussflug unter einer PNR**: Wenn ein Anschlussflug verpaesst wird, zaehlt die Gesamtverspaetung am Endziel fuer den Ausgleich; separate PNRs begrenzen den Anspruch auf die jeweilige Strecke.
- **Aussergewoehnliche Umstaende begruendungspflichtig**: Die Airline muss sowohl das aussergewoehnliche Ereignis als auch die zumutbaren Gegenmassnahmen darlegen; pauschale Verweise genuegen nicht.
- **Verjaebrung**: Der Anspruch verjaehrt in drei Jahren nach § 195 BGB; auf Jahresende-Berechnung nach § 199 BGB achten.

## Typische Fehler

- Annullierung und lange Verspaetung werden nicht unterschieden: Beide koennen Ausgleichsansprueche ausloesen, aber die Beweislage ist unterschiedlich.
- Volle Ausgleichszahlung wird beansprucht, obwohl die Airline einen Ersatzflug mit kurzer Verspaetung angeboten hat: Art. 7 Abs. 2 VO 261/2004 sieht eine Halbierung vor.
- Forderungsschreiben ohne Bankverbindung: Airline kann nicht leisten; Verzug tritt erst mit konkreter Zahlungsmoeglichkeit ein.
- Umbuchungs-Voucher als Erfuellung akzeptiert: Ein Gutschein ersetzt den Baranspruch nicht, wenn der Passagier dem nicht ausdruecklich zugestimmt hat.
- Ansprueche von Mitreisenden ohne Vollmacht geltend gemacht: Prozessual fehlt dann die Ermaechtigung zur Einziehung fremder Forderungen.

## Querverweise

- `prozessrecht` — Wenn der Fluggast-Fall vor dem Amtsgericht wird und prozessrechtliche Fragen (Zustaendigkeit, Fristen, Mahnbescheid) auftauchen.
- `selbstvertreter-amtsgericht` — Wenn der Mandant ohne Anwalt klagen will und eine Orientierung fuer das Amtsgerichtsverfahren benoetigt.

## Quellen und Aktualitaet

- Stand: 05/2026
- VO (EG) Nr. 261/2004 in geltender Fassung
- § 23 Nr. 1 GVG: Streitwertgrenze 10.000 EUR seit 01.01.2026
- EuGH C-402/07 (Sturgeon), EuGH C-11/11 (Folkerts), EuGH C-559/16 (Wegener), EuGH C-257/14 (van der Lans), EuGH C-74/19 (Kruesemann)

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
