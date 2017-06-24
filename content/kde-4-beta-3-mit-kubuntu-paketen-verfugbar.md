Title: KDE 4 Beta 3 mit Kubuntu Paketen verfügbar
Date: 2007-10-19 13:04
Author: Monika Eggers
Tags: KDE
Slug: kde-4-beta-3-mit-kubuntu-paketen-verfugbar

<div id="outerColumnContainer">

</p>
<div id="innerColumnContainer">

</p>
Das dritte Beta Release von KDE 4 wurde veröffentlicht und es sind
Pakete für Kubuntu Gutsy verfügbar. Pakete für 7.04 werden gerade
kompiliert und sollten bald in feisty-backports verfügbar sein.

</p>
KDE 4 Beta 3 installiert sich in Kubuntu in */usr/lib/kde4* und kann
daher neben einem bestehenden KDE 3 installiert werden.

</p>
<!--</p><p><p>The packages are in <a href="https://help.ubuntu.com/community/UbuntuBackports">feisty-backports</a>, available from Adept Manager when you choose <em>Unsupported Updates</em> from the <em>Updates</em> tab of <em>Manage Repositories</em>.</p></p><p><p>Packages are also in the Gutsy development version.</p></p><p>--><!--</p><p><p>The packages are in <a href="https://help.ubuntu.com/community/UbuntuBackports">feisty-backports</a>, available from Adept Manager when you choose <em>Unsupported Updates</em> from the <em>Updates</em> tab of <em>Manage Repositories</em>.</p></p><p><p>Packages are also in the Gutsy development version.</p></p><p>-->

### Anleitung:

</p>
-   kdebase-workspace und kde4base-dev installieren.
-   Die KDE 4 Pakete installieren nach /usr/lib/kde4, deshalb muss
    Folgendes ausgeführt werden:

    </p>
    -   export LD\_LIBRARY\_PATH=/usr/lib/kde4/lib
    -   export KDEDIRS=/usr/lib/kde4
    -   export PATH=/usr/lib/kde4/bin/:\$PATH
    -   export KDEHOME=\~/.kde4

    </p>
    <p>
-   Um das Starten eines zweiten X-Servers zu vermeiden, kann
    xserver-xephyr installiert werden. Danach *Xephyr :1 & export
    DISPLAY=:1; xterm* in der Konsole ausführen und *startkde* in dem
    Xerphyr xterm eingeben.
-   Um KDE 4 als volle Sitzung zu starten muss
    /usr/lib/kde4/share/apps/kdm/sessions/kde.desktop nach
    /usr/share/xsessions/kde4.desktop kopiert werden, danach muss der
    Namenseintrag in kde4.desktop in "KDE 4" umbenannt werden und die
    vier "Export Zeilen" an den Anfang von /usr/lib/kde4/bin/startkde
    gesetzt werden. Nun kann eine neue Sitzung "KDE 4" in KDM gestartet
    werden.

</p>
[Hier](http://kubuntu.org/announcements/kde4-beta3.php) ist das original
Announcement von kubuntu.org zu finden.

</div>

</p>
<p>

</div>

</p>
<!--break--><!--break-->
