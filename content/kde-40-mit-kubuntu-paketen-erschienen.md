Title: KDE 4.0 mit Kubuntu Paketen erschienen!
Date: 2008-01-11 12:01
Author: Monika Eggers
Tags: KDE
Slug: kde-40-mit-kubuntu-paketen-erschienen

[![Bild:KDE.png](http://wiki.kubuntu-de.org/images/Kde.png){width="100"
height="100"}](http://wiki.kubuntu-de.org/images/Kde.png "Bild:KDE4-Plasma.png"){.image}

</p>
[Eine Vision wird Wirklichkeit]{.mw-headline}
=============================================

</p>
 Wie geplant, haben die KDE Entwickler heute die erste stabile Version
von KDE 4.0 freigegeben. Diese Freigabe markiert den Startpunkt der KDE
4 Ära. Die Desktopumgebung erfuhr umfangreiche Änderungen und
Verbesserungen. Mehr dazu in unserem Artikel. Die Kubuntu Entwickler
stellen Pakete für Kubuntu 7.10 Gutsy Gibbon und 8.04 Hardy Heron zur
Verfügung.

</p>
Nach mehreren Jahren intensiver Entwicklungsarbeit und zuletzt mehreren
Monaten Verspätung ist der Traum der
[KDE-Gemeinschaft](http://www.kde.org) Wirklichkeit geworden: KDE 4.0
ist endlich erschienen. Die Ansprüche an den runderneuerten Desktop sind
hoch: Nicht mehr und nicht weniger als die Revolution des Desktops wurde
angestrebt. Dennoch sollte man von der heute freigegebenen Version 4.0
nicht zu viel erwarten, denn einige spannende Features der neuen
Desktopoberfläche sind derzeit noch nicht vollständig implementiert.
Deshalb muss betont werden: KDE 4.0 ist nicht KDE4 wie Entwickler
Stephan Binner aka beineri in [seinem
Blog](http://www.kdedevelopers.org/node/3174 "http://www.kdedevelopers.org/node/3174") schreibt, vielmehr ist es der Anfang eines Jahre andauernden
Release-Zyklus.

</p>
### [![Bild:KDE4-Plasma.png](http://wiki.kubuntu-de.org/images/KDE4-Plasma.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Plasma.png "Bild:KDE4-Plasma.png"){.image} [![Bild:KDE4-Plasma2.png](http://wiki.kubuntu-de.org/images/KDE4-Plasma2.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Plasma2.png "Bild:KDE4-Plasma2.png"){.image}[![Bild:KDE4-Konqueror.png](http://wiki.kubuntu-de.org/images/KDE4-Konqueror.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Konqueror.png "KDE4-Konqueror.png"){.image} {#bildkde4-plasma.png-bildkde4-plasma2.pngbildkde4-konqueror.png align="center"}

</p>
**Update:** *The English Translation could be found
[here](http://www.kubuntu-de.org/english/kde-4-0-released-packages-kubuntu-available).
(Die Englische Übersetzung ist
[hier](http://www.kubuntu-de.org/english/kde-4-0-released-packages-kubuntu-available)
zu finden. )*

</p>
<!--break--><!--break-->

[]{#F.C3.BCr_ganz_Eilige:_Installation_von_KDE_4.0_unter_Gutsy_Gibbon}

</p>
[Für ganz Eilige: Installation von KDE 4.0 unter Gutsy Gibbon]{.mw-headline}
----------------------------------------------------------------------------

</p>
Für Kubuntu 7.10 Gutsy Gibbon und die aktuelle Entwicklungsversion sind
bereits Pakete verfügbar.

</p>
KDE 4.0 installiert sich in das Verzeichnis /usr/lib/kde4 und kann daher
neben einem bestehenden KDE 3 installiert werden. Ein Test ohne
Installation ist mit der KDE 4 [Live
CD](http://cdimage.ubuntu.com/kubuntu/releases/gutsy/kde4/) möglich.

</p>
Anleitung:

</p>
-   Zuerst müssen eventuell vorhandene Pakete einer vorherigen KDE 4
    Installation entfernt werden, da sie nicht mehr kompatibel sind mit
    KDE 4 (*apt-get remove kdelibs5 kde4base-data kde4libs-data*)
-   Danach folgende Paketquelle zur Datei /etc/apt/sources.list
    hinzufügen "deb
    <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu> gutsy main"
-   Das Paket "kde4-core" installieren. Dabei sollte beachtet werden,
    das persönliche Paketarchive nicht mit einem Schlüssel
    authentifiziert werden. Bei der Installation muss also eine Warnung
    bestätigt werden.
-   Die KDE 4 Applikationen erscheinen im KDE 3 KMenü, man kann aber
    auch durch Anwählen von "KDE 4" in der Anmeldemaske eine vollwertige
    Sitzung starten.
-   Um das Betreiben eines zweiten X-Servers zu vermeiden, kann
    xserver-xephyr installiert werden. Danach Xephyr :1 & export
    DISPLAY=:1; xterm in der Konsole ausführen und startkde in dem
    Xerphyr xterm eingeben.

</p>
[]{#Das_Wichtigste_im_.C3.9Cberblick}

</p>
[ Das Wichtigste im Überblick]{.mw-headline}
--------------------------------------------

</p>
Das Offensichtlichste ist erstmal die neue Fensterdekoration und das
neue Iconset: [Oxygen](http://www.oxygen-icons.org/) orientiert sich an
den Vorgaben des freedesktop.org Projekts und sorgt so für ein
einheitliches, konsistentes und wahnsinnig gut aussehndes Äußeres der
neuen Desktopumgebung Plasma, die nun auch das neue Panel bereitstellt,
und es ermöglicht zahlreiche kleine Anwendungen, sogenannte Widgets, zu
starten.

</p>
Hinzu kommen unzählige kleine und größere Änderungen an der
Benutzeroberfläche. So gibt es einen neuen Datei-Öffnen Dialog, Dolphin
ist ein ausgewachsener Dateimanager geworden, der kaum Wünsche
übriglässt und der Befehl-Ausführen-Dialog wurde um zahlreiche nützliche
Features erweitert. Nicht zu vergessen ist Kickoff, welches das alte
KMenu ersetzt, das alte KMenü ist aber auch weiterhin vorhanden.

</p>
Alle diese Änderungen würden allerdings höchstens ein 3.6.x Release
rechtfertigen, wenn es denn die Einzigen wären. Die wichtigsten
Änderungen in KDE 4.0 sind für den Nutzer unsichtbar. Die
[KDE-Community](http://www.kde.org) hatte sich entschieden einen
Großteil der Basis zu überarbeiten. Den Anfang machte hierbei die
Portierung auf das Qt-Toolkit von Trolltech in der Version 4, das es
ermöglicht KDE4 Anwendungen unter allen bekannten Betriebsystemen laufen
zu lassen. Alle grundlegenden Programmbibliotheken - die kdelibs -
wurden entschlackt und überarbeitet.

</p>
Dazu kamen viele Basistechnologien, die es vor allem erleichtern sollen
Anwendungsprogramme für KDE4 zu schreiben. Einige dieser
Basistechnologien wie Solid und Phonon werden schon in der Version 4.0
enthalten sein, andere wie Decibel oder Akonadi erst mit den
Folgeversionen. Auch wenn sich diese Technologien für den Nutzer sehr
versteckt und im Hintergrund halten, wird ihre volle Wirkung erst mit
ihrer Einbettung in den Anwendungsprogrammen zutage treten und nach und
nach das volle Potenzial von KDE 4 freilegen.

</p>
[]{#Grundlegendes}

</p>
[ Grundlegendes]{.mw-headline}
------------------------------

</p>
[]{#Plattformunabh.C3.A4ngigkeit}

</p>
### 

</p>
### [ Plattformunabhängigkeit]{.mw-headline}

</p>
Bei der Entwicklung von KDE4 wurde ebenfalls großer Wert auf die
Plattformunabhängigkeit gelegt. KDE4 Applikationen sollen problemlos auf
allen Systemen (Windows, Mac OS X, usw.) laufen und werden derzeit
portiert. Dies ist unter anderem durch die hohe Flexibilität von Qt
möglich. So wurde beispielsweise Amarok 2 nach knapp 2 Tagen auf Windows
zum ersten Mal kompiliert und gestartet. Eine Portierung von Plasma ist
derzeit nicht geplant, auch wenn die Entwickler bereits verlauten
ließen, dass es sie nicht wundern würde, wenn "irgendein Verrückter"
Plasma auf Windows portieren würde. In einem Proof-of-Concept wurde
Plasma bereits auf dem Neo1973 Smartphone kompiliert und gestartet.

</p>
[]{#Qt_4}

</p>
### 

</p>
### [ Qt 4]{.mw-headline}

</p>
Das [Qt-Toolkit](http://trolltech.com/products/qt/homepage) der Firma
Trolltech ist das Fundament von KDE und mit der neuen Generation Qt4 hat
sich einiges geändert. So wurde beispielsweise die gesamte Bibliothek
feiner unterteilt was Programme kleiner und speicherschonender machen
soll. Dies führte dazu, dass die neue KDE-Version sehr viel weniger
Speicher benötigt als sein Vorgänger. Ein wichtiger Bestandteil von Qt 4
ist die neue Paintengine "Arthur", welche auch unter anderem OpenGL
weitaus effektiver nutzen kann als Qt 3. Auch eine umfangreiche
SVG-Funktionalität wurde hinzugefügt.  

Qt4.4 (Veröffentlichung für das 1. Quartal 2008 geplant) steht bereits
in den Startlöchern und wird unter anderem Amarok 2 als Grundlage
dienen.

</p>
[]{#Phonon}

</p>
### [ Phonon]{.mw-headline}

</p>
[Phonon](http://phonon.kde.org/) ist entgegen einiger Befürchtungen kein
neues Soundsystem im Sinne von GStreamer oder ähnlichem, sondern eine
Schicht zwischen dem Soundsystem und Audioprogrammen. Phonon ist nicht
dazu gedacht komplexe Multimedibearbeitung zu ermöglichen sondern dient
der einfachen Aus- und Eingabe von Multimediadaten an ein Backend (wie
z.B. GStreamer, Xine, usw.). Ein Vorteil ist hier beispielsweise die
Plattformunabhängigkeit aber auch die Flexibilität. So brauchen KDE4
Anwendungen keinerlei Kenntnis von der unterliegenden
Multimediaarchitektur zu haben, sondern sprechen diese über Phonon an.

</p>
Es muss auch nicht extra auf jeder Plattform ein Soundsystem installiert
werden damit KDE4 Programme funktionieren. Sie können einfach über ein
Backend auf die Fähigkeiten der unterliegenden Plattform zugreifen.
Sollte der Benutzer während der Arbeit sich dazu entscheiden das
Soundsystem zu wechseln, braucht Phonon nur das Backend auszutauschen,
ohne dass die laufenden KDE4 Applikationen davon beeinträchtigt werden.
Somit gehören Probleme wie ein schlafender Artsdaemon (aRts wurde in
KDE3 und darunter zum Abspielen und Aufzeichen von Sounds verwendet),
dessen Puffer sich mit der Zeit füllte und sich beim Aufwecken in einem
Wust aus übereinanderliegenden Geräuschen entleerte, endgültig der
Vergangenheit an. Zusätzlich wird es auch möglich sein die Soundausgabe
von Programmen aufeinander reagieren zu lassen. Während der Benutzer
beispielsweise einen Webstream ansieht, könnten alle anderen Programme
kurzzeitig stummgeschaltet werden.  

Trolltech hat bereits angekündigt, dass Phonon Teil der nächsten Qt
Versionen werden wird.

</p>
### [](http://wiki.kubuntu-de.org/Bild:KDE4-Systemeinstellungen.png "Bild:KDE4-Systemeinstellungen.png"){.image}

</p>
### [![Bild:KDE4-Systemeinstellungen.png](http://wiki.kubuntu-de.org/images/KDE4-Systemeinstellungen.png){width="160" height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Systemeinstellungen.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Solid.png](http://wiki.kubuntu-de.org/images/KDE4-Solid.png){width="160" height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Solid.png)[![Bild:KDE4-Phonon.png](http://wiki.kubuntu-de.org/images/KDE4-Phonon.png){width="160" height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Phonon.png) {#bildkde4-systemeinstellungen.pngbildkde4-solid.pngbildkde4-phonon.png align="center"}

</p>
###  

</p>
[]{#Solid}

</p>
### [ Solid]{.mw-headline}

</p>
[Solid](http://solid.kde.org/) ist wie Phonon ein Framework und
ermöglicht KDE4 Applikationen den Zugriff oder das Ansprechen der
Hardware. So sorgt ein Backend des Networkmanager dafür, dass Programme
immer den Status der Netzwerkanbindung kennen. Verlässt man
beispielsweise einen WLAN-Hotspot, schalten alle Programme, die eine
Internetverbindung benötigen, in den Offlinemodus. Da Solid aber noch
recht neu ist muss diese Technologie noch in die Programme implementiert
werden. Desweiteren verfügt Solid derzeit über Backends für die
Energieverwaltung und Bluetooth.

</p>
[]{#Strigi}

</p>
###  

</p>
### [ Strigi]{.mw-headline}

</p>
Strigi ist die schon aus Gutsy Gibbon bekannte kleine, sehr schnelle,
indexbasierte Desktopsuche. Im Gegensatz zur KDE 3 Version ist sie nun
wesentlich ausgereifter und ist zusammen mit den semantischen Funktionen
von Nepomuk ein mächtiges Suchwerkzeug. Ähnlich wie mit Beagle unter
Gnome lassen sich nun die eigenen Dateien indizieren und schnell
durchsuchen. Zudem arbeitet Strigi sehr ressourcenschonend und belastet
das System nicht so stark wie andere Desktop-Suchmaschinen.

</p>
[]{#Nepomuk-KDE}

</p>
### [ Nepomuk-KDE]{.mw-headline}

</p>
[Nepomuk](http://nepomuk-kde.semanticdesktop.org/xwiki/bin/view/Main/WebHome)
ist kein reines KDE-Projekt sondern ein großes Forschungs und
Entwicklungsprojekt, in dem dem zahlreiche Firmen, Forscher und
Entwickler daran arbeiten die Vision eines semantischen Desktops
umzusetzen und so das Informationsmanagement mittels
Informationstechnologie zu revolutionieren.

</p>
Mit der Implementation von Nepomuk in KDE4 ist es nun möglich Dateien zu
bewerten, zu kommentieren und mit Schlagworten (sogenannten Tags) zu
versehen. Ähnlich wie beim Durchssuchen von Blogs oder Multimediaseiten
wie Youtube, ist es mit Nepomuk möglich einfach nur nach den jeweiligen
Tags zu suchen. Da diese auch nach dem Umbenennen von Dateien erhalten
bleiben, lassen sich so auch versehentlich umbenannte Dateien einfach
und schnell wiederfinden. Mit dem Tagsystem lassen sich Dateien auch
nach Inhalten ordnen. So könnte man ein Tag mit der Bezeichnung "Hund"
anlegen, welches sämtliche Videos oder Bilder auf denen ein Hund zu
sehen, beinhaltet. Nepomuk ist bereits in Dolphin integriert.

</p>
[]{#Die_Sichtbarsten_Ver.C3.A4nderungen_gegen.C3.BCber_KDE_3.5.x}

</p>
[ Die Sichtbarsten Veränderungen gegenüber KDE 3.5.x]{.mw-headline}
-------------------------------------------------------------------

</p>
[]{#Plasma}

</p>
### [ Plasma]{.mw-headline}

</p>
Die sicherlich auffälligste Veränderung an KDE4 ist
[Plasma](http://plasma.kde.org/), der neue Desktop. Hier wird voll und
ganz auf das Konzept von Widgets gesetzt. Hinter den Widgets verbergen
sich kleine Programme, die unter anderem den Ladestand des Akkus,
RSS-Feeds oder Uhren auf dem Desktop anzeigen. Die Widgets lassen sich
nicht nur frei auf dem Desktop platzieren, sondern können auch in der
Taskbar platziert werden. Hierfür mussten früher 2 unterschiedliche
Programme geschrieben werden.

</p>
Das Widget selbst erkennt in welchem Umfeld es abgelegt wurde und passt
sich in Größe und Verhalten seiner Umgebung an. So würde zum Beispiel
ein Widget welches viele Informationen anzeigt sich in der Taskbar
platzsparend verhalten und nur wenig ausgewählte Informationen anzeigen
und auf dem Desktop eventuell noch eine passende Grafik oder dergleichen
präsentieren. Da die Miniprogramme komplett auf SVG Vektorgrafiken
basieren, sind sie frei rotierbar und können beliebig skaliert werden.

</p>
Ein weiterer Ansatz ist die neue Taskbar, die selbst nur ein Widget ist,
in dem weitere Widgets abgelegt werden können. So sind die Taskleiste,
der K-Button oder die Systray nichts anderes als Widgets, die man je
nach Belieben platzieren oder austauschen kann. Damit kann sich jeder
Benutzer einen komplett individuellen Desktop zusammenstellen.

</p>
Da Plasma eines der letzten Projekte ist, die in der Entwicklung von
KDE4 in Angriff genommen wurden, gibt es derzeit noch recht wenige
Widgets zur Auswahl. Zudem ist das Panel nur sehr eingeschränkt
konfigurierbar.

</p>
 

</p>
[]{#Systemeinstellungen}

</p>
### [ Systemeinstellungen]{.mw-headline}

</p>
Lange war KControl für die Konfiguration von KDE zuständig. Für viele
Benutzter war es allerdings wegen seiner vielen Optionen und der
Struktur zu unübersichtlich. Kubuntu hat deshalb die Systemeinstellungen
eingeführt, was nun seinen Weg in KDE4 gefunden hat, um KControl zu
ersetzen. Die Übersichtlichkeit des Konzepts macht es KDE Neulingen
einfach die Umgebung nach ihren Wünschen einzurichten, bietet aber auch
weiterhin erfahrenen Benutzern tiefgreifende Möglichkeiten den Desktop
zu konfigurieren.

</p>
<div align="center">

[![Bild:KDE4-Dophin-gruppiert.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-gruppiert.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-gruppiert.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Dolphin-Spalten.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-Spalten.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Dolphin-Spalten.png "Bild:KDE4-Dolphin-Spalten.png"){.image}[![Bild:KDE4-Dolphin-Symbole.png](http://wiki.kubuntu-de.org/images/KDE4-Dolphin-Symbole.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Dolphin-Symbole.png "Bild:KDE4-Dolphin-Symbole.png"){.image}

</div>

</p>
[]{#Dolphin}

</p>
### [Dolphin]{.mw-headline}

</p>
Der Dateimanager Dolphin wurde für KDE4 komplett neugeschrieben. Neben
den Funktionen für Nepomuk bietet er auch ein neues Anzeigemodell, das
Dateien in Gruppen sortiert und verwalten lässt (z. B. alphabetisch,
nach Benutzerrechten usw.). Die Baumansicht, die viele Nutzer bei der
KDE 3 Version von Dolphin so vermisst haben, ist wieder vorhanden. Und
eine Spaltenansicht, wie sie von OS X bekannt ist wurde implementiert,
sodass Dolphin sich nun mit umfangreichen Funktionen ausgestattet ganz
auf die Dateiverwaltung konzentrieren kann, was nun auch seine
Hauptaufgabe ist. Es ist natürlich auch weiterhin möglich Konqueror als
Dateimanager zu nutzen.

</p>
  

</p>
[]{#Oxygen}

</p>
### [Oxygen]{.mw-headline}

</p>
Das neue Gesicht von KDE trägt den Namen
[Oxygen](http://www.oxygen-icons.org/). Hierzu gehört nicht nur ein
neues Look&Feel für die Fenster sondern auch eine ganze Wagenladung an
Icons, die an den Benennungsstandard von
[freedesktop.org](http://www.freedesktop.org) angepasst wurden.
Erklärtes Ziel war es die Icons einheitlich und zueinander passend zu
gestalten und im Vektorformat SVG zu Verfügung zu stellen. Dies
ermöglicht freie Skalierbarkeit sowie dynamische Farbänderungen. Ein
passender KDE-Stil mit dazugehörigem Cursor-Theme und neue Sounds runden
das Gesamtbild ab.

</p>
[]{#KWin}

</p>
### [ KWin]{.mw-headline}

</p>
Seit der Einführung von AIGLX ist der XServer in der Lage grafische
Effekte im Stile von Mac OS X darzustellen. Für solche Effekte wird ein
so genannter Compositemanager wie z.B. Compiz-Fusion benötigt. Da
Compositing nicht nur schön aussieht, sondern auch interessante
Möglichkeiten für die Bedienbarkeit ermöglichen, hat man KWin mit einem
eigenen Compositemanager ausgestattet, die bei Bedarf - und geeigneter
Hardware - aktiviert werden können. Die einzelnen Effekte lassen sich je
nach Belieben an und abschalten.

</p>
[]{#KRunner}

</p>
### [ KRunner]{.mw-headline}

</p>
Während man früher mit dem Menüpunkt "Befehl ausführen" nur Befehle
ausführen konnte, wurde nun als Ersatz KRunner integriert. KRunner wurde
stark erweitert und vereint nun Katapult, Strigi und die Kommandozeile
in sich. Wird ein Begriff eingegeben, werden alle Quellen gleichzeitig
durchsucht und je nach Ergebnis unterschiedliche Optionen zur Auswahl
angeboten.

</p>
 

</p>
<div align="center">

[![Bild:KDE4-Krunner.png](http://wiki.kubuntu-de.org/images/KDE4-Krunner.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Krunner.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Okular.png](http://wiki.kubuntu-de.org/images/KDE4-Okular.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Okular.png "Bild:KDE4-Systemeinstellungen.png"){.image}[![Bild:KDE4-Kwin.png](http://wiki.kubuntu-de.org/images/KDE4-Kwin.png){width="160"
height="100"}](http://wiki.kubuntu-de.org/Bild:KDE4-Kwin.png "Bild:KDE4-Systemeinstellungen.png"){.image}

</div>

</p>
[]{#Ausblick_auf_KDE_4.x}

</p>
[ Ausblick auf KDE 4.x]{.mw-headline}
-------------------------------------

</p>
Ganz nach dem Paradigma der OpenSource-Welt "Release often, release
early" (Veröffentliche oft und früh), sind in dieser ersten Freigabe von
KDE4 einige Kerntechnologien des KDE4-Desktops noch nicht vorhanden.
Dazu gehört vor allem Akonadi, die Basis für das Persönliche
Informationsmanagement in KDE. [Akonadi](http://pim.kde.org/akonadi/)
soll eine zentrale Basis für alle Arten von Groupware-Daten bieten, auf
die dann alle Programme einfach und zugreifen können. Dabei soll
vermieden werden, dass sich die Programme in die Quere kommen oder die
Daten von einem Format in das andere konvertiert werden müssen.

</p>
Hauptsächlich ist zu erwarten, dass viele der bereits vorhandenen
Technologien in die Anwendungsprogramme implementiert werden und nach
und nach alle KDE Programme auf Qt4 und KDE4 portiert werden. Dazu
gehören auch einige wichtige Anwendungsprogramme, wie beispielsweise
[Amarok](http://amarok.kde.org) oder [KOffice](http://www.koffice.org/),
dessen Version 2.0 nicht rechtzeitig zum Veröffentlichungstermin
fertiggestellt werden konnte, in das aber große Hoffnungen gesetzt
werden. Insbesondere soll KOffice2 einmal zur Standard Office-Software
für Kubuntu werden.

</p>
Heiß erwartet wird auch der Audioplayer Amarok2. Dieser wird eine
komplett überarbeite Benutzeroberfläche bieten, die den Kontextbrowser
in den Mittelpunkt stellt. Die beliebten Online-Dienste, wie das Abrufen
von Kontextinformationen aus der Wikipedia oder die Einbindung des
Magnatune-Shops bekommen Gesellschaft.

</p>
[]{#Quellen}

</p>
 
-

</p>

