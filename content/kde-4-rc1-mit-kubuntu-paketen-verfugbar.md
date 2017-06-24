Title: KDE 4 RC1 mit Kubuntu Paketen verfügbar
Date: 2007-11-21 01:07
Author: Monika Eggers
Tags: KDE
Slug: kde-4-rc1-mit-kubuntu-paketen-verfugbar

Der lang ersehnte Release-Kandidat von KDE 4 wurde veröffentlicht und es
sind Pakete für Kubuntu 7.10 "Gutsy Gibbon" verfügbar.

</p>
Der Release-Kandidat von KDE 4 ist für Tester und Entwickler gedacht und
nicht für den produktiven Einsatz! Der KDE Desktop hat in den letzten
Wochen große Fortschritte gemacht, es ist aber zu beachten, dass wegen
der sehr kurzen Testphase durchaus noch Probleme auftauchen können. 
Jeder ist dazu aufgefordert ensprechende Fehlerberichte auf der Seite
[bugs.kde.org](http://bugs.kde.org/ "http://bugs.kde.org:") einzutragen und mitzuhelfen, dass KDE 4 bald, die von den
vorherigen Versionen bekannte Qualität, erreicht.

</p>
KDE 4 RC1 installiert sich in das Verzeichnis /usr/lib/kde4 und kann
daher neben einem bestehenden KDE 3 installiert werden.  

**Update:** Ein Test ohne Installation ist mit der [KDE 4 Live
CD](http://kubuntu.org/~jriddell/cds/kubuntu-kde4-20071126.iso "KDE 4 LiveCD")
möglich.

</p>
<!--break--><!--break-->

Anleitung:

</p>
-   Zuerst müssen eventuell vorhandene Pakete einer vorherigen KDE 4
    Installation entfernt werden, da sie nicht mehr kompatibel sind mit
    KDE 4 RC1 (apt-get remove kdelibs5)
-   Danach folgendes Paketrepositorium zur Datei /etc/apt/sources.list
    hinzufügen "*deb <http://ppa.launchpad.net/tsimpson/ubuntu> gutsy
    main*"
-   Die Pakete kdebase-dev-kde4 kdebase-workspace-dev kdebase-runtime
    installieren
-   Die entsprechenden Umgebungsvariablen exportieren, so dass sie auf
    /usr/lib/kde4 verweisen:

    </p>
    -   export LD\_LIBRARY\_PATH=/usr/lib/kde4/lib
    -   export KDEDIRS=/usr/lib/kde4
    -   export PATH=/usr/lib/kde4/bin/:\$PATH
    -   export KDEHOME=\~/.kde4

    </p>
    <p>
-   Um das Starten eines zweiten X-Servers zu vermeiden, kann
    xserver-xephyr installiert werden. Danach Xephyr :1 & export
    DISPLAY=:1; xterm in der Konsole ausführen und startkde in dem
    Xerphyr xterm eingeben.
-   Um KDE 4 als volle Sitzung zu starten muss kdm-kde4 installiert
    werden und /usr/lib/kde4/share/kde4/apps/kdm/sessions/kde.desktop
    nach /usr/share/xsessions/kde4.desktop kopiert werden, danach muss
    der Namenseintrag in kde4.desktop in "KDE 4" umbenannt werden und
    die vier oben beschriebenen "Export Zeilen" an den Anfang von
    /usr/lib/kde4/bin/startkde gesetzt werden. Nun kann eine
    selbständige Sitzung von KDE 4 über den Anmeldungsmanager KDM
    gestartet werden.

</p>
Die benötigten Pakete werden auch in die Backports-Repositorien von
"Gutsy Gibbon", und in die derzeitige Entwicklungsversion von Kubuntu
"Hardy Heron" heraufgeladen.

</p>
Die Ankündigung auf der englischen Seite ist unter
[www.kubuntu.org](http://kubuntu.org/announcements/kde4-rc1.php) zu
finden.

</p>

