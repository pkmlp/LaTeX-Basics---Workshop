# LaTeX-Basics - Workshop

## Kurzbeschreibung:
In diesem Workshop wird selbständig ein Dokument erstellt, in dem spezifische LaTeX-Themen (gem. Inhalte unten) praktisch geübt werden können. Das Dokument wird mit der eigens installierten LaTeX-Umgebung auf dem eigenen Laptop oder mit dem Online-Editor Overleaf erstellt/bearbeitet. Der Workshop ist so aufgebaut, dass mit Hilfe eines Handbuches selbständig individuelle Themen (gem. Inhalte unten) bearbeitet werden können. Somit haben Teilnehmende die Möglichkeit, sich ein auf ihre Bedürfnise zugeschnittenes LaTeX-Template zu erstellen. 
 
## Inhalte:
-	Trennung von Inhalt und Struktur
-	Text erfassen in LaTeX
-	Mathematische Formeln
-	Fussnoten
-	Bilder/Grafiken und Abbildungsverzeichnis
-	Abkürzungen und Abkürzungsverzeichnis
-	Stichworte und Stichwortverzeichnis
-	Quellen zitieren und Literaturverzeichnis
-	Tabellen und Tabellenverzeichnis
 
## Vorgehen:
- Installation resp. Kontrolle der installierten LaTeX-Umgebung mit dem Dokument aus der Lunch-Session (Dokument wird abgegeben und muss fehlerfrei in der eigenen Arbeitsumgebung erstellt werden können).
-	Selbständig mit Hilfe des Dokumentes **LaTeX-Rezepte** (LaTeX_Cookbook.pdf) die persönlich relevanten/interessanten Themen (gem. Inhalte oben) einbauen (der LaTeX-Source der LaTeX-Rezepte ist in einem separaten Repo vorhanden). 

## Voraussetzung / mitbringen:
-	Erste Erfahrungen mit LaTeX
-	Eigener Laptop mit installierter LaTeX-Umgebung, oder
-	Eigener Laptop und ETH-Account um mit Overleaf Arbeiten zu können
 
## Dieses Repository enthält das Schlussdokument aus der LaTeX-Basics - Lunch-Session als Grundlage für diesen Workshop.

- Das Verzeichnis 11-OrdnerStruktur-Overleaf enthält das letzte Beispiel aus der Latex-Basisc---Lunch-Session, in der mit Overleaf gearbeitet wurde.
- Das Verzeichnis 11-OrdnerStruktur-Texmaker enthält das analoge Dokument, mit leichten Anpassungen für das Literaturverzeichnis (Overleaf-Default Backend für Literatur ist biber, TeXmaker-Default Backend für Literatur ist bibtex). 

**Bitte beachten:** Overleaf stellt selber fest, welche Compiler wie oft aufgerufen werden müssen. In einer IDE ist man selber verantwortlich dafür. PDFLaTeX kann mit vielen Inhalten (Tabellen, Grafiken, Abbildungen, etc.) umgehen. Es gibt jedoch Themen (Literaturverzeichnis, Stichwortverzeichnis) für die spezielle Compiler aufgerufen werden müssen. Für ein Dokument mit allen im Inhalt aufgeführten Inhalten muss in TeXmaker folgende Sequenz ausgeführt werden:
- PDFLaTeX (F6)
- PDFLaTeX (F6)
- BibTeX (F11 - für Literaturverzeichnis)
- PDFLaTeX (F6)
- PDFLaTeX (F6)
- MakeIndex (F12 - für Stichwortverzeichnis)
- PDFLaTeX (F6)
- PDFLaTeX (F6)
- PDF ansehen (F7)

In der Regel können solche Befehls-Sequenzen in einer IDE konfiguriert werden, so dass diese auch mit einem einfachen Mausklick ausgeführt werden können.
