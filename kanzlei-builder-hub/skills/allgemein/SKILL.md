---
name: allgemein
description: "Einstieg und Überblick für den Kanzlei-Builder-Hub: findet, prüft und installiert Community-Skills mit Security-Review-Gate, verwaltet installierte Skills und Plugins, aktualisiert automatisch, erstellt kanzleieigene Playbooks und unterstuetzt bei Konfiguration und Qualitaetsprüfung der KI-Kanzleiumgebung."
---

# Kanzlei-Builder-Hub — Allgemein

## Worum geht es?

Der Kanzlei-Builder-Hub ist die Steuerzentrale fuer Installation, Verwaltung und Qualitaetssicherung von Skills und Plugins in der KI-gestuetzten Kanzleiumgebung. Er fuehrt vor dem Deployment ein Security-Review-Gate durch, das Community-Skills auf Sicherheit, Normkonformitaet und Qualitaet prueft, bevor sie produktiv genutzt werden.

Der Hub ermoeglicht ausserdem die Erstellung kanzleieigener Playbooks aus vorhandenen Musterdokumenten sowie die gezielte Suche und Verwaltung des Skill-Verzeichnisses. Er richtet sich an Kanzleiinhaber, IT-Verantwortliche und Kanzleimanager, die ihre KI-Kanzleiumgebung strukturiert aufbauen und pflegen wollen.

## Wann brauchen Sie diese Skill?

- Sie wollen erstmals den Hub einrichten und Ihr Kanzleiprofil mit Rechtsgebieten und Technikvoraussetzungen erfassen.
- Sie suchen neue Community-Skills fuer ein bestimmtes Rechtsgebiet und moechten diese vor dem Einsatz sicherheitsprufen.
- Ein installierter Skill soll aktualisiert, temporaer deaktiviert oder vollstaendig deinstalliert werden.
- Sie wollen aus Ihren eigenen Musterdokumenten ein kanzleispezifisches Playbook generieren.
- Sie benoetigen eine Qualitaetspruefung aller installierten Skills auf Normaktualitaet und Strukturkonformitaet.

## Fachbegriffe (kurz erklaert)

- **Security-Review-Gate** — Strukturiertes Pruefverfahren, das vor der Freigabe eines Community-Skills Sicherheit, Normverankerung und Qualitaet bewertet.
- **Plugin** — Zusammenschluss mehrerer thematisch verwandter Skills zu einem Funktionspaket fuer ein Rechtsgebiet oder einen Workflow.
- **Skill** — Einzelne spezialisierte Anleitung in einer SKILL.md-Datei, die einen definierten Arbeitsschritt abdeckt.
- **Playbook** — Kanzleispezifischer Pruef- und Arbeitskatalog, der aus eigenen Musterdokumenten automatisch erstellt wird.
- **Kaltstart-Interview** — Strukturiertes Erstgespraech zur Erfassung von Kanzleiprofil, Rechtsgebieten und Konfigurationsparametern.
- **Fundstelle** — Normzitat oder Rechtsprechungsnachweis; der Hub prueft deren einheitliche Zitierweise.

## Rechtsgrundlagen

- § 43a BRAO — Allgemeine Berufspflichten des Rechtsanwalts (Sorgfalt, Verschwiegenheit)
- § 43e BRAO — Dienstleister-Regelung: Berufsrechtliche Anforderungen an IT-Dienstleister der Kanzlei
- Art. 28 DSGVO — Auftragsverarbeitungsvertrag bei externen Dienstleistern
- Art. 32 DSGVO — Technische und organisatorische Massnahmen

## Schritt-fuer-Schritt: Einstieg ins Plugin

1. Kanzleiprofil und Rechtsgebiete im Kaltstart-Interview erfassen.
2. Gewuenschte Skills oder Plugins im Verzeichnis suchen.
3. Security-Review-Gate vor Installation durchlaufen lassen.
4. Skill installieren und Abhaengigkeiten pruefen.
5. Qualitaetspruefung nach Installation; bei Bedarf anpassen oder deaktivieren.

## Skill-Tour (was gibt es hier?)

- `automatischer-aktualisierer` — Plugins und Skills automatisch auf neue Norm-Versionen und Rechtsprechungsaenderungen aktualisieren.
- `deaktivieren` — Einzelne Skills oder Plugins temporaer deaktivieren ohne vollstaendige Deinstallation.
- `deinstallieren` — Plugins oder Skills vollstaendig deinstallieren mit Abhaengigkeitspruefung und Datensicherung.
- `fundstellenglattzieher` — Normen- und Rechtsprechungszitate in Schriftsaetzen und Skills auf einheitliche Zitierweise bringen.
- `kanzlei-builder-hub-anpassen` — Hub an kanzleispezifische Anforderungen anpassen: eigene Plugins, Branding, Workflows.
- `kanzlei-builder-hub-kaltstart-interview` — Kaltstart-Interview: Kanzleiprofil, Rechtsgebiete und gewuenschte Plugins erfassen.
- `playbook-aus-eigenen-daten` — Kanzleieigenes Playbook aus vorhandenen Musterdokumenten automatisch generieren.
- `skill-installierer` — Neue Skills installieren mit Verfuegbarkeitscheck, Abhaengigkeitspruefung und Konfiguration.
- `skill-verwalter` — Uebersicht und Verwaltung aller installierten Skills nach Status, Version und Abhaengigkeiten.
- `skills-qualitaetspruefung` — Installierte Skills auf Normaktualitaet, Description-Qualitaet und Strukturkonformitaet pruefen.
- `verwandte-skills-vorschlag` — Verwandte Skills zu einem Mandat oder Rechtsproblem als Ergaenzungsempfehlung vorschlagen.
- `verzeichnis-durchsuchen` — Skill-Verzeichnis nach Rechtsgebiet, Norm oder Mandantentyp durchsuchen.

## Worauf besonders achten

- **Security-Review-Gate zwingend**: Community-Skills ohne Pruefung koennen falsche Normen, erfundene Aktenzeichen oder datenschutzrechtliche Schwachstellen enthalten.
- **Abhaengigkeitspruefung vor Deinstallation**: Andere Skills oder Workflows koennen auf dem zu entfernenden Skill aufbauen.
- **Normaktualitaet regelmaessig pruefen**: Gesetze und Rechtsprechung aendern sich; veraltete Skills sind ein Haftungsrisiko.
- **Datensicherung vor Deinstallation**: Kanzleieigene Anpassungen gehen bei Deinstallation ohne Sicherung unwiederbringlich verloren.
- **Kaltstart nicht ueberspringen**: Ohne vollstaendiges Kanzleiprofil sind Rechtsgebiet-Filter und Kompatibilitaetspruefungen unzuverlaessig.

## Typische Fehler

- Community-Skills ohne Security-Review direkt in die Produktion uebernehmen.
- Bei der Deinstallation nicht auf abhaengige Workflows pruefen, was zu Folgefehlern fuehrt.
- Kanzleiprofil nach Rechtsgebietswechsel nicht aktualisieren, sodass Skill-Vorschlaege nicht mehr passen.
- Fundstellen verschiedener Zitierweisen im selben Schriftsatz mischen (z. B. BGH-Aktenzeichen ohne einheitliches Format).
- Qualitaetspruefung nur bei Neuinstallation, nicht nach Gesetzesaenderungen durchfuehren.

## Querverweise

- `kanzlei-allgemein` — Zentrales Kanzlei-Workflow-Plugin, das vom Hub mit Skills bestuckt wird.
- `berufsrecht-ki-vertragspruefung` — Berufsrechtliche Pruefung von KI-Anbietervertraegen vor der Installation.
- `ki-richtlinie-kanzleien` — KI-Nutzungsrichtlinie als Rahmen fuer alle installierten KI-Skills.
- `rechtsberatungsstelle` — Skill-Verwaltung fuer studentische Beratungsstellen.

## Quellen und Aktualitaet

- Stand: 05/2026
- Gesetzesfassungen zum Stand-Datum

<!-- AUDIT 27.05.2026 | welle 5a | neuer allgemein-Skill (Pattern: selbstvertreter-orientierung) -->
