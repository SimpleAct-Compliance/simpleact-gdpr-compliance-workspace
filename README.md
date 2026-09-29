# DSGVO-Arbeitsbereich: das Gerüst, auf dem alles andere steht

**Wer sein Verarbeitungsverzeichnis nicht kennt, kann weder löschen noch Auskunft geben noch eine Folgenabschätzung abgrenzen.** Dieses Repository beschreibt die drei Grundlagen, auf die jede weitere Datenschutzpflicht zurückgreift — und die deshalb zuerst stehen müssen.

*The three foundations every other GDPR duty depends on: the record of processing activities, the lawful basis, and the handling of data subject requests.*

---

## Warum diese drei

Die meisten Datenschutzprojekte scheitern nicht an einer schwierigen Rechtsfrage, sondern daran, dass eine banale Grundlage fehlt. Drei Beispiele aus der Praxis:

- Eine Auskunftsanfrage geht ein. Niemand weiß, in welchen Systemen die Person vorkommt — **weil das Verarbeitungsverzeichnis Systeme nicht nennt.**
- Ein Widerspruch geht ein. Niemand kann sagen, ob die Verarbeitung auf berechtigtem Interesse beruht — **weil die Rechtsgrundlage nie einzeln festgelegt wurde.**
- Eine Löschfrist läuft ab. Niemand löscht, **weil der Zweck nie so beschrieben wurde, dass sein Ende erkennbar wäre.**

Alle drei Fehler entstehen an derselben Stelle: bei der Bestandsaufnahme. Sie zeigen sich erst Monate später, unter Zeitdruck, gegenüber jemandem, der eine Frist gesetzt hat.

## Die drei Grundlagen

| Grundlage | Norm | Was sie leistet |
|---|---|---|
| **Verarbeitungsverzeichnis** | Art. 30 | Sagt, was überhaupt verarbeitet wird — die Landkarte für alles Weitere |
| **Rechtsgrundlage je Verarbeitung** | Art. 6, Art. 9 | Entscheidet, welche Betroffenenrechte greifen und ob eine Verarbeitung überhaupt zulässig ist |
| **Verfahren für Betroffenenrechte** | Art. 12–22 | Der Belastungstest: Hier zeigt sich innerhalb eines Monats, ob die ersten beiden stimmen |

Die Reihenfolge ist keine Geschmacksfrage. Die dritte Grundlage lässt sich ohne die ersten beiden nicht erfüllen, und die zweite nicht ohne die erste.

## Der eine Satz, der die meiste Arbeit spart

**Eine Verarbeitungstätigkeit ist nicht dasselbe wie ein System.**

Ein CRM ist kein Eintrag im Verzeichnis, sondern ein Ort, an dem mehrere Verarbeitungstätigkeiten stattfinden — Kundenbetreuung, Vertragsabwicklung, Direktwerbung. Sie haben unterschiedliche Zwecke, unterschiedliche Rechtsgrundlagen und unterschiedliche Löschfristen. Wer sie zu einem Eintrag „CRM" zusammenzieht, kann später keine davon einzeln beantworten.

Umgekehrt gilt dasselbe: Eine Verarbeitungstätigkeit liegt oft in mehreren Systemen. Deshalb gehört die Systemliste in den Eintrag hinein, auch wenn Art. 30 sie nicht ausdrücklich verlangt — ohne sie ist keine Auskunft und keine Löschung durchführbar.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Das Verarbeitungsverzeichnis](./knowledge-base/verarbeitungsverzeichnis.md) | Pflichtinhalte, Zuschnitt der Einträge, die Ausnahme für kleine Unternehmen und warum sie meist nicht greift |
| [Rechtsgrundlagen](./knowledge-base/rechtsgrundlagen.md) | Die sechs Tatbestände des Art. 6, besondere Kategorien nach Art. 9, die Abwägung beim berechtigten Interesse |
| [Betroffenenrechte](./knowledge-base/betroffenenrechte.md) | Fristen, Identitätsprüfung, was Auskunft umfasst, die Grenzen von Löschung und Widerspruch |
| [Vorlage: Verarbeitungstätigkeit](./templates/verarbeitungstaetigkeit.md) | Ein Eintrag nach Art. 30 Abs. 1 |
| [Vorlage: Betroffenenanfrage](./templates/betroffenenanfrage.md) | Bearbeitungsbogen mit Fristenuhr |

## Verhältnis zum AI Act

Der AI Act ersetzt die DSGVO nicht, er kommt hinzu. Ein KI-System, das personenbezogene Daten verarbeitet, braucht beides: einen Eintrag im Verarbeitungsverzeichnis **und** einen im KI-Inventar. Die beiden Register beantworten verschiedene Fragen und lassen sich nicht ineinander überführen — aber sie sollten aufeinander verweisen.

Wo genau die Verzahnung liegt, steht im [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) und im [DSFA-Workflow](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow).

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt Verarbeitungsverzeichnis, KI-Inventar, Löschkonzept und Betroffenenanfragen verknüpft in einem System: **[simpleact.de](https://simpleact.de)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-09-29 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
