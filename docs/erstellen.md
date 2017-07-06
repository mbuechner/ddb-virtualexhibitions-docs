## B.2 Objekte in Omeka

Die Grundbausteine einer Omeka-Ausstellung sind die Objekte, die ‚Exponate‘ der virtuellen Ausstellung. Aus Sicht der Nutzer, die Ihre Ausstellung im Internet besuchen, sind Objekte die Medien (Bilder, Videos, Audioclips, 3D-Objekte), die auf den Ausstellungsseiten präsentiert werden. Das Datenmodell von Omeka ist hier etwas differenzierter. Ein Omeka-Objekt ist nicht mit dem Digitalisat eines realen Objekts gleichzusetzen, es beschreibt vielmehr ein reales Objekt (z.B. ein Buch, ein archivalisches Dokument) durch Metadaten über dieses Objekt. Die Entsprechung zu einem Omeka-Objekt in einer vordigitalen Bibliothek wäre eine Karteikarte im Katalog – also nicht das Medium selbst. Mit einem Omeka-Objekt können in einem zweiten Schritt Dateien verknüpft werden, die dieses Objekt digital repräsentieren. Im klassischen Fall eines digitalisierten Realbestandes sind dies Scans oder Fotos, es kann sich aber auch um ein Video, eine Tonaufnahme oder ein 3D-Modell handeln. Omeka-Objekt und Digitalisat(e) sind also logisch getrennte Einheiten. Das gilt auch für nativ digitale Objekte wie etwa Videos oder Tonaufnahmen.

## B.2.1. Objekte hinzufügen

Um Objekte auf einer Ausstellungsseite einbinden zu können, müssen sie bereits angelegt worden sein. Dies geschieht in der Rubrik „Objekte“, wo auch alle Objekte einer Ausstellung zentral verwaltet werden (Abb. 2.1, 1).

!![Abb. B.2.1 Die Rubrik "Objekte"][B-2-1]

Über die Schaltfläche „Ein Objekt hinzufügen“ (2) kann ein neues Objekt angelegt werden.
Die Seite „Ein Objekt hinzufügen“ (Abb. 2.2) bietet am oberen Rand eine Reihe von Tabs, über die sich die verschiedenen Eingabemasken aufrufen lassen, mit denen die Daten und Verknüpfungen zum betreffenden Objekt erfasst werden. Beim Aufruf der Seite vorausgewählt ist immer das Tab „Dublin Core“ (1).
 
Von dem umfangreichen Dublin-Core-Metadatenschema verwendet die DDB bei ihren virtuellen Ausstellungen nur das erste Feld „Name der Ressource“. Alle weiteren Metadaten werden in einem eigens für die virtuellen Ausstellungen der DDB angepassten Metadatenschema, dem Objekttyp VA DDB, erfasst. Für die interne Verwaltung der Objektdaten in Omeka, ist es erforderlich, diesem ersten Feld von Dublin Core einen Wert zuzuweisen (2): den Titel des Objekts.

{{Kasten Die Metadaten ...}}

!![Abb. B.2.2 Seite Ein Objekt hinzufügen][B-2-2]

Damit Objekte später in Ihrer virtuellen Ausstellung angezeigt werden können, müssen sie den Status „öffentlich“ haben (3). Ein Klick auf die Schaltfläche „Objekt hinzufügen“ (4) legt das neue Objekt in der Datenbank an.

### Praxistipp: Speicherstrategie - erst anlegen, dann ergänzen

Wie bei allen webbasierten Content- bzw. Asset-Management-Systemen arbeiten Sie bei Omeka in Ihrem Webbrowser (Client), die Daten werden aber auf dem Server gespeichert, auf dem Omeka installiert ist. Erst wenn Sie Ihre Eingaben dem Server übermitteln, in diesem Fall durch den Klick auf die Schaltfläche „Objekt hinzufügen“, sind sie dauerhaft gespeichert. Die Tabs am oberen Rand ermöglichen Ihnen allerdings, zu weiteren Eingabemasken zu wechseln, ohne dass die Eingaben in der aktuellen Maske verloren gehen. Sie könnten also alle relevanten Formulare ausfüllen und erst am Ende das Objekt hinzufügen.

Wir empfehlen Ihnen, das Objekt schon anzulegen, nachdem Sie nur das Feld „Name der Ressource“ ausgefüllt haben. Die weiteren Daten können Sie dann im Modus „Objekt bearbeiten“ (siehe unten) einpflegen. So können Sie Ihre Eingaben zwischendurch immer wieder speichern und riskieren nicht, dass durch den Wechsel auf eine andere Seite, etwa durch einen unbedachten Klick auf einen Menüpunkt wie „Ausstellungen“ alle Eingaben verloren gehen.


### Praxistipp: Staus "öffentlich"

In Omeka sind neu angelegte Objekte zunächst nicht öffentlich, wenn Sie nicht explizit im Kästchen „Öffentlich“ einen Haken setzen. Für die Besucher Ihrer Ausstellung werden die Objekte nur angezeigt, wenn ihnen der Status öffentlich zugewiesen wurde. Solange Sie als Nutzer im Backend eingeloggt sind, sehen Sie auch im Frontend diese nichtöffentlichen Objekte. Das kann verwirrend sein und ist eine potenzielle Fehlerquelle. Wir empfehlen deshalb, gleich beim Anlegen eines Objekts die Einstellung „öffentlich“ vorzunehmen. Sie entwickeln Ihre Ausstellung ohnehin auf einem nichtöffentlichen Redaktionssserver , die Veröffentlichung der Ausstellung, und damit auch der Objekte, erfolgt erst nach Fertigstellung durch Einbindung in das Portal der Deutschen Digitalen Bibliothek.

Objekte, die Sie anlegen, am Ende aber doch nicht in Ihrer Ausstellung verwenden, sind für den Nutzer nicht direkt zugänglich, weil sie an keiner Stelle ausgegeben werden. Theoretisch besteht allerdings die Möglichkeit, sie über die Veränderung der URL im Browser des Nutzers aufzurufen, indem deren numerische Komponente verändert wird: z.B. …/show/110 zu .../show/111 oder auf gut Glück …/show/346 Um dies auszuschließen, sollten Sie, bevor Ihre Ausstellung veröffentlich wird, nicht verwendete Objekte löschen oder nicht öffentlich (privat) setzen.


## B.2.2 Das Objekt mit Metadaten versehen

Zum Bearbeiten der Metadaten wählen Sie in der Rubrik „Objekte“ (Abb. 2.3, 1) das betreffende Objekt aus und klicken auf den Textlink „Bearbeiten“ (2).

Die virtuellen Ausstellungen der DDB arbeiten mit einem speziell zu diesem Zweck zusammengestellten Metadatenschema (s. Anhang Abschnitt C.1), das die notwendigen Angaben für unterschiedliche Objektkategorien wie Texte, Bilder, Filme, kunstgewerbliche Gegenstände etc. zusammenfasst, dem Objekttyp „VA DDB“. Die Werte mancher Felder werden bei der Ausgabe im Frontend direkt ausgeben, andere erzeugen nur einen Link oder dienen der Einbindung von Daten, etwa eines Vimeo-Videos. Nicht alle Felder müssen ausgefüllt werden; nicht ausgefüllte Felder werden bei der Ausgabe ignoriert.


!![Abb. B.2.3 Objekt bearbeiten][B-2-3]

Wechseln Sie auf der Seite „Objekt … bearbeiten“ (Abb. 2.4) auf den Tab „Metadaten des Objekttyps“ (1). In der Auswahlliste „Objekttyp“ wählen Sie den einzigen Eintrag „VA DDB“ aus (2) und füllen die Eingabefelder mit den Metadaten des Objekts. Hinweise zu den einzelnen Feldern finden Sie im Anhang (Abschnitt C.1). Sichern Sie anschließend Ihre Eingabe mit einem Klick auf das Bedienfeld „Änderungen übernehmen“. Nachdem Sie das Formular ausgefüllt haben, ist eine gute Gelegenheit, Ihre Eingaben mit „Änderungen übernehmen“ (4) erst einmal zu sichern.

!![Abb. B.2.4 Metadaten des Objekttyps auf der Seite „Objekt … bearbeiten“][B-2-4]

Leider gibt es in Omeka keine Möglichkeit, bei der Bearbeitung der Metadaten die schon vorgenommenen Eingaben zu speichern, ohne die Seite „Objekt … bearbeiten“ zu verlassen und auf die Seite „Objekt …“ zu gelangen (Abb. 2.5).

!![Abb. B.2.5 Seite "Objekt ..."][B-2-5]

m die Bearbeitung fortsetzen zu können, rufen Sie über die Schaltfläche „Bearbeiten“ (1) wieder die Seite „Objekt … bearbeiten“ auf und wählen dort den Tab „Metadaten des Objekttyps“ (vgl. Abb. 2.4). Das ist sicherlich etwas umständlich, die zwei Klicks sind aber gut investiert, und wir empfehlen dringend, bei komplexen Eingaben gelegentlich zwischenzuspeichern.

{{Aufgepasst: Speichern vor dem Wechsel}}

## B.2.3 Das Objekt mit Datein verknüpfen

### B.2.3.1 Verknüpfen mit einer Bild- oder Audiodatei

Sie können nun eine Datei mit dem Objekt verknüpfen. Wenn es sich um eine Bilddatei handelt, wird sie im Frontend als Vorschaubild und in der Lightbox im Großformat angezeigt. Verknüpfen Sie eine Audiodatei mit dem Objekt, erscheint auf der Ausstellungsseite ein entsprechendes Symbol, über das ein Audioplayer geöffnet wird, mit dem die Nutzer den Audioclip anhören können.
Angaben zu verwendbaren Bild- und Audio-Dateiformaten finden Sie im Anhang (XXX).

{{Aufgepasst: Bildateien vor dem Hochladen skalieren}}

!![Abb. B.2.6 Tab „Dateien“ der Seite „Objekt … bearbeiten“][B-2-6]

Zum Verknüpfen mit einer Datei wechseln Sie auf der Seite „Objekt … bearbeiten“ (Abb. 2.6) auf den Tab „Dateien“ (1) und wählen über die Schaltfläche „Durchsuchen“ (2) eine Datei auf Ihrem lokalen Datenträger aus.
Nachdem Sie die Änderungen übernommen haben (3), wird die verknüpfte Datei auf der Objektseite (Abb. 2.7) als Vorschaubild angezeigt. Wenn Sie nun wieder in den Modus „Bearbeiten“ wechseln (1), und dort zum Tab „Dateien“ wechseln (Abb. 2.8), erscheint der Name der verknüpften Datei in einem Drag-and-Drop-Balken mit Textlinks zum Bearbeiten und Löschen der Datei.


!![Abb. B.2.7 Objektseite mit Vorschaubild der verknüpften Datei][B-2-7]

{{Aufgepasst: Datei löschen ist nicht gleich Objekt löSpeichern}}

!![Abb. B.2.8 Tab „Dateien“ der Seite „Objekt … bearbeiten“ mit Textlink zum Bearbeiten der verknüpften Datei][B-2-8]

Über den Textlink „Bearbeiten“ (2) haben Sie die Möglichkeit, die Datei mit Metadaten zu versehen, wobei als Metadatenschema Dublin Core fest vorgegeben ist (Abb. 2.9). Diese Metadaten werden in der Ausgabe nicht berücksichtigt, Sie können sie aber für interne Zwecke nutzen.

!![Abb. B.2.9 Die Seite Datei … bearbeiten][B-2-9]


### B.2.3.2 Verknüpfung mit einer Videodatei

Omeka sieht auch die Möglichkeit vor, Videodateien direkt mit einem Objekt zu verknüpfen. Die Einbindung des Videos erfolgt nicht als Datei, sondern über ein Metadatenfeld, das lediglich den Link zum Vimeo-Video enthält.

In einem ersten Schritt laden Sie dazu Ihre Videodateien bei Vimeo hoch. Sie stellen dazu die Videos in den Vimeo-Kanal der Deutschen Digitalen Bibliothek{FN: https://vimeo.com/user14807229.} ein. Wenden Sie sich dazu bitte an Ihren Ansprechpartner bei der Deutschen Digitalen Bibliothek.

Die Verknüpfung mit dem Objekt erfolgt über nun über das Metadatenfeld „Videoquelle“ des Objekttyps VA DDB (vgl. Abb. 2.4), wo ein „Shortcode“ eingetragen wird (Abb. 2.10).


!![Abb. B.2.10 Einbindung eines Vimeo-Videos über das Metadatenfeld „Videoquelle“][B-2-10]

Der Shortcode enthält die für die Einbindung des Videos notwendigen Angaben in einer formalisierten Syntax. Die doppelten eckigen Klammern „[[ … ]]“ definieren die Zeichenfolge als Shortcode, „video:“ gibt den Medientyp und „vimeo:“ die Plattform an, die anschließende Ziffernfolge die Vimeo-ID des betreffenden Videos. Die Vimeo-ID teilt Ihnen Ihr Ansprechpartner nach erfolgreichem Hochladen Ihrer Videodatei in den Video-Kanal der Deutschen Digitalen Bibliothek mit. Es ist entscheidend, dass Sie die korrekte Vimeo-ID eintragen. Sie finden diese auch, wenn Sie Ihr Video auf Vimeo anschauen. Die Vimeo-ID wird im Player unten rechts angegeben (Abb. 2.11).

!![Abb. B.2.11 Die Vimeo-ID des Videos][B-2-11]

Der Shortcode setzt sich folgendermaßen zusammen:
[[ + video: + vimeo: + ID + ]] also bei unserem Beispiel:
[[video:vimeo:115160867]]
Wenn Sie YouTube-Videos in Ihre virtuelle Ausstellung einbinden möchten, wenden Sie sich bitte an Ihren Ansprechpartner bei der Deutschen Digitalen Bibliothek.

### B.2.3.3 Objekt mit mehreren Dateien verknüpfen

Omeka sieht vor, dass Objekte mit beliebig vielen Dateien verknüpft werden können. Nun wird in der Frontend-Darstellung auf den Ausstellungsseiten immer nur eine Datei angezeigt. Erst wenn der Nutzer das Objekt in der Lightbox aufruft, werden auch die weiteren Abbildungen ausgegeben. In Ausnahmefällen kann das sinnvoll sein, normalerweise sollten aber alle gezeigten Abbildungen auf den Ausstellungsseiten selbst erscheinen. Wollen Sie also beispielsweise mehrere Seiten eines Dokuments anzeigen, legen Sie für jede Seite ein eigenes Objekt an und verknüpfen diese mit den entsprechenden Grafikdateien.

Es besteht aber die Möglichkeit, solche Objekte außerhalb des Layout-Rahmens der Ausstellung in einem „Bookviewer“ anzeigen zu lassen, der das Blättern durch die verschiedenen Seiten eines Dokuments, die Blätter einer Grafikfolge etc. ermöglicht. So ist auf der Seite „Der Mythenerzähler Rosendo“ der Ausstellung „Zu Mythen und Monumenten“ (s.u. Abb. 4.10) im ersten grauen Kasten der rechten Sidebar ein Link zu einer Bookviewer-Darstellung eines Reisenotizbuchs von Konrad Theodor Preuss gesetzt. Der Bookviewer öffnet sich in einem neuen Fenster, das er ganz ausfüllt. Der Nutzer kann hier die Seiten des Heftes durchblättern und sich so das gesamte umfangreiche Dokument anschauen (Abb. 2.12).


!![Abb. B.2.12 Bookviewer-Ansicht eines mehrseitigen Dokuments][B-2-12]

Legen Sie für ein Konvolut, das sie mit dem Bookviewer darstellen möchten, immer ein eigenes Objekt an, auch wenn Sie beispielsweise einzelne Blätter bereits als Objekt angelegt haben.

Nachdem Sie im Tab „Dateien“ das Objekt mit einer ersten Datei verknüpft haben, können Sie im Kasten „Neue Daten hinzufügen“ die nächste Abbildung einbinden (Abb. 4.13, 1). Über die Schaltfläche „Weitere Dateien hinzufügen“ (2) erzeugen Sie einen neuen „Durchsuchen…“ Button für die nächste Grafik-Datei.


!![Abb. B.2.13 Hinzufügen weiterer Dateien zu einem Objekt][B-2-13]

Der letzte Schritt ist nun, einen Link zu erzeugen, mit dem Sie den Bookviewer mit diesem Objekt aufrufen können. Bei dem genannten Beispiel aus der Ausstellung „Zu Mythen und Monumenten“ (vgl. Abb. 4.12) sieht der Link in der Adresszeile Ihres Browsers folgendermaßen aus:
http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/viewer/show/177#page/n0/mode/2up

{{Aufgepasst: Haben Sie Geduld beim Upload}}

Aus dieser absoluten URL machen wir eine relative, die generisch auf die Domain bezogen ist, auf der Ihre virtuelle Ausstellung läuft. Das macht die URL nicht nur kürzer, sondern stellt auch sicher, dass der Link auch nach dem Umzug vom Entwicklungsserver auf das Portal der Deutschen Digitalen Bibliothek noch funktioniert.
 
Die URL lautet nun:
/preuss/viewer/show/177#page/n0/mode/2up
Sie setzt sich aus den folgenden Bestandteilen zusammen:
/preuss – des slug der Ausstellung (vgl. Abschnitt 3. Eine Ausstellung anlegen)
/viewer/show – ruft den Bookviewer auf
/177 – die ID des Objekts; wenn Sie das Objekt bearbeiten, erscheint die ID immer oben hinter einem „#“
#page – ruft die Seite auf
/n0 – die aktuelle angezeigte Seite (hier die erste der Folge)
/mode – definiert den Darstellungsmodus
/2up – wählt den Modus mit zwei Seiten, die sich horizontal durchblättern lassen.
Die URL besteht also aus fixen und variablen Bestandteilen. Um eine passende URL zu erzeugen, fügen Sie die variablen Komponenten mit den fixen nach dem vorgegebenen Schema zusammen. Variabel sind:
der Slug der Ausstellung
die ID der Ausstellung
die beim Aufruf aufzuschlagende Seite (in der Regel die erste, also n0)
der Darstellungsmodus
Die Optionen für den Darstellungsmodus sind:
1up – eine Seite gleichzeitig, Blättern/Scrollen nach unten
2up – zwei Seiten nebeneinander, Blättern mit Blätteranimation horizontal
thumb – Thumbnailgalerie mit allen Seiten des Dokuments
Die Nutzer können, unabhängig von Ihren Voreinstellungen, über die Icons am unteren Rand des Bookviewers zwischen diesen Modi jederzeit wechseln.
Hier noch einmal die Syntax der URL mit fixen (blau) und variablen (orange) Bestandteilen:
/ [Slug der Ausstellung] / viewer/show / [Objekt-ID] #page / [Nr. Seite] / mode / [Modus]
Wenn Ihr Objekt im Bestand der Deutschen Digitalen Bibliothek bereits in einer Bookviewer-Ansicht verfügbar ist (wie z.B. https://portal.dnb.de/bookviewer/view/1017345589#page/n0/mode/2up), genügt es, auf diese Ansicht zu verlinken.

### B.2.3.4 3D-Objekte einbinden

Neben Bildern, Audiodateien und Videos können Sie auch 3D-Objekte in Ihre Ausstellung einbinden. Ein Beispiel finden Sie in der virtuellen Ausstellung zur Geschichte Karlsruhes auf Seite 11 (http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/exhibits/show/vom-privilegienbrief-zum-bundesverfassungsgericht/karl-drais---erfinder-des-zweirads ).

!![Abb. B.2.14 Der Player zur Anzeige eines 3D-Objekts in der Lightbox][B-2-14]

Ein Klick auf das Laufrad (oben rechts) öffnet die Lightbox mit einem 3D-Viewer{FN: Die Deutsche Digitale Bibliothek setzt den X3DOM-Viewer des Fraunhofer-Instituts für Graphische Datenverarbeitung ein, s. http://www.x3dom.org/.}, in dem sich das historische Objekt bzw. sein 3D-Modell von allen Seiten betrachten lässt{Eine Übersicht (auf Englisch) der im 3D-Viewer verfügbaren Navigationsbefehle finden Sie unter http://x3dom.org/download/1.5.1/docs/html/navigation.html.}.
Für das Einfügen von 3D-Dateien steht auf der Seite „Objekt … bearbeiten“ ein eigener Tab zur Verfügung (Abb. 2.15, 1). „X3D“ bezeichnet das erforderliche Format der 3D-Dateien (Informationen zu diesem Format und der erforderlichen Software zur Erstellung von X3D-Modellen siehe http://www.web3d.org).

!![Abb. B.2.15 3D-Objekte einbinden][B-2-15]

Ein Klick auf das Laufrad (oben rechts) öffnet die Lightbox mit einem 3D-Viewer , in dem sich das historische Objekt bzw. sein 3D-Modell von allen Seiten betrachten lässt .
Für das Einfügen von 3D-Dateien steht auf der Seite „Objekt … bearbeiten“ ein eigener Tab zur Verfügung (Abb. 2.15, 1). „X3D“ bezeichnet das erforderliche Format der 3D-Dateien (Informationen zu diesem Format und der erforderlichen Software zur Erstellung von X3D-Modellen siehe http://www.web3d.org).

## B.2.4 Objekte suchen

Omeka bietet Ihnen mehrere Möglichkeiten, ein bestimmtes Objekt in der Liste der angelegten Objekte schnell und komfortabel zu finden. Nach Aufruf der Seite „Objekte durchsuchen“ über die Rubrik „Objekte“ (Abb. 2.16, 1) gibt Omeka die Objektliste auf einer einzigen Seite aus, geordnet nach Erstellungsdatum. Das zuletzt hinzugefügte Objekt erscheint an erster Stelle der Liste. Sie können die Sortierreihenfolge durch einen Klick auf den Spaltentitel „hinzugefügt am“ (a) umkehren (ältestes Objekt oben). Ein Klick auf den Titel der ersten Spalte „Titel“ (b) sortiert die Liste nach Objekttiteln, ein weiterer Klick kehrt die Reihenfolge um (A bis Z, Z bis A).

!![Abb. B.2.16 Die Objektliste][B-2-16]

Bei umfangreichen Listen mit Objekten, die sich nicht leicht auseinanderhalten lassen, kann es sinnvoll sein, die differenzierte Objektsuchfunktion von Omeka zu verwenden. Das Suchformular (Abb. 2.17) rufen Sie über die Schaltfläche „Objekt suchen“ (Abb. 2.12, 2) auf.

!![Abb. B.2.17 Die Suchmaske der Objektsuche][B-2-17]

Geben Sie in eines der Felder einen Suchbegriff ein (1) und klicken Sie auf die Schaltfläche „Objekte suchen“ (2) ganz am Ende des Suchformulars. Für uns sind nur die ersten drei Suchfelder von Belang. Meist genügt die Stichwortsuche (a), um das Objekt zu finden. Die Suchfunktion „Über bestimmte Felder eingrenzen“ (b, c) ermöglicht eine fein differenzierte Suche nach einzelnen Metadatenfeldern (b) und mit logischen Operatoren wie „enthält“ oder „ist leer“ (c). Manchmal kann es sinnvoll sein, direkt nach der Omeka-ID des Objekts zu suchen (d). Im Backend ist sie im Titel der Seite „Objekt … bearbeiten“ mit einer Raute angegeben (z.B. „Objekt #45 bearbeiten“), im Frontend erscheint sie als Ziffernfolge am Ende der URL der Objekt-Detailseite (z.B. …/items/show/45).

[B-2-1]: img/Abb_B-2-1-Rubrik-Objekte.png "Abb. B.2.1 Die Rubrik Objekte"
[B-2-2]: img/Abb_B-2-2-Seite-Objekt-hinzufügen.png "Abb. B.2.2 Seite Ein Objekt hinzufügen"
[B-2-3]: img/Abb_B-2-3-Objekt-bearbeiten.png "Abb. B.2.3 Objekt bearbeiten"
[B-2-4]: img/Abb_B-2-4-Meatdaten-Obejtktyp.png "Abb. B.2.4 Metadaten des Objekttyps auf der Seite Objekt … bearbeiten"
[B-2-5]: img/Abb_B-2-5-Seite-Objekt.png "Abb. B.2.5 Seite Objekt ..."
[B-2-6]: img/Abb_B-2-6-Tab-Dateien.png "Abb. B.2.6 Tab Dateien der Seite Objekt … bearbeiten"
[B-2-7]: img/Abb_B-2-7-Objektseite.png "Abb. B.2.7 Objektseite mit Vorschaubild der verknüpften Datei"
[B-2-8]: img/Abb_B-2-8-Tab-Dateien-Objekt-bearbeiten.png "Abb. B.2.8 Tab Dateien der Seite Objekt … bearbeiten mit Textlink zum Bearbeiten der verknüpften Datei"
[B-2-9]: img/Abb_B-2-9-Seite-Datei-bearbeiten.png "Abb. B.2.9 Die Seite Datei … bearbeiten"
[B-2-10]: img/Abb_B-2-10-Einbindung-Vimeo-Video.png "Abb. B.2.10 Einbindung eines Vimeo-Videos über das Metadatenfeld Videoquelle"
[B-2-11]: img/Abb_B-2-11-Vimeo-ID.png "Abb. B.2.11 Die Vimeo-ID des Videos"
[B-2-12]: img/Abb_B-2-12-Bookviewer-Ansicht.png "Abb. B.2.12 Bookviewer-Ansicht eines mehrseitigen Dokuments"
[B-2-13]: img/Abb_B-2-13-Hinzufügen-weiterer-Dateien.png "Abb. B.2.13 Hinzufügen weiterer Dateien zu einem Objekt"
[B-2-14]: img/Abb_B-2-14-3D-Player.png "Abb. B.2.14 Der Player zur Anzeige eines 3D-Objekts in der img/Abb. B.2.15 3D-Objekte einbinden"
[B-2-15]: img/Abb_B-2-15-3D-Objekte-einbinden.png "Abb. B.2.15 3D-Objekte einbinden"
[B-2-16]: img/Abb_B-2-16-Objektliste.png "Abb. B.2.16 Die Objektliste"
[B-2-17]: img/Abb_B-2-17-Suchmaske.png "Abb. B.2.17 Die Suchmaske der Objektsuche"
