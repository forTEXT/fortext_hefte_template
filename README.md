# Informationen zu Ihrer Einreichung zum Thema “Textannotation in der Hochschullehre”

Beiträge werden unter der Verwendung des hier bereitgestellten Templates erstellt. Den Ordner [`submission_template`](submission_template) können Sie als Vorlage nutzen, indem Sie diesen herunterladen und mit Ihren Inhalten und Informationen "befüllen". Alle notwendigen Dateien finden Sie dort in den vorgesehenen Formaten. Die Guidelines zur Erstellung ihrer Beiträge finden Sie auf [der forTEXT Seite](https://www.fortext-hefte.de/site/guidelines/) unter Guidelines oder [hier](#guidelines---inhalt) in dieser README-Datei.

* [Übersicht über das Repository](#übersicht-über-das-repository)
  * [Vorlagen](#vorlagen)
  * [Beispiele](#beispiele)
* [Formate und Formatierungen](#formate-und-formatierungen)
  * [Beitrag](#beitrag)
  * [Metadaten](#metadaten)
  * [Markdown-Syntax](#markdown-syntax)
  * [Literaturverzeichnis](#literaturverzeichnis)
  * [Zitieren mit Citekeys](#zitieren-mit-citekeys)
  * [Anhänge](#anhänge)
* [Guidelines - Inhalt](#guidelines---inhalt)
  

## Übersicht über das Repository

In diesem Repository finden Sie Vorlagen und Beispiele für die benötigten Bestandteile Ihrer Einreichung. 

#### Vorlagen

Der Ordner [`submission_template`](submission_template) beinhaltet Vorlagen für die Bestandteile Ihrer Einreichung. Um diese zu nutzen, können Sie die Dateien herunterladen und mit eigenen Inhalten füllen. 
Verwenden Sie... 
* für den Beitragstext die Datei [`text.md`](submission_template/text.md),
* für die SItzungsübersicht bzw. den Ablaufplan [`table.md`](submission_template/table.md) oder [`table.csv`](submission_template/table.csv), (abhängig davon, ob Sie mit CSV- oder Markdown-Datei arbeiten möchten),
* für die Bibiographie [`bibliography.json`](submission_template/bibliography.json), [`bibliography.bib`](submission_template/bibliography.bib) oder eine äquivalente Datei mit dem Suffix '.bibtex',
* für die Autor\*innen-Metadaten die Datei [`author_meta.yaml`](submission_template/author_meta.yaml).

Für Anhänge erstellen Sie einen Ordner "Anhänge", in welchen Sie alle weiteren Dateien im PDF-Format legen.
Alle Dateien reichen Sie dann komprimiert als ZIP-Ordner ein. 

#### Beispiele

Neben den Vorlagen finden Sie im Ordner [`submission_example`](submission_example) die entsprechenden Dateien ausgefüllt als Beispiele.
Enthalten sind beispielhaft...
* ein Beitragstext ([`example_text.md`](submission_example/example_text.md)), 
* eine Sitzungsübersicht als Markdown-Datei ([`example_table.md`](submission_example/example_table.md) und als CSV-Datei ([`example_table.csv`](submission_example/example_table.csv))),
* eine Bibliographiedatei ([`example_bib.json`](submission_example/example_bib.json)),
* eine Datei mit Metadaten zu den Autor*innen ([`example_author_meta.yaml`](submission_example/example_author_meta.yaml)). 

Wie diese Beispieleinreichung als von der Redaktion generierter Beitrag aussieht, sehen Sie in [`example_publication.pdf`](submission_example/example_publication.pdf) (Hinweis: Sie reichen _keine_ PDF-Datei des fertigen Beitrags ein, diese wird von der Redaktion generiert).  


## Formate und Formatierungen

#### Beitrag

Der Einführungstext, der Gesamtablauf, die Sitzungsbeschreibungen sowie der Reflexionstext sind als Fließtexte in der Markdowndatei mit dem Namen ```text.md``` (siehe [Template](submission_template/text.md) unter der jeweiligen Überschrift einzufügen. Ändern Sie die Überschriften nicht. Die Sitzungsübersicht reichen Sie als Tabelle in einer separaten Datei im Markdown- oder CSV-Format ein (```table.csv``` oder ```table.md```). Ändern Sie weder Spaltenanzahl noch -namen.
Inhaltliche Guidelines zur Verfassung Ihrer Beiträge finden Sie auf dieser Seite unter [Guidelines - Inhalt](#guidelines---inhalt).
 
#### Metadaten

Die Metadaten der Autor\*innen müssen in einer Metadatendatei im yaml-Format abgegeben werden (siehe Datei [`author_meta.yaml`](submission_template/author_meta.yaml) im Template). Bitte beachten Sie die im Template aufgeführten Hinweise. Zu den relevanten Metadaten gehören: Vorname, Nachname, ORCID, Affiliation, E-Mail-Adresse aller Autor\*innen, der Titel ihres Artikels sowie der Veranstaltungstyp bzw. das Lehrformat, für welches ihr Lehrkonzept entworfen wurde (Workshop, Proseminar etc.), die Anzahl der Sitzungen, auf die sich Ihr eingereichtes Lehrkonzept bezieht (zwei Workshoptage = zwei Sitzungen etc.) sowie 5 Keywords. Fügen Sie keine zusätzlichen Informationen hinzu.

 
#### Markdown-Syntax

Bitte beachten Sie, dass alle Formatierungen im Markdowns-Stil erfolgen müssen. Für die Arbeit mit Markdown-Dokumenten empfehlen wir die Verwendung eines Code-Editors wie beispielsweise Pycharm oder Visual Studio Code. Die meisten Code-Editoren unterstützten Markdownsyntax. Gegebenenfalls können Sie Markdown-Extensions für Ihren Editor herunterladen. Ein webbasierter Markdown-Editor, mit dem Sie sich mit der Markdown-Syntax vertraut machen können, ist beispielsweise StackEdit (https://stackedit.io/app#). Hilfreiche Erläuterungen zur Markdown-Syntax finden Sie auch hier: https://www.markdownguide.org/basic-syntax/.

Sollten Sie nicht die Vorlage verwenden, achten Sie unabhängig von der Wahl des Editors darauf, die Fließtexte sowie ggf. die Tabelle als Markdown-Datei (mit der Dateiendung `.md`) zu speichern.

 
#### Literaturverzeichnis

Die In-Text-Referenzen sowie das Literaturverzeichnis werden von der Redaktion automatisch generiert und im Zitationsstil “The Chicago Manual of Style” formatiert.

Sie müssen daher eine Datei einreichen, die alle Referenzen, die Sie im Fließtext oder in der Sitzungsübersicht zitieren oder dem Anhang hinzufügen, enthält. Sämtliche in der Veranstaltung genutzten Primär- und Sekundärtexte sowie von Ihnen für den Beitrag ergänzte Referenzen müssen in dieser Datei aufgeführt werden.

Sie können Ihr Literaturverzeichnis als BibLaTeX- (```bibliography.bib```), BiBTeX- (```bibliography.bibtex```) oder als CSL JSON-Datei (```bibliography.json```) einreichen. Die vollständigen bibliografischen Metadaten (wie Vorname, Nachname aller Autor\*innen und Herausgeber*innen, Publikationsort, URL, DOI etc.) müssen in Ihrer BibTeX-Datei sauber und vollständig hinterlegt sein.

Beispielhafte Literaturverzeichnis-Dateien sind [`example_bibliography.bib`](submission_example/example_bibliography.bib) und [`example_bibliography.json`](submission_example/example_bibliography.json). Für Ihre Einreichung tragen Sie Ihre Daten in eine der entsprechenden Dateien im [Template Ordner](submssion_template) ein. Alternativ können Sie eine solche Datei auch in Ihrem Literaturverwaltungsprogramm automatisiert generieren lassen. Bitte achten Sie auch hier darauf, die Dateinamen (```bibliography.bib```bzw. ```bibliography.json```) nicht zu verändern. 

_Hinweis_: Es ist nicht nötig, dass Sie am Ende Ihres Fließtextes eine Referenzliste aufführen. 

 
#### Zitieren mit Citekeys

Alle Beiträge werden von der Redaktion unter der Nutzung von Pandoc formatiert und gelayoutet. Aus diesem Grund bitten wir Sie, sämtliche Referenzen als Citekeys anzugeben, d. h. alle In-Text-Verweise werden durch entsprechende Citekeys gesetzt. Citekeys können Sie in Ihrem Literaturverwaltungsprogramm manuell vergeben oder automatisiert generieren. Die meisten Literaturverwaltungsprogramme unterstützen die automatisierte Generierung von Citekeys. In Citavi können Sie diese Option beispielsweise freischalten. Wenn Sie mit Zotero arbeiten, können Sie die Erweiterung “Better BibTeX” installieren. Für jeden Eintrag in Ihrem Literaturverzeichnis werden dann automatisch Citekeys erstellt. Diese Citekeys nutzen Sie dann in Ihrer Einreichung, um Referenzen zu markieren.

Grundsätzlich gilt:

* dass Sie einen Citekey durch ein “@” markieren
* [@fortextetal] führt zu (fortext 2023)
* @fortextetal führt zu fortext (2023)
* [@doe2023; @smith2022; @smith2021] führt zu (Doe 2023, Smith 2021, 2022)
* [@fortext2021, 11 f.] führt zu (fortext 2021, 11 f.)


Weiter Hinweise zur Nutzung von Citekeys finden sie hier: https://pandoc.org/chunkedhtml-demo/8.20-citation-syntax.html

Weitere Hinweise zur Generierung von Citekeys in Citavi bzw. Zotero:

* Citavi und Citation Keys: https://www1.citavi.com/sub/manual6/en/index.html?cse_customizing_citation_keys.html
* Better BibTeX Zotero: https://retorque.re/zotero-better-bibtex/citing/

Im Ordner [`submission_example`](submission_example) finden Sie einige Beispiele zur Nutzung von Citekeys.
Bitte stellen Sie sicher, dass alle Citekeys, die sie nutzen, in ihrem Literaturverzeichnis vorhanden sind.

#### Verweise zu Textabschnitten
Für textinterne Verweise wie beispielsweise Verlinkungen zu Textabschnitten bitten wir Sie, diese gemäß den Konventionen der Markdown-Syntax zu erstellen. Für Textstellen wie “siehe Abs. Einführungstext”, die auf andere Abschnitte verweisen, können Sie Anker erstellen, indem Sie die zu verlinkende Textstelle in eckige Klammern (“[]”) setzen und das Ziel der Verlinkung in runde Klammern (“()”) setzen. In der Verlinkung werden Überschriften als sogenannte "Anker" referenziert, die durch ein vorangestelltes # und den Überschriftentext identifiziert werden.
`[siehe Abschnitt](#zielüberschrift)` führt zu [siehe Abschnitt]() (mit Verlinkung zur Zielüberschrift).
Wenn eine Überschrift mehrere Wörter enthält, wird der Anker automatisch aus dem Text der Überschrift generiert, wobei alle Leerzeichen durch Bindestriche ersetzt und Sonderzeichen entfernt oder angepasst werden. So wird beispielsweise aus der Überschrift 'Mein Abschnittstitel' der Anker #mein-abschnittstitel. Achten Sie daher darauf, die genaue Schreibweise des generierten Ankers zu verwenden, um eine korrekte Verlinkung sicherzustellen.
Eine Anleitung für Verlinkungen auf Abschnitte mit einem ausfürhlichen Beispiel findet sich unter: https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links
 
#### Anhänge

Optional können Sie Ihrer Einreichung entworfene Handouts, Präsentationen, Aufgabenvorschläge, Evaluationen etc. beifügen. Alle optionalen Anhänge geben Sie als PDF-Datei im Ordner “anhänge” ab. Bitte erstellen Sie für jeden Anhang einen Eintrag in der [```author_meta.yaml```](submission_template/author_meta.yaml), indem Sie in dem dafür vorgesehenen Bereich den Titel des Anhangs, die Autor*innen-Namen und das Jahr eintragen. Um im Fließtext auf Anänge zu verweisen verwenden Sie bitte eine Notation der Art "(siehe Anhang <Titel des Anhangs>)". 
Sollten Sie im Fließtext auf Abbildungen verweisen, tun Sie dies bitte im Markdownstil und laden Sie diese als PNG-Dateien als Anhänge hoch. Für Abbildungen sind keine Einträge in Ihrem Literaturverzeichnis nötig.

## Guidelines - Inhalt

Im folgenden stellen wir Ihnen Guidelines zur inhaltlichen Strukturierung Ihres Beitrags zur Verfügung. Die folgenden Guidelines finden Sie auch auf der [Seite der forTEXT-Hefte](https://www.fortext-hefte.de/site/guidelines/). Die Guidelines beziehen sich explizit auf den Inhalt. 

- [Informationen zu Ihrer Einreichung zum Thema “Textannotation in der Hochschullehre”](#informationen-zu-ihrer-einreichung-zum-thema-textannotation-in-der-hochschullehre)
  - [Übersicht über das Repository](#übersicht-über-das-repository)
      - [Vorlagen](#vorlagen)
      - [Beispiele](#beispiele)
  - [Formate und Formatierungen](#formate-und-formatierungen)
      - [Beitrag](#beitrag)
      - [Metadaten](#metadaten)
      - [Markdown-Syntax](#markdown-syntax)
      - [Literaturverzeichnis](#literaturverzeichnis)
      - [Zitieren mit Citekeys](#zitieren-mit-citekeys)
      - [Verweise zu Textabschnitten](#verweise-zu-textabschnitten)
      - [Anhänge](#anhänge)
  - [Guidelines - Inhalt](#guidelines---inhalt)
      - [1. Einführungstext](#1-einführungstext)
        - [1.1 Rahmenbedingungen](#11-rahmenbedingungen)
        - [1.2 Voraussetzungen der Teilnehmenden](#12-voraussetzungen-der-teilnehmenden)
        - [1.3 Durchführung der Lehrveranstaltung (in Bezug auf das eingereichte Lehrkonzept)](#13-durchführung-der-lehrveranstaltung-in-bezug-auf-das-eingereichte-lehrkonzept)
      - [2. Beschreibung des Gesamtablaufs](#2-beschreibung-des-gesamtablaufs)
      - [3. Sitzungsübersicht bei Semesterplänen oder Ablaufübersicht bei kleineren Lehrformaten wie Blockseminaren oder Workshops als Tabelle](#3-sitzungsübersicht-bei-semesterplänen-oder-ablaufübersicht-bei-kleineren-lehrformaten-wie-blockseminaren-oder-workshops-als-tabelle)
      - [4. Detaillierte Darstellung der Sitzungen bzw. Einheiten zum Thema Textannotation](#4-detaillierte-darstellung-der-sitzungen-bzw-einheiten-zum-thema-textannotation)
      - [5. Reflexion des Lehrkonzepts: Gelungene Ansätze und Herausforderungen](#5-reflexion-des-lehrkonzepts-gelungene-ansätze-und-herausforderungen)
        - [5.1. Rahmenbedingungen \& Durchführung der Veranstaltung](#51-rahmenbedingungen--durchführung-der-veranstaltung)
        - [5.2. Studierende](#52-studierende)



#### 1. Einführungstext

**Inhalt:** Beschreiben Sie die Veranstaltung in bis zu 900 Worten. Dieser Text soll insbesondere die Rahmenbedingungen sowie die Voraussetzungen der Teilnehmenden beleuchten. Bitte gehen sie in Fließtextform daher auf die folgenden Punkte zu ihrer Lehrveranstaltung ein.




##### 1.1 Rahmenbedingungen

* Titel der Veranstaltung
* Optional: Beschreibung der Schnittstelle Geisteswissenschaft + Informatik/DH (sofern vorhanden)
* Typ der Veranstaltung und sofern anwendbar, Angabe der ECTS und die Art der Prüfungsleistung
_Beispiele:_ Vorlesung, Übung, Blockseminar, Projekt, Workshop
* Umfang: Für wie viele Semesterwochen bzw. Sitzungen ist das Lehrkonzept konzipiert?
_Beispiele:_ 2 Workshoptage, 16 Semesterwochen o.ä.
* Modus: Fand die Lehrveranstaltung asynchron/synchron/gemischt statt?
* Ungefähre Studierendenzahl
* Wann und wo wurde die Lehrveranstaltung angeboten?
_Beispiele:_ Winter-/Sommersemester 2023 an der TU Darmstadt


##### 1.2 Voraussetzungen der Teilnehmenden

* Zielgruppe: Für welche Zielgruppe(n) ist das Lehrkonzept ausgerichtet? Für Bachelorstudierende, Masterstudierende? Und welcher Studiengänge?
* Notwendige Vorkenntnisse in Bezug auf das Fach und/oder technische Voraussetzungen und Vorkenntnisse (ggf. differenziert nach Gruppen)
_Beispiele:_ Grundkenntnisse in der Erzähltheorie; Arbeiten mit der Commandline, Programmierkenntnisse mit R, Erfahrungen mit Annotationstool CATMA
* Kenntnisstand in Bezug auf das wissenschaftliche Arbeiten
* Vorhandene überfachliche Kompetenzen 
_Beispiele:_ Projektarbeitserfahrung, Sprachkenntnisse, interkulturelle Erfahrung
* Studentische Ausstattung
_Beispiele:_ Laptop, Lizenzen, Internetverbindung



##### 1.3 Durchführung der Lehrveranstaltung (in Bezug auf das eingereichte Lehrkonzept)

* Verfügbarkeit von Medien und Materialien – Welche Materialien waren für die Umsetzung der Lehrveranstaltung notwendig?
_Beispiele:_ Beamer, Lizenz für Online-Meetings, WLAN, Flipchart, PC Pool
* Welche Medien wurden zur Vermittlung von Kompetenzen genutzt? 
_Beispiele:_ “Im Seminar werden Videotutorials auf Youtube zur Einführung in das Tool X genutzt.”, “In einzelnen Sitzungen werden Primärtexte diskutiert, die zuvor vorbereitend gelesen wurden.”
* Unterstützung durch TutorInnen o.ä.
* Informationen zum Arbeitsmodus
_Beispiele:_ Wöchentliche Aufgaben/Abgaben, Referate
* Optional: Information zur Prüfungsleistung
_Beispiel 1:_ “Für das vorgestellte Lehrkonzept ergibt sich keine Prüfungsleistung, da nur ein Teil einer Veranstaltung präsentiert wird/ da keine Prüfungsleistung abgelegt werden muss.”
_Beispiel 2:_ “Das vorgestellte Seminar wird mit einer Studienleistung abgeschlossen. Als Studienleistung sollen Studierende in Gruppen eine Präsentation zu einem von ihnen annotierten literaturwissenschaftlichem Phänomen am Ende des Semester halten.”



#### 2. Beschreibung des Gesamtablaufs


In diesem Teil ihrer Einreichungen beschreiben sie kurz und prägnant den Gesamtablauf des eingereichten Lehrkonzepts in bis zu 600 Worten. 
Dieser Abschnitt soll einen Gesamtüberblick über den Verlauf des vorgestellten Lehrkonzepts geben. 
Unter Punkt [4. Sitzungsbeschreibungen](#4-detaillierte-darstellung-der-sitzungen-bzw-einheiten-zum-thema-textannotation) haben Sie die Möglichkeit, die einzelnen Sitzungen/Einheiten/Arbeitsblöcke im Detail zu beschreiben.
Gehen Sie in diesem Abschnitt auf die Lerninhalte und die zu vermittelnden Kompetenzen in den Einheiten ihres Lehrkonzepts ein.


_Beispiel 1:_ "Die Teilnehmer\*innen des Workshops können nach der Teilnahme eigenständig in CATMA annotieren. Dafür beginnt der Workshop mit einer Einführung in das literaturwissenschaftliche Annotieren. In den folgenden 2 Einheiten wird das Annotationstool CATMA vorgestellt und die Durchführung der verschiedenen Annotationsmöglichkeiten erarbeitet. In der 4. Einheit erstellen die Teilnehmer*innen Annotationen mit einem von ihnen gewählten Text. Der Workshop wird mit der Präsentation der eigenen Annotationen in Einheit 5 abgeschlossen."  

_Beispiel 2:_ "Die Selbststudieneinheit zielt darauf ab, die Lerninhalte Narrationstheorie und die Großgattung Prosa, die Erzählung "Krambambuli" von Marie von Ebner-Eschenbach sowie die Einführung und Anwendung der literaturwissenschaftlichen Methode des Annotierens, sowohl manuell analog als auch manuell digital mit dem Annotationstool CATMA zu vermitteln. Zudem beinhaltet die Einheit die Einzeltextanalyse der Primärlektüre mit einem besonderen Fokus auf die Figurencharakterisierung. [...]"



#### 3. Sitzungsübersicht bei Semesterplänen oder Ablaufübersicht bei kleineren Lehrformaten wie Blockseminaren oder Workshops als Tabelle

**Inhalt:** 
Die Sitzungsübersicht dient als Übersicht Ihres Lehrkonzepts. Und soll Leser*innen einen schnellen Überblick über die Strukturierung ihrer Einheiten ermöglichen. Im darauf folgenden Schritt haben sie die Möglichkeit, ihre Sitzungen im Detail zu beschreiben. Bitte füllen Sie die Tabelle daher stichpunktartig in chronologischer Reihenfolge aus.
Lektüre, Videos und andere Inhalte geben Sie durch die Nutzung von Citekeys an. Diese Citekeys müssen auch in ihrem Literaturverzeichnis vorhanden sein.
Hinweis zur Formatierung: Aufzählungselemente sind durch ein “;” zu trennen.



**Tabellenstruktur:**



| Einheit |	Modus |	Thema |	Inhalt | (Lern-)ziel(e) | Vorbereitung	Für Lehrende | Abgabe/Aufgabe |
|---------|-------|-------|--------|----------------|----------------------------|----------------|
| 1       |	synchron; online |	Einführungssitzung | Einführungsfolien und Semesterplan vorstellen | 	Überblick zum Semester | - | - | 
| 10:00-11:00 |	synchron; präsenz |	Einführungseinheit | Tool X vorstellen und Kenntnisstand der Studierenden abfragen | Hauptfunktionen von Tool X kennenlernen und beherrschen | - | - |



**Übersicht & Erklärung der Spaltennamen:**

* <ins>Spalte 1 (Einheit)</ins>  
Dient zur Gliederung ihrer Veranstaltung. Die Nummerierung erfolgt in Abhängigkeit von ihrem eingereichten Lehrkonzept. Bei Syllabi schlagen wir vor, für jede Sitzung eine Nummer zu vergeben, bei Workshops je nach Dauer/Länge können Sie die Start- und Endzeit oder die Dauer von Einheiten mit bestimmten Fokusthemen angeben. 
_Beispiele:_ “1” für Sitzungsnummer 1 eines Semesterplans, “ca. 1 Stunde” für eine Einheit ihres Workshops oder “10:00 - 12:00 Uhr”
* <ins>Spalte 2 (Modus)</ins>  
Geben Sie an, ob die Sitzung/Einheit synchron oder asynchron konzipiert ist und, ob es sich um eine Online- oder Präsenzsitzung handelt
_Beispiele:_ “synchron, online” 
* <ins>Spalte 3 (Thema)</ins>  
Nenne Sie einen Titel der Sitzung/Einheit
_Beispiele:_ “Einführungssession”, “Einführung in CATMA”, “Lektürediskussion”
* <ins>Spalte 4 (Inhalt)</ins>  
Zählen Sie die Inhalte auf, die in der Sitzung behandelt werden (z.B. Einführung in ein Tool, Diskussion von Lektüre, Projektpräsentation etc.)
_Beispiele:_ “Organisatorisches, Theoretische Einführung in CATMA”, “Seminarlektüre @autorcitekey”,“Einführung zum Thema Figurenanalyse mit Slides @slidesimAnhang”, “Annotationstool CATMA: www.catma.de”
  * _Hinweis:_ Bitte fügen Sie die dafür relevanten Metadaten wie zu Präsentationen auch in das Literaturverzeichnis hinzu und referenzieren Sie den entsprechenden Citekey bei der Aufzählung. Wenn Sie beispielsweise optional weitere Dokumente einreichen, müssen diese auch in ihrem Literaturverzeichnis hinterlegt sein.
* <ins>Spalte 5 (Lern-)ziel(e))</ins>  
Nennen Sie das Lernziel der SItzung/Einheit
_Beispiele:_ “Visualisierungsmöglichkeiten von CATMA lernen”, “Texte im Tool CATMA hochladen”, Grundlagen der Figurenanalyse verstehen und anwenden”
* <ins>Spalte 6 (Vorbereitung)</ins>  
Zählen Sie die Inhalte auf, die die Studierenden bis zu dieser Sitzung/Einheit vorbereiten sollen (Recherche, Lesen, Videos anschauen). Benennen Sie diese Inhalte explizit, indem sie Citekeys aufführen 
Beispiele: “Lesen des Kapitels 2.3. zu Narratologie in @fortextetal2026”, “Kontoeinrichtung auf catma.de” 
* <ins>Spalte 7 (Für Lehrende)</ins>  
Zählen Sie Inhalte wie (weiterführende) Literatur oder Webseiten auf, die für Lehrende für diese Sitzung relevant sind. Zählen Sie diese durch Citekeys und/oder verlinkte Schlagwörter nach Markdownsyntax auf.
Beispiele: “@fortext2026, @hander2026”, “\[Podiumsdiskussion](www.annolehren345.de)”
* <ins>Spalte 8 (Abgabe/Aufgabe)</ins>  
Beschreiben Sie die Auf- bzw. Abgabe, die in dieser Sitzung/Einheit aufgetragen wird und nennen Sie die Sitzungsnummer/-einheit, zu welcher diese fällig ist. Nummerieren Sie die Abgabe/Aufgabe gegebenenfalls.
Die ausführliche Aufgabenstellung können Sie unter Punkt 4 (“Sitzungsbeschreibungen”) in der detaillierten Sitzungsbeschreibung aufführen.
_Beispiele:_ “Abgabe 1: Textzusammenfassung bis Sitzung 9”



#### 4. Detaillierte Darstellung der Sitzungen bzw. Einheiten zum Thema Textannotation

In diesem Teil des Beitrags haben sie die Möglichkeit, die einzelnen Sitzungen/Einheiten/Arbeitsblöcke zum Thema Textannotation genauer zu beschreiben. Es handelt sich somit um einen ausformulierten Fließtext, der sich mit Ihrer Sitzungsübersicht deckt. Sie sollten das Thema der Einheit nennen, auf die Inhalte, Lernziele und die Durchführung im Detail eingehen sowie ggf. Aufgabenstellungen formulieren. Nennen Sie außerdem relevante Literatur, indem Sie dafür die entsprechenden Citekeys aufführen.
Insgesamt sollte dieser Abschnitt nicht mehr als 2500 Wörter enthalten. Jede Sitzungsbeschreibung/Einheitsbeschreibung (bei Workshops) beginnt, analog zur Spalte 1 in der Sitzungsübersicht, mit der Nummer der Sitzung bzw. der Dauer der Einheit sowie dem Titel.



_Beispiel 1:_
Einführungssitzung:
In der Einführungssitzung wird den Studierenden der Seminarplan vorgestellt. Diese Sitzung dient insbesondere organisatorischen Zwecken. 
Für die nächste Sitzung (Nr. 2) sollen die Studierenden die Lerneinheit “Digitale Annotation mit CATMA lehren” vorbereiten [@schumacherLerneinheitDigitaleAnnotation2020].  



_Beispiel 2:_
(Phase 2, 30 Minuten) Einführungseinheit
In der Einführungseinheit wird den Studierenden der Ablauf des Workshops vorgestellt. Außerdem wird in einer Fragerunde erläutert, welche Kenntnisse die Studierenden zum Thema Sentimentanalyse haben.


#### 5. Reflexion des Lehrkonzepts: Gelungene Ansätze und Herausforderungen

In diesem Teil des Beitrages reflektieren Sie Ihre Lehrveranstaltung in Form eines Fließtextes in bis zu 1200 Wörtern.
Allgemein gilt, dass Sie insbesondere in Bezug auf die Zielgruppe und Lernziele darauf eingehen sollten, wie sich genutzte Methoden und Materialien, der Aufbau/die Struktur des Lehrkonzepts bewährt haben. Reflektieren Sie gelungene Elemente und gehen Sie auf Herausforderungen des Lehrkonzepts ein, die sich möglicherweise im Laufe der Veranstaltung ergeben haben. 
Nennen Sie ggf. Ideen oder Lösungsvorschläge zur Überwindung der genannten Herausforderungen oder, falls Sie das Lehrkonzept mehrmals angewendet haben, welche Anpassungen Sie weshalb getätigt haben. Gehen Sie darauf ein, ob Sie bei erneuter Durchführung des Konzepts Anpassungen durchführen würden. Stellen Sie dabei einen Bezug zu Gründen oder möglichen Ursachen auf.
Gehen Sie auch gerne auf Feedback ein, das Sie im Zuge der Durchführung Ihrer Veranstaltung erhalten haben.



_Beispiel:_ “Insgesamt bin ich zufrieden mit dem Verlauf der Selbststudieneinheit sowie der aktiven Beteiligung der Studierenden. Meine Bedenken, dass die geplanten Zeitabschnitte für Arbeitsaufgaben und Plenumsdiskussionen zu eng getaktet sein könnten, hatten sich nicht bestätigt. Dies lag vor allem daran, dass ich die Zeitplanung durchgängig im Blick hatte und Diskussionen so moderierte, dass wir den Zeitrahmen einhielten.
Retrospektiv konnte ich feststellen, dass die Vierteilung des Lehrprojekts eine gute Idee war und die Studierenden das Angebot einer asynchronen Selbststudieneinheit anstelle einer synchronen Sitzung gut annahmen. [...]”
Orientieren Sie sich gerne an den folgenden Punkten. Nicht alle Punkte werden für Ihr Konzept relevant sein. Sie müssen daher nicht auf alle Punkte eingehen und können einzelne je nach Relevanz in Bezug auf ihre Erfahrungen detaillierter ausführen als andere:


##### 5.1. Rahmenbedingungen & Durchführung der Veranstaltung

* War der Veranstaltungstyp (Übung, (Pro)Seminar etc.) in Bezug auf das Lernziel angemessen?
* Umfang und Inhalt: Hat die geplante Durchführung der tatsächlichen Durchführung entsprochen? Zu welchen Änderungen/Anpassungen kam es und was waren die Ursachen?
* Blended Learning: War die Mischung von synchron und asynchronen Elementen sinnvoll? Ggf. Hätte sich die Mischung von synchronen und asynchronen Sitzungen angeboten? 
* Verfügbarkeit von Medien und Materialien: Waren Medien und Materialien (Beamer, Smartboard, Online-Meetings, WLAN) verfügbar und notwendig?
* Materialzugänglichkeit (Bücher, Online-Materialien, Geräte, Ausstattung)
* Tutor\*innen: War die Unterstützung von Tutor\*nnen sinnvoll? Oder wäre die Unterstützung im Rückblick sinnvoll?
* Wie haben sich die Frequenz und der Umfang der Vorbereitungen/Aufgaben/Abgaben bewährt?
* Hat sich die Prüfungsform als sinnvoll erwiesen

##### 5.2. Studierende

* Zielgruppe: Studierende welcher Fachrichtungen und welches angestrebten Hochschulgrades (Bachelor/Master) haben tatsächlich ihre Veranstaltung besucht? Zu welchen Anpassungen führte die möglw. von der Planung abweichende Zielgruppe?
* Waren ausreichend Vorkenntnisse in Bezug auf das Fach (ggf. differenziert nach Gruppen) gegeben? Falls nicht: Wie haben Sie darauf reagiert? Hätten bestimmte Sitzungen ausführlicher oder ggf. zusätzlich eingeplant werden müssen?
* Haben Sich überfachliche Kompetenzen als hilfreich erwiesen? (z.B. Projektarbeitserfahrung, Sprachkenntnisse, interkulturelle Erfahrung)
* Welche technischen Voraussetzungen und Vorkenntnisse waren tatsächlich vorhanden oder wären zwingend notwendig gewesen?
* Gab es für Studierende Barrieren und wie konnten bzw. können diese ggf. überwunden werden?
* Welche Sitzungen waren besonders produktiv/ weniger produktiv?





Bei Fragen oder Anregungen wenden Sie sich gerne an redaktion@fortext-hefte.de. Wir helfen Ihnen gerne weiter und sind für jede Anregung zur Verbesserung unserer Richtlinien dankbar.