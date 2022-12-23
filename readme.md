# LaTeX-Unterlagen

>In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.

## Inhalt
Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.
Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal anzusehen

## PDF erstellen
Das geht ganz schnell und einfach:

&rarr; Zuerst installieren wir [LaTeX](tug.org/texlive/)<br />
&rarr; Dann nutzen wir PDFLaTeX zum Erstellen des PDF 
&emsp;&ensp;**pdflatex ./task.tex** (Das muessen wir mehrfach machen, &emsp;&ensp;damit die PDF auch fertig wird)
<br />&rarr; Alternativ koennen wir auch einfach LaTeX Mk nutzen 
	&emsp;&ensp;**latexmk -pdf ./task.tex**



:warning::warning:ACHTUNG:warning::warning:

LaTeX erstelle einige nervige Dateien (.aux, .log) diese muss man loeschen bevor man einen Commit mit seinen Aenderungen macht!
