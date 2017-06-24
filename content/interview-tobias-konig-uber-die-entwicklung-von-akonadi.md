Title: Interview: Tobias König über die Entwicklung von Akonadi
Date: 2008-03-12 18:16
Author: Monika Eggers
Tags: Sonstiges
Slug: interview-tobias-konig-uber-die-entwicklung-von-akonadi

[![Tobias König auf den Chemnitzer-Linux-Tagen 2008 mit Konqui auf der
Schulter](http://wiki.kubuntu-de.org/images/Tobias_Koenig_CLT-2008-klein.jpg){width="220"
height="165"}](http://wiki.kubuntu-de.org/images/Tobias_Koenig_CLT-2008.jpg)

</p>
<h2>
<span class="mw-headline">kubuntu-de.org im Gespräch mit Tobias König  

</p>
<p>
</span>

</h2>
</p>
*Translations are available in:
[English](http://www.kubuntu-de.org/english/interview-tobias-k-nig-about-development-akonadi),
[Italian](http://www.kde-it.org/news.php?extend.183) (thanks to
kde-it.org) and
[Polish](http://www.kde.org.pl/Wywiady/Tobias_K%C3%B6nig_o_rozwoju_Akonadi)
(thanks to kde.org.pl)*

</p>
[Tobias
König](http://tokoe-kde.blogspot.com/ "http://tokoe-kde.blogspot.com/") ist Informatikstudent und einer der Hauptentwickler von
[Akonadi](http://kdepim.kde.org/akonadi/ "http://kdepim.kde.org/akonadi/"), eine der innovativen Technologien, die es noch nicht in die
erste Version von [KDE
4](../../../../nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen "http://www.kubuntu-de.org/nachrichten/software/kde/kde-4-0-mit-kubuntu-paketen-erschienen") geschafft haben. Akonadi soll eine plattformunabhängige,
innovative Speicherlösung für persönliche Daten werden. Im Interview
erzählt Tobias König über seine Einbindung in die Entwicklung der
[KDE-Desktopbumgebung](http://www.kde.de/ "http://www.kde.de") und die Entwicklung und Funktionen von Akonadi.

</p>
**kubuntu-de.org:** Du bist ja sehr stark in die KDE-Entwicklung
eingebunden. Was machst du wenn du dich gerade nicht mit KDE
beschäftigst?

</p>
**Tobias König:** Wenn ich nicht gerade an KDE entwickle studiere ich
Allgemeine Informatik an der HTW Dresden. Nebenbei arbeite als freier
Mitarbeiter für die credativ GmbH

</p>
<!--break--><!--break-->

**kubuntu-de.org:** Wer ist die credativ Gmbh und was machen die?

</p>
**Tobias König:** Die credativ GmbH bietet Dienstleistungen rund um
Freie Software an. Ein Großteil der Mitarbeiter kommen auch aus dem Open
Source Umfeld, so zum Beispiel dem
[Debian-Projekt](http://www.debian.org/ "http://www.debian.org/") oder von
[Postgres](http://www.postgresql.org/ "http://www.postgresql.org/"). Aber auch ein paar KDE-ler arbeiten da :)

</p>
**kubuntu-de.org:** Könnte man also sagen, du hast dein Hobby zum Beruf
gemacht?

</p>
**Tobias König:** Ja, sozusagen :). Hauptsächlich bin ich aber noch
Student für die nächsten 2,5 Jahre.

</p>
**kubuntu-de.org:** Also rund um die Uhr mit Open Source Software
beschäftig ; ) Könntest du uns erzählen in welchen KDE-Projekten du
überall aktiv bist und welche Aufgaben du dort übernommen hast?

</p>
**Tobias König:** 'Zu Hause' bin ich im [KDE-PIM
Projekt](http://kdepim.kde.org/ "http://kdepim.kde.org"). Das ist ein Subprojekt von KDE, welches sich mit Personal
Information Management, also Kalendern, Adressbüchern und EMails,
befasst. Neben der Betreuung von KAddressBook helfe ich bei der
Entwicklung von Akonadi, dem neuen PIM-Storage. Während der Portierung
von KDE3 auf KDE4 habe ich aber auch hier und da in den Kernbibliotheken
von KDE mitgearbeitet.

</p>
**kubuntu-de.org:** Akonadi ist ein gutes Thema. Könntest du erläutern
was genau das ist? Gibt es nicht schon genug Groupware-Lösungen, die
versprechen mit allen möglichen Dateitypen zurecht zu kommen?

</p>
**Tobias König:** Das Wichtigste zuerst: Akonadi ist kein Groupware
Server!. Akonadi ist vielmehr ein Zwischenspeicher und eine
Abstraktionsschicht für PIM-Daten, ähnlich wie Phonon für Multimedia
oder Solid für Hardware. Akonadi abstrahiert den Zugriff und die
Verwaltung der Daten für das restliche System (z.B. dem Adressbuch oder
dem Kalender), indem es alle Daten über eine einheitliche Schnittstelle
anbietet. Das bringt einige Verbesserungen gegenüber KDE3: 1. Die
PIM-Daten müssen nur einmal im Speicher gehalten werden. 2. Man hat eine
zentrale Instanz, welche jede Veränderung der Daten mitbekommt und somit
andere Komponenten über diese Veränderungen informieren kann. 3. Das
ganze Akonadi-Framework verfolgt einen asynchronen Kommunikationsansatz
- ein Blockieren der Benutzerschnittstelle beim Laden oder Speichern von
Daten sollte nicht mehr vorkommen.

</p>
**kubuntu-de.org:** Das ist ja schon mal eine ganze Menge: So wie ich
das jetzt verstanden habe, wird der Zugriff auf die PIM-Daten einfacher
und trotz zusätlicher Software auch schneller. Wie wirkt sich das ganze
für den einfachen Otto-Normalnutzer aus? In KDE 3 gab es ja auch schon
zahlreiche Möglichkeiten, dass mehrere Programme auf eine Resource
zugreifen. Kopete und Konversation können ja beispielsweise mit Kontact
synchronisiert werden. Worin besteht also der Unterschied dazu?

</p>
**Tobias König:** Der Benutzer profitiert von Akonadi, da es keine
Inkonsistenzen zwischen den verschiedenen Darstellungen auf dem gesamten
Desktop geben wird. Ändert man einen Kontakt im Adressbuch, aktualisiert
sich auch gleich das Plasmoid, welches Geburtstage anzeigt. Der
Speicherverbrauch wird ebenfalls geringer, da nur noch der Akonadi
Server alle Daten im Speicher behalten muss.

</p>
Es ist nun auch möglich die PIM-Daten besser in andere KDE Programme zu
integrieren. Neben dem Namen des Eigentümers einer Datei, könnte z.B.
auch sein Bild im Dateiberechtigungsdialog angezeigt werden. Da die
Komponenten, welche die Daten zwischen dem Akonadi Server und
Datenquelle (z. B. Groupware-Server) transportieren, in separate
Prozesse ausgelagert sind, führt eine schlecht programmierte Komponente
auch nicht gleich zum Absturz des gesamten Systems. Die abgestürzte
Komponente wird einfach wieder neu gestartet und die Daten werden neu
geladen.

</p>
**kubuntu-de.org:** Das riecht ja förmlich nach Innovation! Werden mit
Akonadi auch neue oder verbesserte Ressourcentypen kommen?

</p>
**Tobias König:** Die Hauptaufgabe wird sein, die existierenden
Ressourcen auf Akonadi zu portieren. Durch die saubere, asynchrone
Schnittstelle in Akonadi dürfte sich die Zuverlässigkeit der Ressourcen
zudem verbessern. Im Moment wird zum Beispiel gerade an einer Ressource
für den Zugriff auf MS Exchange gearbeitet. Die Entwickler des
alternativen KDE EMail Programms Mailody entwicklen zudem eine
Ressource, welche auf Daten mittels IMAP zugreift. Damit ist der
KDE-Klient für den Kolab Groupware Server nicht mehr auf KMail
angewiesen, sondern kann direkt über Akonadi mit dem Kolab Server
kommunizieren.

</p>
**kubuntu-de.org:** Und das wird mit 4.1 umgesetzt sein?

</p>
**Tobias König:** KDE 4.1 wird Akonadi als Entwicklerplattform
enthalten. Das bedeutet, dass die APIs stabil sind und man den Dienst
benutzen kann. Es werden aber höchstwahrscheinlich noch nicht alle
PIM-Programme von Akonadi gebrauch machen, da es einfach an den
Entwickler-Ressourcen fehlt.

</p>
**kubuntu-de.org:** Also wird KDE4-PIM von Anfang an auf Akonadi
aufsetzen?

</p>
**Tobias König:** Ja, aber wir haben da auch einen Migrationspfad
geplant, womit man das alte Ressource-Framework in Akonadi integrieren
bzw. über das alte Ressource-Interface auf Akonadi zugreifen kann.

</p>
**kubuntu-de.org:** Wie kann man sich in die Entwicklung einbringen?

</p>
**Tobias König:** Einfach die KDE-PIM-Entwickler auf <kde-pim@kde.org>
oder auf \#kontact kontaktieren und fragen wo man helfen kann. Gerade
das Portieren einiger Ressourcen auf die Akonadi API sollte ein guter
Einstieg in die Akonadi-Welt sein.

</p>
**kubuntu-de.org:** Die Entwicklung von Akonadi war ja länger etwas ...
mmmh... langsam verlaufen. Was habt ihr für die nächste Zeit geplant um
den Rückstand einzuholen?

</p>
**Tobias König:** Der etwas langsame Entwicklungsverlauf ist
hauptsächlich dem Mangel an Entwicklern geschuldet. Im Moment wird die
Hauptentwicklungsarbeit von 3-4 Leuten betrieben (wobei ich das
Engagement von Volker Krause hervorheben möchte, ohne ihn wäre das
Projekt sicher schon eingeschlafen!), wobei zwei Vollzeit arbeiten und
die anderen beiden Studieren bzw. an ihrem Diplom arbeiten... da bleiben
nur die Abendstunden oder Entwicklertreffen zum Hacken. Apropos
Entwicklertreffen: Über das Osterwochenende wird es ein
Akonadi-Hacking-Meeting im KDAB Office in Berlin geben. Dort werden wir
dann die API nochmals überarbeiten und überprüfen. Im April findet ja
der API-Freeze statt. Hoffentlich kommen wir auch noch dazu einige
fehlende Features zu implementieren (vielleicht verstecken wir auch ein
paar Easter-Eggs ;))

</p>
**kubuntu-de.org:** Das hört sich alles sehr spannend und innovativ an.
Was uns als Kubuntu-Nutzer besonders interessiert: Welche Distribution
nutzt du?

</p>
**Tobias König:** Debian Unstable ;). Das hat aber historische Gründe.
Zu der Zeit, wo ich mein System aufgesetzt habe gab es noch kein Ubuntu.
Und seit dem sah ich keinen Grund für eine Neuinstallation :)

</p>
**kubuntu-de.org:** Nutzt du KDE 4 eigentlich schon für deine tägliche
Arbeit? Und wenn ja wie zufrieden bist du zurzeit damit?

</p>
**Tobias König:** Ja, ich verwende KDE 4 schon seit ca. 3 Monaten. Am
Anfang war es nicht so schön, dass jeden zweiten Tag der Plasma Desktop
nicht funktionierte, aber inzwischen ist es stabil und man kann durchaus
damit arbeiten.

</p>
Allerdings sollte man damit leben können, dass hier und da noch nicht
alles reibungsfrei läuft. Gerade in der aktuellsten Version (mit Qt 4.4
Beta) gibt es noch einige Ungereimtheiten, was das Fenstermanagement
anbelangt. Dem Otto-Normalbenutzer würde ich aber empfehlen weiterhin
3.5 zu verwenden und frühestens mit 4.1 umzusteigen.

</p>
**kubuntu-de.org:** Hast du noch etwas, was du der Welt mitteilen
möchtest?

</p>
**Tobias König:** Akonadi rocks! :)

</p>
**kubuntu-de.org:** Dann danken wir für diesen Einblick in die
Entwicklung von Akonadi und freuen uns auf die Innovationen! Vielen Dank
für das Interview.

</p>
**Tobias König:** Bitte sehr, gern geschehen :)

</p>

