Title: KDE 4 RC2 mit Kubuntu Paketen verfügbar
Date: 2007-12-12 19:55
Author: Monika Eggers
Tags: KDE
Slug: kde-4-rc2-mit-kubuntu-paketen-verfugbar

Nachdem das endgültige Release von KDE 4 nun doch in den Januar
verschoben wurde, gibt es noch einen Testkandidaten. Im Vergleich zu
Release Candidate 1 ist der zweite nun wesentlich stabiler, dennoch ist
selbstverständlich immer noch jeder dazu aufgefordert Fehlerberichte auf
der Seite
[bugs.kde.org](http://bugs.kde.org/ "http://bugs.kde.org:") einzutragen und mitzuhelfen, dass KDE 4 bald, die von den
vorherigen Versionen bekannte Qualität, erreicht.


KDE 4 RC2 installiert sich in das Verzeichnis /usr/lib/kde4 und kann
daher neben einem bestehenden KDE 3 installiert werden.  

**Update:** Ein Test ohne Installation ist mit der [KDE 4 Live
CD](http://kubuntu.org/~jriddell/cds/kubuntu-kde4-rc2.iso "KDE 4 LiveCD")
möglich.


<!--break--><!--break-->

Anleitung:


-   Zuerst müssen eventuell vorhandene Pakete einer vorherigen KDE 4
    Installation entfernt werden, da sie nicht mehr kompatibel sind mit
    KDE 4 RC2 (apt-get remove kdelibs5 kde4base-data kde4libs-data)
-   Danach folgendes Paketrepositorium zur Datei /etc/apt/sources.list
    hinzufügen "deb
    <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu> gutsy main"
-   Das neue kdebase-bin Paket installieren
-   Die Pakete kdebase-workspace kdebase-kde4 kdebase-runtime
    installieren
-   Die KDE 4 Applikationen erscheinen im KDE 3 K-menü, man kann aber
    auch durch anwählen von "KDE 4" im Login Manager eine vollwertige
    Sitzung starten.
-   Um das Betreiben eines zweiten X-Servers zu vermeiden, kann
    xserver-xephyr installiert werden. Danach Xephyr :1 & export
    DISPLAY=:1; xterm in der Konsole ausführen und startkde in dem
    Xerphyr xterm eingeben.


Die benötigten Pakete werden auch in die Backports-Repositorien von
"Gutsy Gibbon", und in die derzeitige Entwicklungsversion von Kubuntu
"Hardy Heron" heraufgeladen.


Die Ankündigung auf der englischen Seite ist unter
[www.kubuntu.org](http://kubuntu.org/announcements/kde4-rc1.php) zu
finden.



