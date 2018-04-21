Title: Update: KDE 3.5.7 mit Kubuntu Paketen erschienen
Date: 2007-05-22 20:43
Author: Monika Eggers
Tags: KDE
Slug: update-kde-357-mit-kubuntu-paketen-erschienen

KDE 3.5.7 ist freigegeben worden. Es kann mit den KDE Paketen über eine
der folgenden Quellen installiert werden (eine davon zur
/etc/apt/sources.list hinzufügen):


Die Pakete sind mit [Jonathan Riddels
Schlüssel](http://kubuntu.org/announcements/kubuntu-packages-jriddell-key.gpg)
digital signiert worden. Eine Kopie des Schlüssels wird zu Verifizierung
[auf
people.ubuntu.com](http://people.ubuntu.com/~jriddell/kubuntu-packages-jriddell-key.gpg)
zur Verfügung gestellt.


Die Pakete werden nicht bevorzugt unterstützt. Sicherheits- und sonstige
Aktualisierungen können verzögert erscheinen.


Kubuntu 7.04 (Feisty)


-   deb <http://kubuntu.org/packages/kde-357> feisty main
-   deb <ftp://bolugftp.uni-bonn.de/pub/kde/stable/3.5.7/kubuntu> feisty
    main
-   deb
    <http://www.mirrorservice.org/sites/ftp.kde.org/pub/kde/stable/3.5.7/kubuntu>
    feisty main
-   deb
    <http://mirror.cc.columbia.edu/pub/software/kde/stable/3.5.7/kubuntu>
    feisty main
-   Weitere Spiegelserver sind auf <http://download.kde.org> gelistet.



Die Pakete sind verfügbar für die Architekturen i386 und AMD64.


KDE 3.5.7 wird ebenfalls für Gutsy hochgeladen.


<!--break--><!--break-->

Anleitung


-   Den
    [Schlüssel](http://kubuntu.org/announcements/kubuntu-packages-jriddell-key.gpg)
    auf der Festplatte speichern
-   Adept Manager aus K-Menü-&gt;System aufrufen
-   Im Menü Adept-&gt;Paketquellen verwalten auswählen
-   Den Reiter Authentication wählen
-   "Import Key File" anklicken und anschließend den oben gespeicherten
    Schlüssel auswählen
-   Den Reiter "Third-Party Software" auswählen
-   Füge eine der oben genannten deb-Zeilen mittels "Add" hinzu
-   Den Dialog schließen und "Aktualisierungen holen"
-   "Vollständige Aktualisierung" aus der Werkzeugleiste anklicken
-   Wenn die Installation vollständig ist, aus KDE aus- und wieder
    einloggen



Update: Changelog


Vorweg


Die untenstehende Liste ist eine übersetzte Zusammenfassung des [KDE
3.5.7
Changelogs](http://www.kde.org/announcements/changelogs/changelog3_5_6to3_5_7.php).
Die Übersetzung konzentriert sich auf die bekanntesten Pakete und nur
die offensichtlichsten Änderungen, ist also eine subjektive Auswahl.
Pakete, die eher für Entwickler interessant sind, werden gar nicht
berücksichtigt (die sollten mit dem englischen Changelog eh klar
kommen).


Die quantifizierenden Angaben zur Anzahl der Bugfixes sind
umgangssprachlich, aber abgestuft. "Viele" Bugfixes sind mehr als
"weitere", aber weniger als "zig" oder "Milliarden". Wenn die Existenz
von Bugfixes nicht erwähnt wird, heißt dies nicht, dass es zu dem Paket
keine gab.


Also: wer die kompletten Infos oder näheres erfahren will, der schaue in
[das KDE 3.5.7
Changelog](http://www.kde.org/announcements/changelogs/changelog3_5_6to3_5_7.php).


KDE 3.5.7 Highlights


<ul>


<li>
Verbesserungen bei mehreren Ansichten in
[Kate]{style="font-weight: bold;"} (bugfix)

</li>


<li>
[Monochrome]{style="font-weight: bold;"} Icon-Sammlung hat mehr Icons

</li>


<li>
Bugfix für Crash in [KScreensaver]{style="font-weight: bold;"}

</li>


<li>
"Serbien und Montenegro (yu)" aus [KDEBase]{style="font-weight: bold;"}
entfernt und "Serbien (rs)" und "Montenegro (me)" hinzugefügt

</li>


<li>
[KControl]{style="font-weight: bold;"}: Schriftfarbe der Taskbar kann
jetzt geändert werden

</li>


<li>
[KWin]{style="font-weight: bold;"}: das bei Alt+Tab erscheinende Fenster
kann jetzt deaktiviert werden

</li>


<li>
[KLettres]{style="font-weight: bold;"} unterstützt jetzt Niedersächsisch

</li>


<li>
[kgoldrunner]{style="font-weight: bold;"} hat mit "State of Terror" ein
neues Spiel bekommen

</li>


<li>
[KPDF]{style="font-weight: bold;"} kann jetzt eine PDF-Datei vor dem
Drucken in ein Bild umwandeln; plus viele Bugfixes

</li>


<li>
[Kuickshow]{style="font-weight: bold;"} stürzt nicht mehr ab, wenn man
Entf drückt ohne etwas ausgewählt zu haben

</li>


<li>
[Kopete]{style="font-weight: bold;"} hat verbesserten (schnelleren)
Aufbau des Fensterinhalts beim Chatten, stürzt nicht mehr nach dem
Erstellen eines ICQ-Accounts ab, weitere Bugfixes

</li>


<li>
[KAddressBook]{style="font-weight: bold;"} lässt den Benutzer nun in
beliebigen Feldern suchen; wählt nicht mehr alle ausgewählten Einträge
ab sobald man rechtsklickt; sehr viele Bugfixes

</li>


<li>
[KAlarm]{style="font-weight: bold;"}: sehr viele Bugfixes

</li>


<li>
[KMail[]{}]{style="font-weight: bold;"}

</li>

-   kommt jetzt mit IMAP Quotas klar
-   bei IMAP können jetzt einzelne Ordner vom Synchronisieren
    ausgenommen werden
-   alle Ordner können nun verschoben und kopiert werden
-   Drag&Drop funktioniert jetzt für einen oder mehrere ausgewählte
    Ordner
-   Anhänge im TNEF-Format können nun im Nachrichtenfenster direkt
    angezeigt werden
-   akzeptiert jetzt das Einfügen von Bildern aus externen Quellen per
    Drag&Drop oder Strg+V
-   zeigt optional jetzt den Inhalt der Kopfzeilen "User-Agent" oder
    "X-Mailer" bei Ansichtseinstellung "Dekorativ" für den Vorspann
-   zeigt zu erst die bevorzugte E-Mail-Adresse bei der automatischen
    Vervollständigung
-   eine Milliarde Bugfixes ;)



<li>
[KOrganizer]{style="font-weight: bold;"} hat Feiertagsdateien für
Südafrika und die Ukraine bekommen, sowie einige Bugfixes

</li>


<li>
bei [KWeather]{style="font-weight: bold;"} lässt sich jetzt die
Textfarbe einstellen; Wetterstationen hinzugefügt/korrigiert

</li>


<li>
[ark]{style="font-weight: bold;"} behandelt Dateien mit mehr als 4 GB
jetzt korrekt und stürzt nicht mehr bei Dateinamen ab, die mit "/"
beginnen

</li>


<li>
[klaptopdaemon]{style="font-weight: bold;"} sollte .xsession-errors
nicht mehr mit zahlreichen Warnung füllen

</li>


</ul>



