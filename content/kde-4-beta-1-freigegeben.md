Title: KDE 4 Beta 1 freigegeben
Date: 2007-08-04 09:35
Author: Monika Eggers
Tags: KDE
Slug: kde-4-beta-1-freigegeben

Der erste Beta-Release von KDE 4 ist freigegeben und es sind Pakete für
Kubuntu Feisty (aktueller stabiler Release) und Gutsy
(Entwicklerversion) verfügbar. Nach dieser Veröffentlichung der von
vielen herbeigesehnten vierten Version des K Desktop Environment bleibt
kdelibs, dass von allen anderen KDE-Anwendungen benötigt wird auf einem
stabilen Stand, so dass der Schwerpunkt von jetzt an auf der Integration
anderer Anwendungen liegen wird. KDE4 wird bei Kubuntu parallel zu einem
bestehenden KDE 3 nach ''/usr/lib/kde4'' installiert, so dass man
relativ risikolos testen kann, und offensichtlich nähert sich KDE 4
langsam aber sicher einem benutzbaren Zustand. Allerdings sei hier noch
einmal eindeutig davor gewarnt, ohne das nötige Know-How KDE 4 nutzen zu
wollen. Auch diese Beta-Pakete sind weiter nur für Entwickler gedacht
und eignen sich keinesfalls für den Einsatz auf einem Produktivsystem.


Die Pakete sind für 7.04 in
[feisty-backports](https://help.ubuntu.com/community/UbuntuBackports)
verfügbar und können mit dem Adept Manager installiert werden. Dazu
wählt man unter ''Paketquellen verwalten'' auf dem Reiter ''Updates''
die Auswahlbox ''Nicht unterstützte Aktualisierungen'' an.


### Anleitung:


-   Vergewissert euch, dass ihr
    [feisty-backports](https://help.ubuntu.com/community/UbuntuBackports)
    aktiviert habt oder Gutsy läuft.
-   Installiert kde4base-dev.
-   Diese KDE-4-Pakete werden nach /usr/lib/kde4 installiert, führt
    deshalb folgende Befehle aus:

    
    -   export LD\_LIBRARY\_PATH=/usr/lib/kde4/lib
    -   export KDEDIR=/usr/lib/kde4
    -   export PATH=/usr/lib/kde4/bin:\$PATH
    -   export KDEHOME=\~/.kde4

    
    
-   Um zu vermeiden, für eine vollwertige Sitzung einen zweiten X-Server
    starten zu müssen, installiert xserver-xephyr und startet *Xephyr
    :1; export DISPLAY=:1; xterm*, führt dann *startkde* im Xephyr-xterm
    aus.
-   Um KDE 4 als vollwertige Sitzung starten zu können, kopiert
    /usr/lib/kde4/share/apps/kdm/sessions/kde.desktop nach
    /usr/share/xsessions/kde4.desktop, ändert den Eintrag "Name" in der
    kde4.desktop in "KDE 4", fügt die drei "export" Zeilen von oben am
    Anfang der /usr/lib/kde4/bin/startkde ein und startet im KDM eine
    neue Sitzung mit KDE 4.


Plasma, die neue Desktopoberfläche, scheint zu funktionieren und läuft
ohne Probleme über kdesktop, allerdings fehlt es noch an einigen
Funktionen, so dass Kicker noch nicht ersetzt wurde.


Weiterführende Links:


-   Vorlage
    (<http://wiki.kubuntu-de.org/Team/Redaktion/Nachrichten/02-08-07_KDE_4_Beta_1>)
-   Offizielles Announcement
    (<http://www.kde.org/announcements/announce-4.0-beta1.php>)
-   ProLinux (<http://www.kde.org/announcements/announce-4.0-beta1.php>)


 



