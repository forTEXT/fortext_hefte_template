# Hinweis zur Nutzung des Markdown Formats

Markdown ist eine Auszeichnungssprache, mit der sich Texte klar strukturiert und leicht lesbar formatieren lassen. Dieses Dokument enthält Beispiele für typische Markdown Formatierungen. Um diese nachvollziehen zu können sollten Sie das Dokument in einem passenden Editor öffnen, um sowohl den Rohtext mit den verwendeten Markdown-Symbolen als auch die finale Darstellung zu sehen. So wird ersichtlich, mit welchen Zeichen die Formatierung erfolgt und wie das Ergebnis aussieht.


Hilfreiche Erläuterungen zur Markdown-Syntax finden Sie auch hier: https://www.markdownguide.org/basic-syntax/.



## Links
Zur Verlinkung von Textstellen, setzen sie das zu verlinkende Textelement in eckige Klammern gefolgt vom Ziel des Links in runden Klammern.

Für eine Verlinkung auf eine externe Seite entspricht das Ziel der URL der Seite.

Beispiel: [TU Darmstadt-Seite](https://www.tu-darmstadt.de)

Innerhalb des Textes können Überschriften referenziert werden. Dies geschieht, indem der sogenannte Anker referenziert wird. Der Anker bestejt aus einer Raute (#) und dem Text der Überschrift, wobei alles in Kleinbuchstaben gesetzt und Leerzeichen durch Bindestriche (-) ersetzt werden. Der Anker für die erste Überschrift dieses Textes wäre also #hinweis-zur-nutzung-des-markdown-formats. Der Link auf diesen Anker sieht dann folgendermaßen aus: 

Beispiel: [Dieser Link führt zur ersten Überschrift](#hinweis-zur-nutzung-des-markdown-formats)

Hinweis: Unabhängig, ob es sich um eine H1, H2, H3, ... Überschrift handelt, wird für den Anker eine Raute (#) verwendet.
  
## Fußnoten
Verweise auf Fußnoten werden in Markdwon ebenfalls in eckige Klammern geschrieben. In der Klammer steht ein Dachsymbol/ Zirkumflex (^) gefolgt von der Zahl der Fußnote. Der Inhalt der Fußnote wird erst ganz am Ende (!) des Dokuments definiert. Dabei beginnt die Definition mit demselben Dachsymbol und der Nummer, gefolgt von einem Doppelpunkt und dem Text der Fußnote.

Beispiel:

Dies ist ein Satz mit einer Fußnote[^1].

... Hier folgt der weitere Text des Dokuments ...

[^1]: Hier steht der Inhalt der Fußnote.



## Citekeys
Alle Beiträge werden von der Redaktion unter der Nutzung von Pandoc formatiert und gelayoutet. Aus diesem Grund bitten wir Sie, sämtliche Referenzen als Citekeys anzugeben, d. h. alle In-Text-Verweise werden durch entsprechende Citekeys gesetzt. Citekeys können Sie in Ihrem Literaturverwaltungsprogramm manuell vergeben oder automatisiert generieren. Die meisten Literaturverwaltungsprogramme unterstützen die automatisierte Generierung von Citekeys. In Citavi können Sie diese Option beispielsweise freischalten (siehe:https://www1.citavi.com/sub/manual6/de/index.html?bibtex_keys.html). Wenn Sie mit Zotero arbeiten, können Sie die Erweiterung “Better BibTeX” installieren (https://retorque.re/zotero-better-bibtex/). Für jeden Eintrag in Ihrem Literaturverzeichnis werden dann automatisch Citekeys erstellt. Diese Citekeys nutzen Sie dann in Ihrer Einreichung, um Referenzen zu markieren. 

Ein In-Text Verweis mit einem Citekey beginnt grundsätzlich mit einem @. Darüber hinaus gibt es verschiedene Möglichkeiten die Referenz zu gestalten. Dabei gelten die folgenden Regeln:

* Einfache Referenz in Klammern: [@smith2021] führt zu -> (Smith 2021)
* Direkte Erwähnung: @smith2021 führt zu -> Smith (2021)
* Mehrere Quellen: [@doe2023; @smith2022; @smith2021] führt zu -> (Doe 2023, Smith 2021, 2022) 
* Seitenangabe: [@smith2021, 11 f.] führt zu -> (Smith 2021, 11 f.) 
* Seitenangabe mehrseitig: [@smith2021, 11--14] führt zu -> (Smith 2021, 11-14)
* Mehrere Seitenangaben:[@smith2021, 11--14, 102] führt zu -> (Smith 2021, 11-14, 102)
* Seitenangaben bei direkter Erwähnung: @smith2021 [11--14] führt zu -> Smith (2021, 11-14)
* Kombination der Regeln: [vgl. @Zimmermann-2000, 21-22;@Boekaerts-2000, 418--419, 432] führt -> zu (vgl. Zimmermann 2000, 21–22; Boekaerts und Niemivirta 2000, 418–419, 432)

Weiter Hinweise zur Nutzung von Citekeys finden sie hier: https://pandoc.org/chunkedhtml-demo/8.20-citation-syntax.html


