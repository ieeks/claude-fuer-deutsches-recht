---
name: abgrenzung-konventionelle-software-vs-ki-system
description: "Prueft typische Falschverortungen: wann liegt konventionelle Software vor und wann ein KI-System nach Art. 3 Nr. 1 KI-VO. Abgrenzung zu Expertensystemen deterministischer Logik einfachen Entscheidungsbaeumen und klassischer Automation. Hilft bei Grenzfaellen."
---

# Abgrenzung: Konventionelle Software versus KI-System

## Zweck

Viele Nutzer ordnen ihre Systeme fälschlich als KI-Systeme ein — oder umgekehrt: Sie übersehen, dass eine Komponente ihres Systems die Schwelle zum KI-System überschreitet. Dieser Skill klärt typische Grenzfälle und liefert eine systematische Abgrenzungsmatrix.

## Warum die Abgrenzung entscheidend ist

Wird ein System irrtümlich als KI-System eingestuft, entstehen unnötige Compliance-Lasten. Wird ein KI-System irrtümlich als konventionelle Software behandelt, drohen erhebliche Bußgelder nach Art. 99 bis 101 KI-VO.

## Abgrenzungsmatrix

### Konventionelle Software — in der Regel KEIN KI-System

| Systemtyp | Merkmal | Ergebnis |
|---|---|---|
| Steuerrechner | Deterministisch, keine Inferenz | Kein KI-System |
| Datenbankabfrage (SQL) | Suche, Filterung, keine Vorhersage | Kein KI-System |
| Makro / Skript | Regelbasiert, keine Lernkomponente | Kein KI-System |
| Klassischer Entscheidungsbaum (hartcodiert) | Vollständig manuell definierte Regeln | Kein KI-System |
| Expertensystem ohne maschinelles Lernen | Manuelle Wissensbasis, keine Inferenz aus Daten | Kein KI-System |
| Suchmaschine (reine Indexabfrage) | Kein maschinelles Lernen, reine Volltextsuche | Kein KI-System |

### Grenzfälle — je nach Implementierung

| Systemtyp | Entscheidend | Hinweis |
|---|---|---|
| Recommendation Engine | Inferiert sie Präferenzen aus Nutzungsmustern? | Meist KI-System |
| Fraud-Detection | Regelbasiert ODER Anomalieerkennung per Modell? | Modellbasiert = KI-System |
| Chatbot | Regelbasiert (Skript) ODER KI-Sprachsystem? | KI-Sprachsystem-basiert = KI-System |
| Bildverarbeitung | Hardcodierte Filter ODER neuronales Netz? | Neuronales Netz = KI-System |
| Kreditscoring | Lineare Formel ODER Gradientenverfahren? | Lernbasiert = KI-System |
| Anomalieerkennung | Schwellenwert ODER Clusteringmodell? | Clusteringmodell = KI-System |

### Eindeutige KI-Systeme

| Systemtyp | Grund |
|---|---|
| Neuronale Netze (CNN, RNN, Transformer) | Inferenz, maschinelles Lernen |
| Generative Modelle (Text, Bild, Audio, Code) | Inferenz aus Trainingsdaten |
| Reinforcement-Learning-Systeme | Autonomes Lernen durch Feedback |
| Klassifikatoren (SVM, Random Forest, XGBoost) | Inferenz aus Trainingsdaten |
| Regressionsmodelle mit Vorhersagezweck | Vorhersage-Ausgabe |
| Clustering-Systeme mit Entscheidungsfolge | Ableitung von Kategorien |

## Typische Falschverortungen

**Falsch 1 — „Unser Chatbot ist nur ein FAQ-Bot"**
Wenn der Chatbot auf ein neuronales Netz (z.B. ein vortrainiertes Textgenerationssystem) zurückgreift, selbst wenn nur intern genutzt, liegt ein KI-System vor. Ausnahme: rein skriptbasierte Button-Chatbots ohne Inferenzkomponente.

**Falsch 2 — „Das ist nur eine Suchfunktion"**
Sobald personalisierte Suchergebnisse oder Empfehlungen durch ein Lernmodell generiert werden, ist die KI-VO-Schwelle in der Regel überschritten.

**Falsch 3 — „Das System lernt nicht mehr — es wurde einmal trainiert"**
Die Anpassungsfähigkeit ist ein optionales Merkmal (Art. 3 Nr. 1 KI-VO sagt „kann anpassungsfähig sein"). Ein einmal trainiertes und nun fest eingesetztes Modell ist trotzdem ein KI-System.

**Falsch 4 — „Wir nutzen nur eine externe API"**
Die Nutzung eines fremden KI-Systems als Betreiber begründet eigene Pflichten nach Art. 26 KI-VO. Die eigene Softwarearchitektur darum herum ist dabei unerheblich — das fremde KI-System bleibt ein KI-System.

**Falsch 5 — „Wir haben die Regeln selbst definiert"**
Wenn die Regeln nicht vollständig hardcodiert sind, sondern das System Parameter aus Daten lernt, liegt in der Regel ein KI-System vor — auch wenn der Entwickler die Architektur selbst entworfen hat.

## Rückfragen zur Klärung

Wenn der Nutzer unsicher ist, stellt das System folgende Klärungsfragen:
1. Wurden Trainingsdaten verwendet? (Wenn ja → starkes Indiz für KI-System)
2. Gibt es Gewichte, Parameter oder Schwellenwerte, die durch Daten ermittelt wurden und nicht manuell festgelegt wurden? (Wenn ja → KI-System)
3. Würde das System bei denselben Eingaben immer exakt dieselbe Ausgabe liefern, völlig ohne Zufallskomponente und ohne Kontextanpassung? (Wenn ja → möglicherweise konventionelle Software)
4. Verwendet das System eine externe KI-API oder ein vortrainiertes Modell als Baustein? (Wenn ja → KI-System-Komponente vorhanden)

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Die KI-VO ist in Auslegung und Konkretisierung dynamisch; Leitlinien der Kommission und Durchführungsrechtsakte sind laufend zu beobachten.
