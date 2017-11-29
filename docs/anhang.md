# C Anhang

## C.1 Metadaten

Das Metadatenschema für die Objekte Ihrer Ausstellung ist so ausgelegt, dass ein breites Spektrum an Medientypen abgedeckt ist. Im Zusammenhang der virtuellen Ausstellungen haben die Metadaten in erster Linie eine deskriptive Funktion: Sie sollen über das im Rahmen der Ausstellung gezeigte Objekt informieren – die inhaltserschließende Funktion spielt hier eine untergeordnete Rolle. Sie können deshalb die Metadatenfelder relativ frei befüllen, ohne an ein vorgegebenes Schema für die Datenerfassung gebunden zu sein. Priorität hat die Lesbarkeit und Verständlichkeit aus Sicht des Publikums.

Die meisten Metadaten werden im Frontend der Ausstellung ausgegeben, manche dienen auch nur technischen Zwecken wie der Verknüpfung mit einer Datenquelle. Angezeigt werden Metadaten prinzipiell nicht auf den Ausstellungsseiten selbst, sondern erst nach Aufruf der Lightbox (durch Klicken auf eine Objektabbildung; vgl. Abb. A.5) oder auf der Detailseite (vgl. Abb. A.7) zum Objekt (nach Klick auf den Link „zum Objekt“ in der Lightbox). Die Objekt-Detailseite fasst alle zur Ausgabe vorgesehenen Metadaten zusammen. Dagegen wird in der Lightbox nur ein Teil der Metadaten eines Objekts ausgegeben. Bei Objekten, die bereits in die Deutschen Digitalen Bibliothek ingestiert sind, entfällt die Detailseite, weil hier der Link „zum Objekt“ in der Lightbox direkt auf den Eintrag in der Deutschen Digitalen Bibliothek führt (vgl. Abb. A.6).

Nicht ausgefüllte Metadatenfelder werden bei der Ausgabe der Detailseite ignoriert, es entstehen also keine Lücken. Die für die Ausgabe in der Lightbox vorgesehenen Felder sollten aber stets ausgefüllt werden. Pflichtfelder sind mit einem * gekennzeichnet; wenn Sie diese Felder nicht ausfüllen, erhalten Sie beim Speichern des Objekts eine Fehlermeldung.

##### Titel*

Der Titel des Objekts  
**Ausgabe**: Lightbox, Objekt-Detailseite (als Titel der Seite)

##### Weiterer Titel

z. B. Untertitel, Originaltitel in anderer Sprache (welcher?), gleichwertiger Titel, ursprünglicher Titel (z. B. Mona Lisa/La Joconde), ...  
**Ausgabe**: Objekt-Detailseite

##### Beschreibung

Ausführliche Beschreibung des Objekts  
**Ausgabe**: Objekt-Detailseite

##### Kurzbeschreibung

Kurze Beschreibung des Objekts  
**Ausgabe**: Objekt-Detailseite; in der Lightbox nur dann, wenn keine Bildunterschrift auf der Ausstellungs-Seite angelegt ist

##### Name der Institution*

Offizielle Bezeichnung der Institution, die das Objekt besitzt  
**Ausgabe**: Objekt-Detailseite; Lightbox

##### URL der Institution

Internet-Präsenz der Institution, die das Objekt besitzt  
**Ausgabe**: als Ziel hinter dem verlinkten Namen der Institution: Objekt-Detailseite; Lightbox

##### Link zum Objekt in der DDB

URL des Objekts im Portal der DDB. Wichtig: Die korrekte URL erhalten Sie nur, indem Sie das Objekt in der Deutschen Digitalen Bibliothek aufrufen und dort auf der Objektseite auf den Link „Link auf diese Seite“ klicken, der direkt über dem Titel des Objekts zu finden ist.  
**Ausgabe**: Objekt-Detailseite  
**Anmerkung**: Wenn das Objekt in der Deutschen Digitalen Bibliothek zu finden ist, bitte unbedingt dieses Feld benutzen (und **nicht** das Feld „Link zum Objekt bei der datengebenden Institution“). Bitte kopieren Sie **nicht** die aktuelle URL aus der Adresszeile Ihres Browsers, sondern verwenden Sie immer die stabile URL, die stets in etwa so aussieht: https://www.deutsche-digitale-bibliothek.de/item/XNVHWXKSHKH6O5SYXM22ZBW25PQG4JFE.

##### Link zum Objekt bei der datengebenden Institution

URL des Objekts in der Datenbank oder auf der Website der Institution, die das Objekt besitzt   
**Ausgabe**: Objekt-Detailseite; Lightbox (Ziel des Links „zum Objekt“)  
**Anmerkung**: Bitte **nur** dann ausfüllen, wenn das Objekt **nicht** in der Deutschen Digitalen Bibliothek zu finden ist. Andernfalls unbedingt leer lassen!

##### Rechtsstatus*

Angabe von Lizenz- oder Rechtehinweis; die Eingabe erfolgt über eine Auswahl-Liste.    
**Ausgabe** (als Lizenz-Piktogramm): Objekt-Detailseite; Lightbox (aufrufbar über das (c) -Symbol) 
**Anmerkung**: Die Shortcodes erzeugen in der Lightbox und auf der Detailseite Piktogramme, die mit einer Seite verlinkt sind, auf der die betreffende Lizenz beschrieben ist.

##### Typ

Die Art des Objekts (z. B. Gemälde, Fotografie, Buch ...)  
**Ausgabe**: Objekt-Detailseite  
**Anmerkung**: Da diese Typus-Bezeichnungen nicht für eine Objektsuche oder systematische Kategorisierung verwendet werden, können Sie sie frei verwenden, so, wie sie das Objekt am besten charakterisieren.

##### Teil von

Zugehörigkeit zu einem übergeordneten Werkzusammenhang (z. B. erschienen in ..., Band 3 der Reihe ...)  
**Ausgabe**: Objekt-Detailseite

##### Thema

Thema, Kontext, Indexbegriff, Ort ...  
**Ausgabe**: Objekt-Detailseite

##### Beteiligte Personen und Organisationen

Personen, die an der Herstellung des Objekts beteiligt waren, etwa als AutorIn, HerstellerIn, ...  
**Ausgabe**: Objekt-Detailseite

##### Zeit

Zeitangabe zur Herstellung, zur Laufzeit, Erscheinungsdatum ...  
**Ausgabe**: Objekt-Detailseite

##### Ort

Herstellungs- oder Erscheinungsort, historische Bezeichnung des Orts, wenn der im Titel genannte Ort nicht der tatsächlich dargestellte Ort ist ...    
**Ausgabe**: Objekt-Detailseite

##### Maße/Umfang

Die für das Objekt passenden Angaben zur Dimension: Abmessungen, Seitenzahl, Länge von Ton- oder Filmaufnahmen, ...    
**Ausgabe**: Objekt-Detailseite

##### Material/Technik

Angaben zum verwendeten Material und zur Technik, z. B. Öl auf Leinwand, Holz, Grisaille, mp3, ...    
**Ausgabe**: Objekt-Detailseite

##### Sprache

Bei textuellen Objekten die Sprache, in der der Text verfasst ist, ggf. Angaben zur Übersetzung oder Originalsprache   
**Ausgabe**: Objekt-Detailseite

##### Identifikator

Information, die nötig ist, um das Objekt im Bestand der datengebenden Institution zu finden: Signatur, Inventarnummer, ...     
**Ausgabe**: Objekt-Detailseite

##### Anmerkungen

Feld für interne Vermerke, besonders zum Bearbeitungsstand  
**Ausgabe**: im Frontend nicht ausgegeben

##### Förderung

Fördermittelgeber, Förderprogramm      
**Ausgabe**: Objekt-Detailseite

##### Videoquelle

Sie können Videos aus der DDB oder von Vimeo nutzen. Optional können Sie einen Ausschnitt des Videos zeigen. Bitte nutzen Sie den Video-Shortcode-Helfer (s. [Abschnitt B.2.3.2][1]).  
**Ausgabe**: als Video in einem Player (Ausstellungseite und Objekt-Detailseite)

##### Imagemap

HTML-Code einer verweissensitiven Grafik  
**Ausgabe**: erzeugt Imagemap (Ausstellungsseite und Objekt-Detailseite)  
**Anmerkung**: Imagemaps sind verweissensitive Grafiken, bei denen bestimmte Regionen auf eine interne oder externe URL verlinken. Ein Beispiel finden Sie auf der Seite [„Die Forschungsreise nach Kolumbien“](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/forschungsreise-nach-kolumbien) der Ausstellung „Zu Mythen und Monumenten“. Wenn Sie die historische Kolumbienkarte in der Lightbox aufrufen, verlinken die roten Markierungen auf andere Seiten dieser virtuellen Ausstellung. So können Sie auch auf Objektebene Querverweise in Ihre Ausstellung einbinden. Wie Sie den HTML-Code für eine Imagemap erzeugen, ist auf der Seite [SelfHTML](https://wiki.selfhtml.org/wiki/HTML/Multimedia_und_Grafiken/verweissensitive_Grafiken) ausführlich und gut verständlich erklärt. Zu beachten ist allerdings, dass Sie im Feld „Imagemap“ nicht das Bild (Image), sondern lediglich die Karte (Map), also die Codierung der klickbaren Bereiche einfügen. Das Bild wird – wie bei anderen Objekten auch – über den Tab „Datei“ mit dem Objekt verknüpft (s. oben [Abschnitt B.2.3][2]). Der einzufügende Code beginnt also mit
```
<map name=“ImageMap“>
``` 
und endet mit  

```
</map>
```    
Damit die Imagemap auch nach dem Umzug vom Entwicklungs- auf den Live-Server noch funktioniert, müssen alle Pfade relativ angegeben werden, also z. B.:

````
href="/preuss/exhibits/show/kolumbien-preuss/reise-zu-den-uitioto"

##### Verlinkung auf Objekte
````

Wenn Sie möchten, dass ein Objekt, auf das sie verlinken, direkt in der Lightbox-Ansicht aufgerufen wird, verlinken Sie auf die entsprechende Ausstellungsseite und hängen an die URL den Zusatz „?lbitem“ plus die Objekt-Nummer an (das wievielte der eingebundenen Objekte?). Die URL sieht dann beispielsweise so aus:

````
href="/tanz/exhibits/show/das-gedaechtnis-des-tanzes/moderne-taenze?lbitem=4"
````
Sie können auf diese Weise sowohl aus Imagemaps heraus, als auch aus einem Seitentext auf ein Objekt verlinken.

## C.2 Der Texteditor

Die Eingabe der Texte für die Ausstellungsseiten erfolgt in einem Text-Editor (TinyMCE), der Ihnen in etwa die Formatierungsmöglichkeiten eines einfachen Textverarbeitungsprogramms bietet.

Neben Formatierungen wie Fett- oder Kursiv-Satz erlaubt der Editor auch das Einfügen von Hyperlinks.

Die Icons und Auswahl-Listen des Editors sind leicht verständlich und Ihnen wahrscheinlich aus anderen Programmen vertraut. Im Folgenden ein kurzer Überblick über die einzelnen Optionen.

!!!note "Formatieren Sie bitte sparsam und konsistent!"

    Die Grundformatierung Ihrer virtuellen Ausstellung übernimmt ein Template. Es sorgt dafür, dass alle Elemente gestalterisch aufeinander abgestimmt sind. Die Formatierungsmöglichkeiten des Editors sind lediglich als Ergänzung zu verstehen, um besondere Anforderungen zu erfüllen, etwa die Kursivsetzung eines im Text erwähnten Werktitels. Mit (Zwischen-)Überschriften können Sie längere Texte leserfreundlich strukturieren. Achten Sie dabei bitte darauf, dass die Überschriftenhierarchie nicht mit dem Template kollidiert und sich auf allen Seiten systematisch durchzieht.
	
##### Fett (bold)

Mit dem B-Icon können Sie Wörter oder Textpassagen fett setzen (Abb. C.1). Bitte gehen Sie sparsam mit diesem Gestaltungsmittel um. Die Fettsetzung von Überschriften erfolgt über die Zuweisung des Überschriftenformats, bitte nicht doppelt fetten!

!![Abb. C.1 Texteditor: Text fett setzen][C-1]

##### Kursiv (italic)

Kursiv-Satz bietet sich bei Titeln von Werken oder Publikationen an (Abb. C.2).

!![Abb. C.2 Texteditor: Text kursiv setzen][C-2]

##### Liste (unsortiert)

Mit diesem Icon (Abb. C.3) können Sie Listen in Ihren Text einfügen. Die Liste wird durch Einrückungen und Listenpunkte (Bullet Points) formatiert. Das Aufzählungs-Symbol können Sie nicht verändern, da es auf Template-Ebene festgelegt ist.

Listen sind Absatzformatierungen, die Listenpunkte müssen also zunächst Absätze sein. Markieren Sie dann alle Absätze (durch „Enter“ getrennte Zeilen) und machen Sie sie durch einen Klick auf das Listen-Icon zur Liste. Alternativ können Sie einfach den ersten Absatz als Liste formatieren – mit der Enter-Eingabe wird der folgende Absatz automatisch als Listenabsatz formatiert. Um die Listenformatierung zu entfernen, markieren Sie die gesamte Liste und klicken erneut auf das Listen-Icon.


!![Abb. C.3 Texteditor: unsortierte Liste][C-3]

##### Liste (sortiert)

Nummerierte (sortierte) Listen unterscheiden sich von den unsortierten nur dadurch, dass an Stelle des Listenpunkts eine Ordnungszahl erscheint (Abb. C.4). Auch auf das Format der Nummerierung haben Sie keinen Einfluss.


!![Abb. C.4 Texteditor: sortierte Liste][C-4]

##### Links einfügen

Über das Kettensymbol können Sie in Ihrem Text Hyperlinks zu beliebigen URLs oder auf andere Seiten der Ausstellung setzen. Den zu verlinkenden Text (Ankertext) schreiben Sie zunächst als gewöhnlichen Text, markieren ihn und klicken auf das Kettensymbol (Abb. C.5). Bereits verlinkte Textteile erscheinen im Backend unterstrichen (hier „Lorem ipsum“) – was nicht der Ausgabe im Frontend entspricht. Auch die Formatierung von Links regelt das Template, Sie können sie also nicht beeinflussen.

!![Abb. C.5 Texteditor: einen Link setzen][C-5]

Beim Klick auf das Kettensymbol öffnet sich eine Eingabemaske, in der Sie die zur Verlinkung notwendigen Einstellungen vornehmen können (Abb. C.6). 

Bei Links auf andere Seiten Ihrer Ausstellung setzen Sie als so genannte **relative** Links. Dazu gehen Sie auf die betreffende Seite, kopieren die URL aus der Adresszeile Ihres Browsers und entfernen alles bis zur Top-Level-Domain „.de“. Ein relativer Link sieht dann beispielsweise so aus: „/preuss/exhibits/show/kolumbien-preuss/reise-zu-den-uitioto“. Im Auswahlmenü „Fenster“ wählen Sie den Eintrag „Im selben Fenster öffnen“.

Bei Links auf Seiten außerhalb Ihrer Ausstellung setzen Sie **absolute** Links, die Sie direkt aus der Adresszeile Ihres Browsers übernehmen können. Im Auswahlmenü „Fenster“ wählen Sie den Eintrag „In neuem Fenster öffnen“. 

!![Abb. C.6 Texteditor: Dialogfenster zum Setzen eines Links][C-6]

##### Zitatblock

Das Template der virtuellen Ausstellungen sieht die Möglichkeit vor, hervorgehobene Zitate auf den Seiten zu platzieren. Ein Beispiel finden Sie auf den Seiten der Ausstellung [„Zu Mythen und Monumenten“](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/konrad-theodor-preuss). 
Um einen Absatz als einen solchen Zitatblock zu gestalten, platzieren Sie den Cursor im betreffenden Absatz (oder markieren diesen ganz) und klicken auf das Icon mit dem **einzelnen** blauen Anführungszeichen (Abb. C.7). 
Die Formatierung sieht bereits Anführungszeichen vor (ein großes, symbolhaftes, öffnendes Anführungszeichen oben links), bitte verwenden Sie keine weiteren Anführungszeichen zur Kennzeichnung des Zitats.

!![Abb. C.7 Texteditor: Text als Zitatblock setzen][C-7]

Um die Quelle des verwendeten Zitats anzugeben, steht ein weiteres Spezialformat zur Verfügung, das über das Icon mit den **beiden** blauen Anführungszeichen zugewiesen wird (Abb. C.8). Fügen Sie dazu dem Zitatblock einen Absatz mit der Quellenangabe hinzu, markieren diesen und klicken auf das betreffende Symbol. Es öffnet sich ein Dialogfenster, dessen Felder Sie unausgefüllt lassen können. Klicken Sie einfach auf „Aktualisieren“.

!![Abb. C.8 Texteditor: Quellenangabe Zitatblock][C-8]

##### Überschriften

Das Auswahlfeld in der unteren Zeile der Bedienelemente erlaubt die Zuweisung von Absatzformaten. Voreingestellt ist „Absatz“, was normalem Fließtext entspricht. Sie können über die Auswahl-Liste Überschriften setzen. Dazu schreiben Sie den Text der Überschrift in einen eigenen Absatz, markieren ihn (oder setzen den Cursor in diesen Absatz) und wählen aus der Liste ein passendes Überschriftenformat aus der Überschriften-Hierarchie (Abb. C.9).

!![Abb. C.9 Texteditor: Überschriften][C-9]

Den Überschriften sind unterschiedliche Formatierungen zugewiesen, die bereits im Schriftbild des Editors angedeutet sind. Entscheidend ist die Formatierung im Frontend. Bitte überprüfen Sie das Ergebnis Ihrer Textformatierung immer dort – das Erscheinungsbild im Backend dient nur als Anhaltspunkt. Die Überschrift der Ebene „Überschrift 1“ ist bereits durch den Seitentitel belegt, verwenden Sie deshalb bitte nur die Überschriften der Ebenen 2 bis 6.

Um eine Überschriftenformatierung zu entfernen, weisen Sie wieder das Format „Absatz“ zu.

##### Der HTML-Modus

Die Schaltfläche „HTML“ (Abb. C.10) gibt Ihnen Zugang zu dem Quellcode im HTML-Format, den der Texteditor erzeugt. Wenn Sie zumindest ein wenig mit der HTML-Syntax vertraut sind, können Sie auf diese Weise im Quellcode nachschauen (Abb. C.11), falls Schwierigkeiten im normalen Editor-Modus auftauchen. 

!![Abb. C.10 Texteditor: HTML-Modus aufrufen][C-10]

!![Abb. C.11 Texteditor: HTML Quellcode bearbeiten][C-11]

Hier einige typische Anwendungsfälle:

* beim Kopieren aus einer Vorlage (Word, Webseite) wurden unerwünschte Formatierungen eingeschleppt
* beim Löschen von Text wurde die hierarchische Staffelung von HTML-Tags gestört, indem z. B. ein schließendes Tag versehentlich gelöscht wurde

In aller Regel kommen Sie aber ohne den HTML-Modus aus. Wenn Sie über die nötige Expertise verfügen, kann er die Arbeit beschleunigen – notwendig ist er nicht.

##### Vollbild-Modus

Wenn Sie etwas umfangreichere und komplexer strukturierte Texte bearbeiten, kann es hilfreich sein, den Texteditor im Vollbildmodus zu verwenden. Sie haben dann das gesamte Browserfenster für die Arbeit am Text zur Verfügung. Klicken Sie dazu auf das letzte Icon in der ersten Zeile (Abb. C.12), dann schaltet der Editor in den Vollbildmodus (Abb. C.13).

!![Abb. C.12 Texteditor: Vollbild-Modus aufrufen][C-12]

!![Abb. C.13 Texteditor: im Vollbild-Modus arbeiten][C-13]

Zum Schließen der Vollbild-Ansicht klicken Sie einfach noch einmal auf das entsprechende Icon.


[C-1]: img/C-1.jpg "Abb. C.1 Texteditor: Text fett setzen"
[C-2]: img/C-2.jpg "Abb. C.2 Texteditor: Text kursiv setzen"
[C-3]: img/C-3.jpg "Abb. C.3 Texteditor: unsortierte Liste"
[C-4]: img/C-4.jpg "Abb. C.4 Texteditor: sortierte Liste"
[C-5]: img/C-5.jpg "Abb. C.5 Texteditor: einen Link setzen"
[C-6]: img/C-6.jpg "Abb. C.6 Texteditor: Dialogfenster zum Setzen eines Links"
[C-7]: img/C-7.jpg "Abb. C.7 Texteditor: Text als Zitatblock setzen"
[C-8]: img/C-8.jpg "Abb. C.8 Texteditor: Quellenangabe Zitatblock"
[C-9]: img/C-9.jpg "Abb. C.9 Texteditor: Überschriften"
[C-10]: img/C-10.jpg "Abb. C.10 Texteditor: HTML-Modus aufrufen"
[C-11]: img/C-11.jpg "Abb. C.11 Texteditor: HTML Quellcode bearbeiten"
[C-12]: img/C-12.jpg "Abb. C.12 Texteditor: Vollbild-Modus aufrufen"
[C-13]: img/C-13.jpg "Abb. C.13 Texteditor: im Vollbild-Modus arbeiten"

[1]: /erstellen/index.html#b232-verknupfung-mit-einer-videodatei "zum Abschnitt B.2.3.2"
[2]: /erstellen/index.html#b23-das-objekt-mit-dateien-verknupfen "zum Abschnitt B.2.3"
