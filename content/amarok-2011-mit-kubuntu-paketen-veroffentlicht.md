Title: Amarok 2.0.1.1 mit Kubuntu Paketen veröffentlicht
Date: 2009-01-12 16:52
Author: Monika Eggers
Tags: Amarok
Slug: amarok-2011-mit-kubuntu-paketen-veroffentlicht

[[![Amarok 2.0.1.1 in
Aktion](http://wiki.kubuntu-de.org/images/thumb/Amarok2.0.1.1.png/150px-Amarok2.0.1.1.png){.thumbimage
width="180"
height="113"}](http://wiki.kubuntu-de.org/Bild:Amarok2.0.1.1.png "Amarok 2.0.1.1 in Aktion")]{.inline
.inline-right}Das Team der Amarok Entwickler hat heute die erste
Weiterentwicklung der stabilen Version 2.0 freigegeben. Amarok 2.0.1.1,
Codename "Magellan", beinhaltet hauptsächlich Fehlerkorrekturen, daneben
wurden jedoch auch einige neue Fähigkeiten hinzugefügt sowie weitere
Fähigkeiten aus der Version 1.4 übernommen. So kann man nun die
Wiedergabeliste filtern, nach eigenen Bedürfnissen konfigurieren und die
Sammlung nach dem Interpreten sortieren. Durch Optimierung des Programms
haben die Entwickler erreicht, dass Amarok nun erheblich weniger
Speicher belegt und daher bedeutend schlanker als die Vorgängerversion
ist. Eine vollständige Übersicht der Verbesserungen und Änderungen kann
der [Release
Ankündigung](http://amarok.kde.org/en/releases/2.0.1.1 "http://amarok.kde.org/en/releases/2.0.1.1") entnommen werden.

</p>
Die aktuelle Kubuntu Version "Intrepid Ibex" verwendet noch Amarok
1.4.10, da Amarok 2.0 zum Zeitpunkt der Veröffentlichung dieser Version
noch nicht fertig war. Es existiert allerdings eine inoffizielle Version
von Amarok 2.0 im "Kubuntu Members PPA", die wie folgt installiert
werden kann:

</p>
<!--break--><!--break-->

-   Zunächst muss man das PPA der */etc/apt/sources.list* hinzufügen:
    </p>
    <p>

</p>
    deb http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu intrepid main

Details zum Thema Paketquellen können
[diesem](http://wiki.kubuntu-de.org/Konfiguration/Programme_installieren/Paketmanagement/Paketquellen "http://wiki.kubuntu-de.org/Konfiguration/Programme_installieren/Paketmanagement/Paketquellen") Artikel entnommen werden.

</p>
-   hiernach muss eine Aktualisierung durchgeführt werden, was man zum
    Beispiel so machen kann:
    </p>
    <p>

</p>
``` {.shell}
sudo apt-get update
```

-   und zuletzt muss man nur noch Amarok installieren:
    </p>
    <p>

</p>
``` {.shell}
sudo apt-get install amarok-kde4
```

-   Nutzer von Amarok 2.0 können bei aktivierter Paketquelle einfach
    einfach ein Upgrade machen.
    </p>
    <p>

</p>
Achtung! Es handelt sich nicht um offizielle Pakete für Kubuntu 8.10.
Auf einem Produktivsystem ist daher Vorsicht geboten. Amarok 1.4.10 wird
bei der Installation von *amarok-kde4* deinstalliert.

</p>

