Title: Zweite Amarok 2 Beta "Nujalik" auch für Kubuntu veröffentlicht
Date: 2008-10-11 07:26
Author: Monika Eggers
Tags: Amarok
Slug: zweite-amarok-2-beta-nujalik-auch-fur-kubuntu-veroffentlicht

Das Team um Amarok hat die zweite Betaversion von Amarok 2 unter dem
Codenamen "Nujalik" veröffentlicht. Seit der ersten Betaversion gab es
einige tiefgreifende Änderungen. Die wichtigste Änderung ist die
Umstellung des Datenbank Backend von SQLite auf MYSQL-Embedded. Dies
soll hauptsächlich Performanceverbesserungen mit sich bringen und für
die Zukunft die Option offen lassen auf einen MYSQL Standalone Server
wechseln zu können. MySQL-Embedded bietet die gute Performance von MySQL
ohne die umständliche Konfiguration eines MySQL Servers.

</p>
Allerdings wurde an allen Komponenten von Amarok gearbeitet. Zu den
erwähnenswertesten Änderungen zählt, dass die Unterstützung des
inkrementellen Scannens wieder vorhanden ist. Nach einer Portierung auf
QtScript ist jetzt acuh LibriVox vorhanden, dadurch ist es möglich frei
verfügbare Audiobücher anzuhören. Auch die Kontextansicht wurde
überarbeitet und die Lyrics und last.fm Applets wurden fehlerbereinigt.
Es wurden allerdings noch mehr Bugs gefixed und insgesamt die Stabilität
von Amarok 2 verbessert. Alle Änderungen und Verbesserungen sind in den
[orginal Release
Announcements](http://amarok.kde.org/de/node/556 "http://amarok.kde.org/de/node/556")
aufgeführt.

</p>
<!--break--><!--break-->

Seit heute stehen auch Kubuntu Pakete zur Verfügung. Diese stehen in dem
PPA-Repository für Hardy und Intrepid zur Verfügung:

</p>
    deb http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu hardy main

(ggf. hardy durch intrepid ersetzen)

</p>
Nach dem Hinzufügen dieser Quelle und der Aktualisierung kann das Paket
amarok-kde4 installiert werden. Die Installation erfolgt nach lib/kde4,
so dass Amarok 1.4 nicht ersetzt wird. Die Anwendung kann anschließend
durch "amarok" gestartet werden, wie auch über das Menü (s. auch
[kubuntu.org](http://amarok.kde.org/en/node/554)).

</p>
Aufgrund des späten Zeitpunktes und der Tatsache das Amarok 2 weiterhin
als Beta vorliegt, wird in Kubuntu 8.10 Intrepid Ibex noch Amarok 1.4
Standard sein.

</p>
**Warnung! Amarok 2 Beta 2 ist für Entwickler und Tester gedacht und
sollte nicht auf Produktivsystemen installiert werden. Softwarefehler
sollten beim KDE [Bugtracker](http://bugs.kde.org "http://bugs.kde.org")
gemeldet werden.**

</p>

