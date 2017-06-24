Title: Amarok 2.0 RC 1 "Narwhal" mit Kubuntu-Paketen veröffentlicht
Date: 2008-11-26 22:45
Author: Monika Eggers
Tags: Amarok
Slug: amarok-20-rc-1-narwhal-mit-kubuntu-paketen-veroffentlicht

Schon gestern hat das Amarok Team den ersten Release Kandidaten unter
dem Codenamen "Narwhal" freigegeben. Nur wenige Tage nach der letzten
[Beta
Version](http://www.kubuntu-de.org/nachrichten/software/kde/amarok/amarok-2-0-beta-3-ataksak-mit-kubuntu-paketen-erschienen "http://www.kubuntu-de.org/nachrichten/software/kde/amarok/amarok-2-0-beta-3-ataksak-mit-kubuntu-paketen-erschienen") wurde das Hauptaugenmerk für diese Veröffentlichung auf die
Behebung von Fehlern gelegt. Trotz des "harten" Featurefreeze haben doch
einige Neuerungen den Weg in diese Version geschafft.

</p>
Hierzu zählen unter anderem, dass mit der iTunes Bibliothek jetzt auch
die Statistiken importiert werden können. Ausserdem können die
Trackinformationen im Dateibrowser geändert werden. Die Bearbeitung der
einzelnen Objekte des Wiedergabelisten Browsers kann nun mittels der
Tastatur erfolgen. Die Anzeige des Empfehlungen-Radions des Benutzer
wurde in den Last.fm Service eingebunden. Allerdings wurden auch die
Video und Last.fm Applets deaktiviert, da sie nicht die Produktionsreife
haben. Weitere Informationen über die Neuerungen findet man in der
[Ankündigung des Amarok
Teams](http://amarok.kde.org/en/releases/2.0/rc/1 "http://amarok.kde.org/en/releases/2.0/rc/1")

</p>
<!--break--><!--break-->

Weiterhin sind nicht alle Funktionen der 1.4 Version in Amarok 2.0
enthalten, da diese Version komplett neu geschrieben wurde. Wer sich
dennoch die neue Version von Amarok ansehen will, der findet im "Kubuntu
Members - KDE 4 Repository" bereits Pakete für Kubuntu 8.10, so dass mit
dieser Paketquelle Amarok 2.0 RC 1 wie folgt installiert werden kann:

</p>
-   Zunächst fügt man
    </p>
    <p>

</p>
    deb http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu intrepid maindeb-src http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu intrepid main

  
  

der /etc/apt/sources.list hinzu.

</p>
-   nach einem sudo apt-get update installiert man Amarok 2.0 mit sudo
    apt-get install amarok-kde4
    </p>
    <p>
-   Achtung: Amarok 1.4 wird deinstalliert. Pakete in PPAs (Personal
    Package Archives) sind nicht signiert, so dass eine Warnmeldung
    erscheint.
    </p>
    <p>

</p>
Selbstverständlich ist wie mit jeder Drittquelle auch hier Vorsicht
geboten. Beta-Versionen von Software sollten auf keinen Fall auf
Produktivsystemen eingesetzt werden.

</p>

