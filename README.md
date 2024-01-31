# Leitfaden Barrierefreiheit für Redakteur*innen

Dieser Leitfaden wurde erstellt, um es Redakteur*innen leichter zu machen barrierefreie Inhalte zu erstellen. Er enthält die wichtigsten Regeln in möglichst kurzer Form. Er bildet nicht alle potentiell gültigen Regeln ab. Das komplette zugrundeliegende Regelwerk sind die [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG22/quickref/?versions=2.2)(Englisch).

## Allgemein

*Generell*: **Wenn es keinen wichtigen Grund gibt, sollte nicht von den vorgegebenen Formatvorlagen eines CMS oder Redaktionssystems abgewichen werden. Konkret: Schriften, Farben, Schriftsatz (z.B. linksbündig) werden nicht verändert, da sie bereits optimiert wurden.**

##  Klare und einfache Sprache

* Verwenden Sie **einfache Sprache und Formatierung**, die dem Kontext angemessen ist.
* Schreiben Sie in **kurzen, klaren Sätzen und Absätzen**.
* Vermeiden Sie die Verwendung unnötig komplexer Wörter und Ausdrücke.
* Erweitern Sie Akronyme bei der ersten Verwendung. Zum Beispiel: Web Content Accessibility Guidelines (WCAG).
* Erwägen Sie die Bereitstellung eines Glossars für Begriffe, die den Leser*innen möglicherweise nicht bekannt sind.
* Erwägen Sie die Verwendung von Bildern, Illustrationen, Video, Audio und Symbolen, um die Bedeutung zu verdeutlichen.

Weitere Informationen in der [Kleinen Schreibschule von BIK für Alle](https://bik-fuer-alle.de/kleine-schreibschule.html)


## Textstrukturierung

Strukturieren Sie Texte in **sinnvolle Abschnitte**.
Verwenden Sie **Überschriften, Listen und Absätze** um Texte zu strukturieren.

### Überschriftenhierarchie

Verwenden Sie Überschriften in **austeigender Hierarchie**. Einzelne Überschriftenebenen dürfen nicht übersprungen werden.

**Beispiel**: Nach einer „Überschrift Ebene 2“ kommt entweder eine weitere mit der Ebene 2, oder eine der Ebene 3.


## Textgestaltung
Vermeiden Sie Blocksatz.

## Fremdsprachen kennzeichnen

Wenn ein Text Worte oder Sätze in einer anderen Sprache enthält, müssen dieses entsprechend gekennzeichnet werden, damit Bildschirmvorleseprogramme diese in der passenden Sprache vorlesen können. Das geht in HTML mit dem lang-Attribut, oder in einem CMS mit einer entsprechenden Editor-Einstellung.

## Alternativtexte für Fotos, Schaubilder & Grafiken

Grafiken und Bilder brauchen **aussagekräftige Alternativtexte** um für blinde und seheingeschränkte Menschen verständlich zu sein und wahrgenommen werden zu können.

Unterschiedliche Grafiken erfordern unterschiedliche Alternativ-Texte. Dabei sollte man sich die folgende Frage stellen: „Welchen Zweck erfüllt die Grafik?“

Die häufigsten Fälle:
1. Die Grafik ist nicht verlinkt und vermittelt Bildinformation (z.B. ein Foto): alt=“Beschreibung des Inhalts des Bildes“
2. Die Grafik ist verlinkt und verweist z.B. auf einen Artikel: alt=“Artikelüberschrift“
3. Die Grafik ist ein interaktives Element und löst eine Aktion aus, z.B. ein Hamburger-Icon: alt=“Menü öffnen“
4. Rein dekorative Grafiken brauchen keinen Alternativtext: alt= ““

Weitere Fälle können im [Alt-Decision-Tree(Englisch)](https://www.w3.org/WAI/tutorials/images/decision-tree/) nachgeschlagen werden. Weitere [Infos zu Alternativtexten auf Deutsch](https://bik-fuer-alle.de/alternativtexte-fuer-grafiken.html)

## Eindeutige Seitentitel

Jede Webseite benötigt einen eigenen Titel, der den Inhalt der jeweiligen Seite eindeutig beschreibt und von anderen Seiten unterscheidet. Meist eignet sich dafür die Hauptüberschrift der Seite.

Die wichtigsten Informationen kommen an den Anfang, z.B. den Namen der Seite vor dem Namen der Organisation. Bei Seiten, die Teil eines mehrstufigen Prozesses sind, geben Sie den aktuellen Schritt im Seitentitel an.

**Beispiel**: Bei einem Artikel names „Das war 2022“ im Blog der Agentur „Windrich & Sörgel“ hieße der Titel „Das war 2022 - Windrich & Sörgel“.

## Sprechende Linktexte

Linktexte müssen den Inhalt/Zweck des Linkziels beschreiben.

**Zu vermeiden**: „hier klicken“ oder „mehr lesen“.
**Besser**: Der Titel oder die erste Überschrift der Zielseite.
**Bei Downloads**: Dateityp und -größe angeben, z.B. „Quartalszahlen 2023 (PDF, 20MB)".

## Farben
Eigentlich sollten Sie als Redakteur*in nicht mit Farben in Berührung kommen, weil die bereitgestellten Formatvorlagen alle Fälle abdecken und bereits optimiert sind. Diese Regeln gelten für den Fall, dass sie wider Erwarten etwas Neues erfinden müssen.

### Kontraste

Wenn Sie Grafiken einfügen, oder Texte einfärben, stellen Sie sicher, dass ausreichende Kontraste vorhanden sind. Wenn Vordergrund- und Hintergrundfarben in ihrer Helligkeit zu ähnlich sind, könnte der Kontrast möglicherweise zu gering sein. Hierbei handelt es sich nicht um Fotografien, sondern um Symbole, Schaubilder oder Diagramme. Nutzen Sie einen [Kontrast-Checker](https://contrast-ratio.org).

### Farbe nicht als alleiniges Unterscheidungsmerkmal

Achten Sie darauf, Informationen nicht ausschließlich durch Farben zu vermitteln.

**Beispiel**: Beim Anzeigen einer Fehlermeldung oder Warnung sollte diese nicht nur durch Farbe (Gelb/Rot) zu erkennen sein, sondern auch mit einem Icon gekennzeichnet werden.

**Beispiel 2**: Bei einem Schaubild mit verschiedenen Kurven sollte die Unterscheidung zwischen den Kurven nicht nur durch Farben erfolgen, sondern auch durch unterschiedliche Darstellungsformen wie beispielsweise gestrichelte oder gepunktete Linien.

## Video & Audio

Video & Audioinhalte benötigen Untertitel, Transkript und Gebärdensprachenversionen um barrierefrei zu sein.

[Leitfaden zu audiovisuellen Medien in den WCAG](https://www.w3.org/WAI/media/av/)


## Tabellen
Sehbehinderte Menschen, die Bildschirmvorleseprogramme verwenden, erschließen sich Tabellen, indem sie mit der Tastatur durch die Spalten und Zeilen navigieren.
Tabellen sollten daher so einfach wie möglich gestaltet werden. * Lieber zwei einfache Tabellen anstelle einer komplexen
* keine leeren Zellen für zusätzlichen Abstand einzufügen
* die Zeilen- und Spaltenüberschriften deutlich kennzeichnen

## Quellen

* https://www.w3.org/WAI/roles/writers/
* https://www.w3.org/WAI/tips/writing/
* https://www.w3.org/WAI/tutorials/images/decision-tree/
* https://bik-fuer-alle.de/webinhalte-barrierefrei-pflegen.html
* https://bik-fuer-alle.de/files/pdf/01_Kurzeinstieg%20fuer%20Redakteure.pdf
* https://www.accede-web.com/wp-content/uploads/accessibility-guidelines-editors-template.pdf