Title: KDE 4 - dritter Development Snapshot erschienen
Date: 2007-02-22 18:33
Author: Monika Eggers
Tags: KDE
Slug: kde-4-dritter-development-snapshot-erschienen

Der dritte Development Snapshot von KDE 4 ist veröffentlicht worden und
für Kubuntu Edgy stehen Pakete zur Verfügung. Diese Pakete sind
**nicht** für den produktiven Einsatz gedacht und eignen sich **nur**
für Tester und Entwickler.  

KDE 4 installiert sich nach */usr/lib/kde4* und kann daher neben einem
existierenden KDE 3 verwendet werden. Das Archiv erhält unter anderem
auch einen Snapshot von Okular, dem künftigen Ersatz für KPDF.  

Die Pakete stehen für i368 und amd64 zur Verfügung.


<!--break--><!--break-->

### Installationsanleitung:


-   deb <http://kubuntu.org/packages/kde4-3.80.3/> ./ der
    /etc/apt/sources.list hinzufügen
    
    
-   kde4base-dev installieren, welches das normale QT 4 Paket von
    Kubuntu Edgy benutzt
-   Die KDE 4 Paktete werden nach /usr/lib/kde4 installiert, also ist
    folgendes auszuführen:

    
    -   export LD\_LIBRARY\_PATH=/usr/lib/kde4/lib
    -   export KDEDIR=/usr/lib/kde4
    -   export PATH=/usr/lib/kde4/bin/:$PATH
    -   export KDEHOME=\~/.kde4

    
    
-   Um KDE 4 als eine vollwertige Sitzung nutzen zu können muss
    /usr/lib/kde4/share/apps/kdm/sessions/kde.desktop nach
    /usr/share/xsessions/kde4.desktop, kopiert werden. Der Namenseintrag
    in kde4.desktop muss in "KDE 4" geändert werden und die obigen vier
    Zeilen müssen oben in /usr/lib/kde4/bin/startkde eingefügt werden.
    Nun kann eine neue Sitzung mit KDE 4 im KDM gestartet werden.


Diese News kann
[hier](http://forum.kubuntu-de.org/index.php?topic=7770.0) im Forum
diskutiert werden.



