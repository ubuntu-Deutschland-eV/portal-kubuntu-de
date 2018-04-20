Title: Kubuntu Intrepid Alpha 4 erschienen
Date: 2008-08-17 20:45
Author: Monika Eggers
Tags: Kubuntu
Slug: kubuntu-intrepid-alpha-4-erschienen

Mit der am vergangenen Freitag erschienen vierten Alpha-Version von
Kubuntu 8.10 "Intrepid Ibex" wird für die Nutzer die aktuelle Version
des X-Servers 1.5 und ein Kernel basierend auf Version 2.6.26.2
(Ubuntu-Version 2.6.26-5.15) verfügbar gemacht.


Kubuntu 8.10 ermöglicht nun die Einrichtung verschlüsselter privater
Verzeichnisse. Dadurch wird der Schutz ihrer privaten Daten besonders
auf mobilen Geräten wie Notebooks erheblich verbessert.


<!--break--><!--break-->

Sind die Pakete "ecryptfs-utils" und "auth-client-config" installiert,
so wird die Verschlüsselung folgendermaßen aktiviert:


    sudo auth-client-config -p ecryptfs_standard -t pam-auth,pam-session,pam-passwordecryptfs-setup-private

Nennenswert ist auch die Einführung eines Gast-Accounts, der ohne
Passwort auskommt. Eine dauerhafte Speicherung von Daten auf dem System
ist für diesen Account nicht vorgesehen und er verfügt auch nicht über
ein eigenes /home-Verzeichnis.


Neu ist auch der NetworkManager in der Version 0.7. Diese Version und
das entsprechende KDE-Frontend sollen jedoch Berichten zufolge noch
Probleme bereiten.


Warnung: Kubuntu 8.10 Intrepid Ibex Alpha 4 ist eine reine Test- und
Entwicklerversion. Sie ist AUF KEINEN FALL für den produktiven Einsatz
gedacht, da Stabilität und Datensicherheit nicht garantiert werden
können.


Wer sich am Testen von Kubuntu 8.10 Intrepid Ibex beteiligen möchte,
kann sich die
[Installations-CDs](http://cdimage.ubuntu.com/kubuntu/releases/intrepid/alpha-4/ "http://cdimage.ubuntu.com/kubuntu/releases/intrepid/alpha-4/")
vom Hauptserver oder einem der zahlreichen
[Mirrorserver](http://wiki.ubuntu.com/Mirrors "http://wiki.ubuntu.com/Mirrors")
herunterladen.


Ein Upgrade von Hardy Heron sollte mit einer entsprechenden Anpassung
der Paketquellen möglich sein. Fehlerberichte können auch
[hier](https://bugs.launchpad.net/ubuntu "https://bugs.launchpad.net/ubuntu")
an den Bugtracker von Ubuntu gesendet werden.


### Siehe auch


-   [Offizielle Ankündigung
    (englisch)](https://lists.ubuntu.com/archives/ubuntu-devel-announce/2008-August/000470.html "https://lists.ubuntu.com/archives/ubuntu-devel-announce/2008-August/000470.html")
    
    



