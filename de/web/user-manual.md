# Allgemeines

Um SOGo korrekt verwenden zu können, ist es wichtig, JavaScript und Pop-Ups für die entsprechende Domain zuzulassen. 

Desweiteren sind ggf. nicht alle Optionen in Ihrer SOGo Installationen aktiviert und damit verfügbar.

## Einstellungen

Alle generellen Einstellungen für SOGo und seine Module finden Sie unter "Einstellungen" am oberen Bildschirmrand.

Hier finden Sie auch die Möglichkeit, Ihr "Standard Modul" zu definieren, welches nach dem Anmelden angezeigt werden soll.

![](img/screenshot_038.png)

Unter dem Reiter "Kalender" (1) können Sie denjenigen "Standardkalender" (2) wählen, welcher verwendet wird, wenn Sie keinen anderen durch markieren gewählt haben.

![](img/screenshot_039.png)

Ihre Mail-Signatur können Sie unter "IMAP-Konten" (1) nach einem Klick auf "(Zum Erstellen klicken)" (2) verfassen. Um die Änderung zu speichern schließen Sie das Fenster mit einem Klick auf "OK" und "Speichern und Schließen".

![](img/screenshot_040.png)








# Module

## Kalender

### Ansichtsarten ###

SOGo bietet zur Zeit folgende Ansichtsarten, bei welchen die angezeigten Kalender über die linke Kalenderliste an- und abgewählt werden können:

Tagesansicht
![](img/screenshot_005.png)

Mehrspaltige Tagesansicht
![](img/screenshot_006.png)

![](img/screenshot_037.png)

Wochenansicht
![](img/screenshot_008.png)

Monatsansicht
![](img/screenshot_007.png)


### Anlegen eines Termines

Um einen neuen Termin anzulegen wählen Sie den entsprechenden Kalender in der Liste (1) am linken Bildschirmrand aus. Klicken Sie nun auf "Neuer Termin" (2) oder wählen Sie durch Klicken, Halten und Ziehen (3) in der Tages/Mehrspaltigen Tagesansicht/Wochenansicht direkt das entsprechende Zeitfenster.

![](img/screenshot_009.png)

Nun befüllen Sie bitte die einzelen Eingabefelder mit den entsprechenden Eingaben.

![](img/screenshot_010.png)

<dl>
	<dt>Kategorie</dt> 
	<dd>Kategorien können in den Einstellungen eine farbige Markierung erhalten und helfen Ihnen damit auf den ersten Blick, die Art des Termins zu erfassen.</dd>

	<dt>Kalender</dt> 
	<dd>Bezeichnet den Kalender, in den das Ereignis eingetragen werden soll.</dd>

	<dt>Priorität</dt>
	<dd>Textmarke für die Wichtigkeit des Termines ohne weitere visuelle Erkennbarkeit.</dd>
	
	<dt>Ganztägiger Termin</dt> 
	<dd>Ganztägige Termine haben keine Start- und Endzeit und werden am oberen Rand der Tagesspalte angezeigt.</dd>
	
	<dt>Zeige Zeit als Verfügbar</dt> 
	<dd>Sollten Sie diese Option wählen, werden Sie für andere Benutzer wärend dieses Termins nicht als belegt angezeigt. Mehr zu diesem Thema finden Sie unter dem Punkt [Teilnehmer einladen]().</dd>
	
	<dt>Verabredungsbenachrichtigungen senden</dt> 
	<dd>Sollten Sie Teilnehmer eingetragen und diese Option ausgewählt haben, wird automatisch eine Einladung verschickt.</dd>
	
	<dt>Wiederholen</dt> 
	<dd>Wählen Sie ein vordefiniertes endloses Interval aus oder erstellen Sie Ihr eigenes durch die Auswahl "Benutzerdefiniert...". Hier können Sie nun auch bei Bedarf ein Enddatum setzen.</dd>
	
	<dt>Erinnerung</dt> 
	<dd>Eine Erinnerung gilt für alle Teilnehmer einer Veranstaltung und kann auch von diesen nicht deaktiviert werden. Unter "Benutzerdefiniert..." haben Sie aber die Möglichkeit, eine E-Mail-Erinnerung einzutragen und diese auch nur für sich zu aktivieren.</dd>
	
	<dt>Teilnehmer einladen</dt>
	<dd>siehe [Besprechung planen](#besprechung-planen)</dd>
	
	<dt>Vertraulichkeit</dt>
	<dd>SOGo unterscheidet drei Arten von Terminen: <i>Öffentliche</i> und <i>Vertrauliche</i> Termine werden für alle authorisierten Benutzer "geschwärzt" dargestellt, somit sind nur Datum und Uhrzeit ersichtlich. Ereignisse, die als <i>privat</i> gekennzeichnet sind, sind nur für Sie sichtbar. Diese Grundeinstellungen können unter Benutzerrechte individuell angepasst werden.</dd>
</dl>


### Besprechung planen ###

Wenn Sie nun "Teilnehmer einladen..." wählen aktivieren Sie die Besprechungsplanung mit anderen Benutzern. Das folgende Fenster öffnet sich:

![](img/screenshot_011.png)

Um einen Teilnehmer einzuladen, tippen Sie die E-Mail-Adresse in die dafür vorgesehene Zeile (1). Sollten Sie eine Freigabe für Kalender dieses Benutzers besitzen, sehen Sie die Belegt-/Frei-Zeiten (2). Nun können Sie über die Eingabefelder (3) den Termin ensprechend anpassen.

Nach dem Klick auf "OK" ist die Teilnehmerplanung abgeschlossen:

Um den Termin endgültig zu speichern, ist "Speichern und Schließen" anzuwählen.

Die eingeladenen Teilnehmer erhalten automatisch eine Einladungs-Mail. Sollten es interne Benutzer der Universität sein, werden die Terminanfragen automatisch in deren Kalender eingetragen! Beim nächsten Aufruf von SOGo hat er dann die Möglichkeit, zuzustimmen oder abzulehnen. Dieses ist auch mit Thunderbird Lightning und Apple iCal möglich. Folgend ein Beispiel für solch eine Einladung:

![](img/screenshot_002.png)


### Anlegen eines eigenen Kalenders

Um einen neuen Kalender anzulegen, klicken Sie bitte auf das erste kleine Kalendericon (1) links über der Kalenderliste mit dem grünen Plus. Ein kleines Overlay-Fenster öffnet sich, in welches Sie den Namen des gewünschten Kalenders eingeben:

![](img/screenshot_012.png)

![](img/screenshot_013.png)

Nach "OK" erscheint Ihr neuer Kalender.


### Benutzerrechte ###
Um einen Kalender anderen Benutzern oder der Allgemeinheit freizugeben, klicken Sie mit der rechten Maustaste auf den Kalendernamen. Wählen Sie hier "Benutzerrechte...".

![](img/screenshot_017.png)

Wie Sie sehen können ist hier standardmäßig eine Freigabe für "alle authentifizierten Benutzer" eingetragen. Diese Freigabe wird benötigt, damit alle SOGo-Benutzer Ihre Frei-/Belegt-Zeiten einsehen können.

Um weiteren Personen erweiterte Zugriffsrechte zu vergeben, klicken Sie bitte auf (1). 

![](img/screenshot_018.png)

In dem sich öffnenden Fenster können Sie durch Eingabe (1) einer E-Mail-Adresse und dem anschließenden Klick auf "Hinzufügen" (2) Personen eine Freigabe einräumen.

![](img/screenshot_019.png)

Durch einen Doppelklick auf den entsprechenden Kontakt (1) können Sie nun die Sichtbarkeiten für die verschiedenen Vertraulichkeitsstufen einrichten und Freigaben für das Löschen und Ändern von Einträgen vergeben. Damit der Benutzer Ihren Kalender nicht extra abonnieren muss, empfiehlt es sich, die Option "Für den Benutzer abonnieren" (2) auszuwählen.

![](img/screenshot_020.png)

![](img/screenshot_021.png)



### Abonnieren eines freigegebenen Kalenders ###

Klicken Sie dazu oberhalb Ihrer Kalenderliste auf (1).

![](img/screenshot_014.png)

Nun suchen Sie über das Eingabefeld (1) den entsprechenden Benutzer und öffnen durch einen Klick auf (2) die Liste der freigegebenen Kalender. Nach der Auswahl des entsprechenden Kalenders und der Bestätigung mittels "Hinzufügen" (3) finden Sie diesen nun in Ihrer Kalenderliste.

![](img/screenshot_015.png)

![](img/screenshot_016.png)

Die angezeigten Informationen eines abonnierten Kalenders sind dabei von den erteilten Rechten des Benutzers abhängig. Im obigen Beispiel sehen Sie zum Beispiel, dass öffentliche Termine alle Informationen enthalten, vertrauliche hingegen nur Datum und Uhrzeit.


### Benutzerrechte ###
Um einen Kalender anderen Benutzern oder der Allgemeinheit freizugeben, klicken Sie mit der rechten Maustaste auf den Kalendernamen. Wählen Sie hier "Benutzerrechte...".

![](img/screenshot_017.png)

Wie Sie sehen können ist hier standardmäßig eine Freigabe für "alle authentifizierten Benutzer" eingetragen. Diese Freigabe wird benötigt, damit alle SOGo-Benutzer Ihre Frei-/Belegt-Zeiten einsehen können.

Um weiteren Personen erweiterte Zugriffsrechte zu vergeben, klicken Sie bitte auf (1). 

![](img/screenshot_018.png)

In dem sich öffnenden Fenster können Sie durch Eingabe (1) einer E-Mail-Adresse und dem anschließenden Klick auf "Hinzufügen" (2) Personen eine Freigabe einräumen.

![](img/screenshot_019.png)

Durch einen Doppelklick auf den entsprechenden Kontakt (1) können Sie nun die Sichtbarkeiten für die verschiedenen Vertraulichkeitsstufen einrichten und Freigaben für das Löschen und Ändern von Einträgen vergeben. Damit der Benutzer Ihren Kalender nicht extra abonnieren muss, empfiehlt es sich, die Option "Für den Benutzer abonnieren" (2) auszuwählen.

![](img/screenshot_020.png)

![](img/screenshot_021.png)




### Kalendereinstellungen
Klicken Sie mit der rechten Maustaste auf den entsprechenden Kalender und wählen Sie in der erscheinenden Liste "Einstellungen" aus.

![](img/screenshot_022.png)

Der Name (1) und die Farbe (2) erscheint in jeder Kalenderliste, die diesen Kalender abonniert hat. Durch die Farbe ist auch die einfache Differenzierung in den verschiedenen Ansichten möglich.

![](img/screenshot_023.png)

### Drucken

Um Ihren Kalender zu drucken klicken Sie bitte auf "Ansicht drucken".

![](img/screenshot_024.png)

Standardmäßig wird die aktuelle Ansicht zum Druck vorgeschlagen. Durch die Pfeiltasten (1,2) kann der entsprechende Zeitabschnitt angepasst und über die "Formatierung" (3) die entsprechende Darstellung angepasst werden.

![](img/screenshot_025.png)

![](img/screenshot_026.png)











## Aufgaben
Den Ereignis- (1) und Aufgabenbereich (2) können Sie über den Pfeil (3) am rechten Bildschirmrand ein- und ausblenden und über die Trennlinie (4) in der Höhe anpassen.

![](img/screenshot_027.png)

### Anlegen einer Aufgabe ###
Um eine neue Aufgabe anzulegen klicken Sie auf "Neue Aufgabe".

![](img/screenshot_028.png)

Im sich nun öffnenden Fenster können Sie Ihre entsprechenden Angaben vornehmen. Titel, Ort, Kategorie, Kalender, Priorität, Wiederholen, Erinnerung und Beschreibung verhalten sich dabei gleich wie beim Anlegen eines [neuen Termines](). Folgende Felder sind hingegen neu und helfen Ihnen, Ihre Aufgaben zu filtern:

<dl>
	<dt>Beginn</dt>
	<dd>Start Datum/Uhrzeit dieser Aufgabe.</dd>

	<dt>Fällig</dt>
	<dd>End Datum/Uhrzeit bis zu welcher diese Aufgabe erledigt sein sollte.</dd>

	<dt>Status</dt>
	<dd>z.B. "Abgeschlossen am" 2014-09-03 zu 80%.</dd>
</dl>

![](img/screenshot_029.png)

Über die Liste "Anzeigen" (1), die Checkbox "Abgeschlossene Aufgaben anzeigen" (2) und das Suchfeld (3) können Sie Ihre Aufgaben entsprechend der Eingaben filtern. Die Anzahl der unabgeschlossenen Aufgaben wird dabei in der Kalenderliste rechts neben dem Namen angezeigt. Um eine Aufgabe abzuschließen setzen Sie einen Haken links (4) in der entsprechenden Zeile.

![](img/screenshot_030.png)

Da Aufgaben immer einem Kalender zugeordnet sind, erben diese auch die Rechte und Freigaben.




















## Adressbuch

### Globale Adressbücher ###
Globale Adressbücher sind durch ein Globus-Icon gekennzeichnet und bieten die Besonderheit, dass diese nur durchsucht werden können. Je nach Konfiguration sind dabei nur eine bestimmte Anzahl von Treffern sichtbar.

### Neues Adressbuch anlegen ###

Klicken Sie auf (1) und geben Sie in dem sich öffnenden Fenster den Namen (2) Ihres neuen Adressbuches ein.

![](img/screenshot_031.png)

![](img/screenshot_032.png)

### Kontakt hinzufügen ###

Um einen Kontakt in Ihr Adressbuch hinzuzufügen klicken Sie auf "Neue Adresskarte".

![](img/screenshot_033.png)

Wählen Sie aus der oberen Liste (1) das Zieladressbuch für diesen Kontakt aus und füllen Sie die entsprechenden Felder aus. Dabei stehen nur die sichtbaren Optionen zu Verfügung. Es ist also nicht möglich, zusätzliche E-Mail Adressen oder Telefonnummern einzutragen.

![](img/screenshot_034.png)

### Adressliste erstellen ###

Eine Adressliste ist eine Sammlung von E-Mail-Adressen und hilft Ihnen beim regelmäßigen Versenden von Rundmails. Dabei ist zu beachten, dass jede E-Mail Adresse in einer Adresskarte des entsprechenden Adressbuches vorhanden sein muss. Ist dies nicht der Fall, wird ein neuer Kontakt angelegt. Bitte beachten Sie, dass eine nachträgliche Änderung in einer Adresskarte keine Aktualisierung in der Liste nach sich zieht.

Um eine neue Liste zu erstellen wählen Sie das entsprechende Adressbuch aus (1) und klicken Sie auf "Neue Liste" (2).

![](img/screenshot_035.png)

Nun tragen Sie die entsprechenden E-Mail-Adressen in die Liste (1) ein. Eine neue Zeile bekommen Sie nach einem Klick auf (2).

![](img/screenshot_036.png)
