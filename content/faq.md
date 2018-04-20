Title: FAQ
Date: 2007-01-19 06:03
Author: Monika Eggers
Slug: faq

FAQ {#faq align="left"}
===


<div align="left">


-   [Was ist Kubuntu?](#wasistkubuntu)
-   [Ist es ein Fork von Ubuntu?](#fork)
-   [Ich habe schon Ubuntu installiert, wie kann ich nun Kubuntu
    bekommen?](#vonubuntu)
-   [Sind Kubuntu CDs bei Shipit erhältlich?](#shipit)
-   [Wieso ist der Konqueror so langsam?](#ipv6)
-   [Wie kann ich mp3s abspielen?](#mp3s)
-   [Wie ist das root Passwort?](#root)
-   [Wie stelle ich die normalen KDE Profile im Konqueror wieder
    her?](#konqueror)
-   [Wie kann ich die Systemordner wieder sichtbar machen?](#rootordner)
-   [Darf ich Kubuntu CDs oder Computer mit vorinstalliertem Kubuntu
    verkaufen?](#verkauf)
-   [Was bedeutet Kubuntu?](#kubuntubedeutung)
-   [Wo kann ich Hilfe bekommen?](#hilfebekommen)
-   [Wo kann ich ein Problem melden?](#problem)
-   [Wie kann ich helfen?](#hilfe)




</div>


###  Was ist Kubuntu? {#was-ist-kubuntu align="left"}


<div align="left">

Kubuntu ist die erste von Ubuntu abgeleitete Distribution. Die Kubuntu
CDs werden aus der Ubuntu Basis mit KDE erstellt. Der gleiche Effekt
kann dadurch erreicht werden, indem Ubuntu installiert und danach die
KDE Pakete aus den Ubuntu Archiven hinzugefügt (und die Gnome Pakete
entfernt) werden.

</div>


###  Ist es ein Fork von Ubuntu? {#ist-es-ein-fork-von-ubuntu align="left"}


<div align="left">

Nein, Kubuntu ist ein offizieller Teil von Ubuntu. Alle Pakete sind in
den selben Archiven.

</div>


###  Ich habe schon Ubuntu installiert, wie kann ich Kubuntu bekommen? {#ich-habe-schon-ubuntu-installiert-wie-kann-ich-kubuntu-bekommen align="left"}


<div align="left">

</div>


Einfach "*kubuntu-desktop"* mit adept oder auf der Kommandozeile
installieren. 


<div align="left">


> *sudo apt-get install kubuntu-desktop*




</div>


[InstallingKDE](http://wiki.kubuntu.org/InstallingKDE "InstallingKDE")
(englisch) bietet einen vollständige Erklärung.


<div align="left">

</div>


###  Sind Kubuntu CDs bei ShipIt erhältlich? {#sind-kubuntu-cds-bei-shipit-erhältlich align="left"}


<div align="left">

</div>


Kubuntu CDs sind seit Dapper für PC und 64bit PCs bei
[ShipIt](https://shipit.kubuntu.org "ShipIt") verfügbar. Leider gibt es
keine Edgy CDs. Weitere Informationen beinhaltet die [Ubuntu ShipIt
FAQ](http://www.ubuntu.com/support/faq#head-7eef2db63e0a75424cdd663ee6f7b8eedcf19607 "Ubuntu ShipIt FAQ")
(englisch).


<div align="left">

</div>


 


<div align="left">

</div>


### Warum ist der Konqueror so langsam? {#warum-ist-der-konqueror-so-langsam align="left"}


<div align="left">

</div>


Das Ausstellen der IPv6 Unterstützung sollte den KDE Browser ein ganzes
Stück schneller machen. Hierzu einfach in der Konsole eingeben:


<div align="left">


> 
> *echo "KDE\_NO\_IPV6=TRUE" &gt;&gt; /etc/environment*
>
> 
> 





</div>


###  Wie kann ich mp3s abspielen? {#wie-kann-ich-mp3s-abspielen align="left"}


<div align="left">

</div>


Es ist notwendig das Paket *"libxine-extracodecs"* aus dem multiverse
Repository zu installieren.


<div align="left">


> *sudo apt-get install libxine-extracodecs*


Unter Edgy ist es möglich mit Amarok beim erstmaligen Abspielen einer
mp3 die entsprechenden Codecs zu installieren. 

</div>


Für JuK müssen zusätzlich "*libarts1-mpeglib"* und "*libakode2-mpeg"
installiert werden*.


<div align="left">


> *sudo apt-get install  libarts-1mpeglib und libakode2-mpeg *
> 
> 




</div>


mp3 Support für k3b kann man mit "*libk3b2-mp3*" nachrüsten.


<div align="left">


> *sudo apt-get install libk3b2-mp3*
> 
> 




</div>


[RestrictedFormats](http://wiki.kubuntu.org/RestrictedFormats "RestrictedFormats")
(englisch) erklärt, wieso die mp3 Funktionalität nicht von Anfang an zur
Verfügung steht.


<div align="left">

</div>


###  Wie ist das root Passwort? {#wie-ist-das-root-passwort align="left"}


<div align="left">

Es gibt standardmäßig kein root Passwort. Falls KDE
Administratorenrechte braucht, kann das Passwort des Users genutzt
werden, der bei der Installation angelegt wurde. Man kann auch Dateien
als root im Konqueror editieren: mit einem Rechtsclick *"-&gt; Aktionen
-&gt;  Als root bearbeiten*". Für weitere Informationen ist die [Root
Sudo](http://www.ubuntulinux.org/wiki/RootSudo "Root Sudo") Wiki Seite
empfehlenswert.

</div>


###  Wie stelle ich die normalen KDE Profile im Konqueror wieder her? {#wie-stelle-ich-die-normalen-kde-profile-im-konqueror-wieder-her align="left"}


<div align="left">

</div>


Kubuntu Dapper und Edgy haben ein vereinfachtes Konqueror Profil, um das
Arbeiten im Gegensatz zum original KDE nutzerfreundlicher zu machen. Um
die Standardprofile von KDE wiederherzustellen, muss man folgende
Befehle ausführen:


<div align="left">


> *sudo rm -r
> /usr/share/kubuntu-default-settings/kde-profile/default/share/apps/konqueror*
>  
> 
> 


> *sudo cp /usr/share/apps/konqueror/konqueror-orig.rc
> /usr/share/apps/konqueror/konqueror.rc*




</div>


Damit Konqueror tar und zip files öffnet:<em>  

</em>


<div align="left">


> *sudo rm -r
> /usr/share/kubuntu-default-settings/kde-profile/default/share/mimelnk/application/*




</div>


###  Wie kann ich die Systemordner wieder sichtbar machen? {#wie-kann-ich-die-systemordner-wieder-sichtbar-machen align="left"}


<div align="left">

Normalerweise sind die Ordner, die nicht dem Nutzer gehören in Edgy
versteckt. Um sie im Konqueror anzeigen zulassen muss man *"Ansicht
-&gt; Versteckte  Dateien anzeigen* auswählen". Um sie gar nicht mehr zu
verstecken muss man *"/etc/kubuntu-default-settings"* editieren und die
Datei leeren.  Die Order werden in Feisty nicht mehr versteckt sein. 

</div>


###  Darf ich Kubuntu CDs oder Computer mit vorinstalliertem Kubuntu verkaufen? {#darf-ich-kubuntu-cds-oder-computer-mit-vorinstalliertem-kubuntu-verkaufen align="left"}


<div align="left">

Ja, denn Kubuntu ist freie Software, deswegen können sie CDs oder mit
Kubuntu vorinstallierte Computer verkaufen. Allerdings muss der
Quelltext genauso kostenfrei zur Verfügung gestellt werden, falls der
Kunde danach fragen sollte. Source ISOs sind für Dapper
[hier](http://cdimage.ubuntu.com/kubuntu/releases/dapper/release/source/ "Dapper Source")
und für Edgy
[hier](http://cdimage.ubuntu.com/kubuntu/releases/edgy/release/source/ "Edgy Source")
erhältlich  Falls für Name oder Werbung des Produktes das Wort Kubuntu
oder das Kubuntu Logo genutzt wird, muss eine
[Produktlizenz](http://www.ubuntu.com/ubuntu/TrademarkPolicy/ "Produktlizenz")
von Canonical erworben werden, die in der Regel ohne Kosten erhältlich
ist.



</div>


###  Was bedeutet Kubuntu? {#was-bedeutet-kubuntu align="left"}


<div align="left">

Kubuntu bedeutet *"zur Menschlichkeit"* in der Sprache
[Bemba](http://de.wikipedia.org/wiki/Bemba_(Sprache) "Bemba"). 
Gleichzeitig bedeutet es auch *"frei"* in
[Kirundi](http://de.wikipedia.org/wiki/Kirundi "Kirundi"), was in
Burundi gesprochen wird. Kubuntu wird "koo-**boon**-too" ausgesprochen.



</div>


###  Wo kann ich Hilfe bekommen? {#wo-kann-ich-hilfe-bekommen align="left"}


<div align="left">

Kubuntu-de.org bietet eine Vielzahl an Supportmöglichkeiten, Fragen kann
man an die
[Mailingliste](https://lists.ubuntu.com/mailman/listinfo/kubuntu-de "Mailingliste"),
im IRC Kanal \#kubuntu-de auf irc.freenode.org und im
[Forum](/forum "Forum") stellen. Englischsprachige Supportmöglichkeiten
sind auf der Kubuntu [Support](http://kubuntu.org/support.php "Support")
Seite (englisch) zu finden.



</div>


###  Wo kann ich ein Problem melden? {#wo-kann-ich-ein-problem-melden align="left"}


<div align="left">

Zuerst sollte man die
[KnownProblems](https://wiki.kubuntu.org/KubuntuDapperKnownProblems "KnownProblems")
Seite überprüfen und falls es sich um ein neues Problem handelt es im
Lanchpad [Malone](http://launchpad.net/malone "Malone") melden.



</div>


###  Wie kann ich helfen? {#wie-kann-ich-helfen align="left"}


<div align="left">

Die
[HelpingKubuntu](https://wiki.kubuntu.org/HelpingKubuntu "Helping Kubuntu")
Seite (englisch) enthält einige Hinweise. Selbstverständlich kann man
sich auch jederzeit an das Kubuntu-de.org
[Team](/portal/contact "Kontakt") wenden.

</div>



