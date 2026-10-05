# seiwald-mitschrift

Das ist die README.md-Datei. MD steht für markdown. Markdown ist eine heutzutage weit verbreitete Auszeichungssprache (_Markup Language_, [Wikipedia](https://de.wikipedia.org/wiki/Auszeichnungssprache)).

Weitere bekannte AUszeichungssprachen sind:

- Hypertxt Markup Language (HTML)
- Extensible Markup Language (XML)
- Yet Another Markup Language (YAML, YML)

## Installation von Node.js

Javascript läuft unter normalen Umständen in einer Browser Sandbox (nur im Browser).
Seit ca. 2010 gibt es eine Laufzeitumgebung (_Runtime Environment_) für JS, damit man auch Serverseitg JS programmieren und ausführen kann: [Node.js] (https://nodejs.org/).

## Installation von pnpm

Der Standardmäßige _Package Manager_ für Node.js ist `npm` (_node package Manager_). Eine etwas modernere und inzwischen beliebtere Variante ist [`pnpm`] (https://pnpm.io/).

Eine Path-Variable ist eine Umgebungsvariable, die dem Betriebssystem mitteilt, wo es ausführbare Dateien finden kann. Wenn du `pnpm` installierst, wird es normalerweise automatisch zu deiner Path-Variable hinzugefügt, damit du es von überall in der Kommandozeile ausführen kannst.

##

var benutzt man nicht mehr
let x = 3;

let y = 4.2;

let x: number = 3;

int x = 3;

double y = 4.2;

## Installation von strapi

Installation mit dem Script `pnpm create strapi`.
Daraufhin führt das CLI (_Command Line Interface_) durch die Installation. Falls bei der Installation sogeannte "build scripts` nicht ausgeführt werden können, schlägt die CLI die Fehlerbehandlung selbstständig vor:

1. Wechsel in das Installationsverzeichnis (mit `cd my-strapi-project`).
2. Neuerlicher Versuch der Installation mit `pnpm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve-builds` manuell freigegeben werden.

# VibeCoding / AgenticEngineering mit VS-Code und Github Copilot

Vibecoding passiert in VS-Code in erster Linie über die neu eingeführte Agent View.
Dort können alle Anpassungen des "_Coding Harness_" vorgenommen werden. Wir können unseren Harness mit verscheidenen Methoden anpassen:

- **MCP-Server**:
  MCP steht für _Model Context Protocoll_. Es ist ein Standard der von Anthropic entwickelt wurde. Mithilfe von MCP können Chatbots/LLMs (_Large Language Models_) auf zusätzliche Tools zugreifen, die sie zu Experten in einem bestimmten Themenbreiech machen.

---

## Javascript-Frontendentwicklung mit Frameworks (Svelte, React, Vue, Angular)

Frontend-Entwicklung basiert auf Komponenten.

## DOM

DOM = Document Object Model
DOM ist quasi das html.

JS => Daten + Funktionen

Template(Vorlage) <> HTML

<ul>
{for item in List}
<li>{item}</li>
</ul>

## Runes

$state(): für Reactivity, dass die Variablen automatisch aktualisiert werden, wenn sich ihr Wert ändert.
$derived(): für abgeleitete Werte
$effect(): Konstruktor für ein ".svelte"-file (SFC = Single File Component)

## UI, GUI und CLI

- UI (User Interface): Allgemeiner Begriff für die Schnittstelle, über die ein Benutzer mit einem System interagiert.
- GUI (Graphical User Interface): Benutzeroberfläche mit grafischen Elementen wie Buttons, Fenstern und Icons.
- CLI (Command Line Interface): Benutzeroberfläche, die über Texteingaben in der Kommandozeile bedient wird.

## Komponenten

Komponenten sind die Bausteine der Website. Diese sind html, Javascript und CSS.

## aria

ARIA (Accessible Rich Internet Applications) ist eine Sammlung von Attributen, die HTML-Elementen hinzugefügt werden, um die Zugänglichkeit für Benutzer mit Behinderungen zu verbessern. Beispiele sind `aria-label`, `aria-hidden` und `aria-expanded`.
