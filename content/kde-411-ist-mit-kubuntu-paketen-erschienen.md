Title: KDE 4.1.1 ist mit Kubuntu Paketen erschienen
Date: 2008-09-03 20:41
Author: Monika Eggers
Tags: KDE
Slug: kde-411-ist-mit-kubuntu-paketen-erschienen

KDE 4.1.1 ist heute unter dem Codenamen "Cebidae" erschienen und es sind
Pakete für Kubuntu 8.04 Hardy Heron erhältlich. Diese Pakete
installieren sich, wie auch bei den anderen Versionen von KDE 4, in
/usr/lib/kde4 und können somit parallel zu einer existierenden
KDE-3-Installation laufen.


Verbesserungen gab es in fast allen Teilen von KDE: So wurde
beispielsweise die Performance, die Handhabung und die Genauigkeit des
Renderers in Konqueror bzw. von KHTML verbessert. Auch die Stabilität
und die Benutzerinteraktion von Plasma haben Verbesserungen erfahren.
Korrekturen gab es auch am PDF-Backend in Okular und der
Thumbnailansicht von Gwenview. Abgerundet wird das Ganze von einer
erhöhten Stabilität und verbesserten Interaktion in KMail. Sämtliche
Änderungen können in der [offiziellen
Ankündigung](http://dot.kde.org/1220442784/)nachgelesen werden.


<!--break--><!--break-->

Die neuen Pakete sind über das Kubuntu Members KDE 4 Personal Package
Archive (PPA) Paketarchiv erhältlich. Um das Update auf KDE 4.1.1 zu
vollziehen, sind folgende Schritte durchzuführen:


1.  Mit einem Editor  

    
          *deb <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu>
    hardy main*  

    in der /etc/apt/sources.list einfügen.

    
2.  Wenn die kubuntu-kde4-desktop Pakete bereits installiert sind, in
    einer Konsole einfach  

    
          *sudo apt-get update && sudo apt-get dist-upgrade*  

    eingeben und die dann erscheinenden Fragen mit "j" beantworten. Wenn
    kubuntu-kde4-desktop bisher nicht installiert ist, einfach  

          <em>sudo apt-get update && sudo apt-get install
    kubuntu-kde4-desktop  

    
    </em>eingeben, ebenfalls in einer Konsole, und die dann
    erscheinenden Fragen mit "j" beantworten.


Danke an Harald, Jon, Steve und Guillaume für die Erstellung der Pakete.
Besonderen Dank an Scott für die Nachtschicht, um die Pakete für Kubuntu
Intrepid Alpha 5 fertig zu bekommen.



