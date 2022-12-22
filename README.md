# LaTeX-Unterlagen
***

#### *In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.*
***

## Inhalt
Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.<br>
Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal anzusehen.

## PDF erstellen
Das geht ganz schnell und einfach:
* Zuerst installieren wir [LaTeX](tug.org/texlive/)
* Dann nutzen wir PDFLaTeX zum Erstellen des PDF[^1]
* Alternativ koennen wir auch einfach LaTeX Mk nutzen[^2]

[^1]: "pdflatex ./task.tex" (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
[^2]: "latexmk -pdf ./task.tex"

**!!ACHTUNG!!** <br>
LaTeX erstelle einige nervige Dateien (.aux, .log). Diese muss man loeschen bevor man einen Commit mit seinen Aenderungen macht!



