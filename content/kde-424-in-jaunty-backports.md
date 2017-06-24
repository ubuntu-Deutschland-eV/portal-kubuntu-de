Title: KDE 4.2.4 in Jaunty Backports
Date: 2009-09-29 20:03
Author: Monika Eggers
Tags: Kubuntu
Slug: kde-424-in-jaunty-backports

KDE 4.2.4 steht schon einige Zeit in einem PPA zur Verfügung und wurde
nun in die offiziellen Backports verschoben. Die neuen Pakete stellen
unter anderem einige zusätzliche und auch sicherheitsrelevante
Fehlerkorrekturen zur Verfügung, so dass auch Nutzer, die bereits die
Pakete aus dem PPA genutzt haben eine Aktualsierung vornehmen sollten.
Die Pakete im Updates PPA werden in Kürze gelöscht.

</p>
Die offiziellen Backports sind in der Standardinstallation nicht aktiv,
so dass man die entsprechende Zeile in der */etc/apt/sources.list*
auskommentieren muss. Hierfür reicht es, wenn man die Raute (\#) vor

</p>
    deb-src http://de.archive.ubuntu.com/ubuntu/ jaunty-backports main restricted universe multiverse

oder einer ähnlichen Angabe entfernt und danach eine vollständige
Aktualsierung, zum Beispiel mit

</p>
``` {.shell}
sudo apt-get update && sudo apt-get dist-upgrade
```

Diese Nachricht kann im
[Forum](http://forum.kubuntu-de.org/index.php?board=1.0 "http://forum.kubuntu-de.org/index.php?board=1.0"){.external
.text} diskutiert werden.

</p>

