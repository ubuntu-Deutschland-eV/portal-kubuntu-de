Title: KDE 4.0.1 mit Paketen für Kubuntu erschienen!
Date: 2008-02-04 23:01
Author: Monika Eggers
Tags: KDE
Slug: kde-401-mit-paketen-fur-kubuntu-erschienen

Erstes Wartungsrelease für KDE 4 erschienen![![Bild:KDE.png](http://wiki.kubuntu-de.org/images/Kde.png){width="100" height="100"}](http://wiki.kubuntu-de.org/images/Kde.png "Bild:KDE4-Plasma.png"){.image}
============================================================================================================================================================================================================

</p>
Das [KDE-Projekt](http://www.kde.org/ "http://www.kde.org") hat heute mit der Versionsnummer 4.0.1 das [erste Wartungsrelease
der KDE
4](http://www.kde.org/announcements/announce-4.0.1.php "http://www.kde.org/announcements/announce-4.0.1.php") Reihe freigegeben und es sind bereits Pakete für Kubuntu 7.10
Gutsy Gibbon und die aktuelle Entwicklungsversion Hardy Heron verfügbar.
In dieses Release gingen zahlreiche Fehlerkorrekturen ein, welche über
die Seite bugs.kde.org berichtet wurden. Unter anderem wurden einige
Verbesserungen in der Stabilität von KHTML - der Web-Engine von KDE -
getätigt. Die Compositing Fähigkeiten (Grafikeffekte) von KWin wurden
verbessert, zahlreiche Fehler in Okular, den Systemeinstellungen und
vielen anderen Programmen behoben. Was viele besonders freuen wird, die
nervigsten Fehler von Plasma wurden behoben und einige kleinere
Funktionen sind hinzugekommen! Leider kann man das Panel noch nicht
verkleinern. Diese Änderung im Quellcode hat es leider nicht mehr
rechtzeitig ins Release geschafft. Auch die Übersetzungsteams haben
einiges geleistet, so ist KDE 4.0.1 nun auch in Dänisch, Friesisch,
Kasachisch und Tschechisch verfügbar. Insgesamt sind es damit schon fast
50 Sprachen, in die KDE 4 übersetzt wurde. 

</p>
Update: Das Paket kdelibs5 sollte nicht entfernt werden!

</p>
<!--break--><!--break-->

[ Installation der Pakete]{.mw-headline}
----------------------------------------

</p>
Wer unter Kubuntu 7.10 Gutsy Gibbon oder Hardy Heron bereits KDE 4.0
installiert hat, braucht nur mit dem Paketmanager seiner Wahl (z.B.
Adept oder apt-get) ein Upgrade durchzuführen. Für alle Anderen hier
nochmal die Anleitung: Wer schon Hardy Heron installiert hat muss nur
das Paket kde4-core installieren. Für Gutsy Gibbon ist ein wenig mehr zu
beachten:

</p>
KDE 4.0.1 installiert sich in das Verzeichnis /usr/lib/kde4 und kann
daher neben einem bestehenden KDE 3 installiert werden.

</p>
-   Zuerst müssen eventuell vorhandene Pakete einer vorherigen KDE 4
    Installation entfernt werden, da sie nicht mehr kompatibel sind mit
    KDE 4 (apt-get remove kde4base-data kde4libs-data)
-   Danach folgende Paketquelle zur Datei /etc/apt/sources.list
    hinzufügen "deb
    <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu> gutsy main"
-   Das Paket "kde4-core" installieren. Dabei sollte beachtet werden,
    das persönliche Paketarchive nicht mit einem Schlüssel
    authentifiziert werden. Bei der Installation muss also eine Warnung
    bestätigt werden.
-   Die KDE 4 Applikationen erscheinen im KDE 3 KMenü, man kann aber
    auch durch Anwählen von "KDE 4" in der Anmeldemaske eine vollwertige
    Sitzung starten.
-   Um das Betreiben eines zweiten X-Servers zu vermeiden, kann
    xserver-xephyr installiert werden. Danach Xephyr :1 & export
    DISPLAY=:1; xterm in der Konsole ausführen und startkde in dem
    Xerphyr xterm eingeben.

</p>
Eine detaillierte Liste aller Änderungen seit dem Release von KDE 4.0
ist im englischen
[Changelog](http://www.kde.org/announcements/changelogs/changelog4_0to4_0_1.php "http://www.kde.org/announcements/changelogs/changelog4_0to4_0_1.php") einzusehen.

</p>
Informationen über KDE 4 im allgemeinen ist in unserer [Ankündigung für
die Version
4.0](../../../../nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen "http://www.kubuntu-de.org/nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen") ersichtlich und auf der deutschen Seite von
[KDE](http://kde.org/announcements/4.0/index-de.php "http://kde.org/announcements/4.0/index-de.php").

</p>
[ So geht es weiter mit KDE 4]{.mw-headline}
--------------------------------------------

</p>
Wie schon
[angekündigt](../../../../nachrichten/software/kde/releasefahrplan-f-r-kde-4 "http://www.kubuntu-de.org/nachrichten/software/kde/releasefahrplan-f-r-kde-4") wird KDE nun jeden Monat ein Wartungsrelease für KDE 4
herausbringen, bis vorraussichtlich am 29. Juli das nächste große
Release KDE 4.1 mit vielen neuen Funktionen herauskommen wird. Wer sich
vorab schon über die geplanten neuen Features und Technologien
informieren möchte, kann diese dem [Feature
Plan](http://techbase.kde.org/index.php?title=Schedules/KDE4/4.1_Feature_Plan "http://techbase.kde.org/index.php?title=Schedules/KDE4/4.1_Feature_Plan") und der Festlegung der [Release
Ziele](http://techbase.kde.org/index.php?title=Schedules/KDE4/4.1_Release_Goals "http://techbase.kde.org/index.php?title=Schedules/KDE4/4.1_Release_Goals") entnehmen.

</p>

