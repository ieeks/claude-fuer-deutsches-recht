---
name: falsche-wiese-warnung-ki-vo
description: "Warnt vor typischen Rechtsgebiets-Verwechslungen: KI-VO versus DSGVO versus Produkthaftungsrichtlinie versus Medizinprodukteverordnung versus Maschinenverordnung versus Cyber Resilience Act. Gibt Orientierung welches Recht tatsaechlich einschlaegig ist."
---

# Warnung: Falsche Wiese — Verwechslung der Rechtsgebiete

## Zweck

Ein häufiger Fehler in der Praxis besteht darin, die KI-VO auf Sachverhalte anzuwenden, die tatsächlich von einem anderen Rechtsgebiet erfasst werden — oder umgekehrt: KI-spezifische Pflichten zu übersehen, weil der Nutzer glaubt, DSGVO-Konformität genüge. Dieser Skill klärt die Abgrenzung.

## Verwechslungsfall 1 — KI-VO versus DSGVO

**Häufiges Szenario:** Nutzer fragt nach Datenschutzpflichten beim Einsatz eines KI-Systems.

**Richtigstellung:**
- Die DSGVO (Verordnung (EU) 2016/679) regelt den Schutz personenbezogener Daten und gilt für jede Verarbeitung personenbezogener Daten, unabhängig davon, ob KI eingesetzt wird.
- Die KI-VO (Verordnung (EU) 2024/1689) regelt zusätzliche Anforderungen an KI-Systeme als solche: Risikoklassen, Konformitätsbewertung, Transparenzpflichten, menschliche Aufsicht.
- Beide Regelwerke können gleichzeitig gelten und ergänzen sich. DSGVO-Konformität ersetzt keine KI-VO-Konformität.
- Praktische Schnittstelle: Art. 27 KI-VO (Grundrechte-Folgenabschätzung für Betreiber) ist eng verzahnt mit Datenschutz-Folgenabschätzung nach Art. 35 DSGVO.

**Routing:** Wenn primär Datenschutzfragen bestehen → anderes Plugin (Datenschutzrecht). Wenn KI-spezifische Pflichten geprüft werden sollen → weiter in diesem Workflow.

## Verwechslungsfall 2 — KI-VO versus Produkthaftungsrichtlinie

**Häufiges Szenario:** Nutzer fragt nach Haftung für Schäden durch ein KI-System.

**Richtigstellung:**
- Die KI-VO ist keine Haftungsregelung. Sie begründet öffentlich-rechtliche Pflichten und Sanktionen, aber keine privatrechtlichen Schadensersatzansprüche.
- Die neue EU-Produkthaftungsrichtlinie (2024/2853) und die KI-Haftungsrichtlinie (Entwurf) betreffen Haftungsfragen. Diese sind vom KI-VO-Workflow zu trennen.
- Compliance mit der KI-VO kann jedoch haftungsmindernd wirken, wenn ein Verstoß zugleich eine Sorgfaltspflichtverletzung darstellt.

**Routing:** Haftungsfragen → Fachanwalt IT-Recht / Produkthaftung; KI-VO-Compliance → dieser Workflow.

## Verwechslungsfall 3 — KI-VO versus Medizinprodukteverordnung (MDR/IVDR)

**Häufiges Szenario:** KI-System in einem Medizinprodukt oder für Diagnose/Behandlung.

**Richtigstellung:**
- Die MDR (Verordnung (EU) 2017/745) und IVDR (Verordnung (EU) 2017/746) gelten für Medizinprodukte und In-vitro-Diagnostika.
- Ein KI-System, das in einem Medizinprodukt eingesetzt wird, kann gleichzeitig der MDR und der KI-VO unterliegen.
- Für KI-Systeme, die als Sicherheitsbauteil eines Medizinprodukts eingestuft werden, gilt Art. 6 Abs. 1 KI-VO i.V.m. Anhang I Nr. 1 KI-VO (MDR ist dort gelistet).
- Konformitätsbewertung nach MDR durch benannte Stelle kann teilweise auf KI-VO-Anforderungen angerechnet werden (Art. 43 Abs. 3 KI-VO).

**Routing:** Medizinprodukt-Konformität → Fachanwalt Medizinrecht; KI-VO-Schicht → weiter in diesem Workflow.

## Verwechslungsfall 4 — KI-VO versus Maschinenverordnung

**Häufiges Szenario:** KI-System in einer Maschine (Roboter, Produktionsanlage, Fahrzeug).

**Richtigstellung:**
- Die Maschinenverordnung (Verordnung (EU) 2023/1230) regelt die Sicherheit von Maschinen.
- KI-Systeme in Maschinen können gleichzeitig der KI-VO unterliegen, wenn sie Sicherheitsbauteile sind.
- Anhang I Nr. 7 KI-VO listet die Maschinenverordnung als relevanten Unionsrechtsakt; damit kann das KI-System als Hochrisiko nach Art. 6 Abs. 1 KI-VO einzustufen sein.

## Verwechslungsfall 5 — KI-VO versus Cyber Resilience Act

**Häufiges Szenario:** Nutzer fragt nach Cybersicherheitspflichten für KI-Produkte.

**Richtigstellung:**
- Der Cyber Resilience Act (Verordnung (EU) 2024/2847) regelt Cybersicherheitsanforderungen für Produkte mit digitalen Elementen.
- Für KI-Systeme, die unter den Cyber Resilience Act fallen, können beide Rechtsakte gleichzeitig gelten.
- Art. 15 KI-VO (Genauigkeit, Robustheit, Cybersicherheit für Hochrisiko-KI) greift unabhängig vom Cyber Resilience Act.

## Checkliste — Welches Recht gilt?

| Situation | Relevantes Recht |
|---|---|
| Datenschutzverletzung durch KI | DSGVO + ggf. KI-VO |
| Schaden durch KI-Fehler | Produkthaftung + ggf. KI-VO |
| KI in Medizinprodukt | MDR/IVDR + KI-VO |
| KI in Maschine/Roboter | Maschinenverordnung + KI-VO |
| KI-Produktsicherheit allgemein | Produktsicherheits-VO + KI-VO |
| KI-spezifische Risikopflichten | KI-VO primär |

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
