Wie Benutzt Man Diese Vorlage?
==========================

1. Entsprechende Änderungen in main.tex vornehmen
Es geht hier um Titel, Autor, usw. und dito für die 
ehrenwörtliche Erklärung

2. Im Verzeichnis ./images kannst Du Deine Abbildungen abspeichern

3. Schreibe Deine Kapitel im Verzeichnis ./content/chapter 
und gebe sie Nummer als Namen: 01.tex usw.

4. Schreibe Deine Zusammenfassung in Datei ./content/abstract.tex

5. Arbeite dito in acronyms.tex, glossary.tex und appendix.tex

Wenn Du ein sauberes, aktuelles PDF mit korrekten Literaturverweisen
und intertextuelle Verweisen generieren möchtest, dann gehe wie folgt vor:
1. Führe "pdfLatex" aus auf Datei main.tex
2. Führe "biber" aus auf Datei main.tex
3. Führe nochmal "pdfLatex aus auf Datei main.tex


An dieser Stelle noch den Hinweis, dass eine bessere, aber auch etwas komplexere, 
Fassung dieser Vorlage downloadbar ist unter:
	 https://github.com/schnes4/dhbw-heidenheim-latex-template
	 
Viel Erfolg!
