---
name: allgemein
description: "Einstieg in das Vertragsrecht-Plugin: Lieferanten- und Vertriebsvertraege, AGB-Pruefung, NDA, SaaS/MSA, Abmahnung UWG, Renewal-Tracking und Eskalationsrouting nach deutschem Recht."
---

# Vertragsrecht — Allgemein

## Worum geht es?

Dieses Plugin unterstuetzt Rechtsanwaelte und Unternehmensjuristen bei der Pruefung, Verhandlung und Verwaltung von Vertraegen nach deutschem Recht. Schwerpunkte sind Lieferanten- und Dienstleistervertraege, AGB-Kontrolle nach §§ 305 ff. BGB, Nichtoffenbarungsvereinbarungen (NDA), SaaS- und Rahmenvertraege sowie das Widerrufsrecht im Fernabsatz.

Das Plugin arbeitet mit einem Kanzlei-Playbook-Konzept: Einmal definierte Standards (Roter Bereich, Gelber Bereich, Gruenes Licht) werden bei jeder Vertragspruefung konsistent angewendet. Ergebnisse werden entweder als juristisches Memo oder als vereinfachte Stakeholder-Zusammenfassung ausgegeben.

## Wann brauchen Sie diese Skill?

- Die Rechtsabteilung erhaelt einen Lieferantenvertrag der Gegenseite und will ihn gegen das eigene Playbook pruefen.
- Ein Unternehmen will ein NDA auf kritische Klauseln (Geheimhaltungsumfang, Laufzeit, Rueckgabe) pruefen lassen.
- Ein SaaS-Anbieter oder -Kaeufer prueft einen Subscription Agreement auf AGB-Konformitaet und automatische Verlaengerungsklauseln.
- Eine UWG-Abmahnung ist eingegangen und muss beantwortet oder selbst verfasst werden.
- Ein Vertrag laeuft aus und die Kuendigungs- oder Verlaengerungsfrist ist knapp.

## Fachbegriffe (kurz erklaert)

- **AGB** — Allgemeine Geschaeftsbedingungen; vorformulierte Vertragsbedingungen unterliegen der Inhaltskontrolle nach §§ 307-309 BGB.
- **NDA** — Non-Disclosure Agreement (Nichtoffenbarungsvereinbarung); verpflichtet Parteien zur Geheimhaltung vertraulicher Informationen.
- **MSA** — Master Service Agreement; Rahmenvertrag fuer wiederkehrende Leistungsbeziehungen, ergaenzt durch spezifische Leistungsbeschreibungen.
- **Playbook** — Internes Regelwerk der Rechtsabteilung mit Mindestanforderungen und Roten Linien fuer Vertragsverhandlungen.
- **Eskalationsmatrix** — Festgelegte Zustaendigkeiten fuer die Genehmigung von Vertragsabweichungen nach Risikohoehe.
- **Fernabsatz** — Vertragsschluss ohne gleichzeitige Anwesenheit via Internet, Telefon oder Katalog; loest Widerrufsrecht nach § 312g BGB aus.
- **UWG** — Gesetz gegen den unlauteren Wettbewerb; regelt Abmahnungen bei wettbewerbswidrigen Handlungen.

## Rechtsgrundlagen

- §§ 305-310 BGB (AGB-Kontrolle)
- §§ 311-313 BGB (Schuldverhaeltnisse, culpa in contrahendo, Stoerung der Geschaeftsgrundlage)
- §§ 631 ff. BGB (Werkvertrag), §§ 611 ff. BGB (Dienstvertrag)
- §§ 312g, 355 BGB (Widerrufsrecht im Fernabsatz)
- § 13 UWG (Abmahnung im Wettbewerbsrecht)
- §§ 17-18 GeschGehG (Geschaeftsgeheimnisschutz, relevant fuer NDA)
- § 307 BGB (Generalklausel Inhaltskontrolle)

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Mandantenkonstellation klaeren: Vertragstyp, Vertragspartnerrolle (Lieferant, Auftraggeber, Lizenznehmer) und Rechtsabteilungs-Profil.
2. Kanzlei-Profil aufnehmen oder aktualisieren (`vertragsrecht-kaltstart-interview` oder `vertragsrecht-anpassen`).
3. Passenden Skill auswaehlen (z. B. NDA-Pruefung, Lieferantenvertrag, AGB, SaaS/MSA, Abmahnung).
4. Eilfristen pruefen: Kuendigungsfristen, Verlaengerungsfristen, Abmahn-Fristen.
5. Anschluss-Skill bestimmen: Gegenentwurf erstellen, Eskalation oder Stakeholder-Zusammenfassung?

## Skill-Tour (was gibt es hier?)

- `vertragsrecht-kaltstart-interview` — Erstgespraech zur Mandatsaufnahme im Vertragsrecht; Kanzlei- oder Mandatsprofil anlegen.
- `vertragsrecht-mandat-arbeitsbereich` — Mandatsarbeitsbereiche verwalten: neu anlegen, auflisten, wechseln oder abschliessen.
- `vertragsrecht-anpassen` — Kanzleiprofil im Vertragsrecht gezielt anpassen ohne erneutes Erstgespraech.
- `vertragspruefung` — Vertrag gegen das Kanzlei-Playbook nach deutschem Recht pruefen und Risikokategorien ausweisen.
- `lieferantenvertrag-pruefung` — Eingehenden Lieferanten- oder Dienstleistervertrag gegen das Playbook pruefen (Werk-/Dienstvertrag, Haftungscaps).
- `nda-pruefung` — Schnelle Triage eingehender NDA in Gruen/Gelb/Rot; nur auffaellige Vereinbarungen eskalieren.
- `nda-durchsetzer` — NDA der Gegenseite konservativ im Aenderungsmodus ueberarbeiten ohne Struktur zu veraendern.
- `agb-pruefung` — AGB auf Einbeziehung, Inhaltskontrolle nach §§ 305-310 BGB und unwirksame Klauseln pruefen.
- `saas-msa-pruefung` — SaaS-Abonnement- und Rahmenvertraege pruefen (AGB-Kontrolle, automatische Verlaengerung, Datenschutzklauseln).
- `abmahnung-uwg` — UWG-Abmahnung verfassen oder pruefen sowie modifizierte Unterlassungserklaerung entwerfen.
- `widerruf-fernabsatz` — Widerrufsrecht im Fernabsatz nach §§ 312g und 355 BGB pruefen; Belehrungspflichten und Fristberechnungen.
- `eskalations-marker` — Vertragsproblem dem richtigen Genehmiger per Eskalationsmatrix zuordnen und Genehmigungsanfrage erstellen.
- `stakeholder-zusammenfassung` — Vertragspruefungsmemo in eine Zusammenfassung fuer Geschaeftsfuehrung oder Einkauf uebersetzen.
- `aenderungs-historie` — Veraenderungen eines Vertrags ueber Basisvertrag und Nachtraege hinweg nachvollziehen.
- `vertragsverlaengerungs-monitor` — Vertraege mit ablaufenden Kuendigungsfristen anzeigen und rechtzeitig warnen.
- `pruefungsvorschlaege` — Ausstehende Playbook-Aktualisierungsvorschlaege pruefen und genehmigen oder ablehnen.

## Worauf besonders achten

- AGB-Kontrolle im B2B-Verkehr: § 307 BGB gilt auch zwischen Kaufleuten; marktunuebliche Haftungsausschluesse koennen unwirksam sein.
- Kuendigungsfristen in laufenden Vertraegen pruefen, bevor Verlaengerungsautomatik greift — besonders bei SaaS-Vertraegen.
- NDA-Laufzeiten: Zeitlich unbeschraenkte Geheimhaltungspflichten koennen nach deutschem Recht problematisch sein.
- Fernabsatz-Widerrufsrecht gilt auch im B2C-SaaS: 14 Tage Widerrufsfrist, Belehrungspflicht vor Vertragsschluss.
- Abmahnungen nach UWG haben kurze Reaktionsfristen — Unterlassungserklaerung nicht vorschnell unterzeichnen.

## Typische Fehler

- Haftungsklauseln in AGB ohne Differenzierung nach Verschuldensgrad: Totalausschluss ist nach § 309 Nr. 7 BGB unwirksam.
- NDA mit unklarem Schutzgegenstand: Was als vertraulich gilt, ist nicht hinreichend definiert — im Streitfall beweisbar schwach.
- SaaS-Vertraege ohne Datenrueckgabeklausel: Mandant verliert Zugang zu Daten nach Vertragsende.
- Verlaengerungsklausel uebersehen: Vertrag verlaengert sich automatisch um ein Jahr, weil Kuendigungsfenster verpasst wurde.
- Playbook nicht auf aktuellen Gesetzesstand gebracht: AGB-Aenderungen durch EuGH-Rechtsprechung oder BGH-Urteile werden nicht eingepflegt.

## Querverweise

- `datenschutzrecht` — Datenschutzklauseln in SaaS- und Lieferantenvertraegen (Art. 28 DSGVO, AVV).
- `corporate-kanzlei` — M&A-Vertraege (SPA, NDA, Disclosure) haben erweitertes Vertragsrecht-Profil.
- `geldwaeschepraevention-aml-kyc` — Vertraege mit Hochrisiko-Partnern benoetigen KYC-Pruefung.
- `regulatorisches-recht` — Regulierte Vertraege (DORA-IKT-Vertraege) haben Sonderanforderungen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum
- BGB in der zum Stand-Datum geltenden Fassung
- UWG in der geltenden Fassung

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
