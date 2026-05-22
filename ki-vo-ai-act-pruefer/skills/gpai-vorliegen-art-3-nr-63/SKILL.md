---
name: gpai-vorliegen-art-3-nr-63
description: "Prueft ob ein GPAI-Modell im Sinne von Art. 3 Nr. 63 KI-VO vorliegt: Training auf grosser Datenmenge selbstueberwachtes Lernen allgemeine Aufgabenerfuellung. Abgrenzung vom GPAI-System Art. 3 Nr. 66 KI-VO. Sonderstatus Foundation-Modelle."
---

# Liegt ein GPAI-Modell vor? — Art. 3 Nr. 63 KI-VO

## Zweck

GPAI-Modelle (General-Purpose-KI-Modelle) unterliegen einem eigenen Pflichtenkatalog nach Art. 51 bis 55 KI-VO, der seit dem 2. August 2025 anwendbar ist. Dieser Skill klärt, wann ein GPAI-Modell vorliegt und wie es vom GPAI-System abzugrenzen ist.

## Legaldefinition — Art. 3 Nr. 63 KI-VO

Ein GPAI-Modell ist ein KI-Modell, das Folgendes aufweist:
- Es wird mit großen Datenmengen unter Verwendung von selbstüberwachtem oder unüberwachtem Lernen in großem Maßstab trainiert
- Es ist so konzipiert, dass es für eine allgemeine Ausgabe ausreichend generalisiert ist
- Es kann eine Vielzahl unterschiedlicher Aufgaben kompetent ausführen
- Es kann in eine Vielzahl nachgelagerter Systeme oder Anwendungen integriert werden

## Tatbestandsmerkmale — Checkliste

### Merkmal 1 — Großskaliges Training auf großen Datenmengen

**Prüffragen:**
- Wurde das Modell auf einer sehr großen Datenmenge trainiert (in der Größenordnung von Milliarden von Parametern, Terabytes an Trainingsdaten)?
- War das Training ressourcenintensiv (erhebliche Rechenleistung, nicht auf einem einzelnen Server in kurzer Zeit)?

### Merkmal 2 — Selbstüberwachtes oder unüberwachtes Lernen

**Prüffragen:**
- Wurde das Modell ohne vollständig manuelle Annotation aller Trainingsdaten trainiert?
- Wurden Methoden wie Self-Supervised Learning, Pretraining auf Rohdaten (Text, Bilder, Code) oder ähnliche Verfahren eingesetzt?

**Hinweis:** Auch Modelle, die zuerst self-supervised vortrainiert und dann mit überwachtem Lernen feinabgestimmt wurden (Fine-Tuning, RLHF), fallen unter die GPAI-Definition, wenn das Vortraining die wesentliche Grundlage bildet.

### Merkmal 3 — Allgemeine Aufgabenerfüllung (Generalisierung)

**Prüffragen:**
- Kann das Modell kompetent eine breite Palette verschiedener Aufgaben erfüllen, ohne für jede Aufgabe separat trainiert worden zu sein?
- Ist das Modell nicht ausschließlich auf eine sehr spezifische Aufgabe ausgerichtet?

**Abgrenzung:** Ein Modell, das ausschließlich auf eine eng definierte Aufgabe (z.B. Bildklassifikation in einer Produktkategorie) spezialisiert wurde und keine Generalisierung über verschiedene Domänen hinweg zeigt, ist in der Regel kein GPAI-Modell.

### Merkmal 4 — Integrierbarkeit in nachgelagerte Systeme

**Prüffragen:**
- Kann das Modell als Grundlage (Foundation) für verschiedene nachgelagerte Anwendungen verwendet werden?
- Bieten Sie das Modell über eine API oder als Infrastruktur anderen Entwicklern an?

## Typische GPAI-Modell-Kategorien (nicht abschließend)

- Große Sprachmodelle (Large Language Models) mit breiten Fähigkeiten
- Multimodale Modelle (Text + Bild, Text + Audio, Text + Code)
- Foundation-Modelle für Bildgenerierung und -analyse
- Code-Generierungsmodelle mit breitem Sprachspektrum

## Abgrenzung: GPAI-Modell versus GPAI-System

**GPAI-Modell (Art. 3 Nr. 63 KI-VO):** Das Modell selbst — die trainierten Gewichte, die Architektur, das Ergebnis des Trainingsprozesses. Anbieter eines GPAI-Modells sind in der Regel Unternehmen, die das Training durchgeführt haben und das Modell anderen zur Nutzung bereitstellen.

**GPAI-System (Art. 3 Nr. 66 KI-VO):** Ein KI-System, das auf einem GPAI-Modell basiert und für eine Vielzahl von Zwecken eingesetzt werden kann, einschließlich wenn es direkt mit dem Nutzer interagiert oder einen Inhalt erstellt. Anbieter eines GPAI-Systems sind Unternehmen, die das Modell in einer Anwendung (Chatbot, Zusammenfassungstool, Codierungshilfe) bereitstellen.

**Praktische Konsequenz:** Wer nur ein auf dem GPAI-Modell basierendes GPAI-System betreibt, ohne selbst das Modell entwickelt zu haben, ist Betreiber. Die GPAI-Modell-Pflichten nach Art. 51 bis 55 KI-VO treffen primär den Modellanbieter.

## Ergebnis und Routing

- **GPAI-Modell bestätigt:** → Pflichten nach Art. 51 bis 55 KI-VO → `gpai-modelle-art-51-bis-55`
- **GPAI-Modell mit systemischem Risiko (über 10e25 FLOP oder Kommissionsbeschluss):** → Zusätzliche Pflichten → `gpai-systemisches-risiko-schwelle-10e25-flop`
- **Kein GPAI-Modell, aber KI-System:** → Risikoklassen-Triage → `risikoklassen-uebersicht-und-triage`

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
