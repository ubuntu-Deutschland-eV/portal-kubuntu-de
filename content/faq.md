Title: FAQ
Date: 2007-01-19 06:03
Author: Monika Eggers
Slug: faq

FAQ {#faq align="left"}
===

</p>
<div align="left">

</p>
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
    verkaufen?](#verkauf)[]{#Darf ich Kubuntu verkaufen?}
-   [Was bedeutet Kubuntu?](#kubuntubedeutung)
-   [Wo kann ich Hilfe bekommen?](#hilfebekommen)
-   [Wo kann ich ein Problem melden?](#problem)
-   [Wie kann ich helfen?](#hilfe)

</p>
<p>

</div>

</p>
### []{#wasistkubuntu} Was ist Kubuntu? {#was-ist-kubuntu align="left"}

</p>
<div align="left">

Kubuntu ist die erste von Ubuntu abgeleitete Distribution. Die Kubuntu
CDs werden aus der Ubuntu Basis mit KDE erstellt. Der gleiche Effekt
kann dadurch erreicht werden, indem Ubuntu installiert und danach die
KDE Pakete aus den Ubuntu Archiven hinzugefügt (und die Gnome Pakete
entfernt) werden.

</div>

</p>
### []{#fork} Ist es ein Fork von Ubuntu? {#ist-es-ein-fork-von-ubuntu align="left"}

</p>
<div align="left">

Nein, Kubuntu ist ein offizieller Teil von Ubuntu. Alle Pakete sind in
den selben Archiven.

</div>

</p>
### []{#vonubuntu} Ich habe schon Ubuntu installiert, wie kann ich Kubuntu bekommen? {#ich-habe-schon-ubuntu-installiert-wie-kann-ich-kubuntu-bekommen align="left"}

</p>
<div align="left">

</div>

</p>
Einfach "*kubuntu-desktop"* mit adept oder auf der Kommandozeile
installieren. 

</p>
<div align="left">

</p>
> *sudo apt-get install kubuntu-desktop*

</p>
<p>

</div>

</p>
[InstallingKDE](http://wiki.kubuntu.org/InstallingKDE "InstallingKDE")
(englisch) bietet einen vollständige Erklärung.

</p>
<div align="left">

</div>

</p>
### []{#shipit} Sind Kubuntu CDs bei ShipIt erhältlich? {#sind-kubuntu-cds-bei-shipit-erhältlich align="left"}

</p>
<div align="left">

</div>

</p>
Kubuntu CDs sind seit Dapper für PC und 64bit PCs bei
[ShipIt](https://shipit.kubuntu.org "ShipIt") verfügbar. Leider gibt es
keine Edgy CDs. Weitere Informationen beinhaltet die [Ubuntu ShipIt
FAQ](http://www.ubuntu.com/support/faq#head-7eef2db63e0a75424cdd663ee6f7b8eedcf19607 "Ubuntu ShipIt FAQ")
(englisch).

</p>
<div align="left">

</div>

</p>
 

</p>
<div align="left">

</div>

</p>
### []{#ipv6}Warum ist der Konqueror so langsam? {#warum-ist-der-konqueror-so-langsam align="left"}

</p>
<div align="left">

</div>

</p>
Das Ausstellen der IPv6 Unterstützung sollte den KDE Browser ein ganzes
Stück schneller machen. Hierzu einfach in der Konsole eingeben:

</p>
<div align="left">

</p>
> </p>
> *echo "KDE\_NO\_IPV6=TRUE" &gt;&gt; /etc/environment*
>
> </p>
> <p>

</p>
</p>
<p>

</div>

</p>
### []{#mp3s} Wie kann ich mp3s abspielen? {#wie-kann-ich-mp3s-abspielen align="left"}

</p>
<div align="left">

</div>

</p>
Es ist notwendig das Paket *"libxine-extracodecs"* aus dem multiverse
Repository zu installieren.

</p>
<div align="left">

</p>
> *sudo apt-get install libxine-extracodecs*

</p>
Unter Edgy ist es möglich mit Amarok beim erstmaligen Abspielen einer
mp3 die entsprechenden Codecs zu installieren. 

</div>

</p>
Für JuK müssen zusätzlich "*libarts1-mpeglib"* und "*libakode2-mpeg"
installiert werden*.

</p>
<div align="left">

</p>
> *sudo apt-get install  libarts-1mpeglib und libakode2-mpeg *
> </p>
> <p>

</p>
<p>

</div>

</p>
mp3 Support für k3b kann man mit "*libk3b2-mp3*" nachrüsten.

</p>
<div align="left">

</p>
> *sudo apt-get install libk3b2-mp3*
> </p>
> <p>

</p>
<p>

</div>

</p>
[RestrictedFormats](http://wiki.kubuntu.org/RestrictedFormats "RestrictedFormats")
(englisch) erklärt, wieso die mp3 Funktionalität nicht von Anfang an zur
Verfügung steht.

</p>
<div align="left">

</div>

</p>
### []{#root} Wie ist das root Passwort? {#wie-ist-das-root-passwort align="left"}

</p>
<div align="left">

Es gibt standardmäßig kein root Passwort. Falls KDE
Administratorenrechte braucht, kann das Passwort des Users genutzt
werden, der bei der Installation angelegt wurde. Man kann auch Dateien
als root im Konqueror editieren: mit einem Rechtsclick *"-&gt; Aktionen
-&gt;  Als root bearbeiten*". Für weitere Informationen ist die [Root
Sudo](http://www.ubuntulinux.org/wiki/RootSudo "Root Sudo") Wiki Seite
empfehlenswert.

</div>

</p>
### []{#konqueror} Wie stelle ich die normalen KDE Profile im Konqueror wieder her? {#wie-stelle-ich-die-normalen-kde-profile-im-konqueror-wieder-her align="left"}

</p>
<div align="left">

</div>

</p>
Kubuntu Dapper und Edgy haben ein vereinfachtes Konqueror Profil, um das
Arbeiten im Gegensatz zum original KDE nutzerfreundlicher zu machen. Um
die Standardprofile von KDE wiederherzustellen, muss man folgende
Befehle ausführen:

</p>
<div align="left">

</p>
> *sudo rm -r
> /usr/share/kubuntu-default-settings/kde-profile/default/share/apps/konqueror*
>  
> </p>
> <p>

</p>
> *sudo cp /usr/share/apps/konqueror/konqueror-orig.rc
> /usr/share/apps/konqueror/konqueror.rc*

</p>
<p>

</div>

</p>
Damit Konqueror tar und zip files öffnet:<em>  

</em>

</p>
<div align="left">

</p>
> *sudo rm -r
> /usr/share/kubuntu-default-settings/kde-profile/default/share/mimelnk/application/*

</p>
<p>

</div>

</p>
### []{#rootordner} Wie kann ich die Systemordner wieder sichtbar machen? {#wie-kann-ich-die-systemordner-wieder-sichtbar-machen align="left"}

</p>
<div align="left">

Normalerweise sind die Ordner, die nicht dem Nutzer gehören in Edgy
versteckt. Um sie im Konqueror anzeigen zulassen muss man *"Ansicht
-&gt; Versteckte  Dateien anzeigen* auswählen". Um sie gar nicht mehr zu
verstecken muss man *"/etc/kubuntu-default-settings"* editieren und die
Datei leeren.  Die Order werden in Feisty nicht mehr versteckt sein. 

</div>

</p>
### []{#verkauf} Darf ich Kubuntu CDs oder Computer mit vorinstalliertem Kubuntu verkaufen? {#darf-ich-kubuntu-cds-oder-computer-mit-vorinstalliertem-kubuntu-verkaufen align="left"}

</p>
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
</p>
<p>

</div>

</p>
### []{#kubuntubedeutung} Was bedeutet Kubuntu? {#was-bedeutet-kubuntu align="left"}

</p>
<div align="left">

Kubuntu bedeutet *"zur Menschlichkeit"* in der Sprache
[Bemba](http://de.wikipedia.org/wiki/Bemba_(Sprache) "Bemba"). 
Gleichzeitig bedeutet es auch *"frei"* in
[Kirundi](http://de.wikipedia.org/wiki/Kirundi "Kirundi"), was in
Burundi gesprochen wird. Kubuntu wird "koo-**boon**-too" ausgesprochen.
</p>
<p>

</div>

</p>
### []{#hilfebekommen} Wo kann ich Hilfe bekommen? {#wo-kann-ich-hilfe-bekommen align="left"}

</p>
<div align="left">

Kubuntu-de.org bietet eine Vielzahl an Supportmöglichkeiten, Fragen kann
man an die
[Mailingliste](https://lists.ubuntu.com/mailman/listinfo/kubuntu-de "Mailingliste"),
im IRC Kanal \#kubuntu-de auf irc.freenode.org und im
[Forum](/forum "Forum") stellen. Englischsprachige Supportmöglichkeiten
sind auf der Kubuntu [Support](http://kubuntu.org/support.php "Support")
Seite (englisch) zu finden.
</p>
<p>

</div>

</p>
### []{#problem} Wo kann ich ein Problem melden? {#wo-kann-ich-ein-problem-melden align="left"}

</p>
<div align="left">

Zuerst sollte man die
[KnownProblems](https://wiki.kubuntu.org/KubuntuDapperKnownProblems "KnownProblems")
Seite überprüfen und falls es sich um ein neues Problem handelt es im
Lanchpad [Malone](http://launchpad.net/malone "Malone") melden.
</p>
<p>

</div>

</p>
### []{#hilfe} Wie kann ich helfen? {#wie-kann-ich-helfen align="left"}

</p>
<div align="left">

Die
[HelpingKubuntu](https://wiki.kubuntu.org/HelpingKubuntu "Helping Kubuntu")
Seite (englisch) enthält einige Hinweise. Selbstverständlich kann man
sich auch jederzeit an das Kubuntu-de.org
[Team](/portal/contact "Kontakt") wenden.

</div>

</p>

