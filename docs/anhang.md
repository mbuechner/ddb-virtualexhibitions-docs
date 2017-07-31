# C Anhang

## C.1 Metadaten

Das Metadatenschema für die Objekte Ihrer Ausstellung ist so ausgelegt, dass ein breites Spektrum an Medientypen abgedeckt ist. Im Zusammenhang der virtuellen Virtuellen Ausstellung haben die Metadaten in erster Linie eine deskriptive Funktion; sie sollen über das im Rahmen der Ausstellung gezeigte Objekt informieren. Die inhaltserschließende Funktion spielt hier eine untergeordnete Rolle. Sie können deshalb die Metadatenfelder relativ frei befüllen, ohne an ein vorgegebenes Schema für die Datenerfassung gebunden zu sein. Priorität hat die Lesbarkeit und Verständlichkeit aus Sicht der Nutzer.

Die meisten Metadaten werden im Frontend der Ausstellung ausgegeben, manche dienen auch nur technischen Zwecken wie der Verknüpfung mit einer Datenquelle. Angezeigt werden Metadaten prinzipiell nicht auf den Ausstellungsseiten selbst, sondern erst nach Aufruf der Lightbox (durch Klicken auf eine Objektabbildung; vgl. Abb. A.5) oder auf der Detailseite (vgl. Abb. A.7) zum Objekt (nach Klick auf den Link „zum Objekt“ in der Lightbox). Die Detailseite fasst alle zur Ausgabe vorgesehenen Metadaten zusammen. Dagegen wird in der Lightbox nur ein Teil der Metadaten eines Objekts ausgegeben. Bei Objekten, die bereits in die Deutschen Digitalen Bibliothek ingestiert sind, entfällt die Detailseite, weil hier der Link „zum Objekt“ in der Lightbox direkt auf den Eintrag in der Deutschen Digitalen Bibliothek führt (vgl. Abb. A.6).

Nicht ausgefüllte Metadatenfelder werden bei der Ausgabe der Detailseite ignoriert, es entstehen also keine Lücken. Die für die Ausgabe in der Lightbox vorgesehenen Felder sollten aber stets ausgefüllt werden. Pflichtfelder sind mit einem * gekennzeichnet; wenn Sie diese Felder nicht ausfüllen, erhalten Sie beim Speichern des Objekts eine Fehlermeldung.

##### Titel*

Der Titel des Objekts  
**Ausgabe**: Lightbox, Objekt-Detailseite (als Titel der Seite)

##### Weiterer Titel

Sekundäre Titelangabe, z.B. Untertitel, Originaltitel in anderer Sprache (welcher?), gleichwertiger Titel, ursprünglicher Titel (z. B. Mona Lisa/La Joconde), ...  
**Ausgabe**: Objekt-Detailseite

##### Beschreibung

Ausführliche Beschreibung des Objekts  
**Ausgabe**: Objekt-Detailseite

##### Kurzbeschreibung

Kurze Beschreibung des Objekts.  
**Ausgabe**: Objekt-Detailseite; in der Lightbox, allerdings nur, wenn keine Bildunterschrift auf der Ausstellungs-Seite angelegt ist

##### Name der Institution*

Offizielle Bezeichnung der Institution, die das Objekt besitzt.  
**Ausgabe**: Objekt-Detailseite; Lightbox

##### URL der Institution

Internetadresse der Institution, die das Objekt besitzt.  
**Ausgabe** als URL, mit der der Name der Institution verlinkt wird: Objekt-Detailseite; Lightbox

##### Link zum Objekt in der DDB

URL des Objekts im Portal der DDB. Die korrekte URL erhalten Sie, indem Sie das Objekt in der Deutschen Digitalen Bibliothek aufrufen und dort auf der Objektseite auf den Link „Link auf diese Seite“ klicken, der direkt über dem Titel des Objekts zu finden ist.  
**Ausgabe**: Objekt-Detailseite  
**Anmerkung**: Wenn das Objekt in der Deutschen Digitalen Bibliothek zu finden ist, bitte unbedingt dieses Feld benutzen (und **nicht** das Feld „Link zum Objekt bei der datengebenden Institution“). Bitte verwenden Sie immer die persistente URL (s.o.) und kopieren Sie nicht die aktuelle URL aus der Adresszeile Ihres Browsers.

##### Link zum Objekt bei der datengebenden Institution

URL des Objekteintrags in der Datenbank der Institution, die das Objekt besitzt.   
**Ausgabe**: Objekt-Detailseite; Lightbox (Ziel des Links „zum Objekt“)  
**Anmerkung**: Bitte **nur** dann ausfüllen, wenn das Objekt **nicht** in der Deutschen Digitalen Bibliothek zu finden ist. Andernfalls unbedingt leer lassen!

##### Rechtestatus*

Angabe von Lizenz oder Rechtehinweis; die Eingabe erfolgt über eine Auswahlliste.    
**Ausgabe** (als Lizenz-Piktorgramm): Objekt-Detailseite; Lightbox (aufrufbar über das (c) -Symbol) 
**Anmerkung**: Die Shortcodes erzeugen in der Lightbox und auf der Detailseite Piktogramme, die mit einer Seite verlinkt sind, auf der die betreffende Lizenz beschrieben ist. Siehe Abschnitt XXX mit weiteren Informationen zu den Lizenzen.

##### Typ

Die Art des Objekts (z.B. Gemälde, Fotografie, Buch ...)  
**Ausgabe**: Objekt-Detailseite  
**Anmerkung**: Da diese Typus-Bezeichnungen nicht für eine Objektsuche oder systematische Kategorisierung verwendet werden, können sie frei verwendet werden, wie sie das Objekt am besten charakterisieren.

##### Teil von

Zugehörigkeit zu einem übergeordneten Werkzusammenhang (z.B. Erschienen in ..., Band der Reihe ...)  
**Ausgabe**: Objekt-Detailseite

##### Thema

Thema, Konext, Indexbegriff, Ort ...  
**Ausgabe**: Objekt-Detailseite

##### Beteiligte Personen

Personen, die an der Herstellung des Objekts beteiligt waren, etwa als AutorIn, HerstellerIn, ...  
**Ausgabe**: Objekt-Detailseite

##### Zeit

Zeitangabe zur Herstellung, zur Laufzeit, Erscheinungsdatum ...  
**Ausgabe**: Objekt-Detailseite

##### Ort

Herstellung oder Erscheinungsort, evtl. historische Bezeichnung des Orts; gemeint ist nicht der gezeigte Ort auf einer Darstellung  
**Ausgabe**: Objekt-Detailseite


##### Maße/Umfang

Die für das Objekt passenden Angaben zur Dimension: Abmessungen, Seitenzahl, Länge von Ton- oder Filmaufnahmen    
**Ausgabe**: Objekt-Detailseite

##### Material/Technik

Angaben zum verwendeten Material und zur Technik, z.B. Öl auf Leinwand, Holz, Grisaille, mp3    
**Ausgabe**: Objekt-Detailseite

##### Sprache

Bei textuellen Objekten die Sprache, in der der Text verfasst ist, ggf. Angaben zur Übersetzung   
**Ausgabe**: Objekt-Detailseite

##### Identifikator

Information, die nötig ist, um das Objekt im Bestand der datengebenden Institution zu finden: Signatur, Inventarnummer, ...     
**Ausgabe**: Objekt-Detailseite

##### Anmerkungen

Feld für interne Vermerke, besonders zum Bearbeitungsstand  
**Ausgabe**: im Frontend nicht ausgegeben

##### Material/Technik

Angaben zum verwendeten Material und zur Technik, z.B. Öl auf Leinwand, Holz, Grisaille, mp3    
**Ausgabe**: Objekt-Detailseite

##### Förderung

Fördermittelgeber, Förderprogramm      
**Ausgabe**: Objekt-Detailseite

##### Videoquelle

Sie können Videos aus der DDB oder von Vimeo nutzen. Optional können Sie einen Ausschnitt des Videos zeigen. Bitte nutzen Sie den Video-Shortcode-Helfer (siehe Abschnitt B.2.3.2)  
**Ausgabe**: als Video in einem Player (Ausstellungseite und Objekt-Detailseite)

##### Imagemap

HTML-Code einer verweissensitiven Grafik  
**Ausgabe**: erzeugt Imagemap (Ausstellungsseite und Objekt-Detailseite)  
**Anmerkung**: Imagemaps sind verweissensitive Grafiken, bei denen bestimmte Regionen auf eine interne oder externe URL verlinken. Ein Beispiel finden Sie auf der Seite [„Die Forschungsreise nach Kolumbien“](http://ausstellungen.deutsche-digitale-bibliothek.de/preuss/exhibits/show/kolumbien-preuss/forschungsreise-nach-kolumbien) der Ausstellung „Zu Mythen und Monumenten“. Wenn Sie die historische Kolumbienkarte in der Lightbox aufrufen, verlinken die roten Markierungen auf andere Seiten dieser virtuellen Ausstellung. So können Sie auch auf Objektebene Querverweise in Ihre Ausstellung einbinden. Wie Sie den HTML-Code für eine Imagemap erzeugen, ist auf der Seite [SelfHTML](https://wiki.selfhtml.org/wiki/HTML/Multimedia_und_Grafiken/verweissensitive_Grafiken) ausführlich und gut verständlich erklärt. Zu beachten ist allerdings, dass Sie im Feld „Imagemap“ nicht das Bild (Image), sondern lediglich die Karte (Map), also die Codierung der klickbaren Bereiche einfügen. Das Bild wird – wie bei anderen Objekten auch – über den Tab „Datei“ mit dem Objekt verknüpft (siehe oben Abschnitt B.2.3). Der einzufügende Code beginnt also mit
```
<map name=“ImageMap“>
``` 
und endet mit  

```
</map>
```    
Damit die Imagemap auch nach dem Umzug vom Entwicklungs- auf den Live-Server noch funktioniert, müssen alle Pfade relativ angegeben werden, also z.B.:

````
href="/preuss/exhibits/show/kolumbien-preuss/reise-zu-den-uitioto"
````

Wenn Sie möchten, dass das verlinkte Objekt direkt in der Lightbox-Ansicht aufgerufen wird, verlinken Sie auf die entsprechende Ausstellungsseite und und hängen an die URL den Zusatz „?lbitem“ + plus die Objekt-Nummer an (das wievielte der eingebundenen Objekte). Die URL sieht dann beispielsweise so aus:

````
href="/tanz/exhibits/show/das-gedaechtnis-des-tanzes/moderne-taenze?lbitem=4"
````

!![Abb. B.1 Legende][B-1]


!!!note "Aufgepasst"

    Aufgepasst Text
	

[C-1]: img/C-1.jpg "Legende x"
[C-2]: img/C-2.jpg "Legende x"
[C-3]: img/C-3.jpg "Legende x"
[C-4]: img/C-4.jpg "Legende x"
[C-5]: img/C-5.jpg "Legende x"
[C-6]: img/C-6.jpg "Legende x"
[C-7]: img/C-7.jpg "Legende x"
[C-8]: img/C-8.jpg "Legende x"
[C-9]: img/C-9.jpg "Legende x"
[C-10]: img/C-10.jpg "Legende x"
[C-11]: img/C-11.jpg "Legende x"
[C-12]: img/C-12.jpg "Legende x"





