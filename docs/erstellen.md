## B.2 Objekte in einer DDBstudio-Ausstellung anlegen

Die Grundbausteine einer DDBstudio-Ausstellung sind die Objekte, die ‚Exponate‘ der virtuellen Ausstellung. Aus Sicht der NutzerInnen, die Ihre Ausstellung im Internet besuchen, sind Objekte die Medien (Bilder, Videos, Audio-Clips, 3D-Objekte), die Sie auf den Ausstellungsseiten präsentieren. Das Datenmodell der Ausstellungs-Software ist etwas differenzierter: Ein Objekt bezeichnet hier nicht einfach das Digitalisat eines realen Objekts, sondern es beschreibt das reale Objekt (z. B. ein Buch, ein archivalisches Dokument) vermittels Metadaten. Die Entsprechung in einer vordigitalen Bibliothek zu einem Objekt in einer DDBstudio-Ausstellung wäre eine Karteikarte im Katalog – also nicht das Medium selbst.

Wenn Sie das Objekt mit Hilfe von Metadaten beschrieben haben, sollten Sie es in einem zweiten Schritt mit einer Datei verknüpfen, die dieses Objekt digital repräsentiert. Im klassischen Fall eines digitalisierten Realbestandes sind dies Scans oder Fotos, es kann sich aber auch um ein Video, eine Tonaufnahme oder ein 3D-Modell handeln. Objekt und Digitalisat(e) sind also logisch getrennte Einheiten – das gilt auch für genuin digitale Objekte wie etwa Videos oder Tonaufnahmen.

## B.2.1. Objekte hinzufügen

Um Objekte auf einer Ausstellungsseite einbinden zu können, müssen sie bereits angelegt worden sein. Dies geschieht in der Rubrik „Objekte“, wo Sie auch alle Objekte der Ausstellung zentral verwalten (Abb. B.2.1, <span class="red-circle">1</span>).

!![Abb. B.2.1 Die Rubrik „Objekte“][B-2-1] 

Über die Schaltfläche „Neues Objekt hinzufügen“ (<span class="red-circle">2</span>) kann ein neues Objekt angelegt werden.
Die Seite „Neues Objekt hinzufügen“ (Abb. B.2.2) bietet am oberen Rand drei Tabs, über die sich die verschiedenen Eingabemasken aufrufen lassen, mit denen die Daten und Verknüpfungen zum betreffenden Objekt erfasst werden. Ein Klick auf die Schaltfläche „Objekt hinzufügen“ (<span class="red-circle">1</span>) legt das neue Objekt in der Datenbank an. Zuvor müssen Sie allerdings noch einige Metadatenfelder zum Objekt ausfüllen, denn es handelt sich um Pflichtfelder.  

!![Abb. B.2.2 Seite „Neues Objekt hinzufügen“][B-2-2]


## B.2.2 Das Objekt mit Metadaten versehen

Wenn Sie die Metadaten eines bereits angelegten Objekts ergänzen oder ändern möchten, wählen Sie in der Rubrik „Objekte“ (Abb. B.2.3, <span class="red-circle">1</span>) das betreffende Objekt aus und klicken auf den Textlink „Bearbeiten“ (<span class="red-circle">2</span>).

!![Abb. B.2.3 Objekt bearbeiten][B-2-3]

Die virtuellen Ausstellungen der Deutschen Digitalen Bibliothek arbeiten mit einem speziell zu diesem Zweck zusammengestellten Metadatenschema (s. Anhang [Abschnitt C.1][1]), das die notwendigen Angaben für unterschiedliche Objektkategorien wie Texte, Bilder, Filme, kunstgewerbliche Gegenstände etc. zusammenfasst. Die Werte mancher Felder werden bei der Ausgabe im Frontend direkt ausgeben, andere erzeugen nur einen Link oder dienen der Einbindung von Daten, etwa eines Vimeo-Videos. Nicht alle Felder müssen ausgefüllt werden; nicht ausgefüllte Felder werden bei der Ausgabe ignoriert. Pflichtfelder sind in der grauen Box über dem Eingabefeld als solche gekennzeichnet, außerdem finden Sie dort bei den meisten Feldern eine kurze Erläuterung bzw. Beispiele, mit welchen Informationen das Feld zu befüllen ist. Hinweise zu den einzelnen Feldern der Eingabemaske finden Sie außerdem im Anhang ([Abschnitt C.1][1]). 

Wenn Sie fertig sind, sichern Sie Ihre Eingabe mit einem Klick auf das Bedienfeld „Änderungen übernehmen“ (Abb. B.2.4, <span class="red-circle">1</span>).

!![Abb. B.2.4 Metadaten des Objekts auf der Seite „Objekt … bearbeiten“][B-2-4]

Leider gibt es in der verwendeten Ausstellungs-Software keine Möglichkeit, bei der Bearbeitung der Metadaten die schon vorgenommenen Eingaben zu speichern, ohne die Seite „Objekt … bearbeiten“ zu verlassen und auf die Seite „Objekt …“ zu gelangen (Abb. B.2.5).

!![Abb. B.2.5 Seite „Objekt ...“</a>][B-2-5]

Um die Bearbeitung fortsetzen zu können, rufen Sie über die Schaltfläche „Bearbeiten“ (<span class="red-circle">1</span>) wieder die Seite „Objekt … bearbeiten“ auf und wählen dort den Tab „Metadaten des Objekts“ (vgl. Abb. B.2.4). Das ist sicherlich etwas umständlich, die zwei Klicks sind aber gut investiert, und wir empfehlen dringend, bei komplexen Eingaben gelegentlich zwischenzuspeichern.

## B.2.3 Das Objekt mit Dateien verknüpfen

### B.2.3.1 Verknüpfen mit einer Bild- oder Audiodatei

Sie können nun eine Datei mit dem Objekt verknüpfen. Wenn es sich um eine Bilddatei handelt, wird sie im Frontend als Vorschaubild und in der Lightbox im Großformat angezeigt. Verknüpfen Sie eine Audiodatei mit dem Objekt, erscheint auf der Ausstellungsseite ein entsprechendes Symbol, über das ein Audioplayer geöffnet wird, mit dem die NutzerInnen den Audioclip anhören können.
Welche Bild- und Audio-Dateiformate Sie verwenden können, finden Sie direkt im Backend erläutert. Die wichtigste Information: Sie können keine PDF-Dateien einbinden.

!![Abb. B.2.6 Tab „Dateien“ der Seite „Objekt … bearbeiten“][B-2-6]

Zum Verknüpfen mit einer Datei wechseln Sie auf der Seite „Objekt … bearbeiten“ (Abb. B.2.6) in den Reiter „Dateien“ (<span class="red-circle">1</span>) und wählen über die Schaltfläche „Datei auswählen“ (<span class="red-circle">2</span>) eine Datei auf Ihrem lokalen Datenträger aus.
Nachdem Sie die Änderungen übernommen haben (<span class="red-circle">3</span>), wird die verknüpfte Datei auf der Objektseite (Abb. B.2.5) als Vorschaubild angezeigt. Wenn Sie nun wieder in den Modus „Bearbeiten“ (<span class="red-circle">1</span>) und dort zum Reiter „Dateien“ wechseln (Abb. B.2.6), erscheint der Name der verknüpften Datei in einem Drag-and-Drop-Balken mit Textlinks zum Löschen der Datei (Abb. B.2.7).

!![Abb. B.2.7 Tab „Dateien“ nach Einfügen einer Datei][B-2-7]

!!! note "Datei löschen ist nicht gleich Objekt löschen"

    Wenn Sie eine verknüpfte Datei löschen möchten, klicken Sie bitte auf den Textlink „Löschen“ (neben „Bearbeiten“) und nicht auf die Schaltfläche „Löschen“ im Kasten rechts – diese löscht das ganze **Objekt**, nicht nur die Datei!


### B.2.3.2 Verknüpfung mit einer Videodatei

Die Software sieht auch die Möglichkeit vor, Videodateien direkt mit einem Objekt zu verknüpfen. Die Einbindung des Videos erfolgt nicht als Datei, sondern über das Metadatenfeld „Videoquelle“.

In einem ersten Schritt müssen Ihre Videodateien bei einer der beiden unterstützten Videoplattformen hochgeladen werden: In der Deutschen Digitalen Bibliothek (DDB) oder auf Vimeo. Wenden Sie sich dazu bitte an Ihre Ansprechperson bei der Deutschen Digitalen Bibliothek.

Die Verknüpfung mit dem Objekt erfolgt nun über das Metadatenfeld „Videoquelle“ (Abb. B.2.8), wo ein so genannter Shortcode eingetragen wird. Über die Schaltfläche „Video-Shortcode-Helfer“ (<span class="red-circle">1</span>) können Sie die notwendigen Angaben bequem über Dialogfelder eingeben.

!![Abb. B.2.8 Einbindung eines Videos über das Metadatenfeld „Videoquelle“][B-2-8]

In der Dialogbox „Video-Shortcode bearbeiten“ (Abb. B.2.9) stellen Sie zunächst die Videoplattform ein (<span class="red-circle">1</span>), dann die ID des Videos (<span class="red-circle">2</span>) auf der betreffenden Plattform. Die ID können Sie auf Vimeo über den Button „Teilen“ abrufen. Tragen Sie bitte nur die ID selbst in das Feld ein, nicht die Domain der Plattform (also **ohne** https://vimeo.com/).

Über die Felder „Startzeit“ und „Stoppzeit“ (<span class="red-circle">3</span>, <span class="red-circle">4</span>) können Sie festlegen, dass in der Ausstellung nur eine bestimmte Sequenz aus dem Video abgespielt wird. Mit „Übernehmen“ bestätigen Sie Ihre Eingaben, gespeichert werden sie erst beim Speichern des Objekts.

!![Abb. B.2.9 Dialogbox „Video-Shortcode bearbeiten“][B-2-9]

### B.2.3.3 Objekt mit mehreren Dateien verknüpfen

Die Software sieht vor, dass Objekte mit beliebig vielen Dateien verknüpft werden können. Nun wird in der Frontend-Darstellung auf den Ausstellungsseiten immer nur eine Datei angezeigt. Erst wenn die NutzerInnen das Objekt in der Lightbox aufrufen, werden auch die weiteren Abbildungen ausgegeben. In Ausnahmefällen kann das sinnvoll sein, normalerweise sollten aber alle gezeigten Abbildungen auf den Ausstellungsseiten selbst erscheinen. Wollen Sie also beispielsweise mehrere Seiten eines Dokuments anzeigen, legen Sie für jede Seite ein eigenes Objekt an und verknüpfen diese mit den entsprechenden Grafikdateien.

Es besteht aber auch die Möglichkeit, solche Objekte außerhalb des Layout-Rahmens der Ausstellung in einem  so genannten Bookviewer anzeigen zu lassen, der das Blättern durch die Seiten eines Dokuments, die Blätter einer Grafikfolge etc. ermöglicht. Der Bookviewer öffnet sich in einem neuen Fenster, das er ganz ausfüllt (Abb. B.2.10).

!![Abb. B.2.10 Bookviewer-Ansicht eines mehrseitigen Dokuments][B-2-10]

Legen Sie für ein Konvolut, das Sie mit dem Bookviewer darstellen möchten, immer ein eigenes Objekt an, auch wenn Sie beispielsweise dessen  einzelne Blätter bereits als Objekte angelegt haben.

Nachdem Sie im Tab „Dateien“ das Objekt mit einer ersten Datei verknüpft haben, können Sie im Kasten „Neue Dateien hinzufügen“ die nächste Abbildung einbinden (Abb. B.2.11, <span class="red-circle">1</span>). Über die Schaltfläche „Weitere Datei hinzufügen“ (<span class="red-circle">2</span>) erzeugen Sie einen neuen „Durchsuchen…“-Button für die nächste Grafik-Datei.

!![Abb. B.2.11 Hinzufügen weiterer Dateien zu einem Objekt][B-2-11]

Der letzte Schritt ist nun, einen Link zu erzeugen, mit dem Sie den Bookviewer mit diesem Objekt in Ihre Ausstellung einbinden können. Den Link zum Bookviewer finden Sie auf der Seite „Objekt ...“ (vgl. Abb. B.2.5) in der rechten Spalte im untersten Kasten.

Sie können nun noch die Darstellungsoptionen im Viewer ändern, indem Sie die Parameter „n0“ und „2up“ ändern. „n1“ schlägt initial die Seite 2 der Folge auf, „n5“ die Seite 6 usw. Analog dazu zeigt „1up“ Einzelseiten, „2up“ jeweils zwei Seiten usw.

### B.2.3.4 3D-Objekte einbinden

Neben Bildern, Audiodateien und Videos können Sie auch 3D-Objekte in Ihre Ausstellung einbinden. Ein Beispiel finden Sie in der virtuellen Ausstellung zur Geschichte Karlsruhes auf [Seite 11](http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/exhibits/show/vom-privilegienbrief-zum-bundesverfassungsgericht/karl-drais---erfinder-des-zweirads).

!![Abb. B.2.12 Der Player zur Anzeige eines 3D-Objekts in der Lightbox][B-2-12]

Ein Klick auf das Laufrad (oben rechts) öffnet die Lightbox mit einem 3D-Viewer, in dem sich das historische Objekt bzw. sein 3D-Modell von allen Seiten betrachten lässt (Abb.B.2.12). Eine Übersicht (auf Englisch) der im 3D-Viewer verfügbaren Navigationsbefehle finden Sie [hier](http://x3dom.org/download/1.5.1/docs/html/navigation.html).
Für das Einfügen von 3D-Dateien steht auf der Seite „Objekt … bearbeiten“ ein eigener Reiter zur Verfügung (Abb. B.2.13, <span class="red-circle">1</span>). Sie benötigen drei Dateien für die Darstellung eines 3D-Objekt im 3D-Player:

* eine .X3D-Datei als räumliches Modell, 
* eine .jpg-Datei als Textur 
* und ein Vorschaubild.

!![Abb. B.2.13 3D-Objekte einbinden][B-2-13]

## B.2.4 Objekte suchen

DDBstudio bietet Ihnen mehrere Möglichkeiten, ein bestimmtes Objekt in der Liste der angelegten Objekte schnell und komfortabel zu finden. Mit Hilfe des Buttons „Objekte suchen“ über der Objektliste gelangen Sie auf die Seite „Objekte suchen“ (Abb. B.2.14).

!![Abb. B.2.14 Die Suchmaske der Objektsuche][B-2-14]

Die Eingabe in „In allen Feldern suchen“ (<span class="red-circle">a</span>) funktioniert als Freitextsuche in den Metadaten. „Suche auf bestimmte Felder eingrenzen“ (<span class="red-circle">b</span>) ermöglicht es Ihnen, in bestimmten Metadatenfeldern zu suchen (linke Auswahlliste) und dabei logische Operatoren wie „enthält nicht“ oder „ist leer“ zu verwenden (rechte Auswahlliste). Wenn Ihnen die ID des Objekts oder der Objekte bekannt ist, können Sie den dritten Suchschlitz verwenden (<span class="red-circle">c</span>). Die Suche nach dem Kriterium der Sichtbarkeit im Frontend (<span class="red-circle">d</span>) kann nützlich sein, wenn bei der Abnahme der Ausstellung durch Ihre Ansprechperson bei der Deutschen Digitalen Bibliothek bestimmte Objekte auf „nicht sichtbar“ gestellt wurden (etwa, weil die Lizenzauszeichnung fehlt) und Sie gezielt diese Objekte nacharbeiten möchten. 

[B-2-1]: img/B-2-1.jpg "Die Rubrik „Objekte“"
[B-2-2]: img/B-2-2.jpg "Abb. B.2.2 Seite „Neues Objekt hinzufügen“"
[B-2-3]: img/B-2-3.jpg "Abb. B.2.3 Objekt bearbeiten; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba) (obere Maske)"
[B-2-4]: img/B-2-4.jpg "Abb. B.2.4 Metadaten des Objekts auf der Seite „Objekt … bearbeiten“"
[B-2-5]: img/B-2-5.jpg "Abb. B.2.5 Seite „Objekt ...“; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba) (obere Maske)"
[B-2-6]: img/B-2-6.jpg "Abb. B.2.6 Tab „Dateien“ der Seite „Objekt … bearbeiten“"
[B-2-7]: img/B-2-7.jpg "Abb. B.2.7 Tab „Dateien“ nach Einfügen einer Datei; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba) (obere Maske)"
[B-2-8]: img/B-2-8.jpg "Abb. B.2.8 Einbindung eines Videos über das Metadatenfeld „Videoquelle“"
[B-2-9]: img/B-2-9.jpg "B.2.9 Dialogbox „Video-Shortcode bearbeiten“" 
[B-2-10]: img/B-2-10.jpg "Abb. B.2.10 Bookviewer-Ansicht eines mehrseitigen Dokuments; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/viewer/show/177#page/n0/mode/1up](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/viewer/show/177#page/n0/mode/1up)"
[B-2-11]: img/B-2-11.jpg "Abb. B.2.11 Hinzufügen weiterer Dateien zu einem Objekt; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/fokus-masken-mythen-kagaba) (obere Maske)"
[B-2-12]: img/B-2-12.jpg "Abb. B.2.13 Der Player zur Anzeige eines 3D-Objekts in der Lightbox; Quelle: [http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/exhibits/show/vom-privilegienbrief-zum-bundesverfassungsgericht/karl-drais---erfinder-des-zweirads](http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/exhibits/show/vom-privilegienbrief-zum-bundesverfassungsgericht/karl-drais---erfinder-des-zweirads)"
[B-2-13]: img/B-2-13.jpg "Abb. B.2.14 3D-Objekte einbinden"
[B-2-14]: img/B-2-14.jpg "Die Suchmaske der Objektsuche"

[1]: /anhang/index.html#c1-metadaten "zum Abschnitt C.1 Metadaten"

