Title: KDE4 und Kubuntu
Date: 2007-03-21 15:32
Author: Monika Eggers
Tags: KDE
Slug: kde4-und-kubuntu

Die viel diskutierte vierte Version des K Desktop Environment beginnt
langsam Formen anzunehmen. KDE4 wird komplett auf qt4 aufsetzen, was
bedeutet, dass alle unter KDE3.x laufenden Anwendungen an QT4 angepasst
werden müssen. Viele Anwender erhofften sich die Veröffentlichung
bereits letztes Jahr, wurden aber enttäuscht, denn der Aufwand dafür
scheint doch größer, als erwartet. Obwohl Spötter KDE 4 schon als
"Vaporware" bezeichnen, scheint eine Veröffentlichung in diesem Jahr
jedoch immer wahrscheinlicher. Nachdem bereits drei Snapshots für
Entwickler veröffentlicht worden sind, präsentierte das Release Team von
KDE jetzt einen
[Zeitplan](http://techbase.kde.org/Schedules/KDE4/4.0_Release_Roadmap)
bis zum Erscheinungstermin des ersten stabilen Version im Oktober.

</p>
<!--break--><!--break-->

Wie aus dem Releaseplan hervorgeht wird die Version 4.0 noch nicht alle
geplanten Funktionen besitzen. Man verspricht sich von der
Veröffentlichug dieser "Basisversion" aber eine Beschleunigung der
Arbeit an den fehlenden Verbesserungen, die dann in die Version 4.1
einfließen sollen. Mit dem Festschreiben der, in den KDE-Bibliotheken
(kdelibs) enthaltenen Subsysteme wäre am 1.April ein "Meilenstein"
erreicht. Damit wären die Bibliotheken frei von KDE3-Code und die
Build-Umgebung festgelegt. Am 1. Mai soll dann das auf QT 4.3 aufbauende
API eingefroren werden und eine Alpha version von KDE 4.0 erscheinen.
Bis dahin soll auch festgelegt werden welche Hauptmodule in der Version
erscheinen und welche von KDE 4.0 abgetrennt werden. Danach sollen
monatlich Betaversionen zur Fehlerkorrekturen erscheinen. Im Oktober
könnte dann KDE 4.0 tatsächlich veröffentlicht werden.

</p>
kubuntu-de.org hat Jonathan Riddell, den Chefentwickler von Kubuntu zum
Thema KDE4.0 und die Auswirkungen auf Kubuntu befragt:

</p>
 

</p>
 

</p>
</p>
<table>
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
<td>
</p>
**Redaktion**: Jonathan, viele Kubuntu-Nutzer warten begierig auf KDE 4,
kannst du uns einen Blick hinter die Kulissen geben, oder lässt dir die
Arbeit an Kubuntu keine Zeit für KDE 4?

</p>
Jonathan Riddell: Beim letzten Ubuntu Entwickler-Gipfeltreffen habe wir
uns mit dem Thema KDE4 beschäftigt und die Einführung in die Archive
geplant. Die Pakete kde4libs und kde4base sind schon eingefügt, der Rest
ist in einer Warteschleife bis ein Administrator sie genehmigt. Einige
der Pakete sind aufgrund von Lizenproblemen schon abgelehnt worden
(nichts weltbewegendes, einfach nur eine fehlende Datei). Deshalb ist es
gut, dass wir schon so früh damit beginnen, damit solche Probleme gleich
beseitigt werden können. Diese neuen Pakete können parallel mit dem
gegenwärtigen KDE 3 installiert werden und innerhalb KDE 3 oder in einer
eigenen Sitzung benutzt werden. Allerdings sind die neuen Pakete noch
sehr instabil und daher noch nicht für den täglichen Gebrauch geeignet.
Außerdem wurden noch keine Abhängigkeiten definiert, weshalb sie manuell
installiert werden müssen.

</p>
-   [Feisty KDE4 Plan](https://wiki.kubuntu.org/KubuntuFeistyKde4Plan)
    (englisch)
    </p>
    <p>
-   [Warteschleife](https://launchpad.net/ubuntu/feisty/+queue)
    (englisch)
-   [KDE4 neben KDE3](http://kubuntu.org/announcements/kde4-3.80.3.php)
    (englisch)

</p>
<p>
</td>
</p>
<p>
<td valign="top" bgcolor="#e1ebff">
![](http://www.kubuntu-de.org/files/riddell.jpg){width="130"
height="178"}**Jonathan Riddell**:  

</p>
Der 25 jährige Schotte Jonathan Riddell ist Kubuntu Chefentwickler und
bei Canonical angestellt. Er kennt Kubuntu wie niemand sonst, bei ihm
laufen die Fäden zusammen. Er koordiniert, programmiert, stellt eigene
Pakete zur Verfügung und weiß auf fast jede Frage zu Kubuntu eine
Antwort. Darüberhinaus arbeitet er bei KDE mit. In seiner Freizeit fährt
er gerne Kanu oder besucht Quäker Versammlungen.

-   Riddell bei 
    [BehindUbuntu](http://www.behindubuntu.org/interviews/JonathanRiddell/)
    (englisch)

</p>
<p>
</td>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
<table>
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
<td>
</p>
 

</p>
**Redaktion**: Für Kubuntu 6.10 gibt es KDE 4-Entwicklerpakete, wird es
bald auch eine Testversion für normale Anwender geben?

</p>
Jonathan Riddell: Unser gegenwärtiges Hauptanliegen ist die Erstellung
und Bereitstellung von Werkzeugen für die Entwickler. Wir wollen das
neueste CMake (das neue Software-Paketerstellungssystem für KDE 4) in
Feisty und den Backports zur Verfügung stellen. Wir haben auch die
neuesten Strigi und Decibel Bibliotheken die für KDE 4 gebraucht werden.
Die Anwender sind eingeladen diese Pakete auszuprobieren, aber ich kann
es nicht empfehlen sie wirklich zu benutzen, außer um Fehler zu finden
und damit zu beginnen sie zu bereinigen.

</p>
</td>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
<table>
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
<td>
</p>
</p>
**Redaktion**: Unlängst gab es Berichte in der Presse, die für die
Veröffentlichung eines Release-Fahrplans waren. Was schätzt du, wann
wird KDE4 veröffentlicht?

</p>
Jonathan Riddell: Vor einiger Zeit habe ich gehofft es für letzten
Oktober zu schaffen. Das war KDEs 10. Geburtstag. Offensichtlich lag ich
damit ziemlich daneben. Vielleicht sollte ich jetzt eine Schätzung um
den 11. Geburtstag herum abgeben :) Selbst nachdem KDE 4 freigegeben
wurde, werden für eine Weile immer noch KDE 3 Anwendungen im Umlauf
sein, da es eine ziemlich lange Zeit dauern wird bis die Portierungen
für alle Anwendungen abgeschlossen sein werden. Wir haben schon damit
begonnen Kubuntu mit Ubiquity und anderen Anwendungen die schon jetzt Qt
4 benutzen, für KDE 4 umzusetzen. Andererseits sind einige Anwendungen
wie Adept und Guidance KDE-funktionalitätsabhängig, sodass es nicht
möglich ist die Portierung zu beginnen bis KDE 4 stabiler geworden ist.

</p>
</td>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
<table>
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
<td>
</p>
**Redaktion**: Wenn KDE 4 veröffentlicht ist, welche Kubuntu Version
wird es beinhalten, 7.10 oder eher 8.04?

</p>
Jonathan Riddell: Ich vermute, dass KDE 4 nicht stabil genug sein wird,
um als Standardbenutzeroberfläche für 7.10 fungieren zu können. Für 8.04
sollte es fertig sein, aber es ist möglich, dass 8.04 unsere nächste
LTS-Version sein wird. Wir wollen auf keinen Fall, dass unsere erste KDE
4-Version auch eine LTS-Version ist. Auf jeden Fall werden wir Pakete
und ISO-Dateien zur Verfügung stellen, damit sie jeder austesten kann,
sobald es irgendwie möglich sein wird dies zu tun ohne den Verstand zu
verlieren.

</p>
<table>
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
<p>
</td>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
<table width="980" height="24">
</p>
<p>
<tbody>
</p>
<p>
<tr>
</p>
<p>
<td>
**Redaktion**: Wir bedanken uns für das Interview.

</p>
<p>
</td>
</p>
<p>
</tr>
</p>
<p>
</tbody>
</p>
<p>
</table>
</p>
Diese Nachricht kann
[hier](http://forum.kubuntu-de.org/index.php?topic=8045.0) im Forum
diskutiert werden und hier geht es zum
[Originaltext](http://www.kubuntu-de.org/interview-mit-riddell-zu-kde4-englisch)
des Interviews (englisch).

</p>

