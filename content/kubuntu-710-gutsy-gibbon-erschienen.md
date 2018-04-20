Title: Kubuntu 7.10 Gutsy Gibbon erschienen
Date: 2007-10-18 06:12
Author: Monika Eggers
Slug: kubuntu-710-gutsy-gibbon-erschienen

Etwa ein halbes Jahr ist es her, dass Mark Shuttleworth das nächste
Release von Ubuntu 7.10 unter dem Codenamen "Gutsy Gibbon" (übers.
Mutiger Gibbon) angekündigt hatte.


Nun ist es endlich soweit: Kubuntu 7.10 (die Ubuntu Variante mit der KDE
Arbeitsumgebung) bringt viele Neuerungen mit sich. Ganz zu Beginn eine
kleine Enttäuschung: KDE 4.0 wird nicht als Standarddesktop enthalten
sein, die Entwickler versprechen jedoch Pakete für Kubuntu zu erstellen
und zu pflegen sobald ein stabiles Release erscheint. Was wahrscheinlich
in den nächsten Monaten geschehen wird. Eine Veränderung die manche
freudig begrüßen andere bedauern werden: Dolphin wird Konqueror als
neuen Dateimanager ablösen. Diese Entscheidung wurde vor allem aus
Gründen der Benutzerfreundlichkeit getroffen, auf die die Entwickler von
Dolphin ganz besonders viel Wert legen.


Mit Strigi gibt es endlich auch eine KDE eigenen Desktop-Suche. Mit der
Installation nur eines Pakets (kubuntu-restricted-extras) können
wichtige Audio- und Video-Codecs, die wegen ihrer restriktiven Lizenz
nicht im Standardumfang enthalten sind, leicht nachinstalliert werden.
Das gleiche gilt für Treiber mit proprietärer Lizenz, die mittels des
neuen Restricted-Managers mit einem Mausklick nachgerüstet werden
können, um so beispielsweise den vollen Funktionsumfang aktueller
Grafikkarten zu erhalten.


**Update:** Download-Server aktualisiert


<!--break--><!--break-->

Kubuntu 7.10 Gutsy Gibbon
-------------------------


### Kernel


Der Kernel ist die Basis des Betriebssystems, u.a. ist er die
Schnittstelle zur Hardware. Gutsy setzt auf Version 2.6.22 und ist damit
so aktuell wie möglich, da der Kernel 2.6.23 gerade erst freigegeben
wurde.


Ubuntu stellt nicht nur eine Kernelvariante zur Verfügung, sondern
bietet für die unterschiedlichen Anforderungen auch unterschiedliche
Betriebssystemkerne. Für den Normaluser reicht hier allerdings der
Standardkernel "generic" aus, der sich der Hardware entsprechend
anpasst.


Mit diesem Kernel unterstützt Kubuntu auch neueste Hardware meist "out
of the box" und es ist in der Regel daher nicht notwendig die
Standardinstallation stark anzupassen. Sollte man sich unsicher sein, ob
die eingesetzte Hardware wirklich linuxtauglich ist, so kann man sich
mit der "Live CD" ein komplettes Kubuntu ohne Installation nur von CD
starten und einen ersten Test ohne Risiko vornehmen.


### KDE


Das [K Desktop Environment](http://www.kde.org) ist die Desktopumgebung,
die Kubuntu das K in seinem Namen beschert. KDE ist eine seit über 10
Jahren bestehende grafische Benutzeroberfläche, die sich durch
Vielseitigkeit und Anpassungsfähigkeit auszeichnet. KDE bringt nicht nur
von Haus aus schon viele Funktionen mit sich, die man anderswo mühsam
nachinstallieren müsste, es ist dazu auch noch vollständig im Design
anpassbar, so dass jeder Nutzer sich die Umgebung schaffen kann, die er
braucht und genießen kann.


Mit KDE in der Version 3.5.8 werden sehr viele, wenn auch nicht
kritische, aber doch nervige Fehler behoben. Änderungen im
Funktionsumfang gibt es zur vorherigen Versionen kaum, diese sollen in
erheblichem Maße mit dem sehnlichst erwarteten KDE 4.0 eingepflegt
werden.


### Edubuntu KDE


Edubuntu ist eine Ubuntu-Variante, deren Ausstattung sich speziell an
die Bedürfnisse von Schulen und anderen Bildungseinrichtungen richtet.
Mit Kubuntu 7.10 ist es nun möglich durch die Installation des Pakets
edubuntu-desktop-kde den KDE-Desktop Arbeitsoberfläche für Edubuntu zu
verwenden. Zusätzlich werden die Programme des "KDE Education" Projekts
installiert. Das sind z.B. ein Vokabeltrainer, ein
Geografie-Lern-Programm und sehr viele mehr. Eine vollständige Übersicht
gibt es auf der Seite des [KDE Education Project
(Englisch)](http://edu.kde.org/).


Neuigkeiten und Anwendungen im Einzelnen
----------------------------------------


Unter Linux sucht man sich im Normalfall nicht einfach eine Datei im
Internet und installiert diese dann, denn es steht dem Nutzer eine
mächtige [Paketverwaltung](http://wiki.ubuntuusers.de/Paketverwaltung)
zur Verfügung. Mit dem Programm adept hat man in Kubuntu eine einfache
grafische Möglichkeit auf diese Paketverwaltung zuzugreifen. Hier sind
tausende von Programmen verfügbar, die je nach Bedarf einfach
installiert werden können. Sollte man dennoch einmal nicht die
gewünschte Software finden können, hat man aber ein für Kubuntu
optimiertes .deb Paket zur Verfügung, so kann man neu in Gutsy mit gdebi
dieses einfach mit einem Mausklick installieren, eventuelle
Abhängigkeiten werden automatisch aufgelöst.


### Restricted Manager


[![Restricted Drivers
Manager](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smkrm.png)](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=krm.png "Größere Darstellung")


Ganz neu ist der "Restricted-Manager". Dieses kleine nützliche Programm
erkennt automatisch Hardware, wie z.B. 3D-Grafikkarten, für die
proprietäre Treiber zur Verfügung stehen, und fragt ob diese installiert
werden sollen. So wird es noch einfacher den vollen Funktionsumfang
aktueller Hardware auch unter Kubuntu auszureizen.


### Dolphin


[![Dolphin](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smdolphin.png)](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=dolphin.png "Größere Darstellung")


KDE hat jahrelang auf Konqueror als Dateimanager und Browser in einem
gesetzt, allerdings kürzlich entschieden in der vierten Generation auf
einen schlankeren Manager namens Dolphin zu setzen. Dolphin ist kein
neues Programm und auch als Qt3 Version verfügbar. Gutsy geht mit der
Zeit und implementiert Dolphin als Standarddateimanager schon in einem
KDE 3.


### Konqueror


Konqueror ist der KDE eigene Browser, der auch als Dateimanager
verwendet werden kann. Der "Konqui" bietet alles was ein moderner
Browser haben muss, Tabbed Browsing, Werbefilter, Download des
Flashplugins und eine ausgereifte Lesezeichenverwaltung. Ein großer
Vorteil des Konquerors ist die Erweiterbarkeit durch kio-plugins.


In Gutsy Gibbon funktioniert nun das Flashplugin von Adobe wieder
einwandfrei. Alternativ zu dem proprietären Flashplugin ist nun eine
vollkommen freie Implementation von Flash hinzugekommen. Das
Gnash-Plugin für den Konqueror lässt sich einfach über das Paket klash
aus den Paketquellen installieren.


### Strigi


[![Strigi](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smstrigi1.png)](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=strigi1.png "Größere Darstellung")


Mit Strigi hält einen neue Engine für die Desktopsuche in Ubuntu Einzug.
Sie zeichnet sich vor allem durch ihre hervorragende Geschwindigkeit
aus. Unter KDE kann die Suche über zwei Wege erreicht werden. Entweder
über das Mini-Applet im Systembereich der Kontrolleiste oder über ein
KIO-Slave des Konquerors, das über das KMenü gestartet werden kann.


### GDebi


[![GDebi
KDE](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smgdebi.png)](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=gdebi.png "Größere Darstellung")


Bisher war es unter Kubuntu nicht möglich, einfach heruntergeladene .deb
Pakete zu installieren. Zwar konnte man es mittels des Kontextmenüs im
Konqueror installieren, dies scheiterte jedoch oft, da das dahinter
liegende Skript keine Abhängigkeiten auflösen konnte. Mit GDebi kommt
jetzt ein Tool mit ansprechender grafischer Obefläche, dass es
ermöglicht .deb Pakete mit einem Klick zu installieren. Alle
Abhängigkeiten werden automatisch aufgelöst und die entsprechenden
Pakete installiert.


### PIM


Eines der am meisten verwendeten Programmtypen sind diejenigen, die
persönliche Daten wie E-Mails, Termine, Notizen und Adressen verwalten.
Auf Englisch werden diese kurz PIM (Personal Information Manager)
genannt.


In Kubuntu 7.10 Gutsy Gibbon wurde der aktuelle Unternehmenszweig der
KDE PIM Anwendungen eingepflegt. Dieser ist eine solide und stabilere
Freigabe der bekannten KDE PIM Anwendungen, von denen Kontact das
Hauptfrontend für die gesamte Suite in sich vereinigt. Eine Verwendung
der Programme als Einzelanwendungen ist aber genauso gut möglich. Im
einzelnen sind dies die Programme KMail, KAddressBook, KAlarm, KNotes
und zahlreiche weitere.


Zur KDE PIM Suite wurde von den Kubuntu Entwicklern die
Standardinstallation zur Verwendung von GPG und S/MIME Ver- und
Entschlüsselung, Signierung und Verifikation hinzugefügt. Alle GPG
Komponenten werden bei der Installation richtig eingestellt und stehen
zur sofortigen Anwendung bereit. Bei einem Upgrade von der Version 7.04
Feisty Fawn sind jedoch einige Einstellungsänderungen nötig. Weitere
Informationen über die GPG Implementation können auf den Ubuntu
[Hilfeseiten
(Englisch)](https://help.ubuntu.com/community/KMailGPGAgent#head-c6757d6675d3932eaeffb136479725842a81d9b6)
nachgelesen werden.


#### Kontact


[Kontact](http://kontact.kde.org/) integriert sämtliche Anwendungen der
Suite unter einer Oberfläche. Addressverwaltung, Email-Client,
Terminkalender, RSS-Newsreader, ein einfaches Notizprogramm werden -
ergänzt durch eine Übersichtsdarstellung - zu einer Einheit
zusammengefasst, die den Zugriff und die Verwaltung von persönlichen
Informationen erleichtert.


#### KMail


KMail ist der E-Mail Client der KDE PIM-Suite, er kann sich vollständig
in Kontact integrieren. In der aktuellen Version 1.9.6 sind nicht nur
zahlreiche Fehler vorheriger Versionen behoben sondern auch einige neue
Funktionen enthalten, so ist z.B. endlich das Gruppieren der Ordner in
der Baumansicht per Drag&Drop möglich.


Auf den ersten Blick eher einfach gehalten ist KMail ein mächtiges
Werkzeug zur Verwaltung von E-Mails, dazu gehört natürlich IMAP, POP3
und SMTP Unterstützung, aber auch die Möglichkeit Mailinglisten zu
verwalten und deren Nachrichten gruppiert anzuzeigen, sowie
Verschlüsselte oder Signierte E-Mails zu empfangen und zu senden und
natürich der Import aus vielen beliebten E-Mail Programmen
unterschiedlichster Betriebssysteme, z.B. Outlook-Express, The Bat!,
Opera, Evolution, MaxOS X und einigen mehr.


Einige weitere Funktionen sind:


-   Sicheres Einloggen per SSL, TLS oder DIGEST-MD5
-   Anti-Spam-Filter
-   Unterstützung von Schriften aller Sprachen
-   Umfangreiche Filter und Suchfunktionen
-   Rechtschreibprüfung
-   Sehr gute Integration mit anderen KDE-Programmen


 


#### Korganizer


KOrganizer ist der Terminkalender von KDE. Er ermöglicht es nicht nur
die persönlichen Termine zu speichern und in diversen Darstellungen zu
visualisieren, sondern kann auf diverse Exchange-Server zugreifen und
ist so auch für die Terminkoordination in Unternehmen geeignet. Eine
Journalkomponente und Erinnerungsfunktion runden das Programm ab.


#### BasKet


Basket ist ein separat zur restlichen KDE-PIM Suite entwickeltes
Programm zur übersichtlichen Verwaltung von Notizen aller Art und Form.
Verknüpfungen zu Programmen, Sprachnotizen oder formatierte Texte können
einfach in Spalten oder frei angeordnet gruppiert, in Hierarchien
geordnet, farbig gestaltet und mit unterschiedlichen Tags versehen
werden. Zur besseren Übersicht werden, die Notizen in "Körben" (engl.
Baskets) gesammelt, die in einer Baumansicht zu Hierarchien geordnet
werden können. Leider bettet sich das Programm nicht mehr wie bisher in
Kontact ein, da die verwendete "Enterprise"-Version der KDE-PIM Suite
dies nicht vorsieht.


Das Programm ist in der Version 1.0.2 in Gutsy enthalten und ist im
derzeitigen Funktionsumfang auch als Einzelanwendung sehr nützlich und
hilft, das tägliche Zettelchaos übersichtlicher zu gestalten und auch
umfangreichere Projekte sinnvoll zu ordnen.


**Achtung:** basket gehört nicht zur Standardinstallation.


### Kontakt


#### Kopete


[Kopete](http://kopete.kde.org/) ist ein freier Instant Messenger, der
z. B. AIM, ICQ, IRC, Jbber, MSN, Yahoo und viele weitere unterstützt.
Das Programm ist direkt in KDE integriert und bietet daher z.B. der
Adressverwaltung kaddressbook Informationen, die den einzelnen Kontakten
beigefügt werden. Dem Nutzer präsentieren sich somit auf einen Blick
sämtliche Möglichkeiten, mit Freunden, Kollegen und anderen in Kontakt
zu treten.


#### Konversation


Das Programm [Konversation](http://konversation.kde.org/) ist ein
grafischer IRC-Client, der Benutzeroberfläche KDE. Es ist möglich
mehrere Verbindungen zu verschiednen Servern aufzubauen. Ein Highlight
ist eine OnScreen-Anzeige bei bestimmten Verhalten z. B. Highlights,
Querys etc. DCC-Verbindungen und Lesezeichen für Server und Channels
sind ebenso standardmäßig enthalten wie eine Nickvervollständigung mit
&lt;Tab&gt;. Selbstverständlich beinhaltet Gutsy die neuste Version, mit
der man u.a. unseren Supportkanal \#kubuntu-de aus Server
irc.freenode.net erreichen kann. Hier sind häufig zahlreiche Mitglieder
der Community versammelt, die einen direkten Support auch in
vermeintlich "einfachen" Fragen geben. Nebenher kann man in
\#kubuntu-de.org an der Entwicklung des Projektes kubuntu-de.org direkt
teilnehmen.


### Office


#### OpenOffice.org


[![OpenOffice.org](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smooo1.png)]{}


Als Standard Office-Paket wird auch in Kubuntu das beliebte
[OpenOffice.org](http://de.openoffice.org/) installiert. In der
brandneuen Version 2.3.0 bietet es zahlreiche Detailverbesserungen aber
euch einige größere Änderungen. So wurde das Tool zur Erstellung von
Diagrammen (Chart) vollständig überarbeitet, die Verwendung logischer
gestaltet und einige neue Funktionen eingebaut und das
Textverarbeitungsprogramm Writer kann nun direkt in das MediaWiki-Format
exportieren.


OpenOffice.org enthält unter anderem:


-   Writer (Textverarbeitung)
-   Calc (Tabellenkalkulation)
-   Impress (Präsentationen)
-   Draw (Vektorgrafik)
-   Base (Datenbank-Erstellung und -Verwaltung)


 


#### KOffice


Das eigentliche KDE-Officepaket KOffice ist zwar nicht standardmäßig
installiert, ist aber inzwischen eine echte Alternative zu
OpenOffice.org geworden. Besonders bemerkenswert ist wie viele
Komponenten hier zu einem umfassenden Officepaket geschnürt wurden. So
gibt es auch Programme, die Bereiche abdecken, die in anderen Paketen
fehlen. Z.B. das Grafikprogramm Krita, welches pixelbasierte
Bildmanipulation erlaubt, KPlato für das Projektmanagement oder Kivio,
ein Programm für die Erstellung von Flussdiagrammen. Die aktuelle in
Gutsy Gibbon enthaltene Version 1.6.3 ist die letzte vor dem Release der
Version 2.0 und enthält daher hauptsächlich Fehlerbehebungen. Sie
enthält unter anderen die folgenden Programme:


-   KWord (Textverarbeitung)
-   KSpread (Tabellenkalkulation)
-   KPresenter (Präsentationen)
-   Kivio (Erstellung von Flussdiagrammen)
-   Kexi (Datenbank-Erstellung und Bearbeitung)
-   KPlato (Projektmanagement)
-   Krita (Pixelbasierte Grafikmanipulation)
-   Karbon14 (Vektorgrafik)


 


KOffice muss bei bedarf aus den Paketquellen nachinstalliert werden.
Eine vollständige Liste aller enthaltenen Programme und Funktionen
finden sie auf der Projekthomepage von [KOffice
(Englisch)](http://www.koffice.org/)


### Multimedia


#### Kubunut Restricted Extras


Die erste Frage jedes Kubuntu Neulings lautet: Warum kann Kubuntu keine
MP3\`s abspielen? Da das beliebte Audio-Format leider einer
geschlossenen Lizenz unterliegt, dürfen die entsprechenden Codecs
standardmäßig nicht installiert werden. Damit die nachträgliche
Installation so leicht wie möglich geht, gibt es nun das Paket
kubuntu-restricted-extras. Wer dieses installiert, kann sofort MP3\`s,
MPEG und AVI Dateien abspielen und damit die vollen
Multimediafähigkeiten seines Computers nutzen.


#### Amarok


[![Amarok](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=smamarok.png)](https://wiki.ubuntu.com/GutsyGibbon/Beta/Kubuntu?action=AttachFile&do=get&target=amarok.png "Größere Darstellung")


[Amarok](http://amarok.kde.org/de) ist ein Audioplayer für KDE der -
entsprechende Codecs vorausgesetzt - die Dateiformate OGG, MP3, MP4,
AAC, FLAC, RealMedia und WMA abspielen kann. Neben einer integrierten
Suchfunktion, ist es auch problemlos möglich Webradio zu hören. Mit
einem Punktesystem kann man einzelne Stücke bewerten und dadurch werden
Lieblingssongs öfters gespielt. Mit einer last.fm Anmeldung ist es sogar
möglich, weite Stücke angezeigt zu bekommen, die zu der Playlist passen.


Amarok kann nur als der beste Audioplayer bezeichnet werden, der
momentan verfügbar ist, ob man seinen iPod befüllen, Cover downloaden,
die Sammlung samt ID3 Tags verwalten oder einfach nur Musik hören will,
Amarok ist ein Allrounder.


#### k3b


[K3b](http://k3b.plainblack.com/) ist das Brennprogramm für KDE. Es ist
möglich alle Varianten von CD's und DVD's sowohl zu brennen als auch zu
löschen. k3b zählt sicherlich zu den besten Programmen seiner Art und es
hat nicht umsonst erst kürzlich die Version 1.0 erreicht, womit deutlich
gemacht werden sollte, dass die ursprünglichen Ziele einer ersten
Version erreicht wurden.


#### kaffeine


Kaffeine ist ein Videoplayer für Linux-Systeme mit KDE als
Benutzeroberfläche. Es werden alle gängigen Video- und Audioformate
unterstützt, zu wahrer Höchstform läuft die Applikation aber erst im
Zusammenspiel mit einem DVB-T Stick oder ähnlichem auf. Kubuntu ist "out
of the box" dazu in der Lage in jeder Hinsicht als Entertainment Center
zu dienen.


Wie bekommt man Kubuntu 7.10 ?
------------------------------


### Download


Sie können sich die LiveCD von Kubuntu und die Alternative
Installations-CD von den folgenden Servern herunterladen. Die LiveCD
dient dazu das System ausprobieren zu können ohne Änderungen am Computer
vorzunehmen. Sie bietet außerdem die Möglichkeit Kubuntu 7.10 über eine
ansprechende grafische Benutzeroberfläche zu installieren, diese ist
über ein Symbol auf dem Desktop des gestarteten Systems zugänglich.


Die Alternative Installations-CD bietet unterschiedliche Möglichkeiten
Kubuntu 7.10 auf ihrem PC zu installieren.


iso-Downloads:


-   [Austria
    Ubuntu.gds.tuwien.ac.at](http://ubuntu.gds.tuwien.ac.at/cdimage/releases/kubuntu/gutsy/){.country_AT
    .continent_EU}
-   [De.archive.ubuntu.com-release](http://de.archive.ubuntu.com/ubuntu-releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Esslingen University of Applied
    Sciences](http://ftp-stud.hs-esslingen.de/pub/Mirrors/releases.ubuntu.com/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [intergenia
    AG](http://ubuntu.intergenia.de/releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Freie Universität
    Berlin](ftp://ftp.fu-berlin.de/linux/ubuntu/releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [RRZN, Leibniz Universität
    Hannover](ftp://ftp.rrzn.uni-hannover.de/pub/mirror/linux/ubuntu-releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Secaron](ftp://mirror.secaron.lu/ubuntu/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [University of Applied Sciences
    Wolfenbuettel](http://releases.ubuntu.uasw.edu/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Ftp-stud.fht-esslingen.de](http://ftp-stud.fht-esslingen.de/Mirrors/releases.ubuntu.com/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Ftp.tu-chemnitz.de](http://ftp.tu-chemnitz.de/pub/linux/ubuntu-releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Releases.ubuntu.mirror.at.stealer.net](http://releases.ubuntu.mirror.at.stealer.net/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Snert.mi.hs-heilbronn.de](http://snert.mi.hs-heilbronn.de/pub/ubuntu/releases/kubuntu/gutsy/){.country_DE
    .continent_EU}
-   [Alle Server](http://www.kubuntu.org/download.php)


 


### Upgrade


Ein Upgrade auf Kubuntu 7.10 Gutsy Gibbon ist **nur** von der vorherigen
Version Kubuntu 7.04 Feisty Fawn möglich. Über die automatischen Updates
wird bekanntgegeben, dass eine neue Version des Betriebsystems zur
Verfügung steht. Sollte die automatische Benachrichtigung nicht
funktionieren kann die Upgrade-Software auch über den Befehl
[update-manager -d] manuell initialisiert
werden. Weitere Anweisungen hierzu gibt es [hier
(Englisch)](https://help.ubuntu.com/community/GutsyUpgrades#head-3cb12417f0af7f24d4a34f2ae4040bf791c42f52).


### Ship It


Für alle ohne schnelle Internetverbindung wird ein spezieller Service
geboten. Nach kurzer Anmeldung können über
[ShipIt](https://shipit.kubuntu.org/) Kubuntu-CDs bestellt werden. Dies
kann allerdings bis zu 10 Wochen dauern. Für Eilige lohnt es sich daher,
in gut sortierten Buchläden und Elektronikgeschäften nach Kubuntu zu
fragen.



