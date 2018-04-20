Title: KDE SC 4.3.4 vom Kubuntu-PPA in Karmic Backports verschoben
Date: 2010-01-05 20:06
Author: Monika Eggers
Tags: Kubuntu
Slug: kde-sc-434-vom-kubuntu-ppa-in-karmic-backports-verschoben

KDE SC 4.3.4 is nun in den Backports für Karmic Koala auch bekannt als
Kubuntu 9.10. Die Pakete werden bald aus dem PPA entfernt werden.


Selbst wenn man die PPA Pakete schon installiert hat sollte man auf die
Backports Version aktualisieren, denn dort sind einige Fehlerkorrekturen
die die Sicherheit betreffen enthalten, die die PPA Pakete nicht bieten.


<!--break--><!--break-->

Die Backports Quellen sind in der Standardinstallation nicht aktiv, aber
in der /etc/apt/sources.list enthalten. Aus diesem Grund muss man unter
Umständen das Repository aktivieren. Die entsprechende Zeile sollte dann
so aussehen:


    deb http://archive.ubuntu.com/ubuntu/ karmic-backports main restricted universe multiverse

Einige Paketempfehlungen wurden geändert, do dass man bei der
Aktualisierung von 4.3.2 auf 4.3.4 dist-upgrade (oder für aptitude
full-upgrade) benutzen muss.


Diese Nachricht kann im
[Forum](http://forum.kubuntu-de.org/index.php?board=1.0 "http://forum.kubuntu-de.org/index.php?topic=13256.0")
diskutiert werden.



