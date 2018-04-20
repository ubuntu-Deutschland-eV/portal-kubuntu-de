Title: Amarok 2.0 mit Kubuntu-Paketen erschienen
Date: 2008-12-10 22:12
Author: Monika Eggers
Tags: Amarok
Slug: amarok-20-mit-kubuntu-paketen-erschienen

Nach langen 2 Jahren Entwicklungszeit haben die Entwickler die stabile
Version von Amarok 2.0 veröffentlicht. Der für KDE 4 neu geschriebene
Mediaplayer und Musikmanager wurde komplett überarbeitet und kommt mit
vielen neuen Fähigkeiten und vor allem einer umgebauten
Benutzeroberfläche daher.  

Das Redesign von Amarok war nötig, da mit dem alten Framework die
Weiterentwicklung immer schwieriger und schwerfälliger wurde. Zudem
konnte auf diese Weise direkt für KDE 4 entwickelt werden, was einer
Portierung der Version 1.4 vorgezogen wurde.


Neben der zuvor erwähnten neu gestalteten Benutzeroberfläche sind u.a.
weitere Fähigkeiten das Framework für Internetdienste, eine überholte
Skript-API und Plugin-Unterstützung. Erwähnenswert ist natürlich auch
der Gebrauch von KDE 4 eigenen Technologien wie Solid, Phonon und
Plasma.


<!--break--><!--break-->

Durch die jetzige Aufteilung der Oberfläche können noch mehr
Informationen bezüglich des aktuellen Künstlers wie zum Beispiel
Liedtexte oder Albumcover im Kontextbereich angezeigt werden. Letzteres
wird durch Nutzung von Plasmoids in diesem Bereich, der die Mitte der
Oberfläche bildet möglich.  

Durch die stärkere Bindung an Internetdienste, können Angebote wie
Last.fm, Shoutcast oder Magnatune direkt in einer zentralen Stelle aus
Amarok 2 heraus genutzt werden.  

Außerdem gibt es gewichtete Wiedergabelisten, die ähnlich wie die
dynamischen Listen in Amarok 1, automatisch mit den Liedern gefüllt
werden, die den festgelegten Kriterien entsprechen. Alle Neuerungen
können der [offiziellen
Ankündigung](http://amarok.kde.org/en/releases/2.0 "http://amarok.kde.org/en/releases/2.0") entnommen werden.


Ein besonderes Augenmerk legen die Entwickler auf die Feststellung, dass
diese Veröffentlichung von Amarok 2.0 ein Anfang und kein Endpunkt ist.
Der Mediaplayer wird wie auch KDE 4 noch intensiv weiterentwickelt. Dies
sei die erste stabile Version nach dem Redesign. Amarok ist noch nicht
wieder komplett und so werden erst in den kommenden Veröffentlichungen
alte Fähigkeiten ─ wie zum Beispiel der Filter für die Wiedergabelisten
─ zurückkehren.  

Durch die neuen Frameworks ist es nun möglich mittels GetNewHotStuff
(wie man es auch von Hintergrundbildern, Farbschemen, usw. in KDE
gewohnnt ist) neue Funktionen zu integrieren und es gibt schon eine
Menge Skripte, welche Amarok bereichern. Die Anbindung von tragbaren
Medienplayern wird erst nach Arbeiten an den unterliegenden
KDE-Schichten, somit in einer späteren Freigabe, möglich sein.


  


[]{#Installation}  

### [ Installation]


**Hinweis:** Wer bereits eine Vorversion von Amarok 2 installiert hat,
erhält die neue Version automatisch mit den Systemaktualisierungen,
sofern das entsprechende PPA freigeschaltet ist.


1.  Man muss die Zeile **deb
    <http://ppa.launchpad.net/kubuntu-members-kde4/ubuntu> intrepid
    main** der /etc/apt/sources.list hinzufügen und danach folgende
    Kommandos ausführen:
    
    
2.  
        sudo apt-get update

3.  
        sudo apt-get install amarok-kde4


**Warnung:** Die Installation von amarok-kde4 entfernt die alte KDE 3
Version (1.4.10)



