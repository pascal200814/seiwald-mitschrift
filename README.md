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
Daraufhin führt das CLI durch die Installation. Falls bei der Installation sogeannte "build scripts` nicht ausgeführt werden können, schkägt die CLI die Fehlerbehandlung selbstständig vor:

1. Wechsel in das Installationsverzeichnis (mit `cd my-strapi-project`).
2. Neuerlicher Versuch der Installation mit `pnpm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve-builds` manuell freigegeben werden.
