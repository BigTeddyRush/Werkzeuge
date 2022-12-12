# LaTeX-Unterlagen
***

#### *In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.*

***

Diese Aufgabe befasst sich mit der Implementation der Klasse DataSet.
DataSet ist eine Spezifikation der abstrakten Klasse DataSetInterface und dient der Verwaltung mehrerer DataSetItems.
Insbesondere befasst sich diese Aufgabe mit Magic Methods.


PDF erstellen
<----------->

Das geht ganz schnell und einfach:

-> Zuerst installieren wir LaTeX (tug.org/texlive/)
-> Dann nutzen wir PDFLaTeX zum Erstellen des PDF
	"pdflatex ./task.tex" (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
-> Alternativ koennen wir auch einfach LaTeX Mk nutzen 
	"latexmk -pdf ./task.tex"


!!ACHTUNG!!

LaTeX erstelle einige nervige Dateien (.aux, .log) diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!
