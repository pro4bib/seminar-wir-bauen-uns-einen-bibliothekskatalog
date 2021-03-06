# 7.4 Transformationen anwenden

## Aufgabe: Speichern Sie die bisher durchgeführten Transformationsregeln und wenden Sie diese auf eine andere MARCXML-Datei an

OpenRefine verfügt über hilfreiche Undo/Redo-Funktionen, mit denen Sie auch alle bisher in einem Projekt durchgeführten Transformationsregeln speichern und auf ein anderes Projekt anwenden können.

Hinweise:

* Nutzen Sie die Funktion "Extract" im Bereich Undo/Redo und speichern Sie die Regeln in einer Textdatei zwischen (z.B. mit Windows Editor).
* Wenden Sie diese anschließend über die Funktion "Apply" in einem neuen Projekt an (z.B. per copy & paste)

## Lösung

Transformationsregeln extrahieren (altes Projekt):

* {%s%}Oben links Menü Undo / Redo den Button Extract... drücken{%ends%}
* {%s%}Alles im rechten Textfeld in die Zwischenablage kopieren (z.B. mit STRG+A und STRG+C){%ends%}

Transformationsregeln anwenden (neues Projekt):

* Neues Projekt erstellen wie in [Kapitel 6.3 Aufgabe 2](https://felixlohmeier.gitbooks.io/seminar-wir-bauen-uns-einen-bibliothekskatalog/content/06_3_openrefine_starten_und_daten_laden.html) beschrieben
* {%s%}Oben links Menü Undo / Redo den Button Apply... drücken{%ends%}
* {%s%}Den Inhalt der Zwischenablage einfügen (z.B. mit STRG+V) und den Button Perform Operations drücken.{%ends%}

## Literatur

* [History-Funktionen in OpenRefine Dokumentation](https://github.com/OpenRefine/OpenRefine/wiki/History)
* [JSON and my notepad or how to write script in google refine](http://kb.refinepro.com/2012/06/google-refine-json-and-my-notepad-or.html)
