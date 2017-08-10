## B.4 Ausstellungsseiten anlegen

### B.4.1 Seite anlegen

Nun beginnt der kreative Teil der Ausstellungsgestaltung: das Anlegen der Ausstellungsseiten. Um eine Seite anzulegen (zu der bereits vorhandenen Seite „Inhalt der Ausstellung“ siehe unten Abschnitt B.4.4.5), klicken Sie unterhalb der Eingabemaske für die Metadaten der Ausstellung auf die Schaltfläche „Neue Seite hinzufügen“ (Abb. B.4.1, <span class="red-circle">1</span>).

!![Abb. B.4.1 „Seite hinzufügen“ auf der Seite „Ausstellung …“][B-4-1]

Auf der Seite „Seite hinzufügen“ gelangen Sie zunächst zu einer Eingabemaske für die Metadaten der Ausstellungsseite (Abb. B.4.2). Der Titel (<span class="red-circle">1</span>) erscheint in der Frontend-Ausgabe links oben über den Inhalten der Seite, direkt unter der grafischen Seitennavigation. Im Feld „Slug“ (<span class="red-circle">2</span>) geben Sie die Zeichenfolge an, die am Ende der URL erscheinen soll, wenn ein Nutzer die Ausstellungsseite in seinem Browser aufruft. Bitte beachten Sie unbedingt die Regeln und Konventionen, die wir im Abschnitt zu den Metadaten der Ausstellung erläutert haben (Abschnitt 3). Es empfiehlt sich, hier aussagekräftige Begriffe zu verwenden, um die Auffindbarkeit der Inhalte für Suchmaschinen zu optimieren. Sie können dieses Feld auch leer lassen, dann erstellt Omeka, sobald sie „Änderungen übernehmen“ klicken (<span class="red-circle">3</span>) einen Slug aus dem Titel der Seite, den Sie bei Bedarf später anpassen können.

!![Abb. B.4.2 Die Metadaten der Ausstellungsseite - Titel und Slug ][B-4-2]

Das Feld „Widget Content“ (Abb. B.4.3, <span class="red-circle">1</span>) bietet Ihnen die Möglichkeit, in der rechten Sidebar der Ausstellungsseite einen Kasten mit Inhalten zu platzieren. Er erscheint über dem ersten Inhaltswidget der Ausstellung und ggf. über dem zweiten Inhaltswidget (vgl. Abb. A.2, d).

Gedacht ist dieser Bereich für Querverlinkungen und weiterführende Informationen. Für alle wesentlichen Informationen verwenden Sie bitte den Inhaltsbereich der Seite.

Die Grafik, die Sie über „Vorschaubilder-Ansicht für die Seitennavigation“ auswählen (<span class="red-circle">2</span>), erscheint als Vorschaubild in der grafischen Navigation über den Inhalten der Seite (vgl. Abb. A.1, b). Die erforderlichen Abmessungen von 92 x 71 Pixel sind im Formular angegeben; als Dateiformate sind .jpg und .png möglich. Für das Erscheinungsbild und die Funktionalität der Ausstellung zahlt es sich aus, diese Vorschaubilder sorgfältig zu gestalten. Der gewählte Ausschnitt (in der Regel: einer Abbildung von der betreffenden Seite) sollte attraktiv, aussagekräftig und einprägsam sein.

!![Abb. B.4.3 Die Metadaten der Ausstellungsseite - Widget Content und Vorschaubild][B-4-3]

Nun wählen Sie ein Seitenlayout für Ihre Ausstellungsseite aus (<span class="red-circle">3</span>). Welche Optionen Ihnen dabei zur Verfügung stehen, erläutern wir ausführlich im nachfolgenden Abschnitt. Abschließend speichern Sie Ihre Eingaben über die Schaltfläche „Änderungen übernehmen“ (<span class="red-circle">4</span>).

### B.4.2 Die Layouts für Ausstellungsseiten

Wie wir in Abschnitt A gesehen haben (vgl. Abb. A.7), bietet Ihnen das die Ausstellungs-Software der Deutschen Digitalen Bibliothek eine Palette von Layouts, die Objekte und Textblöcke auf unterschiedliche Weise miteinander kombinieren.

Bei der Planung Ihrer Ausstellung können Sie sich an den Seiten der bestehenden [virtuellen Ausstellungen der Deutschen Digitalen Bibliothek](https://www.deutsche-digitale-bibliothek.de/content/ausstellungen) orientieren. Sie vermitteln einen guten Eindruck über die Möglichkeiten der einzelnen Layout-Optionen.

Im Folgenden ein kurzer Überblick über die acht verfügbaren Layouts.

##### Layout 1: Seite mit Bild rechts und Vorschaubildern

Dieses Layout (Abb. B.4.4) kombiniert Text in der linken Spalte mit einer Zusammenstellung von Objekten in der rechten Spalte. Bei den Objekten ist das erste Objekt hervorgehoben. Es (genau genommen: das dem Objekt zugeordnete Bild) erscheint spaltenbreit und in seinen Originalproportionen. Darunter wird eine Galerie mit weiteren Objekten angezeigt. Die Bilder dieser Galerie-Objekte werden von Omeka automatisch zu kleinen quadratischen Vorschaubildern skaliert und beschnitten. Die Bilder sind in Zeilen von drei Vorschaubildern angeordnet. Sie können maximal zwölf Galerie-Objekte pro Seite einstellen. 


!![Abb. B.4.4 Layout 1 – Seite mit Bild rechts und Vorschaubildern][B-4-]

Klicken die NutzerInnen auf eines der Objekte, öffnet sich die Lightbox mit einer Großansicht des Bildes bzw. einem Audio- oder Video-Player (vgl. Abb. A.5). Das Verhalten von Haupt- und Galerieobjekten ist – und das gilt für alle Layouts – in dieser Hinsicht identisch.

Layout 1 bietet zudem die Möglichkeit, die rechte Spalte mit Text zu versehen. Er erscheint dann unterhalb der Objekte. Bei größeren Textmengen können Sie so zweispaltige Textlayouts realisieren. Was dabei zu beachten ist, werden wir in Abschnitt 4.5 erläutern.

Für alle Layouts gilt: Sie können Elemente auslassen, die Frontend-Ausgabe passt sich dann automatisch an, es entstehen also keine „Lücken“. Verzichten Sie z. B. auf das Hauptbild, erscheint in der rechten Spalte nur die Objekt-Galerie. 

##### Layout 2: Seite mit Bild rechts und Vorschaubildern als Karussell

Von Layout 1 unterscheidet sich Layout 2 (Abb. B.4.5) lediglich durch die Form, in der die Galerie-Objekte dargestellt werden. Unter dem Hauptbild erscheinen immer maximal drei quadratische Vorschaubilder. Sind weitere Objekte in der Galerie vorhanden, können die NutzerInnen über die Pfeile links und rechts der Galerie den ‚Filmstreifen‘ um je drei Bilder weiter bzw. zurückschieben. Auch hier ist die Anzahl der Galerie-Objekte auf zwölf limitiert.

!![Abb. B.4.5 Layout 2 - Seite mit Bild rechts und Vorschaubildern als Karussell][B-4-5]

##### Layout 3: Vorschaubilder-Galerie mit optionalem Text oben und unten

Ein reines Galerie-Format bietet Layout 3 (Abb. B.4.6). Bis zu 24 Objekte erscheinen hier in Zeilen zu maximal sechs quadratischen Vorschaubildern nebeneinander. Über und unter dieser Galerie kann jeweils zweispaltiger Text eingefügt werden. Zu den Besonderheiten des zweispaltigen Textlayouts siehe unten, Abschnitt 4.5.

!![Abb. B.4.6 Layout 3 – Vorschaubilder-Galerie mit optionalem Text oben und unten][B-4-6]

##### Layout 4: Seite mit Bildern links

Bei den bisher vorgestellten Layouts waren die Seiten aus in sich geschlossenen Text- und Objektblöcken aufgebaut. Layout 4 (Abb. B.4.7) ermöglicht Ihnen, jedem gezeigten Objekt je einen Text zuzuordnen. In diesem Fall erscheint das Objekt in der linken, der zugehörige Text in der rechten Spalte. Wie sich das auf die Gewichtung von Text zu Bild auswirkt, können Sie unter Layout 6 detaillierter nachlesen. 

Nehmen die Texte weniger Raum ein, als die Höhe der Abbildung vorgibt, entsteht Weißraum unter dem Text (siehe das abgebildete – fiktive – Beispiel). Damit bekommt der Text eher den Charakter einer erweiterten Bildlegende oder eines Kommentars zur Abbildung. Sollten Sie Wert auf ein geschlossenes Seitenlayout legen, müssen Sie hier Textlängen und Bildgrößen aufeinander abstimmen.

Ist der Text umfangreicher, rücken umgekehrt die Objekte in der linken Spalte auseinander. 

!![Abb. B.4.7 Layout 4 – Seite mit Bildern links][B-4-7]

##### Layout 5: Seite mit Bildern abwechselnd links und rechts

Was die Zuordnung von Objekt und Text angeht, folgt Layout 5 (Abb. B.4.8) dem gleichen Prinzip wie Layout 4, nur, dass mit jedem eingebundenen Objekt die Position von Objekt und Text zwischen links und rechts wechselt. Ist hier der Text zu einem Objekt sehr viel kürzer oder länger als der neben dem Objekt zur Verfügung stehende Raum vorgibt, entsteht ein ausgesprochen unruhiges Erscheinungsbild der Seite. Wir empfehlen dieses Layout nur zu verwenden, wenn Proportionen der Objektabbildungen und die Längen der Beschreibungstexte relativ einheitlich sind bzw. wenn Sie in der Lage sind, beide aufeinander abzustimmen.

!![Abb. B.4.8 Layout 5 – Seite mit Bildern abwechselnd links und rechts][B-4-8]

##### Layout 6: Seite mit Bildern rechts

Layout 6 (Abb. B.4.9) unterscheidet sich von Layout 4 nur durch die Position der Objekte, die hier auf der rechten Seite erscheinen. Texte und Objekte sind auch hier einander direkt zugeordnet. In Anbetracht der für europäische Sehgewohnheiten üblichen Leserichtung von links nach rechts kann man davon ausgehen, dass der links positionierte Text für den Nutzer hier dominanter ist als bei Layout 4. Wenn Sie also, was bei dem gezeigten Beispiel inhaltlich der Fall ist, einen Text mit Abbildungen versehen wollen, bietet sich Layout 6 an. Wenn dagegen Abbildungen durch Texte erläutert werden sollen, ist das Schema von Layout 4 vielleicht etwas besser geeignet.

!![Abb. B.4.9 Layout 6 – Seite mit Bildern rechts][B-4-9]

##### Layout 7: Seite mit großen, fortlaufenden Bildern rechts

Wie bei Layout 1 und 2 sind auch bei Layout 7 (Abb. B.4.10) die Textblöcke in sich geschlossen und nicht unmittelbar auf die einzelnen, in der rechten Spalte angezeigten Objekte bezogen. Alle Objekte werden hier gleichrangig dargestellt, sie erscheinen spaltenbreit in den Originalproportionen der zugehörigen Bilder. 

!![Abb. B.4.10 Layout 7 – Seite mit großen, fortlaufenden Bildern rechts][B-4-10]

Auch bei Layout 7 besteht die Möglichkeit, Texte in der rechten Spalte unterhalb der Objekte zu platzieren.

##### Layout 8: Seite mit kleinen, fortlaufenden Bildern rechts

Demselben Prinzip wie Layout 7 folgt Layout 8 (Abb. B.4.11), mit dem Unterschied, dass hier die Objekt-Abbildungen etwas kleiner dargestellt werden. Das betrifft vor allem Hochformate, die bei spaltenbreiter Darstellung sonst recht viel Platz einnehmen würden. 

!![Abb. B.4.11 Layout 8 – Seite mit kleinen, fortlaufenden Bildern rechts][B-4-11]

### B.4.3 Inhalte einstellen

Nach der Auswahl eines Layouts (Abb. B.4.2, <span class="red-circle">XXX</span>) und dem Speichern über „Änderungen übernehmen“ wechselt die Ansicht auf die Seite „Inhalt der Seite … bearbeiten“ (Abb. 4.11). Hier können Sie die einzelnen Inhaltsbereiche befüllen. Texte – Textblöcke, Bildlegenden, Zwischenüberschriften für zweispaltige Texte – geben Sie direkt in die entsprechenden Felder ein, Objekte wählen Sie über die Schaltflächen „Objekt hinzufügen“ aus. Leere Inhaltselemente werden bei der Ausgabe im Frontend ignoriert. Sie können also etwa nur einen Text einstellen und auf die Einbindung von Objekten verzichten oder bei Layout 1 (vgl. Abb. 4.3) das Hauptbild oder die Bildergalerie weglassen.

Für die Texteingabe steht Ihnen ein Editor zur Verfügung (Abb. 4.12), mit dem Sie Ihre Texte formatieren können. Über die Bedien-Elemente am oberen Rand (a) über dem Texteingabefeld (b) können Sie u. a. 
* Überschriften in verschiedenen Hierarchiestufen vergeben (Überschrift 1-6), 
* Fett- und Kursiv-Satz vornehmen, 
* Listen erstellen und 
* externe oder interne Links setzen. 
Über die genauen Formatierungsmöglichkeiten informiert Abschnitt XXX im Anhang.


Für die Texteingabe steht Ihnen ein Editor zur Verfügung (Abb. 4.13), mit dem Sie Ihre Texte formatieren können. Über die Bedienelemente am oberen Rand (<span class="red-circle">a</span>) über dem Texteingabefeld (<span class="red-circle">b</span>) können Sie u.a. Überschriften in verschiedenen Hierarchiestufen vergeben (Überschrift 1-4), Fettungen und Kursivsetzungen vornehmen, Listen erstellen und externe oder interne Links setzen. Über die genauen Formatierungsmöglichkeiten informiert Abschnitt XXX im Anhang.

!![Abb. B.4.13 Der Texteditor][B-4-13]

Das Einfügen eines Objekts erfolgt über die Schaltfläche „Objekt hinzufügen“ (Abb. B.4.14, <span class="red-circle">a</span>) des jeweiligen Inhaltselements. Zum Auswählen des Objekts öffnet sich das Dialogfenster „Objekt hinzufügen“ (Abb. B.4.15).

!![Abb. B.4.14 Objekt hinzufügen][B-4-14]
!![Abb. B.4.15 Dialogfenster „Objekt hinzufügen“][B-4-15]

Sie können die Liste aller Objekte durchblättern, um das gewünschte Objekt auszuwählen und über die Schaltfläche „Ausgewähltes Objekt hinzufügen“ in die Ausstellungsseite einzubinden.

Nach dem Einfügen des Objekts ist die Anzeige des Objekt-Inhaltselements erweitert (Abb. 4.14). Oben links erscheint der Titel des Objekts und ein Vorschaubild (a). Darunter bietet ein Editor die Möglichkeit, eine Bildunterschrift einzufügen (b). Wenn Sie das Objekt von Ihrer Ausstellungsseite wieder entfernen möchten, klicken Sie auf die Schaltfläche „Dieses Objekt entfernen“ (c). Vorsicht: Das Objekt wird sofort und endgültig von dieser Ausstellungsseite gelöscht, ohne dass Sie noch einmal um eine Bestätigung gebeten werden.

Nach dem Einfügen des Objekts ist die Anzeige des Objekt-Inhaltselements erweitert (Abb. B.4.16). Oben links erscheint der Titel des Objekts und Vorschaubild (<span class="red-circle">a</span>). Darunter bietet ein Editor die Möglichkeit, eine Bildunterschrift (Legende) einzufügen (<span class="red-circle">b</span>). Wenn Sie das Objekt von Ihrer Ausstellungsseite wieder entfernen möchten, klicken Sie auf die Schaltfläche „Dieses Objekt entfernen“ (<span class="red-circle">c</span>). Vorsicht: Das Objekt wird sofort und endgültig gelöscht, ohne dass Sie noch einmal um eine Bestätigung gebeten werden.

!![Abb. B.4.16 Inhaltselement Objekt – hier ein Hauptbild][B-4-16]

!!!note "Bildlegenden werden nur bei Hauptbildern ausgegeben"

    Omeka sieht für jedes eingebundene Objekt die Möglichkeit vor, eine Bildlegende einzugeben. In der Frontend-Ausgabe werden allerdings nur bei Hauptbildern diese Bildlegenden auch angezeigt, bei allen Vorschaubildern werden sie auf den Ausstellungsseiten einfach ignoriert. Hauptbilder sind Objekte, deren verknüpfte Dateien (also in der Regel die Abbildung des Objekts) in den Originalproportionen, nicht als quadratisches Vorschaubild angezeigt werden. Ist eine Bildlegende vorhanden, wird sie im Textfeld der Lightbox (s. Abb. A.4) unter dem Objekttitel angezeigt.

Nachdem Sie alle Texte eigegeben und alle Objekte eingebunden haben, sollten Sie sich das Ergebnis im Frontend anschauen. Speichern Sie dazu Ihre Eingaben zunächst über die Schaltfläche „Änderungen übernehmen“ (Abb. B.4.16, <span class="red-circle">1</span>) ab, und klicken dann auf die Schaltfläche „Seite anzeigen“ (<span class="red-circle">2</span>). Es öffnet sich ein neuer Browser-Tab mit der Frontend-Darstellung Ihrer Ausstellungsseite.

Denken Sie bitte auch daran, die Ausgaben zu den Objekten zu überprüfen, die in der Lightbox erscheinen. Klicken Sie dazu auf das erste Objekt der Seite und blättern in der Lightbox alle Objekte durch. Zu jedem Objekt sollten Sie vor der Veröffentlichung auch die Angaben Korrektur lesen, die sich hinter dem ©-Icon der Lightbox verbergen.

##### Praxistipp: Frontend-Tabs immer wieder schließen

Wenn Sie von der Frontend-Darstellung ins Omeka-Backend zurückwechseln, Änderungen an der Seite vornehmen, diese abspeichern (2) und wieder auf „Öffentliche Seite anzeigen“ (3) klicken, öffnet sich ein neuer, weiterer Browser-Tab mit der aktualisierten Vorschau. Nach einer Reihe von Wiederholungen verlieren Sie leicht den Überblick, welche Frontend-Darstellung dem aktuellen Stand Ihrer editorischen Arbeit entspricht. Wir empfehlen deshalb, den Vorschau-Tab immer gleich wieder zu schließen, nachdem Sie die Frontend-Ausgabe überprüft haben.

Sie können nach Abschluss Ihrer Arbeiten an der aktuellen Seite einfach eine neue Seite anlegen, indem Sie auf die Schaltfläche „Speichern und Seite hinzufügen“ (Abb. 4.11, 4) klicken. Oder Sie wechseln auf die Ausstellungsseite zurück – am einfachsten durch einen Klick auf den Ausstellungstitel in der Breadcrumb-Navigation am oberen Rand des Formulars – und fügen neue Seiten hinzu, wie bei der ersten Seite über die Schaltfläche „Seiten hinzufügen“ (Abb. 4.1, 1).

### B.4.4 Seiten arrangieren und bearbeiten

#### B.4.4.1 Änderung der Reihenfolge

Die von Ihnen bereits angelegten Seiten erscheinen auf der Seite „Ausstellung …“ als beigefarbene, mit dem Seitentitel beschriftete Balken. Mit diesen Balken können Sie die Anordnung Ihrer Seiten ganz einfach und intuitiv per „Drag & Drop“ anpassen. 
Fahren Sie dazu mit dem Mauszeiger über den Balken der betreffenden Seite (nicht über den Titel oder das „x“). Der Zeiger Ihrer Maus ändert sich dabei von einem einfachen Pfeil zu einem Vier-Wege-Pfeil. Halten Sie nun die linke Maustaste gedrückt, können Sie den Balken verschieben (Abb. 4.15, 1). 

!![Abb. B.4.15 Sortieren der Ausstellungsseiten durch Drag and Drop][B-4-15]

Positionieren Sie den Balken an die gewünschte Stelle und geben die linke Maustaste wieder frei. Die geänderte Reihenfolge wird nun angezeigt – Sie haben die Seiten umsortiert. Diese Änderungen werden allerdings erst übernommen, wenn Sie Ihre Ausstellung speichern. Vergessen Sie also nicht, nach dem Umsortieren auf die Schaltfläche „Änderungen übernehmen“ (2) zu klicken.

!![Abb. B.4.17 Sortieren der Ausstellungsseiten durch Drag and Drop][B-4-17]

#### B.4.4.2 Seiten Löschen

Um eine Seite aus Ihrer Ausstellung zu entfernen, können Sie in der der Seitenliste auf das „x“ am rechten Rand des entsprechenden Balkens klicken (Abb. 4.17, a - 1). Die Seite ist dann zum Löschen vorgemerkt – der Balken ist nun braun hinterlegt und aus dem „x“ ist ein Rückgängigmachen-Pfeil geworden (b). Erst nachdem Sie Ihre Eingaben mit „Änderungen übernehmen“ (2) gespeichert haben, wird die Seite – dann allerdings unwiderruflich – gelöscht und der Balken verschwindet aus der Liste. Wenn Sie im braunen Balken auf das Pfeilsymbol klicken oder die Seite „Ausstellung …“ verlassen, ohne gespeichert zu haben, bleiben die zur Löschung vorgemerkten Seiten erhalten.

!![Abb. B.4.18 Seiten aus der Seitenliste löschen][B-4-18]

#### B.4.4.3 Änderungen auf bestehenden Seiten

Als webbasiertes Content-Management-System ist die Ausstellungs-Software sehr flexibel, was den Workflow bei der Erstellung von virtuellen Ausstellungen angeht. Sie können die Ausstellung Seite für Seite erarbeiten oder beispielsweise erst alle Seiten anlegen und diese später und in beliebiger Reihenfolge mit Objekten und Texten befüllen. Und selbstverständlich bleiben alle Inhalte bis zur Veröffentlichung auf der Website der Deutschen Digitalen Bibliothek editierbar. 

Solange Sie bestehende Seiteninhalte editieren oder neue hinzufügen, gelten die Hinweise, die wir im Kapitel „Inhalte einstellen“ gegeben haben.

Leider bietet die Software kein einfaches Verfahren, um die Anordnung der Objekte auf der Seite zu verändern, also etwa ein Galeriebild zum Hauptbild zu machen, die Reihenfolge der Galeriebilder anzupassen oder ein neues Galeriebild zwischenzuschieben. Anzahl und Anordnung der Inhaltselemente (vgl. Abb. 4.20, die in blauen Kästchen durchnummerierten Boxen) ist fix, Sie können Sie nur mit Objekten belegen oder diese entfernen.

Um es an einem Beispiel zu verdeutlichen: Wenn Sie in einer Galerie mit 7 Objekten an Stelle 4 ein neues Objekt einfügen möchten, entfernen Sie an Stelle 4, 5, 6 und 7 die Objekte, fügen anschließend an Stelle 4 das neue und an Stelle 5, 6, 7 und 8 die folgenden Objekte ein. 

Es empfiehlt sich also, beim Anlegen von Objektsequenzen gründlich zu planen und systematisch vorzugehen. Andererseits ist das Entfernen und Hinzufügen von Objekten mit wenigen Klicks erledigt, lassen Sie sich also nicht zu sehr in Ihrer Experimentierfreude oder Ihrem Optimierungsbedürfnis einschränken. Wenn die Änderungen Hauptbilder betreffen, sollten Sie bereits eingestellte Bildunterschriften in einer Textdatei zwischenspeichern, da diese beim Entfernen eines Objekts verloren gehen.

Änderungen an den Metadaten der Seite sind unproblematisch. Auch ein Wechsel des ausgewählten Layouts (vgl. Abb. 4.2, 4) ist möglich. Dabei ist allerdings zu bedenken, dass sich ein solcher Layout-Wechsel auf die Organisation der Inhalte auf der Ausstellungsseite auswirkt.

Die Software Omeka verhält sich bei einem Layout-Wechsel insofern „robust“, als es bestehende Inhalte den Inhaltselementen des neuen Layouts zuordnet. Dabei kann es zu unerwünschten, chaotischen Veränderungen bei den Eingabemasken kommen, vor allem, wenn Inhaltselemente aus den zweispaltigen Bereichen unterhalb der Objekte im neuen Template keine Entsprechung haben.

##### Praxistipp: Layouts und Layout-Wechsel

Am einfachsten ist es, wenn Sie ohne Layout-Wechsel auskommen. Machen Sie sich bereits in der Planungsphase mit den verfügbaren Layouts vertraut und wählen Sie ein geeignetes Layout für die betreffende Seite.

Der Wechsel zwischen verwandten Layouts (z.B. Layout 1 und 2, Layout 4 und 6) bereitet in der Regel keine Probleme.

Hat ein Layout-Wechsel das Schema der Eingabefelder auf unerwünschte Weise verändert, empfehlen wir, die Seite mit dem gewünschten Layout neu anzulegen, mit den Inhalten zu befüllen und die alte Seite zu löschen.

#### B.4.4.4 Zweispaltiger Texte

Bei den meisten Layouts sind Texte und Objekte auf zwei Spalten aufgeteilt: Text links, Objekte rechts oder umgekehrt (bei Layout 5 alternierend). Das Layout 3 (Galerie) präsentiert die Textblöcke und die Bildergalerie jeweils über die gesamte Breite des Content-Bereichs. Da Textzeilen von mehr als 100 Zeichen Länge mühsam zu lesen währen, ist der Text hier zweispaltig gesetzt. Die Aufteilung auf die beiden Spalten erfolgt im Browser des Nutzers automatisch, wobei sich der Spaltenumbruch an die – durch die Breite des Browserfensters bedingte – Breite des Content-Bereichs anpasst. 

!!!note "Der Spaltenumbruch muss automatisch erfolgen"

    Es ist sinnlos, den Spaltenumbruch durch Zeilenumbrüche, Absätze, Leerzeilen oder mit ähnlichen „Manipulationen“ erzwingen zu wollen, er würde dann nur für genau die Fensterbreite passen, in der Sie das Frontend gerade betrachten. Wenn Sie dieses Fenster groß und klein ziehen, wird Ihnen dieser Zusammenhang sofort anschaulich.

!![Abb. B.4.19 Eingabe zweispaltiger Text im Layout Vorschaubilder-Galerie mit optionalem Text oben und unten - unterer Textblock mit Überschrift][B-4-19]

Für die Eingabe des zweispaltigen Textblocks **unter** der Bildergalerie steht Ihnen ein spezielles Feld für die Überschrift des Blocks zur Verfügung (Abb. B.4.19, <span class="red-circle">1</span>). Normalerweise werden Überschriften im Textfeld eingegeben und per Auswahlliste als Überschrift einer bestimmten Ebene formatiert. Da die Überschrift hier aber über beide Spalten des Textblocks laufen soll, erfolgt die Eingabe separat. Auch hier sollten Sie dem Text der Überschrift ein Überschriften-Format zuweisen. Im Folgenden Feld (Abb. B.4.19, <span class="red-circle">2</span>) können Sie den Text eingeben, der - wie der Text oberhalb der Vorschaubilder-Galerie - im Frontend automatisch zweispaltig ausgegeben wird.

##### PRAXISTIPP: Halten Sie zweispaltige Textblöcke kurz!

Das mehrspaltige Textlayout ist uns im Printbereich aus Zeitschriften, Katalogen oder Broschüren vertraut. Auf Webseiten ist es (noch) eher die Ausnahme. Das hat einen guten Grund: Im Web fehlt eine feste Beziehung zwischen Sichtfeld (Viewport) und Paginierung. Bei der Darstellung im Browser der NutzerInnen können die unteren Teile der Spalten leicht unter den unteren Rand des Browserfensters geraten. Die NutzerInnen lesen dann den oberen Teil der linken Spalte, scrollen nach unten, lesen weiter, bis sie am Spaltenende angekommen sind, scrollen wieder nach oben, beginnen mit der rechten Spalte usw. Achten Sie deshalb darauf, dass zweispaltige Textblöcke nach Möglichkeit auch bei schmalen Browserfenstern noch ganz auf einen Bildschirm passen. Bei längeren Texten sollten Sie die Möglichkeit nutzen, sie auf einen Textblock ober- und einen unterhalb der Vorschaubilder-Galerie aufzuteilen.

Bei sehr kleinen Fensterbreiten (z. B. von mobilen Browsern) sorgt das responsive Design des Layouts dafür, dass die Zweispaltigkeit aufgehoben wird.

Eine andere Form von zweispaltiger Textanordnung bieten die Layouts 1, 2, 6 und 7. Hier lässt sich in der rechten Spalte unterhalb der Objekte ein Textblock einfügen (Abb. B.4.20, <span class="red-circle">1</span>). 

!![Abb. B.4.20 Texteingabe für die rechte Spalte unterhalb der Objekte][B-4-20]

Bei den Layouts 1 und 2 ist zudem die Möglichkeit vorgesehen, zweispaltig gesetzte Textblöcke mit automatischem Spaltenumbruch im unteren Teil der Ausstellungsseite einzufügen, analog zum Galerie-Layout 3 mit über die ganze Breite des Inhalts-Bereichs laufenden Überschriften. Auch hier finden Sie die entsprechenden Eingabefelder unterhalb der Schaltflächen zur Einbindung von Objekten (vgl. Abb. B.4.19). 

##### Praxistipp: Keep it short and simple!

Die zuletzt beschriebene Layoutvariante mit einer Textspalte links neben und einer Spalte rechts unter den Objekten plus zweispaltigen Textblöcken im unteren Bereich der Ausstellungsseite ist die komplexeste Zusammenstellung von Texten und Bildern, die das Online-Tool ermöglicht - komplex für Sie bei der Erstellung, aber eben auch für die Nutzerin oder den Nutzer. Fragen Sie sich deshalb bitte immer, bevor Sie diese Möglichkeit nutzen, ob Sie die Inhalte nicht besser auf mehrere Ausstellungsseiten aufteilen. Kurze, einfach strukturierte Seiten lassen sich besser erfassen und machen den Besuch Ihrer virtuellen Ausstellung mehr vergnüglich als fordernd. Wenn Sie durch eine solche Aufteilung dieselben Objekte auf mehreren Seiten einbinden müssen, ist das technisch kein Problem und unter Umständen auch inhaltlich bereichernd.

#### B.4.4.5 Der Apparat – Literatur, Team, Inhalt

Als letzten Teil einer Ausstellung ist ein Apparat mit ergänzenden Informationen, der Vorstellung der Mitwirkenden und einem Inhaltsverzeichnis vorgesehen. Standard sind drei Seiten: Literatur, Team und Inhalt.

Die Seite für das Inhaltsverzeichnis ist bereits angelegt und mit dem passenden Template verknüpft. Das Inhaltsverzeichnis selbst wird vom Online-Tool automatisch erstellt. Sie können diese Liste der Ausstellungsseiten mit einer kurzen Einleitung (Abb. B.4.21, <span class="red-circle">1</span>) und nachgestellten Erläuterungen (Abb. B.4.22, <span class="red-circle">1</span>) versehen.

!![Abb. B.4.21 Texteingabe Einleitung zum Inhaltsverzeichnis][B-4-21]

!![Abb. B.4.22 Texteingabe nachgestellte Erläuterungen zum Inhaltsverzeichnis][B-4-22]

Für die anderen Seiten des Apparats verwenden Sie das Layout 1 (ohne Objekte einzubinden) oder Layout 3 für zweispaltige Texte.

Sie können den Apparat gerne um weitere Seiten ergänzen. So gibt es beispielsweise in der virtuellen Ausstellung zur Geschichte Karlsruhes ([„Vom Privilegienbrief zum Bundesverfassungsgericht“](http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/) ein [Glossar](http://ausstellungen.deutsche-digitale-bibliothek.de/ka300/exhibits/show/vom-privilegienbrief-zum-bundesverfassungsgericht/glossar) zu in den Ausstellungstexten erwähnten historischen Fachbegriffen.

Das Vorschaubild für die grafische Seitennavigation (vgl. Abschnitt 4.1) ist hier kein Ausschnitt einer Objektabbildung (es handelt sich ja um reine Textseiten), sondern ein speziell formatierter Schriftzug mit dem Seitentitel. Diese Vorschaubilder werden vom Team der Deutschen Digitalen Bibliothek erzeugt und eingestellt, Sie können das betreffende Metadatenfeld einfach leer lassen.


[B-4-1]: img/B-4-1.jpg "Abb. B.4.1 „Seite hinzufügen“ auf der Seite „Ausstellung …“"
[B-4-2]: img/B-4-2.jpg "Abb. B.4.2 Die Metadaten der Ausstellungsseite - Titel und Slug"
[B-4-3]: img/B-4-3.jpg "Abb. B.4.3 Die Metadaten der Ausstellungsseite - Widget Content und Vorschaubild"
[B-4-4]: img/B-4-4.jpg "Abb. B.4.4 Layout 1 – Galerie rechts und Thumbnails"
[B-4-5]: img/B-4-5.jpg "Abb. B.4.5 Layout 2 - Galerie rechts und Thumbnails als Karussell"
[B-4-6]: img/B-4-6.jpg "Abb. B.4.6 Layout 3 – Thumbnailgalerie mit optionalem Text oben und unten"
[B-4-7]: img/B-4-7.jpg "Abb. B.4.7 Layout 4 – Bilder links"
[B-4-8]: img/B-4-8.jpg "Abb. B.4.8 Layout 5 – Bilder abwechselnd links und rechtstt"
[B-4-9]: img/B-4-9.jpg "Abb. B.4.9 Layout 6 – Bilder rechts"
[B-4-10]: img/B-4-10.jpg "Abb. B.4.10 Layout 7 – große, fortlaufende Bilder rechts"
[B-4-11]: img/B-4-11.jpg "Abb. B.4.11 Layout 8 – kleine, fortlaufende Bilder rechts"
[B-4-12]: img/B-4-12.jpg "Abb. B.4.12 Die Seite „Inhalt der Seite … bearbeiten“"
[B-4-13]: img/B-4-13.jpg "Der Texteditor"
[B-4-14]: img/B-4-14.jpg "Abb. B.4.14 Objekt hinzufügen"
[B-4-15]: img/B-4-15.jpg "Abb. B.4.15 Dialogfenster „Objekt hinzufügen“"
[B-4-16]: img/B-4-16.jpg "Abb. B.4.16 Inhaltselement Objekt – hier ein Hauptbild"
[B-4-17]: img/B-4-17.jpg "Abb. 4.17 Abb. B.4.16 Sortieren der Ausstellungsseiten durch Drag and Drop"
[B-4-18]: img/B-4-18.jpg "Abb. B.4.18 Seiten aus der Seitenliste löschen"
[B-4-19]: img/B-4-19.jpg "Abb. B.4.19 Eingabe zweispaltiger Text im Layout Vorschaubilder-Galerie mit optionalem Text oben und unten - unterer Textblock mit Überschrift"
[B-4-20]: img/B-4-20.jpg "Abb. B.4.20 Texteingabe für die rechte Spalte unterhalb der Objekte"
[B-4-21]: img/B-4-21.jpg "Abb. B.4.21 Texteingabe Einleitung zum Inhaltsverzeichnis"
[B-4-22]: img/B-4-22.jpg "Abb. B.4.22 Texteingabe nachgestellte Erläuterungen zum Inhaltsverzeichnis"
