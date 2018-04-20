Title: Kubuntu 8.04 Hardy Heron Alpha 1 erschienen
Date: 2007-12-03 20:52
Author: Monika Eggers
Tags: Kubuntu
Slug: kubuntu-804-hardy-heron-alpha-1-erschienen

Am 29. August 2007 hat Jono Bacon die nächste Version (8.04) von Kubuntu
unter dem Codenamen Hardy Heron auf der Ubuntu Entwickler-Mailinglist
bekannt gegeben. Das Hauptaugenmerk für Kubuntu 8.04 für die
Kubuntu-Community liegt auf der Stabilität des Systems. Als weiteres
Ziel planen die Kubuntu Entwickler eine neue Strategie zu
implementieren, die es Kubuntu erlauben soll zu einiger Funktionalität
von Ubuntu aufzuschließen. Die Standard KDE Version wird 3.5.x sein.
Keine Angst für diejenigen, die auf Kubuntu und KDE 4 warten, die Pakete
sind verfügbar und es gibt eine LiveCD mit Kubuntu Gusty Gibbon und KDE
4.  

Alpha 1 ist der aktuellste Snapshot von Hardy, sowie die erste in einer
Serie von Meilensteinen von CD Images, welche während der Hardy
Entwicklung freigegeben werden. Die Vorfreigaben sollten frei sein von
CD-build- oder Installationsfehlern, sie sind allerdings nicht empfohlen
für den Einsatz in Produktivumgebungen. Diese Freigaben sind für
diejenigen, die entwickeln, dokumentieren und testen wollen gedacht. Die
Alphafreigabe kann
[hier](http://cdimage.ubuntu.com/kubuntu/releases/hardy/)
heruntergeladen werden.


**Achtung:** Kubuntu 8.04 ist eine Alpha-Version. Diese sollte auf
keinen Fall auf Systemen benutzt werden, die Stabilität erfordern.
Vorversionen von Kubuntu 8.04 sind für Kubuntu Entwickler und Benutzer
gedacht, die beim Testen, Berichten und Beseitigen von Fehlern helfen
wollen.  

Screenshots werden bald unter diese
[Link](http://www.thecodingstudio.com/opensource/linux/?q=node/55) zur
Verfügung stehen.


<!--break--><!--break-->

Neues in Kubuntu Hardy Heron Alpha 1
------------------------------------


Die erste CD-Version von Hardy Heron bringt viele Updates sowie neue und
aufregende Applikationen. Für die aktuelle Version von Kubuntu 8.04
wurden die Standards der Benutzerfreundlichkeit verbessert und bereits
einige ästhetische Veränderungen vollzogen. Neben diesen Änderungen,
wurden ebenfalls Updates zu vielen bekannten Anwendungen sowie Bugfixes
eingespielt. Mit jeder neuen Vorversion werden die Updates dokumentiert,
sodas die Testinstallation von Kubuntu 8.04 gründlich überprüft werden
kann. Bedenke das alle diese Funktionen Teil der Vorverion von Kubuntu
sind und es teils zu (erheblichen) Problemen kommen kann. Bitte schreibt
für alle Probleme, die euch auffallen einen Bugreport ins
[Launchpad](https://launchpad.net/distros/ubuntu/+filebug), falls nicht
schon einer existiert.


### Kvkbd


[Kvkbd](http://www.kde-apps.org/content/show.php/Kvkbd?content=56019)
ist eine virtuelle Bildschirmtastatur für KDE, welche für Benutzer mit
eingeschränkten Bewegungsmöglichkeiten gedacht ist. Die aktuelle Version
0.4.7 beinhaltet einen neuen Knopf um das Kontextmenü zu öffnen, welches
Benutzern hilft, die nicht die Möglichkeit haben einen Rechts-Klick
auszuführen. Auch hat der Nutzer nun die Möglichkeit die Position der
Tastatur auf dem Bildschirm zu speichern und wieder herzustellen.


### KDE Bluetooth


Das [KDE-Bluetooth-Framework](http://bluetooth.kmobiletools.org/)
beinhaltet eine Vielzahl nützlicher Werkzeuge, welche auf dem Linux
Bluetooth stack BlueZ basieren. Das Ziel von KDE Bluetooth ist einen
einfachen Zugriff auf die häufigsten Bluetooth Profile zu gewährleisten
und den Datenaustausch mit Bluetoothfähigen Handys und PDAs so einfach
wie möglich zu gestalten.


### Compiz & KDE


Basierend auf dem KDE 3.5.4 [minipager
applet](http://www.kde-apps.org/content/show.php?content=46021) für
Kicker, wird es nun eine modifizierte Version geben, die besser mit
Compiz zusammenarbeitet als die derzeitige Version des
Arbeitsflächenumschalters.  

Das neue Applet ist darauf ausgelegt, mit Window-Managern
zusammenzuarbeiten, die das Konzept des "großen Desktops" verwenden,
anstatt auf das Konzept der multiplen-virtuellen Desktops aufzubauen,
wie dies KWin tut.  

Auch wird es eine neue
[Taskbar](http://www.kde-apps.org/content/show.php?content=49484) geben,
die besser mit Compiz zusammenarbeitet als die derzeitige.


### KNetworkManager


Der [KNetworkManager](http://en.opensuse.org/Projects/KNetworkManager)
ist die KDE Benutzeroberfläche für den NetworkManager. Er bietet eine
anspruchsvolle und intuitive Benutzeroberfläche, welche es Benutzern
ermöglicht leicht ihre Netzwerkumgebung zu wechseln. Die neuesten
Updates für den KNetworkManager in Kubuntu 8.04 beinhaltet Unterstützung
für PPP und KPPP und es wurde die Unterstüzung für PPTP aktiviert.


### Kopete OTR Plugin


INFO: <http://kopete-otr.follefuder.org/>  

Das OTR Plugin für Kopete wurde aktiviert und bietet nun die Möglichkeit
der "Off The Record" Verschlüsselung für den Instant Messenger. Mit dem
Kopete OTR Plugin, können nun verschlüsselte Chatsitzungen mit anderen
Benutzer gestartet werden, deren Instant Messenger auch über eine die
OTR Funktionalität verfügt.


### KTorrent


[Ktorrent](http://ktorrent.org/), die BitTorrent-Anwendung von KDE, ist
in Hardy Heron in der aktuellen Version 2.2.4 enthalten. Diese bringt
eine verbesserte Benutzeroberfläche, sowie die Möglichkeit so viele
Ansichten in Tabs zu öffnen, wie benötigt werden, dies funktioniert auch
für Suchanfragen über das verbesserte Such-Plugin. Dazu gibt es nun die
Möglichkeit vollständige Downloads in ein anderes Verzeichnis zu
verschieben, und noch viele andere Verbesserungen....


### Automatische Codec Installation in Kaffeine


Codecs (momentan libxine1-ffmpeg) werden automatisch installiert, wenn
man das erste mal eine Datei mit Kaffeine öffnet. Zukünftige
Implementierungen werden die automatische Installation von DVD-Codecs
erlauben.


### NTFS Support


Endlich ist auch in Kubuntu der NTFS Lese- und Schreibzugriff von Anfang
an aktiviert.


### LUKS Support


KIO Media unterstützt nun die Entschlüsselung und das Einbinden von
verschlüsselten [LUKS Partitionen](http://luks.endorphin.org/).


Feedback
--------


Das Kubuntu-Team würde sich freuen Rückmeldungen über Kubuntu 8.04 Hardy
Heron Alpha 1 zu erhalten. Ist es genau, dass was ihr euch wünscht?
einfach nur OK oder findet ihr es nicht gelungen? Jede - höfliche
formulierte - Rückmeldung (auf Englisch) ist erwünscht. Ihr könnt dem
Kubuntu Team eure Meinung über folgende Seite zukommen lassen: [Kubuntu
Feedback](https://wiki.kubuntu.org/HardyHeron/Alpha1/Kubuntu/Feedback).



