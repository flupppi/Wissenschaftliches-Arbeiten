-----------------------------------------------------------------------------------------------------
# Beamer-Präsentationsvorlage für den Fachbereich Informatik der Hochschule Trier im Hochschulstil. #
#                                      Version 1.0 - 28.4.2017                                      #
-----------------------------------------------------------------------------------------------------

Diese Präsentationsvorlage verwendet das LaTeX-Paket Beamer, um Features bereitzustellen, die häufig 
in Präsentationen verwendet werden (z.B. Animationsschritte).

Aufgrund der für die Titelzeile verwendeten Layout-Mechanismen, muss das Dokument mindestens zwei mal 
mit dem LaTeX-Compiler verarbeitet werden, um ein korrektes Layout zu erhalten. Dies ist dadurch 
begründet, dass beim ersten Lauf Informationen gesammelt werden, die beim zweiten Lauf benötigt 
werden, um die Titelzeile zu layouten. Bitte stellen Sie ihren LaTeX-Editor entsprechend ein, oder 
führen Sie die Kompilierung mehrfach aus. In der Regel ist dies für die meisten LaTeX-Dokumente 
sowieso nötig, da Referenzen und Literatur-Verweise auch mehrere Durchläufe benötigen.

Für die Verwendung direkt relevant sind die folgenden Dateien:
- praesentation.tex     Die Hauptdatei der Vorlage.
- literatur.bib         Leere Litarturdatenbank, die in der Vorlage als Platzhalter referenziert wird.

Ein kleines Einführungsbeispiel in LaTeX-Beamer ist in folgenden Dateien zu finden:
- tutorial.tex          Quell-Datei des Tutorials. Bitte Lesen Sie diese Datei, 
                        um einen Überblick über die Funktionsweise von Beamer zu erhalten.
- tutorial.pdf          Kompilierte Version des Tutorials.
- tutorial.bib          Literaturdatenbank für das Tutorial.

Für weiterführende Informationen über Beamer finden Sie hier das offizielle Manual:
http://mirrors.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf 

Weiterer Inhalt der Vorlage:
- beamercolorthemeHochschuleTrier.sty   Definiert das Farbschema der Vorlage, 
                                        die Fachbereichsfarben stehen im Dokument unter den Namen 
                                        Petrol und Senfgelb zur Verfügung.
- beamerinnerthemeHochschuleTrier.sty   Definiert die Gestaltung innerhalb des Inhalts der Folien.
- beamerouterthemeHochschuleTrier.sty   Definiert die Struktur des Folien-Layouts.
- beamerthemeHochschuleTrier.sty        Verbindet obige Dateien zum Gesamt-Theme.
- HochschuleLogo.pdf                    Das Logo, das im Titel-Bereich eingebettet wird.
- templatesetup.tex                     Präambel-Code der Vorlage.

