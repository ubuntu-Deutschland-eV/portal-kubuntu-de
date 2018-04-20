Title: KDE SC 4.6 mit Kubuntu-Paketen erschienen
Date: 2011-01-27 23:29
Tags: KDE
Slug: kde-sc-46-mit-kubuntu-paketen-erschienen

[](http://www.kubuntu-de.org/nachrichten/software/kde/2054-kde-sc-4-6-mit-kubuntu-paketen-erschienen){.FlattrButton}Das
[KDE-Team](http://www.kde.org "http://www.kde.org") hat nun die nächste
Hauptversion 4.6 von KDE Plasma, KDE Anwendungen und KDE Plattformen
veröffentlicht. Zeitgleich sind auch Pakete des KDE SC 4.6 für Kubuntu
10.10 und die Entwicklerversion 11.04 herausgegeben worden.


[![KDE SC 4.6 - Elegently
Yours](http://wiki.kubuntu-de.org/images/Kde-sc-4.6.png){width="500"
height="181"}](http://www.kubuntu-de.org/nachrichten/software/kde/2054-kde-sc-4-6-mit-kubuntu-paketen-erschienen)


[]{#Installation}  

### [ Installation]{.mw-headline}


Wer KDE SC 4.6 installieren möchte, kann sie sich unter Kubuntu 10.10
die Updates über das Kubuntu-Backports-PPA ([Anleitung Backports
PPA](http://wiki.kubuntu-de.org/Installation/Upgrade/Kubuntu_10.10_auf_KDE_4.6_aktualisieren "http://wiki.kubuntu-de.org/Installation/Upgrade/Kubuntu_10.10_auf_KDE_4.6_aktualisieren"))
einspielen. Nutzer der Entwicklerversion Kubuntu 11.04 erhalten KDE SC
4.6 regulär mit den Systemupdates.


<!--break--><!--break-->

[]{#.C3.84nderungen_in_KDE_Plasma_Workspaces_4.6}  

### [ Änderungen in KDE Plasma Workspaces 4.6]{.mw-headline}


In KDE Plasma Workspaces, welches die Desktopumgebung enthält, wurde vor
allem Arbeit in die Aktivitäten investiert. So wurde die Verwaltung
dieser verbessert und weiter wurde auch die Zuordnung von Anwendungen zu
Aktivitäten verbessert. Ebenfalls überarbeitet wurde die
Energieverwaltung, die nun wesentlich modularer, einfacher und flexibler
sein soll.


KWin wurde hinsichtlich der Performance weiterentwickelt, auch werden
die Möglichkeiten der Grafikkarten nun besser erkannt und ausgeschöpft.
Verfeinert wurde zudem der "Fenster zeigen"-Effekt, von dem aus jetzt
auch Fenster geschlossen werden können.


Darüber hinaus sind weitere nennenswerte Punkte die effizientere
Anwendungsstartbenachrichtigung (der standardmäßig hüpfende Cursor), ein
überarbeitetes Benachrichtigungssystem, dessen Meldungsfenster überall
platziert werden kann. Ein zusätzliches Miniprogramm mit dem mysteriösen
Namen "Regal" kam dazu. Dieses kann verschiedene Dinge beinhalten wie
favorisierte Programme, neue Dokumente oder ungelesene Mail (s.
Screenshot). Die Lesbarkeit der digitalen Uhr bei unterschiedlichen
Farbschemen wurde verbessert, die Taskleiste kann nun einfache
Anwendungsstarter beherbergen (Programm dahinziehen) und zuletzt seien
die Geschwindigkeitsverbesserungen und eine bessere Touch-Unterstützung
bei der Netbook-Oberfläche erwähnt.


[![Das Miniprogramm
'Regal'](http://wiki.kubuntu-de.org/images/Regal-Miniprogramm-sm.png){width="500"
height="260"}](http://wiki.kubuntu-de.org/images/Regal-Miniprogramm.png "Zur Großansicht")


Im Dateimanager Dolphin wurde die Dateisuche (KFind) integriert,
außerdem wurde ein "facettiertes Browsing" eingeführt, in dem durch
verschiedene Filteroptionen anhand der Metadaten Dateien angezeigt
werden. Dazu gibt es nun eine zusätzliche Seitenleiste, über die anhand
selbiger Daten ebenfalls Suchen durchgeführt werden können. Dazu wurde
die Einstellung der Spaltenbreiten in der Spaltenansicht verbessert. Als
Extra gibt es ein Git-Plugin zur Versionskontrolle und diverse
Überarbeitungen bei den Servicemenüs.


Der Texteditor Kate kann nun ungesicherte Daten beim nächsten Start
wiederherstellen. Außerdem wurde er um einen einfachen SQL-Client
erweitert, der mit allen von Qt unterstützten SQL-Datenbanken kompatibel
ist. Zwei weitere Plugins runden Kate ab.


Alle Anwendungen die mit Grafiken umgehen, dazu zählen der
Bildbetrachter Gwenview oder auch das Screenshot-Tool KSnapshot können
nun Bilder direkt an zahlreiche Dienste, aber auch Rechner, verteilen.
Ferner können bei KSnapshot nun auch Freihand-Regionen ausgewählt
werden.


Mit dem Globus Marble ist nun auch Routenplanung anhand der
OpenStreeMap-Karten möglich (die Mobilvariante für Maemo beherrscht
Navigation). KStars, ein Planetarium, kann nun auch durch OpenGL
angezeigt werden, was zu Performanceverbesserungen führt. Außerdem gab
es diverse Änderungen bei den Spielen.


[![Routenplanung mit
Marble](http://wiki.kubuntu-de.org/images/Marble-Routenplaner-sm.png){width="500"
height="350"}](http://wiki.kubuntu-de.org/images/Marble-Routenplaner.png "Zur Großansicht")


Nicht geschafft hat es die neue, auf Akonadi basierende Kontact-Version.
Diese soll aber mit einer der kommenden Wartungsveröffentlichungen,
nachgeliefert werden.


[]{#Zu_guter_Letzt:_KDE_Platforms_4.6}  

### [ Zu guter Letzt: KDE Platforms 4.6]{.mw-headline}


Durch weitere Modularisierungen konnte die Mobil-Variante von KDE, die
beim experimentellen Kubuntu Mobile zum Einsatz kommt, weiter
entschlackt werden. Kontact Mobile ist eine der Anwendungen, die davon
Gebrauch machen.


Miniprogramme (Plasmoids) können fortan auch in QML geschrieben werden,
eine deklarative Markup-Sprache, die ursprünglich bei Qt Quick zum
Einsatz kommt. Das KDE Team weißt sogar darauf hin, dass QML nun die
bevorzugte Sprache zur Entwicklung von Plasmoiden sei - die
Unterstützung aller weiteren Sprachen bleibt nach wie vor bestehen. In
diesem Zusammenhang gibt es auch neue DataEngines zum Austausch von
Dateien sowie zum Caching für Offline-Zwecke. Mit einem speziellen KPart
sollen Miniprogramm nun auch einfach in Anwendungen integriert werden
können. Die Musikverwaltung Amarok und die Finanzanwendung Skrooge
arbeiten derzeit an der Integration dieser Möglichkeit.


Mit KDE Platforms 4.6 sind nun auch die Abhängigkeiten zur alten
Hardwareabstraktion HAL aufgelöst, sodass komplett UPower, UDev und
UDisks verwendet werden können. Werden diese vom System nicht
unterstützt, bleibt HAL jedoch verfügbar.


Nepomuk wurde mit Funktionen zum Backup und zur Synchronisation
angereichert um den Transport von Metadaten zwischen verschiedenen
Geräten zu erleichtern. Während die Backup-Funktionen über eine
grafische Schnittstelle verfügen, ist die Synchronisation zur Zeit noch
ausschließlich über die Kommandozeile möglich.


Die Funktionalität des Fenstermanagers KWin kann nun mit eigenen
Skripten weiter ausgebaut werden und der Oxygen GTK Stil wurde komplett
überarbeitet. Schließlich ist mit BlueDevil ein neues
Bluetooth-Framework etabliert worden, das wesentlich
benutzerfreundlicher sein soll.


[![Nepomuk Backup der
Metadaten](http://wiki.kubuntu-de.org/images/Nepomuk-Backup-sm.png){width="499"
height="381"}](http://wiki.kubuntu-de.org/images/Nepomuk-Backup.png "Zur Großansicht")


Diese Nachricht kann im
[Forum](http://forum.kubuntu-de.org/index.php?board=1.0 "http://forum.kubuntu-de.org/index.php?board=1.0")
diskutiert werden.



