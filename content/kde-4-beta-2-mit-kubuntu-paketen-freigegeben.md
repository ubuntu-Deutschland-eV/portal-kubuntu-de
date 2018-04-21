Title: KDE 4 Beta 2 mit Kubuntu Paketen freigegeben
Date: 2007-09-07 21:14
Author: Monika Eggers
Tags: KDE
Slug: kde-4-beta-2-mit-kubuntu-paketen-freigegeben

Am gestrigen späten Abend wurde die Beta 2 von KDE 4 veröffentlicht, mit
ihr erschienen Pakete für die Entwicklerversion Gutsy. Pakete für Feisty
Fawn sind inzwischen über die Feisty Backports verfügbar.


Der Google Summer of Code soll die Entwicklung von KDE 4.0 besonders
angeregt und vorangetrieben haben, wie die Ankündigung seitens KDE
betont.


Der Tradition früherer Freigaben folgend kann auch diese Version von KDE
4 neben der bestehenden KDE 3 Version verwendet werden, da eine
Installation nach /usr/lib/kde4 erfolgt. Es ist ferner möglich, in der
laufenden Sitzung auf KDE 4 zu schalten. Eine Anleitung zur Installation
befindet sich am Ende dieser Nachricht.


[Update:]Überarbeiteter KDE 4.0 Zeitplan


<!--break--><!--break-->

<a href="http://kde.org/announcements/announce_4.0-beta2/desktop-plasma-big.png">![KDE
4
Screenshot](http://kde.org/announcements/announce_4.0-beta2/desktop-plasma-small.png)  

Größere Darstellung</a>


Nach dem Freeze der Systembibliotheken, welcher mit der Beta 1
daherging, wurde nun auf Fähigkeiten und Funktionalität Wert gelegt. Die
weiteren Aufgaben beinhalten das Ausreifen dieser Komponenten, das
Schreiben und Übersetzen von Dokumentationen, verbessern der
Gebrauchstauglichkeit und das Vervollständigen des Artworks.


Weitere Fähigkeiten werden in KDE 4.0 nicht mehr eingehen, da mit dieser
Veröffentlichung auch der Stopp der Entwicklung dieser eingeleitet
wurde. Der Fokus liegt nun auf dem finden und beheben von
Programmfehlern. Somit können neue Ideen und Implementationen erst in
KDE 4.1 einfließen. Eine Ausnahme gibt es jedoch: die Arbeit an Plasma
wird weiter vorangetrieben.


Die 2. Beta der freien Desktopumgebung bringt unter anderem die
gleichzeitig erschienen 3. Alpha von KOffice mit sich. Gearbeitet wurde
dabei an den Grundlagen wie dem Laden von Formen in KPresenter und
KSpread, die Portierung einiger Filter in Karbon, Verbesserungen in
KChart2 sowie an der Stabilität und Gebrauchstauglichkeit. Auch weitere
Features kamen dazu, zu nennen wären vor allem der Umlauf von Text um
einen frei definierten Rahmen oder eine mit Tabs realisierte
Werkzeugleiste in Kexi. Obwohl diese deutlich verbessert und
gebrauchsfähiger geworden ist, so bleibt dies dennoch eine Vorschau auf
die endgültige Version.


Weitere nennenswerte Verbesserungen gibt es in der Grafikbibliothek
Blitz, welches eingesetzt wird, solange Qasar nicht fertig ist, dem
Einstellungssystem Kconfig, Strigi (Unterstützung für XESAM und
Kalzium), Avogadro (einschließlich Integration in Kalzium), Kate
(Suchfunktion) und PlugIn-Dialog (z.b. für Kate, Kopete).


Darüberhinaus haben weitere Projekte die KDE 4 Versionen ihrer
Anwendungen vorangetrieben. So gibt es in Kolourpaint mehr Funktionen,
bessere Nutzbarkeit und ausgeprägtere Robustheit. Ebenso wurde KGPG
anwenderfreundlicher gestaltet und mit mehr Funktionalität versehen. In
Amarok wurde Plasmaintegration realisiert und auch Okular verbessert.


Anleitung:
----------


<ul>


<li>
Vergewissert euch, dass ihr
[feisty-backports](https://help.ubuntu.com/community/UbuntuBackports)
aktiviert habt oder Gutsy läuft.

</li>


<li>
Installiert kdebase-workspace (anders als in Beta 1)

</li>


<li>
Diese KDE-4-Pakete werden nach /usr/lib/kde4 installiert, führt deshalb
folgende Befehle aus:

</li>

-   export LD\_LIBRARY\_PATH=/usr/lib/kde4/lib
-   export KDEDIRS=/usr/lib/kde4
-   export PATH=/usr/lib/kde4/bin:$PATH
-   export KDEHOME=\~/.kde4



<li>
Um zu vermeiden, für eine vollwertige Sitzung einen zweiten X-Server
starten zu müssen, installiert xserver-xephyr und startet *Xephyr :1;
export DISPLAY=:1; xterm*, führt dann *startkde* im Xephyr-xterm aus.

</li>


<li>
Um KDE 4 als vollwertige Sitzung starten zu können, kopiert
/usr/lib/kde4/share/apps/kdm/sessions/kde.desktop nach
/usr/share/xsessions/kde4.desktop, ändert den Eintrag "Name" in der
kde4.desktop in "KDE 4", fügt die vier "export" Zeilen von oben am
Anfang der /usr/lib/kde4/bin/startkde ein und startet im KDM eine neue
Sitzung mit KDE 4.

</li>


</ul>


Weiterführende Links:


-   [Offizielles
    Announcement](http://kde.org/announcements/announce-4.0-beta2.php)
-   [Kubuntu](http://kubuntu.org/announcements/kde4-beta2.php)
-   [ProLinux](http://www.pro-linux.de/news/2007/11694.html)


Update
------


Einen Tag nach der Veröffentlichung der KDE 4.0 Beta 2, die übrigens den
Codenamen "Cartoffel" hat, wurde auch der Zeitplan bis zur
Veröffentlichung der finalen Version überarbeitet und veröffentlicht. In
dem Zug wurde die Idee der Beta 4 fallen gelassen und die Freigabe der
finalen Version auf den 11. Dezember vorgezogen.


Die Eckdaten sehen nun wie folgt aus:


-   2\. Oktober: Beta 3
-   19\. Oktober: Stopp des Einbaus weiterer Funktionen, lediglich Behebungen
    kritischer Fehler können noch dazu kommen.
-   30\. Oktober: Release Candidate (Freigabekandidat) 1
-   14\. November: Release Candidate 2
-   11\. Dezember: Veröffentlichung KDE 4.0


Weiterführende Links:


-   [KDE](http://dot.kde.org/1189160442/)
-   [Pro-Linux](http://www.pro-linux.de/news/2007/11700.html)



