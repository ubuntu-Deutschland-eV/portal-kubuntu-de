Title: "Project Neon": Amarok 2 Pakete für Kubuntu
Date: 2008-05-04 19:20
Author: Monika Eggers
Tags: Amarok
Slug: project-neon-amarok-2-pakete-fur-kubuntu

![Logo des Amarok Projekts
"Neon"](http://www.kubuntu-de.org/files/ProjectNeonLogo.png)Mit dem neu gegründeten [Projekt
"Neon"](http://amarok.kde.org/wiki/User:Apachelogger/Project_Neon),
haben sich die Entwickler des beliebten Musikplayers
[Amarok](http://amarok.kde.org) das Ziel gesetzt, tagesaktuelle Pakete
von Amarok 2 für verschiedene Distributionen bereitzustellen. "Project
Neon" soll die jeweils aktuellste Version von Amarok für normale Nutzer
verfügbar machen, damit sich noch mehr Leute an der Entwicklung
beteiligen oder Fehler testen und korrigieren können.


Momentan stehen nur Pakete für Kubuntu Hardy Heron zur Verfügung, aber
es ist geplant auch andere Distributionen zu bedienen. Um dies zu
erreichen, rufen die Entwickler die Paketbetreuer anderer Distributionen
auf sich an diesem Projekt zu beteiligen. Wer Pakete bauen kann, sollte
sich im IRC auf irc.freenode.net im Raum \#rokymotion bei apachelogger
melden.


<!--break--><!--break-->

Beim Berichten von Fehlern bittet das Team von Amarok darum zu beachten,
dass nur Fehlerberichte akzeptiert werden, die leicht reproduzierbar und
nicht offensichtlich sind. Am besten sind natürlich Fehlerberichte mit
angehängtem Patch.


Die Installation unter Kubuntu Hardy Heron funktioniert folgendermaßen:


-   *deb <http://ppa.launchpad.net/project-neon/ubuntu> hardy main* in
    die Datei */etc/apt/sources.list* einfügen.
-   Paketliste aktualisieren und mit dem grafischen Paketmanager Adept
    oder auf der Konsole das Paket **amarok-nightly** installieren.
-   Amarok kann nun aus dem KMenü oder in der Konsole durch Eingabe von
    "amarok-nightly" gestartet werden


Da die Konfiguration im Verzeichnis \~/.amarok-nightly gespeichert wird,
ist es möglich die stabile und die Entwicklerversion von Amarok parallel
zu installieren.


**Warnung: Das Paket amarok-nightly enthält in der Entwicklung
befindlichen Code, der teilweise vollkommen ungetest ist. Auch wenn sich
die Amarok-Entwickler Mühe geben nichts anzustellen, kann es durchaus
sein, dass dieses Paket das System zerstört. Eine Installation auf
Produktivsystemen ist nicht empfehlenswert!**



