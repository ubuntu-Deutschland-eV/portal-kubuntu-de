Title: KDE 4.1.2 mit Kubuntu Paketen veröffentlicht
Date: 2008-10-04 10:43
Author: Monika Eggers
Tags: KDE
Slug: kde-412-mit-kubuntu-paketen-veroffentlicht

Gestern hat das KDE Team das neuste Wartungs- und Bugfixrelease von KDE4
die Version 4.1.2 unter dem Codenamen "Codename" veröffentlicht. Wie für
diese Wartungsreleases üblich wurde wieder an der Stabilität gearbeitet
und versucht so viele Fehler wie möglich zu beheben.

</p>
Zu den wichtigsten Verbesserungen zählt sicher der
Geschwindigkeitszuwachs beim Löschen von Dateien. Dieser Vorgang konnte
um das 32-fache beschleunigt werden. Weiterhin standen KHTML und die
neue JavaScript Interpreter Frostbyte im Mittelpunkt der Arbeiten, so
konnten auch hier viele Verbesserungen und Fehlerkorrekturen
eingearbeitet werden und die "Stop Animation" Funktion ist wieder im
Konqueror enthalten. Bei Kopete wurden einige Fehler in den ICQ, YAHOO
und Gadu-Gadu Protokollen behoben. Bei KGPG wurden Fehler behoben, die
zum Absturz des Programmes geführt haben. Ebenso wurden das Okular
Backend verbessert und die Thumbnailansicht in Gwenview.

</p>
Mehr Informationen über Änderungen in diesem Release können der
[offiziellen
Ankündigung](http://www.kde.org/announcements/announce-4.1.2.php "http://www.kde.org/announcements/announce-4.1.2.php"){.external
.text} oder [dem
Changelog](http://www.kde.org/announcements/changelogs/changelog4_1_1to4_1_2.php "http://www.kde.org/announcements/changelogs/changelog4_1_1to4_1_2.php"){.external
.text} entnommen werden.

</p>
<!--break--><!--break-->

Diese Version ist schon mit dem Beta-Release von Intrepid Ibex für die
kommende Kubuntu-Version erschienen und verfügbar. Die neuen Pakete für
Hardy Heron sind über das Kubuntu Members KDE 4 Personal Package Archive
(PPA) Paketarchiv erhältlich. Um das Update auf KDE 4.1.2 zu vollziehen,
sind folgende Schritte durchzuführen:

</p>
1\. Mit einem Editor

</p>
               deb http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu hardy main

in der /etc/apt/sources.list einfügen.

</p>
2\. Wenn die kubuntu-kde4-desktop Pakete bereits installiert sind, in
einer Konsole einfach

</p>
               sudo apt-get update && sudo apt-get dist-upgrade

eingeben und die dann erscheinenden Fragen mit "j" beantworten. Wenn
kubuntu-kde4-desktop bisher nicht installiert ist, einfach

</p>
               sudo apt-get update && sudo apt-get install kubuntu-kde4-desktop

eingeben, ebenfalls in einer Konsole, und die dann erscheinenden Fragen
mit "j" beantworten.

</p>
Die Pakete werden nach /usr/lib/kde4 installiert und können so auch
parallel zu KDE3 genutzt werden.

</p>
Danke an Harald, Jon, Steve und Guillaume für die Erstellung der Pakete.

</p>

