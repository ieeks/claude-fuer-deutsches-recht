---
name: allgemein
description: "Einstieg ins Mandantenanfragen-Assistent-Plugin: eingehende Kanzlei-E-Mails parsen, Erstantwort DSGVO-konform generieren, Dringlichkeit prüfen, Konfliktcheck vorschalten und Mandatshinweis setzen."
---

# Mandantenanfragen-Assistent — Allgemein

## Worum geht es?

Der Mandantenanfragen-Assistent unterstuetzt Anwaltskanzleien bei der Bearbeitung eingehender Mandantenanfragen per E-Mail. Er strukturiert den Eingang, erkennt Dringlichkeit und Fristen, erzeugt eine professionelle Erstantwort mit korrekter Anrede und allen berufsrechtlich gebotenen Hinweisen (kein Mandatsverhaeltnis, DSGVO, Verschwiegenheit) und bereitet CRM-Eintrag sowie Aktenanlage vor.

Das Plugin ersetzt kein eigentliches Mandat. Es schafft einen effizienten, berufsrechtskonformen Eingangskanal fuer Sekretariat und Anwaltschaft.

## Wann brauchen Sie diese Skill?

- Eine neue E-Mail-Anfrage ist eingegangen und das Sekretariat soll schnell entscheiden, wie dringend und ob ein Interessenkonflikt besteht.
- Eine Erstantwort soll professionell, mit exakter Anrede und Pflichthinweisen, innerhalb von Minuten verschickt werden.
- Der potenzielle Mandant hat auf Englisch, Franzoesisch oder Italienisch geschrieben und die Antwort soll in derselben Sprache erfolgen.
- Das Kanzlei-CRM soll mit den Kerndaten aus der Anfrage befuellt werden, ohne dass die Anwaltschaft jeden Eintrag manuell verfasst.
- Es soll geprueft werden, ob eine Anfrage Spam, Phishing oder eine Massen-Mandantenanfrage ist.

## Fachbegriffe (kurz erklaert)

- **Mandatsverhaeltnis** — das durch Mandatsvertrag begrundete Rechtsverhaeltnis zwischen Anwalt und Mandant; entsteht nicht bereits durch eine Erstanfrage.
- **Interessenkonflikt** — Situation, in der der Anwalt nicht beide Seiten vertreten darf (§ 43a Abs. 4 BRAO, § 3 BORA); muss vor Mandatsannahme geprueft werden.
- **DSGVO-Einwilligung** — erforderlich, wenn die Kanzlei ein Telefongespraech transkribiert und den Text verarbeitet (Art. 6 Abs. 1 lit. a DSGVO).
- **Transkriptionsservice** — Kanzlei-Angebot, bei dem der Mandant seinen Fall per Telefon schildert und die Aufzeichnung fuer das Erstgespraech aufbereitet wird.
- **Berufsrecht** — BRAO, BORA und die berufsrechtlichen Pflichten des Anwalts, insbesondere Verschwiegenheit (§ 43a Abs. 2 BRAO) und Unabhaengigkeit.

## Rechtsgrundlagen

- § 43a Abs. 2 BRAO — Verschwiegenheitspflicht
- § 43a Abs. 4 BRAO — Verbot der Vertretung widerstreitender Interessen
- § 3 BORA — Interessenkonflikt-Check
- § 203 StGB — Verletzung von Privatgeheimnissen (Grenze anwaltlicher Schweigepflicht)
- Art. 6 Abs. 1 lit. a DSGVO — Einwilligung als Rechtsgrundlage
- Art. 13 DSGVO — Informationspflicht bei Datenerhebung

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Ist die Anfrage eine echte Neuanfrage, eine Folgekommunikation oder Spam?
2. Phase des Mandats bestimmen: Erstkontakt (kein Mandat), vor Mandatsannahme (Konfliktcheck noetig) oder laufendes Mandat?
3. Passenden Skill auswaehlen (siehe Skill-Tour unten).
4. Eilfristen pruefen: Dringlichkeits-Check auf Signalwoerter (Hauptverhandlung, Kuendigungsfrist, Zwangsvollstreckung).
5. Anschluss-Skill bestimmen: Nach Erstantwort ggf. Folgekorrespondenz-Vorbereitung und CRM-Eintrag.

## Skill-Tour (was gibt es hier?)

- `anfrage-eingang-parser` — Eingehende E-Mail strukturiert auswerten: Kontaktdaten, Sachverhalts-Extrakt, Dringlichkeitssignale.
- `dringlichkeitsmarker` — Erkennt Eilbedarf in der Anfrage (Fristen, Vollstreckung, Hauptverhandlung) und gibt Dringlichkeitsstufe aus.
- `spam-und-massen-anfrage-filter` — Unterscheidet echte Mandantenanfragen von Spam, Phishing und Massen-Anfragen.
- `konfliktcheck-vorab` — Gibt Abfragestruktur fuer den Interessenkonflikt-Check nach § 43a Abs. 4 BRAO vor.
- `anrede-uebernehmen` — Ermittelt die korrekte formelle Anredezeile aus dem Absender (Titel, Doppelnamen, Paare).
- `erstantwort-generator` — Erzeugt die vollstaendige Erstantwort-E-Mail mit Pflichthinweisen, Terminangebot und DSGVO-Text.
- `muster-erstantwort` — Fertige ausfuellbare Vorlage fuer die Erstantwort in drei Varianten (Standard, Vorname, Transkriptionsservice).
- `mehrsprachige-antwort` — Erstantwort auf Englisch, Franzoesisch oder Italienisch in der Sprache der eingehenden Anfrage.
- `einwilligung-hinweis-datenschutz` — DSGVO-konforme Einwilligungsklausel fuer den Transkriptionsservice (Art. 6 DSGVO).
- `transkriptionsdienst-erklaerung` — Erklaert den Transkriptionsservice und integriert den Ablauf in die Erstantwort.
- `mandatsverhaeltnis-hinweis` — Disclaimer-Texte: kein Mandatsverhaeltnis, keine Rechtsberatung durch Erstanfrage.
- `vertraulichkeit-erinnerung` — Instruktion fuer das Sekretariat: wann die Schweigepflicht gilt und was das konkret bedeutet.
- `folgekorrespondenz-vorbereiten` — CRM-Skeleton-Eintrag und Aktenanlage aus den geparsten Anfragedaten.
- `telefon-konfiguration` — Kanzlei-Telefonnummern fuer Sekretariat und Transkriptionsservice in Templates hinterlegen.

## Worauf besonders achten

- **Kein Rechtsrat in der Erstantwort**: Auch eine gut gemeinte Erstantwort darf keine inhaltliche Rechtsberatung enthalten; das loest Haftungsrisiken aus, ohne dass ein Mandat begruendet wurde.
- **Anrede prazise uebernehmen**: Fehler bei akademischen Titeln (Dr., Prof.) oder Doppelnamen sind der haeufigste Grund fuer unprofessionellen Ersteindruck.
- **DSGVO-Pflichten beim Transkriptionsservice**: Ohne Einwilligung und Datenschutzhinweis ist die Transkription eines Telefonats nicht rechtsgemaess; die Einwilligung muss fuer den konkreten Zweck erteilt werden.
- **Interessenkonflikt-Zeitpunkt**: Der Check muss vor jeder Terminvergabe erfolgen — nicht erst bei Mandatsannahme.
- **Schweigepflicht gilt nicht ab Erstanfrage**: Sekretariatsmitarbeiter muessen wissen, dass die Verschwiegenheitspflicht erst nach Mandatsbeginn gilt, vorher aber allgemeine Diskretionspflichten bestehen.

## Typische Fehler

- Erstantwort enthaelt bereits inhaltliche Einschaetzungen zum Sachverhalt: Der Anwalt ist dann moeglicherweise beratend taetig ohne Verguetungsanspruch und mit Haftungsrisiko.
- Interessenkonflikt-Check wird uebersprungen: Bei spaeterer Entdeckung muss das Mandat niedergelegt werden; Reputations- und Haftungsschaden.
- DSGVO-Einwilligung fuer Transkription fehlt: Datenschutzrechtliche Abmahnung oder Busgeld moeglich.
- Spam nicht erkannt: Massen-Anfragen und 419-Scams binden Kanzlei-Ressourcen ohne jeden Nutzen.
- Mehrsprachige Anfragen auf Deutsch beantwortet: Mandant fuehl sich nicht abgeholt; Kanzlei verliert potenzielle Mandate.

## Querverweise

- `arbeitsrecht` — Wenn die Erstanfrage ein arbeitsrechtliches Anliegen betrifft und sofortige Fristen-Pruefung (§ 4 KSchG) noetig ist.
- `prozessrecht` — Bei Mandantenanfragen mit unmittelbar drohendem Gerichtstermin oder Vollstreckungsankuendigung.
- `fluggastrechte` — Wenn Mandantenanfragen per E-Mail zu Flugstoerungen eingehen und Selbst-Mandats-Workflow beginnt.

## Quellen und Aktualitaet

- Stand: 05/2026
- BRAO in geltender Fassung
- BORA in geltender Fassung
- DSGVO (VO (EU) 2016/679) in geltender Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
