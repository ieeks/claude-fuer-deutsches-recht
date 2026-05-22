---
name: triage-rechtsfrage-oder-norm
description: "Interaktiver Einstieg: Erfasst strukturiert, ob der Nutzer eine Rechtsfrage, einen Lebenssachverhalt, eine konkrete Norm oder eine Mischung davon hat. Stellt gezielte Rueckfragen und leitet zum passenden naechsten Skill weiter. Warnt vor typischen Eingabefehlern."
---

# Triage: Rechtsfrage oder Norm?

## Zweck

Dieser Skill ist der erste Schritt im Subsumtions-Workflow. Er stellt sicher, dass das System versteht, was der Nutzer mitgebracht hat: eine abstrakte Rechtsfrage, einen konkreten Lebenssachverhalt, eine benannte Norm oder eine Kombination davon. Erst nach dieser Erfassung kann sinnvoll subsumiert werden.

## Ablauf

**Schritt 1 — Eingabeerfassung**

Das System stellt folgende Eingangsfragen:

1. Was haben Sie konkret? Bitte wählen Sie:
   - (A) Ich habe einen konkreten Lebenssachverhalt (Ereignis, Streit, Vertrag, Handlung, Bescheid).
   - (B) Ich habe eine abstrakte Rechtsfrage (z. B. „Darf mein Arbeitgeber …?", „Ist es erlaubt …?").
   - (C) Ich weiß bereits, welche Norm ich prüfen will (z. B. „§ 823 Abs. 1 BGB" oder „Art. 6 Abs. 1 lit. f DSGVO").
   - (D) Ich habe beides: Sachverhalt und Norm.
   - (E) Ich weiß es nicht genau — bitte führe mich.

2. Falls (A) oder (D): Bitte schildern Sie den Sachverhalt in knappen Stichpunkten. Wer? Wann? Was ist passiert? Welche Dokumente gibt es?

3. Falls (B): Bitte formulieren Sie die Frage so präzise wie möglich.

4. Falls (C) oder (D): Welche Norm genau (Paragraph, Absatz, Satz, Nummer, Buchstabe)?

**Schritt 2 — Plausibilitätsprüfung**

Das System prüft:
- Ist die genannte Norm vollständig bezeichnet (mit Abs., Satz, Nr., Buchstabe)?
- Passt der Sachverhalt auf den ersten Blick zur genannten Norm?
- Gibt es offensichtliche Rechtsgebiets-Fehlzuordnungen (z. B. Sachverhalt klingt nach Strafrecht, Norm aus BGB)?

Das System korrigiert nicht eigenständig, sondern weist auf Auffälligkeiten hin und fragt nach.

**Schritt 3 — Routing**

Je nach Eingabetyp leitet das System zum nächsten Skill weiter:
- Nur Sachverhalt → `einschlaegige-normen-vorschlagen-de` oder `einschlaegige-normen-vorschlagen-eu`
- Norm bereits bekannt → `norm-zerlegen-in-tatbestandsmerkmale`
- Unklares Ziel → `ziel-und-rechtsweg-bestimmung`

## Wichtige Eingabe-Hinweise

- Das System akzeptiert keine „Muster-Sachverhalte" oder fiktive Testakte.
- Unvollständige Sachverhalte führen zu unvollständigen Ergebnissen — das System weist darauf hin.
- Bereits juristische Fachbegriffe im Sachverhalt werden als Nutzerangaben behandelt, nicht als gesicherte Rechtslage.

## Fehlereingaben

- Norm ohne Paragrafenzeichen: System ergänzt und bestätigt beim Nutzer.
- Sachverhalt zu allgemein: System stellt konkretisierende Rückfragen (Wer? Wann? Wo? Was?).
- Mehrere Normen gleichzeitig: System behandelt sie nacheinander und weist auf Konkurrenzfragen hin.

## Warnblock

**Warnung — Mechanische Prüfung, keine Rechtsberatung:**
Dieser Skill erfasst nur, was der Nutzer eingibt. Er kann nicht prüfen, ob die Sachverhaltsdarstellung vollständig, korrekt oder rechtlich erheblich ist. Er kann nicht prüfen, ob die gewählte Norm die richtige Rechtsgrundlage ist oder ob es eine speziellere oder vorrangige Regelung gibt. Das gesamte Ergebnis steht unter dem Vorbehalt, dass der Sachverhalt und die Norm vom Nutzer korrekt benannt worden sind.

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen und der vom Nutzer gewählten Norm. Falsche Normwahl oder falsche Sachverhaltsdarstellung kann das gesamte Ergebnis entwerten.
